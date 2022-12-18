# Setup Cluster #
Basis ist ein K3s-Cluster. [https://k3s.io/](https://k3s.io/)

## Install ArgoCD ##
`kubectl create namespace argocd`

`kubectl -n argocd apply -k argocd`

## Install Setup App ##
`kubectl -n argocd apply -f setup.yaml`

Cluster isntalliert sich selbst 