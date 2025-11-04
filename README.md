# docker-springboot-app
# 🐳 Dockerized Spring Boot App

Containerized a Spring Boot app using a multi-stage Docker build.

### 🧰 Commands
```bash
mvn clean package -DskipTests
docker build -t springboot-app .
docker run -p 8080:8080 springboot-app
