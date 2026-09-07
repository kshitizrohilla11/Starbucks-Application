# Starbucks Application – CI/CD Deployment

## 🚀 Project Overview

This project demonstrates the deployment of a Starbucks web application
using a CI/CD pipeline implemented with Jenkins, Docker, Docker Hub,
and AWS EC2.

The application source code is maintained in GitHub. Jenkins automatically
checks out the source code, installs dependencies, builds the Docker image,
pushes the image to Docker Hub, and deploys the application as a Docker
container on an AWS EC2 instance.

## 🛠️ Technologies Used

- AWS EC2
- Jenkins
- Docker
- Docker Hub
- Git
- GitHub
- Node.js
- NPM
- Linux
- Shell Scripting

## 🔄 CI/CD Workflow

```text
GitHub
   │
   ▼
Jenkins
   │
   ├── Clean Workspace
   │
   ├── Git Checkout
   │
   ├── Install NPM Dependencies
   │
   ├── Build Docker Image
   │
   ├── Push Image to Docker Hub
   │
   └── Deploy Docker Container
             │
             ▼
         AWS EC2
             │
             ▼
    Starbucks Application
```

## ⚙️ Jenkins Pipeline

The Jenkins pipeline automates the following process:

1. Clean Workspace
2. Git Checkout
3. Install NPM Dependencies
4. Build Docker Image
5. Tag Docker Image
6. Push Docker Image to Docker Hub
7. Deploy Docker Container

## 🐳 Docker

The application is containerized using Docker.

Docker image:

```
sinu11/starbucks:latest
```

The Docker image is built by Jenkins and pushed to Docker Hub.

## ☁️ AWS EC2 Deployment

The application is deployed on an AWS EC2 instance.

Jenkins is used to automate the deployment of the Docker container on
the EC2 server.

## 📸 Screenshots

### Jenkins Pipeline
![Jenkins Pipeline](screenshots/jenkins-pipeline.png)

### Jenkins Deployment
![Jenkins Deployment](screenshots/jenkins-deployment.png)

### Docker Hub
![Docker Hub](screenshots/dockerhub-image.png)

### Starbucks Application
![Starbucks Application](screenshots/starbucks-application.png)

## 🎯 Key Learnings

- Jenkins CI/CD pipeline configuration
- GitHub and Jenkins integration
- Docker containerization
- Docker image creation
- Docker Hub integration
- AWS EC2 deployment
- Linux and shell scripting
- Automated application deployment

## 👨‍💻 Author

**Kshitiz Rohilla**

GitHub: https://github.com/kshitizrohilla11

LinkedIn: https://www.linkedin.com/in/kshitiz-rohilla-681bb0255
