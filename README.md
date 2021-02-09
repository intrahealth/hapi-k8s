# Simple HAPI on Kubernetes w/Postgres

> Before using in production, remove load balancer in fhir-service to ensure that the HAPI QUI and FHIR endpoint are not exposed to the public.

```
kubectl apply -f ./main
```

Visit: http://localhost:8080 and http://localhost:8080/fhir

```
kubectl delete -f ./main
```