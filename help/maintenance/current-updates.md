---
title: Workfront Maintenance Updates
description: Underhållsuppdateringar för [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 17e60b281dc05073247083257121d8809a271722
workflow-type: tm+mt
source-wordcount: '1289'
ht-degree: 0%

---

# [!DNL Workfront] Underhållsuppdateringar

Följande underhållsuppdateringar gjordes 2024.

>[!NOTE]
>
>Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Supporten meddelar dig när ett ärende som du har skickat har åtgärdats.

Underhållsuppdateringar före 2023 finns på [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

## Uppdateringar i februari 2024

+++**Underhållsuppdatering 1 februari 2024**

### (Planerat) Underhållsuppdatering den 1 februari 2024

#### Inloggning

**Användare som använder enkel inloggning omdirigeras inte till den ursprungliga platsen när de loggar in**

När en användare är på en sida i [!DNL Workfront] och loggar in med enkel inloggning när inloggningen är klar dirigeras de till [!UICONTROL Home] i stället för sidan som de var på innan de loggade in.

#### Mallar

**Fel vid kopiering av mallar**

När en användare försöker kopiera en ny eller befintlig mall kopieras inte mallen och användaren ser följande fel:

&quot;[!UICONTROL ID Cannot be Null]&quot;

+++

## Uppdateringar i januari 2024

+++**Underhållsuppdatering (snabbkorrigering) 30 januari 2024**

### Underhållsuppdatering (snabbkorrigering) 30 januari 2024

#### Rapporter

**Externt API-fält visar inte alla tillgängliga värden i listor och rapporter**

Tidigare kunde användarna se det valda värdet (och redigera värdet) för ett externt uppslagsfält i listor och rapporter, men kunde inte se listrutan med alternativen från API:t.

När ett anpassat fält för extern sökning används i en lista eller rapport är nu listrutan med alla alternativ från det externa API:t tillgänglig.

+++

+++**Underhållsuppdatering 25 januari 2024**

### Underhållsuppdatering 25 januari 2024

#### Varumärkena

**Kort som inte flyttas till rätt kolumn när status ändras**

När statusen för det länkade objektet för ett anslutet kort ändras direkt på objektet flyttas kortet inte till rätt kolumn. Om objektets status ändras på kortet, eller om kortet dras till den nya kolumnen, fungerar kortet som förväntat.

#### Meddelanden

**Markeringsmeddelanden som de visas kvarstår inte**

När en användare markerar sina meddelanden som de ser och sedan navigerar till en annan sida på [!DNL Workfront]visas fortfarande antalet olästa meddelanden som fanns innan användaren markerade dem som synliga och meddelanden fortfarande när användaren klickar på ikonen. Detta fortsätter om användaren markerar dem som synliga och navigerar till en annan sida eller tillbaka till den ursprungliga sidan.

#### Uppdateringar

**Problem med taggning i äldre kommentarer**

När en användare är taggad i en kommentar i den tidigare kommentarsfunktionen uppstår följande problem:

* Endast användarens förnamn finns i kommentaren
* Användarens namn är inte markerat med en @-symbol
* Användarens namn är inte blått
* Användarens namn är inte en länk till den användarens profil

Användaren får som förväntat ett e-postmeddelande om taggen.

+++

+++**Underhållsuppdatering 18 januari 2024**

### Underhållsuppdatering 18 januari 2024

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

#### Egna formulär

**Det går inte att lägga till eller ta bort anpassade formulär gruppvis i malluppgifter**

Om en användare försöker att lägga till eller ta bort ett anpassat formulär gruppvis i en mallåtgärd läggs inte formuläret till eller tas bort, och användaren ser följande fel:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

Om användaren hittar mallen med angivet GUID och sedan försöker lägga till eller ta bort anpassade formulär i resten av malluppgifterna, kommer felet att inträffa igen med ett annat templateID.

Anpassade formulär kan läggas till eller tas bort i en enda mallåtgärd. Det här felet gäller endast för masstillägg och borttagning.

#### Portfolio

**Anpassad terminologi gäller inte för gruppsidan**

När en användare anger anpassad terminologi på Portfolio-nivå, gäller inte termen gruppnivåsidan.

#### Inställningar

**Det går inte att dölja valfria statusvärden**

När en användare försöker dölja valfria statusar på system- och gruppnivå döljs inte statusen. Om användaren visar statusen är alternativet att dölja statusen inte aktiverat, även om användaren aktiverade det och sparade ändringarna.

**Status för standardutleverans saknas för vissa typer av utleveranser i installationsprogrammet**

När en användare visar problem i installationsprogrammet ser de att standardstatusvärdena för problem (Nytt, Pågår och Fullständigt) saknas i vissa typer av problem. Standardstatusvärden har inte möjlighet att ändra utgåvans typ, så användaren kan inte konfigurera om statusvärdena så att de visas för de berörda utgåvorna.

#### Team

**Problem med att ställa in teamstatus för [!UICONTROL Done] knapp**

Följande problem har rapporterats angående status för [!UICONTROL Done] när du redigerar eller skapar ett team:

* Vissa statusar kan saknas i knappområdet Klar i [!UICONTROL New team] eller [!UICONTROL Team Settings] del av ett befintligt team.
* Om användaren försöker spara teamet kan felet&quot;Du måste välja minst en status i varje kategori&quot; visas.

#### Mallar

**Fel vid koppling av mall till projekt**

När en användare försöker koppla en mall till ett projekt visas följande fel:

&quot;Hoppsan! Något gick fel. Kontakta Workfront för att ta reda på vad som gick fel och åtgärda det.&quot;

Detta inträffar när användaren inte har behörigheten Visa för ett anpassat formulär som är kopplat till mallen.

#### Uppdateringar

**Kommentarerna överförs inte mellan gamla och nya upplevelser**

En kommentar som gjorts i det gamla kommentargränssnittet kanske inte syns i det nya kommentarsgränssnittet. Det motsatta kan också inträffa.

+++

+++**Underhållsuppdatering 11 januari 2024**

### Underhållsuppdatering 11 januari 2024

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
