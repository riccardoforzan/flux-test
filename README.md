# flux-test

Install the latest release of flux

```sh
helm install -n flux-system --create-namespace flux oci://ghcr.io/fluxcd-community/charts/flux2
```

Then apply the configuration with `kubectl apply -f flux-init.yaml`

This enables all flux kustomization defined in [flux-system](./flux-system/)
