---
severity: Awareness
category: Operations management
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.VM.UniqueDns.md
---

# NICs with custom DNS settings

## SYNOPSIS

Network interfaces (NICs) should inherit DNS from virtual networks.

## DESCRIPTION

By default Virtual machine (VM) NICs automatically use a DNS configuration inherited from the virtual network they connect to. Optionally, DNS servers can be overridden on a per NIC basis with a custom configuration.

Using network interfaces with individual DNS server settings may increase management overhead and complexity.

## RECOMMENDATION

Consider updating NIC DNS server settings to inherit from virtual network.

For more information see [Change DNS servers](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-network-interface#change-dns-servers).
