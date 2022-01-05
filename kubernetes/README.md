
```
kubectl create -n devops secret docker-registry regcred --docker-server=docker.pkg.github.com --docker-username=visarsylejmani --docker-password=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

kubectl create -n devops secret generic mongosecret --from-file=mongodb-secret.yaml
```