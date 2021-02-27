[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/flipenergy)](https://artifacthub.io/packages/search?repo=flipenergy)
# Helm chart for deploying Owncast to K8s
**Go to artifact hub for versions.**

A simple helm chart for deploying [Owncast](https://owncast.online/) to k8s.

see [values.yaml](owncast/values.yaml) for configurations.

Install using Helm v3:

```
helm repo add flipenergy https://flipenergy.github.io/k8s-homelab/
helm install my-release flipenergy/owncast
```
