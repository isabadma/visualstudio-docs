---
title: "How to: Add Activities to the Toolbox (Legacy) | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "reference"
helpviewer_keywords: 
  - "Toolbox, adding activities"
  - "activities, adding to Toolbox"
ms.assetid: b66ea29c-120b-40ba-8a61-c1c8240850fa
caps.latest.revision: 5
author: "ErikRe"
ms.author: "erikre"
manager: "erikre"
ms.workload: 
  - "multiple"
---
# How to: Add Activities to the Toolbox (Legacy)
When building a workflow solution with the legacy [!INCLUDE[wfd1](../workflow-designer/includes/wfd1_md.md)] that targets the [!INCLUDE[netfx35_long](../workflow-designer/includes/netfx35_long_md.md)] or the [!INCLUDE[vstecwinfx](../workflow-designer/includes/vstecwinfx_md.md)], custom activities can be added to the workflow project and their designers placed in the **Toolbox** for easy access. You can also add activities directly to the **Toolbox** from a dynamic-link library (DLL).  
  
### To add an activity to the Toolbox from a DLL  
  
1.  Right-click the Toolbox window surface under **Windows Workflow**, and then click **Choose Items**.  
  
2.  In the **Choose Toolbox Items** dialog box, click the **System.Activities Components** tab, and then click **Browse** from the lower right-hand side of the window.  
  
3.  Select the DLL from the file directory that contains the implementation of the custom activity to add to the **Toolbox**, and then click **Open**.  
  
4.  Click **OK** to finish adding the activity to the Toolbox.  
  
## See Also  
 [Using the Legacy Activity Designer](../workflow-designer/using-the-legacy-activity-designer.md)   
 [Legacy Workflow Activities](../workflow-designer/legacy-workflow-activities.md)