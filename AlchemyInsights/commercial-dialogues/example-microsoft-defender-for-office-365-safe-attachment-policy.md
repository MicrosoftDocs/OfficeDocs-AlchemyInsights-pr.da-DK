---
title: Eksempel på politik for Microsoft Defender til Office 365 med sikker vedhæftet fil
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 077762dd37a2974b4e519c1f242fa753623cb49a
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/11/2021
ms.locfileid: "50744527"
---
# <a name="example-microsoft-defender-for-office-365-safe-attachment-policy"></a>Eksempel på politik for Microsoft Defender til Office 365 med sikker vedhæftet fil

Disse indstillinger aktiverer en politik kaldet *Ingen forsinkelser,* der leverer meddelelser med det samme og derefter vedhæftede filer igen, når de er scannet:

- **Navn:** Ingen forsinkelser
- **Beskrivelse:** Leverer straks meddelelser, og vedhæftede filer vedhæftes igen efter scanning.
- **Svar:** Vælg **indstillingen Dynamisk** levering. Du kan finde flere oplysninger i [Dynamisk levering i politikker for sikre vedhæftede filer.](https://go.microsoft.com/fwlink/?linkid=2092328)
- **Afsnittet Omdiriger** vedhæftede filer: Vælg indstillingen til at aktivere **omdirigering,** og angiv derefter mailadressen på den globale Microsoft 365-administrator, sikkerhedsadministrator eller sikkerhedsanalytiker, der vil undersøge skadelige vedhæftede filer.
- **Anvendt på** sektion: Vælg **modtagerdomænet,** og vælg derefter dit domæne. Vælg **Tilføj,** og vælg derefter **OK.** Vælg Gem, når du er **færdig.**

Du kan få mere at vide [under Sikre vedhæftede filer i Microsoft Defender til Office 365.](https://go.microsoft.com/fwlink/?linkid=2092213)
