"⚙️ Jenkins CI/CD Pipeline for Flask Portfolio
This repository illustrates a complete Jenkins workflow that automates the building, testing, and deployment processes for a Flask web application."

🎯 Objectives

Streamline the entire lifecycle of a Flask application through Jenkins automation

Highlight a practical, real-world DevOps CI/CD workflow

Illustrate Docker image building, versioning, and deployment

🧩 Pipeline Overview
The Jenkinsfile orchestrates the following stages:

1️⃣ Code Checkout — Retrieves the latest source code from GitHub
2️⃣ Dependency Installation — Sets up required Python packages (Flask, flake8)
3️⃣ Linting — Ensures code quality with flake8
4️⃣ Docker Image Build — Packages the Flask application into a Docker container
5️⃣ Push to DockerHub — Uploads the Docker image to your DockerHub repository
6️⃣ Staging Deployment — Deploys the latest image to a server on port 5000

🧠 Key Learnings

Setting up Jenkins declarative pipelines for automation

Integrating Docker into CI/CD workflows

Managing credentials securely within Jenkins

Automating the deployment process for Flask applications
