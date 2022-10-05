# argo_playground
Play with argo workflows

## Installation

```sh
helm install \
    --repo=https://argoproj.github.io/argo-helm \
    supervisor argo-workflows \
    --set=singleNamespace=true
```
