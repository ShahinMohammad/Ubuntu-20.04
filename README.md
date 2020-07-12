# How to see phpmyadmin pass and login

shahin@Mac:~$ cd /etc/phpmyadmin/
shahin@Mac:/etc/phpmyadmin$ ls
apache.conf    config.footer.inc.php  lighttpd.conf
conf.d         config.header.inc.php  phpmyadmin.desktop
config-db.php  config.inc.php         phpmyadmin.service
shahin@Mac:/etc/phpmyadmin$ cat config-db.php
<?php
##
## database access settings in php format
## automatically generated from /etc/dbconfig-common/phpmyadmin.conf
## by /usr/sbin/dbconfig-generate-include
##
## by default this file is managed via ucf, so you shouldn't have to
## worry about manual changes being silently discarded.  *however*,
## you'll probably also want to edit the configuration file mentioned
## above too.
##
$dbuser='phpmyadmin';
$dbpass='s098';
$basepath='';
$dbname='phpmyadmin';
$dbserver='localhost';
$dbport='3306';
$dbtype='mysql';
