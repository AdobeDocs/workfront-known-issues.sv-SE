---
title: "Uppdateringar: Extra rader i kommentarer som gjorts via API eller Workfront Fusion"
description: "När en användare skickar in en kommentar via API:t eller via Workfront Fusion visas extra rader i kommentaren som visas i uppdateringsområdet. Ibland finns det så många rader att användaren måste rulla nedåt för att kunna se kommentarinnehållet."
hidefromtoc: true
feature: Updates and Notifications
source-git-commit: 1854e4a003722f1398c703dfba7bc23ef534f81f
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---


# Uppdateringar: Extra rader i kommentarer som gjorts via API eller [!DNL Workfront Fusion]

När en användare skickar en kommentar via API:t eller via [!DNL Workfront Fusion]visar kommentaren som visas i uppdateringsområdet extra rader. Ibland finns det så många rader att användaren måste rulla nedåt för att kunna se kommentarinnehållet.

Detta har rapporterats i den nya kommentarsfunktionen.

**Tillfällig lösning**

Problemet orsakas av mellanslag eller radbrytningar i HTML som har skickats in i kommentaren.

För att undvika detta bör du se till att hela HTML finns på samma rad, utan mellanslag eller radbrytningar mellan elementen i HTML.

Om du vill visa kommentarer som påverkas utan de extra raderna växlar du till den klassiska kommentarfunktionen.

_Först rapporterad den 27 oktober 2023._
