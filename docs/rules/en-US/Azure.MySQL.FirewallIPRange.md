---
severity: Important
category: Security configuration
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.MySQL.FirewallIPRange.md
ms-content-id: d8bf9741-541c-4229-86cb-2e2dad32d9a9
---

# Azure.MySQL.FirewallIPRange

## SYNOPSIS

Determine if there is an excessive number of permitted IP addresses.

## DESCRIPTION

Typically the number of IP address rules permitted through the firewall is minimal, with management connectivity from on-premises and cloud application connectivity the most common.

## RECOMMENDATION

The MySQL server has greater then ten (10) public IP addresses that are permitted network access. Some rules may not be needed or can be reduced.
