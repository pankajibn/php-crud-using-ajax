# PHP PDO CRUD with ajax jQuery and Bootstrap

PHP MySQL CRUD Application using jQuery Ajax and Bootstrap

- git clone the repository

  Project setup
- Rename your project directory to "phpcrudajax"

  Create Database:

- create database name "playersdb"
- create table using given below sql statement

```sh
CREATE TABLE `players` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `pname` varchar(50) NOT NULL,
 `email` varchar(100) NOT NULL,
 `phone` varchar(15) NOT NULL,
 `photo` varchar(100) NOT NULL,
 `status` enum('1','0') NOT NULL DEFAULT '1',
 PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=utf8
```

### Run the Project

Run the localhost (Apache service)
point to the:

```sh
http://localhost/phpcrudajax

```
