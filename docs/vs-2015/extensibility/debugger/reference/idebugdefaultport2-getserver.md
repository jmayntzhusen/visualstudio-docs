---
title: "IDebugDefaultPort2::GetServer | Microsoft Docs"
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
  - "IDebugDefaultPort2::GetServer"
helpviewer_keywords: 
  - "IDebugDefaultPort2::GetServer"
ms.assetid: cacb4b74-0f39-471c-af38-54b73f5b2868
caps.latest.revision: 11
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugDefaultPort2::GetServer
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugDefaultPort2::GetServer](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugdefaultport2-getserver).  
  
This method obtains an interface to the server that this port is on.  
  
## Syntax  
  
```cpp  
HRESULT GetServer(  
   IDebugCoreServer3** ppServer  
);  
```  
  
```csharp  
int GetServer(  
   out IDebugCoreServer3 ppServer  
);  
```  
  
#### Parameters  
 `ppServer`  
 [out] Returns an object implementing the [IDebugCoreServer3](../../../extensibility/debugger/reference/idebugcoreserver3.md) interface.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 The [IDebugCoreServer3](../../../extensibility/debugger/reference/idebugcoreserver3.md) is implemented by Visual Studio and represents the server that the port is located on.  
  
## See Also  
 [IDebugDefaultPort2](../../../extensibility/debugger/reference/idebugdefaultport2.md)   
 [IDebugCoreServer3](../../../extensibility/debugger/reference/idebugcoreserver3.md)

