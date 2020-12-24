# minecraft-helm-chart-values
Helm3 Chart Values to be used by my home Minecraft on Kubernetes installation.

# Quick Start
### 1. Add Helm Repository
  ```
  helm repo add itzg https://itzg.github.io/minecraft-server-charts/
  ```
### 2. Clone ```values.yaml``` from this repo
  ```
  helm install --name minecraft -f values.yaml itzg/minecraft
  ```
### 3. DONE
Now, go open minecraft on your other computer and connect to this machine's IP on port ```25565```



## Reference
  * The source Helm chart - [github.com/itzg/minecraft-server-charts](https://github.com/itzg/minecraft-server-charts/tree/master/charts/minecraft)
  * Reference Values file - [values.yaml](https://github.com/itzg/minecraft-server-charts/blob/master/charts/minecraft/values.yaml)
