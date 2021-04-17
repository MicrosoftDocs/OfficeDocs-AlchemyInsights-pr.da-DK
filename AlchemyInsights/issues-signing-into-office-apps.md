---
title: Problemer med at logge på Microsoft 365-apps
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
- "9000571"
- "2559"
ms.openlocfilehash: c64cf2c9dbf63caad22e54ae801adc3ed8ff0f62
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 04/15/2021
ms.locfileid: "51832997"
---
# <a name="fixing-the-microsoft-365-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a><span data-ttu-id="a96f2-102">Vi rettelse af meddelelsen "Computerens platform, der er tillid til, fungerer ikke korrekt" i Microsoft 365-appsene</span><span class="sxs-lookup"><span data-stu-id="a96f2-102">Fixing the Microsoft 365 apps "Your computer's Trusted Platform module is not functioning properly" message</span></span>

<span data-ttu-id="a96f2-103">Du kan rette fejlen ved at følge disse trin:</span><span class="sxs-lookup"><span data-stu-id="a96f2-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="a96f2-104">Installér de seneste opdateringer til [Windows](https://support.microsoft.com/help/4027667/windows-10-update) og [Office.](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5)</span><span class="sxs-lookup"><span data-stu-id="a96f2-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="a96f2-105">[Ryd Office-legitimationsoplysninger ved](https://docs.microsoft.com/office/troubleshoot/office-suite-issues/another-account-already-signed-in#step-4-clear-cached-credentials-on-the-computer) hjælp af Windows Legitimationsstyring.</span><span class="sxs-lookup"><span data-stu-id="a96f2-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/office-suite-issues/another-account-already-signed-in#step-4-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="a96f2-106">**Bemærk!** Stierne i registreringsdatabasen til Office 2016 er ændret til 16.0.</span><span class="sxs-lookup"><span data-stu-id="a96f2-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="a96f2-107">(Eksempel: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="a96f2-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="a96f2-108">Prøv processen [for brugergendannelse for](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) at løse problemer med fejl i et platformsmodul (Trusted Platform Module).</span><span class="sxs-lookup"><span data-stu-id="a96f2-108">Try the [user recovery process](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) to fix Trusted Platform Module (TPM) failures.</span></span>
- <span data-ttu-id="a96f2-109">Angiv EnableADAL = 0 ved at benytte følgende fremgangsmåde:</span><span class="sxs-lookup"><span data-stu-id="a96f2-109">Set the EnableADAL = 0 using the following steps:</span></span>  
    1. <span data-ttu-id="a96f2-110">Højreklik på knappen Start i Windows, vælg **Kør**, skriv **regedit**, og vælg derefter **OK**.</span><span class="sxs-lookup"><span data-stu-id="a96f2-110">Right-click the Windows Start button, choose **Run**, type **regedit**, and then choose **OK**.</span></span>
    2. <span data-ttu-id="a96f2-111">Vælg **Ja for** at tillade registreringseditor at foretage ændringer på din enhed.</span><span class="sxs-lookup"><span data-stu-id="a96f2-111">Select **Yes** to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="a96f2-112">I Registreringseditor skal du tilføje en **DWORD-værdi af EnableADAL** med en **indstilling på 0** under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span><span class="sxs-lookup"><span data-stu-id="a96f2-112">In Registry Editor, add a DWORD value of **EnableADAL** with a setting of **0** under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>

<span data-ttu-id="a96f2-113">Du kan få mere at vide under Forbindelsesproblemer ved logon efter opdatering til [Office 2016 build 16.0.7967 på Windows 10.](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)</span><span class="sxs-lookup"><span data-stu-id="a96f2-113">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>