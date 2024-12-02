---
title: 'Workfront Proof: 500 fel vid åtkomst till Workfront Proof via API eller Workfront Fusion'
description: 'När en användare kommer åt åtgärden getAllProofs i API:t för Korrektur returnerar Workfront Proof-servern meddelandet: 500 Internal Server Error'
hidefromtoc: true
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
source-git-commit: 2426476490c3762c7511afee99380afa0bfd85e3
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 0%

---

# [!DNL Workfront Proof]: 500 fel vid åtkomst till [!DNL Workfront Proof] via API eller [!DNL Workfront Fusion]

>[!NOTE]
>
>Produktgruppen håller på att utvärdera den här problemlösningen, vilket kan kräva produktförbättringar. Produktförbättringarna presenteras i produktmeddelandena och inte i underhållsuppdateringarna.

<!--This article is on Proof and Fusion TOCs-->

När en användare kommer åt [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] -åtgärden returnerar servern följande meddelande:

[!UICONTROL 500 Internal Server Error]

Eftersom [!DNL Workfront Fusion] använder [!DNL Workfront Proof] API för [!DNL Workfront Proof]-moduler kan det här felet återställas till en modul och ett scenario avbryts.

_Först rapporterad den 28 april 2023._
