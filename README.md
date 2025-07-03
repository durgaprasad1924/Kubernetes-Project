# 3-Tier Web Application Deployment on Kubernetes
This project demonstrates the deployment of a **3-tier architecture** using **Kubernetes** to ensure scalability, reliability, and ease of management. The application is containerized and orchestrated across different tiers: Presentation, Application, and Database.

---

This project showcases the deployment of a traditional 3-tier web application in a cloud-native environment using Kubernetes. 

The architecture includes:

Presentation Layer: NGINX-based frontend serving static web content or SPA (Single Page Application).

Application Layer: Backend API built with PHP running inside a scalable Kubernetes pod.

Data Layer: MySQL running as a stateful container with persistent storage.

The application is containerized using Docker and deployed on Kubernetes clusters with robust networking, load balancing, and persistent storage management. This deployment ensures:

Horizontal scaling of services

Automated recovery of failed pods

Zero-downtime deployment potential

Decoupled service layers for better maintainability

