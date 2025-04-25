

Проверить контекст Kubernetes. Для этого нужно использовать команду 
``` bash
kubectl config current-context
```

Если в выводе будет показан контекст кластера Minikube, то кластер готов.



```bash
kubectl apply -f deployment.yaml

kubectl port-forward svc/scaletestapp-service 80:80
```