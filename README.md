# 🌱 DiscoveryLowCarb

**Part of the [LowCarb](https://github.com/Eddvance/LowCarb) application**

Eureka Server for service discovery in the LowCarb microservices ecosystem.

## 🎯 Role

Central registry where all LowCarb microservices register themselves. Enables:
- Service discovery (services find each other by name, not hardcoded URLs)
- Load balancing
- Health monitoring

## 🛠️ Tech Stack

- Java 17
- Spring Boot 3.x
- Spring Cloud Netflix Eureka Server

## 🚀 Running

This service is part of the LowCarb microservices ecosystem. See the main [LowCarb repository](https://github.com/Eddvance/LowCarb) for full setup instructions with Docker Compose.

**Access:** http://localhost:8761

## 📡 Registered Services

| Service | Port |
|---------|------|
| LowCarb | 8080 |
| LowCarbPower | 8081 |
| CoalFired | 3000 |
| Monitoring | 8082 |

## 📝 License

MIT License - see [LICENSE](LICENSE) for details.
