# Containerized Node.js Hello World

This project is a hands-on demonstration of containerization fundamentals. It features a Node.js application packaged into a lightweight Docker image and prepared for deployment to a cloud registry.

## 🚀 Lab Objectives
* Writing a **Dockerfile** to define a custom environment.
* Building and managing **Docker Images**.
* Running applications in **Detached Mode** with port mapping.
* Pushing images to the **IBM Cloud Container Registry**.

## 🛠️ Tech Stack
* **Node.js**: The application runtime.
* **Docker**: Containerization platform.
* **Alpine Linux**: Base OS for a minimal footprint.
* **IBM Cloud**: Target registry for the image.

## 📦 How to Run Locally

1. **Build the image:**
   ```bash
   docker build -t myimage:v1 .
