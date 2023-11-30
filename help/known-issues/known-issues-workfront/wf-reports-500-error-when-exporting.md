---
title: 'Rapporter: 500 fel vid export av en rapport'
description: När en användare försöker exportera en rapport misslyckas exporten med ett 500-fel.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 0%

---

# Rapporter: 500 fel vid export av en rapport

>[!NOTE]
>
>Problemet korrigerades den 30 november 2023.

När en användare försöker exportera en rapport misslyckas exporten med följande fel:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Detta har rapporterats i rapporter där en `valueexpression` referera till `lastNote` anteckningstext.

_Först rapporterad 8 november 2023._
