---
title: 1336 RecoverableItems mappen er fuld
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1336
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: a048949d5284d018303d03aad26cdf26eee2fb5c
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776391"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="0cd28-102">Mappen genoprettelige elementer er fuld</span><span class="sxs-lookup"><span data-stu-id="0cd28-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="0cd28-103">For Exchange Online-postkasser i Office 365 er standard lagergrænsen for mappen genoprettelige elementer 30 GB.</span><span class="sxs-lookup"><span data-stu-id="0cd28-103">For Exchange Online mailboxes in Office 365, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="0cd28-104">Lagergrænsen for mappen genoprettelige elementer øges automatisk til 100 GB, hvis postkassen er placeret på tvister Hold eDiscovery hold eller er tildelt en Office 365-opbevaringspolitik.</span><span class="sxs-lookup"><span data-stu-id="0cd28-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to an Office 365 retention policy.</span></span>
  
<span data-ttu-id="0cd28-105">Når mappen genoprettelige elementer når lagergrænsen, kan postkassen funktionalitet påvirkes på følgende måder:</span><span class="sxs-lookup"><span data-stu-id="0cd28-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>
  
- <span data-ttu-id="0cd28-106">Brugeren kan ikke slette elementer fra postkassen.</span><span class="sxs-lookup"><span data-stu-id="0cd28-106">The user can't delete items from the mailbox.</span></span>
    
- <span data-ttu-id="0cd28-107">En administreret Mappeassistent kan ikke slette elementer baseret på tilbageholdelse kode eller indstillinger for administrerede mapper.</span><span class="sxs-lookup"><span data-stu-id="0cd28-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>
    
- <span data-ttu-id="0cd28-108">Ikke for postkasser, der er enkelt vare genoprettelse aktiveret eller er sat i venteposition, vedligeholde kopier ved skrivning-side beskyttelse processen versioner af elementer, der er redigeret af brugeren.</span><span class="sxs-lookup"><span data-stu-id="0cd28-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>
    
- <span data-ttu-id="0cd28-109">For postkasser, der har en postkasse Overvåg logføring er aktiveret, kan ingen postkasse overvågningsposter log gemmes i audit-undermappe i mappen genoprettelige elementer.</span><span class="sxs-lookup"><span data-stu-id="0cd28-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>
    
<span data-ttu-id="0cd28-110">Administratorer kan bruge til postkasser, der ikke er på hold, den `Search-Mailbox -SearchDumpsterOnly -DeleteContent` i Exchange Online PowerShell til at slette elementer i mappen genoprettelige elementer.</span><span class="sxs-lookup"><span data-stu-id="0cd28-110">For mailboxes that aren't on hold, admins can use the  `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="0cd28-111">Yderligere oplysninger finder du i følgende emner:</span><span class="sxs-lookup"><span data-stu-id="0cd28-111">For more information, see the following topics:</span></span> 
  
- [<span data-ttu-id="0cd28-112">Søge efter og slette meddelelser</span><span class="sxs-lookup"><span data-stu-id="0cd28-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [<span data-ttu-id="0cd28-113">Søg-postkasse</span><span class="sxs-lookup"><span data-stu-id="0cd28-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
<span data-ttu-id="0cd28-114">Administratorer har for postkasser, der er sat på hold, til at fjerne spærringen, før de kan slettede elementer fra mappen genoprettelige elementer.</span><span class="sxs-lookup"><span data-stu-id="0cd28-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="0cd28-115">Yderligere oplysninger finder du under [slette emner i mappen skybaserede postkasser på hold genoprettelige elementer](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="0cd28-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>
  
<span data-ttu-id="0cd28-116">For at forhindre, at mappen genoprettelige elementer bliver fuld, kan administratorer øge lagergrænsen genoprettelige elementer mappe til postkasser på hold og konfigurere en postkasse opbevaringspolitik, som flytter elementer fra mappen genoprettelige elementer til brugerens arkiv postkasse.</span><span class="sxs-lookup"><span data-stu-id="0cd28-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="0cd28-117">Se [øge genoprettelige elementer kvote for postkasser på hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="0cd28-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
  
