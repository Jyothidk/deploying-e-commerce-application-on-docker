# Roboshop using Docker

Roboshop is a sample popular Microservices application. It is owned by Instana which is acquired by IBM. They use this project in their product developments like instana APM tool and other products. It has all the services used for an ideal ecommerce company.

## Steps:
* Clone this project.
```
cd /home/jyothi/SIVA/
git clone https://github.com/Jyothidk/deploying-e-commerce-application-on-docker.git
```
* Make sure folders are created for Docker volumes.
```
cd /home/jyothi/SIVA/
mkdir mysql rabbitmq redis mongodb
```
## Build docker images and create the containers using docker compose file

```
cd roboshop
docker-compose up -d
```
