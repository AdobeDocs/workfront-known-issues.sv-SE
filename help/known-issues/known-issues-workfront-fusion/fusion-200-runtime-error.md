---
title: "Workfront Fusion: RuntimeError med 200 svar från Workfront-modulen"
description: En Workfront-modul kan returnera svaret "RuntimeError [200]". 2000 innebär ett lyckat svar, men felet visar att begäran misslyckades.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: d99f5b467f31d4e4a77cabe25671470beb847eed
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 0%

---

# Workfront Fusion: RuntimeError med 200 svar från Workfront-modulen

<!--

>[!NOTE]
>
>This issue was fixed on May 9, 2024.

-->

En Workfront-modul kan returnera ett `RuntimeError [200]`-svar. 2000 innebär ett lyckat svar, men felet visar att begäran misslyckades.

Detta kan inträffa om svaret är mycket långt. Data returneras till Fusion, men kan inte behandlas av Fusion.

_Först rapporterad den 3 januari 2024._
