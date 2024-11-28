# Kubernetes Monitoring with Prometheus and Grafana on AWS

## Project Overview
Part of my DevSecOps portfolio focusing on setting up monitoring for a Kubernetes cluster on AWS with a Django application deployment.

## Environment Setup
- EKS cluster provisioned on AWS using eksctl
- Django app deployment with replicas and health checks
- High availability configuration with resource management

## Monitoring Stack
### Prometheus Integration
- Installed via Helm in dedicated namespace
- NodeExporter for hardware metrics
- AlertManager integration
- Core cluster component monitoring

### Grafana Visualization
- Dedicated namespace deployment
- Prometheus data source configuration
- EKS cluster monitoring dashboard
- Real-time metrics visualization

### Metrics Collection
- Kubernetes Metrics Server
- Node and pod resource monitoring
- Cluster health tracking

## Local Development
- kubectl port-forwarding setup
- Prometheus and Grafana UI access
- Debugging capabilities

## Project Architecture

![image](https://github.com/user-attachments/assets/370aaa1f-3515-46d3-8524-25b5608f1f65)

## Screenshots
![image](https://github.com/user-attachments/assets/a53ee42b-c9bc-4951-afda-238f6c1eb80f)
![image](https://github.com/user-attachments/assets/586895da-45ae-4068-9c64-cf796ddbb14e)
![image](https://github.com/user-attachments/assets/4d1e9061-af86-4006-b8e1-3e9019edfcaa)
![image](https://github.com/user-attachments/assets/43d97ed7-1782-4768-b3f7-903f00dc4efe)
![image](https://github.com/user-attachments/assets/c5a5badb-a58b-4feb-96fa-81a9551f2389)


