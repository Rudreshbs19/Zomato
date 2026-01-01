# 📘 DevOps AddressBook – CI/CD with Jenkins & Docker

This repository contains the **DevOps automation** setup for the AddressBook application using **Jenkins** and **Docker**.  
The goal is to demonstrate complete CI/CD automation with containerized deployment.

---

## 🚀 Project Overview

| Feature | Description |
|--------|-------------|
| CI/CD Tool | Jenkins |
| Containerization | Docker |
| Source Control | Git & GitHub |
| Build & Deployment | Automated pipeline |
| Environment | Dev, Staging, Production (Configurable) |

A DevOps pipeline workflow:
1. Developer commits code → GitHub
2. Jenkins pulls latest code
3. Jenkins builds Docker image
4. Docker Hub image push
5. Deploy updated container

---

## 🛠️ Tech Stack

- **Docker**
- **Jenkins**
- **Git & GitHub**
- (Add your application stack here → Java / Python / Node.js)

---

## 📁 Repository Contents

| File / Folder | Purpose |
|--------------|---------|
| `Dockerfile` | To build the app image |
| `Jenkinsfile` | Automated CI/CD pipeline |
| `src/` | Source code of AddressBook app |
| `.gitignore` | Ignores unwanted files |
| `README.md` | Project Documentation |

---

## 📦 Docker Setup

Build and run Docker container manually:

```bash
docker build -t addressbook-app .
docker run -p 8080:8080 addressbook-app

