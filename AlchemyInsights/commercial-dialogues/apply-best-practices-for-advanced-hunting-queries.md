---
title: Anvend bedste fremgangsmåder for avancerede forespørgselsforespørgsler
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: cd13e2e8801db3df91140ce371813d900d72e38b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: da-DK
ms.lasthandoff: 03/11/2021
ms.locfileid: "50744606"
---
# <a name="apply-best-practices-for-advanced-hunting-queries"></a><span data-ttu-id="62779-102">Anvend bedste fremgangsmåder for avancerede forespørgselsforespørgsler</span><span class="sxs-lookup"><span data-stu-id="62779-102">Apply best practices for advanced hunting queries</span></span>

<span data-ttu-id="62779-103">For at få resultater hurtigere og undgå timeouts, mens du kører komplekse forespørgsler, skal du anvende disse bedste fremgangsmåder:</span><span class="sxs-lookup"><span data-stu-id="62779-103">To get results faster and to avoid timeouts while running complex queries, apply these best practices:</span></span>

- <span data-ttu-id="62779-104">Når du prøver nye forespørgsler, skal du altid bruge en grænse for at undgå at få meget store resultatsæt.</span><span class="sxs-lookup"><span data-stu-id="62779-104">When trying new queries, always use a limit, to avoid getting extremely large result sets.</span></span> <span data-ttu-id="62779-105">Bruges også `count` til at foretage en indledende vurdering af resultatsættets størrelse.</span><span class="sxs-lookup"><span data-stu-id="62779-105">Also, use `count` to make an initial assessment of the result set's size.</span></span>
- <span data-ttu-id="62779-106">Brug tidsfiltre først.</span><span class="sxs-lookup"><span data-stu-id="62779-106">Use time filters first.</span></span> <span data-ttu-id="62779-107">Ideelt set bør du begrænse dine forespørgsler til syv dage.</span><span class="sxs-lookup"><span data-stu-id="62779-107">Ideally, limit your queries to seven days.</span></span>
- <span data-ttu-id="62779-108">I starten af en forespørgsel lige efter tidsfilteret skal du tilføje de filtre, der forventes at fjerne de fleste af dataene.</span><span class="sxs-lookup"><span data-stu-id="62779-108">In the beginning of a query, right after the time filter, add the filters expected to remove most of the data.</span></span>
- <span data-ttu-id="62779-109">Når du leder efter fulde tokens, skal du bruge `has` operatoren i stedet for `contains` .</span><span class="sxs-lookup"><span data-stu-id="62779-109">When looking for full tokens, use the `has` operator rather than `contains`.</span></span>
- <span data-ttu-id="62779-110">Kør en søgning på en bestemt kolonne i stedet for på tværs af alle kolonner.</span><span class="sxs-lookup"><span data-stu-id="62779-110">Run a search on a specific column rather than across all columns.</span></span>
- <span data-ttu-id="62779-111">Når du sammenføjer tabeller, skal du først angive tabellen med færre rækker.</span><span class="sxs-lookup"><span data-stu-id="62779-111">When joining tables, first specify the table with fewer rows.</span></span>
- <span data-ttu-id="62779-112">`project` kun de nødvendige kolonner fra de tabeller, du har sammenføjet.</span><span class="sxs-lookup"><span data-stu-id="62779-112">`project` only the necessary columns from the tables you've joined.</span></span>

<span data-ttu-id="62779-113">Hvis du vil have mere at vide, skal [du se bedste fremgangsmåder for avanceret forespørgsel.](https://go.microsoft.com/fwlink/?linkid=2144812)</span><span class="sxs-lookup"><span data-stu-id="62779-113">To learn more, see [Advanced hunting query best practices](https://go.microsoft.com/fwlink/?linkid=2144812).</span></span>