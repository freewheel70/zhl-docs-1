---
title: Delete VM with dependencies on Azure Stack Hub 
description: How to delete a VM (virtual machine) with dependencies on Azure Stack Hub
author: sethmanheim

ms.topic: how-to
ms.custom:
  - devx-track-azurepowershell
ms.date: 02/13/2023
ms.author: sethm
ms.reviewer: thoroet
ms.lastreviewed: 5/20/2021

# Intent: As an Azure Stack user, I want to delete a VM with dependencies in Azure Stack Hub.
# Keyword: virtual machine delete
---

# How to delete a virtual machine with dependencies on Azure Stack Hub

In this article, you can find the steps to remove a virtual machine (VM) and its dependencies from Azure Stack Hub.

If you remove a VM from Azure Stack Hub, the component dependencies; that is, data disks, virtual network interfaces, and diagnostic containers, remain in the resource group. These items won't be automatically deleted along with your OS disk. Follow the steps in this article to remove your OS disc and component dependencies.

Another paragraph.

## Prerequisites

Summary

- item
- item
- item

## Delete a VM with dependencies

When you create a new VM, you typically create a new resource group and put all the dependencies in that resource group. When you want to delete the VM and all of its dependencies, you can delete the resource group. Azure Resource Manager successfully deletes the dependencies. There are times when you cannot delete the resource group to remove the VM; for example, the VM might contain resources that are not dependencies of the VM that you want to keep.

1. item
1. item

## Fix a VM with dependencies

When you create a new VM, you typically create a new resource group and put all the dependencies in that resource group. When you want to delete the VM and all of its dependencies, you can delete the resource group. Azure Resource Manager successfully deletes the dependencies. There are times when you cannot delete the resource group to remove the VM; for example, the VM might contain resources that are not dependencies of the VM that you want to keep.

1. item
1. item

## Code a VM with dependencies

When you create a new VM, you typically create a new resource group and put all the dependencies in that resource group. When you want to delete the VM and all of its dependencies, you can delete the resource group. Azure Resource Manager successfully deletes the dependencies. There are times when you cannot delete the resource group to remove the VM; for example, the VM might contain resources that are not dependencies of the VM that you want to keep.

```python
print("this is python")
```

## Related content

- [Create a VM](deploy-foundational-patterns.md)
- [Create a VM with dependencies](deploy-foundational-patterns.md)
- [Create a VM with a custom image](dev-start-vscode-storage.md)
