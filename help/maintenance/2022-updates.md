---
title: Workfront Maintenance Updates in 2022
description: Underhållsuppdateringar för 2022 för  [!DNL Adobe Workfront]
exl-id: 78ea4e31-143f-4a70-bb9a-060b5a8e097e
feature: Get Started with Workfront
source-git-commit: 8dc177a194ae32bcb135910badc7fdb2c42e530d
workflow-type: tm+mt
source-wordcount: '15336'
ht-degree: 0%

---

# [!DNL Workfront] underhållsuppdateringar 2022

Följande underhållsuppdateringar gjordes 2022.

>[!NOTE]
>
>Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Support meddelar dig när ett problem som du har skickat har åtgärdats.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Underhållsuppdateringar före 2022 finns i [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

## Uppdateringar i december 2022

+++**Underhållsuppdatering 15 december 2022**

**Hjälpmedelsuppdateringar i listor**

*Listor*

Följande tillgänglighetsfunktioner finns nu i listor:

* Kryssrutor i listor har nu en synlig fokusindikator när du tabbar till dem. Detta gör det enklare att visuellt följa tangentbordsnavigering för objekt i en lista.
* Alla knappar i verktygsfälten för listor har nu enhetliga hovring- och fokuslägen, med en grå bakgrund som visas vid hovring och en grå bakgrund och blå kontur som visas vid fokus.
* Tidigare, när en nedrullningsbar meny öppnades i en lista med blankstegstangenten, skulle menyn öppnas och sidan rullas ned en bit, vilket inte var tänkt. Nu rullar sidan inte längre när du trycker på Blanksteg i en listruta, vilket är det korrekta avsedda beteendet.
* När du visar en lista där kryssrutan för rader är markerad kan du nu bläddra igenom varje redigerbart objekt med tabbtangenten och sedan trycka på blankstegstangenten för att växla till redigeringsläget och börja redigera cellen i raden. Tidigare gick det inte att navigera med tangentbordet och dessa objekt krävde att en mus användes. Nu kan du växla till redigeringsläget med både mus och tangentbord.

**[!UICONTROL Whoops]-fel när ett projekt skapas från en mall**

*Projekt*

När en användare försöker skapa ett projekt från en mall skapas inte projektet och användaren ser följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Kombinationsdiagram visar samma data två gånger**

*Rapporter*

När en användare visar ett kombinationsdiagram visas en värdeuppsättning två gånger i stället för att två värdeuppsättningar jämförs. Rätt värdeuppsättningar finns i rapportinformationen.

**Verktygstips har lagts till för nedtonade timceller i tidrapporter**

*Tidrapporter*

Vi har lagt till verktygstips som förklarar varför en timcell kan vara nedtonad i en tidrapport. En del orsaker kan till exempel vara att tidrapporten är stängd eller att projektet är slutfört.

**Inaktiverade användare är tillgängliga vid val av tidrapportgodkännare**

*Tidrapporter*

När en användare skapar en tidrapport och försöker tilldela en godkännare, innehåller listrutan inaktiverade användare. Om en inaktiverad användare väljs sparas inte tidrapporten och användaren ser följande meddelande:

[!UICONTROL Error. Sorry! Only users with Plan license can approve or reject timesheets. Please contact your system administrator.]

Eftersom den inaktiverade användaren inte kan tilldelas måste användaren välja en aktiverad användare. Tidrapporten fungerar därför som förväntat, men de inaktiverade användarna i listan kan orsaka förvirring eller besvär för användaren.

**Det går inte att ange tid i tidrapporten**

*Tidrapporter*

När en användare försöker lägga till tid i en tidrapport ser han eller hon att timrutorna i valfri projekttid eller aktivitetstidsrader är nedtonade och att de inte kan ange tid i dessa rutor. De kan bara ange tid i området Allmän tid.

+++

+++**Underhållsuppdatering 8 december 2022**

**Smart val av användare när godkännare läggs till i en godkännandesökväg**

*Godkännanden*

Vi har förbättrat sättet som användare visas på när du lägger till dem i fältet [!UICONTROL Approvers] för ett nytt godkännande.

När du nu lägger till en användare i fältet [!UICONTROL Approvers] för ett godkännande på systemnivå eller för engångsbruk visas även användarens primära roll och e-postadress, förutom namn och avatar. Detta gör det lättare att skilja mellan flera användare med liknande eller identiska namn.

**Projektstatus följer inte gruppprojektinställningarna**

*Projekt*

När en användare skapar ett projekt från en mall får det nya projektet inte den status som angetts i gruppprojektinställningarna. Om ett projekt skapas utan en mall visas gruppprojektinställningarna som förväntat.

**Det går inte att lägga till underaktivitet**

*Uppgifter*

När en användare försöker lägga till en underaktivitet med knappen [!UICONTROL +New] visas inga alternativ i fönstret [!UICONTROL New Task] och användaren ser följande meddelande:

[!UICONTROL Cannot read properties of undefined (reading 'validations)]

**Fel vid stängning eller sparande av tidrapporter**

*Tidrapporter*

När en användare försöker lägga till eller stänga en tidrapport, sparas inte tidrapporten och användaren ser följande fel:

* Databasfel på grund av ogiltig SQL-sats.
* Dina senaste ändringar sparades inte. Uppdatera sidan för att visa de senast sparade ändringarna.

+++

+++**Underhållsuppdatering (snabbkorrigering) 1 december 2022**

**Inline-redigeringsfel per användare orsakar inga felmeddelanden**

*Listor*

När en användare infogar redigering av ett objekt och gör ett fel som ska skapa ett felmeddelande, visas inget felmeddelande. Själva felet sparas inte i Workfront, vilket betyder att data inte påverkas, men det beror på att ett felmeddelande saknas.

Detta har rapporterats i följande situationer:

* Föregående: En föregående slinga skapas, till exempel att en uppgift tilldelas sig själv
* Datum: Ett omöjligt datum har angetts, t.ex. ett slutförandedatum som är före startdatumet eller som ligger efter projektets slutförandedatum

Alternativet **&quot;Flytta till&quot; är inte tillgängligt i problemrapporter**

*Rapporter*

När en användare visar en problemrapport och försöker flytta ett problem är alternativet &quot;Flytta till&quot; inte tillgängligt på menyn Mer (tre punkter).


**Det går inte att stänga användarkortet i uppdateringsdataströmmen**

*Uppdateringar*

När en användare visar uppdateringar och håller pekaren över ett namn visas ett kort med information om användaren vars namn det är öppet och stängs inte automatiskt. Sidan svarar inte förrän kortet stängs manuellt genom att klicka på X:et i det övre högra hörnet.


+++

+++**Underhållsuppdatering 1 december 2022**

**Aktiviteten har en kanban-eftersläpningsordning på 0**

*Agile*

När en användare visar ett kanban-teams eftersläpning visas en eftersläpningsordning på 0 för en eller flera av uppgifterna.

**[!UICONTROL Invalid custom expression]-meddelande vid referens till [!UICONTROL owner] i ett beräknat fält**

*Anpassade formulär*

När en användare lägger till ett beräknat fält i ett anpassat formulär på problemnivå och försöker lägga till en referens till ett [!UICONTROL owner] (till exempel `ownerID`), sparas inte fältet och användaren ser följande meddelande:

[!UICONTROL This is an invalid customer expression, please try again.]

Detta inträffar även när uttrycket är giltigt.

**Kan inte komma åt element i [!DNL Workfront for Jira] integration**

*Integrationer*

Följande element kan för närvarande inte nås i [!DNL Workfront for Jira]-integreringen för [!DNL Jira Cloud]:

* Sidan [!UICONTROL Configuration]
* Knappen [!UICONTROL Open Workfront] i ett [!DNL Jira]-problem

**Problem med att lägga till anpassade meddelanden i visningsprogrammet**

*Korrektur*

När en användare delar ett korrektur och försöker lägga till ett eget meddelande händer följande:

* Visningsprogrammet för korrektur zoomas in i korrekturet.
* Områdena i den vänstra navigeringen svarar inte längre.

**Inaktiverade användare är tillgängliga vid val av tidrapportgodkännare**

*Tidrapporter*

När en användare skapar en tidrapport och försöker tilldela en godkännare, innehåller listrutan inaktiverade användare. Om en inaktiverad användare väljs sparas inte tidrapporten och användaren ser följande meddelande:

[!UICONTROL Error. Sorry! Only users with Plan license can approve or reject timesheets. Please contact your system administrator.]

Eftersom den inaktiverade användaren inte kan tilldelas måste användaren välja en aktiverad användare. Tidrapporten fungerar därför som förväntat, men de inaktiverade användarna i listan kan orsaka förvirring eller besvär för användaren.

**Tidrapporten har inte genererats**

*Tidrapporter*

Tidrapporter genereras inte trots inställningarna för tidrapportprofilen. Eftersom tidrapporten aldrig genereras är den inte tillgänglig för användaren att ange tid, och den visas inte i listor.

+++

## Uppdateringar i november 2022

+++**Underhållsuppdatering 17 november 2022**

**Dokument som placeras i [!UICONTROL Recycle Bin] om de inte är markerade när du flyttar en uppgift eller ett problem**

*Dokument*

När du nu avmarkerar alternativet [!UICONTROL Documents] när du flyttar en uppgift eller ett problem, placeras dokumenten som är kopplade till uppgiften eller problemet i [!UICONTROL Recycle Bin] i 30 dagar. En administratör kan återställa dem vid behov. Användaren som avmarkerar Dokument i den rörliga processen får en varning om detta i rutan [!UICONTROL Move Task] eller [!UICONTROL Move Issue]. Före den här förbättringen togs dokumenten bort permanent.

**Om du döljer ett objekt döljs det felaktiga objektet**

*Layoutmallar*

När en användare ändrar om ett objekt är dolt eller visas, återspeglas ändringarna i ett annat objekt i layoutmallen.


+++

+++**Underhållsuppdatering 10 november 2022**

**Gruppredigeringsuppgifter ändrar aktivitetstilldelningar**

*Uppgifter*

När en användare gruppvis redigerar ett fält för en uppsättning uppgifter, tillämpas den första uppgiftens tilldelningar på alla uppgifter. Detta tar bort tidigare tilldelningar.

**Kan inte öppna ett interaktivt korrektur**

*Workfront Proof*

När en användare försöker öppna ett interaktivt korrektur öppnas inte korrekturet och användaren ser följande meddelande:

[!UICONTROL Proof not loaded (501) Try again]

+++

+++**Underhållsuppdatering (snabbkorrigering) 4 november 2022**

**Problem med uppgifter som lagts till i en iteration**

*Agile*

Följande problem har rapporterats om problem som har lagts till i en iteration:

* Vissa underaktiviteter för en aktivitet som har lagts till i en iteration visas inte på sidan [!UICONTROL Iteration].
* När en användare försöker lägga till en saknad uppgift i iterationen läggs uppgiften inte till och användaren ser följande meddelande:

  [!UICONTROL The following error occurred: None of the selected items could be moved, because they are not assigned to an agile team or are not agile items]

**Uppgifter som tilldelats via gruppredigering visas inte i teamets eftersläpning**

*Agile*

När en användare tilldelar uppgifter till ett Scrum-team genom att använda gruppredigering visas inte dessa uppgifter i gruppens eftersläpning.

Kanban-teamen påverkas inte av det här problemet.

Textrutan **[!UICONTROL New proof recipients] är för liten**

*Korrektur*

När en användare visar ett korrektur och försöker dela korrekturet från fliken [!UICONTROL Sharing] är textrutan [!UICONTROL New proof reciepients] mycket liten. Användaren kan skriva ett namn, men eftersom rutan är så liten radbryts texten på ett sätt som är svårt att läsa.

**Rapportanvändningsinformationen uppdateras inte**

*Rapporter*

När en användare visar en rapport uppdateras inte den senast visade informationen, t.ex. Senast visade den och Senast visade av. Detta innebär att all användarinformation kan vara felaktig.

Detta beteende har rapporterats när användaren öppnar rapporten på följande sätt:

* Sök
* Stift
* Favoriter
* Senaste

När du öppnar rapporter via en kontrollpanel uppdateras den senast visade informationen.

**[!DNL Workfront]: 500 fel vid ändringar i ett [!DNL Workfront] object**+

*[!DNL Workfront]*

När en användare försöker göra ändringar i ett [!DNL Workfront]-objekt sparas inte ändringarna och användaren ser följande fel:

[!UICONTROL 500: Database error due to invalid SQL statement.]

Detta har rapporterats i följande situationer:

* Ändra ett objekts status
* Beräknar om tidslinjer
* Bifoga en mall
* Loggningstid

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 3 november 2022**

**Fel gällande [!UICONTROL apiKey] i [!DNL Workfront] > [!UICONTROL Watch Events] module**

*[!DNL Workfront Fusion]*

När en användare försöker lägga till en webkrok i modulen [!DNL Workfront] > [!UICONTROL Watch Events] får de följande fel:

[!UICONTROL The apiKey provided was empty or deemed invalid.]

+++

+++**Underhållsuppdatering 3 november 2022**

**Byt namn på avsnitten &quot;Schema&quot; och &quot;Schemaläggning&quot; för team och projekt i layoutmallen**

*Layoutmallar*

Flikarna Schema och Schemaläggning som är tillgängliga för att läggas till i en layoutmall på den vänstra panelen i ett team eller projekt har bytt namn till Arbetsbelastningsutjämning.

**Fel vid åtkomst av e-postaviseringsinställningar**

*Meddelanden*

>[!NOTE]
>
>Problemet förekommer både i produktions- och förhandsvisningsmiljön.

När en användare försöker ändra inställningarna för e-postmeddelanden kan ett av följande fel uppstå:

* [!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

* [!UICONTROL Failed to fetch email notification]

Detta har rapporterats i följande områden:

* [!UICONTROL Setup] > [!UICONTROL Email notifications]
* [!UICONTROL User] > [!UICONTROL Edit user]
* [!UICONTROL Groups]

**Nya informationsikoner för tidrapporter, tidrapportprofiler och tidrapportinställningar**

*Workfront*

>[!NOTE]
>
>Den här uppdateringen har endast släppts till förhandsvisningsmiljön. Den kommer att lanseras i Production med version 23.1.

Vi har lagt till flera informationsikoner i följande inställningar:

* Kryssrutan&quot;Kan redigera tid&quot; när du skapar eller redigerar en tidrapportprofil eller en tidrapportprofil för att ange att godkännare när den är aktiverad även kan skicka, öppna eller redigera tidrapporten, såvida inte administratören begränsar dessa åtgärder under Inställningar för tidrapport i dialogrutan Inställningar.
* &quot;Begränsa redigering av tidrapporter till ägare och administratörer&quot; i delen Inställningar för tidrapport och timmar i installationsprogrammet för att ange att följande användare även kan redigera tidrapporterna när de är inaktiverade: användare med administrativ åtkomst till tidrapporter och timmars-, tidrapportgodkännare som kan redigera tid och tidrapportägarnas chefer.

Observera att funktionaliteten för de här inställningarna inte har ändrats och att bara informationsikonerna har lagts till för att göra inställningarna tydligare.

+++

## Uppdateringar i oktober 2022

+++**Underhållsuppdatering 27 oktober 2022**

Funktionen **[!UICONTROL HOUR]i beräknade fält använder UTC**

*Anpassade formulär*

När ett beräkningsfält innehåller funktionen [!UICONTROL HOUR] returnerar funktionen värden som baseras på UTC i stället för den förväntade tidszonen. Alla beräkningar som baseras på HOUR-värdet är därför felaktiga.

**[!UICONTROL Quick filter]returnerar inga resultat vid sökning efter team**

*Listor*

När en användare försöker använda [!UICONTROL Quick filter] i en lista för att söka efter ett team returnerar namnet på teamet inga resultat, även när teamet är synligt i listan (till exempel i fältet [!UICONTROL Assigned to]). Om du söker efter ordet [!UICONTROL team] returneras inte heller några resultat.

**Det går inte att fästa en sida igen efter att nålen har tagits bort**

*Navigering*

>[!NOTE]
>
>Problemet löstes i Preview den 13 oktober 2022. Den fastställdes i produktion den 27 oktober 2022.

När en användare väljer alternativet [!UICONTROL Remove pin] på ett häftstift, får ett meddelande om borttagningen och försöker ersätta häftstiftet genom att klicka på [!UICONTROL Undo] i meddelandet, ersätts inte stiftet i den övre navigeringen och läggs inte heller till i listan med punkter i listan [!UICONTROL More pins] (menyn med tre punkter i området [!UICONTROL Pins]).

Om en användare försöker fästa sidan igen genom att gå till sidan och fästa den, skapas inte stiftet och användaren kan inte fästa sidan.

**Alla användare listade i [!UICONTROL Workload Balancer] när en delbar länk används i [!DNL Safari] webbläsare**

*[!UICONTROL Workload Balancer]*

När en användare följer en delbar länk till [!UICONTROL Workload Balancer] när han/hon använder en [!DNL Safari]-webbläsare visas alla användare i stället för bara medlemmarna i teamet som visas.

+++

+++**Underhållsuppdatering 20 oktober 2022**

**Fel vid grupptilldelning av ett team**

*Uppdrag*

När en användare gör en gruppredigering av uppgifter eller problem och tilldelar ett team efter att ha tilldelat en individ, sparas inte uppdragen och användaren ser följande fel:

[!UICONTROL Let's try that again - The following error occurred: teamAssignments must be either a list of objects or a list of IDs]

**[!UICONTROL Failed to upload file] fel**

*Dokument*

När en användare försöker överföra en fil till området [!UICONTROL Documents] överförs inte filen och användaren ser felet [!UICONTROL Failed to upload file].

Detta har rapporterats vid försök att överföra MP4-filer.

**Antalet fel i den vänstra navigeringen av aktiviteten är felaktigt**

*Problem*

När en användare visar en uppgift är det nummer som visas i [!UICONTROL Issues]-avsnittet i den vänstra navigeringen inte korrekt det faktiska antalet problem som är kopplade till uppgiften.


Ikonen **[!UICONTROL Predecessor]saknas i aktivitetshuvudet**

*Uppgifter*

När en användare visar en uppgift saknas ikonen för föregående aktivitet i sidhuvudet.

+++

+++**Underhållsuppdatering 13 oktober 2022**

**Det går inte att fästa en sida igen efter att nålen har tagits bort**

*Navigering*

>[!NOTE]
>
>Problemet kommer att åtgärdas i förhandsversionen den 13 oktober 2022. Den kommer att fastställas i produktion den 27 oktober 2022.

När en användare väljer alternativet [!UICONTROL Remove pin] på ett häftstift, får ett meddelande om borttagningen och försöker ersätta häftstiftet genom att klicka på [!UICONTROL Undo] i meddelandet, ersätts inte stiftet i den övre navigeringen och läggs inte heller till i listan med punkter i listan [!UICONTROL More pins] (menyn med tre punkter i området [!UICONTROL Pins]).

Om en användare försöker fästa sidan igen genom att gå till sidan och fästa den, skapas inte stiftet och användaren kan inte fästa sidan.

**Det går inte att namnge eller spara nyskapade filter**

*[!UICONTROL Resource Planner]*

När en användare försöker namnge ett nytt filter i [!UICONTROL Resource Planner] är namnrutan tom. Om användaren dessutom har tryckt ned blankstegstangenten inaktiveras knappen [!UICONTROL Save].

**Det går inte att redigera namn eller procent färdigt för en aktivitet eller ett problem**

*Uppgifter och problem*

Användare med [!UICONTROL Contribute] åtkomst till en aktivitet eller ett problem kan inte redigera namnet på aktiviteten eller problemet i huvudet. Dessutom kan användare med [!UICONTROL Contribute]-åtkomst inte redigera procentandelen färdigt för en aktivitet eller ett problem.

**Begärande och granskare räknas in i en organisations licensantal**

*[!DNL Workfront Proof]*

När en användare läggs till i ett korrektur som en granskare eller en begärande får de behörigheten [!UICONTROL Visitor], som inte bör använda en [!DNL Workfront Proof]-licens. När användaren läggs till ökar antalet använda [!DNL Workfront Proof] licenser.

+++

+++**Underhållsuppdatering 11 oktober 2022**

**Det går inte att fästa en sida igen efter att nålen har tagits bort**

*Navigering*

>[!NOTE]
>
>Problemet löstes i Preview den 13 oktober 2022. Den kommer att fastställas i produktion den 27 oktober 2022.

När en användare väljer alternativet [!UICONTROL Remove pin] på ett häftstift, får ett meddelande om borttagningen och försöker ersätta häftstiftet genom att klicka på [!UICONTROL Undo] i meddelandet, ersätts inte stiftet i den övre navigeringen och läggs inte heller till i listan med punkter i listan [!UICONTROL More pins] (menyn med tre punkter i området [!UICONTROL Pins]).

Om en användare försöker fästa sidan igen genom att gå till sidan och fästa den, skapas inte stiftet och användaren kan inte fästa sidan.

+++

+++**Underhållsuppdatering 6 oktober 2022**

**Ny ritningstyp**

*Foton*

Ritningstypen Dashboard har lagts till i katalogen med ritningar. Tidigare var endast projektmallar och organisationsstrukturplaner tillgängliga.

**Element som överlappar i den vänstra panelen**

*Anpassade formulär*

När en användare arbetar i formulärbyggaren och formuläret har fler än 100 fält överlappar meddelandet som meddelar användaren om fältgränsen elementen i den vänstra panelen.

**Datumväljaren öppnas inte längre automatiskt vid indatafokus eller klicka på**

*Navigering*

När en användare navigerar med tangentbordet öppnas datumväljare inte längre automatiskt vid det datum som tangentbordsfokus skickas till. Tangentbordsanvändare ska i stället gå till datumväljarikonen med tabbtangenten och trycka på Retur för att öppna datumväljaren. När en användare navigerar med musen öppnas datumväljarna inte längre automatiskt vid det datum användaren klickar på. I stället ska musanvändarna klicka på datumväljarikonen för att öppna datumväljaren.

Den här ändringen gjordes för att bättre överensstämma med gränssnittsmönster för datumväljare och för att skapa en mer tillgänglig upplevelse för användare som använder tangentbord och skärmläsare.

**Om du tilldelar flera team tilldelas bara ett team**

*Team*

>[!NOTE]
>
>Problemet finns bara i förhandsvisningsmiljön.

När en användare tilldelar flera team till en uppgift eller ett problem visas bara ett team i uppdragslistan. Detta påverkar även rapporteringen. Rapporter som visar grupptilldelningar är felaktiga eftersom bara ett team visas som tilldelat uppgiften eller utgåvan.

**[!UICONTROL Your recent changes were not saved]-fel vid autosparande av ändringar i en tidrapport**

*Tidrapporter*

När en användare försöker redigera en tidrapport på ett sätt som skulle utlösa en autosparfunktion, sparas inte ändringarna och användaren ser följande meddelande:

[!UICONTROL Your recent changes were not saved. Refresh the page to view.]

Detta har rapporterats vid redigering av följande:

* Timmar
* Uppgifter

**E-postmeddelanden är fördröjda**

*Workfront Proof*

När en händelse inträffar i [!DNL Workfront Proof] som utlöser ett e-postmeddelande får användaren inte meddelandet omedelbart. Meddelandet kan fördröjas med flera timmar.

+++

+++**Underhållsuppdatering 3 oktober 2022**

**Spara din tidrapport manuellt när tidigare jobbroller har ändrats**

*Tidrapporter*

Om en jobbroll som du har loggat tid för har ändrats och inställningen [!UICONTROL Assign job roles to hour entries manually] har inaktiverats, måste du spara dina tidsposter manuellt tills timmar inte längre loggas för den jobbroll som har ändrats.

+++

## Uppdateringar i september 2022

+++**Underhållsuppdatering 29 september 2022**

**Användaren återgår inte till föregående sida när korrektur stängs**

*Korrektur*

När en användare som visar ett korrektur inom [!DNL Workfront] stänger korrekturet returnerar de inte den sida de var på innan de öppnade korrekturet. De dirigeras i stället om till en annan sida i [!DNL Workfront].

**Kan inte öppna korrektur i[!DNL Workfront]**

*Korrektur*

När en användare visar ett dokument i [!DNL Workfront] och försöker öppna korrekturet öppnas inte korrekturet och användaren återgår till sidan [!UICONTROL Document Details].

**Timmar sparas inte när [!UICONTROL Tab] key** används

*Tidrapporter*

När en användare fyller i en tidrapport och navigerar mellan celler med tangenten [!UICONTROL Tab] sparas inte timarna. Meddelandet [!UICONTROL Auto-save] visas inte längst ned på skärmen och om användaren uppdaterar sidan kan användaren se att timmarna inte sparats.

**Tomma sidor vid visning av ett korrektur med flera sidor**

*[!DNL Workfront Proof]*

När en användare visar ett korrektur med flera sidor kan användaren se sidminiatyrer, men sidorna öppnas inte i huvudvisningsprogrammet.



+++

+++**Underhållsuppdatering 22 september 2022**

**Det går inte att stänga användarkortet i uppdateringsdataströmmen**

*Uppdateringar*

När en användare visar uppdateringar och håller pekaren över ett namn visas ett kort med information om användaren vars namn det är öppet och stängs inte automatiskt. Sidan svarar inte förrän kortet stängs manuellt genom att klicka på X:et i det övre högra hörnet.

+++

+++**Underhållsuppdatering 15 september 2022**

Fel **[!UICONTROL Someone else tried to save this project] vid inmatning av timmar**

*Tidrapporter*

När en användare försöker logga timmar för en uppgift på sin tidrapport sparas inte timmarna automatiskt och användaren ser följande fel:

[!UICONTROL We're sorry, but your save failed because someone else tried to save this project at the same time. Please try to save again.]

**Det går inte att stänga användarkortet i uppdateringsdataströmmen**

*Uppdateringar*

När en användare visar uppdateringar och håller pekaren över ett namn visas ett kort med information om användaren vars namn det är öppet och stängs inte automatiskt. Sidan svarar inte förrän kortet stängs manuellt genom att klicka på X:et i det övre högra hörnet.

**Fältet [!UICONTROL Task role assignment] har bytt namn till [!UICONTROL Role assignment] när du tilldelar arbete i grupp med[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

För att återspegla den nya funktionaliteten att kunna tilldela både uppgifter och problem i grupp från området [!UICONTROL Unassigned Work] har vi ändrat namnet på fältet [!UICONTROL Task role assignment] till [!UICONTROL Role assignment] i [!UICONTROL Workload Balancer]. Fältet refererar till jobbroller som har tilldelats antingen uppgifter eller ärenden och det visas när användare tilldelas till objekt i rutan [!UICONTROL Bulk Assignments].

+++

+++**[!DNL Workfront Scenario Planner]Underhållsuppdatering 15 september 2022**

**Filter som delas med en grupp visas nu i listan [!UICONTROL Import Projects] för medlemmar i alla undergrupper i [!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

När du nu delar ett projektfilter med en grupp som har ytterligare undergrupper visas filtret för alla grupp- och undergruppsmedlemmar som visar projekt i rutan [!UICONTROL Import Projects] för en plan i [!DNL Scenario Planner].

+++

+++**Underhållsuppdatering 8 september 2022**

**Uppdaterade namn har återställts för användar- och rolltilldelningsfälten**

*Uppdrag*

Uppdragsfälten som tillfälligt byttes namn förra veckan har återställts till sina ursprungliga namn:

* [!UICONTROL Assignment Users]
* [!UICONTROL Assignment Roles]

**Fel vid borttagning av projektägaren från huvudet**

*Projekt*

När en användare försöker ta bort en [!UICONTROL Project Owner] från huvudet i ett projekt tas [!UICONTROL Project Owner] inte bort och användaren ser följande felmeddelande:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Rutan med ändrad storlek [!UICONTROL Description] återgår till den ursprungliga storleken**

*Projekt, uppgifter och problem*

När en användare ändrar storlek på rutan [!UICONTROL Description] i informationsområdet för ett arbetsobjekt så att det blir större och sedan börjar skriva i rutan, återgår rutan till sin ursprungliga storlek. Användaren kan fortfarande skriva i rutan och innehållet sparas som förväntat

**Avsluta av misstag när uppgifter eller problem skapas**

*Uppgifter och problem*

När en användare skapar en uppgift eller ett problem i ett projekt och klickar utanför popup-fönstret för att skapa, stängs popup-fönstret utan förvarning och all information som har angetts tidigare går förlorad.

**Möjligheten att skicka ett korrektur via e-post till en dropzone har tagits bort**

*[!DNL Workfront Proof]*

Från och med torsdagen den 8 september 2022 har vi tagit bort möjligheten att skicka ett bevis via e-post till en dropzon i den fristående [!DNL Workfront Proof]-produkten.

Du kan fortfarande använda dropzone på andra sätt för att skicka in nya korrektur och nya versioner av korrektur till ditt konto utan att behöva logga in på ditt konto. Mer information finns i [Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html).

+++

+++**Underhållsuppdatering 6 september 2022**

**Planerade datum har lagts till i listan med fält för anpassningsbara projektrubriker**

*Projekt*

Vi har lagt till [!UICONTROL Projected Start Date] och [!UICONTROL Projected Completion Date] i listan med fält för anpassningsbara projektrubriker när en layoutmall används.

**Ny gräns med ett bekräftelsemeddelande som visar antalet objekt som lagts till i en tidrapport**

*Tidrapporter*

När du väljer mer än 50 objekt att lägga till i en tidrapport får du nu ett bekräftelsemeddelande som visar antalet objekt som ska läggas till i tidrapporten och ger dig möjlighet att ändra kurs och inte lägga till alla objekt. Alla tillagda objekt fästs automatiskt på tidrapporten och måste tas bort manuellt från den aktuella och alla framtida tidrapporter.

+++

+++**Underhållsuppdatering 2 september 2022**

Lägg till fältet [!UICONTROL Integrations] i projektets anpassade rubrik

*Integrationer*

Du kan nu lägga till fältet [!UICONTROL Integrations] i den anpassade rubriken för ett projekt när du använder en layoutmall. När du har lagt till fältet visas en länk till ett externt objekt som är länkat till projektet som finns i [!DNL Salesforce] eller [!DNL Anaplan], beroende på din integrering.

>[!NOTE]
>
>Den här underhållsuppdateringen släpptes tidigare till förhandsvisningsmiljön den 25 augusti 2022 och är nu i produktion.

+++

+++**Underhållsuppdatering 1 september 2022**

**Slutförda objekt har tagits bort från delegeringen**

*Delegeringar*

Nu delegeras endast ofullständiga objekt vars datum matchar datumet för en delegering till andra användare när delegeringen av arbetsobjekt börjar. Om objekt slutfördes innan delegeringen startades, delegeras de inte. Objekt som slutförs under delegeringens tidsram kommer att finnas kvar i arbetslista i Hem-området för både den som delegerar och den som utses i två veckor innan de tas bort automatiskt, om delegeringen inte har avslutats under dessa veckor.

**Metadatauppdateringar för [!DNL Adobe Workfront] för [!DNL Experience Manager Assets] och [!DNL Assets Essentials] integreringar**

*Integrationer*

Metadata pushas automatiskt när du lägger till en resurs i en länkad mapp.

Tidigare skulle metadata bara skickas när du lade till en resurs med den nedrullningsbara menyn [!UICONTROL Add new].

**Det går inte att godkänna eller avvisa timmar i ett problem**

*Problem*

När en användare försöker godkänna eller avvisa timmar på fliken [!UICONTROL Hours] i ett problem saknas knapparna [!UICONTROL Approve] och [!UICONTROL Reject].

**Om du konverterar ett problem till ett projekt med en mall visas ett felaktigt felmeddelande**

*Problem*

När användaren konverterar ett problem till ett projekt med hjälp av en mall och ett fel påträffas visas en sida med meddelandet [!UICONTROL The Project no longer exists] i stället för rätt felmeddelande som förklarar orsaken till den misslyckade konverteringen.

**Det går inte att skapa korrektur för filer över 1,5 GB**

*[!DNL Workfront Proof]*

När du skapar ett nytt korrektur och en användare överför en fil som är större än 1,5 GB blir filnamnet rött och korrekturet kan inte skapas.

+++

## Uppdateringar i augusti 2022

+++**Underhållsuppdatering 25 augusti 2022**

**Länkar för belastningsutjämnare för arbete visas felaktigt i instrumentpaneler**

*Instrumentpaneler*

Delningsbara länkar i Utjämning av arbetsbelastning visas felaktigt när de läggs till i en instrumentpanel som en extern sida. I stället för att använda den unika vyn/de unika filtren som är kopplade till länken, använder kontrollpanelen den senast använda vyn/filtren för arbetsbelastningsutjämnaren.

**Lägg till fältet [!UICONTROL Integrations] i det anpassade projekthuvudet**

*Projekt*

Du kan nu lägga till fältet [!UICONTROL Integrations] i den anpassade rubriken för ett projekt när du använder en layoutmall. När du har lagt till fältet visas en länk till ett externt objekt som är länkat till projektet som finns i [!DNL Salesforce] eller [!DNL Anaplan], beroende på din integrering.

>[!NOTE]
>
>Den här underhållsuppdateringen finns för närvarande bara i förhandsvisningsmiljön. Den släpps till produktion en vecka efter förhandsversionen.

**Anpassade data bevaras inte när ett problem konverteras till ett tomt projekt**

*Projekt*

När en användare konverterar en utgåva till ett tomt projekt (utan mall) överförs inte data i beräknade fält till det nya projektet.

**&quot;Planeringsläge för tidslinje&quot;-fel vid ändring av ett datum i ett projekt**

*Projekt*

När en användare försöker ändra ett datum i ett projekt som har [!UICONTROL Plan Mode] inställt på [!UICONTROL Manual save] > [!UICONTROL Timeline Planning] ändras inte datumet och användaren ser ett fel.

[!UICONTROL Timeline Planning mode is available only when timelineDate is loaded. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Konsekvens när arbetsbelastningsutjämnaren öppnas i månadsvyn**

*Utjämnare för arbetsbelastning*

Nu visas användarens tilldelade objekt utökat när de visas i vyerna [!UICONTROL Day], [!UICONTROL Week] eller [!UICONTROL Month] i arbetsbelastningsutjämnaren. Före den här uppdateringen visades de tilldelade objekten som expanderade för vyerna [!UICONTROL Day] och [!UICONTROL Week] och komprimerade för vyn [!UICONTROL Month].


+++

+++**Underhållsuppdatering 18 augusti 2022**

Alternativen **[!UICONTROL Add to Iteration] och [!UICONTROL Add to Kanban Board] är inte tillgängliga vid redigering av infogade aktiviteter i en rapport**

*Rapporter*

När en användare visar en lista med uppgifter i en rapport och öppnar menyn [!UICONTROL More] (tre punkter) är alternativen [!UICONTROL Add to Iteration] och [!UICONTROL Add to Kanban Board] inte tillgängliga i listrutan. Om rapporten visas i en kontrollpanel är alternativen [!UICONTROL Add to Iteration] och [!UICONTROL Add to Kanban Board] tillgängliga i listrutan.

**Matrisrapporter visas felaktigt vid bläddring**

*Rapporter*

När en användare visar en matrisrapport och rullar kan vissa visuella element i rapporten överlappa eller dupliceras.

Vyn **[!UICONTROL Milestone]har tagits bort från listan över tidrapporter**

*Tidrapporter*

Vyn [!UICONTROL Milestone] har tagits bort från listan över tidrapportprojekt när ett projekt läggs till.

**Hyperlänkar i ett interaktivt korrektur är inte aktiva**

*[!DNL Workfront Proof]*

När en användare visar ett interaktivt korrektur och klickar på en länk eller knapp som innehåller en länk, kommer användaren inte till sidan som länken eller knappen länkar till.

**Nytt korrektursidfält saknar textfält**

*[!DNL Workfront Proof]*

På sidan [!DNL New Proof] visas inte många textfält (inklusive fältetiketter, listrutealternativ och kryssrutenamn).

**Användare får inga meddelanden när de taggas i ett korrektur**

*[!DNL Workfront Proof]*

När en användare är taggad i en korrekturkommentar får han/hon inget e-postmeddelande om kommentaren.

+++

+++**Underhållsuppdatering 12 augusti 2022**

**Nytt anpassbart rubrikfält har lagts till i början av rubriken**

*Sidhuvuden*

När du lägger till ett nytt fält i en anpassningsbar rubrik läggs fältet nu till som det första fältet till vänster i rubriken, eller omedelbart efter rutan [!UICONTROL Search] inuti layoutmallen. Före den här ändringen lades fältet till som det sista fältet i rubriken.

+++

+++**Underhållsuppdatering 11 augusti 2022**

**Det går inte att redigera anpassade formulär på grund av en felaktig teckengräns för beskrivande textfält**

*Anpassade formulär*

När en användare försöker redigera ett anpassat formulär och det anpassade formuläret har ett [!UICONTROL Descriptive text]-fält som för närvarande innehåller fler än 512 tecken, kan användaren inte spara ändringarna i det anpassade formuläret och ser följande fel:

&quot;Följande fält är ogiltiga: (Fält) är för långt, max 512&quot;

Detta påverkar [!UICONTROL Descriptive text] fält som tidigare har fungerat bra trots att de innehåller fler än 512 tecken.

**Data i dolda fält per avsnittsbrytning bevaras inte när du konverterar ett problem till ett projekt**

*Anpassade formulär*

När en användare konverterar ett problem till ett projekt och problemet innehåller ett anpassat formulär med data i en avsnittsbrytning som kan döljas med visningslogik, överförs inte data i det avsnittet till det nya projektet.

**Data i fält som döljs av avsnittsbrytningar bevaras inte när en begäran konverteras till ett projekt**

*Anpassade formulär*

När en användare konverterar en begäran till ett projekt, och begäran innehåller ett anpassat formulär med data i en avsnittsbrytning som kan döljas med visningslogik, överförs inte data i det avsnittet till det nya projektet.

**Det går inte att redigera anpassade formulär på grund av beskrivande textfält**

*Anpassade formulär*

När en användare försöker redigera ett anpassat formulär som innehåller ett beskrivande textfält fylls inte fältets etikett i. Användaren ser felet [!UICONTROL This field is required] i etikettfältet och användaren kan inte redigera det anpassade formuläret på grund av det här felet.

**Det går inte att ta bort instruktioner från ett anpassat fält i det anpassade formulärbyggaren**

*Anpassade formulär*

När en användare redigerar ett anpassat fält och försöker ta bort befintlig text i området [!UICONTROL Instructions], tas texten inte bort när fältet sparas. Användaren kan redigera text, men kan inte ta bort den helt.

**Teamtilldelning när begäran skapas visas inte på ny begäran**

*Begäranden*

När en användare skapar en begäran och tilldelar ett team till begäran och sedan skickar begäran, tilldelas teamet inte den begäran som skapas. Detta påverkar endast grupptilldelning. Användartilldelningar fungerar som förväntat.

+++

+++**Underhållsuppdatering 4 augusti 2022**

Dessa problem har bara åtgärdats i den nya [!DNL Workfront]-upplevelsen.

Alla [!DNL Workfront Classic]-funktioner togs bort 14 juli 2022.

**Fel vid ändring av planerat slutförandedatum i huvudet för en aktivitet eller ett problem**

*Uppgifter och problem*

När en användare försöker ändra [!UICONTROL Planned Completion Date] i huvudet för en aktivitet eller ett problem ändras inte datumet och användaren ser ett fel som liknar följande:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Uppdateringar i juli 2022

+++**Underhållsuppdatering 28 juli 2022**

Dessa problem har bara åtgärdats i den nya [!DNL Workfront]-upplevelsen.

Alla [!DNL Workfront Classic]-funktioner togs bort 14 juli 2022.

**Fel när ett objekt från[!UICONTROL Home Work List]** öppnades

*[!UICONTROL Home]*

När en användare försöker öppna ett objekt på sin [!UICONTROL Home Work List], öppnas inte objektet och användaren ser följande meddelande:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work try refreshing this browser page.]

**Uppgifter och ärenden som delegerats till en användare visas inte i användarens hemarbetslista**

*[!UICONTROL Home]*

När användaren visar sin [!UICONTROL Home Work List] visas inga uppgifter eller problem som delegerats till användaren i listan och användaren kanske inte känner till delegeringarna.

**Schemalagda rapporter skickas inte till alla mottagare**

*Rapporter*

När en schemalagd rapport skickas skickas den inte till alla användare i avsnittet [!UICONTROL Send to]. De utelämnade användarna är slumpmässiga och kan variera varje gång rapporten skickas.

**[!UICONTROL Cannot deselect tasks when attaching template]**

*Mallar*

När en användare bifogar och anpassar en mall ombeds de avmarkera uppgifter som de inte vill inkludera. Ingen av uppgifterna visas som markerad och användaren kan inte avmarkera dem.

Fälten **&quot;Språk&quot; har nu mer specifika etiketter**

*Terminologi*

Vi har uppdaterat deras etiketter för att göra funktionen för [!UICONTROL Locale]-fälten tydligare.

* Fältet [!UICONTROL Locale] i användarprofilen har nu namnet [!UICONTROL Email Locale]
* Fältet [!UICONTROL Locale] som finns i området [!UICONTROL Setup] >[!UICONTROL System] >[!UICONTROL Customer Info] har nu etiketten [!UICONTROL Default Email Locale]

Funktionen för dessa fält har inte ändrats.

**Problem när tidrapporter skapas**

*Tidrapporter*

Följande problem har rapporterats när tidrapporter skapades:

* När en användare försöker skapa en tidrapport för en roll skapas inte tidrapporten och användaren ser felet [!UICONTROL User with primary key values 'XXXXXXXXXXX' not found.]
* När en användare försöker skapa en tidrapport för ett team fylls fältet [!UICONTROL typeahead] inte i med team och knappen [!UICONTROL Create timesheet] inaktiveras.


**Områden i [!DNL Workfront Proof] uppdateras inte när ett korrektur skapas, flyttas eller arkiveras**

*[!DNL Workfront]Korrektur*

Dokumentet har för närvarande problem med indexeringsfördröjningar. Detta kan påverka användarupplevelsen på följande sätt:

* På kontrollpanelerna visas inte rätt antal korrektur
* Mappar uppdateras inte när ett korrektur skapas eller flyttas
* Arkiverade korrektur finns kvar i aktiva korrekturlistor.

+++

+++**Underhållsuppdatering (snabbkorrigering) 26 juli 2022**

Dessa problem har bara åtgärdats i den nya [!DNL Workfront]-upplevelsen.

Alla [!DNL Workfront Classic]-funktioner togs bort 14 juli 2022.

**Timmar som visas på tidrapporten skiljer sig från tidrapportlistan**

*Tidrapporter*

När en användare öppnar en tidrapport för att visa den, skiljer sig de timmar som visas från när användaren visar samma tidrapport i en tidrapportlista.


**Begäran konverterad till projekt med mall visar grupp från begärandekö, inte grupp från mall**

*Begäranden*

När en användare konverterar en begäran till ett projekt med hjälp av en mall kopplas det nya projektet till gruppen som äger begärandekön, inte till gruppen som är tilldelad mallen. Detta inträffar trots att gruppen som är kopplad till mallen fylls i i fältet [!UICONTROL Group] när projektet skapas.

+++

+++**Underhållsuppdatering 21 juli 2022**

Dessa problem har bara åtgärdats i den nya [!DNL Workfront]-upplevelsen.

Alla [!DNL Workfront Classic]-funktioner togs bort 14 juli 2022.

**Avvisningsstatus som är associerad med ett godkännande följer godkännandearbetsflödet**

**OBS! Den här funktionen släpptes 22 juli 2022.**

*Godkännanden*

Om du väljer en status som är associerad med en godkännandeprocess som avvisningsstatus för en godkännandesökväg, flyttas det avvisade objektet till den valda statusen och markeras som [!UICONTROL Pending approval]. Om du t.ex. väljer [!UICONTROL On Hold] som avvisandestatus och [!UICONTROL On Hold]-statusen är associerad med en godkännandeprocess, placeras det avvisade objektet i statusen [!UICONTROL On Hold- Pending approval], vilket kräver godkännande.

Före den här uppdateringen har objektet kringgått godkännandeprocessen för avvisningsstatusen och placerats i statusen [!UICONTROL On Hold].

**Konfigurera en anpassad hjälp-URL**

*[!UICONTROL Main Menu]*

Om din organisation har en anpassad intern hjälpwebbplats kan du konfigurera ikonen [!UICONTROL Main Menu] [!UICONTROL Help] för att gå till den platsen. Detta är användbart om hjälpwebbplatsen innehåller information om hur din organisation använder [!DNL Workfront].
Den här anpassade URL:en påverkar inte huvudhjälplänken i det övre området av [!DNL Workfront], inte heller kontextkänsliga hjälplänkar i hela [!DNL Workfront] som tar användare till hjälpwebbplatsen för [!DNL Workfront].

**Det går inte att välja Förfluten tid vid infogad redigering[!UICONTROL Task Duration]**

*Uppgifter*

När en användare visar en uppgiftslista och försöker redigera [!UICONTROL Task Duration] är följande varaktighetsenheter inte tillgängliga:

* [!UICONTROL Elapsed Minutes]
* [!UICONTROL Elapsed Hours]
* [!UICONTROL Elapsed Days]
* [!UICONTROL Elapsed Weeks]
* [!UICONTROL Elapsed Months]

**[!UICONTROL My Updates]-sidan är tom**

*Uppdateringar*

När en användare försöker visa sin [!UICONTROL My Updates]-sida läses sidan inte in. Användaren kan bara se navigeringsrubriken [!DNL Workfront].

Inställningen **[!UICONTROL Only Allow SAML 2.0 Authentication] saknas när en användare kopieras**

*Användare*

När en gruppadministratör kopierar en användare och avmarkerar alternativet [!UICONTROL Send an invite email to this person] visas inte kryssrutan [!UICONTROL nly Allow SAML 2.0 Authentication] som förväntat. Detta kan inträffa även när alla åtkomstkrav och behörighetskrav för den här åtgärden uppfylls.

+++

+++**Underhållsuppdatering 14 juli 2022**

Dessa problem har bara åtgärdats i den nya [!DNL Workfront]-upplevelsen.

Alla [!DNL Workfront Classic]-funktioner togs bort 14 juli 2022.

**Fel vid återställning av lösenord**

*Inloggning*

När en användare försöker återställa sitt lösenord kan han/hon inte återställa det och han/hon ser ett meddelande som talar om att han/hon inte har åtkomst. Användaren kan inte logga in på Workfront.

**Det går inte att begära mer åtkomst till en rapport**

*Rapporter*

När en användare med begränsad åtkomst till en rapport försöker begära mer åtkomst till en rapport är alternativet att begära mer åtkomst inte tillgängligt på menyn [!UICONTROL report actions].

**Ett bekräftelsemeddelande uppdaterades när ett begärandeutkast togs bort**

*Begäranden*

När en utkast tas bort visas följande bekräftelsemeddelande när du klickar på [!UICONTROL Discard draft]:

* [!UICONTROL Draft was discarded] (det här är ett meddelande som meddelar dig om att ditt utkast har tagits bort)
* [!UICONTROL Undo] (det här är en länk som du kan klicka på för att ångra åtgärden att ta bort utkastet. Då behålls utkastet i stället för att det tas bort.)

Före den här ändringen var alternativen:

* [!UICONTROL Draft will be discarded]
* [!UICONTROL Cancel]

**Datumvärden för journalpostfält är felaktiga när de används via API:t**

*Uppdateringar*

När en användare ändrar ett datumvärde för ett objekt och sedan öppnar den journalpost som representerar den datumändringen via API:t, är datumvärdena för [!UICONTROL oldDateVal] och [!UICONTROL newDateVal] som returneras av API:t felaktiga.

**Fel vid försök att ångra kommentar**

*Uppdateringar*

När en användare försöker ångra en kommentar ångras inte kommentaren och användaren ser följande fel:

[!UICONTROL Error 403: You do not have sufficient access to delete this Note /attask/api-internal/NOTE]

**Ny begränsning av antalet tecken i en uppdatering i förhandsvisningen**

*Uppdateringar*

För att förbättra prestandan för området [!UICONTROL Updates] har vi infört en ny gräns för hur många tecken du kan ange i en uppdatering eller ett svar på en befintlig uppdatering. Den nya gränsen är 15 000 tecken. Uppdateringen ändrade inte antalet tecken som tillåts när API:t används. API-teckengränsen för uppdateringar är 4 000.

**Fel vid överföring av bilaga från [!DNL Workfront] för Outlook-integrering**

*Workfront-integreringar*

När en användare försöker överföra en bifogad fil med integreringen [!DNL Workfront for Outlook], överförs inte den bifogade filen och användaren ser följande meddelande:

[!UICONTROL Some attachments have not been uploaded. Reason: Something went wrong with uploading attachments.]

**Uppdatering av korrekturmeddelanden via e-post**

*[!DNL Workfront]Korrektur*

Tidigare den här månaden, som en del av en korrigering till produktionsmiljön [!DNL Workfront], har vi åtgärdat ett fel i systemet för korrekturmeddelanden via e-post. Den här ändringen kommunicerades inte i underhållsuppdateringen när den släpptes. Vi har lagt till följande information i [underhållsuppdateringen den 2 juni 2022](#maintenance-update-on-june-2-2022):

Som ett resultat av felkorrigeringarna har den e-postadress som används för att skicka korrekturmeddelanden ändrats.

Tidigare innehöll korrekturmejladresserna organisationens underdomän. Till exempel meddelanden@[företagsdomän].my.workfront.com

Nu innehåller profiler för e-postadresser inte längre någon underdomän för organisationen. Alla korrekturmeddelanden via e-post kommer från följande adress: notification@my.workfront.com

Därför rekommenderar vi att du utför följande åtgärder om du inte redan gjort det:

* Uppdatera skräppostfiltren så att de accepterar e-post från notification@my.workfront.com
* Uppdatera tillåtelselista för att acceptera e-post från notification@my.workfront.com

**Det går inte att ändra användaralternativ efter den första konfigurationen i Arbetsflödesmallar**

*[!DNL Workfront Proof]*

När en användare lägger till en användare i en arbetsflödesmall kan de konfigurera alternativ. När den inledande konfigurationen är klar kan användaren dock inte längre ändra följande:

* [!UICONTROL Resolve comments and apply actions]-funktion
* [!UICONTROL "Share proof by tagging]-funktion
* Korrekturroll ([!UICONTROL Reviewer], [!UICONTROL Approver] osv.)

Filtret **[!UICONTROL This project's work items] har återställts i projektet[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Vi har återställt filtret &quot;Det här projektets arbetsobjekt&quot; i området [!UICONTROL Assigned] när du öppnar [!UICONTROL Workload Balancer] från ett projekt.

Det här filtret visas nu under avsnittet [!UICONTROL Suggested] i filtren för [!UICONTROL Assigned Work]-området i ett projekts [!UICONTROL Workload Balancer].

+++

## Uppdateringar i juni 2022

+++**Underhållsuppdatering 30 juni 2022**

**Visa [!UICONTROL Workload Balancer] i en vecka**

*[!UICONTROL Workload Balancer]*

Baserat på den feedback vi har fått från många kunder har vi nu lagt till ett alternativ för att visa [!UICONTROL Workload Balancer] i en vecka. Före den här uppdateringen kan du visa [!UICONTROL Workload Balancer] i 4, 6 och 12 veckor. Med den här uppdateringen har vi också ändrat alternativet 12 veckor till 3 månader.

**Panelen Delegera är nu tillgänglig från arbetsbelastningsutjämnaren**

*[!UICONTROL Workload Balancer]*

Obs! Den här uppdateringen finns bara i förhandsvisningsmiljön. Funktionerna som är kopplade till den här uppdateringen kommer att vara tillgängliga i Production med version 2.3.

Du kan nu visa delegaterna för en uppgift eller ett problem från Utjämning av arbetsbelastning. När du tilldelar en uppgift eller ett problem från Utjämning av arbetsbelastning kan du visa en lista över tilldelningar samt en lista över delegater för uppgiften eller utgåvan, om de är delegerade.

**Det går inte att öppna slutpunktsinformation i API Explorer**

*API*

När en användare visar [!DNL API Explorer] och klickar på en slutpunkt visas inte slutpunktsinformationen.

**Problem med knappen [!UICONTROL Details] när[!UICONTROL Home Calendar]** används

*Startsida*

När en användare använder [!UICONTROL Home Calendar] och klickar på en uppgift kan något av följande inträffa:

* Knappen [!UICONTROL Details] visas kort och försvinner sedan. Användaren kan inte komma åt informationen.
* Knappen [!UICONTROL Details] visas inte. Användaren kan inte komma åt informationen.
* Knappen [!UICONTROL Details] visas, men finns inte på rätt plats. Användaren kan klicka på knappen för att komma åt informationen.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 24 juni 2022**

**Datumväljaren stängs inte när det anpassade formuläret redigeras**

*Anpassad Forms*

När en användare redigerar ett anpassat formulär och försöker ändra ett datum, stängs inte datumväljaren när datumet markeras. Användaren kan inte stänga datumväljaren genom att spara, avbryta eller klicka utanför datumväljaren.

Detta har rapporterats i följande områden:

* [!UICONTROL Updates] område
* [!UICONTROL Home]

**Användaren kan inte flytta sig till en annan fas i ett korrektur**

*Korrektur*

När en användare visar [!UICONTROL Proof Workflow] för ett korrektur och försöker dra sig själv till en annan fas av korrekturet, fäster användarens namn tillbaka till den ursprungliga scenen och läggs inte till på den önskade scenen.

+++

+++**Underhållsuppdatering 23 juni 2022**

**[!UICONTROL Cannot add new request through dashboard]**

*Instrumentpaneler*

När en användare visar en instrumentpanel i ett projekt och försöker lägga till en ny begäran genom att klicka på knappen [!UICONTROL +New Request], svarar inte knappen och användaren kan inte lägga till en ny begäran.

**Fel vid visning av objekt i Home Worklist**

*[!UICONTROL Home]*

När en användare visar sin [!UICONTROL Home Work List] och klickar på ett objekt i avsnittet [!UICONTROL Approvals I've Submitted] visas följande fel på sidan:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

Om användaren uppdaterar sidan och sedan klickar på ett objekt i [!UICONTROL Work List] visas felet. Problemet påverkar inte längre bara objekt i avsnittet [!UICONTROL Approvals I've Submitted].

**Anpassat avsnitt i ett objekt innehåller resultat som inte finns i det objektet**

*Objekt*

När en användare visar ett [!UICONTROL custom]-avsnitt på ett objekt, visar det anpassade avsnittet objekt som inte är en del av det objektet. Detta har rapporterats när det anpassade avsnittet läggs till direkt i objektet och när ett anpassat avsnitt läggs till via en layoutmall.

**Aktiviteter flyttas till felaktigt projekt**

*Uppgifter*

När en användare flyttar uppgifter från projekt A till projekt B och sedan flyttar fler uppgifter från projekt A till projekt C, visas de uppgifter som ursprungligen flyttades till projekt B i projekt C.

**Vissa knappar/ikoner fungerar inte vid åtkomst av [!UICONTROL Workload Balancer] från en delad länk eller instrumentpanel**

*[!UICONTROL Workload Balancer]*

När en användare går till [!UICONTROL Workload Balancer] via en delad länk eller en länk i en kontrollpanel och försöker använda elementet längst upp på skärmen, fungerar inte elementen. Detta har rapporterats för följande:

* [!UICONTROL Today]
* Bakåt- och framåtpilar
* [!UICONTROL Weeks]
* Kalenderikon (datumväljare)

+++

+++**[!DNL Workfront]Underhållsuppdatering av scenarioplan 23 juni 2022**

**Användare med [!UICONTROL Manage] behörighet för en plan kan dela den med andra**

Som användare med [!UICONTROL Manage] behörigheter för en plan i [!DNL Scenario Planner] kan du nu dela den med andra användare. Före den här uppdateringen var det bara den som skapade planen som kunde dela planen med andra användare.

+++

+++**Underhållsuppdatering 16 juni 2022**

**Gruppadministratören kan inte lägga till medlemmar i gruppen**

*Grupper*

När en gruppadministratör försöker lägga till en användare i en grupp fylls inte användaren i i listrutan. Gruppadministratören kan inte välja några användare och kan därför inte lägga till några användare i gruppen.

**Anpassade kvartal visas inte när du anger ett filter**

*Filter*

När en användare skapar ett filter och filtrerar efter ett datumfält innehåller listrutan med tillgängliga operatorer för datumfältet inte några nyligen tillagda anpassade kvartal.

**&quot;Hoppfel&quot; vid konvertering av ett problem till ett projekt via en mall**

*Projekt*

När en användare försöker konvertera ett problem till ett projekt via en mall och utgåvan har ett anpassat formulär som innehåller ett avsnitt som bara är tillgängligt för administratörer, konverteras inte problemet och användaren ser följande fel:

[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Begäranden skickas utan obligatoriska fält ifyllda**

*Begäranden*

När en användare skapar en begäran som inte fyller i obligatoriska fält och sedan skickar begäran, skickas begäran utan data i de obligatoriska fälten. Det förväntade beteendet är att begäran inte skulle skickas och att användaren skulle få ett meddelande om att de måste fylla i de obligatoriska fälten innan begäran skickas.

**Nya anpassade kvartal verkar inte spara**

*Konfigurera*

När en användare lägger till ett nytt anpassat kvartal från området Projekt i installationsprogrammet och klickar på [!UICONTROL Save], visas ingen visuell indikation på sparandet. Användaren ser inget meddelande om att åtgärden lyckades, och knappen [!UICONTROL Save] finns fortfarande och är aktiv. Men om användaren uppdaterar sidan kan han eller hon se att de nya kvartalen visas i listan med anpassade kvartal.

Om användaren lägger till ett nytt kvartal, klickar på [!UICONTROL Save], inte får någon indikation på att filen har sparats, lägger till ytterligare ett kvartal utan att sidan uppdateras och klickar på [!UICONTROL Save] igen, kan det hända att det andra tillagda kvartalet inte sparas.

**[!UICONTROL Team Work Requests]-sidan är tom**

*Team*

OBS! Säkerhetsluckan finns bara i förhandsvisningsmiljön.

När en användare försöker öppna området [!UICONTROL Work Requests] på en gruppsida är sidan tom. Användaren kan se det övre navigeringsfältet, men inget sidinnehåll.

+++

+++**Underhållsuppdatering 9 juni 2022**

**Det går inte att markera objekt som ska filtreras i [!UICONTROL Portfolio Optimizer] inställningar**

*Portfolio*

När en användare är i [!UICONTROL Portfolio Optimizer] och visar fliken [!UICONTROL Project Filters] i området [!UICONTROL Preferences], är kryssrutorna bredvid objekten inte tillgängliga. Användaren kan inte markera eller avmarkera kryssrutor och kan därför inte markera objekt som ska filtreras.

**Det går inte att ändra [!UICONTROL Planned Start Date] eller [!UICONTROL Planned Completion Date] när [!UICONTROL Schedule From] inte är markerad**

*Projekt*

När en användare försöker redigera [!UICONTROL Planned Start Date] eller [!UICONTROL Planned Completion Date] för ett projekt och alternativet [!UICONTROL Schedule From] för det projektet inte är markerat, inaktiveras [!UICONTROL Planned Start Date]- och [!UICONTROL Planned Completion Date]-områdena och användaren kan inte redigera dessa datum.

**Det går inte att redigera åtkomstnivån för användare**

*Användare*

När en användare som har planeraråtkomst som inkluderar användaradministratörsåtkomst (gruppanvändare) försöker redigera användare i gruppen som de är administratör för, inaktiveras fältet [!UICONTROL Access]-nivå och användaren kan inte redigera åtkomstnivån.

+++

+++**[!DNL Workfront Scenario Planner]Underhållsuppdatering 9 juni 2022**

**Vänster panel med ändringsbar storlek i[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Du kan nu ändra storlek på den vänstra panelen i en plan i [!DNL Scenario Planner]. På så sätt kan längre initialnamn visas helt. Före den här uppdateringen trunkerades längre initialnamn.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 9 juni 2022**

**Data från anpassade formulär är inte tillgängliga i [!DNL Workfront Fusion] [!DNL Workfront] moduler**

*[!DNL Workfront Fusion]*

När en användare konfigurerar en [!DNL Workfront]-modul i [!DNL Workfront Fusion] och försöker välja utdata för modulen, visas inte fält från anpassade formulär. Detta inträffar när det anpassade formuläret skapades för en typ av [!DNL Workfront]-objekt och sedan lades en annan typ till i det. [!DNL Workfront Fusion] visar endast fält från anpassade formulär som ursprungligen skapats för den valda objekttypen.

**Det går inte att rulla för att visa alla scenariokörningar**

*[!DNL Workfront Fusion]*

När en användare visar ett scenario körningshistorik och försöker rulla nedåt för att visa fler körningar, slutar körningarna att läsas in och användaren kan inte visa dem. Dessutom kan användaren inte bläddra tillbaka till de senaste körningarna.

+++

+++**Underhållsuppdatering 2 juni 2022**

**[!UICONTROL Portfolio Optimizer]visar poängen 0 vid användning av andra språk än engelska**

*Portfolio*

När en användare använder [!DNL Workfront] på ett annat språk än engelska och visar [!UICONTROL Portfolio Optimizer] visas poängen som 0. Detta kan inträffa även när affärsärendet inte är fullständigt.

**Beräknade fältvärden är felaktiga när du skapar projekt från mallen**

*Projekt*

När en användare skapar ett projekt från en mall som innehåller beräknade fält är fältvärdena som visas i det nya projektet felaktiga.

**Det går inte att redigera [!UICONTROL Conditions] i området [!UICONTROL Project Preferences] i[!UICONTROL Setup]**

*[!UICONTROL Setup]*

När en användare försöker redigera [!UICONTROL Conditions] i området [!UICONTROL Project Preferences] i [!UICONTROL Setup] är sidan tom.

**Ny begränsning av antalet tecken i en uppdatering i förhandsvisningen**

*[!UICONTROL Workload Balancer]*

>[!NOTE]
>
>Den här uppdateringen gäller bara förhandsvisningsmiljön.

För att förbättra uppdateringsområdets prestanda har vi infört en ny gräns för hur många tecken du kan ange i en uppdatering eller svara på en befintlig uppdatering. Den nya gränsen är 15 000 tecken. Uppdateringen ändrade inte antalet tecken som tillåts när API:t används. API-teckengränsen för uppdateringar är 4 000. Uppdateringar
Stöd för anpassade typograferingsfält i filter för belastningsfördelning

Vi stöder nu filter som baseras på anpassade fält av typen [!UICONTROL Typeahead] i arbetsbelastningsutjämnaren. Före den här korrigeringen var filtrering för den här typen av anpassade fält inte möjlig i arbetsbelastningsutjämnaren.

**Det går inte att redigera behörigheter för en användares roll**

*[!DNL Workfront Proof]*

När en användare försöker redigera behörigheterna [!UICONTROL Resolve comments and apply actions] eller [!UICONTROL Share a proof by tagging] för en användares roll i [!DNL Workfront Proof] sparas inte ändringarna. Användaren får ett meddelande om att mallen har uppdaterats, men om användaren öppnar rollbehörigheterna igen kan användaren se att ändringarna inte sparades.

+++


## Uppdateringar i maj 2022

+++**Underhållsuppdatering 26 maj 2022**

Dessa problem har bara åtgärdats i den nya [!DNL Workfront]-upplevelsen. [!DNL Adobe Workfront Classic] stöds inte längre.

Alla [!DNL Workfront Classic]-funktioner tas bort i juli 2022. Byt till den nya upplevelsen så snart som möjligt.

**Uppdaterade vägbeskrivningsavgränsare**

*[!DNL Workfront]*

OBS! Den här uppdateringen släpptes 24 maj 2022.

Vi har uppdaterat vägbeskrivningarna i alla områden där vägbeskrivningar finns tillgängliga. Objekten i vägbeskrivningarna avgränsas nu med rörledningar (|). Före den här uppdateringen separerades de med snedstreck (/).

**Kan inte redigera anpassade formulär med avsnittsbrytningar**

*Anpassad Forms*

När en användare försöker redigera ett anpassat formulär som har en avsnittsbrytning, kan han/hon inte redigera formuläret och ser följande meddelande:

[!UICONTROL Specified section break security cannot be applied on all object types]

**Problem vid utskrift av instrumentpaneler till PDF**

*Instrumentpaneler*

Följande problem har rapporterats vid utskrift av en kontrollpanel till PDF:
PDF skriver inte ut varje rad i rapporten. Där rader saknas visas bara tomt utrymme.
PDF innehåller blanksteg mellan kolumnrubrikerna och den första raden i rapporten.

**[!DNL Portfolio Optimizer]visar poängen 0 vid användning av andra språk än engelska**

*Portfolio*

När en användare använder [!DNL Workfront] på ett annat språk än engelska och visar [!UICONTROL Portfolio Optimizer] visas poängen som 0. Detta kan inträffa även när affärsärendet inte är fullständigt.

**Vissa anpassade formulär visas inte när en mall redigeras**

*Mallar*

När en användare försöker redigera de anpassade formulären i en mall genom att klicka på [!UICONTROL Edit] i mallens sidhuvud, visas bara ett av de anpassade formulären som är kopplade till mallen i [!UICONTROL Edit Template] -fönstret.

**Delad länk till Utjämning av arbetsbelastning visar felaktigt tilldelat arbete**

*[!UICONTROL Workload Balancer]*

När en användare tittar på [!UICONTROL Workload Balancer] med hjälp av en delad länk, inkluderar [!DNL Workload Balancer] [!UICONTROL Assigned Work] i avsnittet [!UICONTROL Unassigned Work]. [!UICONTROL Assigned Work] har inget separat avsnitt. När användaren tittar på [!UICONTROL Workload Balancer] utan att använda den delade länken visas [!UICONTROL Assigned Work] som förväntat.

+++

+++**Underhållsuppdatering 19 maj 2022**

**Det går inte att skapa ett korrektur från en[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

När en användare försöker skapa ett korrektur från en [!DNL PowerPoint] som innehåller ett diagram, misslyckas skapandet av korrektur.

**Det går inte att skapa ett korrektur från ett [!UICONTROL Word] dokument**

*[!DNL Workfront Proof]*

När en användare försöker skapa ett korrektur från ett [!DNL Word]-dokument som innehåller ett diagram, misslyckas skapandet av korrektur.

**Det går inte att lägga till ett anpassat meddelande när du delar ett korrektur**

*[!DNL Workfront Proof]*

När en användare visar ett korrektur, öppnar området [!UICONTROL Share proof] och väljer knappen [!UICONTROL Add custom message] kan användaren inte skriva i textrutan som öppnas. När användaren försöker skriva i den här rutan försvinner rutan omedelbart.

**Kan inte stänga korrektur**

*[!DNL Workfront Proof]*

När en användare visar ett korrektur och försöker stänga det saknas X:et som stänger korrekturet i det övre högra hörnet av korrekturet.

**Det går inte att lägga till eller ta bort gruppadministratör**

*Grupper*

Om en användare visar en [!UICONTROL Group]-sida och försöker lägga till eller ta bort en gruppadministratör med hjälp av området [!UICONTROL Group Administrators] i rubriken, sparas inte ändringarna och användaren ser följande fel:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Vågrät rullningslist blockerar objekt i slutet av listan**

*Projekt*

När en användare visar en lista i en vy som sträcker sig utanför skärmens sida blockerar den vågräta rullningslisten användarens vy över det sista objektet i listan.

**[!UICONTROL Unexpected error] vid konvertering av ett problem till ett projekt med en mall**

*Listor*

När en användare försöker konvertera ett problem till ett projekt med hjälp av en mall konverteras inte problemet och användaren ser följande meddelande:

[!UICONTROL An unexpected error happened]

**Fältet [!UICONTROL Status] i en tidrapportvy är nu skrivskyddat**

*Tidrapporter*

Vi har ändrat fältet [!UICONTROL Status] i en tidrapportvy till skrivskyddat. Före den här ändringen kunde användare redigera statusen för en tidrapport som gjorde att de kunde åsidosätta beslutet för tidrapportgodkännarna.

+++

+++**Underhållsuppdatering 12 maj 2022**

Knappen **[!UICONTROL Save]slutar inte att läsas in när du redigerar ett projekt**

*Projekt*

När en användare redigerar ett projekt och försöker spara, märker de att knappen [!UICONTROL Save] visar ordet [!UICONTROL Loading]. Om användaren klickar på den här knappen för att spara ändringarna i projektet svarar inte knappen och ändringarna sparas inte.

**Fältetiketter visas inte när du visar ett objekt i[!UICONTROL Home]**

*Startsida*

När en användare väljer ett objekt från sin [!UICONTROL Home Work List], kommer området till höger om [!UICONTROL Home Work List] som visar objektet inte att innehålla fältetiketter. Fältvärdena finns.

**Snabbfilter fokuserar inte automatiskt på sökfältet**

*Listor*

När en användare är i en lista och klickar på förstoringsglaset för att snabbt filtrera, och sedan börjar skriva, visas inte texten. Det beror på att fokus ligger kvar på förstoringsglaset i stället för att flyttas till sökfältet.

Om du klickar på sökfältet överförs fokus och användaren kan ange texten i sin sökning.

**Användare kan inte infoga redigeringsfält i en rapport**

*Rapporter*

När en användare försöker redigera ett fält i en rapport och fältet hämtas från ett anpassat formulär, kan användaren inte redigera fältet. Detta inträffar när det anpassade formuläret ursprungligen skapades för en annan objekttyp än det objekt det är kopplat till.

**Etikett- och knapptext visas inte när ett korrektur skapas**

*[!DNL Workfront Proof]*

OBS! Säkerhetsluckan finns bara i förhandsvisningsmiljön.

När en användare försöker skapa ett korrektur visas inte texten för alternativ eller knappar. Därför vet användaren inte vad varje alternativ eller knapp representerar och kan inte konfigurera korrekturet.

+++

+++**Underhållsuppdatering 5 maj 2022**

**Kan inte lägga till en ny faktureringspost**

*Projekt*

Om användaren försöker lägga till en ny faktureringspost visas inte fälten för en ny faktureringspost och det inte går att skapa faktureringsposten när användaren befinner sig i området [!UICONTROL Billing Records] för ett projekt och använder vyn [!UICONTROL New Billing Record].

**Fel vid grupptilldelning i[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

När en användare försöker göra tilldelningar i [!DNL Workload Balancer] för ett projekt, dirigeras användaren om till en sida med följande meddelande:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

Användaren kan inte navigera bort från den här sidan förrän sidan har uppdaterats.

**Navigeringen för att öppna panelen [!UICONTROL Summary] för uppgifter och problem i[!UICONTROL Workload Balancer]** har uppdaterats

*[!UICONTROL Workload Balancer]*

Om du klickar på en uppgift eller ett problem i [!UICONTROL Workload Balancer] öppnas panelen Sammanfattning. Innan den här uppdateringen var du tvungen att klicka på ikonen [!UICONTROL Open Summary] i verktygsfältet och sedan klicka på uppgiften eller problemet. Detta hade visat sig vara en förvirrande upplevelse som nu har korrigerats. Du kan också klicka på menyn [!UICONTROL More] bredvid uppgifts- eller problemnamnet och sedan klicka på [!UICONTROL Open Summary].

**Gruppadministratören kan inte visa information om användare i gruppen**

*Användare*

När en användare som har tilldelats en åtkomstnivå som innehåller åtkomstinställningen [!UICONTROL User Admin (Group Users)] försöker visa information om en användare i sin grupp, visas följande fel:

[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Det går inte att ta bort anpassad gruppstatus**

*Grupper*

När en användare försöker ta bort en anpassad gruppstatus från sidan [!UICONTROL Group], blir sidan tom och statusen tas inte bort.

**Inställningarna för e-postavisering är inkonsekventa mellan kontaktområdet och användarinformationen**

*[!DNL Workfront Proof]*

De e-postaviseringsinställningar som visas i området [!UICONTROL Contacts] för [!DNL Workfront Proof] för en viss användare skiljer sig från de e-postaviseringsinställningar som har angetts i användarens [!UICONTROL User Details].

**Det går inte att använda textverktyget när du gör en kommentar i ett korrektur**

*[!DNL Workfront Proof]*

När en användare gör en kommentar om ett korrektur och försöker öppna verktyget [!UICONTROL Text], öppnas inte verktyget och användaren ser följande meddelande:

[!UICONTROL Text data for this page is still downloading. Please wait.]

**Proof-e-post kommer att skickas till användarens primära e-postadress**

*[!DNL Workfront Proof]*

Vi justerar hur e-postmeddelanden om korrektur skickas. Nu kommer meddelanden att skickas till användarens primära e-postadress i stället för till det alias som genereras av systemet.

Mer information om varför systemet genererar aliasmeddelanden finns i Användarsynkronisering mellan Adobe [!DNL Workfront] och [!DNL Workfront Proof].

+++

## Uppdateringar i april 2022

+++**Underhållsuppdatering 28 april 2022**

**Det går inte att rulla till knappen [!UICONTROL Save] när du redigerar en tidrapport**

*Tidrapporter*

När en användare redigerar en tidrapport kan de inte rulla redigeringsfönstret tillräckligt långt för att se knappen [!UICONTROL Save] och kan därför inte redigera tidrapporten.

**Den elektroniska signaturen kontrollerar nu Federations-ID**

*Korrektur*

När du signerar ett korrektur elektroniskt kontrollerar systemet nu Federations-ID, om du har konfigurerat enkel inloggning i [!DNL Workfront Proof], utöver din e-postadress i [!DNL Workfront].

Tidigare kontrollerade systemet endast din e-post i Workfront.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 25 april 2022**

**[!UICONTROL Workload Balancer]läser inte in**

*[!UICONTROL Workload Balancer]*

När en användare försöker öppna [!UICONTROL Workload Balancer] läses sidhuvudet och den vänstra navigeringen in, men innehållet i belastningsutjämnaren läses inte in. Användaren ser blinkande grå fyrkanter i stället för data. Ibland läses en del av innehållet in, men användaren ser fortfarande grå fyrkanter där de data som saknas finns.

+++

+++**Underhållsuppdatering 21 april 2022**

**Om du lägger till en uppgift hoppar sidan nedåt**

*Uppgifter*

När en användare lägger till en uppgift under en befintlig uppgift i en lista, hoppar sidan till nedre delen av listan. Även om den nya aktiviteten finns på rätt plats måste användaren rulla tillbaka för att hitta den.

**Användare som har lagts till i ett korrektur kan inte komma åt korrekturets arbetsobjekt i[!DNL Workfront]**

*Korrektur*

Om en användare läggs till på en scen i ett korrekturarbetsflöde läggs användaren inte till i dokumentdelningen och får inte behörighet till korrekturets arbetsobjekt i [!DNL Workfront]. När användaren är i [!DNL Workfront] och försöker öppna arbetsposten som korrekturet är kopplat till visas följande meddelande:

[!UICONTROL You do not have sufficient access to view this (object)]

Problemet gäller endast korrektur som redan skapats och användare som lagts till efter detta. Att lägga till användare i arbetsflödet innan korrekturskapande fungerar som förväntat.

**Det går inte att skicka e-post för återställning av lösenord från[!DNL Workfront]**

*Användare*

När en användare försöker skicka ett e-postmeddelande för lösenordsåterställning från en användarlista i [!DNL Workfront] är alternativet att skicka e-postmeddelandet inte tillgängligt.

**Knappen visar [!UICONTROL Start Issue] i stället för [!UICONTROL Start Request]**

*Begäranden*

När en användare visar en begäran som tilldelats deras team visas knappen [!UICONTROL Start Issue] i huvudet i stället för knappen [!UICONTROL Start Request].

Alternativet **[!UICONTROL Undo comment] tar bort taggade användare**

*Uppdateringar*

När en användare taggar en annan användare i en kommentar, skickar kommentaren och sedan väljer alternativet [!UICONTROL Undo comment], visas kommentaren som vanligt i en uppdateringsruta, men den taggade användaren finns inte i rutan [!UICONTROL Tagged users].

**Det går inte att rulla när [!UICONTROL Milestone]-vyn används i en rapport**

*Rapporter*

När en användare visar en rapport och väljer vyn [!UICONTROL Milestone], visar sidan vyn Milstolpe men inte längre rullar och användaren kan inte visa några milstolpar som skulle ligga längre ned på sidan.

**Felaktig valuta när rapporten visas på kontrollpanelen**

*Rapporter*

När en användare visar en rapport på en kontrollpanel är den valuta som används i rapporten felaktig. När användaren visar rapporten utanför kontrollpanelen är valutan korrekt.

**Filtret Slutfört visar inte Slutfört arbetsobjekt** &#x200B;

*[!UICONTROL Home]*

När en användare visar sin [!UICONTROL Home Work List] med filtret [!UICONTROL Completed] markerat visas inte slutförda arbetsobjekt i listan. När filtret [!UICONTROL All] har valts inkluderas slutförda objekt i listan, vilket visar att det finns slutförda objekt.

**[!DNL Workfront]läser inte in**

*[!DNL Workfront]*

När en användare försöker logga in på [!DNL Workfront] verkar sidan ha fastnat i en slinga med omdirigeringar eller uppdateringar och läses inte in.

+++

+++**Underhållsuppdatering 14 april 2022**

**Det går inte att lägga till en aktivitet från en rapport i ett anpassat avsnitt i en aktivitet**

*Uppgifter*

När en användare visar ett anpassat avsnitt för en uppgift och avsnittet innehåller en uppgiftsrapport, kan användaren inte lägga till en uppgift från den rapporten. Knappen [!UICONTROL Add Task] markerar rapporten, men öppnar inget fönster där användaren kan lägga till en uppgift.

**Klar knapp på fel plats när en vy redigeras**

*Vyer*

När en användare redigerar en vy visas knappen [!UICONTROL Done] högre upp på skärmen och kan överlappa text.

Användaren kan redigera vyn som vanligt. Funktionen påverkas inte.

**Det går inte att rulla när [!UICONTROL Milestone]-vyn används i en rapport**

*Rapporter*

När en användare visar en rapport och väljer vyn [!UICONTROL Milestone], visar sidan vyn Milstolpe men inte längre rullar och användaren kan inte visa några milstolpar som skulle ligga längre ned på sidan.

**Tom skärm när uppdateringar visas**

*Uppdateringar*

När en användare visar uppdateringar och rullar skärmen för att visa uppdateringar längre ned, blir skärmen tom och användaren kan inte se några uppdateringar.

**Fel vid grupptilldelning av användare till aktivitet som inte är tilldelad användarens roll**

*[!UICONTROL Workload Balancer]*

När en användare i [!UICONTROL Workload Balancer] försöker tilldela uppgifter till en användare vars jobbroll inte matchar den jobbroll som är tilldelad aktiviteterna visas ett meddelande om att uppgiften tilldelas med den primära jobbrollen för den tilldelade användaren. När användaren klickar på [!UICONTROL Assign] tilldelas uppgifterna inte och användaren ser följande fel:

[!UICONTROL Error. The server encountered an unknown error.]

+++

+++**Underhållsuppdatering 7 april 2022**

**Användare som lagts till i korrektur har felaktiga roller**

*Korrektur*

När en användare lägger till en annan användare i ett korrektur anges den användarens roll i korrekturet som [!UICONTROL Read-only], trots användarens faktiska korrekturroll.

**Det går inte att skicka e-post för återställning av lösenord till användaren**

*Användare*

När en användare försöker skicka en lösenordsåterställning till en annan användare ser han/hon att alternativet [!UICONTROL Send Forgot Password Email] inte är tillgängligt på menyn [!UICONTROL More].

**[!UICONTROL Update All]skickar uppdateringar till användarprofiler i stället för projektet**

*Uppdateringar*

När en användare visar området [!UICONTROL People] i ett projekt och väljer alternativet [!UICONTROL Update All] och sedan anger en uppdatering, bokförs inte uppdateringen i själva projektet. Istället läggs de in i de enskilda användarprofilerna för varje användare i projektet.

**För många sidor vid utskrift av uppdateringar**

*Uppdateringar*

När en användare visar en uppdateringsström som skulle vara mer än en utskriven sida, och försöker skriva ut sidan, visar utskriftsskärmen att antalet sidor ligger långt över det faktiska antalet sidor som behövs för att skriva ut uppdateringarna. Om användaren sedan försöker skriva ut till PDF misslyckas skapandet av PDF.

**Användare kan inte se hela listan med entiteter som delas med en rapport när inställningen [!UICONTROL Visible System-Wide] är aktiverad**

*Rapporter*

När du delar rapporter med flera entiteter som visas i rutan [!UICONTROL Report Access], kan användare inte rulla till listens nederkant för att se hela listan när inställningen [!UICONTROL Visible System-Wide] är aktiverad.

**Felaktig valuta används i rapporter**

*Rapporter*

Om en användare anger att valutan för ett projekt ska vara en annan än standardvalutan, visas en rapport om det projektet i stället för projektets standardvaluta.

**Senast visade information uppdateras inte i [!UICONTROL Report Usage] rapporter**

*Rapporter*

När en användare visar en rapport som visar information om den senaste gången rapporten visades, kan den informationen vara tom eller vara gammal. Detta berör fält som:

* [!UICONTROL Last Viewed By]
* [!UICONTROL Last Viewed Data]
* [!UICONTROL Last X Viewers]
* [!UICONTROL Views This Month / Quarter / Year]

**Slutförda uppgifter visas i[!UICONTROL Home Work List]**

*[!UICONTROL Home]*

När en användare visar sina [!UICONTROL Home Work List] ser de Slutförda uppgifter i listan, även när alternativet att visa Slutförda uppgifter inte har valts.

**Knappen Schema är inte synlig för att schemalägga uppdatering av sandlådan**

*Sandlådemiljö*

Knappen [!UICONTROL Schedule] som används för att schemalägga en uppdatering av en sandlåda visas inte i den övre banderollen i sandlådemiljön.

**Ändringar i ett beräknat fält påverkar alla beräknade fält i ett formulär**

*Anpassad Forms*

När en användare är i den anpassade formulärbyggaren och ändrar värdet för ett beräknat formulär, visar alla beräknade fält i formuläret det nya värdet. Detta kan påverka nya eller befintliga beräkningsfält.

**Färger flimrar i anpassad formulärbyggare**

*Anpassad Forms*

När en användare arbetar med beräkningsfält i det anpassade formulärbyggaren, flimrar färgerna för fälten och uttrycken.

**[!UICONTROL Cannot reject an approval]**

*Godkännanden*

När en användare försöker avvisa ett godkännande svarar inte knappen [!UICONTROL Reject] och godkännandet avvisas inte.

Fliken **[!UICONTROL Projects]har standardvärdet Alla projekt trots föregående val**

*Projekt*

När en användare går till en projektsida via en flik som har fästs som en del av layoutmallen, blir sidan som standard [!UICONTROL All Projects] i den vänstra navigeringen. Detta inträffar även när användaren väljer ett annat område i den vänstra navigeringen och sedan navigerar bort från sidan Projekt och tillbaka.

+++


## Uppdateringar i mars 2022

+++**Underhållsuppdatering den 31 mars 2022**

**Tidszoner är inte konsekventa mellan [!DNL Workfront] och[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

När en användares profil är inställd på en viss tidszon i [!DNL Workfront] ställs användarens tidszon i [!DNL Workfront Proof] in på en annan tidszon.

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

När en användare försöker tilldela en annan användare till en uppgift på [!UICONTROL Workload Balancer], och uppgiften tilldelas en annan jobbroll än den tilldelade användarens primära jobbroll, tilldelas användaren till uppgiften med den primära jobbrollen och följande meddelande visas:

&quot;\&lt;Namn\> matchar inte rollen \&lt;Uppgiftsrolltilldelning\>. 1 arbetsuppgift som för närvarande är tilldelad rollen &lt;\Task role assign\> tilldelas \&lt;Name\> i rollen \&lt;Primary job role\>.&quot;

Detta inträffar även om användaren inte har jobbrollen för aktivitetsrolltilldelningen som en sekundär jobbroll.

**Problem med skärmanslaget &quot;Visa fler arbetsuppgifter&quot; b** &#x200B;

*Agile*

När en användare klickar på fältet [!UICONTROL Show more work items] på en skärmavla och sedan rullar för att se de nya objekten, fäster [!UICONTROL Show more work items]-fältet vid skärmavlan och följer med när det rullas. Detta kan göra korten svåra att läsa.

**Röda punkter visas i obligatoriska fält i anpassade formulär**

Anpassad Forms

När en användare visar ett obligatoriskt fält i ett anpassat formulär visas två röda punkter under asterisken som anger att fältet är obligatoriskt.

**Tidslistrutan har stängts av i uppmaningar**

*Rapporter*

När en användare fyller i uppmaningarna för en rapport och påträffar en datumväljare visas inte timväljaren längst ned i datumväljaren efter 2, och användaren kan inte välja något timvärde förutom 1 eller 2.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 29 mars 2022**

**Det går inte att ändra eller spara beräkningar i verktyget för anpassade formulär**

*Anpassade formulär*

Om en användare skriver in en beräkning manuellt i ett beräkningsfält i verktyget för anpassade formulär och sparar formuläret, sparas inte beräkningen. Om användaren öppnar det anpassade formuläret igen är fältet tomt.

Om en användare anger en beräkning i ett beräkningsfält i verktyget för anpassade formulär genom att använda listrutorna och sparar formuläret, sparas det värdet. Om användaren öppnar det anpassade formuläret på nytt kan användaren inte redigera det här fältet eller ta bort värdet, antingen manuellt eller med listrutan.

OBS! Den här felkorrigeringen innehåller ytterligare funktioner. När du börjar skriva i ett beräkningsfält visas möjliga uttryck eller beräkningar i en listruta nedan på samma sätt som i beräkningsredigeraren. Klicka på ett objekt i listrutan för att lägga till det i beräkningsfältet.

+++

+++**Underhållsuppdatering 24 mars 2022**

**Tidszoner är inte konsekventa mellan [!DNL Workfront] och[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

När en användares profil är inställd på en viss tidszon i [!DNL Workfront] ställs användarens tidszon i [!DNL Workfront Proof] in på en annan tidszon.

**Obligatoriskt fältfel för ifyllda anpassade fält när en mall bifogas**

*Projekt*

När en mall med obligatoriska anpassade fält bifogas till ett projekt där fältet redan finns och är ifyllt visas följande fel: [!UICONTROL There are incomplete fields. Enter values for required fields before you can continue.]
Genom att klicka på [!UICONTROL Take me there] kan de se att fälten är ifyllda och de kan bifoga mallen.

**[!UICONTROL Workload Balancer] blinkar när du växlar mellan datum**

*[!UICONTROL Workload Balancer]*

Timmarna för användaren som anges först i [!UICONTROL Workload Balancer] visas inte när du uppdaterar tidslinjen. Användaren och timmarna visas med alla grå rutor som bara blinkar. Det här händer om du går framåt och bakåt på tidslinjen.

Det verkar som om visningen återställs när du uppdaterar filtret. Om du flyttar bakåt och framåt på tidslinjen visas emellertid inte blixten igen och användaren måste ange att timmarna inte ska visas.

**Den anpassade terminologin är inkonsekvent**

*Layoutmallar*

Användare rapporterar att när administratören för [!DNL Workfront] anpassar terminologin för vissa objekt med en layoutmall visas det nya objektnamnet inkonsekvent i gränssnittet.

På sidan [!UICONTROL Projects] kan du till exempel fortfarande se sidtiteln som [!UICONTROL Projects], även om [!DNL Workfront]-administratören har ändrat namnet för [!UICONTROL Projects] till något annat.

Detta skapar förvirring för slutanvändarna.

+++

+++**Underhållsuppdatering 17 mars 2022**

**Miniatyrbilder och huvudbilder är tomma när flersidiga filer visas med [!DNL Safari] webbläsare**

*[!DNL Workfront Proof]*

När en användare försöker visa en fil med flera sidor i webbläsaren [!DNL Safari] är miniatyrbilderna tomma. Ibland kan huvudbilden också vara tom.

**Felaktig användarlista när grupptilldelningar görs i[!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

När en användare gör en grupptilldelning i [!UICONTROL Workload Balancer] och väljer ett projekt och en jobbroll är listan med tillgängliga användare felaktig. Det kan visa användare utan behörighet för Jobbroll eller Projekt, och användare med behörighet för Jobbroll och Projekt visas inte i listan.

**[!UICONTROL Sorting is not working in reports]**

*Rapporter*

När en användare klickar på en kolumn för att sortera efter den verkar sorteringen fungera, men resultatet återgår direkt till den ursprungliga sorteringen som den såg ut innan användaren klickade på kolumnen. Sorteringen i valfri kolumn behålls inte.

**Om du väljer [!UICONTROL Nothing] återställs [!UICONTROL Report Default]-grupperingen**

*Rapporter*

När en rapport har en inbyggd gruppering och användaren försöker välja [!UICONTROL Nothing] i den nedrullningsbara menyn [!UICONTROL Grouping] visas rapporten inom kort utan gruppering och återgår sedan till grupperingen [!UICONTROL Report Default].

**Fliken [!UICONTROL Blueprints access] har tagits bort från inställningarna för utkast**

*Foton*

OBS! Säkerhetsluckan finns bara i förhandsvisningsmiljön.

Fliken [!UICONTROL Blueprints access] har tagits bort från inställningen för utkast. Inga funktioner har tagits bort från inställningarna för utkast.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 14 mars 2022**

**Det går inte att rulla nedåt i användarlistan när tilldelning görs på Kanban-tavlan**

*Agile*

När en användare visar ett [!DNL Kanban]-kort och försöker göra en tilldelning, fortsätter användarlistan som visas när användaren skriver att hoppa tillbaka till toppen när användaren rullar nedåt. Användaren kan inte markera en användare som inte finns i den övre delen av listan och kan inte spara uppdragsändringen.

**[!UICONTROL Milestone]Vyn i projektrapporten orsakar felet**

*Rapporter*

När en projektrapport visas i [!UICONTROL Milestone]-vyn visas ett [!UICONTROL APIModel INTERNAL does not support namedQuery TILE:milestone-view (UIVW)]-fel.

**Den anpassade terminologin är inkonsekvent**

*Layoutmallar*

Användare rapporterar att när administratören för [!DNL Workfront] anpassar terminologin för vissa objekt med en layoutmall visas det nya objektnamnet inkonsekvent i gränssnittet.

På sidan [!UICONTROL Projects] kan du till exempel fortfarande se sidtiteln som [!UICONTROL Projects], även om [!DNL Workfront]-administratören har ändrat namnet för [!UICONTROL Projects] till något annat.

Detta skapar förvirring för slutanvändarna.

**Det går inte att uppdatera beräkningar för befintliga beräknade fält**

*Anpassad Forms*

Användarna kan inte uppdatera/ändra beräkningarna i beräkningsfält. Om fältet skapades och sparades utan någon beräkning återgår byggaren till tom varje gång du försöker lägga till ett uttryck och spara/använda.

Om du skapar ett beräkningsfält med ett visst uttryck och sparar det återgår det till det tidigare värdet varje gång du försöker ändra beräkningen.

**[!UICONTROL Invalid Parameter]-fel vid återställning av lösenord**

*Inloggning*

Användarna kan inte återställa sina lösenord i någon miljö. När de anger sin e-postadress och försöker fortsätta ser de ett fel.

[!UICONTROL Error: Invalid Parameter: Search Parameter value "domain"].

+++

+++**Underhållsuppdatering 10 mars 2022**

**Problem med att logga in i förhandsvisningsmiljön**

*Inloggning*

Följande problem med att logga in i förhandsvisningsmiljön har rapporterats.

När en användare försöker logga in i förhandsvisningsmiljön visas ett meddelande om att han/hon har angett fel ID eller lösenord.

När en användare försöker återställa sitt lösenord visas felet [!UICONTROL ?Multiple users were found with the email address <example@example.com>?]

**Anpassade formulär läses in långsamt i [!UICONTROL Project Details] område**

*Projekt*

När en användare försöker visa ett projekts [!UICONTROL Project Details]-område läses alla anpassade formulär som är kopplade till projektet in först efter en fördröjning på minst 15 sekunder. Alternativet [!UICONTROL Add custom forms] påverkas också av den här fördröjningen.

**Anpassade formulärfältsvärden har inte sparats på dokumentsammanfattningspanelen**

*Dokument*

När en användare uppdaterar anpassade formulärfält på dokumentsammanfattningspanelen, och ett eller flera av dem är ett huvudfält, sparar ändringarna och navigerar bort från sammanfattningspanelen, sparas inte uppdateringarna. Detta inträffar endast när ett texthuvudfält redigeras, även om alla fält påverkas.

**Data bevaras inte vid konvertering av mallar på grund av åtkomstnivåer för malldelning**

*Projekt*

När en användare som har åtkomst till Visa på en delad mall försöker konvertera ett problem till ett projekt, överförs inte data i anpassade formuläravsnitt som kräver [!UICONTROL Conrtibute] eller senare åtkomst för att kunna visas till det skapade projektet.

**Fel vid överföring av ny dokumentversion**

*Dokument*

När en användare försöker överföra en ny version av ett dokument från dokumentlistan överförs inte dokumentet och användaren ser följande fel:

[!UICONTROL Error Cannot invoke "com.attask.boz.Document.getCurrentVersion()" because "document" is null]

**Det går inte att redigera faktureringstariffer**

*Projekt*

När en användare försöker redigera en faktureringsfrekvens på fliken [!UICONTROL Billing Rates] i ett projekt öppnas fönstret [!UICONTROL Edit] kort när användaren klickar på knappen [!UICONTROL Edit] , men det stängs innan användaren kan ändra faktureringsfrekvensen. Redigeringsfönstret öppnas inte när du klickar på knappen igen.

**Offentlig länk för dokument leder till en tom sida**

*Dokument*

När en användare försöker öppna ett dokument med hjälp av en offentlig länk leder länken till en tom sida. Detta inträffar när länken öppnas i ett fönster där en aktiv [!DNL Workfront]-session är öppen.

**Hoppar över fel när aktivitet eller problem läggs till i listan**

*Uppgifter och problem*

När en användare som inte är administratör försöker lägga till en uppgift eller ett problem i en lista och fyller i anpassade fält skapas inte aktiviteten eller problemet och användaren ser följande fel:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Om du lämnar en uppdatering efter en statusändring återställs objektet till ett tidigare läge**

Projekt, uppgifter och problem

Om du ändrar status för ett projekt, en uppgift eller ett problem och sedan omedelbart börjar skriva en uppdatering utan att uppdatera sidan, visas föregående status i uppdateringsrutan. Om uppdateringen har bokförts återställs objektet till föregående status.

**Användare som lagts till i korrektur har felaktiga roller**

*Korrektur*

När en användare lägger till en annan användare i ett korrektur anges den användarens roll i korrekturet som [!UICONTROL Read-only], trots användarens faktiska korrekturroll.

Lösning:
Ställ in användarens korrekturroll i profilen till något annat och återställ sedan till rätt roll.

**Anpassat formulär läses inte in när utgåva konverteras till projekt med mallen**

*Anpassade formulär*

När en användare försöker konvertera ett ärende till ett projekt med hjälp av en mall kanske inte ett eller flera av de anpassade formulären som är kopplade till mallen läses in. När användaren konfigurerar mallen för det nya projektet visas följande meddelande i stället för de anpassade formulären:

&quot;[!UICONTROL Something went wrong, could not load form].&quot;

**Användaren kan inte lägga till ett fel i den anpassade listrutan som visas i vyn**

*Listor*

När en användare lägger till ett problem från en textbunden lista och det finns en anpassad vy där anpassade listrutefält tillämpas på listan, uppstår ett fel när användaren bara fyller i det nedrullningsbara fältet. Användaren har åtkomst till att redigera anpassade formulär och är projektägare med behörighet att hantera projektet.

[!UICONTROL Error: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it!]

**Behörigheter att lägga till uppgifter i ett projekt krävs inte för att flytta eller kopiera en uppgift till projektet**

*Uppgifter*

Nu kan du flytta eller kopiera en uppgift till en annan uppgift i ett projekt utan att ha behörighet att lägga till uppgifter i målprojektet. Du måste ha behörighet att lägga till uppgifter i minst en av målprojektets uppgifter. Före den här uppdateringen behövde du behörighet att lägga till uppgifter i projektet för att flytta eller kopiera en uppgift till projektet eller någon av dess uppgifter.  Den här uppdateringen är nu tillgänglig i produktionsmiljön. Den har varit tillgänglig i förhandsvisningsmiljön från och med underhållsuppdateringen 24 mars 2022.

Obs! Den här uppdateringen är tillgänglig i produktionsmiljön när du kopierar eller flyttar utgåvor efter 22.2-produktionsutgåvan. Mer information om den aktuella versionen finns på workfront.com/release.

**Listrutan Fråga är inaktiverad**

*Rapporter*

När du använder en uppmaning i en rapport kommer de nedrullningsbara menyer som gör att du kan välja filtreringsvillkor för rapporten att tas bort. Därför visas inte villkoren längst ned i den nedrullningsbara menyn.

**Arbetsobjektet återgår till föregående status när en uppdatering görs**

*Uppdateringar*

När en användare ändrar status för en arbetspost i huvudet uppdateras inte statusen i området [!UICONTROL Update]. Om användaren sedan gör en uppdatering visar listrutan fortfarande den tidigare statusen. När uppdateringen sparas skriver den här tidigare, felaktiga statusen över den status som angetts i rubriken.

+++

+++**Underhållsuppdatering 3 mars 2022**

**Det går inte att lägga till dokument från[!DNL Google Drive]**

*Dokument*

När en användare försöker lägga till ett dokument från [!DNL Google Drive] svarar inte markeringen och användaren kan inte välja vilka dokument som ska läggas till.

**Taggade användare läggs inte till för att uppdatera tråden**

*Uppdateringar*

När en användare är taggad i en uppdatering visas de inte i uppdateringsområdet [!UICONTROL To] eller i dess svar.

**Korrekturanvändare har två separata korrekturkonton**

*[!DNL Workfront Proof]*

En användares e-postadress i [!DNL Workfront Proof] kan finnas i två separata konton med separata ID:n, vilket ger användaren två konton. Detta kan göra det svårt att hitta rätt konto.

**Hoppfel i rapportrubriker**

*Rapporter*

När en användare visar en rapport visas följande fel i rapportrubriken:

[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

Om användaren visar en kontrollpanel kan felet visas i huvudet för alla rapporter på kontrollpanelen.

**Data i fält som bara kan redigeras av administratörer i anpassade formulär bevaras inte vid konvertering av utgåvor till projekt**

*Projekt*

När en icke-admin-användare försöker konvertera ett problem till ett projekt med hjälp av en mall och felet innehåller data i fält som bara kan redigeras av en administratör, överförs inte data i dessa fält till det nya projektet.

När en administratör konverterar problemet överförs data till det nya projektet som förväntat.

Filstorleken **[!DNL XLS]och [!DNL XLSX] har tillfälligt minskats till 100 MB för korrektur**

*Korrektur*

För att åtgärda ett säkerhetsproblem har vi tillfälligt begränsat den maximala filstorleken för [!DNL XLS]- och [!DNL XLSX]-filer till 100 MB när vi skapar ett korrektur.

Obs! Den här uppdateringen gjordes i förhandsvisningsmiljön den 24 februari och kommer att finnas i produktionsmiljön den 3 mars.

**Uppdatera till Workfront Search**

Sök

En fasad utrullning påbörjades den här veckan för att uppdatera infrastrukturen för sökfunktionen [!DNL Workfront]. Uppdateringen kommer att göra framtida förbättringar av sökfunktionen enklare och tillförlitligare. Med de här ändringarna indexeras objekt som läggs till i [!DNL Workfront] snabbare och kommer därför att returneras i sökresultaten tidigare.

Den stegvisa utrullningen fortsätter i 2 veckor.

**Uppdaterade verktygsfält för rapporter på kontrollpaneler**

Rapporter

Rapporter på kontrollpaneler visar nu ett nytt verktygsfält. Det här verktygsfältet är en del av uppdateringarna av listor och rapporter som sker i hela [!DNL Workfront].

+++


## Uppdateringar i februari 2022

+++**Underhållsuppdatering (snabbkorrigering) den 24 februari 2022**

**Data bevaras inte vid konvertering av problem till projekt om fältet är dolt i mallen**

*Projekt*

När en användare konverterar ett ärende till en mall och mallen innehåller ett anpassat formulär som visar eller döljer fält baserat på värden i andra fält, överförs inte data i fält som är dolda i mallen (datalfritt) vid konverteringen till det nya projektet.

**Det går inte att exportera resursplaneraren med rollen**

*Resursplanering*

När en användare försöker exportera [!DNL Resource Planner] när alternativet [!UICONTROL View by Role] används, lyckas inte exporten och användaren får ett e-postmeddelande med följande meddelande:

Ett fel uppstod när dina [!DNL Resource Planner]-data exporterades.

**Knappen för kopieringsbegäran fungerar inte**

*Begäranden*

När en användare försöker kopiera en begäran fungerar inte knappen [!UICONTROL Copy Request] om användaren inte har åtkomst till köavsnittet.

+++

+++**Underhållsuppdatering 24 februari 2022**

**Anpassade formulärdata försvinner när andra formulärfält fylls i**

*Anpassade formulär*

När en användare fyller i ett anpassat formulär som en del av konverteringen av ett problem till ett projekt, kan det hända att data i ett annat anpassat fält försvinner om du fyller i ett anpassat fält. Om användaren anger de data som saknas igen visas följande felmeddelande när han/hon försöker skapa projektet:

[!UICONTROL You must be a system admin to change this custom data parameter value]

Fältet **[!UICONTROL This approval process can be used by...] saknas**

*Godkännanden*

När en användare skapar eller redigerar en godkännandeprocess i området [!UICONTROL Setup] saknas fältet [!UICONTROL This approval process can be used by...]. Detta kan inträffa när du skapar en godkännandeprocess eller när du redigerar en befintlig.

**Systemadministratören kan inte tilldela om användare när en grupp tas bort**

*Grupper*

När en systemadministratör tar bort en grupp har de bara möjlighet att tilldela om gruppens användare till grupper som systemadministratören är gruppadministratör för. Andra grupper visas inte i listrutan och administratören kan inte markera dem.

**Hoppfel vid konvertering av problem till projekt**

*Projekt*

När en användare försöker konvertera ett problem till ett projekt med hjälp av en mall och lägger till eller tar bort anpassade formulär från mallen, konverteras inte problemet och användaren ser följande meddelande:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Det går inte att öppna korrektur. Sidan uppdateras**

*Korrektur*

När en användare försöker öppna ett korrektur går det inte att öppna det. Sidan uppdateras till slut.

Filstorleken **[!DNL XLS]och [!DNL XLSX] har tillfälligt minskats till 100 MB för korrektur**

*Korrektur*

För att åtgärda ett säkerhetsproblem har vi tillfälligt begränsat den maximala filstorleken för [!DNL XLS]- och [!DNL XLSX]-filer till 100 MB när vi skapar ett korrektur.

Obs! Den här uppdateringen kommer att finnas i förhandsvisningsmiljön den 24 februari och i produktionsmiljön den 3 mars.

**Behörighet att lägga till aktiviteter eller problem i ett projekt krävs inte för att flytta eller kopiera en aktivitet eller ett problem till projektet**

*Projekt*

Nu kan du flytta eller kopiera en uppgift eller ett problem till en annan uppgift i ett projekt utan att ha behörighet att lägga till uppgifter eller problem i målprojektet. Du måste ha behörighet att lägga till uppgifter eller problem i minst en av målprojektets uppgifter. Före den här uppdateringen behövde du behörighet att lägga till aktiviteter eller problem i projektet för att flytta eller kopiera en aktivitet eller ett problem till projektet eller någon av dess uppgifter. Den här uppdateringen är bara tillgänglig i förhandsvisningsmiljön.

Obs! Den här uppdateringen är tillgänglig i produktionsmiljön när du kopierar eller flyttar uppgifter den 10 mars. Den här uppdateringen är tillgänglig i produktionsmiljön när du kopierar eller flyttar problem med 22.2-produktionsversionen. Mer information om den aktuella versionen finns i workfront.com/release.

**Uppdatera till Workfront Search**

*Sök*

En fasad utrullning påbörjades den här veckan för att uppdatera infrastrukturen för sökfunktionen [!DNL Workfront]. Uppdateringen kommer att göra framtida förbättringar av sökfunktionen enklare och tillförlitligare. Med de här ändringarna indexeras objekt som läggs till i [!DNL Workfront] snabbare och kommer därför att returneras i sökresultaten tidigare.

Den stegvisa utrullningen fortsätter i 2 veckor.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 18 februari 2022**

**Validering av fältvärdetyp har lagts till i [!DNL Anaplan] egenskaper för listobjekt**

*[!DNL Adobe Workfront Fusion]*

Ett problem har korrigerats som tillåter användare att placera fel datatyp i fält för egenskaper för listobjekt. Genom validering av egenskapstypen kan [!DNL Fusion] säkerställa att rätt datatyp skickas till Anaplan, vilket eliminerar fel orsakade av felaktiga datatyper.

+++

+++**Underhållsuppdatering 17 februari 2022**

**Fel vid borttagning av föregående från fliken Föregående**

*Uppgifter*

När en användare försöker ta bort en föregångare från fliken [!UICONTROL Predecessors] för en aktivitet tas aktiviteten inte bort och användaren ser följande fel:

[!UICONTROL Task with primary key value(s) "" not found]

**Hoppfel när användarsidan öppnas**

*Användare*

När en användare försöker öppna sidan [!UICONTROL Users] öppnas inte sidan och användaren ser följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Överlappande element i huvudet i en rapport på en kontrollpanel**

*Instrumentpaneler*

När en användare visar en rapport på en kontrollpanel ser de att grupperingsikonen och etiketten överlappar länkarna till [!UICONTROL Details] och [!UICONTROL Summary].

**Problem med [!UICONTROL More]-menyn för dokument och korrektur**

*Dokument*

När en användare väljer ett dokument eller ett korrektur i en [!DNL Workfront Classic]-dokumentlista och sedan klickar på [!UICONTROL More] kan de se något av följande problem:
Knappen svarar inte
Alla alternativ under knappen har etiketten [!UICONTROL object Object] och kan inte användas.

Felet **&quot;Du måste vara systemadministratör&quot; när du skapar ett projekt**

*Projekt*

När en användare som inte är administratör försöker skapa ett projekt och bifogar ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, kan de inte skapa projektet och de ser följande fel:

&quot;Du måste vara systemadministratör för att kunna ändra det här anpassade dataparametervärdet&quot;

**Data i ett anpassat formuläravsnitt som bara är för administratörer bevaras inte vid konvertering av utgåvor till projekt**

*Projekt*

När en användare konverterar ett problem till ett projekt med hjälp av en mall som har ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, överförs inga data i avsnittet med enbart administratörer till det nya projektet. Detta inträffar även om en administratör konverterar problemet.

+++

+++**Underhållsuppdatering 10 februari 2022**

**[!UICONTROL You must be a system admin]-fel när ett projekt skapades**

*Projekt*

När en användare som inte är administratör försöker skapa ett projekt och bifogar ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, kan de inte skapa projektet och de ser följande fel:

[!UICONTROL You must be a system admin to change this custom data parameter value]

**Användare som har inaktiverats och återaktiverats visas inte i[!UICONTROL Proof contacts]**

*[!DNL Workfront Proof]*

När en användare visar sin kontaktlista i [!DNL Workfront Proof] visas inte användare som har inaktiverats och återaktiverats i listan.

Meddelandet **&quot;Något gick fel&quot; när ett problem konverterades till ett projekt med en mall**

*Projekt*

När en användare som inte är administratör försöker konvertera ett ärende till ett projekt med hjälp av en mall visas följande meddelande i anpassade formulärfält som bara är synliga för administratörer:

[!UICONTROL Something went wrong, could not load form]

**&quot;Det går inte att läsa in sidinnehåll&quot;-fel vid visning av projektinställningar**

*Konfigurera*

När en administratörsanvändare försöker visa projekt, uppgifter eller problem under [!UICONTROL Project Preferences] i området [!UICONTROL Setup] läses inte sidan in och användaren ser följande fel:

[!UICONTROL Cannot load page content. Please try refreshing the page.]

+++

+++**Underhållsuppdatering 3 februari 2022**

**[!UICONTROL BizContext]-fel vid inloggning**

*Inloggning*

När en användare försöker logga in på [!DNL Workfront] misslyckas inloggningen och följande meddelande visas:

[!UICONTROL Let's try that again. Database error: BizContext commit failed!]

Detta har rapporterats i förhandsvisningsmiljön.

**Utskicksuppdateringsströmmen försvinner om problemet väntar på godkännande**

*Uppdateringar*

När en användare klickar i rutan [!UICONTROL New update] i uppdateringsströmmen för ett problem som väntar på godkännande, försvinner hela uppdateringsströmmen.

**Fel vid överföring av ny version av ett dokument**

*Dokument*

När en användare försöker överföra en ny version av ett dokument överförs inte den nya versionen och användaren ser något av följande fel:

* [!UICONTROL documentID cannot be null]
* [!UICONTROL Error: Invalid Parameter: documentID value "undefined"]

**Offentlig länk för dokument leder till en tom sida**

*Dokument*

När en användare försöker öppna ett dokument med hjälp av en offentlig länk leder länken till en tom sida. Detta inträffar när länken öppnas i ett fönster där en aktiv [!DNL Workfront]-session är öppen.

**Listkontroller fungerar inte för rapporter på kontrollpaneler**

*Instrumentpaneler*

När en användare visar en rapport på en kontrollpanel och försöker ändra filtret, grupperingen eller vyn för rapporten ändras inte filtret, grupperingen eller vyn.

**[!UICONTROL You must be a system admin]-fel när ett projekt skapades**

*Projekt*

När en användare som inte är administratör försöker skapa ett projekt och bifogar ett anpassat formulär med ett avsnitt som bara är tillgängligt för administratörer, kan de inte skapa projektet och de ser följande fel:

[!UICONTROL You must be a system admin to change this custom data parameter value]

**Anpassade data bevaras inte vid konvertering av problem till projekt**

*Projekt*

När en användare konverterar ett ärende till ett projekt med hjälp av en mall överförs inte data från ett anpassat formulär i frågan till det jämförbara anpassade formuläret i projektet. Det här händer med data i anpassade fält som kan döljas baserat på värdena i andra anpassade fält.

**Fel vid konvertering av problem till projekt**

*Projekt*

När en användare försöker konvertera ett problem till ett projekt konverteras inte problemet och följande fel visas:

[!UICONTROL An unexpected error occurred]

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

I förhandsgranskningsmiljön har länkarna för kopiering och flyttning uppdaterats till [!UICONTROL Copy to] och [!UICONTROL Move to] både på utgivningssidan och i en utgivningslista.

**Lägg till upp till 45 IP-adresser i din [!DNL Workfront] tillåtelselista**

*Konfigurera*

Gränsen för antalet IP-adresser som läggs till i tillåtelselista [!DNL Workfront] har ökat från 30 till 45.

+++

+++**Underhållsuppdatering 20 januari 2022**

**[!UICONTROL Invalid Parameter]-fel vid skapande av projekt från mall**

*Projekt*

När en användare försöker skapa ett projekt från en mall och tar bort ett anpassat formulär från mallen när projektet skapas, skapas inte projektet och användaren ser ett [!UICONTROL Invalid Parameter]-felmeddelande som anger ett obligatoriskt fält i det borttagna anpassade formuläret.

**Användarlistan läses inte in i [!DNL Safari] webbläsare**

*Användare*

När en användare går till området [!UICONTROL Users] visas rubriken, men listan med användare läses inte in.

**Fördröjning vid dra uppgifter i en lista gör att aktiviteten flyttas till fel plats**

*Listor*

När en användare försöker flytta en uppgift i en lista genom att dra den, flyttas den blå raden som anger var uppgiften ska flyttas mycket långsammare än markören. När användaren släpper uppgiften flyttas den till den plats där den blå linjen finns, även om markören pekar på en annan plats i listan.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 14 januari 2022**

**Vissa mappade fält återställs när[!UICONTROL new field to map]** väljs

*[!DNL Workfront Fusion]*

När minst ett fält i modulerna [!DNL Workfront] [!UICONTROL Create] eller [!UICONTROL Update] har mappning aktiverat och en användare väljer ett nytt fält att mappa, förlorar de tidigare mappade fälten som är aktiverade mappningsvärden.

+++

+++**Underhållsuppdatering 13 januari 2022**

**Det går inte att lägga till en hyperlänk i en kommentar på sammanfattningspanelen**

*Uppgifter*

När en användare gör en kommentar på sammanfattningspanelen för en uppgift och försöker lägga till en hyperlänk till kommentaren, öppnas hyperlänksfönstret, men så fort användaren klickar i fönstret stängs det och användaren inte kan lägga till en hyperlänk. Om användaren tabbar in i fönstret kan han/hon skriva eller klistra in en länk i fältet, men hyperlänken sparas inte. I båda fallen avmarkeras uppgiften.

**Redigera teamsida stängs inte**

*Team*

När en användare försöker redigera ett team stängs inte sidan [!DNL Edit team]. Användaren kan inte stänga sidan genom att klicka på någon av knapparna, klicka på X:et eller navigera bort från sidan.

**E-post och meddelanden i programmet skickas inte**

*Meddelanden*

När en händelse som ska utlösa ett meddelande inträffar, skickas inte meddelandet. Detta kan inträffa för e-post eller meddelanden i appen och kan inträffa även om andra meddelanden skickas.

Listan **[!UICONTROL My Work]visas tom**

*[!UICONTROL My Work]*

När en användare visar sin [!UICONTROL My Work]-lista och layoutmallen för sin [!UICONTROL My Work]-lista innehåller ett numeriskt värde som [!UICONTROL Percent Complete], visas inte [!UICONTROL My Work]-listan.

**[!UICONTROL Percent Complete]och [!UICONTROL Hours Complete] kan inte ändras på Agile Board**

*Agile*

När en användare väljer [!UICONTROL Show more work items] på Agile Board och sedan försöker ändra [!UICONTROL Percent Complete] eller [!UICONTROL Hours Complete] för ett av de nya arbetsobjekten, kan de inte ändra Procent färdigt eller Timmar färdigt. Knappen [!UICONTROL Percent Complete] är också grå, vilket anger att den är inaktiv.

+++

+++**Underhållsuppdatering 6 januari 2022**

**[!UICONTROL Invalid Parameter]-fel vid koppling av mallar eller anpassade formulär till projekt**

*Projekt*

När en användare försöker bifoga ett anpassat formulär eller en mall till ett befintligt projekt, fyller i de obligatoriska fälten i det anpassade formuläret eller mallen och sparar ändringarna i projektet, sparas inte ändringarna och användaren ser ett [!UICONTROL Invalid Parameter]-fel högst upp på sidan med projektinformation.

**Korrekturkommentarer visas inte i dokumentuppdateringar**

*Korrektur*

När en användare visar ett korrektur i [!UICONTROL Documents]-området visas inte kommentarer som gjorts i själva korrekturet i dokumentets [!UICONTROL updates]-område.

**[!UICONTROL Workload Balancer]: [!UICONTROL ?[object Object]?] visas i överallokeringsinformation**

*[!UICONTROL Workload Balancer]*

Om en användare visas som överallokerad i [!UICONTROL Workload Balancer] på grund av en aktivitet som överlappar användarens tid av ledigt utrymme, och en annan användare visar sin överallokering, visas [!UICONTROL ?[object Object]?] i området [!UICONTROL Capacity] i överallokeringsinformationen i stället för användarens faktiska kapacitet.

+++

## Tidigare underhållsuppdateringar

Information om tidigare underhållsuppdateringar finns här:

* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2021](2021-updates.md)
