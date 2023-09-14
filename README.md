# Kubernetes Exercise

My collection kubernetes exercise files.
Exercise use convention name, <number-purpose>
- number it show sequential through
- purpose it show the purpose of the exercise
``` bash 
1-simplePod 
1-simplePod/pod.yaml
```


```
kubectl create -f file.yaml
```

kubectl run pod --image image-name
kubectl describe pod pod-name
kubectl delete pod pod-name
## How to rollback deployment
kubectl rollout undo deployment deployment-name

### check deployment status
kubectl rollout status deployment dpeloyment-name
