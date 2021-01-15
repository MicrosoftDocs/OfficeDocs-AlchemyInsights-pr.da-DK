---
title: Sådan tilføjer og administrerer du administratorer – anbefalede trin
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/07/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004114"
- "7194"
ms.openlocfilehash: ed3aa5defabdd4f505ee4f74570023d990910dcb
ms.sourcegitcommit: 04bf13605a30ad4a2218ad9e94dcffcee4cc9aa6
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 01/05/2021
ms.locfileid: "49755829"
---
# <a name="how-to-add-and-manage-administrators---recommended-steps"></a><span data-ttu-id="b45ea-102">Sådan tilføjer og administrerer du administratorer – anbefalede trin</span><span class="sxs-lookup"><span data-stu-id="b45ea-102">How to add and manage administrators - recommended steps</span></span>

<span data-ttu-id="b45ea-103">Afhængigt af din problembeskrivelse har vi fundet en løsning til dig.</span><span class="sxs-lookup"><span data-stu-id="b45ea-103">Based on your issue description, we’ve found a solution for you.</span></span> <span data-ttu-id="b45ea-104">De fleste kunder har kunnet løse deres problemer efter eget efter at have fulgt vores dokumentation.</span><span class="sxs-lookup"><span data-stu-id="b45ea-104">Most customers were able to resolve their issue on their own after following our documentation.</span></span>

<span data-ttu-id="b45ea-105">**Rediger abonnements administratoren eller kollegaen**</span><span class="sxs-lookup"><span data-stu-id="b45ea-105">**Edit the Subscription Administrator or Co-administrator**</span></span>

