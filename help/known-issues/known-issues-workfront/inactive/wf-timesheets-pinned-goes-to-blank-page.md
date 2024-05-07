---
title: "Tidrapporter: Fäst tidrapport går till tom sida"
description: "När en användare klickar på ett häftstift i Workfront som är avsett att gå till sin tidrapport, hamnar stiftet i stället på en tom sida. Det finns en lösning."
hidefromtoc: true
feature: Timesheets
source-git-commit: 229d3accabec51a7c559279b680336ca096c0e70
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 0%

---


# Tidrapporter: Fäst tidrapport går till tom sida

När en användare klickar på ett häftstift i Workfront som är avsett att gå till sin tidrapport, hamnar stiftet i stället på en tom sida.

Detta beror på att URL:en för tidrapporten har ändrats. den `/own` i slutet av URL:en inte längre är rätt URL. Om användaren har fäst en URL som innehåller `/own`, leder nålen till en tom sida.

**Tillfällig lösning**

1. Plocka bort tidrapporten.
1. Ta bort `/own` från slutet av URL:en
1. Fäst tidrapporten igen.

_Först rapporterad den 7 maj 2024._

