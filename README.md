# s3proxy-helm-chart
Used to deploy [s3-proxy](https://github.com/gaul/s3proxy).
Heavily inspired from [this s3proxy PR](https://github.com/gaul/s3proxy/pull/428).

## Usage
You can use this helm chart with [helm CLI](https://helm.sh/docs/intro/install/):
```bash
helm install s3proxy oci://ghcr.io/nastaliss/helm/s3-proxy
```

## Publishing
This helm chart automatically publishes to the version specified in `Chart.yaml`:
- `<version>-alpha` on any branch
- `<version>-beta` on the `main` branch
- `<version>` when tagged with `v<version>`
