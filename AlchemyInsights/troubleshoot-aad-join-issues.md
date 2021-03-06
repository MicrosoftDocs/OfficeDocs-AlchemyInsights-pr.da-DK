---
title: Fejlfinding af problemer med Azure AD-joinforbindelse
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/24/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003246"
- "6157"
ms.openlocfilehash: 0e9f7c95cf522340e9976f668c1d1a9eaff71910
ms.sourcegitcommit: db908b3da2c7a6508a77bf4f2c80afb294fadbd1
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/29/2021
ms.locfileid: "51404629"
---
# <a name="troubleshoot-azure-ad-join-issues"></a>Fejlfinding af problemer med Azure AD-joinforbindelse

1. Hvis du konfigurerer enhedsregistreringer for første gang, skal du kontrollere, at du har gennemgået Introduktion til enhedshåndtering i [Azure Active Directory,](https://docs.microsoft.com/azure/active-directory/devices/overview) der kan hjælpe dig med at få enheder under kontrol til Azure AD. 
1. Hvis du registrerer enheder direkte i Azure AD og tilmelder dem i Intune, skal du først sikre [](https://docs.microsoft.com/mem/intune/fundamentals/licenses-assign) dig, at du har konfigureret [Intune](https://docs.microsoft.com/mem/intune/enrollment/device-enrollment) og licensering.
1. Sørg for, at du er autoriseret til at udføre handlinger i Azure AD. Kun en global administrator i Azure AD kan administrere indstillingerne for enhedsregistreringer.
1. Hvis du vil udføre implementering af Azure AD-joinforbindelse, skal [du se Planlæg Azure AD Join.](https://docs.microsoft.com/azure/active-directory/devices/azureadjoin-plan)

Hvis du vil have mere at vide om at løse almindelige problemer med Azure AD-joinforbindelse, skal du se Ofte stillede spørgsmål om [Azure Ad Join](https://docs.microsoft.com/azure/active-directory/devices/faq#azure-ad-join-faq) og for Windows 10 Pro-enhed. Kan ikke deltage i Windows [10 Pro-maskine](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_install-mso_win10-mso_365hp/unable-to-join-windows-10-pro-machine-to-azure-ad/abb1ca7d-b317-45ec-a628-e1c10eae2900) i Azure AD – skal opgraderes til – Microsoft Community
