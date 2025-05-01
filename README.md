# 🚪 Generic Gateway Service

This is the **API Gateway** for the microservices system, built using **Spring Cloud Gateway**. 

It routes incoming client requests to the appropriate microservice using Eureka.

## 📝 Description

The gateway provides:
- Load-balanced routing using Eureka.
- Centralized access point to all microservices.
- Security features like authentication and global authorization using keycloak as resource server that issues a jwt token.
- TODO rate limiting and circuit breaker.