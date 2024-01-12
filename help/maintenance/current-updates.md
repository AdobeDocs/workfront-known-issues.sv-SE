---
title: Workfront Maintenance Updates
description: Underhållsuppdateringar för [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: b74a577bc652f822b4ff9d835952f9b8145ae6dc
workflow-type: tm+mt
source-wordcount: '507'
ht-degree: 0%

---

# [!DNL Workfront] Underhållsuppdateringar

Följande underhållsuppdateringar gjordes 2024.

>[!NOTE]
>
>Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Supporten meddelar dig när ett ärende som du har skickat har åtgärdats.

Underhållsuppdateringar före 2023 finns på [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

## Uppdateringar i januari 2024

+++**Underhållsuppdatering 12 januari 2024**

### Underhållsuppdatering 12 januari 2024

#### Varumärkena

**Kan inte bifoga ett dokument till ett kort**

När en användare försöker bifoga ett dokument till ett anslutet kort kan han eller hon välja det dokument som ska bifogas, men dokumentet visas inte i kortets dokumentområde och dokumentet är inte bifogat till objektet som kortet är anslutet till.

Detta har rapporterats i kort som är kopplade till problem.

**Kortet visas på flera sprutor**

När en användare visar en utskrift på korten visas kort som är i olika utskrifter på ritbordet. Det här problemet är tillfälligt.

**Kortet stängs inte när du använder vyn för anslagstavlor i ett projekt**

När en användare visar vyn för anslagstavlor i en uppgiftslista i ett projekt och skapar ett kort, stängs eller sparas inte kortet. Detta förhindrar användaren från att gå tillbaka till projektet.

För att stänga kortet måste användaren redigera URL:en för att ta bort&quot;board&quot; och allt till höger om&quot;board&quot;.

**Korten behålls vid ändring av upprepning**

När en användare visar en upprepning på en anslagstavla och sedan ändrar upprepningen, är korten som visas för den nya upprepningen korten från en iteration som användaren visade tidigare.

**Fel i [!UICONTROL Comments] kortavsnitt**

När en användare visar ett kort och rullar till [!UICONTROL Comments], avsnitt, kommentarer visas inte och användaren ser följande fel:

&quot;[!UICONTROL Something went wrong. Please try again later.]&quot;

**Problem vid visning av delaktivitetsstatus**

Följande problem har rapporterats när det gäller att visa status för underaktiviteter på ett kort i Boards:

* Statusen visas som &quot;Välj status&quot; även när aktiviteten redan har en status. Den här statusen visas när du visar uppgiften direkt.
* Om användaren försöker välja en status, blir skärmen tom och måste uppdateras.

**&quot;[!UICONTROL You have no access]&quot; när du visar kommentarer på ett kort**

När en användare försöker visa kommentarer på ett kort som inte är anslutet till en [!DNL Workfront] visas följande meddelande:

&quot;[!UICONTROL You have no access to view comments on this object]&quot;

Detta kan inträffa även när användaren tidigare kan se kommentarer på kortet.

+++

+++**Underhållsuppdatering 11 januari 2023**

### Underhållsuppdatering 11 januari 2023

#### Varumärkena

**Slutförda kort läses inte in korrekt på dynamiska kort**

Tidigare var det enda sättet att lägga in det färdiga arbetet på en dynamisk anslagstavla att ladda korten som arkiverade kort. I annat fall lästes inte de färdiga korten in alls. Detta orsakade problem med att kunna hitta kort.

När du skapar ett dynamiskt kort läses färdiga kort in som standard som arkiverade kort, men du kan välja Arkivera inte ifyllda kort för att läsa in alla ifyllda kort på kortet som synliga kort i kolumnen Slutfört.

+++

## Tidigare underhållsuppdateringar

Information om tidigare underhållsuppdateringar finns här:

* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2023](2023-updates.md)
* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2022](2022-updates.md)
* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2021](2021-updates.md)
