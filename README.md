# WordPress on Google Kubernetes Engine (GKE) – Beginner Project

This project demonstrates how to deploy **WordPress on Google Kubernetes Engine (GKE)** using **Kubernetes manifests (YAML)**.

It is designed for **beginners** who are new to:
- Google Cloud Platform (GCP)
- Google Kubernetes Engine (GKE)
- Kubernetes

By the end of this project, you will have a **publicly accessible WordPress website running on GKE**.

---

## 🏗 Architecture Overview

The deployment consists of:

- **WordPress** (PHP + Apache) running in a Kubernetes Pod
- **MySQL 8.0** database running in a separate Pod
- **Kubernetes Services** for internal and external access
- **LoadBalancer Service** to expose WordPress to the internet
- **Kubernetes Secret** to store the database password securely

