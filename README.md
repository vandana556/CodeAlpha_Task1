# CodeAlpha Task 1 – CI/CD Pipeline using Docker

## Project Overview

This project demonstrates a complete CI/CD pipeline for deploying a containerized web application.

The application is stored in GitHub, automatically built using GitHub Actions, pushed to Docker Hub, and deployed as a live web service using Render.

## CI/CD Architecture

GitHub Repository
        ↓
GitHub Actions
        ↓
Docker Image Build
        ↓
Docker Hub
        ↓
Render
        ↓
Live Web Application

## Technologies Used

- HTML
- Docker
- Nginx
- GitHub
- GitHub Actions
- Docker Hub
- Render
- YAML

## Project Structure

```text
CodeAlpha_Task1/
│
├── index.html
├── Dockerfile
├── .github/
│   └── workflows/
│       └── docker-image.yml
└── README.md
