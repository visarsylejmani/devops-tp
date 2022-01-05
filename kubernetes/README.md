
# TP - Partie 2 - kubernetes

:construction_worker: Nour :construction_worker: Sylejmani

```sh
kubectl create namespace devops
```

```sh
kubectl create -n devops secret docker-registry regcred --docker-server=docker.pkg.github.com
```

```sh
kubectl create -n devops -f .\kubernetes.yaml
```

```sh
kubectl proxy --port=8080
```

:earth_africa: http://127.0.0.1:8080/api/v1/namespaces/devops/services/node/proxy
