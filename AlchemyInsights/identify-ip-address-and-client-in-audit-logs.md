---
title: Identificere IP-adresse og klienten i overvågningslogge
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1367
ms.assetid: ''
ms.openlocfilehash: 7e30a638de5926aa11b8ae637613a48076d7bdc9
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 04/23/2019
ms.locfileid: "32416937"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="71fbe-102">Identificere IP-adresse og klienten i overvågningslogge</span><span class="sxs-lookup"><span data-stu-id="71fbe-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="71fbe-103">Den IP-adresse, der svarer til en aktivitet af en bruger eller administrator fremgår af overvågningslogge.</span><span class="sxs-lookup"><span data-stu-id="71fbe-103">The IP address that corresponds to an activity by a user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="71fbe-104">Oplysningerne om klienten registreres også.</span><span class="sxs-lookup"><span data-stu-id="71fbe-104">The client information is also logged.</span></span> <span data-ttu-id="71fbe-105">Her er skridt til at identificere sådanne oplysninger</span><span class="sxs-lookup"><span data-stu-id="71fbe-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="71fbe-106">Log på [Office 365 & overholdelse Sikkerhedscenter](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="71fbe-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="71fbe-107">Klik på **Søg og undersøgelse** , og vælg **Revision Log søgning**.</span><span class="sxs-lookup"><span data-stu-id="71fbe-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

   <span data-ttu-id="71fbe-108">Hvis du er interesseret i en bestemt aktivitet, kan du vælge den på listen **aktiviteter** .</span><span class="sxs-lookup"><span data-stu-id="71fbe-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="71fbe-109">Hvis ikke, returneres alle aktiviteter for den valgte bruger (standardindstilling).</span><span class="sxs-lookup"><span data-stu-id="71fbe-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="71fbe-110">**Bemærk**: visse aktiviteter er muligvis ikke tilgængelig i menuen **aktiviteter** . dog de overvåge varer returneres, hvis **Vis resultater for alle aktiviteter, der** er markeret (standardindstilling).</span><span class="sxs-lookup"><span data-stu-id="71fbe-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="71fbe-111">Angiv brugernavnet i feltet **brugere** , vælge det relevante datointerval for aktiviteten, og klik derefter på **Søg**.</span><span class="sxs-lookup"><span data-stu-id="71fbe-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="71fbe-112">I resultaterne, kan du se IP-adressen for den pågældende aktivitet i resultatruden.</span><span class="sxs-lookup"><span data-stu-id="71fbe-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="71fbe-113">Vælg revisionspost for at se detaljerede oplysninger i **Detaljer** -mærke (for eksempel klienten, bruger, der foretog handlingen osv.).</span><span class="sxs-lookup"><span data-stu-id="71fbe-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="71fbe-114">Yderligere oplysninger finder du under [finde IP-adressen på den computer, der bruges til at få adgang til en kompromitteret konto](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="71fbe-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>