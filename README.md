## Kubernetes

### Create namespace
$ kubectl apply -f namespace.yml

### Create config name
$ kubectl apply -f config-map.yml
$ kubectl get configMap -n atta

### Create deployment
$ kubectl apply -f deployment.yml