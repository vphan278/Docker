# Flask MySQL Kubernetes Deployment (Docker)

This repository contains a containerized Flask application deployed with MySQL using Docker and Kubernetes.

The project demonstrates how to build a backend service, package it using Docker, and deploy it into a Kubernetes cluster.

--------------------------------------------------

PROJECT STRUCTURE

Docker
└── flask-mysql-k8s
    ├── app
    │   ├── Dockerfile
    │   ├── app.py
    │   └── requirements.txt
    │
    └── k8s
        ├── configmap.yaml
        ├── flask-deployment.yaml
        ├── flask-service.yaml
        ├── mysql-deployment.yaml
        ├── mysql-service.yaml
        └── secret.yaml

--------------------------------------------------

APPLICATION

Flask Application
A simple Python Flask backend application that connects to a MySQL database.

Docker
The application is containerized using Docker to ensure consistent environments.

Kubernetes
Kubernetes configuration files are used to deploy and manage the Flask application and MySQL database.

--------------------------------------------------

KUBERNETES COMPONENTS

Deployment
Defines how the Flask and MySQL containers run in the cluster.

Service
Exposes the application so it can be accessed within the cluster or externally.

ConfigMap
Stores configuration values used by the application.

Secret
Stores sensitive information such as database credentials.

--------------------------------------------------

TECHNOLOGIES USED

Python  
Flask  
Docker  
Kubernetes  
MySQL  

--------------------------------------------------

GOAL

The goal of this project is to practice containerization and container orchestration using Docker and Kubernetes while building a simple backend application.

--------------------------------------------------

AUTHOR

Vinh Tan Phan  
Computer Science Student  
De Anza College
