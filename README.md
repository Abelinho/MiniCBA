# Bank
A Bank management application for bank using Spring Boot

It offers many services as:  
-Account transaction: payment, transfer and withdrawal   
-Account information: list of transaction, creation date, discount

It uses a mySQL database and spring data to handles the persistence layer.

-use username=admin, pasword=admin to log in after calling localhost:8080 on your

web browser. On the first run, set 'spring.jpa.hibernate.ddl-auto=create' in the application.properties file


REQUIREMENTS
for building and running the application you need:

*JDK 1.8

*Maven 


RUNNING THIS PROJECT

1. Clone this project: https://github.com/Abelinho/MiniCBA.git
2. create database bankDB in your mySQL workbench   
3.Run this Query in mysql:

CREATE DATABASE  IF NOT EXISTS `bankDB`;
USE `bankDB`;

N.B: Hibernate creates the tables automatically when u run the app for the first time

setting 'spring.jpa.hibernate.ddl-auto=create' in your application.properties file; for SUBSEQUENT runs, set the property to

update i.e: 'spring.jpa.hibernate.ddl-auto=update';


4.Run Project One time using Spring boot command - mvn spring-boot:run or using eclipse IDE run as Java Application