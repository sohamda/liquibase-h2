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

Follow the step-by-step guide in this blog : 

### Inpired by

A few blogs to mention
1. https://javadeveloperzone.com/spring-boot/spring-boot-liquibase-example/
2. https://www.baeldung.com/liquibase-refactor-schema-of-java-app
3. https://www.liquibase.org/get-started
4. https://docs.spring.io/spring-boot/docs/current/reference/html/howto.html#howto-database-initialization