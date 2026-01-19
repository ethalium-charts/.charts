# Ethalium Charts
Helm repository for all published Ethalium charts. 

## Usage
```bash
helm repo add ethalium http://charts.ethalium.eu/
helm repo update

helm install <releaseName> ethalium/<chart> --version <version>
```

## Charts
<!-- CHARTS:START -->
| Chart | Version&nbsp;(Stable) | Description |
|:------|:-----------------|:------------|
| [`common`](https://github.com/ethalium-charts/common) | `1.0.0` | Shared functions/templates for helm charts |  |
| [`test`](https://github.com/ethalium-charts/test) | `1.0.0` | Shared functions/templates for helm charts |  |
<!-- CHARTS:END -->
