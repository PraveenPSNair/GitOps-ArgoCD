# GitOps-ArgoCD

kubectl get pods -n argocd
kubectl get svc -n argocd
kubectl edit svc argocd-server -n argocd 

minikube service list -n argocd
minikube service argocd-server -n argocd  # To expose and create a tunnel
