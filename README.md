
# TaskFlow

A learning-oriented distributed task management system built with Java 21 and Spring Boot Microservices.

## Architecture

TaskFlow is composed of independent microservices communicating through REST APIs and Apache Kafka.

## Technology Stack

- Java 21
- Spring Boot 4
- Spring Cloud Gateway
- PostgreSQL
- Keycloak
- Apache Kafka
- Redis
- Docker and Docker Compose
- Maven

## Services

| Service | Responsibility |
|---|---|
| User Service | User profile management |
| Project Service | Project management |
| Task Service | Task management |
| Notification Service | Event-driven notifications |
| API Gateway | Centralized API entry point |

## Infrastructure

- Keycloak: Authentication and authorization
- Kafka: Asynchronous communication
- Redis: Caching
- PostgreSQL: Persistent storage
- Docker Compose: Local infrastructure and service orchestration

## Project Status

Phase 0 - Environment setup and repository initialization.

