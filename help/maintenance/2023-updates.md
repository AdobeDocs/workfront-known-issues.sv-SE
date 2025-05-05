---
title: Workfront Maintenance Updates in 2023
description: Underhållsuppdateringar för  [!DNL Adobe Workfront]
feature: Get Started with Workfront
exl-id: 87d54104-38b7-4950-ab21-6524a14f7f2a
source-git-commit: 1bc69d197e26e8c5543ad03164ebca1839789274
workflow-type: tm+mt
source-wordcount: '7242'
ht-degree: 0%

---

# [!DNL Workfront] underhållsuppdateringar 2023

Följande underhållsuppdateringar gjordes 2023.

>[!NOTE]
>
>Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

Underhållsuppdateringar före 2023 finns i [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

## Uppdateringar i december 2023

+++**Underhållsuppdatering 21 december 2023**

**Problem vid visning av delaktivitetsstatus**

_Vandrar_

Följande problem har rapporterats när det gäller att visa status för underaktiviteter på ett kort i Boards:

* Statusen visas som &quot;Välj status&quot; även när aktiviteten redan har en status. Den här statusen visas när du visar uppgiften direkt.
* Om användaren försöker välja en status, blir skärmen tom och måste uppdateras.

**Kan inte bifoga ett dokument till ett kort**

_Vandrar_

När en användare försöker bifoga ett dokument till ett anslutet kort kan han eller hon välja det dokument som ska bifogas, men dokumentet visas inte i kortets dokumentområde och dokumentet är inte bifogat till objektet som kortet är anslutet till.

Detta har rapporterats i kort som är kopplade till problem.

**Det går inte att välja mall från [!UICONTROL Favorites] list**

_Mallar_

När en användare försöker välja en mall från listan [!UICONTROL Favorites] försvinner listan när användaren flyttar musen till listan och användaren inte kan välja någon mall.

**Vissa uppdateringar saknas i den nya kommentarsfunktionen**

_Uppdateringar_

När en användare visar uppdateringar i den nya kommentarsfunktionen visas inte vissa kommentarer som ska visas. Om användaren växlar till den tidigare kommentarfunktionen visas alla kommentarer.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 21 december 2023**

Modulfältet tar för lång tid att öppna

_[!DNL Workfront Fusion]_

<!--no article-->

När en användare konfigurerar en modul och modulen kräver data från det anslutna kontot (t.ex. för att välja en post), kan modulen inte hämta data och begäran om data tar för lång tid.

+++

+++**Underhållsuppdatering 14 december 2023**

**Korrektur som väntar på godkännande visas inte i rapporter**

_Korrektur_

När en användare visar en rapport för väntande korrekturgodkännanden visas inte vissa väntande godkännanden i rapporten.
+++

+++**Underhållsuppdatering 7 december 2023**

**Godkännandet fastnat i [!UICONTROL Awaiting my approval] widget**

_Startsida_

När en ny version av ett dokument överförs och den föregående versionen har ett godkännande som inte är fullständigt, fastnar den gamla versionen av dokumentet på godkännarens [!UICONTROL Awaiting my approval]-widget. Godkännandet kan inte godkännas eftersom det finns en ny version och det kan inte tas bort från widgeten.

**Problem när arbetsobjekt läggs till i vyn över uppgifter eller problem i styrelsen**

_Uppgifter/problem_

När en användare tittar på styrelsens vy över uppgifter eller problem i ett projekt och försöker lägga till en uppgift eller ett problem kan följande inträffa:

* Popup-fönstret växlar fram och tillbaka mellan två olika fönsterformat
* Användaren kan inte stänga popup-fönstret

Detta har rapporterats inträffa när en användare väljer ett område från den vänstra navigeringen i popup-fönstret innan han eller hon anger någon information.

+++

## Uppdateringar i november 2023

+++**Underhållsuppdatering 30 november 2023**

**Uppgifter visas inte i [!UICONTROL My Work] widget**

_[!UICONTROL Home]_

När en användare visar sin [!UICONTROL My Work]-widget i [!UICONTROL Home] visas inte vissa av de uppgifter som de är tilldelade till i widgeten. En användare kan till exempel gå till ett projekt och se att de är tilldelade uppgifter i projektet, men dessa uppgifter visas inte i användarens [!UICONTROL My Work]-widget.

**Inloggningssidan omdirigeras till utloggningsstartsidan**

_Inloggning_

När en användare försöker logga in på [!DNL Workfront], i stället för inloggningssidan, dirigeras de till sidan som de skulle logga in på om de skulle logga ut.

**500-fel vid export av en rapport**

_Rapporter_

När en användare försöker exportera en rapport misslyckas exporten med följande fel:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Detta har rapporterats i rapporter där `valueexpression` används som referens för anteckningstexten `lastNote`.

+++

+++**Underhållsuppdatering 16 november 2023**

**Budgeterade timmar i användningsrapporten matchar inte budgeterade timmar som rapporterats via API**

_Rapporter_

När en användare gör ett API-anrop till RPBGHR-objektet för ett givet projekt och jämför resultatet av anropet med användningsrapporten för det projektet, matchar inte resultaten.

**Felaktig anpassad valuta visas på sidan Ny begäran**

_Begäranden_

När en användare skickar en begäran och gör ett val som ändrar visningslogiken i begärandeformuläret, återställs den visade valutan till standardvalutan i stället för den anpassade valuta som är inställd på det projekt som begärandekön representerar.

När användaren skickar sin begäran visas valutan som den korrekta anpassade valutan för projektet som begärandekön representerar

**Extra rader i kommentarer som gjorts via API eller[!DNL Workfront Fusion]**

_Uppdateringar_

När en användare skickar en kommentar via API:t eller via [!DNL Workfront Fusion] visas extra rader i kommentaren som visas i uppdateringsområdet. Ibland finns det så många rader att användaren måste rulla nedåt för att kunna se kommentarinnehållet.

Detta har rapporterats i den nya kommentarsfunktionen.

+++

+++**Underhållsuppdatering 9 november 2023**

**Widgeten Mitt arbete saknar objekt när den inte är överst på sidan**

_Startsida_

Om widgeten Mitt arbete är högst upp på den nya hemsidan, hämtas alla förväntade objekt. Om den här widgeten däremot finns under andra widgetar på sidan, hämtas endast 10 objekt.

**Det går inte att generera bevis**

_Korrektur_

När en användare försöker generera ett korrektur skapas inte korrekturet och användaren ser följande fel:

[!UICONTROL Error generating proof]

Detta inträffar när användarens åtkomstnivåinställning [!UICONTROL &#x200B; View Contact Info] är Inaktiverad.

**Fält rensas när ett dokument läggs till i en begäran**

_Begäranden_

När en användare skapar en begäran fyller i fält i ett formulär och sedan lägger till eller tar bort ett dokument, tas vissa fält i formuläret bort från data och användaren måste fylla i dem igen innan begäran skickas.

**Personlig uppgift visas på tidrapporten**

_Tidrapporter_

När en användare skapar en uppgift i [!UICONTROL Todo]-widgeten för den nya [!UICONTROL Home]-upplevelsen visas den uppgiften på användarens tidrapport. Detta inträffar även om aktiviteten inte har några timmar loggad och det personliga projektet inte är fäst.

+++

+++**Underhållsuppdatering (snabbkorrigering) 3 november 2023**

**Underordnade aktiviteter visas i fel ordning när de flyttas under den överordnade aktiviteten**

_Mallar_

När en användare skapar uppgifter i en mall och sedan flyttar dessa uppgifter under en överordnad uppgift, visas inte numren som tilldelats de underordnade uppgifterna i den förväntade ordningen. När sidan uppdateras sorteras de underordnade uppgifterna därför efter de oväntade aktivitetsnumren, och de underordnade aktiviteterna är därför i fel ordning.

+++

+++**Underhållsuppdatering 2 november 2023**

**Privata uppdateringar visas i värdeuttrycksfält**

_Rapporter_

När ett rapportfält innehåller ett värdeuttryck som refererar till en privat uppdatering, kan användare som inte ingår i den privata uppdateringen se det i rapporten.

**Användaren visas som överallokerad på grund av felaktig kapacitet**

_Utjämnare för arbetsbelastning_

En användare kan visa i belastningsutjämnaren som överallokerad. Om en användare hovrar över övertilldelningen ser de att användarens kapacitet är inställd på 0.

Om användaren ändrar datumintervallet är allokeringen korrekt. Om användaren uppdaterar sidan kan det dock hända att kapaciteten blir felaktig igen.

+++

## Uppdateringar i oktober 2023

+++**Underhållsuppdatering 26 oktober 2023**

**Sökningen fungerar inte**

_Vandrar_

När en användare försöker söka på anslagstavlor returnerar sökningen inte alla kort som uppfyller sökvillkoren.

**Det går inte att visa interaktivt korrektur i Web Viewer**

_Korrektur_

När en användare försöker visa ett korrektur i webbkorrekturläsaren visas inte korrekturet och användaren ser följande fel:

[!UICONTROL Missing Key-Pair-Id query parameter or cookie value]

**Kan inte skapa en ny version av ett korrektur**

_Korrektur_

När en användare försöker skapa en ny version av ett korrektur skapas inte den nya versionen och användaren ser följande felmeddelande:

[!UICONTROL Error generating proof]

**Användaren dupliceras när en begäran delas**

_Begäranden_

Om åtkomstnivån för en användare som begäran delas med ändras när en begäran delas, blir användaren precis ovanför den användaren i listan den användaren.

Om begäran till exempel delas med användare A och användare B och åtkomst för användare B ändras, ändras användare A till användare B och det nu finns två användardatabaser i listan. Dessutom har endast den översta användar-B-åtkomsten ändrats.

**[!UICONTROL Whoops]-fel i aktivitetshuvudet**

_Uppgifter_

När en användare tittar på en uppgift innehåller uppgiftshuvudet ingen information. I stället ser användaren följande felmeddelande:

[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]

+++

+++**Underhållsuppdatering 19 oktober 2023**

Användarna meddelas inte om svar på en kommentarstråd

_Meddelanden_

När en användare svarar på en kommentar, kommer andra användare som bör få meddelanden om svaret inte att få dem. Vissa användare kan få meddelandet, medan andra inte får det.

**Extra, tom kommentar när du gör en kommentar i ett korrektur**

_Korrektur_

När en användare gör en kommentar om ett korrektur skapas även en annan kommentar, som är tom.

Detta har rapporterats på videokorrektur.

Fliken **[!UICONTROL Proof activity]öppnas inte**

_Korrektur_

När en användare visar ett korrektur och klickar på fliken [!UICONTROL Proof activity] återgår användaren till fliken [!UICONTROL Proof details].

**[!UICONTROL Planned Hours]omallokeras när ytterligare en användare tilldelas till en aktivitet**

_Uppgifter_

När en användare tilldelas till en aktivitet som har [!UICONTROL Planned Hours] allokerats till andra tilldelningar för aktiviteten, fördelas aktivitetens [!UICONTROL Planned Hours] jämnt till alla tilldelningar för aktiviteten.

**[!UICONTROL Deleted] visas som användarnamn i systemuppdateringar när utgåvan konverteras till aktiviteten**

_Uppdateringar_

När en användare som är inloggad som en annan användare konverterar ett problem till en aktivitet och problemet tilldelas till ett team, visas [!UICONTROL Deleted] som den användare som begärde att teamet ska arbeta med uppgiften.

+++

+++**Underhållsuppdatering 12 oktober 2023**

**Arbetsströmmar borttagna för konton som inte använder dem**

_Vandrar_

För konton som aldrig har skapat ett arbetsflöde i Boards-programmet har Workstreams-området tagits bort från instrumentpanelen för paneler. Konton som använder arbetsflöden har fortfarande tillgång till dem.

**Beräknade fält behåller inget värde när utgåvan konverteras till aktiviteten**

_Anpassade formulär_

Beräknade fält som refererar till sig själva behåller inte sina värden när en utgåva konverteras till en uppgift.

När du konverterar problemet till en uppgift visas det önskade värdet korrekt i redigeringsfönstret. När konverteringen är klar visas dock ett N/a-värde i beräkningsfältet.

**Fel vid ändring av filter i[!UICONTROL Home]**

_Startsida_

När en användare ändrar filtren på [!UICONTROL Home] läses inte området [!UICONTROL Home] in och användaren ser följande fel:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

+++

+++**Underhållsuppdatering 5 oktober 2023**

**Kortet läses in långsamt**

_Vandrar_

När en användare läser in en bräda laddas brädet extremt långsamt. Detta kan inträffa även om styrelsen har ett litet antal kort.

Arkiverade kort, även om de inte visades, påverkade kortens inläsningstid.

**Kan inte flytta kort mellan kolumner**

_Vandrar_

När en användare försöker flytta ett kort ombord flyttas inte kortet. Detta inträffar under följande omständigheter:

* Dra och släpp
* Alternativet Flytta på kortet
* Redigera kortet

**Det går inte att flytta kort från inloppskolumnen**

_Vandrar_

Användaren kan dra ut ett kort från inmatningskolumnen till en annan kolumn på kortet, men efterföljande kort kan inte flyttas ut från inmatningskolumnen.

**Gruppera efter påverkar kortets prestanda**

_Vandrar_

När användaren försöker gruppera korten efter tilldelningar eller taggar blir kortets prestanda väldigt långsamt.

**Automatiska påminnelser skickas inte**

_Meddelanden_

Automatiska e-postpåminnelser skickas inte. Detta började den 14 september 2023.

+++

## Uppdateringar i september 2023

+++**Underhållsuppdatering 28 september 2023**

**Det går inte att ta bort det anpassade fältet**

_Anpassade formulär_

När en användare försöker ta bort ett anpassat fält kan de inte ta bort det och de ser meddelandet [!UICONTROL Database error due to constraint violation].

**Kommentarer som gjorts i den nya kommentarsfunktionen visas inte i den äldre versionen.**

_Uppdateringar_

När en användare gör en kommentar i den nya kommentarsfunktionen och den kommentaren visas i kommentarsområdet i den nya upplevelsen kanske samma kommentar inte visas i den gamla kommentarsfunktionen. Detta kan leda till att användare som använder äldre erfarenhet missar kommentarer.

**Objektsidan saknar element**

_Workfront_

När en användare navigerar till ett anpassat avsnitt på ett objekt i [!DNL Workfront] kan det saknas vissa element på sidan som läses in. Dessa element kan vara:

* Den vänstra navigeringspanelen
* Namnet på objektet som det anpassade avsnittet tillhör
* Fält och information i rubriken

+++

+++**Underhållsuppdatering 21 september 2023**

**Det går inte att tilldela användare på en anslagstavla i en arbetsström**

_Vandrar_

När en användare försöker tilldela en annan användare till en uppgift från en arbetsyta som är en del av ett arbetsflöde och börjar skriva användarens namn, visas inte användaren i listrutan med tillgängliga användare. Detta inträffar även när användaren är aktiv och medlem av både styrelsen och arbetsflödet.

Användaren kan också se att inaktiverade användare visas i listrutan.

**Det går inte att ta bort checklisteobjektet**

_Vandrar_

När en användare försöker ta bort ett checklisteobjekt från ett kort på en bräda svarar inte knappen [!UICONTROL Delete] och objektet tas inte bort.

**Anpassade formulär läses in långsamt**

_Anpassade formulär_

När en användare försöker läsa in ett anpassat formulär läses det anpassade formuläret in långsamt.

**Det går inte att flytta dokumentet till en annan mapp**

_Dokument_

När en användare flyttar ett dokument till en objektmapp kan han/hon inte flytta objektet till en annan mapp.

**XML-fel vid hämtning**

_Dokument_

När en användare försöker hämta ett dokument hämtas inte dokumentet, och användaren ser en sida med följande meddelande följt av XML-text.

[!UICONTROL The XML file does not appear to have any style information associated with it. The document tree is below.]

**Det går inte att hämta dokument från förhandsgransknings-/sandlådemiljöer**

_Dokument_

När en användare försöker hämta ett dokument från en annan miljö än produktionsmiljön hämtas inte dokumentet och användaren ser följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]

**Korrektur visas omättade eller beskurna**

_Korrektur_

Följande problem har rapporterats när du skapar ett korrektur från en URL.

* Behållaren ser uttunnad eller urtvättad ut.
* Beviset beskärs.

Detta kan göra att korrekturläsningsbeslut blir svåra eftersom korrekturet inte återges korrekt.

**Det tar lång tid att generera** korrektur

_Korrektur_

När en användare försöker generera ett korrektur tar det lång tid att generera korrekturet. Korrekturgenereringen kan ta flera dagar.

+++

+++**Underhållsuppdatering 14 september 2023**

**[!UICONTROL No factory]-fel vid tillägg av dokument**

_Dokument_

När en användare försöker lägga till ett dokument från en extern källa, kan [!DNL Workfront] inte komma åt källan och användaren ser följande fel:

[!UICONTROL The following error occurred: No factory found for authentication type null]

**&quot;Hoppfel&quot; i matrisrapporter**

_Rapporter_

När en användare försöker visa en matrisrapport läses rapporten inte in och användaren ser följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]

