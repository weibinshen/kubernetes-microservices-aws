# Deploying Microservices to AWS using Kubernetes

### Overview
- **workloads.yaml**: Defining all `Deployments`.
- **services.yaml**: Defining all `Services`.
- **storage.yaml** and **storage-aws.yaml**: Defining `PersistentVolumeClaim`, `PersistentVolume` and `StorageClass` for minikube or AWS deployments respectively.
- **mong-stack**: Defining `Deployments` and `Services` for MongoDB.

### Logging, Monitoring and Alerts
- **Logging**: ElasticStack with Fluentd
- **Monitoring**: Prometheus/Grafana
- **Alerts**: Slack channel through Webhook
