---
title: 'Tidrapporter: Fäst tidrapport går till tom sida'
description: När en användare klickar på ett häftstift i Workfront som är avsett att gå till sin tidrapport, hamnar stiftet i stället på en tom sida. Det finns en lösning.
hidefromtoc: true
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 1aed6a440155c99f8ce0b0f42c44dd9a3c660af4
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 0%

---

# Tidrapporter: Fäst tidrapport går till tom sida

<!--article live for workaround-->

När en användare klickar på ett häftstift i Workfront som är avsett att gå till sin tidrapport, hamnar stiftet i stället på en tom sida.

Detta beror på att URL:en för tidrapporten har ändrats. The `/own` i slutet av URL:en inte längre är rätt URL. Om användaren har fäst en URL som innehåller `/own`, leder nålen till en tom sida.

**Tillfällig lösning**

1. Plocka bort tidrapporten.
1. Ta bort `/own` från slutet av URL:en
1. Fäst tidrapporten igen.

_Först rapporterad den 7 maj 2024._
