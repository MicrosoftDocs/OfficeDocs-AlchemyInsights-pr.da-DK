---
title: Problemer med installation af Microsoft Defender på Mac eller Linux
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
ms.custom:
- "6028"
- "9001222"
ms.openlocfilehash: a8d5ad2246b9b83e1e0a4d5be4dd8bb41c16e734
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 09/14/2020
ms.locfileid: "50713389"
---
# <a name="issues-installing-microsoft-defender-on-mac-or-linux"></a><span data-ttu-id="0ac5d-102">Problemer med installation af Microsoft Defender på Mac eller Linux</span><span class="sxs-lookup"><span data-stu-id="0ac5d-102">Issues installing Microsoft Defender on Mac or Linux</span></span>

<span data-ttu-id="0ac5d-103">**Mac**</span><span class="sxs-lookup"><span data-stu-id="0ac5d-103">**Mac**</span></span>

- <span data-ttu-id="0ac5d-104">Sørg for, at systemkravene er opfyldt, før du installerer Microsoft Defender ATP til Mac.</span><span class="sxs-lookup"><span data-stu-id="0ac5d-104">Ensure that system requirements are met before installing Microsoft Defender ATP for Mac.</span></span> <span data-ttu-id="0ac5d-105">Du kan få mere at vide [under Sådan installerer du Microsoft Defender ATP til Mac.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-mac#how-to-install-microsoft-defender-atp-for-mac)</span><span class="sxs-lookup"><span data-stu-id="0ac5d-105">For more info, see [How to install Microsoft Defender ATP for Mac](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-mac#how-to-install-microsoft-defender-atp-for-mac).</span></span>  
- <span data-ttu-id="0ac5d-106">Gennemse oplysningerne i filen: "/Library/Logs/Microsoft/mdatp/install.log".</span><span class="sxs-lookup"><span data-stu-id="0ac5d-106">Review the information in the file: "/Library/Logs/Microsoft/mdatp/install.log".</span></span>

<span data-ttu-id="0ac5d-107">**Linux**</span><span class="sxs-lookup"><span data-stu-id="0ac5d-107">**Linux**</span></span>

- <span data-ttu-id="0ac5d-108">Sørg for, at systemkravene er opfyldt, før du installerer Microsoft Defender ATP til Linux.</span><span class="sxs-lookup"><span data-stu-id="0ac5d-108">Ensure that system requirements are met before installing Microsoft Defender ATP for Linux.</span></span> <span data-ttu-id="0ac5d-109">Du kan få mere at vide [under Sådan installerer du Microsoft Defender ATP til Linux.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements)</span><span class="sxs-lookup"><span data-stu-id="0ac5d-109">For more info, see [How to install Microsoft Defender ATP for Linux](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements).</span></span> 
- <span data-ttu-id="0ac5d-110">Hvis du vil bekræfte, at MDATP-tjenesten kører, skal du se [Installation mislykkedes.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#installation-failed)</span><span class="sxs-lookup"><span data-stu-id="0ac5d-110">To verify that MDATP service is running, see [Installation failed](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#installation-failed).</span></span>  
    <span data-ttu-id="0ac5d-111">Hvis du vil foretage fejlfinding og løse problemer, hvis tjenesten ikke kører, skal du se Trin til fejlfinding, [hvis mdatp-tjenesten ikke kører.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#steps-to-troubleshoot-if-mdatp-service-isnt-running)</span><span class="sxs-lookup"><span data-stu-id="0ac5d-111">To troubleshoot and resolve issues if the service is not running, see [Steps to troubleshoot if mdatp service isn't running](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#steps-to-troubleshoot-if-mdatp-service-isnt-running).</span></span>
- <span data-ttu-id="0ac5d-112">Du kan finde trin til at kontrollere klientkonfigurationen, som bekræfter produktets tilstand, og til at køre en registreringstest på tekstfilen EICAR under [Klientkonfiguration.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-install-manually#client-configuration)</span><span class="sxs-lookup"><span data-stu-id="0ac5d-112">For steps to check the client configuration, which verifies the health of the product, and to run a detection test on the EICAR text file, see [Client configuration](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-install-manually#client-configuration).</span></span>  

    <span data-ttu-id="0ac5d-113">**Bemærk!** Du kan finde en liste over understøttede filsystemer til aktivitet ved adgang under [Microsoft Defender ATP til Linux.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements)</span><span class="sxs-lookup"><span data-stu-id="0ac5d-113">**Note** For a list of supported file systems for on-access activity, see [Microsoft Defender ATP for Linux](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements).</span></span>