# 📊 Spring Boot Admin Server

This project is a **Spring Boot Admin Panel** built using the `spring-boot-admin-starter-server` dependency by [codecentric](https://github.com/codecentric/spring-boot-admin). It provides a powerful and user-friendly web UI to monitor and manage Spring Boot applications in real-time.

## ✅ Features

- Auto-discovery of Spring Boot clients
- Real-time metrics (memory, CPU, threads, etc.)
- Log file access and log level management
- JVM environment and system properties
- Trace and HTTP request monitoring
- Endpoint browsing (via Spring Boot Actuator)
- Notifications and status monitoring (email, Slack, etc.)
- Authentication and Security (optional)

## 🔧 Technologies Used

- **Spring Boot Admin Server**
- **Spring Boot Actuator**
- **Spring Web**
- **Maven** or **Gradle** for build
- **Spring Security** (optional)

## 🚀 Getting Started

### 1. Clone the Project

```bash
git clone https://github.com/benalif/SpringBootOps.git
cd SpringBootOps/
cd spring-boot-admin/ && mvn clean package
cd ../spring-boot-client/ && mvn clean package
docker-compose up -d
