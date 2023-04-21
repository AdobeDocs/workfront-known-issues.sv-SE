---
title: "Korrektur: [!UICONTROL Active Proof Stages] fältet är tomt"
description: "När en användare skapar ett bevis och sedan visar det i en rapport som [!UICONTROL Document Version] eller [!UICONTROL Proof Approval] de ser att [!UICONTROL Active Proof Stages] fältet är tomt. Detta inträffar när korrekturet skapas efter att dokumentet har överförts, antingen som en [!UICONTROL Simple Proof] eller en [!UICONTROL Advanced Proof] med [!UICONTROL Basic Workflow]."
hidefromtoc: true
source-git-commit: 67d7e907af995a40ecad3792584ebf8768ad4570
workflow-type: tm+mt
source-wordcount: '161'
ht-degree: 0%

---


# Korrektur: [!UICONTROL Active Proof Stages] fältet är tomt

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof. Article created by request.-->

>[!NOTE]
>
>Produktgruppen håller på att utvärdera den här problemlösningen, vilket kan kräva produktförbättringar. Produktförbättringarna presenteras i produktmeddelandena och inte i underhållsuppdateringarna.

När en användare skapar ett korrektur och sedan visar det korrekturet i en rapport, till exempel en [!UICONTROL Document Version] eller [!UICONTROL Proof Approval] de ser att [!UICONTROL Active Proof Stages] fältet är tomt. Detta inträffar när korrekturet skapas efter att dokumentet har överförts, antingen som en [!UICONTROL Simple Proof] eller en [!UICONTROL Advanced Proof] med [!UICONTROL Basic Workflow].

**Tillfällig lösning**

Gör något av följande:

* När du lägger till ett nytt dokument lägger du till det som ett korrektur genom att välja [!UICONTROL Add new] > [!UICONTROL Proof].
* Skapa ett korrektur av ett befintligt dokument som [!UICONTROL Advanced Proof] med [!UICONTROL Automated Workflow].

_Först rapporterad den 31 augusti 2022._

