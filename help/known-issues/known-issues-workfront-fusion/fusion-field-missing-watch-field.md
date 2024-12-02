---
title: 'Workfront Fusion: Fältet saknas i modulen'
description: När en användare konfigurerar en modul i Workfront Fusion kan det hända att ett fält saknas bland de tillgängliga alternativen. Detta kan inträffa när en användare uppdaterar sina anpassade fält och har använt scenariodesignern inom den senaste timmen.
hidefromtoc: true
feature: Workfront Fusion
exl-id: c5d2d11c-ff31-4189-a630-b0248c02134e
source-git-commit: 7aba3a4ce3e0436a8fd9850197bc44da9dafe347
workflow-type: tm+mt
source-wordcount: '137'
ht-degree: 0%

---

# Workfront Fusion: Fältet saknas i modulen

När en användare konfigurerar en modul i Workfront Fusion kan det hända att ett fält saknas bland de tillgängliga alternativen. Detta kan inträffa när en användare uppdaterar sina anpassade fält och har använt scenariodesignern inom den senaste timmen.

Detta har rapporterats i modulen Workfront > Bevakade fält.

**Tillfällig lösning**

Problemet beror på cachelagring i Workfront Fusion. Eftersom cacheminnet uppdateras varje timme väntar du en timme och försöker sedan igen.

_Först rapporterad den 2 februari 2024, 2024._
