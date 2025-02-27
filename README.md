
## MicroServices-Project

#Application Overview
We will be building a simple e-commerce application where customers can order products. Our application contains the following services:
Product Service
Order Service
Inventory Service
Notification Service

To focus on the principles of Spring Cloud and Microservices, we developed services with essential functionality rather than creating fully-featured e-commerce services.



<img width="709" alt="image" src="https://github.com/user-attachments/assets/0ee878a5-b1f6-40c2-95a9-5d4781935635" />



## Features & Implementations

### 1️⃣ **RESTful API Development**
- Developed RESTful services using **Spring Boot 3**, following best practices.

### 2️⃣ **Inter-Service Communication**
- Implemented **synchronous communication** using **Spring Cloud OpenFeign**.

### 3️⃣ **Service Discovery**
- Integrated **Spring Cloud Netflix Eureka** for dynamic service registration and discovery.

### 4️⃣ **API Gateway**
- Configured **Spring Cloud Gateway** for centralized request routing and security.

### 5️⃣ **Security & Authentication**
- Implemented **Keycloak** for authentication, authorization, and identity management.

### 6️⃣ **Resilience & Fault Tolerance**
- Used **Resilience4J** for **circuit breaking**, ensuring high availability.

### 7️⃣ **Event-Driven Architecture**
- Leveraged **Kafka** for **asynchronous communication and event processing**.

### 8️⃣ **Observability & Monitoring**
- **Distributed Tracing** using **OpenTelemetry & Grafana Tempo**.
- **Log Aggregation** with **Grafana Loki**.
- **Metrics Collection & Visualization** via **Prometheus & Grafana dashboards**.

### 9️⃣ **Containerization & Deployment**
- **Docker** for containerizing services.
- **Docker Compose** for managing multi-container applications.
- **Kubernetes** migration for **scalability, orchestration, and high availability**.

## 🏗️ **Getting Started**
### Prerequisites
- Java 17+
- Docker & Docker Compose
- Kubernetes & kubectl (for K8s deployment)
- Kafka (for event-driven architecture)
- Keycloak (for authentication)

### Installation & Setup
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-repo/microservices-architecture.git
   cd microservices-architecture




