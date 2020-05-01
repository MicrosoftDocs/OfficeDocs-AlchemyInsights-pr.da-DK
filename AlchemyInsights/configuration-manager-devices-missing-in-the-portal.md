---
title: Der mangler Configuration Manager-enheder i portalen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: 7a11ad3c6970be2c52a7cf0696bd3810b9bd665a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: da-DK
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789703"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a><span data-ttu-id="5b8a6-102">Der mangler Configuration Manager-enheder i portalen</span><span class="sxs-lookup"><span data-stu-id="5b8a6-102">Configuration Manager devices missing in the portal</span></span>

<span data-ttu-id="5b8a6-103">For at enhedssynkronisering kan fungere, skal du [nødvendige internetslutpunkter](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) kunne nås fra den lokale server, der hoster rollen Tjenesteforbindelsespunkt.</span><span class="sxs-lookup"><span data-stu-id="5b8a6-103">For device sync to work, [required internet endpoints](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) must be reachable from the on-premise server hosting the Service Connection Point role.</span></span> <span data-ttu-id="5b8a6-104">Hvis du vil foretage fejlfinding af enhedssynkronisering, skal du se **CMGatewaySyncUploadWorker.log**, der er placeret på tjenesteforbindelsespunktet.</span><span class="sxs-lookup"><span data-stu-id="5b8a6-104">To troubleshoot device sync, please review the **CMGatewaySyncUploadWorker.log** located on the service connection point.</span></span>

<span data-ttu-id="5b8a6-105">Få mere at vide om [Tilknytning af lejer i Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span><span class="sxs-lookup"><span data-stu-id="5b8a6-105">Learn more about [Tenant attach in Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span></span>