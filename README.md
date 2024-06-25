To test: 
- make sure the proper tables/database is in sql
FOR SQL 

create database pythonProject;
use pythonProject;

create table users 
(
	ID int Primary key auto_increment,
	email varchar(30),
	username varchar(20) NOT NULL unique,
	password varchar(20) NOT NULL
);

create table hall1
(
	SeatID int primary key,
    	ID int,
    	voucher boolean
);

create table hall2
(
	SeatID int primary key,
    	ID int,
    	voucher boolean
);

create table hall3
(
	SeatID int primary key,
    	ID int,
    	voucher boolean
);

create table hall4
(
	SeatID int primary key,
    	ID int,
    	voucher boolean
);

- add/change the password in py code
- change the asset path 
