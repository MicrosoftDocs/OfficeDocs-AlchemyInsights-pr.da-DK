---
title: Klargøring af bruger
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004348"
- "8428"
ms.openlocfilehash: bd415b2d44bccf0c2b3eccb4e38452498b748b3a
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/04/2021
ms.locfileid: "50481097"
---
# <a name="user-provisioning"></a><span data-ttu-id="cdae7-102">Klargøring af brugere</span><span class="sxs-lookup"><span data-stu-id="cdae7-102">User provisioning</span></span>

- <span data-ttu-id="cdae7-103">Brug [klargøringsfunktionaliteten efter](https://docs.microsoft.com/azure/active-directory/app-provisioning/provision-on-demand) behov til at klargøre en bruger og få detaljeret diagnosticering af de trin, der er taget.</span><span class="sxs-lookup"><span data-stu-id="cdae7-103">Use the [on-demand provisioning](https://docs.microsoft.com/azure/active-directory/app-provisioning/provision-on-demand) capability to provision a user and get detailed diagnostics about the steps taken.</span></span>
- <span data-ttu-id="cdae7-104">Hvis du vil foretage fejlfinding af problemer, du støder på under klargøring af brugere og grupper, skal du se [fejlfindingsvejledningen Ingen brugere klargøres.](https://docs.microsoft.com/azure/active-directory/app-provisioning/application-provisioning-config-problem-no-users-provisioned)</span><span class="sxs-lookup"><span data-stu-id="cdae7-104">To troubleshoot issues you encounter when provisioning users and groups, see the troubleshooting guide [No users are being provisioned](https://docs.microsoft.com/azure/active-directory/app-provisioning/application-provisioning-config-problem-no-users-provisioned).</span></span>
- <span data-ttu-id="cdae7-105">Hvis du ser, at brugerne ikke bliver klargjort, kan du se [Klargøringslogfiler (forhåndsvisning)](https://docs.microsoft.com/azure/active-directory/reports-monitoring/concept-provisioning-logs) i Azure Active Directory (AD).</span><span class="sxs-lookup"><span data-stu-id="cdae7-105">If you observe that users are not being provisioned, see [Provisioning logs (preview)](https://docs.microsoft.com/azure/active-directory/reports-monitoring/concept-provisioning-logs) in Azure Active Directory (AD).</span></span> <span data-ttu-id="cdae7-106">Søg efter logposter, der er relevante for en bestemt bruger.</span><span class="sxs-lookup"><span data-stu-id="cdae7-106">Search for log entries pertaining to a specific user.</span></span>
- <span data-ttu-id="cdae7-107">Genstart med jævne mellemrum klargøring for at fange eventuelle brugere, der er blevet overset i en tidligere klargøringscyklus.</span><span class="sxs-lookup"><span data-stu-id="cdae7-107">Periodically restart provisioning to catch any users that were missed in a previous provisioning cycle.</span></span>
- <span data-ttu-id="cdae7-108">Brugeren/gruppen er muligvis ikke blevet klargjort, fordi vores tjeneste endnu ikke har haft mulighed for at evaluere brugeren.</span><span class="sxs-lookup"><span data-stu-id="cdae7-108">The user/group may not have been provisioned because our service hasn't had a chance to evaluate the user yet.</span></span> <span data-ttu-id="cdae7-109">Gennemgå vejledningen for, hvor lang tid klargøring tager, samt statuslinjen på konfigurationssiden for klargøring.</span><span class="sxs-lookup"><span data-stu-id="cdae7-109">Review the guidance for how long provisioning takes as well as the progress bar on the provisioning configuration page.</span></span> <span data-ttu-id="cdae7-110">Hvis den konstante tilstand, der er angivet i sektionen med yderligere oplysninger, er før den dato, hvor brugeren blev oprettet/opdateret/slettet, betyder det, at vi endnu ikke har evalueret brugeren.</span><span class="sxs-lookup"><span data-stu-id="cdae7-110">If the steady state specified in the additional details section is before the date the user was created/updated/deleted, it means we have not evaluated the user yet.</span></span> <span data-ttu-id="cdae7-111">I dette scenarie er det bedste at vente på, at klargøringstjenesten afsluttes.</span><span class="sxs-lookup"><span data-stu-id="cdae7-111">In this scenario, the best thing to do is wait for the provisioning service to finish.</span></span> <span data-ttu-id="cdae7-112">Hvis der er opnået stabil tilstand, anbefaler vi, at du udfører en genstart fra brugergrænsefladen i Azure-portalen.</span><span class="sxs-lookup"><span data-stu-id="cdae7-112">If the steady state has been achieved, we recommend performing a restart from the UI in the Azure Portal.</span></span>
  - <span data-ttu-id="cdae7-113">Bemærk, at vores tjeneste kun er opmærksom på ændringer af en bruger/gruppe i kildesystemet (Azure Active Directory).</span><span class="sxs-lookup"><span data-stu-id="cdae7-113">Note that our service is only aware of changes to a user/group in the source system (Azure Active Directory).</span></span> <span data-ttu-id="cdae7-114">Hvis en bruger/gruppe fjernes direkte i programmet (f.eks. ServiceNow), er vi ikke opmærksomme på disse ændringer og kan ikke rulle den tilbage baseret på brugerens tilstand i kildesystemet.</span><span class="sxs-lookup"><span data-stu-id="cdae7-114">If a user/group is removed directly in the application (for example, ServiceNow), we are not aware of those changes and do not roll it back based on the state of the user in the source system.</span></span> <span data-ttu-id="cdae7-115">I dette scenarie er det bedst at tilbagerulle ændringen direkte i destinationsprogrammet.</span><span class="sxs-lookup"><span data-stu-id="cdae7-115">In this scenario, it is best to roll back the change directly in the target application.</span></span>
- <span data-ttu-id="cdae7-116">Vores tjeneste evaluerede brugeren/gruppen og vurderede, at den ikke skulle klargøres:</span><span class="sxs-lookup"><span data-stu-id="cdae7-116">Our service evaluated the user/group and determined it should not be provisioned:</span></span>
  - <span data-ttu-id="cdae7-117">Hvis du har angivet området til tildelte brugere og grupper, skal du kontrollere, om brugeren/gruppen er tildelt til programmet.</span><span class="sxs-lookup"><span data-stu-id="cdae7-117">If you have set the scope to assigned users and groups, check if the user/group is assigned to the application.</span></span>
  - <span data-ttu-id="cdae7-118">Hvis brugeren/gruppen er tildelt til programmet, skal du sikre dig, at de ikke er tildelt standardadgangsrollen.</span><span class="sxs-lookup"><span data-stu-id="cdae7-118">If the user/group is assigned to the application, ensure that they are not assigned to the default access role.</span></span> <span data-ttu-id="cdae7-119">Denne rolle kan ikke bruges til klargøring.</span><span class="sxs-lookup"><span data-stu-id="cdae7-119">This role cannot be used for provisioning.</span></span>
  - <span data-ttu-id="cdae7-120">Hvis du har angivet en attribut baseret på et filter til angivelse af område, skal du sikre dig, at brugeren opfylder de kriterier, du har angivet.</span><span class="sxs-lookup"><span data-stu-id="cdae7-120">If you have set an attribute based scoping filter, ensure that the user meets the criteria that you have specified.</span></span>
  - <span data-ttu-id="cdae7-121">Hvis brugerne allerede findes i destinationssystemet og brugerens tilstand i kilde- og målmatchet, vil vi ikke gøre yderligere.</span><span class="sxs-lookup"><span data-stu-id="cdae7-121">If users already exist in the target system and the state of the user in the source and target match, we won't take any further action.</span></span>
- <span data-ttu-id="cdae7-122">Vores tjeneste forsøgte at klargøre brugeren, og det mislykkedes.</span><span class="sxs-lookup"><span data-stu-id="cdae7-122">Our service attempted to provision the user and it failed.</span></span> <span data-ttu-id="cdae7-123">For disse scenarier skal du gennemgå fanen med fejlfinding og anbefalinger i klargøringslogfilerne:</span><span class="sxs-lookup"><span data-stu-id="cdae7-123">For these scenarios, review the troubleshooting and recommendations tab of the provisioning logs:</span></span>
  - <span data-ttu-id="cdae7-124">En påkrævet attribut på brugeren mangler muligvis i Azure Active Directory eller svarer ikke til det format, der kræves af tredjepartsprogrammet.</span><span class="sxs-lookup"><span data-stu-id="cdae7-124">A required attribute on the user might be missing in Azure Active Directory or does not match the format required by the third party application.</span></span> <span data-ttu-id="cdae7-125">Eksempelvis kan attributten Land for en bruger være indstillet til USA, når den skal være USA.</span><span class="sxs-lookup"><span data-stu-id="cdae7-125">For example, the Country attribute on a user might be set to United States when it should be US.</span></span>
  - <span data-ttu-id="cdae7-126">Attributten er en referentiel attribut, der endnu ikke findes i destinationsprogrammet.</span><span class="sxs-lookup"><span data-stu-id="cdae7-126">The attribute is a referential attribute that does not yet exist in the target application.</span></span> <span data-ttu-id="cdae7-127">En referentiel attribut er en attribut, der peger på et andet objekt, f.eks. en bruger, der er medlem af en gruppe.</span><span class="sxs-lookup"><span data-stu-id="cdae7-127">A referential attribute is an attribute that points to another object, for example, a user that is a member of a group.</span></span> <span data-ttu-id="cdae7-128">Brugerens id findes i medlemsattributten for gruppen, men det kan kun behandles, hvis det brugerobjekt, det peger på, allerede findes.</span><span class="sxs-lookup"><span data-stu-id="cdae7-128">The user's ID would be in the member attribute of the group, but can only be processed if the user object it points to already exists.</span></span>