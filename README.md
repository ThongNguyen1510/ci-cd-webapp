# CI/CD Web App
- Node.js + Express, Dockerized
- GitHub Actions: test → build → push Docker Hub → deploy EC2 via SSH & Docker Compose

## Run local
docker build -t demo .
docker run -p 3000:3000 demo
curl http://localhost:3000/
