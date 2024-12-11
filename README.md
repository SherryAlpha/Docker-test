# Docker Test

This repository demonstrates deploying a Node.js app using Docker Swarm and CI/CD.

## Features
- Node.js Express app
- Docker Compose for local development
- Docker Swarm deployment with Docker Stack
- GitHub Actions for CI/CD

## Prerequisites
- Docker and Docker Compose installed
- A DockerHub account
- GitHub repository with secrets configured:
  - `DOCKER_USERNAME`: Your DockerHub username
  - `DOCKER_PASSWORD`: Your DockerHub password

## Usage
### Run Locally
```bash
docker-compose up
