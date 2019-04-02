---
title: 1554 Winsock-fejl 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f44ed42906b85e63f1f694813f54710906969904
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/22/2019
ms.locfileid: "30772436"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="7c7a1-102">Winsock-fejl 10061</span><span class="sxs-lookup"><span data-stu-id="7c7a1-102">Winsock error 10061</span></span>

<span data-ttu-id="7c7a1-103">Denne fejlkode betyder, at Office 365 ikke kunne oprette en TCP socket (connection) med destinationsværten.</span><span class="sxs-lookup"><span data-stu-id="7c7a1-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="7c7a1-104">Den mest sandsynlige årsag til denne fejl er et problem med firewallkonfigurationen af.</span><span class="sxs-lookup"><span data-stu-id="7c7a1-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="7c7a1-105">Du kan løse problemet ved at kontrollere disse indstillinger:</span><span class="sxs-lookup"><span data-stu-id="7c7a1-105">To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="7c7a1-106">Kontrol firewall-konfiguration med oplysninger i [Office 365 URL-adresser og IP-adresseområder](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="7c7a1-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="7c7a1-107">Hvis fejlen er bestemt til Exchange Online beskyttelse (EOP), skal du have tidligere meddelt en ændring i [Exchange Online beskyttelse IP-adresser](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="7c7a1-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="7c7a1-108">Kontroller, at din internetudbyder (ISP) ikke er blokerer for porten.</span><span class="sxs-lookup"><span data-stu-id="7c7a1-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="7c7a1-109">Kontroller smart værten og målcomputerne serverindstillingerne i dine forbindelser.</span><span class="sxs-lookup"><span data-stu-id="7c7a1-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="7c7a1-110">Bemærk, at Office 365 ikke blokerer *indgående* forbindelser på denne måde.</span><span class="sxs-lookup"><span data-stu-id="7c7a1-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  
