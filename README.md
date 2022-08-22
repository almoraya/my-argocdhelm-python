# my-argocdhelm-python
This is a python hello world application deployed with ArgoCD/Helm


<p align="center">
<img  width="40%" height= "40%" src=images/argocdhelm-tree.png alt="Full Airflow Diagram">
</p>

.
├── argocd-helm-dev-python.yaml
├── argocd-helm-prod-python.yaml
├── helm-python-helloworld
│   ├── Chart.yaml
│   ├── templates
│   │   ├── configmap.yaml
│   │   ├── deployment.yaml
│   │   ├── namespace.yaml
│   │   └── service.yaml
│   ├── values-prod.yaml
│   └── values.yaml
└── python-manifests
    └── deployment.yaml
