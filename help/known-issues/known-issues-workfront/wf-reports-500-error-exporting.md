---
title: "Rapporter: 500 fel vid export av en rapport"
description: "När en användare försöker exportera en rapport exporteras inte rapporten och användaren ser ett fel. Det finns en lösning."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 1f516bdbea40c2946dec1935b7ada63b28b3451c
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 0%

---


# Rapporter: 500 fel vid export av en rapport

När en användare försöker exportera en rapport exporteras inte rapporten och användaren ser följande fel:

500: Det går inte att anropa com.attask.biz.Parameter.getDisplayType() eftersom parametern är null /attask/api-internal/report/export

Detta inträffar när rapporten refererar till ett anpassat valutafält på projektnivå.

**Tillfällig lösning**

Ta bort kolumnen som refererar till det anpassade valutafältet och exportera rapporten igen.

_Först rapporterad den 4 april 2024._
