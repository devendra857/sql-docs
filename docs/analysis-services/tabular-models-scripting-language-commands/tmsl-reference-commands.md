---
title: "Commands in Tabular Model Scripting Language (TMSL) | Microsoft Docs"
ms.date: 05/07/2018
ms.prod: sql
ms.technology: analysis-services
ms.component: tabular-models
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# TMSL Reference - Commands
[!INCLUDE[ssas-appliesto-sqlas-aas](../../includes/ssas-appliesto-sqlas-aas.md)]
  You can execute commands on an XMLA endpoint, formulating object definitions in JSON using the Tabular Model Scripting Language (TMSL), against Tabular model databases.   See [Object Definitions in Tabular Model Scripting Language &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-objects/tmsl-reference-tabular-objects.md) for a list of objects used with the following commands.  
  
## Object operations  
  
|||  
|-|-|  
|[Alter command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/alter-command-tmsl.md)|Make inline modifications to an object without having to specify the full definition.|  
|[Create command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/create-command-tmsl.md)|Creates a new object, including its descendants.|  
|[CreateOrReplace command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/createorreplace-command-tmsl.md)|Create or replace parts of an object definition. The full definition must be provided.|  
|[Delete command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/delete-command-tmsl.md)|Delete an object, including its descendants.|  
  
## Data refresh operations  
  
|||  
|-|-|  
|[MergePartitions command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/mergepartitions-command-tmsl.md)|Merge a target partition into a source, and delete the target.|  
|[Refresh command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/refresh-command-tmsl.md)|Process a database, table, or partition.|  
  
## Scripting  
  
|||  
|-|-|  
|[Sequence command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/sequence-command-tmsl.md)|Batch operations sequentially or in parallel|  
  
## Database management operations  
  
|||  
|-|-|  
|[Attach command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/attach-command-tmsl.md)|Adds a file to the server.|  
|[Detach command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/detach-command-tmsl.md)|Removes a file from the servers.|  
|[Backup command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/backup-command-tmsl.md)|Creates a backup file of a database.|  
|[Restore command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/restore-command-tmsl.md)|Restores database to the server.|  
|[Synchronize command &#40;TMSL&#41;](../../analysis-services/tabular-models-scripting-language-commands/synchronize-command-tmsl.md)|Synchronizes an Analysis Services database with another existing database.|  
  
## See Also  
 [Tabular Model Scripting Language &#40;TMSL&#41; Reference](../../analysis-services/tabular-model-scripting-language-tmsl-reference.md)   
 [Install Analysis Services data providers &#40;AMO, ADOMD.NET, MSOLAP&#41;](../../analysis-services/instances/install-windows/install-analysis-services-data-providers-amo-adomd-net-msolap.md)   
 [Compatibility Level for Tabular models in Analysis Services](../../analysis-services/tabular-models/compatibility-level-for-tabular-models-in-analysis-services.md)  
  
  
