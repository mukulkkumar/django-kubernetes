# Django-Kubernetes

## *Commands to execute:-*

To start the minikube single node kubernetes cluster
```
minikube start
```

To create a deployment
```
kubectl create -f django-deployment.yaml
```

To create a service
```
kubectl create -f django-service.yaml
```

To get the url for accessing the service
```
minikube service myapp-service --url
```
