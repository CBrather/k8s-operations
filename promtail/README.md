# Installation

Insert a valid API Key to the values.yaml or add the full URI via --set to the helm upgrade command

Navigate to this directory and run:

```
helm repo add grafana https://grafana.github.io/helm-charts

helm repo update

helm upgrade --install -f values.yaml -n telemetry promtail grafana/promtail
```