Detta inträffar när en rapport grupperas efter datumintervall.

+++

+++**Underhållsuppdatering 11 september 2023**

**Personliga uppgifter visas inte i tidrapporter**

_Tidrapporter_

Personliga uppgifter visas inte längre på tidrapporten som standard. Personliga uppgifter visas på tidrapporten när de är fästa eller har loggat timmar. Före den här ändringen visas personliga uppgifter på tidrapporter som standard.

+++

+++**Underhållsuppdatering 7 september 2023**

**Projektet är tomt när det läses in från en ny [!UICONTROL Home] upplevelse**

_Projekt_

När en användare klickar på ett projekt från sin [!UICONTROL Home]-sida i den nya hemupplevelsen, läses projektsidan inte in.

Detta inträffar när användaren har loggat in som en annan användare, sedan loggat ut som den andra användaren och återgått till sin egen [!UICONTROL Home]-sida.

+++

## Uppdateringar i augusti 2023

+++**Underhållsuppdatering 31 augusti 2023**

**Filter gäller inte för widgetar i den nya [!UICONTROL Home] upplevelsen**

_[!UICONTROL Home]_

När en användare använder ett filter på en widget i den nya [!UICONTROL Home]-upplevelsen visar widgeten objekt som ska uteslutas av filtret.

