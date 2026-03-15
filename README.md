# LinkedIn Microservices Project

A LinkedIn-style backend system built using Spring Boot microservices architecture.

## Architecture

The system consists of multiple services:

- API Gateway
- Discovery Server (Eureka)
- Auth Service (JWT Authentication)
- User Service
- Posts Service
- Connections Service

## Tech Stack

- Java 21
- Spring Boot
- Spring Cloud Gateway
- Eureka Service Discovery
- JWT Authentication
- PostgreSQL
- Maven

## Microservices

### API Gateway
Handles routing and authentication filtering.

### Discovery Server
Service registry using Netflix Eureka.

### Auth Service
Handles login and generates JWT tokens.

### User Service
Manages user profiles.

### Posts Service
Handles post creation and retrieval.

### Connections Service
Handles follow/connection logic.

## Running the Project

Start services in this order:

1. Discovery Server
2. API Gateway
3. Auth Service
4. User Service
5. Posts Service
6. Connections Service
