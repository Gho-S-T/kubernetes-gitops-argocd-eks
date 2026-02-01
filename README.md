# kubernetes-gitops-argocd-eks
Production-ready GitOps deployment workflow using ArgoCD, Helm, Terraform, and AWS EKS.
This repository showcases a complete GitOps-driven Kubernetes deployment model.
An EKS cluster is provisioned using Terraform, while applications are deployed using Helm charts with separate environment values.
ArgoCD automates continuous delivery with auto-sync, rollbacks, drift detection, and version-controlled manifests.
CI pipelines ensure secure container builds, vulnerability scanning, and manifest updates before being picked up by ArgoCD.
