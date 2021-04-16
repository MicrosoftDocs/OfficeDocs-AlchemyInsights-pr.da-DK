---
title: Et af dine lokale sammenslutningstjenestecertifikater udløber
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 45a679e83aa8f07d65d2e7e84d7eb2a2b5a721e8
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 04/15/2021
ms.locfileid: "51810046"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a><span data-ttu-id="9fbfd-102">Et af dine lokale sammenslutningstjenestecertifikater udløber</span><span class="sxs-lookup"><span data-stu-id="9fbfd-102">One of your on-premises Federation Service Certificates is expiring</span></span>

<span data-ttu-id="9fbfd-103">Du kan løse dette problem ved at følge disse trin:</span><span class="sxs-lookup"><span data-stu-id="9fbfd-103">To resolve this issue, follow these steps:</span></span>
  
- <span data-ttu-id="9fbfd-104">Installer Microsoft Azure Active Directory-modulet til Windows PowerShell på computeren (hvis modulet ikke allerede er installeret).</span><span class="sxs-lookup"><span data-stu-id="9fbfd-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="9fbfd-105">For at gøre dette skal du gå [til Azure Active Directory PowerShell til Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span><span class="sxs-lookup"><span data-stu-id="9fbfd-105">To do this, go to [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span></span>
    
- <span data-ttu-id="9fbfd-106">Følg trinnene i afsnittet "Scenarie 1: Ad FS-certifikat til signering med token udløbet" i afsnittet "Der opstod et problem med at få adgang til webstedet" fra AD FS, når en bruger i et organisationsnetværk logger på [Microsoft 365, Azure eller Intune.](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)</span><span class="sxs-lookup"><span data-stu-id="9fbfd-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
- <span data-ttu-id="9fbfd-107">Følg trinnene i Sådan opdaterer eller reparerer du indstillingerne for et organisationsnetværksdomæne i [Microsoft 365, Azure eller Intune.](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)</span><span class="sxs-lookup"><span data-stu-id="9fbfd-107">Follow the steps in [How to update or repair the settings of a federated domain in Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
<span data-ttu-id="9fbfd-108">Du kan finde flere oplysninger om fornyelse af sammenslutningscertifikater i [Certifikatfornyelse for O365 og Azure AD.](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs)</span><span class="sxs-lookup"><span data-stu-id="9fbfd-108">For more information about renewing Federation certificates, see [Certificate renewal for O365 and Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
  

