---
title: Adgangsstyring med Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 59f1aefaeec3d655b2388b00e7d58a8c2338504b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 01/15/2019
ms.locfileid: "28282373"
---
# <a name="conditional-access-with-intune"></a>Adgangsstyring med Intune

Ved hjælp af **Adgangsstyring** med Intune kræver 3 trin: 
  
- Oprette en **Betinget af adgangspolitik** , der definerer, hvilke ressourcer beskyttes, og hvilke betingelser der skal være opfyldt for at få adgang til disse ressourcer. For eksempel skal en enhed være kompatible inden adgang til virksomhedens e-mail. 
    
- Oprette en **Politik for overholdelse** for at definere indstillinger, der skal opfyldes, før enheden anses for at være kompatible. En enhed skal have en PIN-kode på mindst 6 cifre, før den betragtes kompatible. 
    
- At sikre både **Overholdelse politikker** og **Betinget adgang politikker** er målrettet til de ønskede grupper af brugere. Dette kan kræve oprettelse af bestemte grupper af brugere i Active Directory i Azure. 
    
Læs mere:
  
- [Bedste fremgangsmåder for betinget adgang](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/best-practices)
    
- [Introduktion til betinget adgang](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    
