# kustomize
```
├── ArgoCD
│   └── kustomize-app.yaml
├── README.md
├── base
│   ├── kustomization.yaml
│   └── svc.yaml
└── overlays
    └── dev
        └── kustomization.yaml
## PATH
```
cd overlays/dev/
```
## Kustomize build 
```
kustomize build .
```
