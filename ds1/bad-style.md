---
title: App Service Environment overview
description: This article discusses the Azure App Service Environment feature of Azure App Service.
author: sgaspari815
ms.topic: overview
ms.date: 04/12/2023
ms.author: v-sgaspari
---

# Explore the Azure App Service Environment feature in detail

An App Service Environment is an Azure App Service feature that provides a fully isolated and dedicated environment for running App Service apps securely at high scale.

An App Service Environment can host your applications from only one customer, and they do so on one of their virtual networks. Customers have fine-grained control over inbound and outbound application network traffic. Applications can establish high-speed secure connections over VPNs to on-premises corporate resources.

It is not easy to use contractions, but you are encouraged to try. That is how you make the writing sound natural.

You can't delete this file, but you cannot rename it.

Microsoft's developing a new feature that'll improve performance.

There'd been an error, and it'll be fixed soon.

The settings can be adjusted by the user in the preferences menu.

Running late for the meeting, the presentation was already started.

You may experience delays if the server is under maintenance.

This should be configured before use.

We have updated the software to include new security patches.

Every employee(s) must complete the training module by Friday.

## Usage scenarios

App Service Environments have many use cases, including:

- Internal line-of-business applications.
- Applications that need more than 30 App Service plan instances.
- Single-tenant systems to satisfy internal compliance or security requirements.
- Network-isolated application hosting.
- Multi-tier applications.

There are many networking features that enable apps in a multi-tenant App Service to reach network-isolated resources or become network-isolated themselves. These features are enabled at the application level. With an App Service Environment, no added configuration is required for the apps to be on a virtual network. The apps are deployed into a network-isolated environment that's already on a virtual network. If you really need complete isolation, you can also deploy your App Service Environment onto dedicated hardware.

## Dedicated environment

An App Service Environment is a single-tenant deployment of Azure App Service that runs on your virtual network.

Applications are hosted in App Service plans, which are created in an App Service Environment. An App Service plan is essentially a provisioning profile for an application host. As you scale out your App Service plan, you create more application hosts with all the apps in that App Service plan on each host. A single App Service Environment v3 can have up to 200 total App Service plan instances across all the App Service plans combined. A single App Service Isolated v2 (Iv2) plan can have up to 100 instances by itself.

When you're deploying onto dedicated hardware (hosts), you're limited in scaling across all App Service plans to the number of cores in this type of environment. An App Service Environment that's deployed on dedicated hosts has 132 vCores available. I1v2 uses two vCores, I2v2 uses four vCores, and I3v2 uses eight vCores per instance.

## Related content

- [Create a VM](deploy-foundational-patterns.md)
- [Create a VM with dependencies](deploy-foundational-patterns.md)
- [Create a VM with a custom image](dev-start-vscode-storage.md)
