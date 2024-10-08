 # WordPress with MySQL using Docker Compose

This project sets up a WordPress site with a MySQL database using Docker Compose.
It simplifies the process of deploying a WordPress instance with a MySQL backend using containerization.

## Prerequisites

- Docker should be installed 
- Basic knowledge of Docker Compose

 ## Clone the Repository
 git clone https://github.com/kadamvignesh/wordpress-docker-compose.git
 
 cd wordpress-docker-compose

## Build and Run the Containers
docker-compose up -d

## Access WordPress
Open your web browser and navigate to http://localhost:8080 to complete the WordPress setup.

## This is what it will look like
![image alt](https://raw.githubusercontent.com/kadamvignesh/wordpress-docker-compose/main/Screenshot%20(29).png)

## To stop and remove the containers
docker-compose down
