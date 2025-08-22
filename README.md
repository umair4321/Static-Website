# Static Website Deployment with Nginx + Docker + GitHub Actions

## Overview
A simple static HTML website deployed using **Nginx**, containerized with **Docker**, and automated with **GitHub Actions**.

## Features
- Static HTML page
- Dockerfile with Nginx
- CI/CD pipeline on GitHub Actions

## Run Locally
```bash
docker build -t static-website .
docker run -p 8080:80 static-website
