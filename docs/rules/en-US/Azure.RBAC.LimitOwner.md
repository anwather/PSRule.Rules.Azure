---
severity: Important
category: Security operations
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.RBAC.LimitOwner.md
ms-content-id: 43075204-e28b-46a0-90a0-ea5c3b74e9ab
---

# Limit Owner role

## SYNOPSIS

Limit the number of subscription Owners.

## DESCRIPTION

Azure provides a flexible delegation model using Role-Base Access Control (RBAC) that allows administrators to grant fine grained permissions using roles to Azure resources. Over 100 built-in roles exist, and custom roles can be created to perform specific tasks. Permissions can be scoped to management group, subscription, resource group or individual resources.

The Owner role provides the ability to create, delete, update and configure permissions for any resource. When assigned at the subscription scope, these permissions apply to the whole subscription and all resources in the subscription.

## RECOMMENDATION

Consider limiting the number of subscription Owners by using a more specific role or scoping Owner permission to a Resource Group.
