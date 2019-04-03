# Helm GKE

[![Build Status](https://travis-ci.org/ZubAnt/helm-gke.svg?branch=master)](https://travis-ci.org/ZubAnt/helm-gke)

This image is built to be used for deployments to [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/) via [Helm](https://github.com/kubernetes/helm) package manager.

### Utilities
This Alpine image has the following tools installed:
* `gcloud`
* `kubectl`
* `helm`
* `envsubst`

these are required to deploy to k8s using Helm.
