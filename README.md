CI-AdminLTE v1.4.3
====================

## Setup
### Start mariadb
```
$ cd /path/to/CI-AdminLTE
$ docker-compose up
```

### Update database

```
$ cd /path/to/CI-AdminLTE/install/sql
$ mysql -h 127.0.0.1 -P 3306 -u username -p
Enter password: password

mysql> use ci_adminlte;
mysql> source ci_adminlte.sql
mysql> source ci_adminlte_update.sql
```

## Run

Note: work only with php 5.6 but php 7.1 have issues, not remember session.

```
php -t ./ -S 0.0.0.0:8088
```

 * http://127.0.0.1:8088/

### Login
 * Email : `admin@admin.com`
 * Password : `password`

## Browser Compatibility
Support for most major browsers including Chrome, Firefox, IE9+, Opera and Safari.

## Languages
  * English
  * French
  * Portuguese (translation by [marcelod](https://github.com/marcelod))
  * ... and more soon
 
## Dependencies
| NAME | VERSION | WEB | REPO |
| :--- | :---: | :---: | :---: |
| CodeIgniter | 3.1.0 | [Website](http://codeigniter.com) | [Github](https://github.com/bcit-ci/CodeIgniter/)
| AdminLTE | 2.3.5 | [Website](https://almsaeedstudio.com) | [Github](https://github.com/almasaeed2010/AdminLTE/)
| Bootstrap | 3.3.7 | [Website](http://getbootstrap.com) | [Github](https://github.com/twbs/bootstrap)
| Ion Auth | 2.6.0 | [Website](http://benedmunds.com/ion_auth) | [Github](https://github.com/benedmunds/CodeIgniter-Ion-Auth)
| jQuery | 2.2.4 | [Website](http://jquery.com) | [Github](https://github.com/jquery/jquery)
| Font Awesome | 4.6.3 | [Website](http://fortawesome.github.io/Font-Awesome/) | [Github](https://github.com/FortAwesome/Font-Awesome)
