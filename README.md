## kubectl-resourceful

This Kubernetes plugin intended to increase allocation of the memory and CPU
resources  for the containers deployed to the kubernetes cluster.

### Use
```bash
kubectl resourceful --set-cpu=200m --set-memory=256Mi -n kube-system -c coredns
```
### Installation
#### Requirements

1. Kubernetes v0.30.0
2. kubectl v1.12.2
3. Python 3
4. Python module _kubernetes_

#### Actual installation

Place _kubectl-resourceful_ somewhere in the PATH, for example, _/usr/local/bin_
