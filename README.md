# mongoexpress
This project demonstrates the deployment of a simple Flask web application alongside MongoDB and Mongo Express, using Docker, Azure Pipelines, and Kubernetes (AKS).
## Project Structure
```
eShop-app/
│
├── app.py                    # Flask application
├── templates/                # HTML templates (index.html, goods.html, services.html)
│
├── kubernetes/
│   ├── mongodb.yaml
│   ├── mongo-secret.yaml
│   ├── mongo-configmap.yaml
│   ├── mongo-express.yaml
│   └── eshop-deployment.yaml
│
├── azure-pipelines.yml       # CI/CD pipeline for Azure DevOps
└── Dockerfile                # Docker config for the Flask app
```

## Features
Flask Web Application with pages: Home, Goods, Services

- MongoDB database deployment

- Mongo Express UI for MongoDB management

- Dockerized app for containerization

- CI/CD with Azure DevOps

- Deployed to AKS (Azure Kubernetes Service)

