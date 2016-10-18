---
title: Wbadmin stop job
description: "Windows Commands"
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 3b83b398-39c7-4410-bf17-5c1fb1a4f46d
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---

# Wbadmin stop job

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Cancels the backup or recovery operation that is currently running. Canceled operations cannot be restarted—you must rerun a canceled backup or recovery operation from the beginning.
To stop a backup or recovery operation with this subcommand, you must be a member of the **Backup Operators** group or the **Administrators** group, or you must have been delegated the appropriate authority. In addition, you must run **wbadmin** from an elevated command prompt. (To open an elevated command prompt right-click **Command Prompt** and then click **Run as administrator**.)
## Syntax
```
wbadmin stop job
[-quiet]
```
## Parameters
|Parameter|Description|
|-------------|---------------|
|-quiet|Runs the subcommand with no prompts to the user.|
#### Additional references
-   [Command-Line Syntax Key](Command-Line-Syntax-Key.md)
-   [Wbadmin](Wbadmin.md)