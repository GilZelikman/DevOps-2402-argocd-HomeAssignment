# Kubernetes Nginx Web Application

This repository contains Kubernetes manifests to deploy a simple Nginx-based web application.

## Contents

- `deployment.yaml`: Defines the Nginx Deployment
- `service.yaml`: Exposes the Deployment as a Service
- `configmap.yaml`: Provides Nginx configuration

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/k8s-nginx-app.git
   cd k8s-nginx-app
   
2. Apply the manifests:

    ```bash
    kubectl apply -f configmap.yaml
    kubectl apply -f deployment.yaml
    kubectl apply -f service.yaml

3. Verify:
    ```bash
    kubectl get all