# This is argo-cd commands
# namespace-created for Argo-DC
kubectl create namespace argocd

# Install Argo-CD components 
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml


