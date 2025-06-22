# Dockerizing a Simple Python Script

This project demonstrates how to **containerize** a basic Python application using **Docker** and deploy it using Docker Hub. It serves as a foundational example for understanding environment consistency, reproducible builds, and basic MLOps principles.

---

## Project Overview

- A simple Python script (`app.py`) prints a message when run.
- The script is containerized using a custom `Dockerfile`.
- The Docker image is built, tested locally, and pushed to Docker Hub.
- The image can be pulled and executed on any machine with Docker installed.

---

## Key Concepts  

| Term                   | Definition                                                                                     |
|------------------------|------------------------------------------------------------------------------------------------|
| **Docker**             | A platform for building, shipping, and running containers. Containers bundle code + dependencies. |
| **Container**          | A lightweight, standalone execution environment packaged from an image.                        |
| **Docker Image**       | A read-only snapshot (template) that defines what goes into your container.                    |
| **Docker file**        | A declarative script used by Docker to build an image—specifies base image, dependencies, tasks. |
| **Docker Hub**         | A public registry where you can push/pull container images.                                    |
| **CI/CD**              | Continuous Integration/Continuous Deployment—automated build, test, and release workflows.     |
| **GitHub Actions**     | GitHub’s native CI/CD engine to automate workflows on push, PR, or schedule events.            |

---

