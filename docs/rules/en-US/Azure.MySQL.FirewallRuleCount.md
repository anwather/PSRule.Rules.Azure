---
severity: Awareness
category: Operations management
online version: https://github.com/BernieWhite/PSRule.Rules.Azure/blob/master/docs/rules/en-US/Azure.MySQL.FirewallRuleCount.md
ms-content-id: 9debdffb-0da1-4b8d-8a17-3f480f1015ec
---

# Azure.MySQL.FirewallRuleCount

## SYNOPSIS

Determine if there is an excessive number of firewall rules.

## DESCRIPTION

Typically the number of firewall rules required is minimal, with management connectivity from on-premises and cloud application connectivity the most common.

## RECOMMENDATION

The MySQL server has greater then ten (10) firewall rules. Some rules may not be needed.
