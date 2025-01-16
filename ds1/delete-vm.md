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
---
# How to delete a virtual machine with dependencies on Azure Stack Hub

first paragraph.

second paragraph.

Another paragraph.

Another paragraph.

## Prerequisites

Summary

- item1
- item2
- item3

## Delete a VM with dependencies

When you create a new VM, you typically create a new resource group and put all the dependencies in that resource group. When you want to delete the VM and all of its dependencies, you can delete the resource group. Azure Resource Manager successfully deletes the dependencies. There are times when you cannot delete the resource group to remove the VM; for example, the VM might contain resources that are not dependencies of the VM that you want to keep.

1. item1
2. item2

## Delete a VM with dependencies

When you create a new VM, you typically create a new resource group and put all the dependencies in that resource group. When you want to delete the VM and all of its dependencies, you can delete the resource group. Azure Resource Manager successfully deletes the dependencies. There are times when you cannot delete the resource group to remove the VM; for example, the VM might contain resources that are not dependencies of the VM that you want to keep.

```C++
abc
```

## Related content

- [Create a VM](deploy-foundational-patterns.md)
- [Create a VM with dependencies](deploy-foundational-patterns.md)
- [Create a VM with a custom image](dev-start-vscode-storage.md)
- [Create a VM with a custom image](dev-start-vscode-storage.md)
