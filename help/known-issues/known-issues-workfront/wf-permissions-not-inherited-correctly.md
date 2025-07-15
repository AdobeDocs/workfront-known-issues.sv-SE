---
title: 'Behörigheter: Objektbehörigheter ärvs inte korrekt'
description: Ärvda behörigheter tillämpas inte korrekt på objekt. Detta kan inträffa på grund av de ärvda behörigheternas komplexitet.
hidefromtoc: true
feature: Projects, Tasks, Work Management
source-git-commit: 798be3dd7ef5e7bf0ecf14484242f7758ac9d9a4
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 0%

---


# Behörigheter: Objektbehörigheter ärvs inte korrekt

>[!NOTE]
>
>Produktgruppen håller på att utvärdera den här problemlösningen, vilket kan kräva produktförbättringar. Produktförbättringarna presenteras i produktmeddelandena och inte i underhållsuppdateringarna.

Ärvda behörigheter tillämpas inte korrekt på objekt. Detta kan inträffa på grund av komplexiteten i de ärvda behörigheterna, som kan påverkas av följande:

* Objektet delas med ett stort antal personer
* Ett stort antal objekt påverkas av en ärvd behörighetsändring

**Tillfällig lösning**

Du kan undvika det här problemet genom att begränsa objektens storlek eller komplexitet. Du bör inte ha fler än 10 000 underordnade objekt under något överordnat objekt.

_Först rapporterad den 21 mars 2025._
