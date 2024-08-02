---
title: Oracle on Azure IaaS landing zone accelerator
description: Learn how you can use the Oracle on Azure IaaS landing zone accelerator to automate the deployment of an environment capable of hosting Oracle on Azure IaaS Virtual Machines.
author: jfaurskov
ms.author: janfaurs
ms.date: 07/20/2024
ms.topic: conceptual
ms.service: azure-cloud-adoption-framework
ms.subservice: scenario
ms.custom: think-tank
---

# Oracle on Azure IaaS landing zone accelerator

The Oracle on Azure IaaS landing zone accelerator is an open-source collection of Terraform/Bicep and Ansible templates. You can use these templates to automate the deployment of an environment capable of hosting Oracle on Azure Virtual Machines. It can provide a specific architectural approach and reference implementation to prepare your landing zones. The landing zones adhere to the architecture and best practices of the Cloud Adoption Framework.

Customers adopt Oracle on Azure IaaS in various ways. The landing zone accelerator can be adapted to produce an architecture that fits your scenario and puts your organization on a path to sustainable scale.

## Prerequisites

The Oracle on Azure IaaS landing zone accelerator assumes that you already successfully implemented Azure landing zone. However, you can use the Oracle on Azure IaaS landing zone accelerator if your infrastructure doesn't conform to Azure landing zones. For more information, review these articles:

- [Start with Cloud Adoption Framework enterprise-scale landing zones](../../ready/enterprise-scale/index.md)
- [Implement Cloud Adoption Framework enterprise-scale landing zones in Azure](../../ready/enterprise-scale/implementation.md)

## What the Oracle on Azure IaaS landing zone accelerator provides

The landing zone accelerator approach to landing zones provides these assets to support your project:

- A modular approach, so that you can customize environment variables.
- Design guidelines to aid in evaluating critical decisions.
- The landing zone architecture.
- An implementation that includes:
  - A deployable reference capable of creating the environment for your Oracle on Azure IaaS deployment.
  - A Microsoft-recommended Oracle on Azure IaaS reference implementation to test the deployed environment.

## Design guidelines

These articles provide guidelines for creating your landing zone:

- [Network topology and connectivity for Oracle on Azure Virtual Machines landing zone accelerator](./oracle-network-topology.md)
- [Security guidelines for Oracle on Azure Virtual Machines landing zone accelerator](./oracle-security-guideline-landing-zone.md)
- [Business continuity and disaster recovery (BCDR) for Oracle on Azure Virtual Machines landing zone accelerator](./oracle-disaster-recovery-oracle-landing-zone.md)
- [Manage and monitor Oracle workloads on Azure Virtual Machines landing zone accelerator](./oracle-manage-monitor-workload.md)
- [Governance and compliance for Oracle on Azure Virtual Machines landing zone accelerator](./governance-compliance-oracle-landing-zone.md)

## Example conceptual reference architecture

This diagram shows an example conceptual reference architecture illustrating design areas and best practices.

:::image type="content" source="media/index/reference-architecture-oracle-iaas-landing-zone.svg" alt-text="Diagram showing a reference architecture of Oracle on Azure landing zone accelerator." lightbox="media/index/reference-architecture-oracle-iaas-landing-zone.svg":::

## Obtain the Oracle on IaaS landing zone accelerator

The Oracle on IaaS landing zone accelerator is available [here](https://aka.ms/lza/oracle-accelerator).

## Next steps

- Review the Oracle on IaaS landing zone accelerator design areas to make complete considerations and recommendations for your architecture.