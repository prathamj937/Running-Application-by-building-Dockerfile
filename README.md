# 🚀 React App in Docker

This project runs a React app using Docker. It builds the app, serves it using `serve`, and exposes it on port 3000.

---

## 📦 Prerequisites

- Docker Desktop installed and running
- Internet connection (for downloading dependencies)

---

## Make sure you're in the root folder of the project (where the Dockerfile is located).

## 1. 🛠️ Build Docker Image
ON BASH: docker build -t my-react-app .

## 2. 🚀 Run Docker Container
ON BASH: docker run -d -p 3000:3000 --name react-container my-react-app
