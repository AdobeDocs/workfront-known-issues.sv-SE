---
title: "Anpassade formulär: HOUR-funktionen i beräkningsfält använder UTC"
description: "När ett beräkningsfält innehåller funktionen HOUR returnerar funktionen värden baserade på UTC i stället för den förväntade tidszonen. Därför är alla beräkningar som baseras på HOUR-värdet felaktiga."
hidefromtoc: true
source-git-commit: a681d8afd4bcf1ddfccf192871442e63dae1b2c3
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Anpassade formulär: [!UICONTROL HOUR] funktionen i beräkningsfält använder UTC

>[!NOTE]
>
>Problemet löstes den 3 november 2022.

När ett beräkningsfält innehåller [!UICONTROL HOUR] funktionen returnerar funktionen värden baserade på UTC i stället för den förväntade tidszonen. Alla beräkningar som baseras på HOUR-värdet är därför felaktiga.

_Först rapporterad den 17 oktober 2022._

