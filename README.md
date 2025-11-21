# docker-nginx-devops-project
This project demonstrates a simple Nginx web server using Docker.

**Steps:**
1. Built Docker image using Dockerfile.
2. Added a custom index.html page.
3. Deployed image to Kubernetes with 2 replicas.
4. Exposed service using NodePort.
5. Verified deployment using `kubectl get pods` and `kubectl get svc`.
