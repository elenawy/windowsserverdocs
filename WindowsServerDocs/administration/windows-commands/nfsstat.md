---
title: nfsstat
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: da7a9768-44bd-404b-97ee-c388d00dc395
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# nfsstat

>Applies To: Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

You can use **nfsstat** to display or reset counts of calls made to Server for NFS.
## Syntax
**nfsstat** [-z]
## Description
When used without the **-z** option, the **nfsstat** command-line utility displays the number of NFS V2, NFS V3, and mount V3 calls made to the server since the counters were set to 0, either when the service started or when the counters were reset using **nfsstat -z**.
