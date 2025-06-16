
# Docker and Containers Guide

Welcome to the **Docker and Containers** repository! This repo is a curated collection of Docker examples, exercises, and best practices for learning containerization from scratch or strengthening your skills.

---

## What You'll Find Here

- Beginner-friendly Docker projects
- Real-world `docker-compose.yml` examples
- 🛠Custom Dockerfiles for web and database services
- Network and volume configuration examples
- Docker CLI command cheat sheets
- Common errors & troubleshooting tips

---

## Folder Structure


├── 01_hello-docker/           # Basic Dockerfile & image creation
├── 02_docker-compose/         # Multi-container app with Docker Compose
├── 03_custom_images/          # Custom Dockerfiles for various services
├── 04_volumes_networks/       # Examples using volumes and custom networks
├── 05_troubleshooting/        # Common error cases and solutions
├── cheatsheets/               # Docker CLI and Compose reference
└── README.md                  # You are here :)

---

## Prerequisites

* Basic understanding of Linux commands
* Docker Desktop or Docker Engine installed

---

## Learning Goals

By the end of using this repo, you should be able to:

* Build and run custom Docker images
* Use Docker Compose to manage multi-container setups
* Manage Docker volumes and networks
* Debug and solve common container issues

---

## Tools Used

* Docker CLI
* Docker Compose
* Bash/Zsh
* Optional: Visual Studio Code with Docker extension

---

## Useful Commands


# List all containers
docker ps -a

# Remove all stopped containers
docker container prune

# Remove all images
docker rmi $(docker images -q)

# Build image from Dockerfile
docker build -t your-image-name .

# Run container from image
docker run -d -p 8080:80 your-image-name



---

## Connect

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/maya-mnaizel/)


