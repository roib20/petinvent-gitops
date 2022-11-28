# petinvent-gitops

[![License](https://img.shields.io/badge/license-MIT-blue)](https://opensource.org/licenses/MIT)
[![CI Status](https://github.com/roib20/petinvent/actions/workflows/ci-pipeline.yml/badge.svg)](https://github.com/roib20/petinvent/actions/workflows/ci-pipeline.yml)

GitOps repo for [PetInvent](https://github.com/roib20/petinvent/) - for use with Argo CD. App-of-apps can be installed either as a Helm Chart or Kubernetes deployment. For personal use, please fork this repo and make sure to edit the values under `petinvent-gitops/charts/values/`.

An example deployment using GKE and Cloudflare is shown here: [Terraform - Provision a GKE Cluster with Cloudflare Ingress and ArgoCD (deploy-petinvent branch)](https://github.com/roib20/terraform-provision-gke-cloudflare/tree/deploy-petinvent)
