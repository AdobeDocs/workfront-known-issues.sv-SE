---
title: 'Godkännanden: Delegering av godkännande har angetts för felaktigt antal dagar'
description: När en användare schemalägger"Personlig tid av" och delegerar sina godkännanden för den tiden, kan godkännandedelegeringen inkludera dagar före eller efter den schemalagda tidpunkten.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
hidefromtoc: true
source-git-commit: 875945978c7bdb4a7128ade826b6fbc31da04ae9
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# Godkännanden: Delegering av godkännande har angetts för felaktigt antal dagar

<!--Live for workaround-->

>[!NOTE]
>
>Problemet har stängts eftersom det inte är något problem.

När en användare schemalägger sin personliga tid och delegerar sina godkännanden för den tiden, kan godkännandedelegeringen inkludera dagar före eller efter den schemalagda tidpunkten.

**Tillfällig lösning**

Skillnaden beror på en skillnad mellan tidszonen i en användarprofil och tidszonen för användarens tilldelade schema.

Vi rekommenderar att du skapar ett unikt schema för varje tidszon som användarna arbetar från och tilldelar varje användare det schema som matchar tidszonen i deras användarprofil.

_Först rapporterad den 24 mars 2022._
