# Azure Cloud Foundation

## Project Overview

This project establishes the foundation of an Azure cloud environment using an Azure for Students subscription.

The objective is to demonstrate cloud resource organization, governance, cost management, and Role-Based Access Control (RBAC).

## Technologies
- Microsoft Azure
- Azure for Students
- Azure Resource Groups
- Azure Resource Tags
- Azure Cost Management
- Azure RBAC
- Microsoft Azure Portal

## 1. Resource Organization

**Resource Group:** `rg-cloudsec-lab`

**Region:** East US

The resource group provides a logical container for organizing and managing related cloud resources.

## 2. Resource Tags

| Tag | Value |
|---|---|
| Environment | Lab |
| Project | CloudSecurity |
| Owner | Student |
| Purpose | SecurityTraining |
| CostCenter | PersonalLearning |

Tags support resource identification, ownership tracking, and cost organization.

## 3. Cost Management

**Budget Name:** `budget-cloudsec-lab`

**Budget Period:** Annual

**Budget Amount:** $100

### Alert Thresholds

| Threshold | Amount |
|---|---:|
| 50% | $50 |
| 75% | $75 |
| 90% | $90 |
| 100% | $100 |

Actual spending alerts are configured to notify the designated email recipient.

Budgets provide spending visibility but do not automatically prevent additional charges.

## 4. Identity and Access Management

Azure Role-Based Access Control (RBAC) was reviewed at the resource group scope.

**Assigned Role:** Owner

**Scope:** `rg-cloudsec-lab`

The Owner role provides full resource management permissions and the ability to assign Azure RBAC roles within the assigned scope.

### RBAC Concepts Reviewed
- Role assignments
- Security principals
- Role definitions
- Resource scope
- Least privilege
- Owner, Contributor, and Reader roles

## 5. Implementation Checklist

- [x] Azure subscription access
- [x] Resource group created
- [x] Resource tags configured
- [x] Annual budget configured
- [x] Budget alert thresholds configured
- [x] RBAC permissions reviewed
- [x] Screenshots uploaded as project evidence
- [x] Infrastructure deployment documented

## 6. Lessons Learned

This project demonstrates foundational Azure administration skills, including resource organization, governance, financial monitoring, and access management.

These capabilities provide the foundation for managing secure and cost-conscious cloud infrastructure.

## Disclaimer

This is an independent educational project using synthetic lab configurations. It is not an official Department of Defense environment and contains no government, employer, classified, or sensitive information.
