---
title: '"Dokument: Behörigheter ärvs inte när ett dokument flyttas till ett nytt projekt'
description: '"När en användare flyttar ett dokument till ett annat projekt ärver dokumentet inte delningsbehörigheter från det nya projektet. Dokumentet delas inte med användarna som projektet delas till. '''
hidefromtoc: true
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
source-git-commit: 17906db6aadc416c8be01e60d1b796143c97c061
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---

# Dokument: Behörigheter ärvs inte när ett dokument flyttas till ett nytt projekt

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Valid issue, won't fix.-->

När en användare flyttar ett dokument till ett annat projekt ärver dokumentet inte delningsbehörigheter från det nya projektet. Dokumentet delas inte med användarna som projektet delas till.

**Tillfällig lösning:**

1. Navigera till dokumentets överordnade objekt, till exempel Projekt, Uppgift eller Utgåva.

1. Ta bort ärvda behörigheter från det överordnade objektets resurslista genom att klicka på&quot;x&quot; bredvid ärvda behörigheter och klicka sedan på **[!UICONTROL Save]**.

1. Lägg till ärvda behörigheter igen genom att gå tillbaka till det överordnade objektets resurslista och klicka på **[!UICONTROL Undo]** bredvid ärvda behörigheter och klicka sedan på **[!UICONTROL Save]**.

Du kan också anteckna dokumentets ID (finns i URL:en för [!UICONTROL Document Details] sida) och kontakt [!DNL Workfront] kundsupport.

_Först rapporterad den 6 januari 2023._
