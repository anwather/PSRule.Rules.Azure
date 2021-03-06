---
severity: Important
category: Security configuration
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.PostgreSQL.FirewallIPRange.md
ms-content-id: fc3b5764-5b4a-4915-9311-75ec6a0d0d55
---

# Azure.PostgreSQL.FirewallIPRange

## SYNOPSIS

Determine if there is an excessive number of permitted IP addresses.

## DESCRIPTION

Typically the number of IP address rules permitted through the firewall is minimal, with management connectivity from on-premises and cloud application connectivity the most common.

## RECOMMENDATION

The PostgreSQL server has greater then ten (10) public IP addresses that are permitted network access. Some rules may not be needed or can be reduced.
