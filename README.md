# Tourism-Management

This is my Training Project build on Eclipse IDE for Enterprise Java Developers. Version: 2019-09 R (4.13.0) Build id: 20190917-1200 with jdk 1.8

Maven Project based on maven-archtype-webapp 1.0

mySQL 5.7.

sql queries -

Main table and database -

create database tourism_project; use tourism_project;

create table tourism( id int not null auto_increment, name varchar(45) not null, from_location varchar(45) not null, to_location varchar(45) not null, no_of_days int not null, price double(7,2) not null, primary key (id) )ENGINE = InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET= latin1;

user login table -

use tourism_project; create table user_manage( username varchar(20) not null unique, password varchar(20) not null, primary key(username) ); insert into user_manage values("abc","abc123");

