# Symplichain Hackathon Assignment

This repository contains the GitHub Actions workflow for CI/CD deployment of a Django + React application.

## Workflow Details

- Triggered on push to `main` and `staging` branches
- Builds frontend using Node.js
- Installs backend dependencies (Django)
- Collects static files
- Deploys to EC2 via SSH
- Restarts Gunicorn and Nginx

## Author

Omprakash Karri
