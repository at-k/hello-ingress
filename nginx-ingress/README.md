# nginx-ingress

## Description
to do

## How to
```
kubectl create namespace ingress

kubectl create configmap nginx-custom-tmpl --from-file=nginx.tmpl -n ingress --dry-run | kubectl apply -f -

helm upgrade --install nginx-ingress stable/nginx-ingress -f values.yaml --namespace ingress --version 0.20.1
```
