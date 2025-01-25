Run this command once your brought the application and all other kubernetes workloads and make sure all are running state.

kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml