# This is a Java SpringBoot Application

# Write a dockerfile for creating  docker image
    -----> docker build -t myapp .

# Write yaml file for deploy into kubernetes
    -----> kubectl apply -f deployment.yaml 
    -----> kubectl apply -f service.yaml
    
# To check pods info
    -----> Kubectl get pods
    
# To get service 
    -----> minikube service backend-service
