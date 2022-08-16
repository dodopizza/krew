# krew-index

[Krew](https://krew.sigs.k8s.io/) is the plugin manager for kubectl command-line tool. This repository hosts the krew index for custom kubectl plugins by DodoPizza.

## Install kubectl

<https://kubernetes.io/docs/tasks/tools/install-kubectl/>

## Install krew

<https://krew.sigs.k8s.io/docs/user-guide/setup/install/>

## Configure DodoPizza krew-index

```bash
kubectl krew index add dodopizza https://github.com/dodopizza/krew-index.git
kubectl krew update
```

## Install plugins

To install any plugin from DodoPizza Index, use following command:

```bash
kubectl krew install dodopizza/<plugin-name>
```

For example:

```bash
kubectl krew install dodopizza/app-traffic
kubectl krew install dodopizza/stand
```
