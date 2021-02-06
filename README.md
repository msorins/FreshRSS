# Kubernetes commands

## Create resources
```
kubectl apply -f freshrss-app-namespace.yaml &&\
kubectl apply -f freshrss-app-storage-class.yaml &&\
kubectl apply -f data-persistentvolumeclaim.yaml &&\
kubectl apply -f freshrss-app-deployment.yaml &&\
kubectl apply -f freshrss-app-service.yaml &&\
kubectl apply -f freshrss-app-ingress.yaml
```

## Delete resources
```
kubectl delete -f freshrss-app-namespace.yaml
```