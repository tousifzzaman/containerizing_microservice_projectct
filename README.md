# EmartApp – Multi-Service Web Application

A complete microservice-based e-commerce app powered by Docker and modern web technologies. This app demonstrates integration between frontend, backend, and multiple databases using Docker Compose.

## 🧩 Services

- **client/** – Angular frontend (runs on port `4200`)
- **nodeapi/** – Node.js Express API (runs on port `5000`)
- **javaapi/** – Java Spring Boot API (runs on port `9000`)
- **nginx/** – NGINX reverse proxy (runs on port `80`)
- **emongo** – MongoDB database (used by `nodeapi`)
- **emartdb** – MySQL database (used by `javaapi`)
- **kkartchart/** – Additional charts module (if applicable)

## 🐳 Run with Docker Compose

```bash
docker-compose up --build
```

## 📷 Screenshot

![Preview](assets/screenshot.png)

 


