```
kubectl apply -f ingress-nginx/configmap.yml
kubectl apply -f ingress-nginx/loadbalancer.yml
kubectl patch deployment ingress-nginx-controller -n ingress-nginx --patch-file ingress-nginx/deployment.yaml
```
