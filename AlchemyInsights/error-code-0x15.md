---
title: Fejlkode 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Hvis du modtager en fejl under aktivering af Office-2013 på Remote Desktop Services (RDS) installationer, kan du overveje at aktivere ADAL ved at redigere registreringsdatabasen.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 01/15/2019
ms.locfileid: "28282875"
---
Hvis du modtager en fejl under aktivering af Office-2013 på Remote Desktop Services (RDS) installationer, kan du overveje at aktivere ADAL ved at redigere registreringsdatabasen. 
  
|**Nøgle i registreringsdatabasen**|**Type**|**Værdi**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |
   
Yderligere oplysninger finder du under [Aktivere moderne godkendelse for 2013 til Office på Windows-enheder](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL er aktiveret som standard i Office 365 ProPlus og Office 2016. > Fjernskrivebord-tjenester (RDS) blev tidligere kaldt Terminal Services. 
  
