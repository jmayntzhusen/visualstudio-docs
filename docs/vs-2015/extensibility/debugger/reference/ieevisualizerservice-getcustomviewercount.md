---
title: "IEEVisualizerService::GetCustomViewerCount | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IEEVisualizerService::GetCustomViewerCount"
helpviewer_keywords: 
  - "IEEVisualizerService::GetCustomViewerCount method"
ms.assetid: f7b095c2-e538-4352-8cad-d4c6d4f6bdbc
caps.latest.revision: 10
ms.author: "gregvanl"
manager: "ghogen"
---
# IEEVisualizerService::GetCustomViewerCount
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IEEVisualizerService::GetCustomViewerCount](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/ieevisualizerservice-getcustomviewercount).  
  
This method gets the number of type visualizers available from this service.  
  
## Syntax  
  
```cpp  
HRESULT GetCustomViewerCount(  
   ULONG* pcelt  
);  
```  
  
```csharp  
int GetCustomViewerCount(  
   out uint pcelt  
);  
```  
  
#### Parameters  
 `pcelt`  
 [out] Returns the number of type visualizers available.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 [GetCustomViewerCount](../../../extensibility/debugger/reference/idebugproperty3-getcustomviewercount.md) passes the request to this method in its support for type visualizers.  
  
## See Also  
 [IEEVisualizerService](../../../extensibility/debugger/reference/ieevisualizerservice.md)   
 [GetCustomViewerCount](../../../extensibility/debugger/reference/idebugproperty3-getcustomviewercount.md)

