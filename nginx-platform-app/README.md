# Nginx Platform Application Example

This example demonstrates a production-style Kubernetes deployment using Nginx with:

- Resource requests and limits
- Readiness and liveness probes
- Service exposure using ClusterIP
- Clean label/selector architecture
- Separation of concerns (deployment + service)

## Files
- `deployment.yaml` – Application deployment configuration
- `service.yaml` – Internal service exposure

## How to deploy

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

