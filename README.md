# rego-charts
Official Helm charts for rego, https://drorivry.github.io/rego/

- [rego](./charts/rego/)

## Usage

Add this repository using:

```bash
helm repo add rego https://drorivry.github.io/rego-charts/
```

Or by adding the following into `helmfile.yaml`:

```yaml
repositories:
 # ...
 - name: rego
   url: https://drorivry.github.io/rego-charts/
```