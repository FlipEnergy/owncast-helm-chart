# Helm chart for deploying Owncast to K8s

Bare bones helm chart for deploying [Owncast](https://owncast.online/) to k8s.

see [values.yaml](owncast/values.yaml) for configurations.

Install using Helm v3:

```
helm repo add flipenergy https://flipenergy.github.io/k8s-homelab/
helm install my-release flipenergy/owncast
```