- <span data-ttu-id="b45ea-106">Konto administratoren kan redigere begge roller, hvorimod abonnements administratoren kun kan ændre samtidig administratorer i Azure- [portalen](https://ms.portal.azure.com/#home).</span><span class="sxs-lookup"><span data-stu-id="b45ea-106">The Account Administrator can edit both roles whereas the Subscription Administrator can only change Co-administrators in the [Azure portal](https://ms.portal.azure.com/#home).</span></span>
- [<span data-ttu-id="b45ea-107">Tilføje eller ændre Azure-abonnements administratorer</span><span class="sxs-lookup"><span data-stu-id="b45ea-107">Add or change Azure subscription administrators</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/add-change-subscription-administrator)

<span data-ttu-id="b45ea-108">**Opdatere abonnements administratoren eller Co-Administrator for interne (AIRS)-abonnementer**</span><span class="sxs-lookup"><span data-stu-id="b45ea-108">**Update the Subscription Administrator or Co-Administrator for Internal (AIRS) Subscriptions**</span></span>

<span data-ttu-id="b45ea-109">Tjenesteadministratoren eller samtidig administrator kan selv behandle denne handling ved hjælp af følgende trin:</span><span class="sxs-lookup"><span data-stu-id="b45ea-109">The Service Administrator or the Co-administrator can self-serve this action by using the following steps:</span></span>

1. <span data-ttu-id="b45ea-110">Log på Azure- [portalen](https://ms.portal.azure.com/#home) , og klik på **omkostningsstyring + fakturering** i venstre blade.</span><span class="sxs-lookup"><span data-stu-id="b45ea-110">Log in to the [Azure portal](https://ms.portal.azure.com/#home) and click **Cost Management + Billing** in the left blade.</span></span>
2. <span data-ttu-id="b45ea-111">Klik på linjeelementet med dit abonnement.</span><span class="sxs-lookup"><span data-stu-id="b45ea-111">Click on the line item with your subscription.</span></span> <span data-ttu-id="b45ea-112">Dette åbner oversigten over dit abonnement.</span><span class="sxs-lookup"><span data-stu-id="b45ea-112">This opens the Overview for your subscription.</span></span>
3. <span data-ttu-id="b45ea-113">Klik på **Egenskaber** på **abonnements** bladet.</span><span class="sxs-lookup"><span data-stu-id="b45ea-113">On the **Subscription** blade, click **Properties**.</span></span> 
4. <span data-ttu-id="b45ea-114">Klik på knappen **tjenesteadministrator** .</span><span class="sxs-lookup"><span data-stu-id="b45ea-114">Click the **Service Admin** button.</span></span>
5. <span data-ttu-id="b45ea-115">Skriv mailadressen på den bruger, du vil angive som tjeneste administrator, og klik på **OK**.</span><span class="sxs-lookup"><span data-stu-id="b45ea-115">Enter the email of the user whom you want to set as a Service Administrator and click **OK**.</span></span>

<span data-ttu-id="b45ea-116">**Tilføj/Rediger/fjern samtidig administrator**</span><span class="sxs-lookup"><span data-stu-id="b45ea-116">**Add/Change/Remove Co-administrator**</span></span>

1. <span data-ttu-id="b45ea-117">Log på Azure- [portalen](https://ms.portal.azure.com/#home) som tjeneste administrator.</span><span class="sxs-lookup"><span data-stu-id="b45ea-117">Log in to the [Azure portal](https://ms.portal.azure.com/#home) as a Service Administrator.</span></span>
2. <span data-ttu-id="b45ea-118">Åbn [abonnementer](https://ms.portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) , og vælg et abonnement.</span><span class="sxs-lookup"><span data-stu-id="b45ea-118">Open [Subscriptions](https://ms.portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) and select a subscription.</span></span> <span data-ttu-id="b45ea-119">(Co-administratorer kan kun tildeles til abonnements området).</span><span class="sxs-lookup"><span data-stu-id="b45ea-119">(Co-adminstrators can only be assigned at the subscription scope.)</span></span>
3. <span data-ttu-id="b45ea-120">Naviger til Classic-administratorer **(Access Control)**  >  **Classic-administratorer**  >  **Tilføj**  >  **Tilføj administrator** for at åbne ruden **Tilføj Co-administrator** (hvis indstillingen Tilføj Co-administrator er deaktiveret, angiver det, at du ikke har tilladelse).</span><span class="sxs-lookup"><span data-stu-id="b45ea-120">Navigate to **Access control (IAM)** > **Classic administrators** > **Add** > **Add co-administrator** to open the **Add co-admin** pane (If the Add co-administrator option is disabled, it denotes that you do not have permissions).</span></span>
4. <span data-ttu-id="b45ea-121">Vælg den bruger, du vil tilføje, og klik på **Tilføj**.</span><span class="sxs-lookup"><span data-stu-id="b45ea-121">Select the user whom you want to add and click **Add**.</span></span>

<span data-ttu-id="b45ea-122">**Lær mere:**</span><span class="sxs-lookup"><span data-stu-id="b45ea-122">**Learn more:**</span></span>
- [<span data-ttu-id="b45ea-123">Tilføj en administrator</span><span class="sxs-lookup"><span data-stu-id="b45ea-123">Add a Co-Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="b45ea-124">Fjerne en administrator</span><span class="sxs-lookup"><span data-stu-id="b45ea-124">Remove a co-administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="b45ea-125">Ændre tjeneste administrator</span><span class="sxs-lookup"><span data-stu-id="b45ea-125">Change the Service Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="b45ea-126">Få vist konto administratoren</span><span class="sxs-lookup"><span data-stu-id="b45ea-126">View the Account Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="b45ea-127">Administrere adgang ved hjælp af RBAC og Azure-portalen</span><span class="sxs-lookup"><span data-stu-id="b45ea-127">Manage access using RBAC and Azure portal</span></span>](https://docs.microsoft.com/azure/role-based-access-control/role-assignments-portal)

<span data-ttu-id="b45ea-128">**Tilføj/slet brugere ved hjælp af Azure Active Directory (AD)**</span><span class="sxs-lookup"><span data-stu-id="b45ea-128">**Add/delete users using Azure Active Directory (AD)**</span></span>

<span data-ttu-id="b45ea-129">Du kan tilføje nye brugere eller slette eksisterende brugere fra din Azure Active Directory-organisation (Azure AD):</span><span class="sxs-lookup"><span data-stu-id="b45ea-129">You can add new users or delete existing users from your Azure Active Directory (Azure AD) organization:</span></span>

1. <span data-ttu-id="b45ea-130">Hvis du vil tilføje en ny bruger, skal du logge på [Azure-portalen](https://ms.portal.azure.com/#home) som Brugeradministrator for organisationen.</span><span class="sxs-lookup"><span data-stu-id="b45ea-130">To add a new user, log in to the [Azure portal](https://ms.portal.azure.com/#home) as a User-administrator for the organization.</span></span>
2. <span data-ttu-id="b45ea-131">Vælg **Azure Active Directory**, Vælg **brugere** , og klik derefter på **ny bruger**.</span><span class="sxs-lookup"><span data-stu-id="b45ea-131">Select **Azure Active Directory**, select **Users** and then click **New user**.</span></span>
3. <span data-ttu-id="b45ea-132">På siden **bruger** skal du udfylde de nødvendige oplysninger.</span><span class="sxs-lookup"><span data-stu-id="b45ea-132">On the **User** page, fill out the required information.</span></span> <span data-ttu-id="b45ea-133">Klik på **Opret**.</span><span class="sxs-lookup"><span data-stu-id="b45ea-133">Click **Create**.</span></span> <span data-ttu-id="b45ea-134">Brugeren oprettes og føjes til din Azure AD-lejer.</span><span class="sxs-lookup"><span data-stu-id="b45ea-134">The user is created and added to your Azure AD tenant.</span></span>

<span data-ttu-id="b45ea-135">**Få mere at vide**:</span><span class="sxs-lookup"><span data-stu-id="b45ea-135">**Learn more**:</span></span>

- [<span data-ttu-id="b45ea-136">Tilføje en ny bruger</span><span class="sxs-lookup"><span data-stu-id="b45ea-136">Add a new user</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory)
- [<span data-ttu-id="b45ea-137">Slette en bruger</span><span class="sxs-lookup"><span data-stu-id="b45ea-137">Delete a user</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory)
- [<span data-ttu-id="b45ea-138">Tilføje eller opdatere en brugers profiloplysninger ved hjælp af Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="b45ea-138">Add or update a user's profile information using Azure Active Directory</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-users-profile-azure-portal)

<span data-ttu-id="b45ea-139">**Anbefalede dokumenter**</span><span class="sxs-lookup"><span data-stu-id="b45ea-139">**Recommended documents**</span></span>

- [<span data-ttu-id="b45ea-140">Hvad er rollebaseret adgangskontrol (RBAC)?</span><span class="sxs-lookup"><span data-stu-id="b45ea-140">What is role-based access control (RBAC)?</span></span>](https://docs.microsoft.com/azure/role-based-access-control/overview)
- [<span data-ttu-id="b45ea-141">Forstå de forskellige roller i Azure</span><span class="sxs-lookup"><span data-stu-id="b45ea-141">Understand the different roles in Azure</span></span>](https://docs.microsoft.com/azure/role-based-access-control/rbac-and-directory-admin-roles)
- [<span data-ttu-id="b45ea-142">Tilladelser som administrator roller i Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="b45ea-142">Administrator role permissions in Azure Active Directory</span></span>](https://docs.microsoft.com/azure/active-directory/roles/permissions-reference)
- [<span data-ttu-id="b45ea-143">Selvstudium: give adgang til en bruger ved hjælp af RBAC og Azure-portalen</span><span class="sxs-lookup"><span data-stu-id="b45ea-143">Tutorial: Grant access for a user using RBAC and the Azure portal</span></span>](https://docs.microsoft.com/azure/role-based-access-control/quickstart-assign-role-user-portal)
- [<span data-ttu-id="b45ea-144">Fejlfinding af RBAC i Azure</span><span class="sxs-lookup"><span data-stu-id="b45ea-144">Troubleshoot RBAC in Azure</span></span>](https://docs.microsoft.com/azure/role-based-access-control/troubleshooting)
- [<span data-ttu-id="b45ea-145">Organisere dine ressourcer med Azure Management groups</span><span class="sxs-lookup"><span data-stu-id="b45ea-145">Organize your resources with Azure management groups</span></span>](https://docs.microsoft.com/azure/governance/management-groups/overview)
- [<span data-ttu-id="b45ea-146">Sådan anmoder du om en kopi af Azure-faktura via mail</span><span class="sxs-lookup"><span data-stu-id="b45ea-146">How to request copy of Azure invoice via email</span></span>](https://azure.microsoft.com/en-us/blog/azure-email-invoices/)
- [<span data-ttu-id="b45ea-147">Sådan tilføjer, opdaterer eller fjerner du et kredit-eller debetkort fra Azure</span><span class="sxs-lookup"><span data-stu-id="b45ea-147">How to add, update or remove a credit or debit card from Azure</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/change-credit-card)
- [<span data-ttu-id="b45ea-148">Administrer abonnementet (Genaktiver/Annuller/Skift)</span><span class="sxs-lookup"><span data-stu-id="b45ea-148">Manage (Reactivate/Cancel/Switch) subscription</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/subscription-disabled)


