---
title: Workfront Maintenance Updates
description: Underhållsuppdateringar för [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 2951a566384274e5f32544dd8be1872f3850af94
workflow-type: tm+mt
source-wordcount: '14492'
ht-degree: 0%

---

# [!DNL Workfront] Underhållsuppdateringar

Följande underhållsuppdateringar gjordes 2022.

>[!NOTE]
>
>Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Supporten meddelar dig när ett ärende som du har skickat har åtgärdats.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Underhållsuppdateringar före 2022 finns på [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

## Uppdateringar i december 2022

+++**Underhållsuppdatering (snabbkorrigering) 1 december 2022**

**Inline-redigeringsfel per användare orsakar inga felmeddelanden**

*Listor*

När en användare infogar redigering av ett objekt och gör ett fel som ska skapa ett felmeddelande, visas inget felmeddelande. Själva felet sparas inte i Workfront, vilket betyder att data inte påverkas, men det beror på att ett felmeddelande saknas.

Detta har rapporterats i följande situationer:

* Föregående: En föregående slinga skapas, till exempel tilldelas en uppgift till sig själv
* Datum: Ett omöjligt datum har angetts, till exempel ett slutförandedatum som är tidigare än startdatumet eller som ligger efter projektets slutförandedatum

**Alternativet &quot;Flytta till&quot; är inte tillgängligt i problemrapporter**

*Rapporter*

När en användare visar en problemrapport och försöker flytta ett problem är alternativet &quot;Flytta till&quot; inte tillgängligt på menyn Mer (tre punkter).


**Det går inte att stänga användarkortet i uppdateringsströmmen**

*Uppdateringar*

När en användare visar uppdateringar och håller pekaren över ett namn visas ett kort med information om användaren vars namn det är öppet och stängs inte automatiskt. Sidan svarar inte förrän kortet stängs manuellt genom att klicka på X:et i det övre högra hörnet.


+++

+++**Underhållsuppdatering 1 december 2022**

**Aktiviteten har en kanban-eftersläpningsordning på 0**

*Agile*

När en användare visar ett kanban-teams eftersläpning visas en eftersläpningsordning på 0 för en eller flera av uppgifterna.

**&quot;[!UICONTROL Invalid custom expression]&quot; när det refereras till &quot;[!UICONTROL owner]&quot; i ett beräkningsfält**

*Egna formulär*

När en användare lägger till ett beräknat fält i ett anpassat formulär på problemnivå och försöker lägga till en referens till ett[!UICONTROL owner]&quot; (t.ex. `ownerID`) sparas inte fältet och användaren ser följande meddelande:

&quot;[!UICONTROL This is an invalid customer expression, please try again.]&quot;

Detta inträffar även när uttrycket är giltigt.

**Kan inte komma åt element i [!DNL Workfront for Jira] integration**

*Integreringar*

Följande element kan för närvarande inte användas i [!DNL Workfront for Jira] integration för [!DNL Jira Cloud]:

* The [!UICONTROL Configuration] page
* The &quot;[!UICONTROL Open Workfront]&quot; på en [!DNL Jira] problem

**Problem med att lägga till anpassade meddelanden i visningsprogrammet för korrektur**

*Korrektur*

När en användare delar ett korrektur och försöker lägga till ett eget meddelande händer följande:

* Visningsprogrammet för korrektur zoomas in i korrekturet.
* Områdena i den vänstra navigeringen är inte längre responsiva.

**Inaktiverade användare är tillgängliga vid val av tidrapportgodkännare**

*Tidrapporter*

När en användare skapar en tidrapport och försöker tilldela en godkännare, innehåller listrutan inaktiverade användare. Om en inaktiverad användare väljs sparas inte tidrapporten och användaren ser följande meddelande:

&quot;[!UICONTROL Error. Sorry! Only users with Plan license can approve or reject timesheets. Please contact your system administrator.]&quot;

Eftersom den inaktiverade användaren inte kan tilldelas måste användaren välja en aktiverad användare. Tidrapporten fungerar därför som förväntat, men de inaktiverade användarna i listan kan orsaka förvirring eller besvär för användaren.

**Tidrapporten genereras inte**

*Tidrapporter*

Tidrapporter genereras inte trots inställningarna för tidrapportprofilen. Eftersom tidrapporten aldrig genereras är den inte tillgänglig för användaren att ange tid, och den visas inte i listor.

+++

## Uppdateringar i november 2022

+++**Underhållsuppdatering 17 november 2022**

**Dokument som placerats i [!UICONTROL Recycle Bin] om det är omarkerat när en aktivitet flyttas eller ett problem**

*Dokument*

När du avmarkerar [!UICONTROL Documents] när en uppgift eller ett problem flyttas, de dokument som är bifogade uppgiften eller problemet placeras i [!UICONTROL Recycle Bin] i 30 dagar. Administratören kan vid behov återställa dem. Den användare som avmarkerar Dokument i den rörliga processen får en varning om detta i [!UICONTROL Move Task] eller [!UICONTROL Move Issue] box. Före den här förbättringen togs dokumenten bort permanent.

**Om du döljer ett objekt döljs det felaktiga objektet**

*Layoutmallar*

När en användare ändrar om ett objekt är dolt eller visas, återspeglas ändringarna i ett annat objekt i layoutmallen.


+++

+++**Underhållsuppdatering 10 november 2022**

**Gruppredigera uppgifter ändrar aktivitetstilldelningar**

*Uppgifter*

När en användare gruppvis redigerar ett fält för en uppsättning uppgifter, tillämpas den första uppgiftens tilldelningar på alla uppgifter. Detta tar bort tidigare tilldelningar.

**Kan inte öppna ett interaktivt korrektur**

*Workfront Proof*

När en användare försöker öppna ett interaktivt korrektur öppnas inte korrekturet och användaren ser följande meddelande:

&quot;[!UICONTROL Proof not loaded (501) Try again]&quot;

+++

+++**Underhållsuppdatering (snabbkorrigering) 4 november 2022**

**Problem med uppgifter som lagts till i en iteration**

*Agile*

Följande problem har rapporterats om problem som har lagts till i en iteration:

* Vissa underuppgifter för en uppgift som lagts till i en iteration visas inte på [!UICONTROL Iteration] sida.
* När en användare försöker lägga till en saknad uppgift i iterationen läggs uppgiften inte till och användaren ser följande meddelande:

   &quot;[!UICONTROL The following error occurred: None of the selected items could be moved, because they are not assigned to an agile team or are not agile items]&quot;

**Uppgifter som tilldelats via gruppredigering visas inte i teamets eftersläpning**

*Agile*

När en användare tilldelar uppgifter till ett Scrum-team genom att använda gruppredigering visas inte dessa uppgifter i gruppens eftersläpning.

Kanban-teamen påverkas inte av detta problem.

**&quot;[!UICONTROL New proof recipients]&quot; textrutan är för liten**

*Korrektur*

När en användare visar ett korrektur och försöker dela korrekturet från [!UICONTROL Sharing] -fliken, &quot;[!UICONTROL New proof reciepients]är mycket liten. Användaren kan skriva ett namn, men eftersom rutan är så liten radbryts texten på ett sätt som är svårt att läsa.

**Rapportanvändningsinformationen uppdateras inte**

*Rapporter*

När en användare visar en rapport uppdateras inte den senast visade informationen, t.ex. Senast visade den och Senast visade av. Detta innebär att all användarinformation kan vara felaktig.

Detta beteende har rapporterats när användaren öppnar rapporten på följande sätt:

* Sök
* Stift
* Favoriter
* Senaste

När du öppnar rapporter via en kontrollpanel uppdateras den senast visade informationen.

**[!DNL Workfront]: 500-fel vid ändringar i en [!DNL Workfront] object**

*[!DNL Workfront]*

När en användare försöker göra ändringar i en [!DNL Workfront] -objektet, ändringarna sparas inte och användaren ser följande fel:

&quot;[!UICONTROL 500: Database error due to invalid SQL statement.]&quot;

Detta har rapporterats i följande situationer:

* Ändra ett objekts status
* Beräknar om tidslinjer
* Bifoga en mall
* Loggningstid

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 3 november 2022**

**Fel gällande [!UICONTROL apiKey] in [!DNL Workfront] > [!UICONTROL Watch Events] modul**

*[!DNL Workfront Fusion]*

När en användare försöker lägga till en webkrok i [!DNL Workfront] > [!UICONTROL Watch Events] får de följande fel:

&quot;[!UICONTROL The apiKey provided was empty or deemed invalid.]&quot;

+++

+++**Underhållsuppdatering 3 november 2022**

**Byt namn på avsnitten &quot;Schema&quot; och &quot;Schemaläggning&quot; för team och projekt i layoutmallen**

*Layoutmallar*

Flikarna Schema och Schemaläggning som är tillgängliga för att läggas till i en layoutmall på den vänstra panelen i ett team eller projekt har bytt namn till Arbetsbelastningsutjämning.

**Fel vid åtkomst till e-postaviseringsinställningar**

*Meddelanden*

>[!NOTE]
>
>Problemet förekommer både i produktions- och förhandsvisningsmiljön.

När en användare försöker ändra inställningarna för e-postmeddelanden kan ett av följande fel uppstå:

* &quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

* &quot;[!UICONTROL Failed to fetch email notification]&quot;

Detta har rapporterats i följande områden:

* [!UICONTROL Setup] > [!UICONTROL Email notifications]
* [!UICONTROL User] > [!UICONTROL Edit user]
* [!UICONTROL Groups]

+++

## Uppdateringar i oktober 2022

+++**Underhållsuppdatering 27 oktober 2022**

**[!UICONTROL HOUR]funktionen i beräkningsfält använder UTC**

*Egna formulär*

När ett beräkningsfält innehåller [!UICONTROL HOUR] funktionen returnerar funktionen värden baserade på UTC i stället för den förväntade tidszonen. Alla beräkningar som baseras på HOUR-värdet är därför felaktiga.

**[!UICONTROL Quick filter]returnerar inga resultat vid sökning efter team**

*Listor*

När en användare försöker använda [!UICONTROL Quick filter] i en lista för att söka efter ett team och om du anger namnet på teamet visas inga resultat, även när teamet är synligt i listan (till exempel i [!UICONTROL Assigned to] fält). Söker efter ordet[!UICONTROL team]&quot; returnerar inte heller några resultat.

**Det går inte att fästa om en sida efter att nålen tagits bort**

*Navigering*

>[!NOTE]
>
>Problemet löstes i Preview den 13 oktober 2022. Den fastställdes i produktion den 27 oktober 2022.

När en användare väljer[!UICONTROL Remove pin]&quot; på ett stift, får ett meddelande om borttagningen och försöker ersätta stiftet genom att klicka på &quot;[!UICONTROL Undo]&quot; i meddelandet ersätts inte stiftet i den övre navigeringen och inte heller läggs det till i listan över punkter under [!UICONTROL More pins] list (the three-dot menu in the [!UICONTROL Pins] område).

Om en användare försöker fästa sidan igen genom att gå till sidan och fästa den, skapas inte stiftet och användaren kan inte fästa sidan.

**Alla användare listas i [!UICONTROL Workload Balancer] när du använder en delbar länk i [!DNL Safari] webbläsare**

*[!UICONTROL Workload Balancer]*

När en användare följer en delbar länk till [!UICONTROL Workload Balancer] när du använder [!DNL Safari] webbläsaren ser de alla användare i stället för bara medlemmarna i teamet.

+++

+++**Underhållsuppdatering 20 oktober 2022**

**Fel vid grupptilldelning av ett team**

*Uppdrag*

När en användare gör en gruppredigering av uppgifter eller problem och tilldelar ett team efter att ha tilldelat en individ, sparas inte uppdragen och användaren ser följande fel:

&quot;[!UICONTROL Let's try that again - The following error occurred: teamAssignments must be either a list of objects or a list of IDs]&quot;

**&quot;[!UICONTROL Failed to upload file]&quot;-fel**

*Dokument*

När en användare försöker överföra en fil till [!UICONTROL Documents] -området, filen överförs inte och användaren ser felet &quot;[!UICONTROL Failed to upload file].&quot;

Detta har rapporterats vid försök att överföra MP4-filer.

**Antalet fel i den vänstra navigeringen av aktiviteten är felaktigt**

*Problem*

När en användare visar en uppgift visas numret på [!UICONTROL Issues] -avsnittet i den vänstra navigeringen representerar inte det faktiska antalet problem som är kopplade till uppgiften.


**[!UICONTROL Predecessor]ikon saknas i uppgiftshuvud**

*Uppgifter*

När en användare visar en uppgift saknas ikonen för föregående aktivitet i sidhuvudet.

+++

+++**Underhållsuppdatering 13 oktober 2022**

**Det går inte att fästa om en sida efter att nålen tagits bort**

*Navigering*

>[!NOTE]
>
>Problemet kommer att åtgärdas i förhandsversionen den 13 oktober 2022. Den kommer att fastställas i produktion den 27 oktober 2022.

När en användare väljer[!UICONTROL Remove pin]&quot; på ett stift, får ett meddelande om borttagningen och försöker ersätta stiftet genom att klicka på &quot;[!UICONTROL Undo]&quot; i meddelandet ersätts inte stiftet i den övre navigeringen och inte heller läggs det till i listan över punkter under [!UICONTROL More pins] list (the three-dot menu in the [!UICONTROL Pins] område).

Om en användare försöker fästa sidan igen genom att gå till sidan och fästa den, skapas inte stiftet och användaren kan inte fästa sidan.

**Kan inte namnge eller spara nyskapade filter**

*[!UICONTROL Resource Planner]*

När en användare försöker namnge ett nytt filter i [!UICONTROL Resource Planner]är namnrutan tom. Om användaren har tryckt ned blankstegstangenten visas dessutom [!UICONTROL Save] knappen inaktiveras.

**Det går inte att redigera namn eller procent färdigt för en aktivitet eller ett problem**

*Uppgifter och problem*

Användare med [!UICONTROL Contribute] åtkomst till en aktivitet eller ett problem kan inte redigera namnet på aktiviteten eller problemet i huvudet. Dessutom har användare med [!UICONTROL Contribute] åtkomsten kan inte redigera procentandelen färdigt för en aktivitet eller ett problem.

**Begärande och granskare räknas in i en organisations licensantal**

*[!DNL Workfront Proof]*

När en användare läggs till i ett korrektur som en granskare eller en begärande får han eller hon ett &quot;[!UICONTROL Visitor]&quot; permissions profile, which should not use a [!DNL Workfront Proof] licens. När användaren läggs till används dock antalet [!DNL Workfront Proof] antalet licenser ökar.

+++

+++**Underhållsuppdatering 11 oktober 2022**

**Det går inte att fästa om en sida efter att nålen tagits bort**

*Navigering*

>[!NOTE]
>
>Problemet löstes i Preview den 13 oktober 2022. Den kommer att fastställas i produktion den 27 oktober 2022.

När en användare väljer[!UICONTROL Remove pin]&quot; på ett stift, får ett meddelande om borttagningen och försöker ersätta stiftet genom att klicka på &quot;[!UICONTROL Undo]&quot; i meddelandet ersätts inte stiftet i den övre navigeringen och inte heller läggs det till i listan över punkter under [!UICONTROL More pins] list (the three-dot menu in the [!UICONTROL Pins] område).

Om en användare försöker fästa sidan igen genom att gå till sidan och fästa den, skapas inte stiftet och användaren kan inte fästa sidan.

+++

+++**Underhållsuppdatering 6 oktober 2022**

**Ny ritningstyp**

*Blueprints*

Ritningstypen Dashboard har lagts till i katalogen med ritningar. Tidigare var endast projektmallar och organisationsstrukturplaner tillgängliga.

**Element som överlappar på den vänstra panelen**

*Egna formulär*

När en användare arbetar i formulärbyggaren och formuläret har fler än 100 fält överlappar meddelandet som meddelar användaren om fältgränsen elementen i den vänstra panelen.

**Datumväljaren öppnas inte längre automatiskt vid indatafokus eller klickar**

*Navigering*

När en användare navigerar med tangentbordet öppnas datumväljare inte längre automatiskt vid det datum som tangentbordsfokus skickas till. Tangentbordsanvändare ska i stället gå till datumväljarikonen med tabbtangenten och trycka på Retur för att öppna datumväljaren. När en användare navigerar med musen öppnas datumväljarna inte längre automatiskt vid det datum användaren klickade på. I stället ska musanvändarna klicka på datumväljarikonen för att öppna datumväljaren.

Den här ändringen gjordes för att bättre överensstämma med gränssnittsmönster för datumväljare och för att skapa en mer tillgänglig upplevelse för användare som använder tangentbord och skärmläsare.

**Om du tilldelar flera team blir det bara ett team tilldelat**

*Team*

>[!NOTE]
>
>Problemet finns bara i förhandsvisningsmiljön.

När en användare tilldelar flera team till en uppgift eller ett problem visas bara ett team i uppdragslistan. Detta påverkar även rapporteringen. Rapporter som visar grupptilldelningar är felaktiga eftersom bara ett team visas som tilldelat uppgiften eller utgåvan.

**&quot;[!UICONTROL Your recent changes were not saved]&quot; fel vid autosparande av ändringar i en tidrapport**

*Tidrapporter*

När en användare försöker redigera en tidrapport på ett sätt som skulle utlösa en autosparfunktion, sparas inte ändringarna och användaren ser följande meddelande:

&quot;[!UICONTROL Your recent changes were not saved. Refresh the page to view.]&quot;

Detta har rapporterats vid redigering av följande:

* Timmar
* Uppgifter

**E-postmeddelanden fördröjs**

*Workfront Proof*

När en händelse inträffar i [!DNL Workfront Proof] som utlöser ett e-postmeddelande får användaren inte meddelandet omedelbart. Meddelandet kan fördröjas med flera timmar.

+++

+++**Underhållsuppdatering 3 oktober 2022**

**Spara tidrapporten manuellt när tidigare jobbroller har ändrats**

*Tidrapporter*

Om en jobbroll som du loggade tid för har ändrats och [!UICONTROL Assign job roles to hour entries manually] inställningen har inaktiverats måste du spara dina tidsposter manuellt tills timmar inte längre är loggade för den ändrade jobbrollen.

+++

## Uppdateringar i september 2022

+++**Underhållsuppdatering 29 september 2022**

**Användaren går inte tillbaka till föregående sida när korrektur stängs**

*Korrektur*

När en användare som visar ett korrektur inom [!DNL Workfront] stänger korrekturet, de returnerar inte sidan de var på innan de öppnade korrekturet. I stället dirigeras de om till en annan sida i [!DNL Workfront].

**Kan inte öppna korrektur i[!DNL Workfront]**

*Korrektur*

När en användare visar ett dokument i [!DNL Workfront] och försöker öppna korrekturet, korrekturet inte öppnas och användaren returneras till [!UICONTROL Document Details] sida.

**Timmar sparas inte när du använder [!UICONTROL Tab] key**

*Tidrapporter*

När en användare fyller i en tidrapport och navigerar mellan celler med [!UICONTROL Tab] så sparas inte timmarna. The [!UICONTROL Auto-save] visas inte längst ned på skärmen och om användaren uppdaterar sidan kan användaren se att timmarna inte sparats.

**Tomma sidor vid visning av ett korrektur med flera sidor**

*[!DNL Workfront Proof]*

När en användare visar ett korrektur med flera sidor kan användaren se sidminiatyrer, men sidorna öppnas inte i huvudvisningsprogrammet.



+++

+++**Underhållsuppdatering 22 september 2022**

**Det går inte att stänga användarkortet i uppdateringsströmmen**

*Uppdateringar*

När en användare visar uppdateringar och håller pekaren över ett namn visas ett kort med information om användaren vars namn det är öppet och stängs inte automatiskt. Sidan svarar inte förrän kortet stängs manuellt genom att klicka på X:et i det övre högra hörnet.

+++

+++**Underhållsuppdatering 15 september 2022**

**&quot;[!UICONTROL Someone else tried to save this project]&quot; fel vid inmatning av timmar**

*Tidrapporter*

När en användare försöker logga timmar för en uppgift på sin tidrapport sparas inte timmarna automatiskt och användaren ser följande fel:

&quot;[!UICONTROL We're sorry, but your save failed because someone else tried to save this project at the same time. Please try to save again.]&quot;

**Det går inte att stänga användarkortet i uppdateringsströmmen**

*Uppdateringar*

När en användare visar uppdateringar och håller pekaren över ett namn visas ett kort med information om användaren vars namn det är öppet och stängs inte automatiskt. Sidan svarar inte förrän kortet stängs manuellt genom att klicka på X:et i det övre högra hörnet.

**The &quot;[!UICONTROL Task role assignment]&quot; har bytt namn till &quot;[!UICONTROL Role assignment]&quot; när du tilldelar grupparbeten med[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

För att återspegla den nya funktionaliteten att kunna tilldela både uppgifter och problem samtidigt från [!UICONTROL Unassigned Work] har vi bytt namn på[!UICONTROL Task role assignment]&quot; fält till &quot;[!UICONTROL Role assignment]&quot; i [!UICONTROL Workload Balancer]. Fältet refererar till jobbroller som har tilldelats antingen uppgifter eller ärenden och det visas när användare tilldelas till objekt i [!UICONTROL Bulk Assignments] box.

+++

+++**[!DNL Workfront Scenario Planner]Underhållsuppdatering 15 september 2022**

**Filter som delas med en grupp visas nu i [!DNL Scenario Planner]&#39;s  [!UICONTROL Import Projects] lista för medlemmar i alla undergrupper**

*[!DNL Workfront Scenario Planner]*

När du nu delar ett projektfilter med en grupp som har ytterligare undergrupper visas filtret för alla grupp- och undergruppsmedlemmar som visar projekt i [!UICONTROL Import Projects] en planruta i [!DNL Scenario Planner].

+++

+++**Underhållsuppdatering 8 september 2022**

**Uppdaterade namn har återställts för användar- och rolltilldelningsfälten**

*Uppdrag*

Uppdragsfälten som tillfälligt byttes namn förra veckan har återställts till sina ursprungliga namn:

* [!UICONTROL Assignment Users]
* [!UICONTROL Assignment Roles]

**Fel när projektägaren togs bort från rubriken**

*Projekt*

När en användare försöker ta bort en [!UICONTROL Project Owner] från projektets huvud [!UICONTROL Project Owner] tas inte bort och användaren ser följande felmeddelande:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Storleksändrad [!UICONTROL Description] går tillbaka till ursprunglig storlek**

*Projekt, uppgifter och problem*

När en användare ändrar storlek på [!UICONTROL Description] i informationsdelen av ett arbetsobjekt för att göra det större och börjar sedan skriva i rutan, så återgår rutan till sin ursprungliga storlek. Användaren kan fortfarande skriva i rutan och innehållet sparas som förväntat

**Oavsiktlig avslutning vid skapande av uppgifter eller problem**

*Uppgifter och problem*

När en användare skapar en uppgift eller ett problem i ett projekt och klickar utanför popup-fönstret för att skapa, stängs popup-fönstret utan förvarning och all information som har angetts tidigare går förlorad.

**Borttagen möjlighet att skicka ett korrektur via e-post till en dropzone**

*[!DNL Workfront Proof]*

Från och med torsdagen den 8 september 2022 har vi tagit bort möjligheten att skicka ett bevis via e-post till en dropzon i den fristående [!DNL Workfront Proof] produkt.

Du kan fortfarande använda dropzone på andra sätt för att skicka in nya korrektur och nya versioner av korrektur till ditt konto utan att behöva logga in på ditt konto. Se [Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) för mer information.

+++

+++**Underhållsuppdatering 6 september 2022**

**Planerade datum som lagts till i listan med fält för anpassningsbara projektrubriker**

*Projekt*

Vi har lagt till [!UICONTROL Projected Start Date] och [!UICONTROL Projected Completion Date] till listan med fält för anpassningsbara projektrubriker när du använder en layoutmall.

**Ny gräns med ett bekräftelsemeddelande som visar antalet objekt som lagts till i en tidrapport**

*Tidrapporter*

När du väljer mer än 50 objekt att lägga till i en tidrapport får du nu ett bekräftelsemeddelande som visar antalet objekt som ska läggas till i tidrapporten och ger dig möjlighet att ändra kurs och inte lägga till alla objekt. Alla tillagda objekt fästs automatiskt på tidrapporten och måste tas bort manuellt från den aktuella och alla framtida tidrapporter.

+++

+++**Underhållsuppdatering 2 september 2022**

Lägg till [!UICONTROL Integrations] fält till projektets anpassade rubrik

*Integreringar*

Nu kan du lägga till [!UICONTROL Integrations] till den anpassade rubriken för ett projekt när du använder en layoutmall. När fältet har lagts till visas en länk till ett externt objekt som är länkat till projektet som finns i [!DNL Salesforce] eller [!DNL Anaplan], beroende på din integrering.

>[!NOTE]
>
>Den här underhållsuppdateringen släpptes tidigare till förhandsvisningsmiljön den 25 augusti 2022 och är nu i produktion.

+++

+++**Underhållsuppdatering 1 september 2022**

**Slutförda objekt som tagits bort från delegering**

*Delegeringar*

Nu delegeras endast ofullständiga objekt vars datum matchar datumet för en delegering till andra användare när delegeringen av arbetsobjekt börjar. Om objekt slutfördes innan delegeringen startades, delegeras de inte. Objekt som slutförs under delegeringens tidsram kommer att finnas kvar i arbetslista i Hem-området för både den som delegerar och den som utses i två veckor innan de tas bort automatiskt, om delegeringen inte har avslutats under dessa veckor.

**Metadatauppdateringar för [!DNL Adobe Workfront] for [!DNL Experience Manager Assets] och [!DNL Assets Essentials] integreringar**

*Integreringar*

Metadata pushas automatiskt när du lägger till en resurs i en länkad mapp.

Tidigare skulle metadata bara skickas när du lade till en resurs med [!UICONTROL Add new] nedrullningsbar meny.

**Det går inte att godkänna eller avvisa timmar i ett ärende**

*Problem*

När en användare försöker godkänna eller avvisa timmar på [!UICONTROL Hours] fliken för ett problem, [!UICONTROL Approve] och [!UICONTROL Reject] knappar saknas.

**Om du konverterar ett problem till ett projekt med en mall visas ett felaktigt felmeddelande**

*Problem*

När användaren konverterar ett problem till ett projekt med hjälp av en mall och ett fel uppstår visas en sida med meddelandet[!UICONTROL The Project no longer exists]&quot; i stället för rätt felmeddelande som förklarar orsaken till den misslyckade konverteringen.

**Kan inte skapa korrektur för filer över 1,5 GB**

*[!DNL Workfront Proof]*

När du skapar ett nytt korrektur och en användare överför en fil som är större än 1,5 GB blir filnamnet rött och korrekturet kan inte skapas.

+++

## Uppdateringar i augusti 2022

+++**Underhållsuppdatering 25 augusti 2022**

**Länkar för belastningsutjämnare visas felaktigt i instrumentpaneler**

*Kontrollpaneler*

Delningsbara länkar i Utjämning av arbetsbelastning visas felaktigt när de läggs till i en instrumentpanel som en extern sida. I stället för att använda den unika vyn/de unika filtren som är kopplade till länken, använder kontrollpanelen den senast använda vyn/filtren för arbetsbelastningsutjämnaren.

**Lägg till [!UICONTROL Integrations] fält till projektets anpassade rubrik**

*Projekt*

Nu kan du lägga till [!UICONTROL Integrations] till den anpassade rubriken för ett projekt när du använder en layoutmall. När fältet har lagts till visas en länk till ett externt objekt som är länkat till projektet som finns i [!DNL Salesforce] eller [!DNL Anaplan], beroende på din integrering.

>[!NOTE]
>
>Den här underhållsuppdateringen finns för närvarande bara i förhandsvisningsmiljön. Den släpps till produktion en vecka efter förhandsversionen.

**Anpassade data bevaras inte när du konverterar ett problem till ett tomt projekt**

*Projekt*

När en användare konverterar en utgåva till ett tomt projekt (utan mall) överförs inte data i beräknade fält till det nya projektet.

**Fel i tidslinjeplaneringsläge vid ändring av datum i ett projekt**

*Projekt*

När en användare försöker ändra ett datum i ett projekt som har [!UICONTROL Plan Mode] ange till [!UICONTROL Manual save] > [!UICONTROL Timeline Planning], ändras inte datumet och användaren ser ett fel.

&quot;[!UICONTROL Timeline Planning mode is available only when timelineDate is loaded. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Konsekvens när arbetsbelastningsutjämnaren öppnas med vyn Månad**

*Utjämning av arbetsbelastning*

Nu visas användarens tilldelade objekt utökat när de visas i [!UICONTROL Day], [!UICONTROL Week], eller [!UICONTROL Month] vyer. Före den här uppdateringen visades de tilldelade objekten som expanderade för [!UICONTROL Day] och [!UICONTROL Week] och komprimerade för [!UICONTROL Month] vy.


+++

+++**Underhållsuppdatering 18 augusti 2022**

**&quot;[!UICONTROL Add to Iteration]&quot; och &quot;[!UICONTROL Add to Kanban Board]&quot; som inte är tillgängliga när infogade redigeringsåtgärder i en rapport**

*Rapporter*

När en användare visar en lista över uppgifter i en rapport och öppnar [!UICONTROL More] -menyn, &quot;[!UICONTROL Add to Iteration]&quot; och &quot;[!UICONTROL Add to Kanban Board]&quot; är inte tillgängliga i listrutan. Om rapporten visas på en kontrollpanel visas[!UICONTROL Add to Iteration]&quot; och &quot;[!UICONTROL Add to Kanban Board]&quot; finns i listrutan.

**Matrisrapporter visas felaktigt vid bläddring**

*Rapporter*

När en användare visar en matrisrapport och rullar kan vissa visuella element i rapporten överlappa eller dupliceras.

**[!UICONTROL Milestone]vy borttagen från listan över tidrapporter**

*Tidrapporter*

The [!UICONTROL Milestone] vyn har tagits bort från tidrapportprojektlistan när du lägger till ett projekt.

**Hyperlänkar i ett interaktivt korrektur är inte aktiva**

*[!DNL Workfront Proof]*

När en användare visar ett interaktivt korrektur och klickar på en länk eller knapp som innehåller en länk, kommer användaren inte till sidan som länken eller knappen länkar till.

**Nytt korrektursidans textfält saknas**

*[!DNL Workfront Proof]*

På [!DNL New Proof] sida visas inte många textfält (inklusive fältetiketter, listrutealternativ och kryssrutenamn).

**Användarna får inga meddelanden när de taggas i ett korrektur**

*[!DNL Workfront Proof]*

När en användare är taggad i en korrekturkommentar får han/hon inget e-postmeddelande om kommentaren.

+++

+++**Underhållsuppdatering 12 augusti 2022**

**Nytt anpassbart rubrikfält har lagts till i början av rubriken**

*Sidhuvuden*

När du lägger till ett nytt fält i en anpassningsbar rubrik läggs fältet nu till som det första fältet till vänster i rubriken, eller omedelbart efter [!UICONTROL Search] inuti layoutmallen. Före den här ändringen lades fältet till som det sista fältet i rubriken.

+++

+++**Underhållsuppdatering 11 augusti 2022**

**Det går inte att redigera anpassade formulär på grund av en felaktig teckengräns för beskrivande textfält**

*Egna formulär*

När en användare försöker redigera ett anpassat formulär och det anpassade formuläret har ett [!UICONTROL Descriptive text] fält som innehåller fler än 512 tecken kan användaren inte spara ändringarna i det anpassade formuläret och ser följande fel:

&quot;Följande fält är ogiltiga: (Fält) är för långt, max 512&quot;

Detta påverkar [!UICONTROL Descriptive text] fält som tidigare har fungerat bra trots att de innehåller fler än 512 tecken.

**Data i fält som är dolda av avsnittsbrytningar bevaras inte vid konvertering av ett problem till ett projekt**

*Egna formulär*

När en användare konverterar ett problem till ett projekt och problemet innehåller ett anpassat formulär med data i en avsnittsbrytning som kan döljas med visningslogik, överförs inte data i det avsnittet till det nya projektet.

**Data i fält som döljs av avsnittsbrytningar bevaras inte när en begäran konverteras till ett projekt**

*Egna formulär*

När en användare konverterar en begäran till ett projekt, och begäran innehåller ett anpassat formulär med data i en avsnittsbrytning som kan döljas med visningslogik, överförs inte data i det avsnittet till det nya projektet.

**Det går inte att redigera anpassade formulär på grund av beskrivande textfält**

*Egna formulär*

När en användare försöker redigera ett anpassat formulär som innehåller ett beskrivande textfält fylls inte fältets etikett i. Användaren ser felet &quot;[!UICONTROL This field is required]&quot; under etikettfältet och användaren kan inte redigera det anpassade formuläret på grund av det här felet.

**Det går inte att ta bort instruktioner från ett anpassat fält i det anpassade formulärverktyget**

*Egna formulär*

När en användare redigerar ett anpassat fält och försöker ta bort befintlig text i [!UICONTROL Instructions] så tas texten inte bort när fältet sparas. Användaren kan redigera text, men kan inte ta bort den helt.

**Teamtilldelning när begäran skapas visas inte på ny begäran**

*Begäranden*

När en användare skapar en begäran och tilldelar ett team till begäran och sedan skickar begäran, tilldelas teamet inte den begäran som skapas. Detta påverkar endast grupptilldelning. Användartilldelningar fungerar som förväntat.

+++

+++**Underhållsuppdatering 4 augusti 2022**

Dessa problem korrigerades endast i den nya [!DNL Workfront] upplevelse.

Alla [!DNL Workfront Classic] togs bort den 14 juli 2022.

**Fel vid ändring av planerat slutförandedatum i huvudet för en aktivitet eller ett problem**

*Uppgifter och problem*

När en användare försöker ändra [!UICONTROL Planned Completion Date] i huvudet på en uppgift eller ett problem ändras inte datumet och användaren ser ett fel som liknar följande:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Uppdateringar i juli 2022

+++**Underhållsuppdatering 28 juli 2022**

Dessa problem korrigerades endast i den nya [!DNL Workfront] upplevelse.

Alla [!DNL Workfront Classic] togs bort den 14 juli 2022.

**Ett fel uppstod när ett objekt öppnades från[!UICONTROL Home Work List]**

*[!UICONTROL Home]*

När en användare försöker öppna ett objekt på sina [!UICONTROL Home Work List], objektet öppnas inte och användaren ser följande meddelande:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work try refreshing this browser page.]&quot;

**Uppgifter och ärenden som delegerats till en användare visas inte i användarens hemarbetslista**

*[!UICONTROL Home]*

När användare tittar på sina [!UICONTROL Home Work List]visas inte uppgifter eller problem som delegerats till användaren i listan och användaren kanske inte är medveten om delegeringarna.

**Schemalagda rapporter skickas inte till alla mottagare**

*Rapporter*

När en schemalagd rapport skickas skickas den inte till alla användare i[!UICONTROL Send to]&quot;. De utelämnade användarna är slumpmässiga och kan variera varje gång rapporten skickas.

**[!UICONTROL Cannot deselect tasks when attaching template]**

*Mallar*

När en användare bifogar och anpassar en mall ombeds de avmarkera uppgifter som de inte vill inkludera. Ingen av uppgifterna visas som markerad och användaren kan inte avmarkera dem.

**&quot;Språk&quot;-fält har nu mer specifika etiketter**

*Terminologi*

Så här gör du funktionen för[!UICONTROL Locale]&quot; fält tydligare, vi har uppdaterat deras etiketter.

* The &quot;[!UICONTROL Locale]&quot; på användarprofilen är nu märkt &quot;[!UICONTROL Email Locale]&quot;
* The &quot;[!UICONTROL Locale]&quot; som finns i [!UICONTROL Setup] >[!UICONTROL System] >[!UICONTROL Customer Info] området har nu etiketten &quot;[!UICONTROL Default Email Locale]&quot;

Funktionen för dessa fält har inte ändrats.

**Problem när tidrapporter skapas**

*Tidrapporter*

Följande problem har rapporterats när tidrapporter skapades:

* När en användare försöker skapa en tidrapport för en roll skapas inte tidrapporten och användaren ser felet &quot;[!UICONTROL User with primary key values 'XXXXXXXXXXX' not found.]&quot;
* När en användare försöker skapa en tidrapport för ett team [!UICONTROL typeahead] fältet fylls inte i med team och [!UICONTROL Create timesheet] knappen är inaktiverad.


**Områden i [!DNL Workfront Proof] uppdateras inte när ett korrektur skapas, flyttas eller arkiveras**

*[!DNL Workfront]Korrektur*

Dokumentet har för närvarande problem med indexeringsfördröjningar. Detta kan påverka användarupplevelsen på följande sätt:

* På kontrollpanelerna visas inte rätt antal korrektur
* Mappar uppdateras inte när ett korrektur skapas eller flyttas
* Arkiverade korrektur finns kvar i aktiva korrekturlistor.

+++

+++**Underhållsuppdatering (snabbkorrigering) 26 juli 2022**

Dessa problem korrigerades endast i den nya [!DNL Workfront] upplevelse.

Alla [!DNL Workfront Classic] togs bort den 14 juli 2022.

**Timmar som visas på tidrapporten skiljer sig från tidrapportlistan**

*Tidrapporter*

När en användare öppnar en tidrapport för att visa den, skiljer sig de timmar som visas från när användaren visar samma tidrapport i en tidrapportlista.


**Begäran konverterad till projekt med mall visar grupp från begärandekö, inte grupp från mall**

*Begäranden*

När en användare konverterar en begäran till ett projekt med hjälp av en mall kopplas det nya projektet till gruppen som äger begärandekön, inte till gruppen som är tilldelad mallen. Detta inträffar trots att gruppen som är kopplad till mallen fylls i i i [!UICONTROL Group] fält.

+++

+++**Underhållsuppdatering 21 juli 2022**

Dessa problem korrigerades endast i den nya [!DNL Workfront] upplevelse.

Alla [!DNL Workfront Classic] togs bort den 14 juli 2022.

**Status för avslag som är associerad med ett godkännande följer arbetsflödet för godkännande**

**OBS! Den här funktionen släpptes 22 juli 2022.**

*Godkännanden*

Om du väljer en status som är associerad med en godkännandeprocess som avvisningsstatus för en godkännandesökväg, flyttas det avvisade objektet till den valda statusen och markeras som &quot;[!UICONTROL Pending approval]&quot;. Om du till exempel väljer [!UICONTROL On Hold] för avvisningsstatus och [!UICONTROL On Hold] status är associerad med en godkännandeprocess, det avvisade objektet får statusen &quot;[!UICONTROL On Hold- Pending approval]&quot;, som kräver godkännande.

Före den här uppdateringen åsidosatte objektet godkännandeprocessen för avvisningsstatusen och placerades i [!UICONTROL On Hold] status.

**Konfigurera en anpassad hjälp-URL**

*[!UICONTROL Main Menu]*

Om din organisation har en anpassad intern hjälpwebbplats kan du konfigurera [!UICONTROL Main Menu] [!UICONTROL Help] -ikon för att gå till den sajten. Detta är användbart om hjälpwebbplatsen innehåller information om hur din organisation använder [!DNL Workfront].
Den här anpassade URL:en påverkar inte huvudhjälplänken i det övre området i [!DNL Workfront]eller de sammanhangsberoende länkarna i [!DNL Workfront]som för användarna till [!DNL Workfront] Hjälpwebbplats.

**Det går inte att välja Förfluten tid vid infogad redigering[!UICONTROL Task Duration]**

*Uppgifter*

När en användare visar en uppgiftslista och försöker redigera [!UICONTROL Task Duration]är följande tidsenheter inte tillgängliga:

* [!UICONTROL Elapsed Minutes]
* [!UICONTROL Elapsed Hours]
* [!UICONTROL Elapsed Days]
* [!UICONTROL Elapsed Weeks]
* [!UICONTROL Elapsed Months]

**[!UICONTROL My Updates]sidan är tom**

*Uppdateringar*

När en användare försöker visa sina [!UICONTROL My Updates] sidan läses inte sidan in. Användaren kan bara se [!DNL Workfront] navigeringsrubrik.

**&quot;[!UICONTROL Only Allow SAML 2.0 Authentication]&quot;-inställningen saknas när en användare kopieras**

*Användare*

När en gruppadministratör kopierar en användare och avmarkerar alternativet[!UICONTROL Send an invite email to this person]&quot;,[!UICONTROL nly Allow SAML 2.0 Authentication]kryssrutan visas inte som förväntat. Detta kan inträffa även när alla åtkomstkrav och behörighetskrav för den här åtgärden uppfylls.

+++

+++**Underhållsuppdatering 14 juli 2022**

Dessa problem korrigerades endast i den nya [!DNL Workfront] upplevelse.

Alla [!DNL Workfront Classic] togs bort den 14 juli 2022.

**Fel vid återställning av lösenord**

*Inloggning*

När en användare försöker återställa sitt lösenord kan han/hon inte återställa det och han/hon ser ett meddelande som talar om att han/hon inte har åtkomst. Användaren kan inte logga in på Workfront.

**Kan inte begära mer åtkomst till en rapport**

*Rapporter*

När en användare med begränsad åtkomst till en rapport försöker begära mer åtkomst till en rapport är alternativet att begära mer åtkomst inte tillgängligt under [!UICONTROL report actions] -menyn.

**Ett bekräftelsemeddelande uppdaterades när ett utkast för en begäran togs bort**

*Begäranden*

När en utkast tas bort visas det bekräftelsemeddelande som visas när du klickar på[!UICONTROL Discard draft]&quot; visar följande:

* [!UICONTROL Draft was discarded] (det här är ett meddelande som talar om att utkastet har tagits bort)
* [!UICONTROL Undo] (det här är en länk som du kan klicka på om du vill ångra åtgärden att ta bort utkastet. Då behålls utkastet i stället för att det tas bort.)

Före den här ändringen var alternativen:

* [!UICONTROL Draft will be discarded]
* [!UICONTROL Cancel]

**Datumvärden för journalpostfält är felaktiga när de används via API**

*Uppdateringar*

När en användare ändrar ett datumvärde för ett objekt och sedan öppnar API:t den journalpost som representerar den datumändringen, datumvärdena för [!UICONTROL oldDateVal] och [!UICONTROL newDateVal] som returneras av API:t är felaktiga.

**Fel vid försök att ångra kommentar**

*Uppdateringar*

När en användare försöker ångra en kommentar ångras inte kommentaren och användaren ser följande fel:

[!UICONTROL Error 403: You do not have sufficient access to delete this Note /attask/api-internal/NOTE]

**Ny begränsning av antalet tecken i en uppdatering i förhandsvisningen**

*Uppdateringar*

Att förbättra prestandan för [!UICONTROL Updates] har vi infört en ny gräns för hur många tecken du kan ange i en uppdatering eller i ett svar på en befintlig uppdatering. Den nya gränsen är 15 000 tecken. Uppdateringen ändrade inte antalet tecken som tillåts när API:t används. API-teckengränsen för uppdateringar är 4 000.

**Fel vid överföring av bifogad fil från [!DNL Workfront] för Outlook-integrering**

*Workfront Integrations*

När en användare försöker överföra en bifogad fil med [!DNL Workfront for Outlook] integrering, bilagan överförs inte och användaren ser följande meddelande:

[!UICONTROL Some attachments have not been uploaded. Reason: Something went wrong with uploading attachments.]

**Uppdatering av korrekturmeddelanden**

*[!DNL Workfront]Korrektur*

Tidigare den här månaden, som en del av en patch till [!DNL Workfront] I produktionsmiljön har vi åtgärdat ett fel i systemet för korrekturmeddelanden via e-post. Den här ändringen kommunicerades inte i underhållsuppdateringen när den släpptes. Vi har lagt till följande information i [Underhållsuppdatering 2 juni 2022](#maintenance-update-on-june-2-2022) :

Som ett resultat av felkorrigeringarna har den e-postadress som används för att skicka korrekturmeddelanden ändrats.

Tidigare innehöll korrekturmejladresser organisationens underdomän. Till exempel meddelanden@[företagsdomän].my.workfront.com

Nu innehåller profiler för e-postadresser inte längre någon underdomän för organisationen. Alla korrekturmeddelanden via e-post kommer från följande adress: notification@my.workfront.com

Därför rekommenderar vi att du utför följande åtgärder om du inte redan gjort det:

* Uppdatera skräppostfiltren så att de accepterar e-post från notification@my.workfront.com
* Uppdatera tillåtelselista för att acceptera e-post från notification@my.workfront.com

**Det går inte att ändra användaralternativen efter den första konfigurationen i Arbetsflödesmallar**

*[!DNL Workfront Proof]*

När en användare lägger till en användare i en arbetsflödesmall kan de konfigurera alternativ. När den inledande konfigurationen är klar kan användaren dock inte längre ändra följande:

* &quot;[!UICONTROL Resolve comments and apply actions]&quot;
* [!UICONTROL "Share proof by tagging]&quot;
* Korrekturroll ([!UICONTROL Reviewer], [!UICONTROL Approver], osv.)

**&quot;[!UICONTROL This project's work items]&quot; har återställts i projektet[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Vi har återställt filtret &quot;Det här projektets arbetsobjekt&quot; i [!UICONTROL Assigned] när du öppnar [!UICONTROL Workload Balancer] från ett projekt.

Filtret visas nu under[!UICONTROL Suggested]&quot; i filtren för [!UICONTROL Assigned Work] del av ett projekts [!UICONTROL Workload Balancer].

+++

## Uppdateringar i juni 2022

+++**Underhållsuppdatering 30 juni 2022**

**Visa [!UICONTROL Workload Balancer] i en vecka**

*[!UICONTROL Workload Balancer]*

Baserat på den feedback vi fått från många kunder har vi nu lagt till ett alternativ för att visa [!UICONTROL Workload Balancer] i en vecka. Före den här uppdateringen kan du visa [!UICONTROL Workload Balancer] för 4, 6 och 12 veckor. Med den här uppdateringen har vi också ändrat alternativet 12 veckor till 3 månader.

**Panelen Delegera är nu tillgänglig från arbetsbelastningsutjämnaren**

*[!UICONTROL Workload Balancer]*

OBS! Uppdateringen finns bara i förhandsvisningsmiljön. Funktionerna som är kopplade till den här uppdateringen kommer att vara tillgängliga i Production med version 2.3.

Du kan nu visa delegaterna för en uppgift eller ett problem från Utjämning av arbetsbelastning. När du tilldelar en uppgift eller ett problem från Utjämning av arbetsbelastning kan du visa en lista över tilldelningar samt en lista över delegater för uppgiften eller utgåvan, om de är delegerade.

**Det går inte att öppna slutpunktsinformation i API-utforskaren**

*API*

När en användare visar [!DNL API Explorer] och klickar på en slutpunkt visas inte slutpunktsinformationen.

**Problem med [!UICONTROL Details] när du använder[!UICONTROL Home Calendar]**

*Startsida*

När en användare använder [!UICONTROL Home Calendar] och klickar på en uppgift kan något av följande inträffa:

* The [!UICONTROL Details] visas kort och försvinner. Användaren kan inte komma åt informationen.
* The [!UICONTROL Details] visas inte. Användaren kan inte komma åt informationen.
* The [!UICONTROL Details] visas, men finns inte på rätt plats. Användaren kan klicka på knappen för att komma åt informationen.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 24 juni 2022**

**Datumväljaren stängs inte när det anpassade formuläret redigeras**

*Anpassad Forms*

När en användare redigerar ett anpassat formulär och försöker ändra ett datum, stängs inte datumväljaren när datumet markeras. Användaren kan inte stänga datumväljaren genom att spara, avbryta eller klicka utanför datumväljaren.

Detta har rapporterats i följande områden:

* [!UICONTROL Updates] area
* [!UICONTROL Home]

**Användaren kan inte flytta sig till en annan fas i ett korrektur**

*Korrektur*

När en användare visar [!UICONTROL Proof Workflow] av ett korrektur och försöker dra sig själv till en annan fas av korrekturet, så fäster användarens namn tillbaka till den ursprungliga scenen och de läggs inte till på den önskade scenen.

+++

+++**Underhållsuppdatering 23 juni 2022**

**[!UICONTROL Cannot add new request through dashboard]**

*Kontrollpaneler*

När en användare visar en kontrollpanel i ett projekt och försöker lägga till en ny begäran genom att klicka på [!UICONTROL +New Request] knappen, knappen svarar inte och användaren kan inte lägga till en ny begäran.

**Fel vid visning av objekt i Home Worklist**

*[!UICONTROL Home]*

När en användare visar sina [!UICONTROL Home Work List] och klickar på ett objekt i [!UICONTROL Approvals I've Submitted] visas följande fel på sidan:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Om användaren uppdaterar sidan klickar du på ett objekt i [!UICONTROL Work List], visas felet. Problemet påverkar inte längre bara objekt i [!UICONTROL Approvals I've Submitted] -avsnitt.

**Anpassat avsnitt i ett objekt innehåller resultat som inte finns i det objektet**

*Objekt*

När en användare visar en [!UICONTROL custom] i ett objekt visar det anpassade avsnittet objekt som inte är en del av det objektet. Detta har rapporterats när det anpassade avsnittet läggs till direkt i objektet och när ett anpassat avsnitt läggs till via en layoutmall.

**Uppgifter flyttas till fel projekt**

*Uppgifter*

När en användare flyttar uppgifter från projekt A till projekt B och sedan flyttar fler uppgifter från projekt A till projekt C, visas de uppgifter som ursprungligen flyttades till projekt B i projekt C.

**Vissa knappar/ikoner fungerar inte vid åtkomst [!UICONTROL Workload Balancer] från en delad länk eller kontrollpanel**

*[!UICONTROL Workload Balancer]*

När en användare går till [!UICONTROL Workload Balancer] via en delad länk eller en länk på en kontrollpanel och försöker använda elementet längst upp på skärmen, fungerar inte elementen. Detta har rapporterats för följande:

* [!UICONTROL Today]
* Bakåt- och framåtpilar
* [!UICONTROL Weeks]
* Kalenderikon (datumväljare)

+++

+++**[!DNL Workfront]Underhållsuppdatering av scenarioplan 23 juni 2022**

**Användare med [!UICONTROL Manage] behörigheter till en plan kan dela den med andra**

Som användare med [!UICONTROL Manage] behörigheter till en plan i [!DNL Scenario Planner]kan du nu dela den med andra användare. Före den här uppdateringen var det bara den som skapade planen som kunde dela planen med andra användare.

+++

+++**Underhållsuppdatering 16 juni 2022**

**Gruppadministratören kan inte lägga till medlemmar i gruppen**

*Grupper*

När en gruppadministratör försöker lägga till en användare i en grupp fylls inte användaren i i listrutan. Gruppadministratören kan inte välja några användare och kan därför inte lägga till några användare i gruppen.

**Anpassade kvartal visas inte när du anger ett filter**

*Filter*

När en användare skapar ett filter och filtrerar efter ett datumfält innehåller listrutan med tillgängliga operatorer för datumfältet inte några nyligen tillagda anpassade kvartal.

**&quot;Hoppar över&quot;-fel vid konvertering av ett problem till ett projekt via en mall**

*Projekt*

När en användare försöker konvertera ett problem till ett projekt via en mall och utgåvan har ett anpassat formulär som innehåller ett avsnitt som bara är tillgängligt för administratörer, konverteras inte problemet och användaren ser följande fel:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Förfrågningar skickas utan att obligatoriska fält har fyllts i**

*Begäranden*

När en användare skapar en begäran som inte fyller i obligatoriska fält och sedan skickar begäran, skickas begäran utan data i de obligatoriska fälten. Det förväntade beteendet är att begäran inte skulle skickas och att användaren skulle få ett meddelande om att de måste fylla i de obligatoriska fälten innan begäran skickas.

**Nya anpassade kvartal verkar inte sparas**

*Inställningar*

När en användare lägger till ett nytt anpassat kvartal under Projekt i installationsprogrammet och klickar på [!UICONTROL Save], finns det ingen visuell indikation på att filen har sparats. Användaren ser inget meddelande om att åtgärden lyckades, och [!UICONTROL Save] finns fortfarande kvar och är aktiv. Men om användaren uppdaterar sidan kan han eller hon se att de nya kvartalen visas i listan med anpassade kvartal.

Om användaren lägger till ett nytt kvartal klickar du [!UICONTROL Save], får ingen indikation på att filen har sparats, lägger till ytterligare ett kvartal utan att sidan uppdateras och klickar [!UICONTROL Save] Även här kan det hända att det andra tillagda kvartalet inte sparas.

**[!UICONTROL Team Work Requests]sidan är tom**

*Team*

OBS! Problemet finns bara i förhandsvisningsmiljön.

När en användare försöker öppna [!UICONTROL Work Requests] på en gruppsida är sidan tom. Användaren kan se det övre navigeringsfältet, men inget sidinnehåll.

+++

+++**Underhållsuppdatering 9 juni 2022**

**Kan inte markera objekt att filtrera i [!UICONTROL Portfolio Optimizer] inställningar**

*Portfolio*

När en användare finns i [!UICONTROL Portfolio Optimizer] och visar [!UICONTROL Project Filters] i [!UICONTROL Preferences] är kryssrutorna intill objekten inte tillgängliga. Användaren kan inte markera eller avmarkera kryssrutor och kan därför inte markera objekt som ska filtreras.

**Kan inte ändra [!UICONTROL Planned Start Date] eller [!UICONTROL Planned Completion Date] när &quot;[!UICONTROL Schedule From]&quot; är inte markerad**

*Projekt*

När en användare försöker redigera [!UICONTROL Planned Start Date] eller [!UICONTROL Planned Completion Date] av ett projekt, och[!UICONTROL Schedule From]&quot;alternativet för det projektet inte är markerat, [!UICONTROL Planned Start Date] och [!UICONTROL Planned Completion Date] områden är inaktiverade och användaren kan inte redigera dessa datum.

**Det går inte att redigera åtkomstnivå för användare**

*Användare*

När en användare som har planeraråtkomst som innehåller användaradmin (gruppanvändare) försöker redigera användare i gruppen som de är administratör för [!UICONTROL Access] nivåfältet är inaktiverat och användaren kan inte redigera åtkomstnivån.

+++

+++**[!DNL Workfront Scenario Planner]Underhållsuppdatering 9 juni 2022**

**Ändra storlek på den vänstra panelen i[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Nu kan du ändra storlek på den vänstra panelen i en plan i [!DNL Scenario Planner]. På så sätt kan längre initialnamn visas helt. Före den här uppdateringen trunkerades längre initialnamn.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 9 juni 2022**

**Data från anpassade formulär är inte tillgängliga i [!DNL Workfront Fusion] [!DNL Workfront] moduler**

*[!DNL Workfront Fusion]*

När en användare konfigurerar en [!DNL Workfront] modulen i [!DNL Workfront Fusion]och försök att välja utdata för modulen innebär att fält från anpassade formulär inte visas. Detta inträffar när det anpassade formuläret skapades för en typ av [!DNL Workfront] och sedan lades en annan typ till. [!DNL Workfront Fusion] visar endast fält från anpassade formulär som ursprungligen skapats för den valda objekttypen.

**Det går inte att rulla för att visa alla scenariokörningar**

*[!DNL Workfront Fusion]*

När en användare visar ett scenario körningshistorik och försöker rulla nedåt för att visa fler körningar, slutar körningarna att läsas in och användaren kan inte visa dem. Dessutom kan användaren inte bläddra tillbaka till de senaste körningarna.

+++

+++**Underhållsuppdatering 2 juni 2022**

**[!UICONTROL Portfolio Optimizer]visar poängen 0 vid användning av andra språk än engelska**

*Portfolio*

När en användare använder [!DNL Workfront] på ett annat språk än engelska och visar [!UICONTROL Portfolio Optimizer], visas poängen som 0. Detta kan inträffa även när affärsärendet inte är fullständigt.

**Felaktiga beräknade fältvärden när du skapar projekt från mall**

*Projekt*

När en användare skapar ett projekt från en mall som innehåller beräknade fält är fältvärdena som visas i det nya projektet felaktiga.

**Kan inte redigera [!UICONTROL Conditions] in [!UICONTROL Project Preferences] område på[!UICONTROL Setup]**

*[!UICONTROL Setup]*

När en användare försöker redigera [!UICONTROL Conditions] i [!UICONTROL Project Preferences] område på [!UICONTROL Setup], sidan är tom.

**Ny begränsning av antalet tecken i en uppdatering i förhandsvisningen**

*[!UICONTROL Workload Balancer]*

>[!NOTE]
>
>Den här uppdateringen gäller bara förhandsvisningsmiljön.

För att förbättra uppdateringsområdets prestanda har vi infört en ny gräns för hur många tecken du kan ange i en uppdatering eller svara på en befintlig uppdatering. Den nya gränsen är 15 000 tecken. Uppdateringen ändrade inte antalet tecken som tillåts när API:t används. API-teckengränsen för uppdateringar är 4 000. Uppdaterar stöd för anpassade TypeHead-typfält i filter för belastningsfördelning

Vi stöder nu filter baserade på [!UICONTROL Typeahead] skriv anpassade fält i arbetsbelastningsutjämnaren. Före den här korrigeringen var filtrering för den här typen av anpassade fält inte möjlig i arbetsbelastningsutjämnaren.

**Det går inte att redigera behörigheter för en användares roll**

*[!DNL Workfront Proof]*

När en användare försöker redigera[!UICONTROL Resolve comments and apply actions]&quot; eller &quot;[!UICONTROL Share a proof by tagging]&quot; behörigheter för en användares roll i [!DNL Workfront Proof], sparas inte ändringarna. Användaren får ett meddelande om att mallen har uppdaterats, men om användaren öppnar rollbehörigheterna igen kan användaren se att ändringarna inte sparades.

+++


## Uppdateringar i maj 2022

+++**Underhållsuppdatering 26 maj 2022**

Dessa problem korrigerades endast i den nya [!DNL Workfront] upplevelse. [!DNL Adobe Workfront Classic] stöds inte längre.

Alla [!DNL Workfront Classic] kommer att tas bort i juli 2022. Byt till den nya upplevelsen så snart som möjligt.

**Uppdaterade vägbeskrivningsavgränsare**

*[!DNL Workfront]*

OBS! Uppdateringen släpptes 24 maj 2022.

Vi har uppdaterat vägbeskrivningarna i alla områden där vägbeskrivningar finns tillgängliga. Objekten i vägbeskrivningarna avgränsas nu med rörledningar (|). Före den här uppdateringen separerades de med snedstreck (/).

**Kan inte redigera anpassade formulär med avsnittsbrytningar**

*Anpassad Forms*

När en användare försöker redigera ett anpassat formulär som har en avsnittsbrytning, kan han/hon inte redigera formuläret och ser följande meddelande:

[!UICONTROL Specified section break security cannot be applied on all object types]

**Problem vid utskrift av instrumentpaneler till PDF**

*Kontrollpaneler*

Följande problem har rapporterats vid utskrift av en kontrollpanel till PDF: PDF skriver inte ut varje rad i rapporten. Där rader saknas visas bara tomt utrymme.
PDF innehåller blanksteg mellan kolumnrubrikerna och den första raden i rapporten.

**[!DNL Portfolio Optimizer]visar poängen 0 vid användning av andra språk än engelska**

*Portfolio*

När en användare använder [!DNL Workfront] på ett annat språk än engelska och visar [!UICONTROL Portfolio Optimizer], visas poängen som 0. Detta kan inträffa även när affärsärendet inte är fullständigt.

**Vissa anpassade formulär visas inte när du redigerar en mall**

*Mallar*

När en användare försöker redigera de anpassade formulären i en mall genom att klicka på [!UICONTROL Edit] i mallens sidhuvud [!UICONTROL Edit Template] visas bara ett av de anpassade formulär som är kopplade till mallen.

**Delad länk till Utjämning av arbetsbelastning visar felaktigt tilldelat arbete**

*[!UICONTROL Workload Balancer]*

När en användare tittar på [!UICONTROL Workload Balancer] med hjälp av en delad länk [!DNL Workload Balancer] inkluderar [!UICONTROL Assigned Work] i [!UICONTROL Unassigned Work] -avsnitt. [!UICONTROL Assigned Work] har inget separat avsnitt. När användaren tittar på [!UICONTROL Workload Balancer] utan att använda den delade länken, [!UICONTROL Assigned Work] visas som förväntat.

+++

+++**Underhållsuppdatering 19 maj 2022**

**Kan inte skapa ett korrektur från en[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

När en användare försöker skapa ett korrektur från en [!DNL PowerPoint] som innehåller ett diagram, kan inte korrekturläsaren skapas.

**Kan inte skapa ett korrektur från en [!UICONTROL Word] dokument**

*[!DNL Workfront Proof]*

När en användare försöker skapa ett korrektur från en [!DNL Word] dokument som innehåller ett diagram kan inte korrekturläsaren skapas.

**Det går inte att lägga till ett anpassat meddelande när ett korrektur delas**

*[!DNL Workfront Proof]*

När en användare visar ett korrektur öppnas [!UICONTROL Share proof] och markerar [!UICONTROL Add custom message] kan användaren inte skriva i textrutan som öppnas. När användaren försöker skriva i den här rutan försvinner rutan omedelbart.

**Kan inte stänga korrektur**

*[!DNL Workfront Proof]*

När en användare visar ett korrektur och försöker stänga det saknas X:et som stänger korrekturet i det övre högra hörnet av korrekturet.

**Det går inte att lägga till eller ta bort gruppadministratör**

*Grupper*

Om en användare visar en [!UICONTROL Group] sida och försöker lägga till eller ta bort en gruppadministratör med hjälp av [!UICONTROL Group Administrators] i sidhuvudet sparas inte ändringarna och användaren ser följande fel:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Horisontell rullningslist blockerar objekt i slutet av listan**

*Projekt*

När en användare visar en lista i en vy som sträcker sig utanför skärmens sida blockerar den vågräta rullningslisten användarens vy över det sista objektet i listan.

**&quot;[!UICONTROL Unexpected error]&quot; vid konvertering av ett problem till ett projekt med hjälp av en mall**

*Listor*

När en användare försöker konvertera ett problem till ett projekt med hjälp av en mall konverteras inte problemet och användaren ser följande meddelande:

[!UICONTROL An unexpected error happened]

**The [!UICONTROL Status] fältet i en tidrapportvy är nu skrivskyddat**

*Tidrapporter*

Vi har ändrat [!UICONTROL Status] i en tidrapportvy som ska vara skrivskyddad. Före den här ändringen kunde användare redigera statusen för en tidrapport som gjorde att de kunde åsidosätta beslutet för tidrapportgodkännarna.

+++

+++**Underhållsuppdatering 12 maj 2022**

**[!UICONTROL Save]knappen slutar inte att läsas in när du redigerar ett projekt**

*Projekt*

När en användare redigerar ett projekt och försöker spara, märker de att [!UICONTROL Save] knappen visar ordet &quot;[!UICONTROL Loading].&quot; Om användaren klickar på den här knappen för att spara ändringarna i projektet svarar inte knappen och ändringarna sparas inte.

**Fältetiketter visas inte när du visar ett objekt i[!UICONTROL Home]**

*Startsida*

När en användare markerar ett objekt från sina [!UICONTROL Home Work List], området till höger om [!UICONTROL Home Work List] som visar att objektet inte innehåller fältetiketter. Fältvärdena finns.

**Snabbfilter fokuserar inte automatiskt på sökfältet**

*Listor*

När en användare är i en lista och klickar på förstoringsglaset för att snabbt filtrera, och sedan börjar skriva, visas inte texten. Det beror på att fokus ligger kvar på förstoringsglaset i stället för att flyttas till sökfältet.

Om du klickar på sökfältet överförs fokus och användaren kan ange texten i sin sökning.

**Användare som inte kan infoga redigeringsfält i en rapport**

*Rapporter*

När en användare försöker redigera ett fält i en rapport och fältet hämtas från ett anpassat formulär, kan användaren inte redigera fältet. Detta inträffar när det anpassade formuläret ursprungligen skapades för en annan objekttyp än det objekt det är kopplat till.

**Etikett- och knapptext visas inte när du skapar ett korrektur**

*[!DNL Workfront Proof]*

OBS! Problemet finns bara i förhandsvisningsmiljön.

När en användare försöker skapa ett korrektur visas inte texten för alternativ eller knappar. Därför vet användaren inte vad varje alternativ eller knapp representerar och kan inte konfigurera korrekturet.

+++

+++**Underhållsuppdatering 5 maj 2022**

**Det går inte att lägga till en ny faktureringspost**

*Projekt*

När en användare finns i [!UICONTROL Billing Records] området i ett projekt och använder [!UICONTROL New Billing Record] Om användaren försöker lägga till en ny faktureringspost visas inte fälten för en ny faktureringspost och faktureringsposten kan inte skapas.

**Fel vid grupptilldelning i[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

När en användare försöker göra tilldelningar i [!DNL Workload Balancer] för ett projekt omdirigeras användaren till en sida med följande meddelande:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Användaren kan inte navigera bort från den här sidan förrän sidan har uppdaterats.

**Uppdaterad navigering för att öppna [!UICONTROL Summary] för uppgifter och problem i[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Nu behöver du bara klicka på en aktivitet eller ett problem i [!UICONTROL Workload Balancer] öppnar panelen Sammanfattning. Innan den här uppdateringen var du tvungen att klicka på [!UICONTROL Open Summary] i verktygsfältet och klicka sedan på uppgiften eller problemet. Detta hade visat sig vara en förvirrande upplevelse som nu har korrigerats. Du kan även klicka på [!UICONTROL More] -menyn bredvid uppgifts- eller problemnamnet och klicka sedan på [!UICONTROL Open Summary].

**Gruppadministratören kan inte visa information om användare i gruppen**

*Användare*

När en användare som tilldelats en åtkomstnivå som innehåller [!UICONTROL User Admin (Group Users)] försök att visa information om en användare i gruppen med åtkomstinställningar visas med följande fel:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Det går inte att ta bort anpassad gruppstatus**

*Grupper*

När en användare försöker ta bort en anpassad gruppstatus från [!UICONTROL Group] sidan blir sidan tom och statusen tas inte bort.

**Inställningarna för e-postavisering är inkonsekventa mellan kontaktområdet och användarinformationen**

*[!DNL Workfront Proof]*

Inställningar för e-postavisering visas i [!UICONTROL Contacts] område på [!DNL Workfront Proof] för en viss användare skiljer sig från den e-postaviseringsinställning som har angetts i användarens [!UICONTROL User Details].

**Det går inte att använda textverktyget när du gör en kommentar i ett korrektur**

*[!DNL Workfront Proof]*

När en användare gör en kommentar på ett korrektur och försöker öppna [!UICONTROL Text] öppnas inte verktyget och användaren ser följande meddelande:

&quot;[!UICONTROL Text data for this page is still downloading. Please wait.]&quot;

**Proof-e-post kommer att skickas till användarens primära e-postadress**

*[!DNL Workfront Proof]*

Vi justerar hur e-postmeddelanden om korrektur skickas. Nu kommer meddelanden att skickas till användarens primära e-postadress i stället för till det alias som genereras av systemet.

Mer information om varför systemet genererar aliasmeddelanden finns i Användarsynkronisering mellan Adobe [!DNL Workfront] och [!DNL Workfront Proof].

+++

## Uppdateringar i april 2022

+++**Underhållsuppdatering 28 april 2022**

**Kan inte rulla till [!UICONTROL Save] när du redigerar en tidrapport**

*Tidrapporter*

När en användare redigerar en tidrapport kan han/hon inte rulla redigeringsfönstret tillräckligt långt för att se [!UICONTROL Save] och kan därför inte redigera tidrapporten.

**Den elektroniska signaturen kontrollerar nu Federations-ID**

*Korrektur*

När du signerar ett korrektur elektroniskt kontrollerar systemet nu Federations-ID om du har konfigurerat enkel inloggning i [!DNL Workfront Proof], förutom din e-post i [!DNL Workfront].

Tidigare kontrollerade systemet endast din e-post i Workfront.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 25 april 2022**

**[!UICONTROL Workload Balancer]läser inte in**

*[!UICONTROL Workload Balancer]*

När en användare försöker öppna [!UICONTROL Workload Balancer]läses sidhuvuds- och vänsternavigeringen in, men innehållet i arbetsbelastningsutjämnaren läses inte in. Användaren ser blinkande grå fyrkanter i stället för data. Ibland läses en del av innehållet in, men användaren ser fortfarande grå fyrkanter där de data som saknas finns.

+++

+++**Underhållsuppdatering 21 april 2022**

**Om du lägger till en uppgift hoppar sidan nedåt**

*Uppgifter*

När en användare lägger till en uppgift under en befintlig uppgift i en lista, hoppar sidan till nedre delen av listan. Även om den nya aktiviteten finns på rätt plats måste användaren rulla tillbaka för att hitta den.

**Användare som läggs till i ett korrektur kan inte komma åt korrekturets arbetsuppgift i[!DNL Workfront]**

*Korrektur*

Om en användare läggs till på en scen i ett korrekturarbetsflöde läggs användaren inte till i dokumentdelningen och får inte behörighet till korrekturets arbetspost i [!DNL Workfront]. När användaren är i [!DNL Workfront] och försöker öppna arbetsposten som korrekturet är kopplat till ser de följande meddelandet:

&quot;[!UICONTROL You do not have sufficient access to view this (object)]&quot;

Problemet gäller endast korrektur som redan skapats och användare som lagts till efter detta. Att lägga till användare i arbetsflödet innan korrekturskapande fungerar som förväntat.

**Kan inte skicka e-post för återställning av lösenord från[!DNL Workfront]**

*Användare*

När en användare försöker skicka ett e-postmeddelande för återställning av lösenord från en användarlista i [!DNL Workfront], är alternativet att skicka e-postmeddelandet inte tillgängligt.

**Knappen visar &quot;[!UICONTROL Start Issue]&quot; istället för &quot;[!UICONTROL Start Request]&quot;**

*Begäranden*

När en användare tittar på en begäran som tilldelats deras team visas en[!UICONTROL Start Issue]&quot; i huvudet i stället för i[!UICONTROL Start Request]&quot;.

**&quot;[!UICONTROL Undo comment]&quot; tar bort taggade användare**

*Uppdateringar*

När en användare taggar en annan användare i en kommentar, skickar kommentaren och väljer sedan&quot;[!UICONTROL Undo comment]&quot;visas kommentaren som vanligt i en uppdateringsruta, men den taggade användaren finns inte i [!UICONTROL Tagged users] box.

**Kan inte rulla när [!UICONTROL Milestone] visa i en rapport**

*Rapporter*

När en användare visar en rapport och väljer [!UICONTROL Milestone] på sidan visas vyn Milstolpe, men den rullas inte längre och användaren kan inte visa några milstolpar som finns längre ned på sidan.

**Felaktig valuta när rapporten visas på kontrollpanelen**

*Rapporter*

När en användare visar en rapport på en kontrollpanel är den valuta som används i rapporten felaktig. När användaren visar rapporten utanför kontrollpanelen är valutan korrekt.

**Slutfört filter visar inte Slutfört arbetsobjekt**&#x200B;

*[!UICONTROL Home]*

När en användare visar sina [!UICONTROL Home Work List] med [!UICONTROL Completed] filter valt, slutförda arbetsobjekt visas inte i listan. När [!UICONTROL All] -filtret är markerat, slutförda objekt tas med i listan och visar att det finns slutförda objekt.

**[!DNL Workfront]läser inte in**

*[!DNL Workfront]*

När en användare försöker logga in [!DNL Workfront]ser sidan ut att ha fastnat i en slinga med omdirigeringar eller uppdateringar och läses inte in.

+++

+++**Underhållsuppdatering 14 april 2022**

**Det går inte att lägga till en aktivitet från en rapport i ett anpassat avsnitt i en aktivitet**

*Uppgifter*

När en användare visar ett anpassat avsnitt för en uppgift och avsnittet innehåller en uppgiftsrapport, kan användaren inte lägga till en uppgift från den rapporten. The [!UICONTROL Add Task] markerar rapporten, men öppnar inte något fönster där användaren kan lägga till en uppgift.

**Knappen Klar på fel plats när du redigerar en vy**

*Vyer*

När en användare redigerar en vy [!UICONTROL Done] visas högre upp på skärmen och kan överlappa text.

Användaren kan redigera vyn som vanligt. Funktionen påverkas inte.

**Kan inte rulla när [!UICONTROL Milestone] visa i en rapport**

*Rapporter*

När en användare visar en rapport och väljer [!UICONTROL Milestone] på sidan visas vyn Milstolpe, men den rullas inte längre och användaren kan inte visa några milstolpar som finns längre ned på sidan.

**Tom skärm när uppdateringar visas**

*Uppdateringar*

När en användare visar uppdateringar och rullar skärmen för att visa uppdateringar längre ned, blir skärmen tom och användaren kan inte se några uppdateringar.

**Ett fel uppstod när användaren skulle tilldelas till en aktivitet som inte är tilldelad användarens roll**

*[!UICONTROL Workload Balancer]*

När en användare i [!UICONTROL Workload Balancer] försöker tilldela uppgifter till en användare vars jobbroll inte matchar den jobbroll som tilldelats aktiviteterna. Användaren ser ett meddelande om att uppgiften tilldelas med den primära jobbrollen för den tilldelade användaren. Men när användaren klickar på[!UICONTROL Assign],&quot; tilldelas uppgifterna inte och användaren ser följande fel:

&quot;[!UICONTROL Error. The server encountered an unknown error.]&quot;

+++

+++**Underhållsuppdatering 7 april 2022**

**Användare som läggs till i korrektur har felaktiga roller**

*Korrektur*

När en användare lägger till en annan användare i ett korrektur anges den användarens roll i korrekturet som &quot;[!UICONTROL Read-only]&quot; trots användarens korrekturroll.

**Det går inte att skicka e-post för återställning av lösenord till användaren**

*Användare*

När en användare försöker skicka en lösenordsåterställning till en annan användare ser han eller hon att [!UICONTROL Send Forgot Password Email] är inte tillgängligt i [!UICONTROL More] -menyn.

**[!UICONTROL Update All]skickar uppdateringar till användarprofiler i stället för projekt**

*Uppdateringar*

När en användare visar [!UICONTROL People] området i ett projekt och markerar [!UICONTROL Update All] och sedan anger en uppdatering, bokförs uppdateringen inte i själva projektet. Istället läggs de in i de enskilda användarprofilerna för varje användare i projektet.

**För många sidor vid utskrift av uppdateringar**

*Uppdateringar*

När en användare visar en uppdateringsström som skulle vara mer än en utskriven sida, och försöker skriva ut sidan, visar utskriftsskärmen att antalet sidor ligger långt över det faktiska antalet sidor som behövs för att skriva ut uppdateringarna. Om användaren sedan försöker skriva ut till PDF misslyckas skapandet av PDF.

**Användarna kan inte se hela listan med enheter som delas med en rapport när[!UICONTROL Visible System-Wide]&quot;-inställningen är aktiverad**

*Rapporter*

När rapporter delas med flera enheter visas i [!UICONTROL Report Access] kan användarna inte rulla till slutet av listan för att se hela listan när &quot;[!UICONTROL Visible System-Wide]&quot; aktiverad.

**Felaktig valuta används i rapporter**

*Rapporter*

Om en användare anger att valutan för ett projekt ska vara en annan än standardvalutan, visas en rapport om det projektet i stället för projektets standardvaluta.

**Senast visade information uppdateras inte i [!UICONTROL Report Usage] rapporter**

*Rapporter*

När en användare visar en rapport som visar information om den senaste gången rapporten visades, kan den informationen vara tom eller vara gammal. Felet påverkar fält som följande:

* [!UICONTROL Last Viewed By]
* [!UICONTROL Last Viewed Data]
* [!UICONTROL Last X Viewers]
* [!UICONTROL Views This Month / Quarter / Year]

**Slutförda uppgifter visas i[!UICONTROL Home Work List]**

*[!UICONTROL Home]*

När en användare visar sina [!UICONTROL Home Work List]visas Slutförda uppgifter i listan även när alternativet att visa Slutfört uppgifter inte har valts.

**Knappen Schema är inte synlig för att schemalägga uppdatering av sandlådan**

*Sandlådemiljö*

The [!UICONTROL Schedule] som används för att schemalägga en uppdatering av en sandlåda visas inte i den övre banderollen i sandlådemiljön.

**Ändringar i ett beräknat fält påverkar alla beräknade fält i ett formulär**

*Anpassad Forms*

När en användare är i den anpassade formulärbyggaren och ändrar värdet för ett beräknat formulär, visar alla beräknade fält i formuläret det nya värdet. Detta kan påverka nya eller befintliga beräkningsfält.

**Färger flimrar i anpassade formulärverktyg**

*Anpassad Forms*

När en användare arbetar med beräkningsfält i det anpassade formulärbyggaren, flimrar färgerna för fälten och uttrycken.

**[!UICONTROL Cannot reject an approval]**

*Godkännanden*

När en användare försöker avvisa ett godkännande [!UICONTROL Reject] knappen svarar inte och godkännandet avvisas inte.

**[!UICONTROL Projects]som standard används avsnittet Alla projekt trots föregående val**

*Projekt*

När en användare går till en projektsida via en flik som har fästs som en del av layoutmallen, blir sidan som standard [!UICONTROL All Projects] området i den vänstra navigeringen. Detta inträffar även när användaren väljer ett annat område i den vänstra navigeringen och sedan navigerar bort från sidan Projekt och tillbaka.

+++


## Uppdateringar i mars 2022

+++**Underhållsuppdatering 31 mars 2022**

**Tidszoner är inte konsekventa mellan [!DNL Workfront] och[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

När en användares profil är inställd på en viss tidszon i [!DNL Workfront], användarens tidszon i [!DNL Workfront Proof] är inställd på en annan tidszon.

**Länk för att skicka ett begärt dokument leder till en tom sida**

*Dokument*

När en användare tar emot en begäran om att skicka ett dokument och klickar på länken till objektet där dokumentet begärdes, leder länken till en tom sida. Detta kan inträffa när du klickar på en länk i ett e-postmeddelande eller i ett meddelande i appen.

**Gruppen tilldelas felaktigt vid konvertering av utgåva till projekt**

Grupper

När en användare konverterar ett problem till ett projekt med hjälp av en mall är funktionen:

* Om mallen har tilldelats en grupp visas den gruppen som gruppen för det nya projektet i fönstret för utleveranskonvertering.
* Om mallen inte har någon tilldelad grupp visas standardgruppen för den användare som konverterar utgåvan som grupp för det nya projektet i fönstret för utgivningskonvertering.
* Om mallen inte har någon grupp bör det nya projektet ärva gruppen från problemets projekt.

**Det går inte att bifoga ett anpassat korsobjektsformulär till begärandekön**

Begäranden

När en användare försöker lägga till ett anpassat korsobjektsformulär på en kös informationssida, visas inte korsobjektsformuläret i listrutan med tillgängliga formulär och användaren kan inte markera det att lägga till det i köinformationen.

**Användare kan inte tilldelas med sekundär jobbroll på[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

När en användare försöker tilldela en annan användare till en uppgift på [!UICONTROL Workload Balancer]och uppgiften har tilldelats en annan jobbroll än den tilldelade användarens primära jobbroll, och användaren tilldelas uppgiften av den primära jobbrollen och följande meddelande visas:

&quot;\&lt;name> matchar inte rollen \&lt;task role=&quot;&quot; assignment=&quot;&quot;>. 1 arbetsuppgift som för närvarande är tilldelad rollen &lt;\Task role tilldelning\> tilldelas \&lt;name> i rollen av \&lt;primary job=&quot;&quot; role=&quot;&quot;>.&quot;

Detta inträffar även om användaren inte har jobbrollen för aktivitetsrolltilldelningen som en sekundär jobbroll.

**Problem med Scrum Board &quot;Show more work items&quot; b**&#x200B;

*Agile*

När en användare klickar på [!UICONTROL Show more work items] på en Scrum Board, rullar sedan för att se de nya punkterna, [!UICONTROL Show more work items] Stapel fäster vid Scrum Board och följer med när den rullas. Detta kan göra korten svåra att läsa.

**Röda punkter visas i obligatoriska fält i anpassade formulär**

Anpassad Forms

När en användare visar ett obligatoriskt fält i ett anpassat formulär visas två röda punkter under asterisken som anger att fältet är obligatoriskt.

**Listrutan Tid har stängts av i uppmaningar**

*Rapporter*

När en användare fyller i uppmaningarna för en rapport och påträffar en datumväljare visas inte timväljaren längst ned i datumväljaren efter 2, och användaren kan inte välja något timvärde förutom 1 eller 2.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 29 mars 2022**

**Det går inte att ändra eller spara beräkningar i verktyget för anpassade formulär**

*Egna formulär*

Om en användare skriver in en beräkning manuellt i ett beräkningsfält i verktyget för anpassade formulär och sparar formuläret, sparas inte beräkningen. Om användaren öppnar det anpassade formuläret igen är fältet tomt.

Om en användare anger en beräkning i ett beräkningsfält i verktyget för anpassade formulär genom att använda listrutorna och sparar formuläret, sparas det värdet. Om användaren öppnar det anpassade formuläret på nytt kan användaren inte redigera det här fältet eller ta bort värdet, antingen manuellt eller med listrutan.

OBS! Den här felkorrigeringen innehåller ytterligare funktioner. När du börjar skriva i ett beräkningsfält visas nu möjliga uttryck eller beräkningar i en listruta nedan, på samma sätt som i beräkningsredigeraren. Klicka på ett objekt i listrutan för att lägga till det i beräkningsfältet.

+++

+++**Underhållsuppdatering 24 mars 2022**

**Tidszoner är inte konsekventa mellan [!DNL Workfront] och[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

När en användares profil är inställd på en viss tidszon i [!DNL Workfront], användarens tidszon i [!DNL Workfront Proof] är inställd på en annan tidszon.

**Obligatoriskt fältfel för ifyllda anpassade fält när en mall bifogas**

*Projekt*

När en mall med obligatoriska anpassade fält bifogas till ett projekt där fältet redan finns och fylls i visas följande fel: &quot;[!UICONTROL There are incomplete fields. Enter values for required fields before you can continue.]&quot; Klicka på &quot;[!UICONTROL Take me there]kan de se att fälten är ifyllda och de kan bifoga mallen.

**The [!UICONTROL Workload Balancer] blinkar när du växlar mellan datum**

*[!UICONTROL Workload Balancer]*

Timmarna för den användare som listas först i [!UICONTROL Workload Balancer] visas inte när du uppdaterar tidslinjen. Användaren och timmarna visas med alla grå rutor som bara blinkar. Det här händer om du går framåt och bakåt på tidslinjen.

Det verkar som att visningen återställs om filtret uppdateras. Om du flyttar bakåt och framåt på tidslinjen visas emellertid inte blixten igen och användaren måste ange att timmarna inte ska visas.

**Anpassad terminologi är inkonsekvent**

*Layoutmallar*

Användarna rapporterar att när [!DNL Workfront] administratören anpassar terminologin för vissa objekt med hjälp av en layoutmall. Det nya objektnamnet visas inkonsekvent i gränssnittet.

På [!UICONTROL Projects] sidan kan du fortfarande se sidtiteln som[!UICONTROL Projects]&quot;, trots [!DNL Workfront] administratören ändrade namnet för[!UICONTROL Projects]till något annat.

Detta skapar förvirring för slutanvändarna.

+++

+++**Underhållsuppdatering 17 mars 2022**

**Miniatyrbilder och huvudbilder är tomma när du visar flersidiga filer med [!DNL Safari] webbläsare**

*[!DNL Workfront Proof]*

När en användare försöker visa en fil med flera sidor i [!DNL Safari] webbläsaren är miniatyrbilderna tomma. Ibland kan huvudbilden också vara tom.

**Felaktig användarlista vid grupptilldelningar i[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

När en användare gör en grupptilldelning i [!UICONTROL Workload Balancer] och väljer ett projekt och en jobbroll är listan med tillgängliga användare felaktig. Det kan visa användare utan behörighet för Jobbroll eller Projekt, och användare med behörighet för Jobbroll och Projekt visas inte i listan.

**[!UICONTROL Sorting is not working in reports]**

*Rapporter*

När en användare klickar på en kolumn för att sortera efter den verkar sorteringen fungera, men resultatet återgår direkt till den ursprungliga sorteringen som den såg ut innan användaren klickade på kolumnen. Sorteringen i valfri kolumn behålls inte.

**Markera[!UICONTROL Nothing]&quot; återgår till [!UICONTROL Report Default] gruppera**

*Rapporter*

När en rapport har en inbyggd gruppering och användaren försöker välja &quot;[!UICONTROL Nothing]&quot; i [!UICONTROL Grouping] i den nedrullningsbara menyn visas rapporten inom kort utan gruppering och återgår sedan till [!UICONTROL Report Default] gruppering.

**Borttagen &quot;[!UICONTROL Blueprints access]&quot; -flik från inställningar för utkast**

*Blueprints*

OBS! Problemet finns bara i förhandsvisningsmiljön.

The [!UICONTROL Blueprints access] har tagits bort från inställningarna för utkast. Inga funktioner har tagits bort från inställningarna för utkast.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 14 mars 2022**

**Det går inte att rulla nedåt i användarlistan när tilldelning görs på Kanban-tavlan**

*Agile*

När en användare visar en [!DNL Kanban] och försöker göra ett uppdrag, den användarlista som visas när användaren skriver fortsätter att hoppa till toppen när användaren rullar nedåt. Användaren kan inte markera en användare som inte finns i den övre delen av listan och kan inte spara uppdragsändringen.

**[!UICONTROL Milestone]Vy i projektrapport orsakar fel**

*Rapporter*

När en projektrapport visas med [!UICONTROL Milestone] Visa, användare får en[!UICONTROL APIModel INTERNAL does not support namedQuery TILE:milestone-view (UIVW)]&quot;-fel.

**Anpassad terminologi är inkonsekvent**

*Layoutmallar*

Användarna rapporterar att när [!DNL Workfront] administratören anpassar terminologin för vissa objekt med hjälp av en layoutmall. Det nya objektnamnet visas inkonsekvent i gränssnittet.

På [!UICONTROL Projects] sidan kan du fortfarande se sidtiteln som[!UICONTROL Projects]&quot;, trots [!DNL Workfront] administratören ändrade namnet för[!UICONTROL Projects]till något annat.

Detta skapar förvirring för slutanvändarna.

**Det går inte att uppdatera beräkningar för befintliga beräknade fält**

*Anpassad Forms*

Användarna kan inte uppdatera/ändra beräkningarna i beräkningsfält. Om fältet skapades och sparades utan någon beräkning återgår byggaren till tom varje gång du försöker lägga till ett uttryck och spara/använda.

Om du skapar ett beräkningsfält med ett visst uttryck och sparar det återgår det till det tidigare värdet varje gång du försöker ändra beräkningen.

**[!UICONTROL Invalid Parameter]fel vid återställning av lösenord**

*Inloggning*

Användarna kan inte återställa sina lösenord i någon miljö. När de anger sin e-postadress och försöker fortsätta ser de ett fel.

[!UICONTROL Error: Invalid Parameter: Search Parameter value "domain"].

+++

+++**Underhållsuppdatering 10 mars 2022**

**Problem vid inloggning i förhandsvisningsmiljön**

*Inloggning*

Följande problem med inloggning i förhandsvisningsmiljön har rapporterats.

När en användare försöker logga in i förhandsvisningsmiljön visas ett meddelande om att han/hon har angett fel ID eller lösenord.

När en användare försöker återställa sitt lösenord visas felet[!UICONTROL ?Multiple users were found with the email address <example@example.com>?]&quot;

**Anpassade formulär läses in långsamt [!UICONTROL Project Details] area**

*Projekt*

När en användare försöker visa ett projekts [!UICONTROL Project Details] -området, kan anpassade formulär som är kopplade till projektet endast läsas in efter en fördröjning på 15 sekunder eller mer. The [!UICONTROL Add custom forms] detta alternativ påverkas också av fördröjningen.

**Anpassade formulärfältsvärden som inte sparats på dokumentsammanfattningspanelen**

*Dokument*

När en användare uppdaterar anpassade formulärfält på dokumentsammanfattningspanelen, och ett eller flera av dem är ett huvudfält, sparar ändringarna och navigerar bort från sammanfattningspanelen, sparas inte uppdateringarna. Detta inträffar endast när ett texthuvudfält redigeras, även om alla fält påverkas.

**Data bevaras inte vid konvertering av mallar på grund av åtkomstnivåer för malldelning**

*Projekt*

När en användare som har åtkomst till Visa i en delad mall försöker konvertera ett problem till ett projekt, kan data i anpassade formuläravsnitt som kräver [!UICONTROL Conrtibute] eller högre visningsåtkomst överförs inte till det skapade projektet.

**Fel vid överföring av ny dokumentversion**

*Dokument*

När en användare försöker överföra en ny version av ett dokument från dokumentlistan överförs inte dokumentet och användaren ser följande fel:

[!UICONTROL Error Cannot invoke "com.attask.boz.Document.getCurrentVersion()" because "document" is null]

**Det går inte att redigera faktureringstariffer**

*Projekt*

När en användare försöker redigera en faktureringsfrekvens på [!UICONTROL Billing Rates] -fliken i ett projekt, klicka på [!UICONTROL Edit] knappen öppnar [!UICONTROL Edit] ett kort fönster, men det stängs innan användaren kan ändra faktureringstakten. Redigeringsfönstret öppnas inte när du klickar på knappen igen.

**Offentlig länk för dokument leder till en tom sida**

*Dokument*

När en användare försöker öppna ett dokument med hjälp av en offentlig länk leder länken till en tom sida. Detta inträffar när länken öppnas i ett fönster där en [!DNL Workfront] sessionen är öppen.

**Hoppar över fel när en uppgift eller ett problem läggs till i listan**

*Uppgifter och problem*

När en användare som inte är administratör försöker lägga till en uppgift eller ett problem i en lista och fyller i anpassade fält skapas inte aktiviteten eller problemet och användaren ser följande fel:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Om du lämnar en uppdatering efter en statusändring återställs objektet till ett tidigare läge**

Projekt, uppgifter och problem

Om du ändrar status för ett projekt, en uppgift eller ett problem och sedan omedelbart börjar skriva en uppdatering utan att uppdatera sidan, visas föregående status i uppdateringsrutan. Om uppdateringen registreras återställs objektet till föregående status.

**Användare som läggs till i korrektur har felaktiga roller**

*Korrektur*

När en användare lägger till en annan användare i ett korrektur anges den användarens roll i korrekturet som &quot;[!UICONTROL Read-only]&quot; trots användarens korrekturroll.

Tillfällig lösning: Ställ in användarens korrekturroll i profilen till något annat och återställ sedan till rätt roll.

**Anpassat formulär läses inte in vid konvertering av problem till projekt med hjälp av mall**

*Egna formulär*

När en användare försöker konvertera ett ärende till ett projekt med hjälp av en mall kanske inte ett eller flera av de anpassade formulären som är kopplade till mallen läses in. När användaren konfigurerar mallen för det nya projektet visas följande meddelande i stället för de anpassade formulären:

&quot;[!UICONTROL Something went wrong, could not load form].&quot;

**Användaren kunde inte lägga till ett internt problem med visning av anpassade nedrullningsbara fält i vyn**

*Listor*

När en användare lägger till ett problem från en textbunden lista och det finns en anpassad vy där anpassade listrutefält tillämpas på listan, uppstår ett fel när användaren bara fyller i det nedrullningsbara fältet. Användaren har åtkomst till att redigera anpassade formulär och är projektägare med behörighet att hantera projektet.

[!UICONTROL Error: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it!]

**Behörighet att lägga till uppgifter i ett projekt krävs inte för att flytta eller kopiera en uppgift till projektet**

*Uppgifter*

Nu kan du flytta eller kopiera en uppgift till en annan uppgift i ett projekt utan att ha behörighet att lägga till uppgifter i målprojektet. Du måste ha behörighet att lägga till uppgifter i minst en av målprojektets uppgifter. Före den här uppdateringen behövde du behörighet att lägga till uppgifter i projektet för att flytta eller kopiera en uppgift till projektet eller någon av dess uppgifter.  Den här uppdateringen är nu tillgänglig i produktionsmiljön. Den har varit tillgänglig i förhandsvisningsmiljön från och med underhållsuppdateringen 24 mars 2022.

OBS! Den här uppdateringen kommer att vara tillgänglig i produktionsmiljön när du kopierar eller flyttar utgåvor efter 22.2-produktionsutgåvan. Mer information om den aktuella versionen finns på workfront.com/release.

**Listrutan Fråga är inaktiverad**

*Rapporter*

När du använder en uppmaning i en rapport kommer de nedrullningsbara menyer som gör att du kan välja filtreringsvillkor för rapporten att tas bort. Därför visas inte villkoren längst ned i den nedrullningsbara menyn.

**Arbetsuppgiften återgår till föregående status när en uppdatering görs**

*Uppdateringar*

När en användare ändrar status för en arbetspost i huvudet uppdateras inte statusen i [!UICONTROL Update] område. Om användaren sedan gör en uppdatering visar listrutan fortfarande den tidigare statusen. När uppdateringen sparas skriver den här tidigare, felaktiga statusen över den status som angetts i rubriken.

+++

+++**Underhållsuppdatering 3 mars 2022**

**Kan inte lägga till dokument från[!DNL Google Drive]**

*Dokument*

När en användare försöker lägga till ett dokument från [!DNL Google Drive], markeringen svarar inte och användaren kan inte välja vilka dokument som ska läggas till.

**Taggade användare läggs inte till för att uppdatera kopplingen**

*Uppdateringar*

När en användare är taggad i en uppdatering visas de inte i[!UICONTROL To]&quot; uppdateringsområdet eller dess svar.

**Korrekturanvändare har två separata korrekturkonton**

*[!DNL Workfront Proof]*

En användares e-postadress i [!DNL Workfront Proof] kan finnas i två separata konton med separata ID:n, som ger användaren två konton. Detta kan göra det svårt att hitta rätt konto.

**Hoppfel som visas i rapportrubriker**

*Rapporter*

När en användare visar en rapport visas följande fel i rapportrubriken:

&quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

Om användaren visar en kontrollpanel kan felet visas i huvudet för alla rapporter på kontrollpanelen.

**Data i fält som bara kan redigeras av administratörer i anpassade formulär bevaras inte vid konvertering av utgåvor till projekt**

*Projekt*

När en icke-admin-användare försöker konvertera ett problem till ett projekt med hjälp av en mall och felet innehåller data i fält som bara kan redigeras av en administratör, överförs inte dessa data till det nya projektet.

När en administratör konverterar problemet överförs data till det nya projektet som förväntat.

**[!DNL XLS]och [!DNL XLSX] filstorleksgränsen har tillfälligt minskats till 100 MB för korrektur**

*Korrektur*

För att åtgärda ett säkerhetsproblem har vi tillfälligt begränsat den maximala filstorleken för [!DNL XLS] och [!DNL XLSX] till 100 MB när du skapar ett korrektur.

OBS! Uppdateringen gjordes i förhandsvisningsmiljön den 24 februari och kommer att finnas i produktionsmiljön den 3 mars.

**Uppdatera till Workfront Search**

Sök

En fasad utrullning inleddes den här veckan för att uppdatera infrastrukturen för [!DNL Workfront] Sökfunktioner. Uppdateringen kommer att göra framtida förbättringar av sökfunktionen enklare och tillförlitligare. Med de här ändringarna läggs objekt till i [!DNL Workfront] indexeras snabbare och därför kommer sökresultaten att returneras snabbare.

Den stegvisa utrullningen fortsätter i 2 veckor.

**Uppdaterade verktygsfält för rapporter på kontrollpaneler**

Rapporter

Rapporter på kontrollpaneler visar nu ett nytt verktygsfält. Det här verktygsfältet är en del av de uppdateringar av listor och rapporter som sker genom [!DNL Workfront].

+++


## Uppdateringar i februari 2022

+++**Underhållsuppdatering (snabbkorrigering) den 24 februari 2022**

**Data bevaras inte vid konvertering av utgåvor till projekt om fältet är dolt i mallen**

*Projekt*

När en användare konverterar ett ärende till en mall och mallen innehåller ett anpassat formulär som visar eller döljer fält baserat på värden i andra fält, överförs inte data i fält som är dolda i mallen (datalfritt) vid konverteringen till det nya projektet.

**Det går inte att exportera resursplaneraren efter roll**

*Resursplanering*

När en användare försöker exportera [!DNL Resource Planner] när du använder [!UICONTROL View by Role] exportalternativet misslyckas inte och användaren får ett e-postmeddelande med följande meddelande:

Ett fel inträffade när din [!DNL Resource Planner] data.

**Knappen Kopiera begäran fungerar inte**

*Begäranden*

När en användare försöker kopiera en begäran, [!UICONTROL Copy Request] fungerar inte om användaren inte har åtkomst till köavsnittet via Visa.

+++

+++**Underhållsuppdatering 24 februari 2022**

**Anpassade formulärdata försvinner när andra formulärfält fylls i**

*Egna formulär*

När en användare fyller i ett anpassat formulär som en del av konverteringen av ett problem till ett projekt, kan det hända att data i ett annat anpassat fält försvinner om du fyller i ett anpassat fält. Om användaren anger de data som saknas igen visas följande felmeddelande när han/hon försöker skapa projektet:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**&quot;[!UICONTROL This approval process can be used by...]&quot;-fält saknas**

*Godkännanden*

När en användare skapar eller redigerar en godkännandeprocess i [!UICONTROL Setup] området,[!UICONTROL This approval process can be used by...]&quot; saknas. Detta kan inträffa när du skapar en godkännandeprocess eller när du redigerar en befintlig.

**Systemadministratören kan inte tilldela om användare när en grupp tas bort**

*Grupper*

När en systemadministratör tar bort en grupp har de bara möjlighet att tilldela om gruppens användare till grupper som systemadministratören är gruppadministratör för. Andra grupper visas inte i listrutan och administratören kan inte markera dem.

**Hoppfel vid konvertering av problem till projekt**

*Projekt*

När en användare försöker konvertera ett problem till ett projekt med hjälp av en mall och lägger till eller tar bort anpassade formulär från mallen, konverteras inte problemet och användaren ser följande meddelande:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Kan inte öppna korrektur; sida uppdateras**

*Korrektur*

När en användare försöker öppna ett korrektur går det inte att öppna det. Sidan uppdateras till slut.

**[!DNL XLS]och [!DNL XLSX] filstorleksgränsen har tillfälligt minskats till 100 MB för korrektur**

*Korrektur*

För att åtgärda ett säkerhetsproblem har vi tillfälligt begränsat den maximala filstorleken för [!DNL XLS] och [!DNL XLSX] till 100 MB när du skapar ett korrektur.

OBS! Uppdateringen kommer att göras i förhandsvisningsmiljön den 24 februari och i produktionsmiljön den 3 mars.

**Behörighet att lägga till uppgifter eller problem i ett projekt krävs inte för att flytta eller kopiera en uppgift eller ett problem till projektet**

*Projekt*

Nu kan du flytta eller kopiera en uppgift eller ett problem till en annan uppgift i ett projekt utan att ha behörighet att lägga till uppgifter eller problem i målprojektet. Du måste ha behörighet att lägga till uppgifter eller problem i minst en av målprojektets uppgifter. Före den här uppdateringen behövde du behörighet att lägga till aktiviteter eller problem i projektet för att flytta eller kopiera en aktivitet eller ett problem till projektet eller någon av dess uppgifter. Den här uppdateringen är bara tillgänglig i förhandsvisningsmiljön.

OBS! Den här uppdateringen kommer att vara tillgänglig i produktionsmiljön när du kopierar eller flyttar uppgifter den 10 mars. Den här uppdateringen är tillgänglig i produktionsmiljön när du kopierar eller flyttar problem med 22.2-produktionsversionen. Mer information om den aktuella versionen finns i workfront.com/release.

**Uppdatera till Workfront Search**

*Sök*

En fasad utrullning inleddes den här veckan för att uppdatera infrastrukturen för [!DNL Workfront] Sökfunktioner. Uppdateringen kommer att göra framtida förbättringar av sökfunktionen enklare och tillförlitligare. Med de här ändringarna läggs objekt till i [!DNL Workfront] indexeras snabbare och därför kommer sökresultaten att returneras snabbare.

Den stegvisa utrullningen fortsätter i 2 veckor.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 18 februari 2022**

**Validering av fältvärdetyp har lagts till i [!DNL Anaplan] egenskaper för listobjekt**

*[!DNL Adobe Workfront Fusion]*

Ett problem har korrigerats som tillåter användare att placera fel datatyp i fält för egenskaper för listobjekt. Validering av egenskapstypen tillåter [!DNL Fusion] för att säkerställa att rätt datatyp skickas till Anaplan, vilket eliminerar fel orsakade av felaktiga datatyper.

+++

+++**Underhållsuppdatering 17 februari 2022**

**Fel vid borttagning av föregående från fliken Föregående**

*Uppgifter*

När en användare försöker ta bort en föregångare från [!UICONTROL Predecessors] för en uppgift tas uppgiften inte bort och användaren ser följande fel:

[!UICONTROL Task with primary key value(s) "" not found]

**Hoppfel när användarsidan öppnas**

*Användare*

När en användare försöker öppna [!UICONTROL Users] sidan öppnas inte sidan och användaren ser följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Överlappande element i rubriken för en rapport på en kontrollpanel**

*Kontrollpaneler*

När en användare visar en rapport på en kontrollpanel ser de att grupperingsikonen och etiketten överlappar länkarna till [!UICONTROL Details] och [!UICONTROL Summary].

**Problem med[!UICONTROL More]&quot; för dokument och korrektur**

*Dokument*

När en användare väljer ett dokument eller ett korrektur på en [!DNL Workfront Classic] dokumentlista och klicka sedan på &quot;[!UICONTROL More],&quot; kan de se något av följande: Knappen svarar inte Alla alternativ under knappen har etiketten &quot;[!UICONTROL object Object]&quot; och kan inte användas.

**Felet&quot;Du måste vara systemadministratör&quot; när du skapar ett projekt**

*Projekt*

När en användare som inte är administratör försöker skapa ett projekt och bifogar ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, kan de inte skapa projektet och de ser följande fel:

&quot;Du måste vara systemadministratör för att kunna ändra det här anpassade dataparametervärdet&quot;

**Data i ett anpassat formuläravsnitt som bara är för administratörer bevaras inte vid konvertering av utgåvor till projekt**

*Projekt*

När en användare konverterar ett problem till ett projekt med hjälp av en mall som har ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, överförs inga data i avsnittet med enbart administratörer till det nya projektet. Detta inträffar även om en administratör konverterar problemet.

+++

+++**Underhållsuppdatering 10 februari 2022**

**&quot;[!UICONTROL You must be a system admin]&quot; fel när ett projekt skapas**

*Projekt*

När en användare som inte är administratör försöker skapa ett projekt och bifogar ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, kan de inte skapa projektet och de ser följande fel:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**Användare som har inaktiverats och återaktiverats visas inte i[!UICONTROL Proof contacts]**

*[!DNL Workfront Proof]*

När en användare visar sin kontaktlista i [!DNL Workfront Proof]visas inte användare som har inaktiverats och återaktiverats i listan.

**Meddelandet &quot;Något gick fel&quot; när ett problem konverterades till ett projekt med hjälp av en mall**

*Projekt*

När en användare som inte är administratör försöker konvertera ett ärende till ett projekt med hjälp av en mall visas följande meddelande i anpassade formulärfält som bara är synliga för administratörer:

&quot;[!UICONTROL Something went wrong, could not load form]&quot;

**Felet &quot;Det går inte att läsa in sidinnehåll&quot; vid visning av projektinställningar**

*Inställningar*

När en administratörsanvändare försöker visa projekt, uppgifter eller problem under [!UICONTROL Project Preferences] i [!UICONTROL Setup] -området, sidan läses inte in och användaren ser följande fel:

&quot;[!UICONTROL Cannot load page content. Please try refreshing the page.]&quot;

+++

+++**Underhållsuppdatering 3 februari 2022**

**[!UICONTROL BizContext]fel vid inloggning**

*Inloggning*

När en användare försöker logga in på [!DNL Workfront], inloggningen misslyckas och följande meddelande visas:

&quot;[!UICONTROL Let's try that again. Database error: BizContext commit failed!]&quot;

Detta har rapporterats i förhandsvisningsmiljön.

**Utgåva av uppdateringsström försvinner om problem väntar på godkännande**

*Uppdateringar*

När en användare klickar på [!UICONTROL New update] i uppdateringsströmmen för ett problem som väntar på godkännande, försvinner hela uppdateringsströmmen.

**Fel vid överföring av ny version av ett dokument**

*Dokument*

När en användare försöker överföra en ny version av ett dokument överförs inte den nya versionen och användaren ser något av följande fel:

* [!UICONTROL documentID cannot be null]
* [!UICONTROL Error: Invalid Parameter: documentID value "undefined"]

**Offentlig länk för dokument leder till en tom sida**

*Dokument*

När en användare försöker öppna ett dokument med hjälp av en offentlig länk leder länken till en tom sida. Detta inträffar när länken öppnas i ett fönster där en [!DNL Workfront] sessionen är öppen.

**Listkontroller fungerar inte med rapporter på kontrollpaneler**

*Kontrollpaneler*

När en användare visar en rapport på en kontrollpanel och försöker ändra filtret, grupperingen eller vyn för rapporten ändras inte filtret, grupperingen eller vyn.

**&quot;[!UICONTROL You must be a system admin]&quot; fel när ett projekt skapas**

*Projekt*

När en användare som inte är administratör försöker skapa ett projekt och bifogar ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, kan de inte skapa projektet och de ser följande fel:

&quot;[!UICONTROL You must be a system admin to change this custom data parameter value]&quot;

**Anpassade data bevaras inte vid konvertering av problem till projekt**

*Projekt*

När en användare konverterar ett ärende till ett projekt med hjälp av en mall överförs inte data från ett anpassat formulär i frågan till det jämförbara anpassade formuläret i projektet. Det här händer med data i anpassade fält som kan döljas baserat på värdena i andra anpassade fält.

**Fel vid konvertering av problem till projekt**

*Projekt*

När en användare försöker konvertera ett problem till ett projekt konverteras inte problemet och följande fel visas:

&quot;[!UICONTROL An unexpected error occurred]&quot;

+++


## Uppdateringar i januari 2022

+++**Underhållsuppdatering 27 januari 2022**

**Anpassade data bevaras inte vid konvertering av problem till projekt**

*Projekt*

När en användare konverterar ett ärende till ett projekt med hjälp av en mall överförs inte data från ett anpassat formulär i frågan till det jämförbara anpassade formuläret i projektet. Det här händer med data i anpassade fält som kan döljas baserat på värdena i andra anpassade fält.

**Användarlistan på journalkortet är inte i alfabetisk ordning**

*Agile*

När en användare tittar på användarlistan på en anslagstavla visas användarna inte i alfabetisk ordning. I stället visas de användare som har flest uppdrag först.

**Uppdaterade länkar för att kopiera och flytta problem**

*Problem*

I förhandsvisningsmiljön har länkarna för kopiering och flyttning uppdaterats till[!UICONTROL Copy to]&quot; och &quot;[!UICONTROL Move to]&quot; både på utgivningssidan och i en utgivningslista.

**Lägg till upp till 45 IP-adresser till dina [!DNL Workfront] tillåtelselista**

*Inställningar*

Gränsen för IP-adresser som läggs till i dina [!DNL Workfront] tillåtelselista har ökat från 30 till 45.

+++

+++**Underhållsuppdatering 20 januari 2022**

**&quot;[!UICONTROL Invalid Parameter]&quot; fel när projekt skapas från mall**

*Projekt*

När en användare försöker skapa ett projekt från en mall och tar bort ett anpassat formulär från mallen när projektet skapas, skapas inte projektet och användaren ser ett &quot;[!UICONTROL Invalid Parameter]&quot; felmeddelande som anger ett obligatoriskt fält i det borttagna anpassade formuläret.

**Användarlistan läses inte in i [!DNL Safari] webbläsare**

*Användare*

När en användare går till [!UICONTROL Users] visas rubriken, men listan över användare läses inte in.

**Sena taggar när du drar uppgifter i en lista leder till att aktiviteten flyttas till fel plats**

*Listor*

När en användare försöker flytta en uppgift i en lista genom att dra den, flyttas den blå raden som anger var uppgiften ska flyttas mycket långsammare än markören. När användaren släpper uppgiften flyttas den till den plats där den blå linjen finns, även om markören pekar på en annan plats i listan.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 14 januari 2022**

**Vissa mappade fält återställs när du väljer[!UICONTROL new field to map]**

*[!DNL Workfront Fusion]*

När minst ett fält finns i [!DNL Workfront] [!UICONTROL Create] eller [!UICONTROL Update] har mappning aktiverat och en användare väljer ett nytt fält att mappa. De tidigare mappade fälten som är mappningsaktiverade förlorar mappningsvärden.

+++

+++**Underhållsuppdatering 13 januari 2022**

**Det går inte att lägga till en hyperlänk till en kommentar i sammanfattningspanelen**

*Uppgifter*

När en användare gör en kommentar på sammanfattningspanelen för en uppgift och försöker lägga till en hyperlänk till kommentaren, öppnas hyperlänksfönstret, men så fort användaren klickar i fönstret stängs det och användaren inte kan lägga till en hyperlänk. Om användaren tabbar in i fönstret kan han/hon skriva eller klistra in en länk i fältet, men hyperlänken sparas inte. I båda fallen avmarkeras uppgiften.

**Redigera teamsida stängs inte**

*Team*

När en användare försöker redigera ett team [!DNL Edit team] sidan stängs inte. Användaren kan inte stänga sidan genom att klicka på någon av knapparna, klicka på X:et eller navigera bort från sidan.

**E-post och meddelanden i programmet skickas inte**

*Meddelanden*

När en händelse som ska utlösa ett meddelande inträffar, skickas inte meddelandet. Detta kan inträffa för e-post eller meddelanden i appen och kan inträffa även om andra meddelanden skickas.

**[!UICONTROL My Work]listan är tom**

*[!UICONTROL My Work]*

När en användare visar sina [!UICONTROL My Work] lista och layoutmall för [!UICONTROL My Work] listan innehåller ett numeriskt värde som [!UICONTROL Percent Complete], [!UICONTROL My Work] listan visas inte.

**[!UICONTROL Percent Complete]och [!UICONTROL Hours Complete] kan inte ändras på Agile Board**

*Agile*

När en användare väljer&quot;[!UICONTROL Show more work items]&quot; på Agile Board, försöker sedan ändra [!UICONTROL Percent Complete] eller [!UICONTROL Hours Complete] på ett av de nya arbetsobjekten kan de inte ändra Procent färdigt eller Timmar färdigt. The [!UICONTROL Percent Complete] knappen är också grå, vilket anger att den är inaktiv.

+++

+++**Underhållsuppdatering 6 januari 2022**

**&quot;[!UICONTROL Invalid Parameter]&quot; fel vid koppling av mallar eller anpassade formulär till projekt**

*Projekt*

När en användare försöker bifoga ett eget formulär eller en mall till ett befintligt projekt, fyller i de obligatoriska fälten i det anpassade formuläret eller mallen och sparar ändringarna i projektet, sparas inte ändringarna och användaren ser ett &quot;[!UICONTROL Invalid Parameter]&quot; fel högst upp på sidan med projektinformation.

**Korrekturkommentarer visas inte i dokumentuppdateringar**

*Korrektur*

När en användare visar ett korrektur i [!UICONTROL Documents] visas inte kommentarer som gjorts på själva korrekturet i [!UICONTROL updates] dokumentets område.

**[!UICONTROL Workload Balancer]: &quot;[!UICONTROL ?[object Object]?]&quot; visas i överallokeringsinformation**

*[!UICONTROL Workload Balancer]*

Om en användare visas som överallokerad i [!UICONTROL Workload Balancer] därför att en uppgift överlappar användarens tid och en annan användare ser sin överbeläggning,[!UICONTROL Capacity]&quot; området för överallokeringsinformationen visar &quot;[!UICONTROL ?[object Object]?]&quot; istället för användarens faktiska kapacitet.

+++

## Tidigare underhållsuppdateringar

Information om tidigare underhållsuppdateringar finns här:

* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2021](2021-updates.md)