Detta har rapporterats i den anpassade sandlådemiljön. Samma widgetar i miljöfiltret för förhandsgranskning och produktion som förväntat.

**Problem vid inläsning av matrisrapporter**

_Rapporter_

När en användare försöker läsa in en matrisrapport som ett diagram kan något av följande inträffa:

* Viss information i rapporten läses inte in
* Rapporten ger felmeddelandet [!UICONTROL Unable to load content from the server]

**Planeraren läses inte in när filter används**

_[!UICONTROL Resource Planner]_

När en användare försöker läsa in [!UICONTROL Resource Planner] läses inte planeraren in och användaren ser följande felmeddelande:

[!UICONTROL The following error occurred: Something went wrong while connecting to WorkPerDay service]

+++

+++**Underhållsuppdatering 24 augusti 2023**

**Det går inte att markera text i listor eller punktlistor**

_Korrektur_

När en användare visar ett korrektur i korrekturläsaren och försöker markera text som finns i en lista eller en punkt, är textmarkeringsverktyget ineffektivt och texten kan inte markeras.

**Om du skapar en ny korrekturversion tas alla versioner av korrektur bort**

_Korrektur_

När en användare skapar ett korrektur från ett dokument skapas korrekturet. Om en användare skapar en annan version av korrekturet tas dock både den gamla och den nya versionen bort. Det finns ett [!UICONTROL Create Proof]-alternativ i originaldokumentet och korrekturversionerna finns i [!UICONTROL Trash]-området i [!UICONTROL Proofing]-området i [!DNL Workfront].

+++

+++**Underhållsuppdatering 17 augusti 2023**

**Det går inte att navigera till projekt med en URL som använder[!UICONTROL Reference ID]**

_Projekt_

När en användare försöker navigera till ett projekt med en URL som innehåller ett [!UICONTROL Reference ID]-nummer, dirigeras de om till en sida med ett felmeddelande. Navigering till en aktivitet med en URL med en [!UICONTROL Reference ID] fungerar som förväntat.

