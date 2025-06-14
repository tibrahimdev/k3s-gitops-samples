# Surveillance Camera Site

## Quickstart
Apply the 
```bash
cd surveillance-camera-site/apps
kubectl apply -f bootstrap.yaml
```

```bash
cd surveillance-camera-site

# install helm chart
helm install surveillance-camera-site ./bootstrap

# upgrade helm chart
helm upgrade surveillance-camera-site ./bootstrap
```
