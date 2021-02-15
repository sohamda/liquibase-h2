# Spring Boot + Liquibase + H2

A simple spring boot application which illustrates how to use Liquibase for your database changes. 
This application uses H2 as in-memory database to showcase, but you can also use an external database instead.

Springboot manages the execution of the liquibase updates at startup automatically. Although you can control that via spring config prop in application.properties.

### Liquibase Props to configure

There are several config options from spring boot. Check this [class](https://github.com/spring-projects/spring-boot/blob/v2.4.2/spring-boot-project/spring-boot-autoconfigure/src/main/java/org/springframework/boot/autoconfigure/liquibase/LiquibaseProperties.java).

## To run this :
`` mvn clean install ``

`` mvn sprint-boot:run``

## Detail - How to

Follow the step-by-step guide in this blog : https://adfjava.blogspot.com/2021/02/spring-boot-liquibase-h2.html
