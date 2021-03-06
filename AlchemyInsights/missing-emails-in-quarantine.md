---
title: Manglende mails i karantæne
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5668"
- "9002625"
ms.openlocfilehash: 563f76f624f428a46894268b478cf05eb757b497
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 05/19/2021
ms.locfileid: "52539818"
---
# <a name="missing-emails-in-quarantine"></a>Manglende mails i karantæne"

Administratorer kan [få vist, slippe eller slette disse meddelelser.](/microsoft-365/security/office-365-security/manage-quarantined-messages-and-files)

Hvis du vil åbne Security & Compliance Center, skal du gå til [https://protection.office.com](https://protection.office.com/) . Hvis du vil åbne siden Karantæne direkte, skal du gå til [https://protection.office.com/quarantine](https://protection.office.com/quarantine) .  

Du kan søge efter følgende værdier:  

- **Meddelelses-id:** GUID (Globally Unique Identifier) i meddelelsen. Hvis du vælger en meddelelse på listen, vises værdien  **Meddelelses-id**  i pop  **op-ruden**  Detaljer, der vises. Administratorer kan bruge [meddelelsessporing til](/microsoft-365/security/office-365-security/message-trace-scc) at finde meddelelser og deres tilsvarende meddelelses-id-værdier.
- **Afsendermailadresse:** En enkelt afsenders mailadresse.
- **Modtagermailadresse:** En enkelt modtagers mailadresse.
- **Emne:** Brug hele meddelelsens emne. Der er ikke store og små bogstaver i søgningen.

Når du har angivet søgekriterierne, skal du klikke på ![ Opdater knap ](/microsoft-365/media/scc-quarantine-refresh.png?view=o365-worldwide) **Opdater** for at filtrere resultaterne.

De cmdlet'er, du bruger til at få vist og administrere meddelelser og filer i karantæne, er:
- [Delete-QuarantineMessage](/powershell/module/exchange/delete-quarantinemessage)
- [Export-QuarantineMessage](/powershell/module/exchange/export-quarantinemessage)
- [Get-QuarantineMessage](/powershell/module/exchange/get-quarantinemessage)
- [Preview-QuarantineMessage](/powershell/module/exchange/preview-quarantinemessage): Bemærk, at denne cmdlet kun er til meddelelser, ikke malwarefiler fra Microsoft Defender til Office 365 til SharePoint Online, OneDrive for Business eller Teams.
- [Release-QuarantineMessage](/powershell/module/exchange/release-quarantinemessage)