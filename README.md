# Node Todo App — CI/CD with GitHub Actions 🚀

A simple Node.js Todo application, fully Dockerized with an automated CI/CD pipeline using GitHub Actions.

## 🛠 Tech Stack
- Node.js + Express
- Docker + Docker Compose
- GitHub Actions (CI/CD)
- DockerHub (image registry)

## ⚙️ How it works
Every push to `main` branch triggers GitHub Actions which:
1. Builds the Docker image
2. Runs tests automatically
3. Pushes the image to DockerHub

## 🚀 Run Locally

**Using Docker:**
```bash
docker pull lekhap15/node-todo-app:latest
docker run -d -p 8000:8000 lekhap15/node-todo-app
```

**Using Docker Compose:**
```bash
docker compose up -d
```

Then open `http://localhost:8000`

## 📦 DockerHub
`lekhap15/node-todo-app`

## 👤 Author

Lekha P
GitHub — https://github.com/Lekha15-cse
