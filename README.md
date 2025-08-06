# VeggieMarket – CI/CD DevOps Pipeline

## Overview
This project demonstrates a full DevOps CI/CD setup using Jenkins, Docker, and GitHub.

## Features
- Frontend (React) and Backend (Node.js + Express)
- MongoDB for data storage
- CI/CD Pipeline using Jenkins
- Docker Compose for container orchestration

## CI/CD Workflow
- On `git push`, Jenkins pulls code from GitHub
- Builds Docker images for frontend and backend
- Spins up MongoDB, backend, and frontend containers using `docker-compose`

## Setup
App accessible at: [http://localhost:3000](http://localhost:3000)
