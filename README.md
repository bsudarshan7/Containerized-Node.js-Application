# Containerized Node.js Application

## Overview

This project demonstrates how to containerize a Node.js application using Docker and deploy it on AWS using Amazon ECR and Amazon ECS (Fargate). The Docker image is built locally, pushed to Amazon ECR, and then deployed as a containerized application through Amazon ECS.

---

## Architecture

Node.js Application
→ Docker Image
→ Amazon ECR
→ Amazon ECS (Fargate)
→ Running Container
→ Browser

---

## AWS Services Used

- Amazon Elastic Container Registry (ECR)
- Amazon Elastic Container Service (ECS)
- AWS Fargate
- AWS Identity and Access Management (IAM)

---

## Tools Used

- Docker
- Node.js
- Git
- GitHub
- AWS CLI

---

## Project Workflow

1. Cloned the existing Node.js application from GitHub.
2. Created a Dockerfile to containerize the application.
3. Built the Docker image locally.
4. Tested the application by running a Docker container.
5. Created an Amazon ECR repository.
6. Logged in to Amazon ECR using AWS CLI.
7. Tagged the Docker image with the ECR repository URI.
8. Pushed the Docker image to Amazon ECR.
9. Created an Amazon ECS cluster using AWS Fargate.
10. Created an ECS Task Definition.
11. Created an ECS Service to deploy the application.
12. Verified the application using the ECS public endpoint.

---

## Project Structur
nodejs-cicd-project-capstone/
│── app.js
│── package.json
│── package-lock.json
│── Dockerfile
│── .dockerignore
│── README.md

---

## Outcome

- Successfully containerized a Node.js application using Docker.
- Stored the Docker image securely in Amazon ECR.
- Deployed the containerized application using Amazon ECS with AWS Fargate.
- Demonstrated practical knowledge of Docker image creation, container deployment, Amazon ECR, and Amazon ECS.
