---
title: Workfront Maintenance Updates
description: Underhållsuppdateringar för [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 89eb14bfaccb517764af1711ca31e2926de63795
workflow-type: tm+mt
source-wordcount: '3288'
ht-degree: 0%

---

# [!DNL Workfront] Underhållsuppdateringar

Följande underhållsuppdateringar gjordes 2024.

>[!NOTE]
>
>Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Supporten meddelar dig när ett ärende som du har skickat har åtgärdats.

Underhållsuppdateringar före 2024 finns på [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

## Uppdateringar i maj 2024

+++**(Planerat) Underhållsuppdatering 9 maj 2024**

### (Planerat) Underhållsuppdatering 9 maj 2024

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Supporten meddelar dig när ett ärende som du har skickat har åtgärdats.

+++

+++**Underhållsuppdatering 2 maj 2024**

### Underhållsuppdatering 2 maj 2024

#### Loggningstid

**Det går inte att redigera timmar för aktiviteter eller problem**

När en användare försöker redigera timmar för en uppgift eller ett problem sparas inte ändringarna.

+++

## Uppdateringar i april 2024

+++**Underhållsuppdatering 25 april 2024**

### Underhållsuppdatering 25 april 2024

#### Uppdateringar

**Numrerade listor numreras inte korrekt**

När en användare skickar en kommentar som innehåller en numrerad lista visas felaktig numrering i uppdateringen.

Detta har rapporterats i den nya kommentarsfunktionen.

**Texten bevaras inte när du navigerar bort och tillbaka till kommentaren**

När en användare skriver en kommentar som innehåller ett @mention, navigerar sedan bort från och tillbaka till kommentaren innan den skickas, saknas all text som har angetts efter @mention i kommentarutkastet.

Detta har rapporterats i den nya kommentarsfunktionen.

+++

+++**Underhållsuppdatering 18 april 2024**

### Underhållsuppdatering 18 april 2024

#### Agile

**Kanban-kort visar inte anpassade fält**

När en användare visar en Kanban-tavla som har konfigurerats för att inkludera anpassade fält, kanske dessa anpassade fält inte visas.

#### Kalendrar

**Fel vid uppdatering av kalender**

När en användare visar en kalender och uppdaterar sidan visas ett &quot;Hoppfel&quot;. Data i kalendern visas som förväntat, men kan skymmas av felmeddelandet.

#### Egna formulär

**Externa sökfält returnerar inte resultat**

När ett externt uppslagsfält refererar till ett flervalsfält som bara har ett värde markerat, returnerar fältet inte värdet.

Om ett externt uppslagsfält till exempel refererar till ett flervalsfält som har både röda och blå värden markerade, fungerar fältet som förväntat. Om fältet bara har &quot;röd&quot; markerat returnerar det externa sökfältet inget värde.

#### Projekt

**Det går inte att konvertera utgåva till projekt om webbofferiet är bifogat**

När en utgåva har ett webbkorrektur bifogat (ett URL-korrektur med en länk från en extern dokumentleverantör som SharePoint) och en användare försöker konvertera utgåvan till ett projekt, misslyckas konverteringen och projektet skapas inte. Användaren ser följande fel:

&quot;Det gick inte att kopiera filen (fil-GUID). Ta bort filen eller kontakta supporten och försök igen.&quot;

+++

+++**Underhållsuppdatering 11 april 2024**

### Underhållsuppdatering 11 april 2024

#### Sök

**Kan inte redigera från sökning**

När en användare använder Avancerad sökning och försöker redigera eller massredigera sökresultaten, svarar inte redigeringsikonen.

#### Uppdateringar

**Förhandsvisning av bilden i uppdateringar är oskarp**

När en användare tittar på uppdateras och klickar på förstoringsglaset på en bild för att förhandsvisa bilden, blir den förhandsvisning som öppnas extremt pixelerad oskarp.

Om användaren hämtar bilden visas den med den förväntade upplösningen.

**&quot;[!UICONTROL We're unable to post your comment]&quot; när du svarar**

När en användare försöker svara på ett meddelande i den nya kommentarsfunktionen sparas inte svaret och användaren ser följande meddelande:

&quot;[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]&quot;

+++

+++**Underhållsuppdatering 4 april 2024**

### Underhållsuppdatering 4 april 2024

#### Sök

**Kan inte redigera från sökning**

När en användare använder Avancerad sökning och försöker redigera eller massredigera sökresultaten, svarar inte redigeringsikonen.

#### Uppdateringar

**Förhandsvisning av bilden i uppdateringar är oskarp**

När en användare tittar på uppdateras och klickar på förstoringsglaset på en bild för att förhandsvisa bilden, blir den förhandsvisning som öppnas extremt pixelerad oskarp.

Om användaren hämtar bilden visas den med den förväntade upplösningen.

**&quot;[!UICONTROL We're unable to post your comment]&quot; när du svarar**

När en användare försöker svara på ett meddelande i den nya kommentarsfunktionen sparas inte svaret och användaren ser följande meddelande:

&quot;[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]&quot;

+++

+++**Underhållsuppdatering 4 april 2024**

### Underhållsuppdatering 4 april 2024

#### Integreringar

**Dokument som inte bifogas när en begäran skapas från[!DNL Outlook]**

När en användare skapar en begäran från [!DNL Outlook], bifogas inte dokumenten i e-postmeddelandet till begäran.

Detta har rapporterats för följande typer av bifogade filer:

XLS PDF

#### Loggningstid

**Användaren kan inte logga tid för den aktuella dagen**

När en användare försöker logga tid i uppdateringsområdet är den aktuella dagen nedtonad och användaren kan inte logga tid för den aktuella dagen.

#### Uppdateringar

<!--no article-->

**Fel vid visning av kommentarer**

När en användare försöker visa kommentarer i den nya kommentarsfunktionen kan han/hon inte se kommentarerna och i stället se följande fel:

&quot;Något gick fel. Försök igen senare.&quot;

De gamla kommentarfunktionerna fungerar som förväntat.

+++

## Uppdateringar i mars 2024

+++**Underhållsuppdatering 28 mars 2024**

### Underhållsuppdatering 28 mars 2024

#### Integreringar

**Dokument som inte bifogas när en begäran skapas från[!DNL Outlook]**

När en användare skapar en begäran från [!DNL Outlook], bifogas inte dokumenten i e-postmeddelandet till begäran.

Detta har rapporterats för följande typer av bifogade filer:

XLS PDF

#### Korrektur

**Korrektur finns kvar på widgeten Mina godkännanden**

Ett korrektur som ska försvinna från widgeten Mina godkännanden finns kvar på widgeten. Detta kan inträffa när flera användare fattar beslut om ett korrektur samtidigt, eller när en användare fattar ett beslut och snabbt ändrar det.

#### Resurshantering

**Skillnad i budgeterade timmar**

Budgeterade timmar som visas i något av följande områden kanske inte matchar dem som visas i något av dessa områden:

* Affärsärende
* Rapporter
* Resursbudgeteringsverktyg

#### Uppgifter

**Föregående verktygstips visar inte aktivitetsnamnet**

När en användare visar en uppgiftslista och för pekaren över en föregående ikon för att få mer information, visas inte namnet på föregående aktivitet i det verktygstips som visas.

#### Uppdateringar

**Dokumentkommentarer visas inte i uppdateringar av det överordnade objektet**

När en användare gör en kommentar i ett dokument, visas inte kommentaren omedelbart i uppdateringsområdet för dokumentets överordnade objekt.

Det här problemet har rapporterats i den nya kommentarsfunktionen. Kommentarerna visas som förväntat i den äldre kommentarsfunktionen.

**Det går inte att tagga en användare**

När en användare är taggad i en kommentar är kommentaren inte synlig för den taggade användaren. Dessutom meddelas inte den taggade användaren om kommentaren, varken via e-post eller via ett meddelande i appen.

Detta har rapporterats i de tidigare kommentarerna.

+++

+++**Workfront Fusion Maintenance Update 28 mars 2024**

### Workfront Fusion Maintenance Update 28 mars 2024

**RuntimeError med 200 svar från Workfront-modulen**

En Workfront-modul kan returnera en `RuntimeError [200]` svar. 2000 innebär ett lyckat svar, men felet visar att begäran misslyckades.

Detta kan inträffa om svaret är mycket långt. Data returneras till Fusion, men kan inte behandlas av Fusion.

+++

+++**Underhållsuppdatering 21 mars 2024**

### Underhållsuppdatering 21 mars 2024

#### Uppdateringar

**Stora mellanrum mellan rader**

När en användare skriver en uppdatering med flera rader med tangenten Retur eller Retur, eller klistrar in flera rader i en uppdatering, visas uppdateringen som förväntat. Om en användare sedan visar uppdateringen i en rapport finns det stora mellanrum mellan raderna.

Detta har rapporterats i den nya kommentarsfunktionen.

**Det går inte att tagga en användare med @**

När en användare taggar en annan användare med @ i en kommentar, läggs användaren inte till i området med taggade användare och får inget meddelande om kommentaren.

Den här korrigeringen gäller bara för den nya kommentarsfunktionen.

+++

+++**Underhållsuppdatering 14 mars 2024**

### Underhållsuppdatering 14 mars 2024

#### Korrektur

**Korrektur som skapats från länkade dokument saknar korrekturmall**

När en användare skapar ett korrektur från ett länkat dokument, tillämpas inte korrekturmallen korrekt och korrekturet kanske saknar information, till exempel arbetsflödet.

Detta gäller även korrektur som skapats via API och Workfront Fusion.

#### Användare

**Lägre åtkomstnivåer är inte tillgängliga när användaren skapas**

När en användare skapar en annan användare är endast den första användarens åtkomstnivå tillgänglig för den nya användaren. Alla åtkomstnivåer med lägre behörigheter än de som användaren skapar bör vara tillgängliga att tilldela till den nya användaren.

+++

+++**Underhållsuppdatering 7 mars 2024**

### Underhållsuppdatering 7 mars 2024

#### Varumärkena

**400 fel när en uppgift läggs till på en anslagstavla**

När en användare visar ett projekt och försöker lägga till en uppgift på en anslagstavla läggs uppgiften inte till och användaren ser följande fel:

Fel: &quot;400: undefined /boards-service/graphql&quot;

#### Startsida

**Fel vid infogad redigering av en uppgift i widgeten Min uppgift**

När en användare försöker att infoga en redigering i widgeten Mina uppgifter ser han/hon följande fel:

&quot;Ett fel har inträffat och vi arbetar för att lösa problemet. Om du vill fortsätta med ditt arbete kan du försöka med att uppdatera den här webbläsarsidan.&quot;


#### Utjämning av arbetsbelastning

**Planerade timmar uppdateras inte i Utjämning av arbetsbelastning**

När de planerade timmarna i ett projekt uppdateras uppdateras de inte i Utjämning av arbetsbelastning. Detta kan inträffa även om ändringen återspeglas korrekt i projektet.

+++

++**Workfront Fusion Maintenance Update den 7 mars 2024

**Workfront Proof > Watch Proof Module - timeout**

Scenarier där Workfront Proof > Watch Proof-modulen används kan inaktiveras på grund av timeout för Watch-korrekturmodulen.

+++

## Uppdateringar i februari 2024

+++**Underhållsuppdatering 29 februari 2024**

### Underhållsuppdatering 29 februari 2024

#### Uppdateringar

**Uppdateringar: Skärmen blir tom när en användare från ett annat företag svarar**

När en användare försöker svara på en kommentar av en användare i ett annat företag, blir skärmen tom.

Detta beror på att användaren inte har behörighet att se användare från andra företag.

+++

+++**Underhållsuppdatering 22 februari 2024**

### Underhållsuppdatering 22 februari 2024

#### Startsida

**[!UICONTROL Home]: [!UICONTROL Workspace] och punkter inte läses in**

När en användare loggar in kan följande inträffa:

* Användarens nya [!UICONTROL Home Workspace] läser inte in och felmeddelandet visas &quot;[!UICONTROL We are unable to load your Workspace information. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;
* Användarens stift läses inte in och felet visas[!UICONTROL Your pins are unavailable because of a system error. Try refreshing your browser to fix the problem.]&quot;

#### Användare

**Gruppadministratören kan inte ange eller ändra en användares åtkomstnivå**

<!--no article-->

När en gruppadministratör försöker ändra åtkomstnivån för en användare kan något av följande inträffa:

* Fältet för åtkomstnivå är inaktiverat.
* Gruppadministratören kan inte välja en lägre åtkomstnivå.

#### Utjämning av arbetsbelastning

**Etikett för ej arbetstid**

Utjämning av arbetsbelastning och personlig tid i kalendern visas nu[!UICONTROL Non-working Hours]&quot; för den tid som en användare ger sig av. Tidigare visades &quot;[!UICONTROL Working Hours]&quot; för arbetstid.

+++

+++**Underhållsuppdatering 15 februari 2024**

### Underhållsuppdatering 15 februari 2024

#### Problem

**Tidsfält sparar felaktig tid vid gruppredigering**

När en användare gör stora redigeringsproblem och väljer ett datum och en tid för ett datumfält och sparar, är tiden som sparas i det här fältet i utgåvan inte den tid som användaren valde. I stället ser tiden ut att konverteras till UTC när användaren sparar.

#### Uppgifter

**Användaren är inte tilldelad från en eller flera uppgifter**

En användare kan automatiskt tas bort från en uppgift som de har tilldelats. Detta kan inträffa för en eller flera uppgifter. Uppdelningen visas inte i aktiviteternas systemuppdateringar, men den visas inte i avsnittet Uppdatera feeds på inställningsmenyn.

#### Uppdateringar

**Alternativet Inaktiverad bild är tillgängligt när du redigerar en kommentar**

Efter [!DNL Workfront] administratören har inaktiverat alternativet att lägga till bilder i kommentarer. Det alternativet är inte tillgängligt när du skapar en kommentar. Om en användare redigerar en befintlig kommentar är dock bildalternativet tillgängligt.

+++

+++**Underhållsuppdatering 8 februari 2024**

### Underhållsuppdatering 8 februari 2024

#### Varumärkena

**Det går inte att flytta ett kort i en kolumn med hjälp av [!UICONTROL Move] alternativ**

När en användare försöker flytta ett kort i en kolumn med hjälp av[!UICONTROL Top of column]&quot; eller &quot;[!UICONTROL Bottom of column]&quot;i menyn med tre punkter flyttas kortet inte.

**Korten behålls vid ändring av upprepning**

När en användare visar en upprepning på en anslagstavla och sedan ändrar upprepningen, är korten som visas för den nya upprepningen korten från en iteration som användaren visade tidigare.

#### Rapporter

**Kolumnen Inget värde visar inga resultat**

När en diagramrapport har[!DNL No value]kolumnen visar inga data, även om det ska finnas data.

#### Resurshantering

**Felaktiga ekonomiska beräkningar på grund av problem med jobbroller**

Timmar- och finansberäkningar kan vara felaktiga, vilket ger en kostnad på 0 även om timmar är inloggade i en jobbroll som har en kostnadstariff.

Detta beror på att jobbroller automatiskt skapar dubblettfrekvenser utan start- eller slutdatum. Eftersom de inte har några start- eller slutdatum behandlas de som värdet 0 när finansiella beräkningar körs.

+++

+++**Underhållsuppdatering 1 februari 2024**

### Underhållsuppdatering 1 februari 2024

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
