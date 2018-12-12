# This project is to build up a hello-world containerized project. I applied docker-maven-plugin into the pom.xml. The github of docker-maven-plugin can be referred from: https://github.com/spotify/docker-maven-plugin .
# To test-run this code, please use the following steps:
* cd [project-folder]
* ./mvnw package
* ./mvnw dockerfile:build
* ./mvnw verify
* ./mvnw dockerfile:push
* ./mvnw deploy 
