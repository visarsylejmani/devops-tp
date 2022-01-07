
# TP - Partie 2 - kubernetes

:construction_worker: Nour :construction_worker: Sylejmani

```sh
kubectl create -f .\kubernetes.yaml
```

```sh
kubectl get pods -n devops
```

```sh
kubectl proxy --port=8080
```

:earth_africa: http://127.0.0.1:8080/api/v1/namespaces/devops/services/node/proxy/

```sh
kubectl delete -n devops
```