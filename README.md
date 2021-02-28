# mysql
#----SET ENGINE AS MyISAM----

mysql> set @@default_storage_engine = 'MyISAM';
Query OK, 0 rows affected (0.00 sec)

#-----CREATE DATABASE-------

mysql> create database k1;
Query OK, 1 row affected (0.00 sec)

#------SHOW DATABASE--------

mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| k1                 |
| mysql              |
| performance_schema |
+--------------------+
4 rows in set (0.05 sec)

#---------USE DATABSE k1-------

mysql> use k1;
Database changed
mysql> create table employeesWithMyISAM (id int,name varchar(50),city varchar(50)) ENGINE = MyISAM;
Query OK, 0 rows affected (0.02 sec)

#-------CREATE TABLES ENGINE AS MyISAM-------

----table1------
mysql> create table data1(id int,name varchar(50))ENGINE=MyISAM;
Query OK, 0 rows affected (0.06 sec)

-----table2------
mysql> create table data2(id int,name varchar(50))ENGINE=MyISAM;
Query OK, 0 rows affected (0.06 sec)

-----table3------
mysql> create table data3(id int,name varchar(50))ENGINE=MyISAM;
Query OK, 0 rows affected (0.03 sec)

------table4-----
mysql> create table employeesWithMyISAM (id int,name varchar(50),city varchar(50)) ENGINE = MyISAM;
Query OK, 0 rows affected (0.02 sec)

-------table5-----
mysql> create table trainees (id int, name varchar(50),state varchar(50))ENGINE= MyISAM;
Query OK, 0 rows affected (0.05 sec)

#------INSERT DATA IN TABLES------
