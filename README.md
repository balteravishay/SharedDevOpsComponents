# Introduction 
This repository demonstrates how to enable cross-team sharing of Azure DevOps pipelines using templating and parameter injection.
Please read [this]() blog for more information about the concept.

# Getting Started

## Pre-requisites
1. An Azure DevOps project
2. Azure Subscription
3. Azure Container Registry
4. Azure Kubernetes Services

## Working with the code sample
1. Clone the repo.
2. Import the pipelines in [the documentation folder](./docs/demo/nodejs/.azure/ci-azure-pipelines.yml) to Azure Pipelines.
3. Create Environment targeting the AKS cluster.
4. Create Service Connection for Azure Subscription and Azure Container Registry.
3. Provide your environment's values to the pipelines parameter.
