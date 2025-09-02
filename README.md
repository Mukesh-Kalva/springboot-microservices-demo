
# 🚀 Spring Boot Microservices Demo  

A **microservices-based application** built with **Spring Boot**, demonstrating scalable architecture, service communication, centralized gateway, and monitoring.  

## 📂 Microservices Overview  
- **Catalog Service** – Manages product catalog.  
- **Dealer Service** – Handles dealer information.  
- **Order Service** – Manages customer orders.  
- **Quote Service** – Provides pricing and quotes.  
- **Shipment Service** – Tracks shipment and delivery.  
- **Rest API Gateway** – Entry point for routing requests.  
- **Web App** – User-facing frontend.  
- **Zipkin Server** – Distributed tracing & monitoring.  

## ✨ Features  
- Service-to-service communication with REST  
- Centralized API Gateway  
- Distributed tracing with **Zipkin**  
- Containerized with **Docker**  
- CI/CD ready (Helm, Kubernetes manifests included)  

## 🛠 Tech Stack  
- **Java + Spring Boot**  
- **Gradle** build system  
- **Docker & Kubernetes** for container orchestration  
- **Zipkin** for monitoring and tracing  
- **CI/CD** with Azure Pipelines / Helm  

## ⚡ Getting Started  

### Prerequisites  
- JDK 17+  
- Gradle / Maven  
- Docker (optional, for containers)  

### Run Locally (Gradle)  
```bash
cd CatalogSrvc
./gradlew bootRun
````

Repeat for other services.

### Run with Docker

```bash
docker build -t catalog-service ./CatalogSrvc
docker run -p 8081:8081 catalog-service
```

### Run with Kubernetes (Helm charts included)

```bash
helm install catalog ./deploy/helm/catalog
```

## 👤 Author

**Mukesh Kalva**
[GitHub](https://github.com/Mukesh-Kalva)

```
  

Do you also want me to give you an **ASCII architecture diagram** (text-based) so it still looks good directly in GitHub README without needing images?
```
