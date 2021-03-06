---
title: Vi beklager, men vi har midlertidige serverproblemer i forbindelse med Microsoft 365-apps
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
- "3420"
- "9001430"
ms.openlocfilehash: 0adf1d66869051b9dd8290ef3466ef9b13aa2d41
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 04/15/2021
ms.locfileid: "51835265"
---
# <a name="fixing-the-microsoft-365-apps-sorry-we-are-having-temporary-server-issues-message"></a>Vi rettelse af meddelelsen "Vi beklager, men vi har midlertidige serverproblemer" i Microsoft 365-apps

Hvis du modtager denne meddelelse, kan du prøve følgende:

1. Kontrollér din firewall, din antivirussoftware og dine proxyindstillinger for at bekræfte, at de ikke blokerer internetadgang til Microsoft 365-apps. Se [URL-adresser og IP-adresseintervaller](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Gå til **Start**  >  **Kør**, og skriv **services.msc**. Sørg for, at følgende tjenester kører alle:
    - Automatisk konfiguration af netværksforbundne enheder
    - Netværklistetjeneste
    - Kendskab til netværksplacering
    - Windows-hændelseslog

Hvis en af disse tjenester ikke kører, kan du prøve at starte den. Hvis du har problemer med at starte tjenesten, skal du køre følgende kommando ved at åbne en kommandoprompt med administratorrettigheder:

**sfc /scannow**

Når denne kommando er fuldført, skal du genstarte computeren.

Du kan finde flere oplysninger [i "Vi beklager, men vi kan ikke oprette forbindelse til din konto. Prøv igen senere"-fejlen, når du aktiverer](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).