# minecraft helm chart

<https://github.com/itzg/minecraft-server-charts>
<https://docker-minecraft-server.readthedocs.io/en/latest/>

Create namespace and deploy Minecraft with Helm:

```bash
kubectl create namespace minecraft
helm template minecraft . --namespace minecraft | kubectl apply -f -
```
