---
title: "Workfront: ZScalar-inställningar kan ge sämre prestanda"
description: "ZScalars webbtjänst använder http/1.1 som standard, vilket kan ge sämre prestanda i Workfront."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 0%

---


# Workfront: ZScalar-inställningar kan ge sämre prestanda

>[!NOTE]
>
>Detta är ett problem med ZScalar och kommer inte att åtgärdas av Workfront.

ZScalars webbtjänst använder `http/1.1` som standard, vilket kan ge sämre prestanda i Workfront.

**Tillfällig lösning**

Konfigurera ZScalar-programvaran så att den använder `http/2`. Detta kan inte konfigureras i Workfront.

Du hittar information om `http/2` i dokumentationen för ZScalar.

_Först rapporterad den 18 november 2024._
