# vote-deploy
Kubernetes Deployment Code for Vote App

# Notes for deployment
- argocd vote app 
https://github.com/sfd226/argo-labs


 - Install Kustomize
 curl -s "https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh"  | bash

-- Clone the repo

git clone https://github.com/vikaskhanna1979/argo-labs.git


-- Install argo-rollout controller
kubectl create namespace argo-rollouts
kubectl apply -n argo-rollouts -f https://github.com/argoproj/argo-rollouts/releases/latest/download/install.yaml


-- Install argo-rollout kubectl utilituy
curl -LO https://github.com/argoproj/argo-rollouts/releases/latest/download/kubectl-argo-rollouts-darwin-amd64

