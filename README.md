# terraform-kubeflow-local

This repository contains a Terraform module that deploys Kubeflow on a local Kubernetes cluster.

## Requirements

- [Terraform](https://www.terraform.io/downloads.html)
- Local Kubernetes cluster (e.g. [Minikube](https://minikube.sigs.k8s.io/docs/start/))
- [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Kustomize](https://kubectl.docs.kubernetes.io/installation/kustomize/)

## Usage

```
cd terraform-kubeflow-local
terraform init
terraform plan
terraform apply
```



