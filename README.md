## Sharded k8s Redis Ambassador Pattern

```bash
kubectl create -f redis-shards.yaml

kubectl create -f redis-service.yaml

kubectl create configmap redis --from-file=nutcracker.yaml

kubectl get pods
```
