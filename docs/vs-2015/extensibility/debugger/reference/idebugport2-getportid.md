---
title: "IDebugPort2::GetPortId | Microsoft Docs"
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
  - "IDebugPort2::GetPortId"
helpviewer_keywords: 
  - "IDebugPort2::GetPortId"
ms.assetid: 837cb924-c113-4224-aa86-3e02b33dfa70
caps.latest.revision: 11
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugPort2::GetPortId
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugPort2::GetPortId](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugport2-getportid).  
  
Gets the port identifier.  
  
## Syntax  
  
```cpp#  
HRESULT GetPortId(   
   GUID* pguidPort  
);  
```  
  
```csharp  
int GetPortId(   
   out Guid pguidPort  
);  
```  
  
#### Parameters  
 `pguidPort`  
 [out] Returns the GUID that identifies the port.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugPort2](../../../extensibility/debugger/reference/idebugport2.md)

