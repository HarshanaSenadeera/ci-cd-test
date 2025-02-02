# CI/CD Pipeline with Docker

This repository demonstrates how to set up a CI/CD pipeline using Docker, GitHub, and Jenkins. The pipeline automates the process of building, testing, and deploying applications, ensuring a smooth and efficient workflow.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Pipeline Overview](#pipeline-overview)
- [Conclusion](#conclusion)

## Introduction
Continuous Integration (CI) and Continuous Deployment (CD) are essential practices in modern software development. By integrating Docker with CI/CD tools like GitHub and Jenkins, we can create a robust pipeline that automates the entire development lifecycle.

## Prerequisites
- Docker installed on your machine
- GitHub account
- Jenkins installed and configured
- Basic knowledge of Docker, Git, and Jenkins

## Setup
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/HarshanaSenadeera/ci-cd-test.git
   cd GitHub-Docker-and-Jenkins-CI-CD-Pipeline
   ```

2. **Configure Jenkins:**
   - Install necessary plugins: Docker, GitHub, Pipeline
   - Create a new Jenkins pipeline job
   - Connect Jenkins to your GitHub repository

3. **Create Dockerfile:**
   - Define the environment and dependencies for your application

4. **Write Jenkinsfile:**
   - Define the stages of your CI/CD pipeline (Build, Test, Deploy)

## Pipeline Overview
1. **Build Stage:**
   - Jenkins pulls the latest code from GitHub
   - Docker builds the application image

2. **Test Stage:**
   - Run automated tests inside the Docker container

3. **Deploy Stage:**
   - Push the Docker image to a container registry
   - Deploy the application to a staging or production environment

## Conclusion
By integrating Docker with a CI/CD pipeline, you can streamline your development process, reduce errors, and ensure consistent deployments. This setup provides a scalable and efficient way to manage your application's lifecycle.

For more details, refer to the documentation and examples provided in this repository.
