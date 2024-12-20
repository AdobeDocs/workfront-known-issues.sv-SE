---
title: 'Korrektur: fältet [!UICONTROL Active Proof Stages] är tomt'
description: När en användare skapar ett korrektur och sedan visar det korrekturet i en rapport, t.ex. en [!UICONTROL Document Version]- eller [!UICONTROL Proof Approval]-rapport, ser de att fältet [!UICONTROL Active Proof Stages] är tomt. Detta inträffar när korrekturet skapas efter att dokumentet har överförts, antingen som [!UICONTROL Simple Proof] eller som en [!UICONTROL Advanced Proof] med en [!UICONTROL Basic Workflow].
feature: Digital Content and Documents
hidefromtoc: true
exl-id: 1cd7baed-b561-48fa-ba58-e0533db01696
source-git-commit: d4dd73ea9edc802c945ee7b8aa478bf18b1c662c
workflow-type: tm+mt
source-wordcount: '161'
ht-degree: 0%

---

# Korrektur: fältet [!UICONTROL Active Proof Stages] är tomt

<!--Requested article. This Known Issue is on the TOC for both Workfront and Workfront Proof.-->

>[!NOTE]
>
>Produktgruppen håller på att utvärdera den här problemlösningen, vilket kan kräva produktförbättringar. Produktförbättringarna presenteras i produktmeddelandena och inte i underhållsuppdateringarna.

När en användare skapar ett korrektur och sedan visar det korrekturet i en rapport, t.ex. en [!UICONTROL Document Version]- eller [!UICONTROL Proof Approval]-rapport, ser de att fältet [!UICONTROL Active Proof Stages] är tomt. Detta inträffar när korrekturet skapas efter att dokumentet har överförts, antingen som [!UICONTROL Simple Proof] eller som en [!UICONTROL Advanced Proof] med en [!UICONTROL Basic Workflow].

**Tillfällig lösning**

Gör något av följande:

* När du lägger till ett nytt dokument lägger du till det som ett korrektur genom att välja [!UICONTROL Add new] > [!UICONTROL Proof].
* När du skapar ett korrektur från ett befintligt dokument skapar du det som en [!UICONTROL Advanced Proof] med [!UICONTROL Automated Workflow].

_Först rapporterad den 31 augusti 2022._
