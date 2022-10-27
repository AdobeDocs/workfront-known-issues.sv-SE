---
title: "Anpassade formulär: HOUR-funktionen i beräkningsfält använder UTC"
description: "När ett beräkningsfält innehåller funktionen HOUR returnerar funktionen värden baserade på UTC i stället för den förväntade tidszonen. Därför är alla beräkningar som baseras på HOUR-värdet felaktiga."
hidefromtoc: true
source-git-commit: 8f04dc85caf0019001913bb4762c924109516a96
workflow-type: tm+mt
source-wordcount: '88'
ht-degree: 0%

---


# Anpassade formulär: [!UICONTROL HOUR] funktionen i beräkningsfält använder UTC

>[!NOTE]
>
>Problemet korrigerades den 27 oktober 2022.

När ett beräkningsfält innehåller [!UICONTROL HOUR] funktionen returnerar funktionen värden baserade på UTC i stället för den förväntade tidszonen. Alla beräkningar som baseras på HOUR-värdet är därför felaktiga.

_Först rapporterad den 17 oktober 2022._

