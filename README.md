# Effective Mobile Test Task

# Project Description

This project is a simple web application deployed using Docker and Docker Compose for Effective-mbile team.

It consists of:   Python backend HTTP server
                  Nginx reverse proxy

Nginx acts as a reverse proxy and forwards all incoming requests to the backend service inside the Docker network.

## Architecture

Client → Nginx (port 80) → Backend (Python HTTP server, port 8080)

---

## Technologies Used

 Python 3 (http.server)
 Nginx (reverse proxy)
 Docker
 Docker Compose

---

##  How to Run

### 1. Clone repository
```bash
git clone https://github.com/Zhorarz/effective.git
cd (repo cloned location)

## For building project
docker compose up --build

## And for checking can do
curl http://localhost

