# vite-react-docker-template

This project is a **Vite + React + TypeScript frontend**, configured to run in **Docker** for development with **hot reload** and ready for production deployment.

---

## 📂 Project Structure

│ Dockerfile.dev # Development Dockerfile (Vite dev server with hot reload)
│ docker-compose.yml # Development Compose config (volumes + watch)


---

## 🗂 File Roles

| File | Purpose |
|------|---------|
| **Dockerfile.dev** | Development container: runs Vite dev server with **hot reload** inside Docker. |
| **docker-compose.yml** | Configures the dev container, maps ports, mounts volumes, and sets up **file watching**. |


---

## ⚡ Development Setup (Local)

### 1. **Ensure you have Docker Desktop installed.**  
### 2. Clone the repository:

```bash
git clone https://github.com/codafine-dev/vite-react-docker-template.git
```

Copy the two files into your project's folder.

### 3. Start the development container with hot reload:
```bash
docker compose up --watch
```

### 4. Open your browser at:
**http://localhost:3000/**
And Voilà !

