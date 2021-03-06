﻿---
title: PowerShell cmdlets reference - Azure Scheduler
description: Learn about PowerShell cmdlets for Azure Scheduler
services: scheduler
ms.service: scheduler
author: derek1ee
ms.author: deli
ms.reviewer: klam
ms.assetid: 9a26c457-d7a1-4e4a-bc79-f26592155218
ms.topic: article
ms.date: 08/18/2016
---

# PowerShell cmdlets reference for Azure Scheduler

> [!IMPORTANT]
> [Azure Logic Apps](../logic-apps/logic-apps-overview.md) 
> is replacing Azure Scheduler, which is being retired. 
> To schedule jobs, [try Azure Logic Apps instead](../scheduler/migrate-from-scheduler-to-logic-apps.md). 

To author scripts for creating and 
managing Scheduler jobs and job collections, 
you can use PowerShell cmdlets. This article lists 
the major [PowerShell cmdlets for Azure Scheduler](/powershell/module/azurerm.scheduler) 
with links to their reference articles. 
To install Azure PowerShell for your Azure subscription, 
see [How to install and configure Azure PowerShell](/powershell/azure/overview). 
For more information about [Azure Resource Manager cmdlets](/powershell/azure/overview), 
see [Using Azure PowerShell with Azure Resource Manager](../powershell-azure-resource-manager.md).

| Cmdlet | Description |
|--------|-------------|
| [Disable-AzureRmSchedulerJobCollection](/powershell/module/azurerm.scheduler/disable-azurermschedulerjobcollection) |Disables a job collection. |
| [Enable-AzureRmSchedulerJobCollection](/powershell/module/azurerm.scheduler/enable-azurermschedulerjobcollection) |Enables a job collection. |
| [Get-AzureRmSchedulerJob](/powershell/module/azurerm.scheduler/get-azurermschedulerjob) |Gets Scheduler jobs. |
| [Get-AzureRmSchedulerJobCollection](/powershell/module/azurerm.scheduler/get-azurermschedulerjobcollection) |Gets job collections. |
| [Get-AzureRmSchedulerJobHistory](/powershell/module/azurerm.scheduler/get-azurermschedulerjobhistory) |Gets job history. |
| [New-AzureRmSchedulerHttpJob](/powershell/module/azurerm.scheduler/new-azurermschedulerhttpjob) |Creates an HTTP job. |
| [New-AzureRmSchedulerJobCollection](/powershell/module/azurerm.scheduler/new-azurermschedulerjobcollection) |Creates a job collection. |
| [New-AzureRmSchedulerServiceBusQueueJob](/powershell/module/azurerm.scheduler/new-azurermschedulerservicebusqueuejob) | Creates a Service Bus queue job. |
| [New-AzureRmSchedulerServiceBusTopicJob](/powershell/module/azurerm.scheduler/new-azurermschedulerservicebustopicjob) |Creates a Service Bus topic job. |
| [New-AzureRmSchedulerStorageQueueJob](/powershell/module/azurerm.scheduler/new-azurermschedulerstoragequeuejob) |Creates a Storage queue job. |
| [Remove-AzureRmSchedulerJob](/powershell/module/azurerm.scheduler/remove-azurermschedulerjob) |Removes a Scheduler job. |
| [Remove-AzureRmSchedulerJobCollection](/powershell/module/azurerm.scheduler/remove-azurermschedulerjobcollection) |Removes a job collection. |
| [Set-AzureRmSchedulerHttpJob](/powershell/module/azurerm.scheduler/set-azurermschedulerhttpjob) |Modifies a Scheduler HTTP job. |
| [Set-AzureRmSchedulerJobCollection](/powershell/module/azurerm.scheduler/set-azurermschedulerjobcollection) |Modifies a job collection. |
| [Set-AzureRmSchedulerServiceBusQueueJob](/powershell/module/azurerm.scheduler/set-azurermschedulerservicebusqueuejob) |Modifies a Service Bus queue job. |
| [Set-AzureRmSchedulerServiceBusTopicJob](/powershell/module/azurerm.scheduler/set-azurermschedulerservicebustopicjob) |Modifies a Service Bus topic job. |
| [Set-AzureRmSchedulerStorageQueueJob](/powershell/module/azurerm.scheduler/set-azurermschedulerstoragequeuejob) |Modifies a Storage queue job. |
||| 

For more details, you can run any of these cmdlets: 

```
Get-Help <cmdlet name> -Detailed
Get-Help <cmdlet name> -Examples
Get-Help <cmdlet name> -Full
```

## See also

* [What is Azure Scheduler?](scheduler-intro.md)
* [Concepts, terminology, and entity hierarchy](scheduler-concepts-terms.md)
* [Create and schedule your first job - Azure portal](scheduler-get-started-portal.md)
* [Azure Scheduler REST API reference](https://msdn.microsoft.com/library/mt629143)
