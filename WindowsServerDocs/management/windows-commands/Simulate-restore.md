---
title: Simulate restore
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: d883d94c-3cb1-4848-9d74-1b4378044b31
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# Simulate restore

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Tests writer involvement in restore sessions on the computer without issuing **PreRestore** or **PostRestore** events to writers.  
  
## Syntax  
  
```  
simulate restore  
```  
  
## Remarks  
  
-   **Simulate restore** is used to test whether or not restore with writers can be successful.  
  
-   Before you can use **simulate restore**, you must load a DiskShadow metadata file by using the **load metadata** command. This loads the selected writers and components for the restore.  
  
#### Additional references  
[Command-Line Syntax Key](Command-Line-Syntax-Key.md)  
  
