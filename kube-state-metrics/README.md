# Installation

Navigate to this directory and run:

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts

helm repo update

helm upgrade --install -f values.yaml -n telemetry ksm prometheus-community/kube-state-metrics
```

 