# java-web-maven-spring-thyme-sqlserver-ssl

## Description
A POC for springboot web app with thymeleaf support
connecting to a database.

Sql server uses self-signed ssl.

## Tech stack
- java
- maven
  - springboot
  - thymeleaf
  - sqlserver connector
- bootstrap
- jquery
- dataTable

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- openjdk:11-jdk

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://spring.io/guides/gs/accessing-data-mysql/
- https://medium.com/@gustavo.ponce.ch/spring-boot-jquery-datatables-a2e816e2b5e9
- https://www.javaguides.net/2019/01/spring-boot-microsoft-sql-server-jpa-hibernate-crud-restful-api-tutorial.html
