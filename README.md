# k8s

## Customer deployment and service ClusterIP

```$bash
kubectl apply -f customer-deployment.yml
```

## Order deployment and service ClusterIP

```$bash
kubectl apply -f order-deployment.yml
```

## frontend deployment and service loadBalancer

```$bash
kubectl apply -f frontend.yml
```
