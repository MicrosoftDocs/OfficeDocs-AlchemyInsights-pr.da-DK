---
title: 932 opgradering af AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 932
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 0bbb847bb1381330065ebba6e109795908b06490
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/22/2019
ms.locfileid: "30778736"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="202c6-102">Opgradering af Azure AD forbindelse</span><span class="sxs-lookup"><span data-stu-id="202c6-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="202c6-103">Automatisk opgradering er som standard aktiveret for Azure AD Connect, som hjælper med at sikre, at du kører den nyeste version.</span><span class="sxs-lookup"><span data-stu-id="202c6-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="202c6-104">For at kontrollere indstillingerne for automatiske opgradering, kan du bruge cmdlet **Get-ADSyncAutoUpgrade** i Azure AD PowerShell.</span><span class="sxs-lookup"><span data-stu-id="202c6-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="202c6-105">Cmdlet returnerer en af følgende værdier:</span><span class="sxs-lookup"><span data-stu-id="202c6-105">The cmdlet will return one of following values:</span></span> 
  
- <span data-ttu-id="202c6-106">**Aktiveret**: automatisk opgradering er aktiveret.</span><span class="sxs-lookup"><span data-stu-id="202c6-106">**Enabled**: Automatic upgrade is enabled.</span></span> 
    
- <span data-ttu-id="202c6-107">**Deaktiveret**: automatisk opgradering er deaktiveret.</span><span class="sxs-lookup"><span data-stu-id="202c6-107">**Disabled**: Automatic upgrade is disabled.</span></span> 
    
- <span data-ttu-id="202c6-108">**Suspenderet**: systemet ikke længere er berettiget til at modtage automatiske opgraderinger.</span><span class="sxs-lookup"><span data-stu-id="202c6-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="202c6-109">Du kan ikke konfigurere denne værdi; angives af systemet.</span><span class="sxs-lookup"><span data-stu-id="202c6-109">You can't configure this value; it's set by the system.</span></span> 
    
<span data-ttu-id="202c6-110">Yderligere oplysninger finder du under [automatisk opgradering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="202c6-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>
  
<span data-ttu-id="202c6-111">For at hente den nyeste version af Azure AD Connect, skal du gå til [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span><span class="sxs-lookup"><span data-stu-id="202c6-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
  
