---
title: '''Projekt: Fel när projektägaren togs bort från rubriken'
description: När en användare försöker ta bort en projektägare från huvudet i ett projekt tas inte Projektägaren bort och användaren ser ett felmeddelande.
hidefromtoc: true
exl-id: 3a995df4-5d6a-44e4-a644-997931c044bf
source-git-commit: a033108ac2c267d36e6bec1cdc53b5917b61bd16
workflow-type: tm+mt
source-wordcount: '88'
ht-degree: 0%

---

# Projekt: Fel vid borttagning av [!UICONTROL Project Owner] från sidhuvudet

>[!NOTE]
>
>Problemet löstes den 9 september 2022.

När en användare försöker ta bort en [!UICONTROL Project Owner] från projektets huvud [!UICONTROL Project Owner] tas inte bort och användaren ser följande felmeddelande:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Tillfällig lösning**

Ta bort [!UICONTROL Project Owner] från projektets [!UICONTROL Details] område.

_Först rapporterad den 9 augusti 2022._
