---
title: Enkelt bruger kan ikke se tilføjelsesprogrammer i Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.openlocfilehash: 8c99b443a2d83f3ac24362d63cd6363a66a81393
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 09/14/2020
ms.locfileid: "47719659"
---
# <a name="single-user-not-seeing-add-ins-in-outlook"></a>Enkelt bruger kan ikke se tilføjelsesprogrammer i Outlook

Brugeren kan være en del af en rolle, der ikke har den korrekte AppsForOfficeEnabled-parameter. Kør denne cmdlet for at finde ud af, om den rette rolle er knyttet til brugeren:

Get-ManagementRoleAssignment-RoleAssignee user@domain.com-delegere $false | Formatér-tabel-automatisk rolle, RoleAssigneeName, RoleAssigneeType

Du kan finde flere oplysninger i [angive de administratorer og brugere, der kan installere og administrere tilføjelsesprogrammer til Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).
