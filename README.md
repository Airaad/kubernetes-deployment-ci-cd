# GitOps with Node.js and Argo CD

This repository contains a simple **Node.js application** that demonstrates how to implement **GitOps practices** using a CI/CD pipeline.

## How It Works 🛠️
- On every push, the CI/CD pipeline:
  - Builds and tests the Node.js application.
  - Updates a **separate repository** containing Kubernetes manifest files → [Manifest Repository](https://github.com/Airaad/argocd-ops-sample.git).
- The manifest repository is connected to **Argo CD**, which automatically syncs changes to the Kubernetes cluster.

## Key Features 🚀
- Automated builds, tests, and deployments using CI/CD.
- GitOps workflow for managing Kubernetes applications.
- Continuous synchronization to the cluster via Argo CD.
