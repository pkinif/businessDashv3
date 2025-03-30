
# 📊 businessDashv3

A modular **Shiny** application built with the **Rhino framework**.

---

## 🚀 Deploy with Docker

### ✅ Prerequisites
- **R version:** 4.3.2 (same version used in the Dockerfile)
- **Docker & Docker Compose** installed

---

### 🔥 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/pkinif/businessDashv3.git
   cd businessDashv3
   ```

2. **Build the Docker image**
   ```bash
   docker build -t business-app-shiny:latest .
   ```

3. **Start the app using Docker Compose**
   ```bash
   docker compose up -d
   ```

4. **Access the app**
   Open your browser and go to:
   ```
   http://localhost:3838
   ```

---

### ℹ️ Notes

- The app is fully modularized using **Rhino**.
- This repository includes:
  - `.dockerignore`
  - `renv.lock`
  - `docker-compose.yml`
- You can easily adapt the `docker-compose.yml` to:
  - Mount volumes
  - Pass environment variables
  - Add NGINX reverse proxy with HTTPS


---
