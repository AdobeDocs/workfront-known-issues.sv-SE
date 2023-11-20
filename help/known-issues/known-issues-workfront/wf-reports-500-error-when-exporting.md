---
title: "Rapporter: 500 fel vid export av en rapport"
description: "När en användare försöker exportera en rapport misslyckas exporten med ett 500-fel."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# Rapporter: 500 fel vid export av en rapport

När en användare försöker exportera en rapport misslyckas exporten med följande fel:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Detta har rapporterats i rapporter där en `valueexpression` referera till `lastNote` anteckningstext.

_Först rapporterad 8 november 2023._
