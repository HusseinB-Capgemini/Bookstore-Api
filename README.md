# Bookstore API

## Project Overview

**Online Bookstore with Microservices Architecture**

This project involves building a simple online bookstore using microservices. Each microservice will be developed with Java and Spring Boot, containerized using Docker, and orchestrated using Kubernetes.

## Part 1: Building the Application in Java

You'll start by creating microservices with Spring Boot, a popular Java framework.

### Key Features:
- **Book Service**: Manages books with CRUD operations.
- **Order Service**: Handles customer orders.
- **Customer Service**: Manages customer information.
- **Payment Service**: Handles payments.
- **Inventory Service**: Tracks stock levels.

### Technologies:
- **Spring Boot**: For building REST APIs.
- **Hibernate and Spring Data JPA**: For database integration.
- **MySQL or PostgreSQL**: As the database.

### Steps:
1. **Set Up Spring Boot**: Create a basic Spring Boot project for each service.
2. **Create REST APIs**: Develop RESTful endpoints for:
   - Adding and retrieving books
   - Creating orders
   - Handling payments
   - Managing customer data
3. **Database Integration**: Use Spring Data JPA for data persistence.
4. **Testing**: Write unit and integration tests using JUnit and Mockito.

## Part 2: Dockerizing the Microservices

Once your services are functional, containerize them using Docker.

### Steps:
1. **Create Dockerfiles**: Write Dockerfiles for each microservice to build and run them in containers.
2. **Build Docker Images**: Use `docker build` to create container images.
3. **Test Locally**: Run your microservices locally using Docker Compose to simulate multiple services running together.

## Part 3: Deploying to Kubernetes

Integrate Kubernetes to orchestrate your microservices.

### Steps:
1. **Set Up a Kubernetes Cluster**:
   - Use a local solution like Minikube or a cloud provider such as Google Kubernetes Engine (GKE) or Amazon EKS.
2. **Create Kubernetes Manifests**: Write YAML files for:
   - **Deployments**: Deploy each microservice as a pod.
   - **Services**: Expose the microservices internally and externally.
   - **ConfigMaps/Secrets**: Manage configurations and database credentials.
3. **Horizontal Scaling**: Configure auto-scaling based on traffic with Horizontal Pod Autoscaler.
4. **Networking**: Set up service discovery and load balancing within the Kubernetes cluster.
5. **CI/CD Integration** (Optional): Use a CI/CD pipeline (e.g., Jenkins or GitLab CI) to automate building, testing, and deploying to Kubernetes.

## Bonus: Monitoring and Logging

- **Monitoring**: Use Prometheus and Grafana.
- **Logging**: Use the ELK Stack (Elasticsearch, Logstash, Kibana) for centralized logging.

## Skills You’ll Learn:
- **Java**: Core concepts, REST API development, database integration.
- **Spring Boot**: Building microservices.
- **Docker**: Containerizing applications.
- **Kubernetes**: Deploying, scaling, and managing containerized applications.
- **CI/CD**: Automating deployment processes.
- **Monitoring and Logging**: Setting up observability for your application.

This project will provide a solid mix of learning Java, Docker, and Kubernetes, and prepare you for real-world cloud-native development.
