In this project we'll set up a continuous integration pipeline on AWS. The first benefits, of course, we get is short MTR, it's going to be agile and we're going to have no human intervention in this.

![Screenshot (202)](https://github.com/arunma076/ci-aws/assets/114279863/45fa093e-d6ae-4aca-8bc4-51e514c39686)

# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


