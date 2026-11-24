# Azure Foundation – Implementation Evidence

This folder contains screenshots documenting the Azure Foundation project configurations and implementation.

## 1. Resource Group Tagging

**Screenshot:** `resource-group-tags.png`

**Description:**

Demonstrates the metadata tags configured on the `rg-cloudsec-lab` resource group.

The tags identify the environment, project, owner, purpose, and cost center.

**Purpose:**

Resource tagging supports cloud governance, resource organization, cost tracking, and management.

---

## 2. Azure Cost Management and Budget Alerts

**Screenshot:** `budget-configuration-and-alerts.png`

**Description:**

Demonstrates the annual $100 Azure budget configured for the Azure for Students subscription, including spending notification thresholds at 50%, 75%, 90%, and 100%.

**Purpose:**

Budget alerts provide visibility into cloud spending and help identify potential cost overruns.

*Note: Azure budget alerts provide notifications; they do not automatically stop resource spending.*

---

## 3. Role-Based Access Control (RBAC)

**Screenshot:** `rbac-owner-role.png`

**Description:**

Demonstrates the subscription-level Owner role assignment for the lab administrator account.

| Configuration | Value |
|---|---|
| Role | Owner |
| Scope | Azure for Students Subscription |
| Status | Active |
| Assignment Type | Permanent |

**Purpose:**

Azure RBAC controls access to cloud resources by defining which actions users can perform and at what scope.

---

## Evidence Summary

These screenshots document the initial Azure Foundation configuration, including resource tagging, cost management, budget monitoring, and subscription-level access control.
