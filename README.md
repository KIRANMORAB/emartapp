# 🛒 EmartApp - Dockerized E-commerce Microservice App

**EmartApp** is a microservices-based e-commerce application that runs entirely in Docker containers using a single `docker-compose.yaml` file, provisioned automatically through Vagrant. It includes services like Angular frontend, Node.js backend, Java API, MySQL, MongoDB, and Nginx.

---

## 🚀 Features

- 🐳 Full Docker-based deployment
- 🔧 One-command Vagrant setup (provisions Docker + runs containers)
- 📦 Microservices architecture (Frontend, Node API, Java API)
- 🗃️ Multi-database setup (MySQL + MongoDB)
- 🌐 Nginx as a reverse proxy
- ⚡ Auto-starts the application on `vagrant up`

---

## ⚙️ Stack Overview

| Component     | Technology                     |
|---------------|--------------------------------|
| Frontend      | Angular (served via Nginx)     |
| Backend 1     | Node.js API                    |
| Backend 2     | Java Spring Boot API           |
| Databases     | MongoDB, MySQL                 |
| Containerization | Docker & Docker Compose     |
| Provisioning  | Vagrant                        |

---

## ⚡ Quickstart (How to Start)

### RUN

```bash
git clone https://github.com/KIRANMORAB/emartapp.git
cd emartapp
vagrant up
```
### ACCESS
```bash
Open your browser and go to:
http://192.168.56.82
