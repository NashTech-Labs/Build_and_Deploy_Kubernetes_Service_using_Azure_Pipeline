## Description

Here, In this template, we will build and deploy the Kubernetes service via an Azure CLI and build in tasks for the Azure pipeline build and deployment.


---

#### Pre-Requisite

* Azure Account
* Install Dependencies as mentioned in the pipeline for build and deploy steps.

---

### Steps

* Login into the AZ account using the `az login`.
* Put this terraform code in your workspace to create a cluster.
* Then, run the terraform script to create a cluster using Managed Identity.
* After creating the AKS Cluster use the given pipelines to build and deploy the image and the application inside the Cluster.
---