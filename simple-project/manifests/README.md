# Sample K8s Project #

## Creating a simple deployment with node port service

### Commands - deploy:
```
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

### Commands - Verify:
```
kubectl get deploy
kubectl get pods
kubectl get svc
kubectl describe svc myservice
```

### Commands - Access:
```
minikube service myservice
```

### Commands - Delete:
```
kubectl delete -f manifests/
```
> [!NOTE]
> To check all the resources we created, use `kubectl get all`