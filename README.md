Objective
Deploy an NGINX server on Kubernetes using the following components:

Deployment: To manage the application replicas.
Service: To expose the deployment within the cluster.
Ingress: To expose the service externally.

Directory Structure: 
.
├── deployment.yaml
├── service.yaml
└── ingress.yaml


Kubernetes CLI Commands
1. Create the Deployment
   kubectl apply -f deployment.yaml
2. Create the Service
   kubectl apply -f service.yaml
3. Create the Ingress
   kubectl apply -f ingress.yaml
