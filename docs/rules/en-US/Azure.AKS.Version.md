---
severity: Important
category: Operations management
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.AKS.Version.md
ms-content-id: b0bd4e66-af2f-4d0a-82ae-e4738418bb7e
---

# Upgrade Kubernetes version

## SYNOPSIS

AKS control plane and nodes pools should use a current stable release.

## DESCRIPTION

The AKS support policy for Kubernetes is include N-2 stable minor releases.
Additionally two patch releases for each minor version are supported.

A list of available Kubernetes versions can be found using the `az aks get-versions -o table --location <location>` CLI command.

## RECOMMENDATION

Consider upgrading AKS control plan and nodes pools to the latest stable version of Kubernetes.

## LINKS

- [Supported Kubernetes versions in Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/supported-kubernetes-versions).
- [Support policies for Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/support-policies)
