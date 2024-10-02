## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

#goal 
- running web app including database by docker ,then upload it into you own docker repository 

#step 
- creat app web db docker file (find the base several images on docker hub) 
- customize the dockerfile 
- wirten docker compose file
- after finish the docker compsoe up
- push the docker images into you own docker hub repository 


## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