Inställningen **[!UICONTROL Disable proof email notifications] visas felaktigt**

_Korrektur_

När en användare visar korrekturinställningar i [!DNL Workfront] visas inte korrekt aktuell inställning i kryssrutan [!UICONTROL Disable proof email notifications]. När kryssrutan är markerad, vilket anger att korrekturmeddelanden via e-post är inaktiverade, aktiveras meddelanden. Motsatsen är också sann.

**Kan inte justera korrekturmarkeringar**

_Korrektur_

När en användare gör en kommentar i korrekturläsaren och sedan klickar bort kan användaren inte längre justera koden.

+++

+++**Underhållsuppdatering 10 augusti 2023**

**Det går inte att ta bort [!UICONTROL To-do] objekt i den nya [!UICONTROL Home]-upplevelsen**

_Startsida_

När en användare i den nya [!UICONTROL Home]-upplevelsen försöker ta bort ett objekt från [!UICONTROL To-do]-widgeten tas inte objektet bort och användaren ser följande fel:

[!UICONTROL There was a problem removing your to-do, please try again soon.]

Detta kan inträffa när timmar loggas till objektet [!UICONTROL To-do].

**Fastnålade projekt visar inte information i vissa kolumner**

_Projekt_

När en användare navigerar till ett fäst projekt med stiftet kan objektlistorna (t.ex. uppgiftslistan) visa tomma kolumner. En [!UICONTROL Assignments]-kolumn kan till exempel inte visa några tilldelningar, även om tilldelningar har gjorts.

**Vilolägesmodulen orsakar att scenarier låser sig**

_[!DNL Workfront Fusion]_

Modulen [!UICONTROL Tools] > [!UICONTROL Sleep] i ett scenario kan göra att ett scenario körs. Dessa körningar har statusen Körs i [!UICONTROL Scenario History] och slutförs inte.

+++

+++**Underhållsuppdatering 3 augusti 2023**

**Svårighet att hitta objekt i inloppskolumnen**

_Vandrar_

Inloppskolumnen på en styrelse sorterades tidigare efter den prioritet som definierats för uppgifter och frågor, vilket gjorde det svårt att hitta specifika punkter.

Standardordningen är nu följande:

Uppgifter:

* Primär order: Projektnamn
* Sekundär ordning: Arbetsfördelningsstruktur

Problem

* Primär order: Projektnamn
* Sekundärordning: Referensnummer

**Projektet löser inte problemet korrekt**

_Projekt/problem_

När en användare ändrar status för ett projekt som är det lösta objektet för ett problem, ändras ärendestatusen till en status som inte matchar samma nyckel som statusen för projektet.

**&quot;Hoppfel&quot; i matrisrapporter**

_Rapporter_

När en användare försöker visa en matrisrapport läses rapporten inte in och användaren ser följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]

Detta har rapporterats för användare inom EMEA.

+++

## Uppdateringar i juli 2023

+++**Underhållsuppdatering 27 juli 2023**

**Taggar och checklisteobjekt fungerar inte korrekt i projektpanelsvyn**

_Vandrar_

Taggar och checklisteobjekt har tagits bort från projektvyn eftersom de inte ingår i Workfront-åtgärderna och inte kan delas mellan användare.

**[!UICONTROL Enable system-wide] och [!UICONTROL View system-wide] representerar olika funktioner**

_Filter_

Om en användare delar ett filter och aktiverar alternativet [!UICONTROL View system-wide] delas filtret med alla användare i systemet. Om en administratör sedan visar det här filtret i [!UICONTROL Setup] ser de att filtret visar [!UICONTROL false] i kolumnen [!UICONTROL Visible System-Wide]. Om du vill göra det här filtret till ett standardsystem måste administratören aktivera alternativet [!UICONTROL Enable system-wide] i [!UICONTROL Setup]. Detta kan orsaka viss förvirring på grund av likheter i ordalydelsen.

+++

+++**Underhållsuppdatering 20 juli 2023**

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

+++

+++**Underhållsuppdatering 13 juli 2023**

**Tidslinjen räknar inte om**

_Projekt/uppgifter/problem_

När en jämn händelse inträffar som ska utlösa en tidslinjeberäkning, beräknas inte tidslinjen om. Detta påverkar omberäkningar som sker vid ändringar och schemalagda omberäkningar. Detta kan påverka noggrannheten för belastningsutjämnaren.

**Låsta korrekturgodkännanden visas fortfarande i arbetslistan**

_Korrektur_

Bevis på godkännanden som har passerat sin deadline och som är låsta visas fortfarande i godkännarens hemarbetslista, i stället för att släppas från listan när tidsgränsen har passerats.

**Användningsrapporten läses inte in**

_Rapporter_

När en kund försöker visa en användningsrapport ser användaren en indikator för snurrande inläsning, men rapporten läses inte in. Rapporten returnerade ett 500-fel, men användaren ser inget som tyder på att rapporten har misslyckats.

**Sidan Redigera användare är tom**

<!--no article-->

_Användare_

När en användare försöker redigera en annan användare är sidan Redigera användare tom och användaren kan inte redigera den andra användaren.

+++

## Uppdateringar i juni 2023

+++**Underhållsuppdatering 29 juni 2023**

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

+++

+++**Underhållsuppdatering 22 juni 2023**

**[!UICONTROL Whoops]-fel vid visning av matrisrapport**

_Rapporter_

När en användare visar en matrisrapport visas följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]

Detta har rapporterats när rapporten sorteras efter datum och alternativet [!UICONTROL Show weeks with no results] är aktiverat.

**Datum visas felaktigt i matrisrapporter**

_Rapporter_

När ett diagram eller en matrisrapport grupperas efter datum kan datum nära grupperingens kanter visas i rätt gruppering, föregående/nästa gruppering eller båda.

+++

+++**Underhållsuppdatering 15 juni 2023**

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

+++

+++**Underhållsuppdatering 8 juni 2023**

Den här uppdateringen innehåller endast mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 8 juni 2023**

[!DNL Fusion] har distribuerat en korrigering som förhindrar att en användares anslutningar tas bort när användaren tas bort eller inaktiveras i [!UICONTROL Adobe Admin Console].

[!DNL Fusion] teamadministratörer kan fortfarande ta bort onödiga anslutningar från sidan [!UICONTROL Connections] i [!DNL Fusion].

+++

+++**Underhållsuppdatering 1 juni 2023**

**Inget felmeddelande visas när aktiviteten sorteras om i [!UICONTROL Pending approval] status**

_Uppgifter_

När en användare försöker ändra ordning på en uppgift i en uppgiftslista och uppgiften har statusen [!UICONTROL Pending approval], verkar aktiviteten flyttas i uppgiftslistan. Användaren ser att objektet inte har flyttats vid uppdateringen. Objektet kan inte flyttas eftersom det har statusen [!UICONTROL Pending approval], men det finns inget meddelande som talar om för användaren att objektet inte kan flyttas, vilket kan leda till missförstånd.

