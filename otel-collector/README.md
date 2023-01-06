# Installation

Navigate to this directory and run:

```
helm repo add open-telemetry https://open-telemetry.github.io/opentelemetry-helm-charts

helm repo update

helm upgrade --install -f values.yaml -n telemetry otel-collector open-telemetry/opentelemetry-collector
```
