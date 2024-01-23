# Argo CD Installation

To bootstrap the cluster Argo CD must be installed manually. After setting up your local Kubernetes context you can run the command listed below to install Argo CD.

```bash
kustomize build ./argo/install | kubectl apply -f -
```
