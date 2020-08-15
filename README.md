# Intro

Sample Project using Springboot, Docker and Kubernetes

# Build
```bash
mvn clean package
```
```bash
docker build -t appregistryone.azurecr.io/gs-spring-boot-docker .
```


# Deploy
kubectl apply -f deployment.yaml
