---
title: 'Rapporter: 500 fel vid export av en rapport'
description: När en användare försöker exportera en rapport exporteras inte rapporten och användaren ser ett fel. Det finns en lösning.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 0%

---

# Rapporter: 500 fel vid export av en rapport

>[!NOTE]
>
>Problemet korrigerades den 5 april 2024.

När en användare försöker exportera en rapport exporteras inte rapporten och användaren ser följande fel:

500: Det går inte att anropa com.attask.biz.Parameter.getDisplayType() eftersom parametern är null /attask/api-internal/report/export

Detta inträffar när rapporten refererar till ett anpassat valutafält på projektnivå.

**Tillfällig lösning**

Ta bort kolumnen som refererar till det anpassade valutafältet och exportera rapporten igen.

_Först rapporterad den 4 april 2024._
