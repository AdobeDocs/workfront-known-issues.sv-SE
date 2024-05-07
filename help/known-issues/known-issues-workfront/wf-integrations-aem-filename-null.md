---
title: 'Integreringar: Filnamnet är null när det skickas till AEM via integration'
description: '"När en stor fil (över 100 MB) skickas till Adobe Experience Manager via Workfront-integreringen är filnamnet i AEM null. '''
hidefromtoc: true
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
source-git-commit: 3ca57c76dc50a348cf6d85d4d3e7366834a5e791
workflow-type: tm+mt
source-wordcount: '104'
ht-degree: 0%

---

# Integreringar: Filnamnet är &quot;null&quot; när det skickas till dokumentintegrering

När en stor fil (över 100 MB) skickas till en dokumentleverantör via en Workfront-integrering blir filnamnet i dokumentprovidern &quot;null&quot;.

Detta har rapporterats för både ZIP- och TIF-filer.

**Tillfällig lösning**

Gör något av följande:

* Koppla dokumentnamnet till titeln i dokumentprovidern.
* Ange filnamnet direkt i dokumentprovidern.

_Först rapporterad den 23 april 2024._

