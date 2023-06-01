DOCKER HUB
Create organization --> repos
IMAGES 
Tomcat --> build image
nginx --> build image
mysql --> build image
memcached --> from dockerhub
rabbitmq --> from dockerhub



--> create a repo
   --> src from github
   --> create docker file for db,web,app
   app--> +target repo (artifacts)
        --> target repo obtained after installing open-jdk-8 amd maven then run mvn install
   db--> + db_backup.sql file
   web--> + nginx.config file
   
   BUILD IMAGES
    --> images name same as repos created on docker hub
   
   
   
