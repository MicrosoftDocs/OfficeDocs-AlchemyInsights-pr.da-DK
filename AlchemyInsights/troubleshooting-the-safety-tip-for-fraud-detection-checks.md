---
title: Fejlfinding i forbindelse med sikkerhed tip til afsløring af svig kontrollerer
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 24842e8cc5c6e47fb0eb637e6a3211637ede1ed8
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 01/15/2019
ms.locfileid: "28283216"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="ee4e0-102">Fejlfinding i forbindelse med sikkerhed tip til afsløring af svig kontrollerer</span><span class="sxs-lookup"><span data-stu-id="ee4e0-102">Troubleshooting the safety tip for fraud detection checks</span></span>

<span data-ttu-id="ee4e0-p101">Hvis du får en sikkerhed tip, der siger "afsenderen mislykkedes vores kontrol til påvisning af svig og muligvis ikke som de ser ud til at være", og derefter afsenderen kunne bestå enten DKIM eller SPF godkendelseskontrol. Den bedste måde at løse dette problem er for afsenderen at godkende sig selv. Hvis afsenderen sender på dine vegne, skal du autorisere dem ved at føje afsenderens IP-adresse til din SPF-post.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-p101">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks. The best method to resolve this is for the sender to authorize themselves. If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="ee4e0-106">Yderligere oplysninger finder du under [fejlfinding rødt (mistænkelige) sikkerhed tip til afsløring af svig kontrollerer](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .</span><span class="sxs-lookup"><span data-stu-id="ee4e0-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="ee4e0-107">Her er nogle links, der kan hjælpe:</span><span class="sxs-lookup"><span data-stu-id="ee4e0-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="ee4e0-108">Hvordan Office 365 bruger afsender policy framework (SPF) for at forhindre spoofing (forfalskning)</span><span class="sxs-lookup"><span data-stu-id="ee4e0-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/en-us/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- [<span data-ttu-id="ee4e0-109">Oprette SPF i Office 365 for at forhindre spoofing (forfalskning)</span><span class="sxs-lookup"><span data-stu-id="ee4e0-109">Set up SPF in Office 365 to help prevent spoofing</span></span>](https://docs.microsoft.com/en-us/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    
