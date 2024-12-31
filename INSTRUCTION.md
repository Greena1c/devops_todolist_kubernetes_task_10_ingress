kind create cluster --config cluster.yml
kubectl apply -f ingress.yml
kubectl get ingress
kubectl describe deployment todoapp -n default
