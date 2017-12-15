---
title: "Current Branch versions"
titleSuffix: "Configuration Manager"
description: "Review the version history of System Center Configuration Manager, and learn about the phases of service offered."
ms.custom: na
ms.date: 11/22/2017
ms.prod: configuration-manager
ms.reviewer: na
ms.suite: na
ms.technology:
  - configmgr-other
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 35b5baec-d313-46aa-9d14-c443aa0d6c09
caps.latest.revision: 8
author: mestew
ms.author: mstewart
manager: angrobe
robots: noindex,nofollow
---
# Support for System Center Configuration Manager current branch versions

*Applies to: System Center Configuration Manager (Current Branch)*

Microsoft plans to release updates for System Center Configuration Manager current branch a few times per year. For versions of Configuration Manager released prior to 1710, support is for 12 months. Beginning with the 1710 release, each update version remains in support for 18 months from its general availability (GA) release date. Technical support is provided for the entire period of support. However, our support structure is dynamic, evolving into two distinct servicing phases that depend on the availability of the latest current branch version.  

-   Security and Critical Updates servicing phase - When running the latest current branch version of Configuration Manager, you receive both Security and Critical updates.  

-   Security Updates (Only) servicing phase - After the release of a new current branch version, support for older branches will reduce to Security updates only for the remainder of that versions support lifecycle (shown in figure 1).  

 ![CM&#95;Servicing&#95;support&#95;timeline](media/CM_Servicing_support_timeline1.png "CM_Servicing_support_timeline")  
Figure 1. Example of the release cycle overlap for current branch servicing support. This example is for illustration of the cycle, and does not represent actual or expected release dates.

> [!NOTE]  
>  The latest current branch version is always in the Security and Critical Updates servicing phase. This support statement means that if you encounter a code defect that warrants a critical update, you must have the latest current branch version installed in order to receive a fix. All other supported current branch versions are eligible to receive only security updates.
> - For versions 1710 and later, all support ends after the 18-month lifecycle for a current branch version has expired.
> - For versions prior to 1710, support ends after the 12-month lifecycle expires.

> We recommend updating your deployment of Configuration Manager to the latest version before support for your current version expires.

 **Version History**  

|Version |Availability Date |Support End Date|  
|-------------|-----------------------|----------------------|  
|1710|November 20, 2017|May 20, 2019 |
|1706|July 31, 2017|July 31, 2018|
|1702|March 27, 2017|March 27, 2018|
|1610|November 18, 2016|November 18, 2017|
|1606|July 22, 2016| July 22, 2017|
|1602|March 11, 2016|March 11, 2017|
|1511|December 8, 2015|December 8, 2016|  




For information about version numbers, and availability as an in-console update or as a baseline, see [Baseline and update versions](/sccm/core/servers/manage/updates#a-namebkmkbaselinesa-baseline-and-update-versions).
