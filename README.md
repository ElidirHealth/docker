# Jenkins
This repository contains the docker image definition for our internal jenkins server

## commands
* `docker build -t ad-jenkins .`
* `docker rm jenkins`
* `docker run -d --restart always  --name jenkins  -p 8080:8080 -p 5000:5000 -v /var/lib/jenkins:/var/jenkins_home adjenkins`
   
   
