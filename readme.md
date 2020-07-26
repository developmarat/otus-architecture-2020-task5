Архитектура решения

![image](./assets/task5-schema.png)

# Deploy
kubectl apply -f auth/config.yaml -f auth/deployment.yaml -f auth/postgres.yaml -f auth/initdb.yaml -f auth/service.yaml -f auth/ingress.yaml -f app/config.yaml -f app/deployment.yaml -f app/postgres.yaml -f app/initdb.yaml -f app/service.yaml -f app/ingress.yaml
