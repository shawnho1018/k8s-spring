## This project is to build up a hello-world containerized project. I applied dockerfile-maven techniques into the pom.xml. The github of dockerfile-maven can be referred from: https://github.com/spotify/dockerfile-maven 

## To test-run this code, please use the following steps:
* cd [project-folder]
* ./mvnw package
* ./mvnw dockerfile:build
* ./mvnw verify
* ./mvnw dockerfile:push
* ./mvnw deploy 
