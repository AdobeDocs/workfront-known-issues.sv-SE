---
title: 'Workfront: ZScaler-inställningar kan ge sämre prestanda'
description: ZScalers webbtjänst använder http/1.1 som standard, vilket kan ge sämre prestanda i Workfront.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 0%

---

# Workfront: ZScaler-inställningar kan ge sämre prestanda

>[!NOTE]
>
>Detta är ett problem med ZScaler och kommer inte att åtgärdas av Workfront.

ZScalers webbtjänst använder `http/1.1` som standard, vilket kan ge sämre prestanda i Workfront.

**Tillfällig lösning**

Konfigurera ZScaler-programvaran så att den använder `http/2`. Detta kan inte konfigureras i Workfront.

Du hittar information om `http/2` i dokumentationen för ZScaler.

_Först rapporterad den 18 november 2024._
