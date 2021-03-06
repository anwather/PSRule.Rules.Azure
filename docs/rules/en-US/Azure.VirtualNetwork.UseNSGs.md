---
severity: Critical
category: Security configuration
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.VirtualNetwork.UseNSGs.md
---

# Azure.VirtualNetwork.UseNSGs

## SYNOPSIS

Subnets should have NSGs assigned.

## DESCRIPTION

Virtual network subnets should have network security groups (NSGs) assigned.

## RECOMMENDATION

The GatewaySubnet is a special named subnet which does not support NSGs. For all other subnets define and assign a NSG.
