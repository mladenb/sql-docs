---
title: "Development, Test, and Production Databases (Visual Database Tools) | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dbe-cross-instance"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "production databases [SQL Server]"
  - "testing databases"
  - "database testing [SQL Server]"
ms.assetid: cb403330-8cbe-41c6-bd23-bc432d50f173
caps.latest.revision: 9
author: "JennieHubbard"
ms.author: "jhubbard"
manager: "jhubbard"
---
# Development, Test, and Production Databases (Visual Database Tools)
  If you have two databases with identical structure, you can make changes in one database and propagate those changes to the other. For example, if you have a personal development database and a group-wide test database, you can modify the development database, then propagate those changes to the test database.  
  
 To accomplish this, perform all the modifications in a single session with the development database, create a Change Script of your session and later run the script on the test database.  
  
## See Also  
 [Multiuser Environments &#40;Visual Database Tools&#41;](visual-database-tools.md)  
  
  