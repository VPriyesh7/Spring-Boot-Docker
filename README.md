# Spring Boot Application with Docker

![GitHub Repo Views](https://img.shields.io/badge/dynamic/json?color=blue&label=Visitors&query=visitors&url=https://api.countapi.xyz/hit/VPriyesh7/Spring-Boot-Docker)

## Overview

This project demonstrates the development and containerization of a Spring Boot application using Docker. It focuses on creating a reliable and portable setup that can be consistently deployed across different environments.

The implementation reflects practical experience in building backend services and packaging them for scalable and environment-independent execution.

## Technology Stack

* Java
* Spring Boot
* Maven
* Docker

## Key Features

* Designed and implemented a RESTful service using Spring Boot
* Containerized the application using Docker to ensure consistency across environments
* Followed a modular and maintainable project structure
* Applied standard development practices for build and dependency management

## Project Structure

The project is organized using a standard Maven layout:

* `src/main/java` – core application logic
* `src/main/resources` – configuration and properties files
* `Dockerfile` – configuration for building the container image
* `pom.xml` – dependency and build configuration

## Running the Application

### Using Docker

Build the Docker image:

```bash id="98bbsp"
docker build -t spring-boot-docker .
```

Run the container:

```bash id="l1jqre"
docker run -p 8080:8080 spring-boot-docker
```

### Running Locally

To run the application without Docker:

```bash id="j84xsl"
mvn clean install
mvn spring-boot:run
```

## API Endpoint

The application exposes a sample endpoint for validation:

* `GET /api/test`

## Future Improvements

* Integrate persistent storage (e.g., relational database)
* Add automated API testing for validation and regression
* Introduce CI/CD pipeline for build and deployment automation
* Enhance logging and monitoring capabilities

## Author

Priyesh Vanzara
Software Development Engineer in Test (SDET) | Java | Test Automation
