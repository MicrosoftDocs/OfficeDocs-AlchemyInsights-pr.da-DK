---
title: Identificere eksterne e-mail-videresendelse på postkasser i overvågningslogge
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1369
ms.assetid: ''
ms.openlocfilehash: 7fb2c161c558a7eb961f86ca2b86e33750d902fd
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 04/23/2019
ms.locfileid: "32417206"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="fd086-102">Identificere når eksterne e-mail-videresendelse er konfigureret til postkasser</span><span class="sxs-lookup"><span data-stu-id="fd086-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="fd086-103">Når brugeren konfigurerer eksterne e-mail-videresendelse på en postkasse, overvåges aktiviteten, som en del af **Set-Mailbox** -cmdlet.</span><span class="sxs-lookup"><span data-stu-id="fd086-103">When a user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="fd086-104">Du kan se aktiviteten ved hjælp af overvågning log Søg i Security & Overholdelsescenter.</span><span class="sxs-lookup"><span data-stu-id="fd086-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="fd086-105">Log på [Office 365 & overholdelse Sikkerhedscenter](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="fd086-105">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="fd086-106">Klik på **Søg og undersøgelse** , og vælg **Revision Log søgning**.</span><span class="sxs-lookup"><span data-stu-id="fd086-106">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="fd086-107">Vælg datointervallet i felterne **startdato** og **slutdato** .</span><span class="sxs-lookup"><span data-stu-id="fd086-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="fd086-108">Du behøver ikke at angive et brugernavn.</span><span class="sxs-lookup"><span data-stu-id="fd086-108">You don't need to specify a username.</span></span> <span data-ttu-id="fd086-109">Kontroller feltet **aktiviteter** er indstillet til at **få vist resultater for alle aktiviteter**.</span><span class="sxs-lookup"><span data-stu-id="fd086-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="fd086-110">Klik på **Søg**.</span><span class="sxs-lookup"><span data-stu-id="fd086-110">Click **Search**.</span></span>

<span data-ttu-id="fd086-111">Klik på **Filtrerede resultater** i resultaterne, og skriv **Sæt postkasse** i filterboksen aktivitet.</span><span class="sxs-lookup"><span data-stu-id="fd086-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="fd086-112">Vælg en revisionspost i resultaterne.</span><span class="sxs-lookup"><span data-stu-id="fd086-112">Select an audit record in the results.</span></span> <span data-ttu-id="fd086-113">**Oplysninger om** mærke, klik på **flere oplysninger**.</span><span class="sxs-lookup"><span data-stu-id="fd086-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="fd086-114">Du skulle se på detaljerne for hver revisionspost til at bestemme, om aktiviteten vedrører e-mail videresendelse.</span><span class="sxs-lookup"><span data-stu-id="fd086-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="fd086-115">**ObjectId**: alias værdien af den postkasse, der er blevet ændret.</span><span class="sxs-lookup"><span data-stu-id="fd086-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="fd086-116">**Parametre**: _ForwardingSmtpAddress_ angiver e-mail-adressen til destinationen.</span><span class="sxs-lookup"><span data-stu-id="fd086-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="fd086-117">**Bruger-id**: den bruger, der konfigureret e-mail-videresendelse på postkassen i feltet **ObjectId** .</span><span class="sxs-lookup"><span data-stu-id="fd086-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="fd086-118">Yderligere oplysninger finder du [fastlægge, der har konfigureret e-mail videresendes til en postkasse](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span><span class="sxs-lookup"><span data-stu-id="fd086-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span></span>