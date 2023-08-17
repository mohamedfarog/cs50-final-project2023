
# CS50 COURSE REGISTRATION

## CS50 2023
>This is my final project for CS50 Introduction to Computer Sciense course
##Features

- [Flask-MySQLdb](https://pypi.org/project/Flask-MySQLdb/)
- [Flask](https://flask.palletsprojects.com/en/1.1.x/)


I used Flask framework based with Python
its was necessary Flask-MySQLdb for manage relational mysql database

# Project title
- CS50 Final Project URL: https://www.youtube.com/watch?v=slmdEhiBEn0

# Description

## Explaining the project and the database
- CS50 Final Project is a web-based application using JavaScript, Python, Flask and SQL
- on which a user can register a new account, login, view details, view home, update details, and logout.
- the register page, a user is able to enter his or her information, including user name, email, and password.
- then press register, which sends a post-reguest to save your date in date base.
- the login page, a user uses the details that were provided earlier during registration (username, password) to login ino system.
- the home page, a Logged in successfully message is displayed with a header that says Welcome!! CS50 Home Page.
- In the side bar, there are 4 buttons: home, user details, update info, and logout, so the user could switch through those pages.
- the user details page, all the user's details are shown.
- On the update page, a user is able to update information, for example, a password or email.
- If the logout button is clicked, the system will logout, and the user must provide login details again to login into the system.
- This project satisfies all the web application rules, including ( CURD ) POST, GET, UPDATE.
- It uses user authentication and verification at both the front-end and back-end levels.

### flask_mysqldb 
I created one table for user "account" which holds the following info which used to register, login, view and update user info
 phpMyAdmin SQL Dump
 version 5.1.1deb5ubuntu1
 https://www.phpmyadmin.net/
 
 Host: localhost:3306
 Generation Time: Aug 17, 2023 at 11:54 AM
 Server version: 8.0.34-0ubuntu0.22.04.1
PHP Version: 8.1.2-1ubuntu2.13

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";

Database: `cs50_final_project`


Table structure for table `accounts`


CREATE TABLE `accounts` (
  `id` int NOT NULL,
  `username` varchar(50) NOT NULL,
  `password` varchar(250) NOT NULL,
  `email` varchar(100) NOT NULL,
  `organisation` varchar(100) NOT NULL,
  `address` varchar(100) NOT NULL,
  `city` varchar(250) NOT NULL,
  `state` varchar(100) NOT NULL,
  `country` varchar(100) NOT NULL,
  `postalcode` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb3;


# How to deploy and run..
- Create mysql database with the name cs50_final_project
- Import the attached file cs50_final_project.sql to your database
- Change the db connection params in app.py bassed on your db details
- Open the project with your preferred IDE
- Flask run
- Browse to http://127.0.0.1:5000 
- On login page switch to register page to create new account
- Use the account details (username and password) to login


# Project screens snapshots

![alt text](https://github.com/mohamedfarog/cs50-final-project2023/tree/main/sapshot/login.png?raw=true)
