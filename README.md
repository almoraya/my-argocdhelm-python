# my-argocdhelm-python
This is a python hello world application deployed with ArgoCD/Helm


<p align="center">
<img  width="40%" height= "40%" src=images/argocdhelm-tree.png alt="Full Airflow Diagram">
</p>

.<br />
├── argocd-helm-dev-python.yaml<br />
├── argocd-helm-prod-python.yaml<br />
├── helm-python-helloworld<br />
│   ├── Chart.yaml<br />
│   ├── templates<br />
│   │   ├── configmap.yaml<br />
│   │   ├── deployment.yaml<br />
│   │   ├── namespace.yaml<br />
│   │   └── service.yaml<br />
│   ├── values-prod.yaml<br />
│   └── values.yaml<br />
└── python-manifests<br />
    └── deployment.yaml<br />
