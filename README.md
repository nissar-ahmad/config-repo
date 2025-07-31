# config-repo

**Centralized Configuration Repository for Microservices**

This repository acts as the **backing store** for the Spring Cloud Config Server (`config-service`) and holds externalized configuration files (`application.yml`) for all individual microservices (e.g., `customer-service`, `account-service`, `api-gateway`, etc.) across different environments (`dev`, `prod`, etc.).

---

## 🌐 Purpose

- To decouple configuration from application code
- Enable **externalized**, **centralized**, and **environment-specific** configuration management
- Support dynamic refresh of properties via Spring Cloud Bus (if enabled)
- Enable fast switching and isolation of configuration for **multi-environment deployments**

---
