---
title: "Debug Package | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "debugging [Debugging SDK], packages"
ms.assetid: 99947fd4-fb87-4c69-b26c-65634e17d285
caps.latest.revision: 10
ms.author: "gregvanl"
manager: "ghogen"
---
# Debug Package
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [Debug Package](https://docs.microsoft.com/visualstudio/extensibility/debugger/debug-package).  
  
The debug package runs in the Visual Studio shell and handles all of the UI. It consumes the Visual Studio debugging interfaces and communicates with the session debug manager (SDM).  
  
 Break events sent through the SDM switch the debugger from run mode to break mode and change the focus to the program where the break occurred. The debug package tracks the stack frame and thread from the information sent to it by the events.  
  
 The debug package has no language or run-time environment dependencies. It is not necessary to implement or modify the debug package.  
  
 The debug package is implemented by vsdebug.dll.  
  
## See Also  
 [Session Debug Manager](../../extensibility/debugger/session-debug-manager.md)   
 [Stack Frames](../../extensibility/debugger/stack-frames.md)   
 [Threads](../../extensibility/debugger/threads.md)   
 [Debugger Components](../../extensibility/debugger/debugger-components.md)

