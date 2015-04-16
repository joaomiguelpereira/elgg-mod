# Set Up the dev environment #

For easy development you can set up a apache2 with PHP in you onw macinhe, then change the code and see what happens. If it please you, you shoul commit the changes.

# My own dev. env. #

  * Ubuntu 9.10 with Apache2, PHP and Mysql (google for elgg installation tips)
  * Have the nidea-theme in some folder under version control and make a symbolic link from apache html folder to the folder under version control. For example, I have elgg installed in /srv/elgg/html and the source folder in ~/developlement/elgg and have a symb link in /srv/elgg/html/mod/nidea-theme to ~/developlement/elgg/mod/nidea-theme. This a a way you have to make changes, hit F5 and see changes. Better ways can exist...
  * The same strategy for languages/pt.php
