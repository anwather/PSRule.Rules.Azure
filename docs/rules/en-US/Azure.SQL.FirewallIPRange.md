---
severity: Important
category: Security configuration
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.SQL.FirewallIPRange.md
ms-content-id: a25b1927-f04c-4a6a-8a3d-42d59d4722ff
---

# Azure.SQL.FirewallIPRange

## SYNOPSIS

Determine if there is an excessive number of permitted IP addresses.

## DESCRIPTION

Typically the number of IP address rules permitted through the firewall is minimal, with management connectivity from on-premises and cloud application connectivity the most common.

## RECOMMENDATION

SQL Server has greater then ten (10) public IP addresses that are permitted network access. Some rules may not be needed or can be reduced.
