# Hola Mundo test #666

A basic Python application running in a Docker container.  
This repository demonstrates how easy it is to create a Docker container for a simple Python app. Once you grasp the concept of this straightforward example, you can easily adapt it for more complex applications.


### Steps to Push the Docker Image to Docker Hub

- Log in to Docker Hub: First, log in to your Docker Hub account by running the following command in your terminal:

```bash
docker login
```

- Build the Docker Image: Make sure you are in the directory containing the Dockerfile, then build the image with this command:

```bash
docker build -t <your-dockerhub-username>/docker-python-helloworld:latest .
```
- Replace <your-dockerhub-username> with your actual Docker Hub username.

- Push the Image to Docker Hub: After successfully building the image, you can upload it to Docker Hub with the following command:

```bash
docker push <your-dockerhub-username>/docker-python-helloworld:latest
```

