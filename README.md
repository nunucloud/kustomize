# kustomize
```
├── base
│   ├── deployment.yaml
│   ├── kustomization.yaml
│   ├── secret.yaml
│   └── svc.yaml
└── overlays
    └── dev
        └── kustomization.yaml
```
## PATH
```
cd overlays/dev/
```
## Kustomize build 
```
kustomize build .
```
