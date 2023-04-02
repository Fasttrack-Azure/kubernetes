Welcome to the Kubernetes labs.

These are hands-on resources to help you learn Kubernetes.

## Pre-reqs

 - [Set up Kubernetes and a Git client](./setup/README.md) 
 - Download your repo
    - Open a terminal (PowerShell on Windows; any shell on Linux/macOS) 
    - Run: `git clone https://github.com/courselabs/kubernetes.git`
     - Open the folder: `cd kubernetes`
- _For advanced topics_
    - Install [Helm](https://helm.sh/docs/intro/install/), [ArgoCD](https://argoproj.github.io/argo-cd/getting_started/#2-download-argo-cd-cli) and [k3d](https://k3d.io/v4.4.8/#installation) command line tools
- _Optional_
    - Install [Visual Studio Code](https://code.visualstudio.com) (free - Windows, macOS and Linux) to browse the repo and documentation

# Day 1

## Containerized Applications

- [Running containers](labs/containers/README.md)
- [Constructing the container environment](labs/env/README.md)

## Distributed Container Apps

- [Docker Compose](labs/compose/README.md)
- [Modelling apps with Compose](labs/compose-model/README.md)

## Real-World Containers
  
- [Troubleshooting](troubleshooting/docker/README.md)
- [Sock Shop on Compose](sockshop/docker/README.md) 

## Core Kubernetes

- [Nodes](labs/nodes/README.md)
- [Pods](labs/pods/README.md)
- [Services](labs/services/README.md)
- [Deployments](labs/deployments/README.md)

# Day 2

## Application Modelling

- [ConfigMaps](labs/configmaps/README.md)
- [Secrets](labs/secrets/README.md)
- [PersistentVolumes](labs/persistentvolumes/README.md)
- [Namespaces](labs/namespaces/README.md)


## Advanced Application Modelling

- [DaemonSets](labs/daemonsets/README.md)
- [Ingress](labs/ingress/README.md)
- [Jobs and CronJobs](labs/jobs/README.md)
- [StatefulSets](labs/statefulsets/README.md)

## Operating Kubernetes

- [Production readiness](labs/productionizing/README.md)
- [Monitoring](labs/monitoring/README.md)
- [Logging](labs/logging/README.md)

# Day 3

## Manage and Optimizing Deployments

- [Image optimizing](labs/docker/README.md)
- [BuildKit](labs/buildkit/README.md)
- [Helm](labs/helm/README.md)
- [Rollouts](labs/rollouts/README.md)

## Kubernetes and Azure
- [Deploying to AKS with ACR](https://github.com/Developing-Scalable-Apps-using-Azure/Core-Kubernetes)
- [Integration with Azure Storage and Azure Key Vault](https://github.com/Fasttrack-Azure/Working-with-Azure-Storage-and-AKV)

# Day 4

## Real Kubernetes

- [Troubleshooting](labs/troubleshooting/README.md)
- [Hackathon!](hackathon/README.md)