**Inget felmeddelande visas när föregående aktivitet flyttas under den beroende aktiviteten**

_Uppgifter_

När en användare försöker ändra ordning på en uppgift i en uppgiftslista och uppgiften har statusen [!UICONTROL Pending approval], verkar aktiviteten flyttas i uppgiftslistan. Användaren ser att objektet inte har flyttats vid uppdateringen. Det går inte att flytta objektet eftersom en föregående aktivitet inte kan flyttas under en aktivitet som det är föregångare till, men det finns inget meddelande som talar om för användaren att objektet inte kan flyttas, vilket kan leda till missförstånd.

+++

## Uppdateringar i maj 2023

+++**Underhållsuppdatering 25 maj 2023**

**[!UICONTROL Kanban]-kort blir tomt när du redigerar kort**

_Agile_

När en användare ändrar något om ett kort på [!UICONTROL Kanban]-kortet blir [!UICONTROL Kanban]-kortet tomt i stället för att uppdateras med ändringen. Om användaren uppdaterar sidan manuellt, returneras [!UICONTROL Kanban]-tavlan med rätt ändring.

Detta har rapporterats under följande omständigheter:

* Redigera ett kort
* Flytta ett kort


+++

+++**Underhållsuppdatering 22 maj 2023**

**Det går inte att justera storleken på beskrivande text**

_Anpassade formulär_

När den anpassade formulärdesignern släpptes som betaversion var funktionen för att justera storleken på den beskrivande texten inte tillgänglig. Problemet har åtgärdats och användare kan nu justera storleken på beskrivande text.

+++

+++**Underhållsuppdatering 18 maj 2023**

**Rapporten sorteras inte korrekt vid sortering efter anpassat fält**

_Rapporter_
När en användare kör en uppgiftsrapport ser rapporten ut att sorteras korrekt när den läses in, men när den har lästs in ser användaren att rapporten inte är korrekt sorterad.

Detta verkar inträffa om alla följande omständigheter är uppfyllda:

* Rapporten är en uppgiftsrapport
* Rapporten sorteras efter ett anpassat fält
* En gruppering används för rapporten

+++

+++**Underhållsuppdatering 11 maj 2023**

**Det går inte att växla korrekturversion vid visning av korrektur**

_Korrektur_

När en användare visar ett korrektur i [!UICONTROL Proofing Viewer] och växlar till en annan version, inaktiveras listrutan för version och användaren kan inte växla tillbaka till den ursprungliga versionen de visade eller till en annan version av korrekturet.

**[!DNL Workfront]Timeout för sökning**

_Sök_

[!DNL Workfront]-sökningen väntar. Sökningen kan returnera några få resultat, eller inga alls.

Det här problemet påverkar även funktionen för modulen [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search].

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 11 maj 2023**

