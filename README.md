# Intro

Sample Project using Springboot, Docker and Kubernetes

# Build
mvn clean package
docker build -t appregistryone.azurecr.io/gs-spring-boot-docker .

# Deploy
kubectl apply -f deployment.yaml
