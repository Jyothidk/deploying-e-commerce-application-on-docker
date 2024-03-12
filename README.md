# Roboshop using Docker

Roboshop is a sample popular Microservices application. It is owned by Instana which is acquired by IBM. They use this project in their product developments like instana APM tool and other products. It has all the services used for an ideal ecommerce company.

## Clone :
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
![image](https://github.com/Jyothidk/deploying-e-commerce-application-on-docker/assets/127189060/9a1f840b-54a9-4bd9-b9ea-b8ba2468a4d4)

![image](https://github.com/Jyothidk/deploying-e-commerce-application-on-docker/assets/127189060/7cdbf5fc-bbec-42eb-973e-90c1fc0d2df9)

## Access the roboshop application on browser

```
http://localhost:80
```

![image](https://github.com/Jyothidk/deploying-e-commerce-application-on-docker/assets/127189060/a6f54f1a-54b4-4faf-9f27-03cd201109d1)


![image](https://github.com/Jyothidk/deploying-e-commerce-application-on-docker/assets/127189060/05a5d23b-f0d7-4a78-9e90-7b136ef21b3e)

