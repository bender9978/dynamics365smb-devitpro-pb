---
title: "Procedures must not subscribe to CompanyOpen events"
ms.author: solsen
ms.custom: na
ms.date: 04/15/2020
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# AppSourceCop Rule AS0061
Procedures must not subscribe to CompanyOpen events  

## Description
Procedures must not subscribe to CompanyOpen events.

[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Remarks
To improve the login time for [!INCLUDE[d365fin_long_md](../includes/d365fin_long_md.md)], extensions should no longer use the **OnBeforeCompanyOpen** and **OnAfterCompanyOpen** events. For more information, see [Replacing OnBeforeCompanyOpen and OnAfterCompanyOpen](../../compliance/apptest-onbeforecompanyopen.md).

## See Also  
[AppSourceCop Analyzer](appsourcecop.md)  
[Getting Started with AL](../devenv-get-started.md)  
[Developing Extensions](../devenv-dev-overview.md)  