---
title: Konfigurere meddelelseskryptering for et hybridmiljø
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 22c2468b7639680b447b6464431a79b69f7198c3
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/11/2021
ms.locfileid: "50744163"
---
# <a name="configure-message-encryption-for-a-hybrid-environment"></a><span data-ttu-id="30c3a-102">Konfigurere meddelelseskryptering for et hybridmiljø</span><span class="sxs-lookup"><span data-stu-id="30c3a-102">Configure message encryption for a hybrid environment</span></span>

<span data-ttu-id="30c3a-103">For hybride Exchange-miljøer kan lokale brugere kun sende krypteret mail ved hjælp af Office-meddelelseskryptering (OME), hvis mail dirigeres via Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="30c3a-103">For hybrid Exchange environments, on-premises users can send encrypted email using Office Message Encryption (OME) only if email is routed through Exchange Online.</span></span>

<span data-ttu-id="30c3a-104">Hvis du vil kryptere mails ved hjælp af OME, skal du udføre følgende trin:</span><span class="sxs-lookup"><span data-stu-id="30c3a-104">To encrypt emails using OME, perform the following steps:</span></span>

1. <span data-ttu-id="30c3a-105">Brug guiden [Hybridkonfiguration til](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) at konfigurere dit hybridmiljø.</span><span class="sxs-lookup"><span data-stu-id="30c3a-105">Use the [Hybrid Configuration wizard](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) to set up your hybrid environment.</span></span> <span data-ttu-id="30c3a-106">Der kræves ingen særlige trin for at konfigurere kryptering.</span><span class="sxs-lookup"><span data-stu-id="30c3a-106">No special steps are required for setting up encryption.</span></span>
2. <span data-ttu-id="30c3a-107">[Konfigurer dine regler for mailflow til kryptering, som](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) du normalt ville gøre det.</span><span class="sxs-lookup"><span data-stu-id="30c3a-107">[Set up your mail flow rules for encryption](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) like you normally would.</span></span>

