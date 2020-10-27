## Introduction

This contains the helm chart and the deployment files for argocd to deploy wordprss to your k8 cluster. 


### DB

Agro will select the `db` path for hosting the local maria db 

### wordpress

The `wordpress` directory is for argo to deploy wordpress to the eks 


### Overrides
overrides are done in argo when deploying from the template of this repo