**Timeoutfel i[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

När ett scenario körs kan det ha ett timeout-fel. Informationen från modulen som innehåller felet når inte sitt mål.

**[!DNL Workfront]Timeout för sökning**

_Sök_

[!DNL Workfront]-sökningen väntar. Sökningen kan returnera några få resultat, eller inga alls.

Det här problemet påverkar även funktionen för modulen [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search].

+++

+++**Underhållsuppdatering 9 maj 2023**

**Sparade filter finns i kolumnen för ritbordsintag**

_Vandrar_

Nu kan du använda befintliga Workfront-uppgiftsfilter och utgivningsfilter när du konfigurerar en anslagskolumn för en anslagstavla. Befintliga filter för inloppskolumner är nu skrivskyddade på konfigurationspanelen. De befintliga filtren används fortfarande i inloppskolumnen, men du måste återskapa filtren om du vill redigera dem.

+++

+++**Underhållsuppdatering 4 maj 2023**

**Det går inte att välja mall från[!UICONTROL Favorite templates]**

_Mallar_

När en användare försöker välja en mall på Åtgärder-menyn (tre punkter) försvinner listan med mallar när användaren flyttar musen till listan och användaren inte kan välja någon mall. Det beror på att rullningslisten är mellan menyn och listan med mallar och musen fokuserar på rullningslisten när den flyttas till listan med mallar.

+++

## Uppdateringar i april 2023

+++**Underhållsuppdatering 27 april 2023**

**Kan inte växla mellan korrektur i[!UICONTROL Proof Viewer]**

_Korrektur_

När en användare visar ett korrektur i [!UICONTROL Proofing Viewer] och växlar till ett annat korrektur, svarar inte knappen för att byta korrektur. Användaren kan inte växla tillbaka till det ursprungliga korrekturet eller till ett annat korrektur.

**Redigera bifogade bilder när du redigerar en kommentar**

_Uppdateringar_

Du kan nu redigera bilden som är kopplad till en kommentar när du redigerar en kommentar. Det här är tillgängligt i uppdateringsavsnittet för Workfront-mål och i det som gäller problem när du aktiverar betafunktionen för kommentarer.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 25 april 2023**

**[!DNL Fusion]hjälplänkar i appen leder inte till specifika hjälpsidor**

_[!DNL Workfront Fusion]_

När en användare visar ett korrektur i [!UICONTROL Proofing Viewer] och växlar till ett annat korrektur, svarar inte knappen för att byta korrektur. Användaren kan inte växla tillbaka till det ursprungliga korrekturet eller till ett annat korrektur.

+++

+++**Underhållsuppdatering 20 april 2023**

**Problem i anpassade listrutefält**

_Anpassade formulär_

Anpassade listrutefält som är aktiverade som flervalsfält kan visa följande problem:

* Knappen +[!UICONTROL Add] finns inte när formuläret inte är i redigeringsläge.
* Fält som inte har värden visar ett &quot;—[!UICONTROL no label]—&quot;-alternativ.

**Det går inte att använda polygonverktyget när du gör en kommentar i ett korrektur**

_Korrektur_

När en användare visar ett korrektur i korrekturläsaren och försöker göra en kommentar med polygonverktyget markeras inte korrekturet.

**Textalternativrutan visar &quot;textAnnotations&quot;**

_Korrektur_

När en användare visar ett korrektur, börjar lägga till en kommentar och öppnar textverktyget, visas ordet&quot;textAnnotation&quot; bredvid alternativen i verktyget. Textverktyget fungerar fortfarande som förväntat och&quot;textAnnotation&quot; försvinner när kommentaren har publicerats.

**Behåll bilder som utkast när du flyttar bort från en uppdatering för mål och för problem i kommenteringsbetaupplevelsen**

>[!NOTE]
>
>Den här funktionen släpptes till Preview den 19 april 2023 och släpptes till produktion den 20 april 2023.

_Uppdateringar_

När du nu navigerar bort från uppdateringssidan medan du komponerar ett meddelande där du har bifogat en bild bevaras meddelandet och bilden när du går tillbaka. Före den här uppdateringen bevarades den ej inskickade kommentaren, men bilden togs bort. Detta är tillgängligt i uppdateringsavsnittet för mål och problem när du aktiverar betafunktionen för kommentarer.

**Uppdateringar i realtid och borttagna kommentarer i uppdateringsavsnittet**

>[!NOTE]
>
>Den här funktionen släpptes till Preview den 19 april 2023 och släpptes till produktion den 20 april 2023.

_Uppdateringar_

När någon lägger till en kommentar eller svarar, eller tar bort en kommentar från uppdateringsområdet, kan du nu se den nya kommentaren eller en indikation på att kommentaren togs bort i realtid, utan fördröjning. Detta är tillgängligt i uppdateringsavsnittet för mål och problem när du aktiverar betafunktionen för kommentarer.

**Åtkomstnivån har ändrats av systemet utan att det fanns någon post för ändringen**

_Användare_

En användares åtkomstnivå kan ändras oförutsägbart av systemet. När detta inträffar finns det ingen synlig uppdatering och ändringen visas inte i granskningsloggen.

+++

+++**Underhållsuppdatering 17 april 2023**

**Visa nya kommentarer utanför det synliga skärmområdet i [!UICONTROL Updates] -avsnittet av problem (nya kommentarer i Beta) och[!UICONTROL Goals]**

_Uppdateringar_

Vi har lagt till en meddelandebanderoll för avsnittet [!UICONTROL Updates] för att informera användare när det finns nyare kommentarer för ett objekt som kanske ligger utanför det synliga området på skärmen. Den här uppdateringen är för närvarande tillgänglig i målavsnittet [!UICONTROL Updates] och i problemavsnittet när den nya betafunktionen för kommentarer har aktiverats för problem.

+++

+++**Underhållsuppdatering 13 april 2023**

**Filter används inte på listan över förfrågningar**

_Begäranden_

När en användare visar en lista med begäranden som har ett filter, innehåller listan begäranden som filtret ska utesluta.

**Det går inte att välja [!UICONTROL Default Hour Type] eller[!UICONTROL Available Hour Types]**

_Användare_

När en administratör redigerar en användare och försöker välja en [!UICONTROL Default Hour Type] eller [!UICONTROL Available Hour Type] ser de att listrutorna för dessa fält är inaktiverade och att de inte kan välja timtyper.

+++

+++**Underhållsuppdatering 6 april 2023**

**Listrutor öppnas inte när en användare läggs till i ett korrektur**

_Korrektur_

När en användare lägger till en annan användare i ett korrektur i [!UICONTROL Proofing Viewer] kan inte listrutorna [!UICONTROL Proof role] och [!UICONTROL Email alerts] öppnas. Användaren kan inte tilldela ett korrekturfält eller en e-postavisering. Detta kan inträffa när en användare läggs till via en kommentar eller när korrekturet delas med användaren.

+++

## Uppdateringar i mars 2023

+++**Underhållsuppdatering 30 mars 2023**

**Det går inte att växla korrekturversion vid visning av korrektur**

_Korrektur_

När en användare visar ett korrektur i [!UICONTROL Proofing Viewer] och växlar till en annan version, inaktiveras listrutan för version och användaren kan inte växla tillbaka till den ursprungliga versionen de visade eller till en annan version av korrekturet.

**504-fel vid export av rapporter**

_Rapporter_

När en användare försöker exportera en rapport med ett stort antal objekt visas ett 504-fel och rapporten kan inte exporteras.

**Uppdatering som gjorts för en användares räkning visas direkt från användaren**

_Uppdateringar_

När en administratör är inloggad som användare och gör en kommentar, visas kommentaren som direkt från användaren, i stället för från administratören för användarens räkning.

+++

+++**Underhållsuppdatering 23 mars 2023**

**[!UICONTROL Summary]panelinnehåll är för brett för panelen**

_Dokument_

När en användare visar panelen [!UICONTROL Summary] för ett dokument är innehållet för brett för att visas på panelen. Panelen har nu en vågrät rullningslist och användaren måste rulla vågrätt för att se innehållet i panelen [!UICONTROL Summary]. Det beror på att dokumentets filnamn inte radbryts. Problemet är begränsat till filer där filnamnet har filtillägget HTML.

**Ny [!UICONTROL Desktop Proofing Viewer] version**

_Korrektur_

För att åtgärda ett kommentarsproblem i [!UICONTROL Desktop Proofing Viewe]r har vi distribuerat en ny version av korrekturläsaren för skrivbordet.

Användare som redan har [!UICONTROL Desktop Proofing Viewer] installerat får uppdateringen automatiskt.

Användarna kan även manuellt välja den senaste versionen. Mer information finns i [Installera [!UICONTROL Desktop Proofing Viewer]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html).

* Tidigare version: 2.1.22
* Ny version: 2.1.23

+++

+++**Underhållsuppdatering 16 mars 2023**

**Objekt i checklistan kopieras inte när ett kort kopieras**

_Vandrar_

När du kopierar ett ad hoc-kort (anslutna kort kan inte kopieras) kopieras inte checklisteobjekt till det nya kortet.

**Anpassat fält saknas när problem konverteras till projekt**

_Projekt_

När en användare konverterar ett problem till ett projekt med hjälp av en mall visas inte ett anpassat fält som fanns på problemet i projektet. Problemet gäller endast icke-administratörer.

**Anpassade meddelanden visas inte i e-postmeddelanden**

_Korrektur_

När en användare delar ett korrektur och lägger till ett anpassat meddelande visas inte det anpassade meddelandet i e-postmeddelandet till mottagaren. Ämnet är korrekturnamnet och meddelandet visas inte i e-postmeddelandet.

+++

+++**Underhållsuppdatering 9 mars 2023**

**Åtkomstnivån tilldelas inte när användaren återaktiveras**

_Användare_

När en användare återaktiverar en inaktiverad användare och försöker tilldela dem en åtkomstnivå i fönstret [!UICONTROL Reactivate User], fylls inte listrutan på åtkomstnivå som användartyper och användaren kan inte välja en åtkomstnivå. Om användaren skriver i åtkomstnivån och sparar, tilldelas den återaktiverade användaren inte den åtkomstnivån.

**Spara utkastet av en kommentar i [!DNL Goals] området**

_[!DNL Workfront Goals]_

När du nu navigerar bort från sidan [!UICONTROL Updates] för ett mål medan ett meddelande disponeras bevaras meddelandet när du går tillbaka. Före den här uppdateringen skulle den ej inskickade kommentaren ha tagits bort.

+++

+++**Underhållsuppdatering 2 mars 2023**

**Kan inte lägga till kort när gruppering används**

_Vandrar_

När en användare visar en anslagstavla med en gruppering och försöker lägga till ett kort, kan användaren bara ange kortets namn. Resten av kortfälten är inaktiverade, inklusive knappen [!UICONTROL Save].

Om användaren ändrar grupperingen till [!UICONTROL None] kvarstår problemet. Användaren måste ändra grupperingen till [!UICONTROL None] och sedan uppdatera sidan för att återställa möjligheten att lägga till ett kort.

**Anslutna kort har inte lagts till i kolumner baserat på status**

_Vandrar_

Även om kolumnprofiler används för status, visas nya anslutna kort i kolumnen längst till vänster och inte i den kolumn som motsvarar deras status.


**Länk till en kommentar omdirigeras till [!UICONTROL Details] sida**

_Uppdateringar_

När en användare följer en länk till en kommentar om ett objekt i Workfront läses uppdateringsströmmen in en kort stund och sedan dirigeras användaren till objektets [!UICONTROL Details]-område. Detta kan inträffa om användaren klickar på länken från ett e-postmeddelande eller klistrar in länken i sin webbläsare.

Detta påverkar för närvarande bara Document-objekt.

**Utskriftssammanfattningen läses inte in**

_[!UICONTROL Workfront Proof]_

När en användare försöker att läsa in sidan Skriv ut sammanfattning ser det ut som om sidan läses in, men aldrig läses in.

+++

## Uppdateringar i februari 2023

+++**Underhållsuppdatering 23 februari 2023**

**Länk till en kommentar omdirigeras till [!UICONTROL Details] sida**

_Uppdateringar_

När en användare följer en länk till en kommentar om ett objekt i Workfront läses uppdateringsströmmen in en kort stund och sedan dirigeras användaren till objektets [!UICONTROL Details]-område. Detta kan inträffa om användaren klickar på länken från ett e-postmeddelande eller klistrar in länken i sin webbläsare.

Detta påverkar för närvarande bara Document-objekt.

**Användaren kan inte redigera sina egna meddelandeinställningar**

_Användare_

När en användare med en [!UICONTROL Worker]-licens försöker redigera sina egna meddelandeinställningar, visas inte alternativen för [!UICONTROL Notifications] i [!UICONTROL Edit]-fönstret och användaren kan inte redigera inställningarna.

+++

+++**Underhållsuppdatering 16 februari 2023**

**Flera teamtilldelningar på anslagstavlor**

_Vandrar_

Du kan nu tilldela flera team till en uppgift eller ett ärende i en styrelse och till själva styrelsen.

**Ökning av kortets reservgräns**

_Vandrar_

Utgångsdatumet för kortet har ökat till 8 veckor/60 dagar i stället för 4 veckor/30 dagar.

**Den schemalagda inaktiveringen inaktiverar inte användaren**

_Användare_

När en användare är schemalagd att inaktiveras och det schemalagda datumet och den schemalagda tiden passerar, inaktiveras inte användaren.

+++

+++**Underhållsuppdatering 9 februari 2023**

Fältet **[!UICONTROL Story Points]har lagts till i uppgiftslistor och problemlistor och rapporter**

_Rapporter_

Fältet [!UICONTROL Story Points] är nu tillgängligt att lägga till i listor och rapporter för uppgifter eller problem. Det är ett redigerbart frihandsfält som inte är kopplat till planerade timmar eller grupptilldelningar.

+++

+++**Underhållsuppdatering 8 februari 2023**

**Filterknapp i intagskolumnen**

_Vandrar_

Inloppskolumnen på en anslagstavla innehåller nu en **[!UICONTROL Add a filter]**-knapp när kolumnen är tom och inga filter har skapats. Knappen öppnar konfigurationsområdet, där du kan lägga till filter för att ta in uppgifter och problem i inloppskolumnen.

+++

+++**Underhållsuppdatering 2 februari 2023**

Ikonen **[!UICONTROL Boards]visas i [!UICONTROL Main Menu] som standard**

_Vandrar_

Ikonen [!UICONTROL Boards] visas nu i [!UICONTROL Main Menu] för användare som inte har någon layoutmall. Alla nya layoutmallar som skapas innehåller som standard även stödlinjer på huvudmenyn. Befintliga layoutmallar har inte ändrats.

**Kan inte spara e-postmallar**

_Konfigurera_

När en användare försöker skapa eller redigera en e-postmall svarar inte knappen [!UICONTROL Save] och användaren kan inte spara mallen.

+++

## Uppdateringar i januari 2023

+++**Underhållsuppdatering 30 januari 2023**

**Kortkommandon har lagts till för vanliga tidrapportåtgärder**

_Tidrapporter_

Vi har introducerat följande kortkommandon för följande vanliga åtgärder i en tidrapport:

* Lägg till rad (Cmd+Option++ / Ctrl+Alt++)
* Radera en rad (Cmd+Option+- / Ctrl+Alt+-)
* Fäst eller ta bort fästpunkter för ett arbetsobjekt (Alt+P/Alternativ+P)
* Öppna kommentar (Skift+F2 / Skift+F2)
* Spara kommentar (Cmd+Enter / Ctrl+Retur)
* Expandera (Skift+Alt+Uppåtpil/Skift+Alt+Uppåtpil)
* Komprimera (Skift+Alt+Nedpil/Skift+Alt+Nedpil)

Området där dessa åtgärder utförs måste markeras för att de ska kunna tillämpas.

**Nya informationsikoner för tidrapporter, tidrapportprofiler och tidrapportinställningar**

_Tidrapporter_

>[!NOTE]
>
>Den här uppdateringen släpptes endast i förhandsvisningsmiljön den 3 november 2022 och är nu tillgänglig i Production.

Vi har lagt till flera informationsikoner i följande inställningar:

* Kryssrutan [!UICONTROL Can edit time] när du skapar eller redigerar en tidrapport eller en tidrapportprofil för att ange att godkännare när den är aktiverad även kan skicka, öppna eller redigera tidrapporten, såvida inte administratören begränsar dessa åtgärder i [!UICONTROL Timesheet Preferences] -området i [!UICONTROL Setup].
* &quot;[!UICONTROL Restrict timesheet editing to owners and admins]&quot; i området [!UICONTROL Timesheet & Hour Preferences] i [!UICONTROL Setup] för att indikera att följande användare även kan redigera tidrapporterna när de är inaktiverade: användare med administrativ åtkomst till tidrapporter och timmar, tidrapportgodkännare som har behörighet att redigera tid samt tidrapportsägarnas hanterare.

Observera att funktionaliteten för de här inställningarna inte har ändrats och att bara informationsikonerna har lagts till för att göra inställningarna tydligare.

+++

+++**Underhållsuppdatering 26 januari 2023**

**Fel när begäran skickades från[!DNL Outlook]**

_Integrationer_

När en användare försöker skicka en begäran med bifogade filer från ett [!DNL Outlook]-e-postmeddelande, överförs inte en eller flera bifogade filer och användaren ser följande fel:

[!UICONTROL The following error occurred: File with handle xxxx does not exist.]

Detta inträffar endast när en tilldelning görs för den nya begäran, antingen via begärandekön eller manuellt när begäran skapas.

**Ny version av korrekturläsaren för skrivbordet**

_Korrektur_

För att åtgärda ett problem med frysning i Desktop Proofing Viewer har vi distribuerat en ny version av Desktop Proofing Viewer. Användare som redan har installerat Desktop Proofing Viewer får den här uppdateringen automatiskt.

Användarna kan även manuellt välja den senaste versionen. Mer information finns i [Installera Desktop Proofing Viewer](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Tidigare version: 2.1.19
* Ny version: 2.1.20

**Användaren kan inte redigera sin egen användarinställning**

_Användare_

När en användare med en licens för Arbete, Granska eller Begäran försöker redigera sina egna användarinställningar, är popup-fönstret som öppnas tomt och användaren kan inte göra några ändringar. Användaren måste uppdatera sidan för att kunna stänga popup-fönstret.

+++

+++**Underhållsuppdatering 19 januari 2023**

**Intagskolumnfilter kan nu delas**

_Vandrar_

När intagskolumnens funktion släpptes till Boards kunde filter för att ställa in intagskolumnen bara ses av den person som skapade dessa filter. Nu kan skaparen dela filtren med andra användare eller team.

**Fästfunktionen finns i [!UICONTROL More] menu**

_Navigering_

Följande funktioner är nu tillgängliga på menyn [!UICONTROL More] för stift i produktionsmiljön:

* Byter namn på punkter
* Ändra ordning på punkter på menyn [!UICONTROL More]
* Flytta ett häftstift från menyn [!UICONTROL More] (när du gör det flyttas det sista stiftet i det övre navigeringsfältet till menyn [!UICONTROL More])

+++

+++**Underhållsuppdatering 18 januari 2023**

**Uttryck med jokertecken är inte giltiga i anpassade fält**

_Anpassad Forms_

När en användare använder ett jokertecken som \$$TODAY eller $$NOW tillsammans med en modifierare (till exempel&quot;-30d&quot;) i ett anpassat fält, accepterar inte valideraren jokertecknet som giltigt. Jokertecken utan modifierare betraktas som giltiga.

**[!UICONTROL Workload Balancer]visar timmar som inte är associerade med ett projekt/en aktivitet/ett problem**

_[!UICONTROL Workload Balancer]_

När en användare tittar på [!UICONTROL Workload Balancer] ser de timmar som loggats för en användare som inte är kopplad till något projekt, aktivitet eller problem, och de loggas inte heller som [!UICONTROL General] timmar. Dessa timmar kan endast visas i vyn 4 veckor eller 6 veckor.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering (snabbkorrigering) 12 januari 2023**

**404 fel i [!DNL Workfront] moduler**

_Workfront Fusion_

När ett scenario körs returnerar en [!DNL Workfront]-modul ett 404-fel.

Detta har rapporterats i följande moduler:

* [!UICONTROL Read a record]

+++

+++**Underhållsuppdatering (snabbkorrigering) 12 januari 2023**

**[!UICONTROL Whoops]-fel vid inställning av ett beräknat fält**

_Anpassad Forms_

När en användare skapar eller redigerar ett beräknat fält i ett anpassat formulär och inkluderar ett anpassat fält i det beräknade fältets uttryck, anses uttrycket vara ogiltigt. Knappen [!UICONTROL Save] är inaktiverad och användaren kan inte navigera bort från det anpassade fältet. Dessutom ser användaren följande meddelande under fältet:

[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]

Om du tar bort det anpassade fältet från uttrycket kan användaren spara och navigera bort från fältet.

**Det går inte att ange åtkomstnivåer**

_Användare_

När en användare försöker ändra åtkomstnivån för en annan användare är åtkomstnivåerna nedtonade och användaren kan inte ändra dem. Detta inträffar även om användaren som försöker göra ändringen är systemadministratör.

+++

+++**Underhållsuppdatering 12 januari 2023**

**Ctrl+F eller Cmd+F fungerar inte som förväntat i listrutor**

_Anpassad Forms_

När en användare fyller i ett anpassat formulär och söker i en listruta med Ctrl+F eller Cmd+F och sedan försöker hoppa till nästa förekomst av sökningen, återgår listrutan till början av listan i stället för att hoppa till nästa förekomst av sökningen. Detta inträffar när en listruta är inställd på att tillåta flera val.

**[!UICONTROL Edit Report]-skärmen är tom**

_Rapporter_

När en användare visar en rapport och försöker redigera rapporten, visas användaren på en tom skärm och kan inte redigera rapporten.

**Indragna uppgifter förblir inte indragna**

_Uppgifter_

När en användare visar en uppgiftslista och drar in en uppgift återgår uppgiften omedelbart till det ursprungliga (indraget) läget.

+++

+++**Underhållsuppdatering 5 januari 2023**

**Fästfunktionen finns i [!UICONTROL More] menu**

_Navigering_

Följande funktioner är nu tillgängliga på menyn [!UICONTROL More] för stift, endast i förhandsvisningsmiljön:

* Byter namn på punkter
* Ändra ordning på punkter på menyn [!UICONTROL More]
* Flytta ett häftstift från menyn [!UICONTROL More] (när du gör det flyttas det sista stiftet i det övre navigeringsfältet till menyn [!UICONTROL More])

**Begränsningen för projektgruppen har tagits bort från att lägga till användare i projektteamet**

_Team_

Vi har tagit bort den begränsning som innebar att användare som måste läggas till i ett projektteam måste finnas i den grupp som är kopplad till projektet. Nu kan du lägga till alla aktiva användare i ett projektteam, oavsett vilka grupper de tillhör.

**Nya informationsikoner för tidrapporter, tidrapportprofiler och tidrapportinställningar**

>[!NOTE]
>
>Den här uppdateringen släpptes till förhandsvisningsmiljön den 3 november 2022 och är nu tillgänglig i Production

_Workfront_

Vi har lagt till flera informationsikoner i följande inställningar:

* Kryssrutan&quot;Kan redigera tid&quot; när du skapar eller redigerar en tidrapportprofil eller en tidrapportprofil för att ange att godkännare när den är aktiverad även kan skicka, öppna eller redigera tidrapporten, såvida inte administratören begränsar dessa åtgärder under Inställningar för tidrapport i dialogrutan Inställningar.
* &quot;Begränsa redigering av tidrapporter till ägare och administratörer&quot; i delen Inställningar för tidrapport och timmar i installationsprogrammet för att ange att följande användare även kan redigera tidrapporterna när de är inaktiverade: användare med administrativ åtkomst till tidrapporter och timmars-, tidrapportgodkännare som kan redigera tid och tidrapportägarnas chefer.

Observera att funktionaliteten för de här inställningarna inte har ändrats och att bara informationsikonerna har lagts till för att göra inställningarna tydligare.

+++

## Tidigare underhållsuppdateringar

Information om tidigare underhållsuppdateringar finns här:

* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2022](2022-updates.md)
* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2021](2021-updates.md)
