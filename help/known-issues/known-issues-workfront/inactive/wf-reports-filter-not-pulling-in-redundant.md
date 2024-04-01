---
title: "Rapporter: Rapportfiltret returnerar inte förväntade resultat"
description: "Ett filter i en rapport kanske inte returnerar alla förväntade resultat. Det finns en lösning."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: ed1fbb6e6c13ad41430e7351e0c9a28cefd46d12
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 0%

---


# Rapporter: Rapportfiltret returnerar inte förväntade resultat

>[!NOTE]
>
>Problemet har stängts.

Ett filter i en rapport kanske inte returnerar alla förväntade resultat.

Detta kan inträffa när filtret är konfigurerat att returnera resultat med vissa villkor och inkluderar en OR-regel som returnerar resultat som är en delmängd av samma villkor.

**Tillfällig lösning**

Se till att filtrets OR-block inte innehåller identiska utvärderingskriterier.

_Först rapporterad den 11 mars 2024._

