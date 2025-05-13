## Flask Docker Application

This is a simple Flask application containerized using Docker. The app responds with **"Hello, Docker!"** when accessed at the root URL (`/`). It is designed to run seamlessly inside a Docker container, making deployment and scaling straightforward.

### 🐳 **Docker Image Features:**

* **Base Image:** `python:3.9-slim` for a lightweight runtime environment.
* **Flask Web App:** Simple HTTP server running on port `5000`.
* **Dockerized:** Easy to deploy and run with Docker.

---

### 🚀 **Quick Start**

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Build the Docker image:**

   ```bash
   docker build -t flask-docker-app .
   ```

3. **Run the container:**

   ```bash
   docker run -d -p 5000:5000 flask-docker-app
   ```

### 🔧 **To pull the image**
 
   ```bash
        docker pull sudheshna998/docker_py:latest
   ```


### 📌 **To run the image**

   ```bash
        docker run -p 5000:5000 sudheshna998/docker_py
   ```


**Access the application:**
   Open your browser and navigate to:

   ```
   http://localhost:5000
   ```

   You should see the message: **Hello, Docker!**





Docker hub:https://hub.docker.com/repository/docker/sudheshna998/docker_py/general



Github :https://github.com/sudheshna-30/docker_py 
