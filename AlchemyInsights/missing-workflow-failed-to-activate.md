---
title: Manglende arbejdsproces kunne ikke aktiveres
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 604dc770c5c14ded6a8de1cec9e311b03b69f094
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 09/14/2020
ms.locfileid: "47667080"
---
# <a name="missing-workflow-failed-to-activate"></a>Manglende arbejdsproces kunne ikke aktiveres

I en Microsoft SharePoint-gruppe af websteder kan du ikke tilføje en globalt genbrugelig arbejdsproces (f. eks "godkendelse-SharePoint 2010") på en liste eller i et bibliotek.
  
Du kan løse dette problem ved at følge disse trin: 
  
1. Åbn rodwebstedet for gruppen af websteder i SharePoint Designer 2013.
  
2. Under **websteds objekter**skal du vælge **arbejdsprocesser**. 
  
3. Vælg **arbejdsproces, der kan genbruges**, i den **nye** sektion på båndet **arbejdsprocesser** . 
  
4. I formularen **Opret genbrugelig arbejdsproces** skal du angive navnet * * *Repair2010* * *. For **platform type**skal du klikke på **SharePoint 2010-arbejdsproces**og derefter klikke på **OK**. 
  
1. I sektionen **Gem** i båndet **arbejdsproces** skal du vælge **Publicer**. 
  
2. I sektionen **Administrer** på båndet i **arbejdsproces** skal du vælge **Publicer globalt**. I bekræftelsesdialogboksen, der vises, skal du vælge **OK**. 
  
3. I en webbrowser skal du finde rodwebstedet for gruppen af websteder og derefter få adgang til funktioner **for gruppen** \> **af**websteder. Derefter skal du slå **arbejdsproces** funktionen til/fra: 
  
· Hvis funktionen er  *aktiveret*  , skal du **klikke på Deaktiver og** derefter klikke på **Aktivér**. 
  
· Hvis funktionen er  *deaktiveret*  , skal du klikke på **Aktivér**. 
  
Hvis du vil have mere at vide, skal du se følgende [artikel](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  

