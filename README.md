# Krew

> Krew index repo

[Krew](https://krew.sigs.k8s.io/) is the plugin manager for kubectl command-line tool. This repository hosts the krew index for custom kubectl plugins by DodoPizza.

### Requirements:

- [Install kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Install krew](https://krew.sigs.k8s.io/docs/user-guide/setup/install/)

### Install dodopizza's krew plugins

```bash
# Setup index
kubectl krew index add dodopizza https://github.com/dodopizza/krew
kubectl krew update

# List avaliable dodopizza's plugins
kubectl krew search dodopizza/

# Install plugin
kubectl krew install dodopizza/<plugin name>
```
