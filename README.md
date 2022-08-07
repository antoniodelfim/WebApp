# WebApp ASP.NET Core .NET 6.0

● Kubernetes - GKE 

● [Crossplane](https://crossplane.io/)

Use Helm 3 to install the latest official stable release of Crossplane:

kubectl create namespace crossplane-system

helm repo add crossplane-stable https://charts.crossplane.io/stable

helm repo update

helm install crossplane --namespace crossplane-system crossplane-stable/crossplane


# Check Crossplane Status
helm list -n crossplane-system
kubectl get all -n crossplane-system

● [Argo CD](https://argo-cd.readthedocs.io/en/stable/).

● Pipeline de deployment no github Actions.

● Certificado para o cluster LetsEncrypt com um DNS válido para as aplicações.
