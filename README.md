# Dockerize-Flask-App
A simple Flask application that says Hello COSC!

## Getting Started

To dockerize this Flask application, follow these steps:

1. Create a `Dockerfile` in the root directory
2. Add a `.dockerignore` file to exclude unnecessary files

## Instructions

Create the necessary Docker configuration files to containerize this Flask application. 

## Docker Execution Instructions

## 🚀 Getting Started

### Prerequisites
- [Docker](https://www.docker.com/products/docker-desktop/) installed
- Git (optional for cloning)

### 🛠️ Setup

1. **Clone the repository** (optional):
   ```bash
   git clone https://github.com/cbitosc/Dockerize-Flask-App.git
   cd Dockerize-Flask-App
   ```
2 . **Build the Docker image:**
  ```bash
  docker build -t flask-cosc-app .
  ```
3 . **Run the container:**
  ```bash
  docker run -p 5000:5000 flask-cosc-app
  ```
4 . **Access the application:**
  ```bash
  Open your browser and visit:
👉 http://localhost:5000
```
