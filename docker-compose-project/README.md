# Docker Compose Multi Container Project

## Technologies Used
- Docker
- Docker Compose
- Nginx
- Node.js
- Redis

## Architecture
Nginx -> Node.js App -> Redis

## Run Project

```bash
docker compose up -d
```

## Verify Containers

```bash
docker ps
```

## Access Application

```bash
http://localhost
```

## Project Features
- Multi-container setup
- Reverse proxy using Nginx
- Redis container integration
- Docker networking
- Volume mounting