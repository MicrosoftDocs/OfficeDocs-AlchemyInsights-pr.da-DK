---
title: Microsoft Edge-understøttelse af Microsoft Defender Application Guard
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/05/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004024"
- "7090"
ms.openlocfilehash: 65cbc867ea7d1c73ca2906f51f72aa3376f31b5d
ms.sourcegitcommit: 2e4a5153e530bf15744a52e982eeb0d99757e9d2
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 12/04/2020
ms.locfileid: "49583367"
---
# <a name="microsoft-edges-support-for-microsoft-defender-application-guard"></a><span data-ttu-id="04b79-102">Microsoft Edge-understøttelse af Microsoft Defender Application Guard</span><span class="sxs-lookup"><span data-stu-id="04b79-102">Microsoft Edge's support for Microsoft Defender Application Guard</span></span>

<span data-ttu-id="04b79-103">Application Guard, der er udviklet til Windows 10 og Microsoft Edge, anvender en hardware isolations metode, der gør det muligt for en bruger at navigere i et websted, der ikke er tillid til, fra en isoleret, Hyper-V-aktiveret beholder, adskilt fra værtsoperativsystemet.</span><span class="sxs-lookup"><span data-stu-id="04b79-103">Designed for Windows 10 and Microsoft Edge, Application Guard uses a hardware-isolation approach that lets a user navigate an untrusted site from inside an isolated, Hyper-V–enabled container, separated from the host operating system.</span></span>

<span data-ttu-id="04b79-104">En virksomhedsadministrator definerer en liste over websteder, der er tillid til, Cloud-ressourcer og interne netværk.</span><span class="sxs-lookup"><span data-stu-id="04b79-104">An enterprise admin defines a list of trusted websites, cloud resources, and internal networks.</span></span> <span data-ttu-id="04b79-105">Når en bruger besøger et websted, der ikke er på listen, vil Microsoft Edge åbne webstedet i beholderen.</span><span class="sxs-lookup"><span data-stu-id="04b79-105">When a user visits a site that's not on the list, Microsoft Edge will open the site in the container.</span></span> <span data-ttu-id="04b79-106">Det betyder, at hvis webstedet nedsættes for at være skadeligt, vil værtscomputeren fortsat være beskyttet, og hackeren vil ikke komme til virksomhedens data.</span><span class="sxs-lookup"><span data-stu-id="04b79-106">This means that if the site turns out to be malicious, the host PC will remain protected and the attacker won't get to the enterprise data.</span></span>

<span data-ttu-id="04b79-107">Installation af udvidelser i beholderen understøttes af Microsoft Edge version 81, og den kan kontrolleres via en politik.</span><span class="sxs-lookup"><span data-stu-id="04b79-107">Installation of extensions in the container is supported as of Microsoft Edge version 81, and it can be controlled via a policy.</span></span> <span data-ttu-id="04b79-108">UpdateURL-adressen, der bruges i ExtensionInstallForcelist-politikken, skal tilføjes som en neutral ressource i de politikker for netværks isolation, der bruges af Application Guard.</span><span class="sxs-lookup"><span data-stu-id="04b79-108">The updateURL address that gets used in the ExtensionInstallForcelist policy should be added as a Neutral Resource in the Network Isolation policies used by Application Guard.</span></span>

<span data-ttu-id="04b79-109">Du kan finde flere oplysninger i [Microsoft Edge support til Microsoft Defender Application Guard](https://go.microsoft.com/fwlink/?linkid=2134229).</span><span class="sxs-lookup"><span data-stu-id="04b79-109">For more info, see [Microsoft Edge support for Microsoft Defender Application Guard](https://go.microsoft.com/fwlink/?linkid=2134229).</span></span>