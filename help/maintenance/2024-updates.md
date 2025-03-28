---
title: Workfront Maintenance Updates in 2024
description: Underhållsuppdateringar för  [!DNL Adobe Workfront]
feature: Get Started with Workfront
source-git-commit: 1a3bb95b27fb660011ac4b0380eb599f77319c2f
workflow-type: tm+mt
source-wordcount: '7155'
ht-degree: 0%

---

# [!DNL Workfront] underhållsuppdateringar

>[!NOTE]
>
>Mer information om underhållsavbrott för alla Adobe-produkter, inklusive Workfront, finns på [Adobe-statussidan](https://status.adobe.com/).

På den här sidan beskrivs de problem som har åtgärdats i de veckovisa uppdateringarna av Workfront.

Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

Underhållsuppdateringar före 2024 finns i [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

Följande underhållsuppdateringar gjordes 2024.

## Uppdateringar i december 2024

+++**Underhållsuppdatering 19 december 2024**

### Underhållsuppdatering 19 december 2024

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. Workfront Support meddelar dig när ett problem som du har skickat har åtgärdats.

+++

+++**Underhållsuppdatering 12 december 2024**

### Underhållsuppdatering 12 december 2024

#### Kontrollpaneler

**Kolumnen försvinner när den används för sortering i en instrumentpanelsrapport**

När du sorterar en rapport som placerats i en kontrollpanel efter en kolumn, försvinner kolumnen och innehållet sorteras inte.

#### Rapporter

**Gruppkolumnen under diagramalternativet orsakar fel**

När du aktiverar alternativet Gruppera kolumn under diagram i en rapport med ett diagram visas följande felmeddelande: &quot;Ett fel har inträffat och vi arbetar för att lösa problemet. Om du vill fortsätta med ditt arbete kan du försöka med att uppdatera den här webbläsarsidan.&quot;

**Ikonerna Redigera och Ta bort gruppvis saknas i rapporter**

Om du försöker redigera eller ta bort flera rapportobjekt samtidigt visas ibland inte ikonerna Redigera och Ta bort.

**Fel i projektrapporter (ekonomiska data)**

Ett snabbfel visas då och då för Project-rapporter (ekonomiska data), både på informationssidan och på matrissidan.

Som en del av att åtgärda det här problemet räknas projekt i den här rapporttypen inte längre om automatiskt innan data läses in. Användarna måste manuellt beräkna om ekonomin för enskilda projekt för att uppdatera data i en ekonomisk datarapport.

+++

+++**Underhållsuppdatering 5 december 2024**

### Underhållsuppdatering 5 december 2024

#### Egna formulär

**Det går inte att lägga till aktivitetsfälten &quot;stimbyHours&quot; eller &quot;hoursPerPoint&quot;**

När en användare försöker lägga till fälten &quot;estimeraByHours&quot; eller &quot;hoursPerPoint&quot; i ett anpassat formulär i formulärbyggaren visas ett felmeddelande: &quot;Detta är ett ogiltigt anpassat uttryck, försök igen.&quot;

**Visningslogik fungerar inte i anpassade formulär**

När en användare anger information i ett anpassat formulär med visningslogik visas inte fält som ska visas baserat på visningslogiken.

#### Startsida

**Medarbetare visade knappen &quot;Arbeta med den&quot; som inte fungerar**

Medverkande användare har tillgång till en icke-funktionell&quot;Work on it&quot;-knapp i widgeten Mitt arbete i hemmet.

#### Rapporter

**Anpassade kvartal visas inte i rapportuppmaningar**

När en användare kör en rapport med en datumbaserad fråga visas inte anpassade kvartal i listan med val för frågan.

+++

## Uppdateringar i november 2024

+++**Underhållsuppdatering 28 november 2024**

### Underhållsuppdatering 28 november 2024

#### Projekt

**Det går inte att dela projekt på grund av felet&quot;åtkomst till borttagning&quot;**

När användaren försöker dela ett projekt visas ett felmeddelande:&quot;Du har inte tillräcklig behörighet för att ta bort det här projektet&quot;. Detta inträffar trots att användaren inte försöker ta bort projektet, samt att användaren är projektägare och har behörighet att dela och hantera projektet.

#### Rapporter

**Fältet Kategorinamn länkar inte till anpassat formulär**

När du visar en lista i en rapport som innehåller ett kategorinamnfält kan du inte klicka på innehållet i kolumnen Kategorinamn för att öppna motsvarande anpassade formulär.

**Gruppera egna färger i rapporter fungerar inte**

När du tilldelar en anpassad färg till en grupp i Report Builder visas inte färgvalet när rapporten körs.

**Långa inläsningstider för rapporter**

Rapporterna tar längre tid att läsa in. Detta påverkar visning av rapporter och redigering och skapande av rapporter i Report Builder.

**Tidsfält saknas för beräknade datum/tid-fält i rapportmeddelanden**

När en rapport körs med ett anpassat datum/tid-fält som används som kommando saknas fältet för tidsval i kommandotolken.

**Det går inte att visa delade rapporter/instrumentpaneler**

När en användare försöker få åtkomst till en rapport eller kontrollpanel som har delats med dem går det inte att få åtkomst till rapporten eller kontrollpanelen.

#### Tidrapporter

**Deltagare har en Skicka för godkännande-knapp**

Trots att användare med åtkomstnivån Medarbetare inte kan ange timmar i tidrapporter har de en Skicka för godkännande-knapp som de kan klicka på.

+++

+++**Underhållsuppdatering 21 november 2024**

### Underhållsuppdatering 21 november 2024

#### Kontrollpaneler

**Det går inte att interagera med rapportfält för stapeldiagram i instrumentpaneler**

När du försöker klicka på eller föra musen över en stapel i en stapeldiagramrapport i en kontrollpanel öppnas inte informationsmenyn, eller så visas inget verktygstips.

#### Projekt

**Projekt kan inte läsas in**

När du navigerar till ett projekt misslyckas sidan ibland med att läsa in något innehåll.

#### Rapporter

**Massredigering i diagramlistor svarar inte**

När en användare visar ett diagram i en rapport och markerar flera objekt i listan som ska redigeras gruppvis, försvinner markören och textrutorna för massredigeringen slutar svara.

**Knapparna Redigera och Ta bort svarar inte i tidrapporter**

När du försöker klicka på ikonerna Redigera eller Ta bort i en tidrapportrapport visas inget svar.

**Rapporter som innehåller typsnittsfält kan inte läsas in**

När du öppnar en rapport som innehåller anpassade typsnittsfält går det ibland inte att läsa in rapporten och ett felmeddelande visas.

+++

+++**Underhållsuppdatering 14 november 2024**

### Underhållsuppdatering 14 november 2024

#### Startsida

**Att göra-widgetfel för nya och slutförda uppgifter**

När man försöker skapa en ny uppgift eller fylla i en befintlig i hemmakonfigurationen, uppstår ett fel och användaren kan inte skapa eller slutföra uppgiften.

#### Användare

Kryssrutan **&quot;Skicka inbjudningsmeddelanden till dessa personer&quot; saknas**

När nya användare importeras till Workfront saknas kryssrutan&quot;Skicka inbjudningsmeddelanden till dessa personer&quot; i dialogrutan.

+++

+++**Underhållsuppdatering 7 november 2024**

### Underhållsuppdatering 7 november 2024

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. Workfront Support meddelar dig när ett problem som du har skickat har åtgärdats.

+++

## Uppdateringar i oktober 2024

+++**Underhållsuppdatering 31 oktober 2024**

### Underhållsuppdatering 31 oktober 2024

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. Workfront Support meddelar dig när ett problem som du har skickat har åtgärdats.

+++

+++**Underhållsuppdatering 24 oktober 2024**

### Underhållsuppdatering 24 oktober 2024

#### Uppdrag

**Ikonen Tid av visas inte när uppgifter tilldelas**

När en användare tilldelar en uppgift och börjar skriva namnet på den som är tilldelad en tid som inte är schemalagd under uppgiften, visas inte ikonen för tid utanför (flygplan) under Föreslagna uppdrag. Om användaren fortsätter att skriva så att namnet visas under området Användare och team visas ikonen.

#### Egna formulär

**Det går inte att uppdatera anpassade data i slutförda projekt**

När en användare försöker uppdatera anpassade data i ett projekt som är färdigt kan de inte uppdatera data och de ser följande meddelande:

&quot;Det går inte att slutföra åtgärden för ett projekt med statusen Slutförd.&quot;

#### Projekt

**Det går inte att lägga till problem i det slutförda projektet**

När en användare försöker lägga till ett problem i ett projekt med statusen Fullständigt kan användaren inte lägga till problemet. Detta kan inträffa även om alternativet Lägg till och redigera problem är aktiverat

**Gantt-schemat är inte korrekt**

När en användare tittar på Gantt-schemat och växlar vy, visar Gantt-schemat inte korrekta data eller visar inga data.

+++

+++**Underhållsuppdatering 17 oktober 2024**

### Underhållsuppdatering 17 oktober 2024

#### Korrektur

**Korrektur visar felaktigt datum**

Datum i dokumentlistan visar det datum då den första versionen av dokumentet skapades, i stället för det datum då den senaste versionen skapades.

#### Tidrapporter

När en användare försöker logga tid på en tidrapport som har statusen Skickat eller Stängt kan användaren inte logga tiden.

Detta är det förväntade beteendet och bör inte ses som något problem.

Tidigare kunde användarna logga tid på inskickade eller stängda tidrapporter via Workfront API eller Workfront Fusion.

+++

+++**Underhållsuppdatering 10 oktober 2024**

### Underhållsuppdatering 10 oktober 2024

#### Varumärkena

**Fel vid flyttning av kort eller tilldelning av användare**

När du flyttar kort eller tilldelar användare händer det ibland att åtgärden inte går igenom och i stället visas felet&quot;Svaret misslyckades: Statuskoden 502&quot; efter en fördröjning.

**Fel vid inläsning av anslagstavla**

När en användare försöker läsa in en anslagstavla, läses inte anslagstavlan in och användaren ser följande meddelande:

&quot;Fel vid inläsning av bräda&quot;

&quot;Något gick fel när den här tavlan lästes in. Uppdatera sidan och försök igen, eller kontakta support med fel-ID nedan om problemet kvarstår.&quot;

#### Startsida

**&quot;Markera som färdig&quot; stänger sammanfattningsrutan för widgeten Mina problem**

När du försöker använda knappen &quot;Markera som färdig&quot; i sammanfattningsrutan för ett problem som har öppnats via widgeten Mina problem stängs sammanfattningsrutan oväntat.

**Inställningarna för layoutmallswidgeten kan inte lägga till kolumnen**

När du markerar ett fält som ska läggas till i en widget via inställningarna för layoutmallswidgeten, kan du markera ett fält men motsvarande kolumn visas inte i widgeten.

#### Uppgifter

**Problem med tidslinjeomberäkning**

Följande problem har rapporterats angående omberäkning av tidslinje:

* När du uppdaterar varaktigheten för en tidslinjeaktivitet tar det lång tid att beräkna om.
* När omberäkningen är klar kan datumen vara inaktiverade eller inaktiverade, som om tidslinjen fortfarande beräknas om.

**Aktivitetsutgifter visas inte**

När du har lagt till en utgift för en aktivitet visas inte utgiften i aktivitetsinformationen trots att API-bekräftelsen har angetts.

+++

+++**Underhållsuppdatering 3 oktober 2024**

### Underhållsuppdatering 3 oktober 2024

#### Varumärkena

**Arkiverade anslutna kort har inte synkroniserats**

För att åtgärda prestandaproblem synkroniseras inte längre anslutna kort som är arkiverade. Ändringar som görs i Workfront-uppgiften eller -problemet återspeglas inte i de arkiverade korten. Om du återställer ett kort synkroniseras det igen.

#### Egna formulär

**Konverteringsfel för visningstyp i anpassade formulär**

RTF-fält orsakar följande fel i anpassade formulär:

&quot;Fel: Konvertering av visningstyp mellan text och RTF tillåts inte.&quot;

Detta kan inträffa under följande förhållanden:

* Användaren börjar redigera formulären men klickar på Använd utan att göra några ändringar.
* Användaren skapar ett anpassat formulär.

I båda fallen ger RTF-fält upphov till problem.

#### Meddelanden

**Deltagare får inga e-postmeddelanden**

Användare med en Contributor-licens får inga e-postmeddelanden. Detta kan påverka både e-postmeddelanden med snabbmeddelanden och e-postmeddelanden med daglig sammandrag.

#### Korrektur

**Det går inte att lägga till elektroniska signaturer när SSO används för korrektur**

När du använder enkel inloggning för att logga in på korrektur kan användare inte ställa in ett korrektur för att kräva elektroniska signaturer.

+++

## Uppdateringar i september 2024

+++**Underhållsuppdatering 26 september 2024**

### Underhållsuppdatering 26 september 2024

#### Agile

**Lägg till i iterationsalternativet visas två gånger när du tilldelar trumteam**

När du tilldelar en uppgift eller ett problem till ett team med flexibla skript visas alternativet Lägg till i upprepning två gånger på menyn Mer. Detta påverkar inte möjligheten att tilldela teamet och visas inte för icke-spridda rörliga team.

#### Anpassad Forms

**Fältlistan i beräkningsredigeraren är begränsad till 200 objekt**

I Beräkningsredigeraren för beräknade fält i anpassade formulär är fältlistan för ett objekt nu begränsad till 200 objekt för att förbättra systemets prestanda. Om du känner till fältnamnet kan du söka efter det med typsnittsalternativet i stället för att bläddra igenom listan.

#### Rapporter

**Rapportleveranser är fördröjda eller saknas**

Rapporter med schemalagda leveranser levereras inte som förväntat. De kanske kommer för sent, eller så kanske de inte levereras alls.

+++

+++**Underhållsuppdatering 19 september 2024**

### Underhållsuppdatering 19 september 2024

#### Kontrollpaneler

**Om du väljer knappen Exportera i en rapport rullas den överst på sidan**

När du klickar på knappen Exportera för en rapport på en kontrollpanel, rullas fönstret till sidans överkant och kräver att du rullar nedåt för att hitta den öppna menyn för exportalternativ.

+++

+++**Underhållsuppdatering 12 september 2024**

### Underhållsuppdatering 12 september 2024

#### Integreringar

**Det uppstod ett fel när en begäran skulle skapas från Outlook**

När en användare försöker skapa en begäran från Workfront för Outlook-integreringen och lägger till en bifogad fil. Användaren ser meddelandet&quot;Något gick fel. Försök igen senare.&quot;

Begäran skapas och det finns en mapp för e-postbilagor i begäran, men mappen är tom och bilagan lades inte till i begäran.

+++

+++**Underhållsuppdatering 5 september 2024**

### Underhållsuppdatering 5 september 2024

#### Grupper

**Undergrupper visas inte korrekt**

När en användare visar grupplistan i inställningsområdet ser de att undergrupper inte visas korrekt under den överordnade gruppen. Undergruppen sparas korrekt under den överordnade gruppen, men listan kan orsaka missförstånd.

Om användaren öppnar undergruppen kan de se i de synliga kolumnerna att undergruppen har sparats korrekt under den överordnade gruppen.

#### Användare

**Det går inte att återaktivera användaren**

När en användare försöker återaktivera en användare med alternativet &quot;Återaktivera användare&quot; på menyn Mer kan användaren välja en åtkomstnivå, men ändringen sparas inte. I stället ser användaren följande fel:

&quot;homeGroupID kan inte vara null&quot;

+++

## Uppdateringar i augusti 2024

+++**Underhållsuppdatering 29 augusti 2024**

### Underhållsuppdatering 29 augusti 2024

#### Egna formulär

**Forms har som standard Project-formulär**

När en användare skapar ett anpassat formulär och väljer en objekttyp för formuläret, ignoreras objekttypen och formuläret skapas som ett anpassat projektformulär.

#### Dokument

**Om du klickar på ett dokumentnamn blir sidan tom**

När en användare försöker visa dokumentinformation genom att klicka på dokumentets namn i en dokumentlista, försvinner listan och användaren dirigeras inte till dokumentinformationen.

#### Startsida

**Väntande widget för godkännande visar borttagna dokument**

När en användare visar sin widget för väntande godkännanden i hemmet, ser de dokument som har tagits bort. Om användaren klickar på ett av dessa dokument, placeras de på en tom sida.

#### Användare

**Fältet E-post för användarprofil har inaktiverats**

För organisationer som använder IMS lagras språkinställningarna i varje användares Adobe Experience Cloud-profil. Fältet E-postspråk i Workfront-användarprofilen har inaktiverats (endast för IMS-organisationer) och ett verktygstips för det fältet innehåller instruktioner om hur du kommer åt språkinställningarna i Adobe-profilen.

Detta åtgärdar ett problem som uppstår när en administratör försöker ändra språkinställningen för e-post för en användare, så återställs den till engelska.

+++

+++**Underhållsuppdatering 22 augusti 2024**

### Underhållsuppdatering 22 augusti 2024

#### Rapporter

**Det går inte att klicka på en rapport från området Anpassade fält i installationsprogrammet**

När en användare visar området Anpassade Forms > Fält i inställningarna, och vyn innehåller fältet Inbyggda rapporter, fungerar inte länkarna till rapporterna. Användaren bör kunna klicka på namnet på en rapport och komma till rapporten, men det går inte att klicka på rapportens namn.

+++

+++**Underhållsuppdatering 15 augusti 2024**

### Underhållsuppdatering 15 augusti 2024

#### Varumärkena

**Problem med dubblettkort**

Följande problem har rapporterats när det gäller dubblettkort på anslagstavlor:

* Ett kort visas två gånger. Detta kan åtgärdas genom att sidan uppdateras.
* Om en användare tar bort ett av de duplicerade korten tas alla instanser av det duplicerade kortet bort.

#### Meddelanden

**Hoppfel vid inställning av aviseringsinställningar**

När en användare försöker visa meddelandeinställningar visas följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]

Detta har rapporterats i följande områden:

* Meddelandeinställningar för en användarprofil
* Området med händelsemeddelanden i installationsprogrammet

#### Projekt

**Valutasymbolen är felaktig vid export**

När en användare exporterar en utgåva matchar inte valutasymbolen i exporten den som angetts i projektet eller utgåvan.

#### Korrektur

**Korrekturmarkeringar är felaktiga**

Korrekturmarkeringar är feljusterade på PDF-utskrifter som tas emot via e-post från funktionen Korrekturutskrift.


+++

+++**Underhållsuppdatering 8 augusti 2024**

### Underhållsuppdatering 8 augusti 2024

#### Varumärkena

**Kortet innehåller inte underaktiviteter**

När en användare visar ett kort för en uppgift som är en överordnad uppgift, visas inte underuppgifterna för den överordnade uppgiften på kortet. Istället visas 0 underaktiviteter på kortet.

### Rapporter

**Rapportleveranser är fördröjda eller saknas**

Rapporter med schemalagda leveranser levereras inte som förväntat. De kanske kommer för sent, eller så kanske de inte levereras alls.

#### Inställningar

**&quot;Logga in som&quot; leder till en tom skärm**

När en administratör loggar in som en annan användare visas en tom skärm i stället för att användarens konto visas.

+++

+++**Underhållsuppdatering 1 augusti 2024**

### Underhållsuppdatering 1 augusti 2024

#### Dokument

**Det går inte att skapa vyn för dokumentlistan**

När en användare försöker skapa en ny vy i en dokumentlista, blir skärmen tom och användaren kan inte skapa vyn.

Befintliga vyer fungerar som förväntat.

#### Integreringar

**Problem med integrering med Dropbox**

Följande problem har rapporterats när det gäller integreringen av Dropbox:

* När en användare försöker söka efter en fil i filväljaren i Dropbox visas ett felmeddelande om auktorisering, och filväljaren hämtar inte filen från Dropbox.
* När en användare försöker öppna en länkad mapp visas ett felmeddelande om att filerna eller mappen inte längre finns i Dropbox.

Dessa problem beror på problem med Dropbox, inte med Workfront.

+++

## Uppdateringar i juli 2024

+++**Underhållsuppdatering 25 juli 2024**

### Underhållsuppdatering 25 juli 2024

#### Egna formulär

**Listrutan stängs när flera värden väljs**

När en användare försöker markera flera värden i ett anpassat formulärfält stängs listrutan när det första värdet har valts.

Detta inträffar när fältet är associerat med visningslogiken i det anpassade formuläret.

#### Meddelanden

**Miniatyrbilder visas inte i e-postmeddelanden**

När en användare visar ett e-postmeddelande om ett dokumentgodkännande visas inte dokumentminiatyrbilden i e-postmeddelandet.

Detta har rapporterats i Gmail.

+++

+++**Underhållsuppdatering 18 juli 2024**

### Underhållsuppdatering 18 juli 2024

#### Agile

**Artikelbordet blir tomt när en underaktivitet läggs till**

När en användare försöker lägga till en underaktivitet på en artikelanslagstavla medan ett filter är markerat, blir skärmen tom och användaren kan inte lägga till underaktiviteten.

#### Startsida

**Kan inte öppna objekt från [!UICONTROL Home Calendar] eller[!UICONTROL Work List]**

När en användare försöker öppna ett arbetsobjekt eller ett korrektur från sin [!UICONTROL Home Calendar] eller [!UICONTROL Home Work List] öppnas inte objektet.

**Administratörens hemsida visas när du är inloggad som en annan användare**

När en administratör är inloggad som en annan användare och visar användarens hemsida, visas administratörens hemsida.

#### Korrektur

**Om du stänger ett korrektur leder det till sidan Produktdokument**

När en användare visar ett korrektur och stänger korrekturet dirigeras användaren till sidan Projektdokument i stället för till sidan som korrekturet öppnades från.

#### Workfront

**Anpassad terminologi används inte**

Anpassad terminologi som angetts i layoutmallen visas inte i vissa områden i Workfront. I stället visas den icke-anpassade standardterminologin.

Detta har rapporterats i följande områden:

* Menyflikar
* Sidhuvuden
* Beskrivningar där projekt listas


+++

+++**Underhållsuppdatering 11 juli 2024**

### Underhållsuppdatering 11 juli 2024

#### Problem

**Fel vid avancerad tilldelning av ett problem**

När en användare försöker göra en avancerad tilldelning till ett problem i Workfront, tilldelas inte problemet och användaren ser följande felmeddelande:

[!UICONTROL APIModel INTERNAL does not support field duration (OpTask)]

#### Rapporter

**Hoppfel vid inställning av matrisinställningar i timrapporten**

När en användare försöker ställa in matrisinställningarna för en timrapport kan de inte ställa in inställningarna och de ser följande fel:

* [!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]


+++

+++**Underhållsuppdatering 4 juli 2024**

### Underhållsuppdatering 4 juli 2024

#### Startsida

**Trepunktsmenyn är ineffektiv**

När en användare klickar på menyn med tre punkter mer i den äldre Home Worlkist utlöses ingen åtgärd.

#### Rapporter

**&quot;Inga data att visa&quot; när grupperingsnamnet har snedstreck eller omvänt snedstreck**

När en användare visar ett diagram i en rapport och klickar på en gruppering i diagrammet och den grupperingen har namnet / eller \, visas inte de öppna detaljerna i grupperingen och användaren ser meddelandet&quot;Inga data att visa&quot;.

#### Uppgifter

**Jobbrollen försvinner inte från listan när användaren tilldelas till aktiviteten**

När en jobbroll tilldelas till en uppgift och den uppgiften tilldelas till en användare som har jobbrollen, försvinner inte jobbrollen från listan med tilldelningar.


+++

## Uppdateringar i juni 2024

+++**Underhållsuppdatering 27 juni 2024**

### Underhållsuppdatering 27 juni 2024

#### Varumärkena

**Endast kortägaren kan uppdatera konfigurationsfilter**

Av säkerhetsskäl är det bara ägaren av en anslagstavla som kan ändra ritytans filter på panelen Konfigurera.

#### Rapporter

**Rapporten läses inte in när standardvalutan är USD**

När en användare försöker visa en rapport som har standardvalutan som USD läses rapporten inte in.

#### Uppdateringar

**Den kopierade länken klistras inte in korrekt**

Om en användare kopierar en länk från en uppdatering genom att högerklicka och välja [!UICONTROL Copy link address] och sedan klistrar in länken i en uppdatering, klistras länken inte in korrekt. Endast den första delen av länken är en länk, och resten av URL:en ignoreras.

Om du kopierar länken med en annan metod, [!UICONTROL Copy link address], kan länken klistras in som förväntat.

+++

+++**Underhållsuppdatering 20 juni 2024**

### Underhållsuppdatering 20 juni 2024

#### Navigering

**Bakåtknappen går inte tillbaka till föregående sida**

När en användare i Workfront klickar på knappen Bakåt i webbläsaren kan något av följande inträffa.

* Namnet på webbläsarfliken ändras, men sidan ändras inte. Problemet kan eventuellt lösas genom att du klickar på knappen Bakåt igen.
* Användaren dirigeras till sin webbläsarstartsida.

#### Korrektur

**Kan inte stänga korrekturläsaren**

När en användare visar ett korrektur i korrekturläsaren och försöker stänga korrekturet genom att klicka på krysset i det övre högra hörnet, stängs inte korrekturet.

+++

+++**Underhållsuppdatering 13 juni 2024**

### **Underhållsuppdatering 13 juni 2024**

#### Grupper

**Det går inte att lägga till undergrupp**

När en användare försöker lägga till en befintlig undergrupp i en grupp, är knappen Spara inaktiv och undergruppen läggs inte till.

+++

+++ **Underhållsuppdatering 6 juni 2024**

### Underhållsuppdatering 6 juni 2024

#### Egna formulär

**Begränsning för inbyggda fält i formulärdesignern**

Flera inbyggda fält stöds nu i anpassade formulär som skapats i formulärdesignern. Tidigare var gränsen ett internt fält per formulär.

+++

## Uppdateringar i maj 2024

+++ **Underhållsuppdatering 30 maj 2024**

### Underhållsuppdatering 30 maj 2024

#### Egna formulär

Fel vid redigering av beskrivande textfält

När en användare försöker redigera den beskrivande texten i ett anpassat formulär sparas inte texten och användaren ser följande fel:

&quot;Dubblettnyckelvärdet bryter mot den unika begränsningen&quot;

Detta har rapporterats i den äldre formulärbyggaren.

#### Uppdateringar

**Om du kopierar och klistrar in ett omnämnande visas inget meddelande för den angivna användaren**

När en användare kopierar en kommentar som innehåller ett omnämnande i @-format och sedan klistrar in kommentaren i uppdateringsområdet för ett annat objekt, meddelas inte den aktuella användaren om den inklistrade kommentaren.

+++

+++ **Underhållsuppdatering 23 maj 2024**

### Underhållsuppdatering 23 maj 2024

#### Rapporter

När en användare visar en rapport och klickar på webbläsarens Bakåt-knapp kan något av följande inträffa:

* Användaren finns kvar på rapportsidan.
* Användaren dirigeras till webbläsarens landningssida.
* Användaren dirigeras till inloggningssidan.

Detta har rapporterats i Chrome webbläsare.

#### Uppdateringar

**Taggad användare kan inte se vem som taggade dem**

När en användare är taggad i en uppdatering kan de inte se vem som taggat dem. Detta inträffar när inställningen &quot;Personer i andra företag bör endast visa användare från..&quot; är inställd på &quot;Deras företag&quot;.

**Det går inte att tagga en användare med @ på sammanfattningspanelen**

När en användare försöker tagga en annan användare genom att använda @ i uppdateringsområdet på en sammanfattningspanel, är det ineffektivt att klicka på användarens namn i listrutan. Försök att tagga användaren en andra gång fungerar som väntat.

+++

+++**Underhållsuppdatering 16 maj 2024**

### Underhållsuppdatering 16 maj 2024

#### Inställningar

**Standardstatus för problem saknas i vissa problemtyper i installationen**

När en användare visar problem i installationsprogrammet ser de att standardstatusvärdena för problem (Nytt, Pågår och Fullständigt) saknas i vissa typer av problem. Standardstatusvärden har inte möjlighet att ändra utgåvans typ, så användaren kan inte konfigurera om statusvärdena så att de visas för de berörda utgåvorna.

#### Användare

**Kan inte ta bort användare**

När en användare försöker ta bort användare tas de inte bort. Detta har rapporterats i organisationer som har migrerat till Adobe Admin Console.

+++

+++**Underhållsuppdatering 9 maj 2024**

### Underhållsuppdatering 9 maj 2024

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

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

**Numrerade listor är inte korrekt numrerade**

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

**Fel vid uppdatering av kalendern**

När en användare visar en kalender och uppdaterar sidan visas ett &quot;Hoppfel&quot;. Data i kalendern visas som förväntat, men kan skymmas av felmeddelandet.

#### Egna formulär

**Externa sökfält returnerar inte resultat**

När ett externt uppslagsfält refererar till ett flervalsfält som bara har ett värde markerat, returnerar fältet inte värdet.

Om ett externt uppslagsfält till exempel refererar till ett flervalsfält som har både röda och blå värden markerade, fungerar fältet som förväntat. Om fältet bara har &quot;röd&quot; markerat returnerar det externa sökfältet inget värde.

#### Projekt

**Det går inte att konvertera utgåvan till ett projekt om det finns ett webbkorrektur bifogat**

När en utgåva har ett webbkorrektur bifogat (ett URL-korrektur med en länk från en extern dokumentleverantör som SharePoint) och en användare försöker konvertera utgåvan till ett projekt, misslyckas konverteringen och projektet skapas inte. Användaren ser följande fel:

&quot;Det gick inte att kopiera filen (fil-GUID). Ta bort filen eller kontakta supporten och försök igen.&quot;

+++

+++**Underhållsuppdatering 11 april 2024**

### Underhållsuppdatering 11 april 2024

#### Sök

**Det går inte att redigera från sökning**

När en användare använder Avancerad sökning och försöker redigera eller massredigera sökresultaten, svarar inte redigeringsikonen.

#### Uppdateringar

**Förhandsvisning av bilden i uppdateringar är oskarp**

När en användare tittar på uppdateras och klickar på förstoringsglaset på en bild för att förhandsvisa bilden, blir den förhandsvisning som öppnas extremt pixelerad oskarp.

Om användaren hämtar bilden visas den med den förväntade upplösningen.

**[!UICONTROL We're unable to post your comment]-meddelande vid svar**

När en användare försöker svara på ett meddelande i den nya kommentarsfunktionen sparas inte svaret och användaren ser följande meddelande:

[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]

+++

+++**Underhållsuppdatering 4 april 2024**

### Underhållsuppdatering 4 april 2024

#### Sök

**Det går inte att redigera från sökning**

När en användare använder Avancerad sökning och försöker redigera eller massredigera sökresultaten, svarar inte redigeringsikonen.

#### Uppdateringar

**Förhandsvisning av bilden i uppdateringar är oskarp**

När en användare tittar på uppdateras och klickar på förstoringsglaset på en bild för att förhandsvisa bilden, blir den förhandsvisning som öppnas extremt pixelerad oskarp.

Om användaren hämtar bilden visas den med den förväntade upplösningen.

**[!UICONTROL We're unable to post your comment]-meddelande vid svar**

När en användare försöker svara på ett meddelande i den nya kommentarsfunktionen sparas inte svaret och användaren ser följande meddelande:

[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]

+++

+++**Underhållsuppdatering 4 april 2024**

### Underhållsuppdatering 4 april 2024

#### Integreringar

**Dokument som inte bifogas när en begäran skapas från[!DNL Outlook]**

När en användare skapar en begäran från [!DNL Outlook] bifogas inte dokumenten till e-postmeddelandet till begäran.

Detta har rapporterats för följande typer av bifogade filer:

XLS
PDF

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

När en användare skapar en begäran från [!DNL Outlook] bifogas inte dokumenten till e-postmeddelandet till begäran.

Detta har rapporterats för följande typer av bifogade filer:

XLS
PDF

#### Korrektur

**Korrektur finns kvar på widgeten Mina godkännanden**

Ett korrektur som ska försvinna från widgeten Mina godkännanden finns kvar på widgeten. Detta kan inträffa när flera användare fattar beslut om ett korrektur samtidigt, eller när en användare fattar ett beslut och snabbt ändrar det.

#### Resurshantering

**Discreency in Budget Hours**

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

En Workfront-modul kan returnera ett `RuntimeError [200]`-svar. 2000 innebär ett lyckat svar, men felet visar att begäran misslyckades.

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

**Lägre åtkomstnivåer är inte tillgängliga när en användare skapas**

När en användare skapar en annan användare är endast den första användarens åtkomstnivå tillgänglig för den nya användaren. Alla åtkomstnivåer med lägre behörigheter än de som användaren skapar bör vara tillgängliga att tilldela till den nya användaren.

+++

+++**Underhållsuppdatering den 7 mars 2024**

### Underhållsuppdatering 7 mars 2024

#### Varumärkena

**400-fel när en uppgift läggs till på en anslagstavla**

När en användare visar ett projekt och försöker lägga till en uppgift på en anslagstavla läggs uppgiften inte till och användaren ser följande fel:

Fel: &quot;400: undefined /boards-service/graphql&quot;

#### Startsida

**Fel vid infogad redigering av en uppgift i widgeten Min uppgift**

När en användare försöker att infoga en redigering i widgeten Mina uppgifter ser han/hon följande fel:

&quot;Ett fel har inträffat och vi arbetar för att lösa problemet. Om du vill fortsätta med ditt arbete kan du försöka med att uppdatera den här webbläsarsidan.&quot;


#### Utjämning av arbetsbelastning

**Planerade timmar uppdateras inte i arbetsbelastningsutjämnaren**

När de planerade timmarna i ett projekt uppdateras uppdateras de inte i Utjämning av arbetsbelastning. Detta kan inträffa även om ändringen återspeglas korrekt i projektet.

+++

++**Workfront Fusion Maintenance Update den 7 mars 2024

**Workfront Proof > Titta på korrekturmodulen - timeout**

Scenarier som använder Workfront Proof > Bevakningskorrektur kan inaktiveras på grund av timeout för modulen Bevakningsbevis.

+++

## Uppdateringar i februari 2024

+++**Underhållsuppdatering 29 februari 2024**

### Underhållsuppdatering 29 februari 2024

#### Uppdateringar

**Uppdateringar: Skärmen blir tom när en användare från ett annat företag svarar.**

När en användare försöker svara på en kommentar av en användare i ett annat företag, blir skärmen tom.

Detta beror på att användaren inte har behörighet att se användare från andra företag.

+++

+++**Underhållsuppdatering 22 februari 2024**

### Underhållsuppdatering 22 februari 2024

#### Startsida

**[!UICONTROL Home]: [!UICONTROL Workspace] och punkter läses inte in**

När en användare loggar in kan följande inträffa:

* Användarens nya [!UICONTROL Home Workspace] läses inte in och felet [!UICONTROL We are unable to load your Workspace information. Please contact Workfront so we can figure out what went wrong and fix it.] visas
* Användarens stift läses inte in och felet [!UICONTROL Your pins are unavailable because of a system error. Try refreshing your browser to fix the problem.] visas

#### Användare

**Gruppadministratören kan inte ange eller ändra en användares åtkomstnivå**

<!--no article-->

När en gruppadministratör försöker ändra åtkomstnivån för en användare kan något av följande inträffa:

* Fältet för åtkomstnivå är inaktiverat.
* Gruppadministratören kan inte välja en lägre åtkomstnivå.

#### Utjämning av arbetsbelastning

**Etikett för ej arbetstid**

Utjämning av arbetsbelastning och personlig tid i kalendern visar nu [!UICONTROL Non-working Hours] för den tid som en användare startar. Tidigare visades [!UICONTROL Working Hours] för ledig tid.

+++

+++**Underhållsuppdatering 15 februari 2024**

### Underhållsuppdatering 15 februari 2024

#### Problem

**Tidsfält sparar felaktig tid vid gruppredigering av problem**

När en användare gör stora redigeringsproblem och väljer ett datum och en tid för ett datumfält och sparar, är tiden som sparas i det här fältet i utgåvan inte den tid som användaren valde. I stället ser tiden ut att konverteras till UTC när användaren sparar.

#### Uppgifter

**Användaren har inte tilldelats från en eller flera uppgifter**

En användare kan automatiskt tas bort från en uppgift som de har tilldelats. Detta kan inträffa för en eller flera uppgifter. Uppdelningen visas inte i aktiviteternas systemuppdateringar, men den visas inte i avsnittet Uppdatera feeds på inställningsmenyn.

#### Uppdateringar

**Alternativet Inaktiverad bild är tillgängligt när du redigerar en kommentar**

När en [!DNL Workfront]-administratör har inaktiverat alternativet att lägga till bilder i kommentarer, är det alternativet inte tillgängligt när du skapar en kommentar. Om en användare redigerar en befintlig kommentar är dock bildalternativet tillgängligt.

+++

+++**Underhållsuppdatering 8 februari 2024**

### Underhållsuppdatering 8 februari 2024

#### Varumärkena

**Det går inte att flytta ett kort i en kolumn med [!UICONTROL Move] options**

När en användare försöker flytta ett kort i en kolumn med alternativen [!UICONTROL Top of column] eller [!UICONTROL Bottom of column] i menyn med tre punkter flyttas inte kortet.

**Kort behålls när upprepning ändras**

När en användare visar en upprepning på en anslagstavla och sedan ändrar upprepningen, är korten som visas för den nya upprepningen korten från en iteration som användaren visade tidigare.

#### Rapporter

Kolumnen **&quot;Inget värde&quot; visar inga resultat**

När en diagramrapport har en [!DNL No value]-kolumn visar kolumnen inga data, även om det finns data.

#### Resurshantering

**Felaktiga ekonomiska beräkningar på grund av problem med jobbrollen**

Timmar- och finansberäkningar kan vara felaktiga, vilket ger en kostnad på 0 även om timmar är inloggade i en jobbroll som har en kostnadstariff.

Detta beror på att jobbroller automatiskt skapar dubblettfrekvenser utan start- eller slutdatum. Eftersom de inte har några start- eller slutdatum behandlas de som värdet 0 när finansiella beräkningar körs.

+++

+++**Underhållsuppdatering 1 februari 2024**

### Underhållsuppdatering 1 februari 2024

#### Inloggning

**Användare som använder enkel inloggning omdirigeras inte till den ursprungliga platsen när de loggar in**

När en användare är på en sida i [!DNL Workfront] och loggar in med enkel inloggning dirigeras de till [!UICONTROL Home] i stället för den sida de var på innan de loggade in.

#### Mallar

**Fel vid kopiering av mallar**

När en användare försöker kopiera en ny eller befintlig mall kopieras inte mallen och användaren ser följande fel:

[!UICONTROL ID Cannot be Null]

+++

## Uppdateringar i januari 2024

+++**Underhållsuppdatering (snabbkorrigering) 30 januari 2024**

### Underhållsuppdatering (snabbkorrigering) 30 januari 2024

#### Rapporter

**Det externa API-fältet visar inte alla tillgängliga värden i listor och rapporter**

Tidigare kunde användarna se det valda värdet (och redigera värdet) för ett externt uppslagsfält i listor och rapporter, men kunde inte se listrutan med alternativen från API:t.

När ett anpassat fält för extern sökning används i en lista eller rapport är nu listrutan med alla alternativ från det externa API:t tillgänglig.

+++

+++**Underhållsuppdatering 25 januari 2024**

### Underhållsuppdatering 25 januari 2024

#### Varumärkena

**Kort flyttas inte till lämplig kolumn när status ändras**

När statusen för det länkade objektet för ett anslutet kort ändras direkt på objektet flyttas kortet inte till rätt kolumn. Om objektets status ändras på kortet, eller om kortet dras till den nya kolumnen, fungerar kortet som förväntat.

#### Meddelanden

**Markeringsmeddelanden som de visas kvarstår inte**

När en användare markerar sina meddelanden som de ser och sedan navigerar till en annan sida inom [!DNL Workfront], visar meddelandeikonen fortfarande antalet olästa meddelanden som fanns innan användaren markerade dem som synliga, och meddelandena visas fortfarande när användaren klickar på ikonen. Detta fortsätter om användaren markerar dem som synliga och navigerar till en annan sida eller tillbaka till den ursprungliga sidan.

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

**Kort behålls när upprepning ändras**

När en användare visar en upprepning på en anslagstavla och sedan ändrar upprepningen, är korten som visas för den nya upprepningen korten från en iteration som användaren visade tidigare.

**Fel i [!UICONTROL Comments]-kortavsnitt**

När en användare visar ett kort och rullar till avsnittet [!UICONTROL Comments] visas inga kommentarer och användaren ser följande fel:

[!UICONTROL Something went wrong. Please try again later.]

**Problem vid visning av delaktivitetsstatus**

Följande problem har rapporterats när det gäller att visa status för underaktiviteter på ett kort i Boards:

* Statusen visas som &quot;Välj status&quot; även när aktiviteten redan har en status. Den här statusen visas när du visar uppgiften direkt.
* Om användaren försöker välja en status, blir skärmen tom och måste uppdateras.

**[!UICONTROL You have no access] vid visning av kommentarer på ett kort**

När en användare försöker visa kommentarer på ett kort som inte är anslutet till ett [!DNL Workfront]-objekt visas följande meddelande:

[!UICONTROL You have no access to view comments on this object]

Detta kan inträffa även när användaren tidigare kan se kommentarer på kortet.

#### Egna formulär

**Det går inte att lägga till eller ta bort anpassade formulär gruppvis i mallaktiviteter**

Om en användare försöker att lägga till eller ta bort ett anpassat formulär gruppvis i en mallåtgärd läggs inte formuläret till eller tas bort, och användaren ser följande fel:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

Om användaren hittar mallen med angivet GUID och sedan försöker lägga till eller ta bort anpassade formulär i resten av malluppgifterna, kommer felet att inträffa igen med ett annat templateID.

Anpassade formulär kan läggas till eller tas bort i en enda mallåtgärd. Det här felet gäller endast för masstillägg och borttagning.

#### Portfolio

**Anpassad terminologi gäller inte för gruppsidan**

När en användare anger anpassad terminologi på Portfolio-nivå, gäller inte termen gruppnivåsidan.

#### Inställningar

**Det går inte att dölja valfria statusar**

När en användare försöker dölja valfria statusar på system- och gruppnivå döljs inte statusen. Om användaren visar statusen är alternativet att dölja statusen inte aktiverat, även om användaren aktiverade det och sparade ändringarna.

**Standardstatus för problem saknas i vissa problemtyper i installationen**

När en användare visar problem i installationsprogrammet ser de att standardstatusvärdena för problem (Nytt, Pågår och Fullständigt) saknas i vissa typer av problem. Standardstatusvärden har inte möjlighet att ändra utgåvans typ, så användaren kan inte konfigurera om statusvärdena så att de visas för de berörda utgåvorna.

#### Team

**Problem med att ställa in teamstatus för [!UICONTROL Done] button**

Följande problem har rapporterats angående status för knappen [!UICONTROL Done] när du redigerar eller skapar ett team:

* Vissa statusar kan saknas i knappområdet Klar i fönstret [!UICONTROL New team] eller i [!UICONTROL Team Settings] i ett befintligt team.
* Om användaren försöker spara teamet kan felet&quot;Du måste välja minst en status i varje kategori&quot; visas.

#### Mallar

**Fel vid koppling av mall till projekt**

När en användare försöker koppla en mall till ett projekt visas följande fel:

&quot;Hoppsan! Något gick fel. Kontakta Workfront för att ta reda på vad som gick fel och åtgärda det.&quot;

Detta inträffar när användaren inte har behörigheten Visa för ett anpassat formulär som är kopplat till mallen.

#### Uppdateringar

**Kommentarerna överförs inte mellan den gamla och den nya upplevelsen**

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
