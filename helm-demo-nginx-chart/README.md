# Helm-demo

Helm demo to istall simple nginx microservice with index.html page.

## Create namespace

```
sudo kubectl create namespace helm-demo
```

## Apply helm-chart

```
helm upgrade --install --name helm-demo helm-demo-nginx-chart/

```
