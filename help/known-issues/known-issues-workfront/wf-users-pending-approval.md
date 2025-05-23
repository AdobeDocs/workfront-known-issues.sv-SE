---
title: 'Användare: Väntande godkännandemärke visas för nya användare'
description: Nya användare i Workfront kan visas i användarlistan med märket Väntande godkännande. Märket finns kvar i mer än några minuter och visas fortfarande när sidan uppdateras.
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---


# Användare: Märket&quot;Väntar på godkännande&quot; visas för nya användare

>[!NOTE]
>
>Problemet kan finnas i organisationer som har migrerats till Adobe Admin Console.

Nya användare i Workfront kan visas i användarlistan med ett&quot;Väntande godkännande&quot;-märke. Märket finns kvar i mer än några minuter och visas fortfarande när sidan uppdateras.

Problemet förvärras när användare laddas upp i stora grupper, t.ex. från ett kalkylblad eller en Workfront Quick-Start.

Det förväntade beteendet är att märket försvinner efter några minuter och inte visas när sidan uppdateras.

## Tillfälliga lösningar

Detta inträffar när användare som läggs till i Workfront inte synkroniserar med Adobe Admin Console.

Vi rekommenderar följande tillfälliga lösningar:

### Lös enskilda användare

Du kan lösa enskilda användare i listan Användare.

1. Välj användare i listan Användare.
1. Klicka på menyn med tre punkter i listhuvudet.
1. Välj **Godkänn**.
1. Uppdatera sidan efter några minuter.

### Lös användare som lagts till i en stor grupp

Om du vill lösa användare som lagts till i en stor grupp kan du lägga till gruppen med användare direkt i Adobe Admin Console.

Instruktioner finns i [Hantera flera användare | Massöverföring av CSV ](https://helpx.adobe.com/se/enterprise/using/bulk-upload-users.html) i Adobe-dokumentationen.


_Först rapporterad 8 maj 2025._
