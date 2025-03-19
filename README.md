This project demonstrates how to build and deploy a multi-container application using Docker Compose.

## Folder Structure

- `app/`: Contains the application code for each service.
  - `service1/`: A web application (NGINX).
  - `service2/`: A REST API (Node.js).
- `docker-compose.yml`: Defines the multi-container setup.

## How to Use

1. Build and start the containers:
   ```
   docker-compose up --build
Access the services:

Service 1 (NGINX): http://localhost:5000

Service 2 (Node.js): http://localhost:5001

Stop the containers:



docker-compose down
Prerequisites
Docker installed: https://docs.docker.com/get-docker/

Docker Compose installed: https://docs.docker.com/compose/install/

Example Commands


Build and Start Containers
docker-compose up --build


Stop Containers
docker-compose down


View Logs
docker-compose logs


Access Service 1 (NGINX)
curl http://localhost:5000


Access Service 2 (Node.js)
curl http://localhost:5001
