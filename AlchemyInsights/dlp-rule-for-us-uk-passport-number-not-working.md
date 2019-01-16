---
title: DLP-regel for US / UK pasnummer virker ikke
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 716d1030d93ce006c36d7925fb132e974ae8feb4
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 01/15/2019
ms.locfileid: "28283456"
---
Du har problemer med **Data tab forebyggelse (DLP)** ikke arbejder for indhold, der indeholder en **US / UK pasnummer** ved brug af typen DLP følsomme oplysninger i O365? Hvis det er tilfældet, skal du sørge for dit indhold indeholder de nødvendige oplysninger for det DLP-Gruppepolitik er søger efter, når det evalueres. 
  
Eksempelvis en **US / UK pasnummer** politik, der er konfigureret med et konfidensniveau på 75%, følgende evalueres og skal registreres for reglen, der udløser 
  
- **[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Ni cifre 
    
- **[Mønster:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Ni på hinanden følgende cifre 
    
- **[Kontrolsum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Nej, der er ingen kontrolsum 
    
- **[Definition:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** En DLP-politik er 75% sikker på, at det har fundet denne type af følsomme oplysninger, hvis, inden for en afstand af 300 tegn: 
    
  - Funktionen Func_usa_uk_passport søger efter indhold, der svarer til mønsteret.
    
  - Der findes et nøgleord fra Keyword_passport.
    
    For eksempel vil udløse følgende eksempel den **US / UK pasnummer** politik: amerikansk pas tallet 123456789 
    
Yderligere oplysninger om, hvad der kræves for en Amerikansk / UK pasnummer skal registreres for dit indhold, se følgende afsnit i denne artikel: [hvad de følsomme oplysningstyper udseende til USA / UK pasnummer](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
Bruge en anden indbygget følsomme oplysninger, se følgende artikel for at få oplysninger om hvad der kræves for andre typer: [Hvad den følsomme oplysningstyper søge efter](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  
