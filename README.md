# NGINX Deployment on Kubernetes

This is my first Kubernetes project! 🎉  
It deploys an NGINX server on a local Kubernetes cluster using Minikube.

## How to Run

1. Start minikube:
   minikube start
2. Deploy:
   kubectl apply -f nginx-deployment.yaml
3. Expose the service:
   kubectl expose deployment nginx-deployment --type=NodePort --port=80
   minikube service nginx-deployment

<img width="1039" alt="Screenshot 2025-05-30 at 10 42 51 PM" src="https://github.com/user-attachments/assets/cbb5a492-afee-4f06-b997-906c10eacf49" />
