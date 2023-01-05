# MariaDB

Collection of compose file for a quick-setup mariadb environment.

By default :

> `user: root`  
> no password


Case sensitivity : lower_case_table_names set to 1, names are stored in lowercase and not compared in a case-sensitive
manner.  
It is the default on Windows system but on UNIX-Based (Linux or MacOS, ...) names are store the same way they are write
and the names use in queries are case-sensitive.  
Doc : https://mariadb.com/kb/en/server-system-variables/#lower_case_table_names

## mariadb-10.yml

Stack with only MariaDB v10.

## mariadb-10-with-phpmyadmin.yml

Stack with MariaDB v10 and phpmyadmin.
