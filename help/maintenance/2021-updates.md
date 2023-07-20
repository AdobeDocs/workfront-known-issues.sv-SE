---
title: Workfront Maintenance Updates for 2021
description: Historik över underhållsuppdateringar för 2021 för [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
feature: Get Started with Workfront
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '8963'
ht-degree: 0%

---

# 2021 [!DNL Workfront] Underhållsuppdateringar

Följande underhållsuppdateringar gjordes 2021:

## Uppdateringar i december 2021

+++**Underhållsuppdatering 23 december 2021**

**Nya uppgifter får som standard en felaktig aktivitetsbegränsning**

_Uppgifter_

När en användare skapar en ny uppgift med[!UICONTROL New Task]&quot; och [!UICONTROL New Task Default Start] Datumalternativet är inställt på[!UICONTROL Today],&quot; ställs aktivitetsbegränsningen för den skapade uppgiften in på &quot;[!UICONTROL As soon as possible]&quot; istället för &quot;[!UICONTROL Start no earlier than].&quot; Detta kan också inträffa när du använder projektmallar.

**Öppningsschema i [!UICONTROL Groups] området leder till en tom sida**

_Inställningar_

När en användare visar grupper i [!UICONTROL Setup] och försöker öppna, redigera eller kopiera ett schema. Schemat öppnas inte och användaren ser en tom sida.

**Ändringarna visas inte när vänsternavigering ändras**

_Navigering_

När en användare försöker ändra ordningen på den vänstra navigeringspanelen genom att dra ett objekt, visas objektet på sin tidigare plats när användaren släpper det. Om användaren uppdaterar sidan visas den nya ordningen på den vänstra panelen.

**Länk för att skicka ett begärt dokument leder till en tom sida.**

_Dokument_

När en användare tar emot en begäran om att skicka ett dokument och klickar på länken till objektet där dokumentet begärdes, leder länken till en tom sida. Detta kan inträffa när du klickar på en länk i ett e-postmeddelande eller i ett meddelande i appen.

**[!UICONTROL Workload Balancer]visar 0 allokerade timmar**

_[!UICONTROL Workload Balancer]_

När en användare visar [!UICONTROL Workload Balancer] och har &quot;[!UICONTROL Show projected dates]&quot; aktiverad, alla datum i framtiden visas som 0 timmar.

**Korrektur försvinner ibland från mappar**

_[!DNL Workfront Proof]_

När en användare som är inloggad [!DNL Workfront Proof] visar en mapp och mappen visas tom. Om användaren checkar tillbaka senare visas korrektur.

+++

+++**Underhållsuppdatering 16 december 2021**

**Om du klickar på ett meddelande i meddelandelistan blir sidan tom**

_Meddelanden_

När en användare öppnar sin lista över meddelanden från [!UICONTROL Notifications] och sedan klickar på ett meddelande, de visas på en tom sida och meddelandet visas inte.

**Sammanfattningspanelen visar &quot;[!UICONTROL No selection]&quot; när aktiviteten har valts**

_Uppgifter_

När en användare öppnar en dokumentsammanfattning i [!UICONTROL Documents] i ett projekt, går sedan till uppgiftslistan, väljer en uppgift och försöker öppna uppgiftssammanfattningen, uppgiftssammanfattningen visas inte och användaren ser följande meddelande:

[!UICONTROL No selection. Select a document in the list to view details.]

I meddelandet omnämns dokument även om användaren finns i uppgiftslistan.

**[!UICONTROL Unassigned Work]läser inte in**

_[!UICONTROL Workload Balancer]_

När en användare i [!UICONTROL Workload Balancer] skapar ett filter med [!UICONTROL Assignment:Role ID] fält, [!UICONTROL Unassigned Work] området inte läses in.

**Koppla mall med &quot;[!UICONTROL Customize and attach]&quot; tar bort anpassade fältvärden**

_Projekt_

Om en användare kopplar en mall till ett projekt med hjälp av[!UICONTROL Customize and attach]&quot;, och projektet har redan ett anpassat formulär kopplat till sig, de anpassade fältvärdena överförs inte och måste anges manuellt igen. Detta inträffar även när mallen innehåller samma anpassade formulär.

+++

+++**Underhållsuppdatering (snabbkorrigering) 10 december 2021**

**[!UICONTROL Whoops]fel vid koppling av mall till befintligt projekt**

_Projekt_

När en användare försöker koppla en mall till ett befintligt projekt bifogas inte mallen och användaren ser följande fel:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

+++

+++**Underhållsuppdatering 9 december 2021**


**Den komprimerade vänstra navigeringspanelen utökas vid sidinläsning**

_Navigering_

När en användare har angett att den vänstra navigeringen ska komprimeras och sedan uppdateras en sida, expanderas den vänstra navigeringen på den nya sidan. Den vänstra navigeringen utökas också om användaren öppnar en sida på en ny flik.

**[!UICONTROL Workload Balancer]visar 0 allokerade timmar**

_[!UICONTROL Workload Balancer]_

När en användare visar [!UICONTROL Workload Balancer] och har &quot;[!UICONTROL Show projected dates]&quot; aktiverad, alla datum i framtiden visas som 0 timmar.

+++

+++**Underhållsuppdatering 8 december 2021**

**Godkännandet återställs när en uppdatering görs**

_Godkännanden_

Om en användare fattar ett beslut om ett godkännande med hjälp av objekthuvudet uppdateras objektet omedelbart, visas godkännandeikonerna i huvudet och godkännandebeslutet sparas inte.

**[!UICONTROL Cannot inline edit an assignment in a report]**

_Rapporter_

När en användare försöker att infoga ett uppdrag i en rapport ändras inte fältvärdet och redigeringen sparas inte.


+++

+++**Underhållsuppdatering 2 december 2021**

**Extra snedstreck läggs till när URL skrivs manuellt**

_Begäranden_

När en användare fyller i en begäran och börjar skriva in en URL manuellt, läggs ett extra snedstreck till i början av URL:en. Användaren kan inte ta bort snedstrecket.

**Det går inte att ta bort anpassade avsnitt från den vänstra navigeringspanelen**

_Navigering_

När en användare försöker ta bort ett anpassat avsnitt från den vänstra navigeringspanelen genom att klicka på X bredvid avsnittet, tas inte avsnittet bort.

**Ej tilldelat arbete läses inte in**

_[!UICONTROL Workload Balancer]_

När en användare i [!UICONTROL Workload Balancer] skapar ett filter med [!UICONTROL Assignment:Role ID] fält, [!UICONTROL Unassigned Work] området inte läses in.

**Sidor som inte läses in i vissa webbläsare**

_[!DNL Workfront]_

När en användare arbetar i [!DNL Workfront], sidor läses inte in och användaren ser följande felmeddelande:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Detta har rapporterats i

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Felet inträffar slumpmässigt och kan påverka alla delar av [!DNL Workfront].

+++


## Uppdateringar i november 2021

+++**Underhållsuppdatering 18 november 2021**

**[!DNL Workfront]for [!DNL Jira] &quot;[!UICONTROL Invalid clientID or clientSecret]&quot; fel vid inloggning**

_Workfront integreringar_

Användare har loggats ut från [!DNL Jira] för integrering med Workfront. När en användare försöker logga in på [!DNL Workfront for Jira] integreringen kan de inte logga in och följande fel visas:

&quot;[!UICONTROL Invalid clientID or clientSecret]&quot;

**Anpassat formulär som är kopplat till begäran uppdateras inte när ett nytt ämne i kön väljs**

_Begäranden_

När en användare skapar en begäran och väljer ett köämne som automatiskt kopplar ett anpassat formulär till begäran och sedan väljer ett annat köämne, förblir det anpassade formuläret från det första köämnet kopplat till begäran.

**Ikonerna visas felaktigt**

_[!DNL Workfront]_

Ikonbilderna visas felaktigt. Detta har rapporterats i många områden över hela världen [!UICONTROL Workfront].

**Aktiviteter exporteras inte till PDF när alternativet &quot;Andra storlekar&quot; är markerat.**

_Uppgifter_

Om en användare försöker exportera en uppgiftslista till PDF och väljer&quot;[!UICONTROL Other Sizes]&quot; kan de välja en storlek och klicka på [!UICONTROL Export], men listan exporteras inte. Det finns inget felmeddelande och inget annat som tyder på att exporten misslyckades.

**Bildindikatorn visas inte i e-postmeddelanden**

_Meddelanden_

När en användare lägger till en bild i en uppdatering och ett e-postmeddelande skickas till mottagaren av uppdateringen, innehåller e-postmeddelandet ingen indikator på att det finns en bild i uppdateringen.

**Sidor som inte läses in i vissa webbläsare**

_[!DNL Workfront]_

När en användare arbetar i [!DNL Workfront], sidor läses inte in och användaren ser följande felmeddelande:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Detta har rapporterats i

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Felet inträffar slumpmässigt och kan påverka alla delar av Workfront.

+++

+++**Underhållsuppdatering 11 november 2021**

**Problem med dokumentintegreringar, tom sida vid popup-fönster för dokumentöverföring från[!DNL Google Drive*]*

_Dokument_

När en användare försöker lägga till ett nytt dokument i [!DNL Workfront] från [!DNL Google Drive] genom att använda [!UICONTROL Add New] >[!UICONTROL From [!DNL Google Drive]]är popup-skärmen för överföring tom.

**Det går inte att använda mer än ett filter i Utjämning av arbetsbelastning**

_[!UICONTROL Workload Balancer]_

När en användare försöker använda mer än ett filter i [!UICONTROL Workload Balancer]ser de följande problem:

* Om användaren väljer två filter tillämpas bara det undre filtret.
* Om användaren väljer mer än två filter visas inga resultat.

**&quot;[!UICONTROL Project Folders]&quot; dokumenthuvudet saknas i projektdokumentområdet**

_Projekt_

När en användare är i ett projekt och visar projektdokumenten, rubriken[!UICONTROL Project Folders]&quot; saknas i den vänstra navigeringen. Pilen finns fortfarande kvar och användaren kan välja en mapp.

**Kolumner på Kanban-tavlan är för breda och kan inte justeras**

_Agile_

När en användare visar en Kanban-panel med flera kolumner är kolumnerna för breda och användaren måste rulla för att visa eller flytta kort till kolumnerna längst till höger. Kolumnbredderna kan inte justeras, så användaren kan inte göra kolumnerna mindre så att alla är synliga på skärmen samtidigt.

**Förbättrat gränssnitt för att skapa ett nytt team**

_Team_

Att skapa team är nu mer intuitivt med nya visuella ledtrådar. När du väljer [!UICONTROL Switch Teams] -ikonen på valfri gruppsida, [!UICONTROL Create New Team] länken har en ikon som anger &quot;[!UICONTROL new],&quot; och länken separeras från resten av listan så att den inte ser ut som ett teamnamn. Det här gränssnittet är detsamma för både flexibla och icke-flexibla team.

+++

+++**Underhållsuppdatering 4 november 2021**

**Nya uppgifter får som standard en felaktig aktivitetsbegränsning**

_Uppgifter_

När en användare skapar en ny uppgift med[!UICONTROL New Task]&quot; och alternativet Nytt uppgifts standardstartdatum är inställt på &quot;[!UICONTROL Today],&quot; ställs aktivitetsbegränsningen för den skapade uppgiften in på &quot;[!UICONTROL As soon as possible]&quot; istället för &quot;[!UICONTROL Start no earlier than].&quot;

**Fält visas inte på Agile-artikelkort**

_Agile_

När en användare tittar på ett Agile-storyboard visas endast [!UICONTROL Description] och [!UICONTROL Status] fält. Andra fält, inklusive anpassade fält, visas inte.

**Kort återgår till den ursprungliga kolumnen innan de flyttas till den nya kolumnen**

_Agile_

När en användare drar ett kort till en ny kolumn på storyboard kan användaren se kortet som dras. När användaren släpper kortet i den nya kolumnen visas kortet kort i den ursprungliga kolumnen innan det visas i den nya kolumnen.

**Värden som inte är tillgängliga för anpassade fält i filter**

_[!UICONTROL Workload Balancer]_

När en användare försöker skapa ett filter med hjälp av ett anpassat fält visas inte värdet för det anpassade fältet och kan inte anges i filtret.

**Sidor läses inte in i [!DNL Firefox] webbläsare**

_[!DNL Workfront]_

När en användare arbetar i [!DNL Workfront] med [!DNL Firefox] webbläsare, sidorna läses inte in och användaren ser följande felmeddelande:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Felet inträffar slumpmässigt och kan påverka alla delar av [!DNL Workfront].

**Datumrelaterat fel när projekt skapas från mall.**

_Mallar_

Om en användare skapar ett projekt från en mall och ställer in schemaläggningsläget på [!UICONTROL Start Date]väljer sedan en uppgiftsbegränsning. När användaren försöker skapa projektet skapas inte projektet och användaren ser ett felmeddelande baserat på uppgiftsbegränsningen.

**[!UICONTROL Export Gantt Chart]dialogrutan svarar inte**

_Gantt-schema_

Om en användare befinner sig på den nya [!DNL Workfront] försök att exportera [!UICONTROL Gantt Chart] och väljer &quot;[!UICONTROL What I See]&quot;, [!UICONTROL Gantt Chart] exporterar inte och dialogrutan svarar inte. Användaren kan inte stänga eller klicka utanför dialogrutan.

**Ikonerna visas felaktigt**

_[!DNL Workfront]_

Ikonbilderna visas felaktigt. Detta har rapporterats i följande fall:

* Bilder för jobbroller eller grupper när ett objekt delas
* Vänster- och högerikoner i kalenderrapporter
* Sorteringsikoner i rapportkolumner

**Lägg till kryssrutor i Förfrågningar i [!UICONTROL Submitted] i [!UICONTROL Requests] area**

_Begäranden_

Vi har lagt till kryssrutor till vänster om namnen på förfrågningarna i [!UICONTROL Submitted list] i [!UICONTROL Requests] område. Detta gör det enklare att markera en begäran och visa ytterligare information.

**Anpassade kvartal stöds nu i filtren för belastningsfördelning**

_[!UICONTROL Workload Balancer]_

Filtren i [!UICONTROL Workload Balancer] har nu stöd för anpassade kvartal.

**Uppdaterad filteroperator för fältet Varaktighet i filtren för belastningsutjämnare**

_[!UICONTROL Workload Balancer]_

Filteroperatorerna har uppdaterats vid filtrering av [!UICONTROL Workload Balancer] områden efter [!UICONTROL Duration].

+++


## Uppdateringar i oktober 2021

+++**Underhållsuppdatering 28 oktober 2021**

**[!UICONTROL Home]och [!UICONTROL My Work] visa tom sida**

_[!UICONTROL Home]/[!UICONTROL My Work]_

När en användare navigerar till [!UICONTROL Home] eller Mitt arbete visas sidan som tom.

**Kan inte visa eller redigera [!UICONTROL Topic Group] information**

_Begäranden_

När en användare försöker visa eller redigera informationen för en ämnesgrupp visas &quot;[!UICONTROL Topic Group Detail]&quot; i rubriken, men är annars tom

**Tomma obligatoriska alternativknappar fylls i automatiskt**

_Begäranden_

När en användare skickar en begäran med ett obligatoriskt alternativknappsfält och användaren inte har valt ett värde för det fältet innan begäran skickas, väljs det första värdet automatiskt när begäran skickas.

+++

+++**Underhållsuppdatering 21 oktober 2021**

**Kan inte lägga till ett filter i[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

När en användare i [!UICONTROL Workload Balancer] försöker lägga till ett filter, [!UICONTROL Add filter] Panelen öppnas, men innehållet på panelen läses inte in och användaren kan inte lägga till filtret.

**Agile Scrum board visar inte artiklar**

_Agile_

När en användare försöker visa Scrum board i ett teams iteration, visas trumman som tom.

**Krusningsrutan är tom när filter används**

_Agile_

När en användare försöker visa ett Scrum-artikelkort med något filter förutom &quot;[!UICONTROL All Team]&quot; visas en tom skärm. Användaren kan inte växla tillbaka till[!UICONTROL All Team]&quot;.

**Listor visas bara på ett litet område på skärmen**

_Listor_

När en användare försöker visa en lista medan han/hon använder en [!DNL Safari] webbläsare på en [!DNL Mac] med [!DNL Big Sur OS]visas listan bara på ett litet område på skärmen. Användaren kan bläddra igenom listan, men området kan vara så litet att listan är svår eller omöjlig att läsa.

**Tomma obligatoriska alternativknappar fylls i automatiskt**

_Begäranden_

När en användare skickar en begäran med ett obligatoriskt alternativknappsfält och användaren inte har valt ett värde för det fältet innan begäran skickas, väljs det första värdet automatiskt när begäran skickas.

+++

+++**Underhållsuppdatering (snabbkorrigering) 21 oktober 2021**

**[!UICONTROL Home]och [!UICONTROL My Work] visa tom sida**

_[!UICONTROL Home]/[!UICONTROL My Work]_

När en användare navigerar till [!UICONTROL Home] eller [!UICONTROL My Work]visas sidan som tom.

+++

+++**Underhållsuppdatering 20 oktober 2021**

**[!UICONTROL Workload Balancer]ange som standardalternativ för schemaläggning**

_[!UICONTROL Workload Balancer]_

Om en användare har [!UICONTROL Scheduler] om standardinställningen används ser de att [!UICONTROL Workload Balancer] har angetts som standard.

+++

+++**Underhållsuppdatering (snabbkorrigering) 19 oktober 2021**

**Det går inte att tilldela en begäran när den skapas**

_Begäranden_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen skapar en begäran och försöker tilldela en användare genom att skriva sitt namn i [!UICONTROL Assignments] fältet visar inte fältet den nedrullningsbara listan och användaren kan inte välja namnet på den som tilldelats.

**Krusningsrutan är tom när filter används**

_Agile_

När en användare försöker visa ett Scrum-artikelkort med något filter förutom &quot;[!UICONTROL All Team]&quot; visas en tom skärm. Användaren kan inte växla tillbaka till[!UICONTROL All Team]&quot;.

+++

+++**Underhållsuppdatering 14 oktober 2021**

**Mallar som delas över hela systemet visas inte**

_Mallar_

När en användare skapar ett projekt och försöker använda en mall som har delats av hela systemet, kan användaren inte se mallen i listan över tillgängliga mallar och kan inte använda mallen.

**Fel när projekt skapades från mallar**

_Mallar_

När en användare försöker skapa ett projekt från en mall som innehåller ett anpassat formulär med ett avsnitt som bara är synligt för administratörer, kan användaren inte skapa projektet och följande meddelande visas:

&quot;[!UICONTROL Category with primary key value(s) "xxxxxxxxxxxxxxxx" not found]&quot;

**Uppdaterade länkar för kopiering och flyttning av uppgifter**

_Uppgifter_

Länkarna för kopiering och flyttning av uppgifter har uppdaterats till[!UICONTROL Copy to]&quot; och &quot;[!UICONTROL Move to]&quot; både på uppgiftssidan och i en uppgiftslista.

**Ta bort gräns för jobbrollssökning när faktureringssatser åsidosätts för ett projekt**

Jobbroller

OBS! Den här uppdateringen finns för närvarande i förhandsvisningsmiljön och kommer att finnas i Production i version 2.1 av Production. Mer information finns i&quot;Versionsöversikt 2.1&quot;.

Om du åsidosätter faktureringsfrekvenser för jobbroller i ett projekt söks nu alla jobbroller i systemet igenom.

Tidigare [!DNL Workfront] sökte efter jobbroller i de första 2000 rollerna i alfabetisk ordning.

+++

+++**Underhållsuppdatering 7 oktober 2021**

**[!UICONTROL In-app notifications disappear from]meddelandecenter**

_Meddelanden_

När en användare tittar på meddelandecentret visas inte längre några tidigare synliga meddelanden. I vissa fall kan meddelandet försvinna innan användaren ser det.

**Meddelanden visas inte på [!UICONTROL All Announcements] page**

_Meddelanden_

När en användare öppnar [!UICONTROL All Announcements] sidan från [!UICONTROL Notifications] området, det finns inga meddelanden som visas inom följande områden:

* [!UICONTROL Inbox]
* [!UICONTROL Favorites]
* [!UICONTROL Drafts]
* [!UICONTROL Deleted]

**Fel vid tilldelning i[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

När en användare försöker göra en tilldelning från [!UICONTROL Workload Balancer], blir arbetet inte tilldelat och användaren ser följande fel:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

+++


## Uppdateringar i september 2021

+++**Underhållsuppdatering 30 september 2021**

**Fel vid navigering snabbt till eller från[!UICONTROL Home]**

_Startsida_

När en användare snabbt navigerar till eller från [!UICONTROL Home], sidan läses inte in och användaren ser följande fel:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

Detta kan också inträffa vid navigering till [!UICONTROL Home] via ett stift.

+++

+++**Underhållsuppdatering 23 september 2021**

**[!UICONTROL Access Denied]fel vid visning av biljetter som skickats till[!DNL Workfront]**

_Problem_

När en användare har skickat in en biljett till [!DNL Workfront] och försöker visa biljetten visas följande fel:

&quot;[!UICONTROL Access Denied: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**Affärsärendesammanfattning visar felaktiga värden**

_Projekt_

När en användare tittar på [!UICONTROL Business Case] sammanfattningspanelen, de värden som visas återspeglar inte värdena i den enskilda [!UICONTROL Business Case] -avsnitt.

**Kolumnrubriker passar inte ihop med kolumner i listor**

_Inställningar_

När en användare finns i [!UICONTROL Setup] område och visar en lista, t.ex. [!UICONTROL Custom Forms] eller [!UICONTROL Access Levels]kolumnrubrikerna för den listan motsvarar inte kolumnerna i listan.

**Användare utan rätt delningsbehörighet kan bifoga anpassade formulär till objekt**

_Anpassad Forms_

När ett anpassat formulär finns i det nya [!DNL Adobe Workfront] upplevelsen är inställd på att vara synlig i hela systemet. Alla användare kan bifoga det här anpassade formuläret till ett objekt. De bör dock bara kunna visa det anpassade formuläret och inte kunna bifoga det till ett objekt om det inte har delats specifikt med dem.

+++

+++**Underhållsuppdatering 16 september 2021**

**Kan inte redigera grupper**

_Grupper_

När en användare försöker redigera eller ta bort en grupp, redigeras eller tas inte gruppen bort och användaren ser följande meddelande:

&quot;[!UICONTROL Let's try that again. Group with primary key value(s) "(Group's ID)" not found]&quot;

**[!UICONTROL Portfolio Optimizer]inte visa projekt**

_Portfolio_

När en användare försöker visa projekt i [!UICONTROL Portfolio Optimizer], visas inte projektlistan och användaren kan därför inte interagera med projekten.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 10 september 2021**

**Datum och tid markerat som UTC vid redigering**

_Listor_

När en användare redigerar ett datum eller en tid textbundet (i en lista med objekt) markeras datumet och tiden som UTC. Datum och tid har inte angetts i UTC i [!DNL Workfront]. Det här problemet påverkar bara visningen, inte själva informationen.

**Textfärgen visas inte korrekt när villkorsstyrd formatering används**

_Rapporter_

När en användare visar en rapport med villkorsstyrd formatering som ändrar textfärgen, visas textfärgen som oförändrad.

+++

+++**Underhållsuppdatering 9 september 2021**

**Problem visar inte någon probleminformation**

_Startsida_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen väljer ett problem i [!UICONTROL Work List]visas vissa fält som om de inte har några värden. Om du navigerar till problemet och visar [!UICONTROL Issue Details]har dessa fält värden.

**Användarna behöver Contribute-behörighet för att kunna se [!UICONTROL Approvals] i nya Workfront Experience**

_Godkännanden_

Användare behöver [!UICONTROL Contribute] behörigheter för ett objekt för att visa [!UICONTROL Approvals] i det nya [!DNL Workfront] Upplevelse. De behöver bara [!UICONTROL View] behörighet att visa [!UICONTROL Approvals] när det finns en godkännandeprocess för objektet.

**[!UICONTROL Whoops]fel när filter används**

_Listor_

När en användare försöker använda något av följande filter:

* [!UICONTROL All Projects]
* [!UICONTROL Projects I'm On]
* [!UICONTROL My Current Tasks]

listan blir tom och användaren ser följande fel:

&quot;[!UICONTROL Let's try that again.]&quot;

**[!UICONTROL Tasks]går tomt när du redigerar textbundet**

_Mallar_

När en användare försöker infoga redigeringsåtgärder i en mall med hjälp av en vy som innehåller[!UICONTROL Assign To: Name]&quot; och uppdraget innehåller en användare, [!UICONTROL Tasks] -avsnittet blir tomt och användaren kan inte redigera malluppgifterna.

**Kan inte exportera[!UICONTROL Portfolio Optimizer]**

_Portfolio_

När en användare försöker exportera [!UICONTROL Portfolio Optimizer] och klickar på något av exportalternativen, [!UICONTROL Portfolio Optimizer] exporterar inte.

**Inga meddelanden skickas för svar**

_Meddelanden_

När en användare svarar på en uppdatering i [!DNL Workfront], får inte andra användare i kommentarstråden meddelanden.

**Ändringar av anpassade data orsakar fördröjning**

_Anpassade fält_

När en användare ändrar anpassade data som utlöser ändringar av andra visade data, läses ändringarna in långsamt.

**Gruppering[!UICONTROL Collapse or Expand All]&quot; visas inte ikonen**

_Rapportering_

The &quot;[!UICONTROL Collapse or Expand All]&quot; visas inte i huvudet i en lista eller rapport när grupperingar används i listan eller rapporten.

**[!UICONTROL Check]och [!UICONTROL Cancel] alternativ som inte visas när uppgiftstilldelningar ändras**

_[!UICONTROL Workload Balancer]_

När en användare försöker ändra uppgiftstilldelningen för en uppgift och tidsramen för den uppgiften sträcker sig till eller utanför kanten av den synliga sidan, [!UICONTROL Check] och [!UICONTROL Cancel] är inte synliga och användaren kan inte spara eller avbryta allokeringsändringarna.

**Lägga till ett anpassat fält i [!UICONTROL Home] orsakar att fältdata saknas**

_[!UICONTROL Home]_

När ett anpassat fält läggs till i [!UICONTROL Home], andra fält börjar att saknas och visas felaktigt.

**Det går inte att visa länkade objekt när de är inloggade som en annan användare**

_Integreringar_

Om en administratör försökte visa länkade objekt från en extern leverantör när han var inloggad som en annan användare, kunde han/hon inte öppna de länkade mapparna och kunde inte visa objekten.

+++

+++**Underhållsuppdatering 2 september 2021**

**Kan inte fästa anpassad instrumentpanel**

_Kontrollpaneler_

När en användare försöker fästa en anpassad kontrollpanel fästs inte instrumentpanelen och användaren ser följande fel:

&quot;[!UICONTROL Something went wrong while pinning. Please contact [!DNL Workfront] so we can fix this.]&quot;

**[!DNL Workfront Proof]utskriftssammanfattning är tom**

[!DNL Workfront Proof]

När en användare öppnar utskriftssammanfattningen för att skriva ut ett korrektur visas rubriken, men själva sammanfattningen är tom.

+++


## Uppdateringar i augusti 2021

+++**Underhållsuppdatering 26 augusti 2021**

**I [!DNL Safari] det finns en mörkgrå bakgrund i kolumnrubriker**

_Listor_

I [!DNL Safari] webbläsare, det finns en mörkgrå bakgrund i kolumnrubriker som markerar texten. Detta är inte något problem med andra webbläsare som stöds.

**Oväntat fel vid inställning av föregångare**

_Uppgifter_

När en användare försöker ange en aktivitet som en föregångare med hjälp av en infogad redigering, ställs föregående aktivitet inte in och användaren ser följande meddelande:

&quot;[!UICONTROL An unexpected error happened]&quot;

+++

+++**Underhållsuppdatering 19 augusti 2021**

**Sparade filter saknas efter att du har valt ett filter som inte visar några problem**

_Listor_

Sparade filter saknas i en lista med problem efter att du har valt ett filter som inte visar några resultat.

**Problem visar inte någon probleminformation**

_[!UICONTROL Home]sammanfattning_

När en användare [!DNL Adobe Workfront Classic] väljer ett problem i dialogrutan [!UICONTROL Work List]visas vissa fält som om de inte har några värden. Om du navigerar till problemet och visar [!UICONTROL Issue Details]har dessa fält värden.

+++

+++**Underhållsuppdatering 12 augusti 2021**

**Det går inte att anpassa en flexibel vy i ett projekt**

_Agile_

När en användare försöker anpassa en tidigare flexibel vy i ett projekt stängs fönstret och användaren kan inte redigera vyn.

**Namnet ändras inte för nya dokumentversioner**

_Dokument_

När en användare överför en ny version av ett dokument uppdateras inte dokumentnamnet så att det matchar den senaste versionens namn.

**Föregående ikon blir inte grön när föregångaren är klar.**

_Uppgifter_

När en aktivitet har en föregående aktivitet och den föregående aktiviteten är slutförd, blir ikonen för föregående aktivitet inte grön.

När ett anpassat formulär finns i det nya [!DNL Adobe Workfront] upplevelsen är inställd på att vara synlig i hela systemet. Alla användare kan bifoga det här anpassade formuläret till ett objekt. De bör dock bara kunna visa det anpassade formuläret och inte kunna bifoga det till ett objekt om det inte har delats specifikt med dem.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 6 augusti 2021**

**Det går inte att välja kalendrar i [!DNL Outloo]k Kalenderinställningar**

_Startsida_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen visar [!DNL Outlook] Kalendern hemma, och inställningarna öppnas, kryssrutorna för att välja kalendrar saknas. Om användaren klickar på var kryssrutan skulle vara svarar kalendern som om kryssrutan var där.

**Det går inte att omauktorisera eller verifiera anslutningen till[!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] användare med scenarier som ansluter till [!UICONTROL Webdam] bör vara medveten om att [!UICONTROL Webdam] anslutningar kräver manuell autentisering var 14:e dag. The [!UICONTROL Webdam] API har för närvarande inte stöd för automatisk omauktorisering.

+++

+++**Underhållsuppdatering 5 augusti 2021**

**Det går inte att interagera med dokumentet i [!UICONTROL Summary panel] eller [!UICONTROL More] meny**

_Dokument_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen visar ett dokument och försöker göra ett val i [!UICONTROL Summary panel] eller [!UICONTROL More] -menyn avmarkeras dokumentet, vilket orsakar [!UICONTROL Summary panel] eller [!UICONTROL More] för att gå tom.

**[!UICONTROL New Request]knapp saknas**

_Begäranden_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen går till [!UICONTROL Requests] sidan, [!UICONTROL New Request] knappen visas inte och kan inte skicka en begäran.

**Användare utan rätt delningsbehörighet kan bifoga anpassade formulär till objekt**

_Anpassad Forms_

När ett anpassat formulär finns i det nya [!DNL Adobe Workfront] upplevelsen är inställd på att vara synlig i hela systemet. Alla användare kan bifoga det här anpassade formuläret till ett objekt. De bör dock bara kunna visa det anpassade formuläret och inte kunna bifoga det till ett objekt om det inte har delats specifikt med dem.

**Det går inte att ändra korrekturinställningar när ett nytt korrektur skapas**

_[!DNL Workfront Proof]_

När en användare skapar ett nytt korrektur och försöker ändra inställningarna, återställs inställningen till en tidigare inställning.

**[!UICONTROL Story Board]inte läses in korrekt**

_Agile_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen navigerar till en [!UICONTROL Story Board]kan det ta upp till 10 sekunder att läsa in kortet. Förseningen med inläsningen beror på att systemet läser in alla kort när det bara ska läsa in 50 kort åt gången.

+++


## Uppdateringar i juli 2021

+++**Underhållsuppdatering (snabbkorrigering) den 29 juli 2021**

**Det gick inte att överföra nytt korrektur eller ny korrekturversion**

_[!DNL Workfront Proof]_

När en användare försöker överföra ett nytt korrektur eller en ny version av ett korrektur i den klassiska [!DNL Workfront] den nya korrektursidan eller sidan med nya versioner är tom och användaren kan inte ladda upp korrekturet eller versionen.

+++

+++**Underhållsuppdatering 29 juli 2021**

**[!UICONTROL Proof Activity]och [!UICONTROL Proof Viewer Settings] sidor alltid tillgängliga**

_[!DNL Workfront Proof]_

The [!UICONTROL Proof Activity] och [!UICONTROL Proof Viewer] Inställningssidorna visas nu alltid, även om användaren inte har tillgång till att uppdatera sidorna.

När en användare med en anpassad behörighetsprofil för korrektur navigerade till ett dokument har [!UICONTROL Proof Activity] och [!UICONTROL Proof Viewer Settings] sidor till vänster inte alltid var synliga.

**Felmeddelande vid användning [!UICONTROL Percentage] alternativ för[!UICONTROL Allocated hours]**

_[!UICONTROL Workload Balancer]_

När en användare väljer [!UICONTROL Percentage] alternativ för [!UICONTROL Allocated hours], och det finns arbeten listade i [!UICONTROL Unassigned work] visas följande fel:

&quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

+++

+++**Underhållsuppdatering 22 juli 2021**

**Nya namn på korrekturversioner har klippts av**

_[!DNL Workfront Proof]_

När en användare [!DNL Adobe Workfront Classic] överför en ny version av ett korrektur som innehåller en punkt i filnamnet. Filnamnet stängs av vid slutet.

+++

+++**Underhållsuppdatering (snabbkorrigering) 19 juli 2021**

**Fel vid navigering till projekt, tidrapporter, uppgifter eller program**

I nya [!DNL Adobe Workfront] när en användare försöker navigera till projekt, tidrapporter, uppgifter eller program visas felmeddelandet &quot;[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

+++

+++**Underhållsuppdatering 15 juli 2021**

**Standardprioritet för nya begäranden är felaktig**

_Begäranden_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen skapar en begäran, begäran uppfyller inte standardprioriteten som anges i [!UICONTROL Project Preferences] och de kan inte justera prioriteten innan de skickar in begäran.

**[!UICONTROL Go to proof]länken leder inte till kommentaren**

_E-postmeddelanden_

När en användare får ett e-postmeddelande om en korrekturkommentar klickar han/hon [!UICONTROL Go to proof], dirigeras de till fel kommentar i korrekturet eller så dirigeras de inte till någon kommentar alls.

**RTF-fältvärden som inte överförs efter konvertering av en utgåva till en uppgift**

_Anpassad Forms_

När en användare konverterar en utgåva till en uppgift och utgåvan har ett bifogat anpassat formulär med ett värde som anges i ett textfält med formatering av RTF, överförs inte värdet i textfältet efter konverteringen.

**Anpassade fältvärden ändras efter markering**

_[!DNL Workfront Proof]_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen skapar ett nytt korrektur och anger ett värde i vissa anpassade fält på ett korrektur. Värdet i vissa tidigare fält återställs till standardvärdena i stället för det värde användaren angav.

**[!UICONTROL Assign to]skrivhuvud fungerar inte**

_[!UICONTROL Home]_

När en användare [!DNL Adobe Workfront Classic] skapar ett projekt, en uppgift eller en förfrågan från [!UICONTROL Home] område, [!UICONTROL Assign to] typsnittsfältet fyller inte i användarnamn.

**Felaktig avrundning av timmar**

_Tidrapporter_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen navigerar till [!UICONTROL Timesheets] > [!UICONTROL All Timesheets]ser de att det totala antalet timmar för vissa tidrapporter avrundas till en decimal i stället för i steg om 0,25, men att det totala antalet timmar visas korrekt i den enskilda tidrapporten. I området Alla tidrapporter visar till exempel en tidrapport totalt 44,8 timmar, men när du öppnar tidrapporten visas totalt 44,75 timmar.

**Det går inte att delegera godkännanden**

_[!UICONTROL Home]_

När en användare [!DNL Adobe Workfront Classic] klickningar [!UICONTROL Delegate My Approvals] i [!UICONTROL Home] och de börjar skriva namnet på den användare som de försöker delegera till, inga resultat visas i [!UICONTROL typeahead] och de kan inte välja en användare.

**[!UICONTROL Gantt Chart]vyn är inte tillgänglig för aktivitetsrapporter**

_Rapporter_

OBS! Detta påverkar även projektrapporter.

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen öppnar en uppgiftsrapport, där du kan välja en [!UICONTROL Gantt Chart] vy saknas i rapportverktygsfältet. Om [!UICONTROL Gantt Chart] är markerat att visas som standard i rapporten. I stället visas ett listformat.

**Klicka [!UICONTROL See More] i rapporten inte läser in något**

_Kontrollpaneler_

När en användare befinner sig på den nya [!DNL Adobe Workfront] en rapport visas på en kontrollpanel och de klickar på [!UICONTROL See More] händer ingenting och de kan inte visa alla objekt i rapporten.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 1 juli 2021**

**Kopiering av moduler fungerar inte**

_[!DNL Adobe Workfront Fusion]_

När en användare markerar flera moduler och försöker kopiera och klistra in dem, klistras inte modulerna in.

+++

+++**Underhållsuppdatering 1 juli 2021**

**Färguppsättningen för kort respekteras inte**

_Kanban_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen anger specifika kortfärger i teaminställningarna. Färgerna återspeglas inte på Kanban-korten.

**Det går inte att klistra in text i det anpassade meddelandefältet**

_[!DNL Workfront Proof]_

När en användare skapar ett nytt korrektur i [!UICONTROL Web Proofing Viewer] och de försöker klistra in text i [!UICONTROL Message] i [!UICONTROL Email notification] kan de inte klistra in texten. Det här händer bara när texten har styckeformatering och det finns en styckebrytning.

**Begäranden har skickats med tomma obligatoriska fält**

_Begäranden_

När en användare gör en begäran och skickar den, skickas ingen information i obligatoriska fält tillsammans med begäran.

**[!UICONTROL New Request]knapp saknas**

_Begäranden_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen går till [!UICONTROL Requests] sidan, [!UICONTROL New Request] knappen visas inte och kan inte skicka en begäran.

**Ett fel uppstod när ett anpassat formulär skulle expanderas**

_Projekt_

När en användare befinner sig på den nya [!DNL Adobe Workfront] försök görs att expandera ett anpassat formulär som är kopplat till ett projekt. De kan inte öppna det anpassade formuläret och se felmeddelandet &quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot; Att uppdatera sidan löser inte problemet.

**[!DNL Adobe Workfront]branding visas nu i e-postmeddelanden från annonscenter**

E-post

Som [!DNL Adobe Workfront] branding introduceras i hela programmet. Följande uppdateringar har gjorts i e-postmeddelanden från annonscenter:

* The [!DNL Adobe Workfront] leon lades till i huvudinnehållsområdet.
* The [!DNL Adobe Workfront] logotypen lades till i sidfoten.

I framtiden kommer den här profileringen att visas på fler typer av e-postmeddelanden från Workfront.

+++


## Uppdateringar i juni 2021

+++**Underhållsuppdatering 24 juni 2021**

**Det går inte att redigera ett team**

_Agile_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelseklickningar [!UICONTROL Edit] för att öppna [!DNL Edit] Teamsida för ett Agile-team, sidan läses in från början, inställningarna försvinner och den blir tom.

**Data har tagits bort från skickad begäran**

_Begäranden_

När en användare befinner sig på den nya [!DNL Adobe Workfront] När en begäran fylls i, saknar den skickade begäran de angivna värdena för vissa anpassade fält, ibland även fält som är obligatoriska.

**Kolumner visas inte**

_Kanban_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen lägger till en skräddarsydd [!UICONTROL Additional Fields] kolumn till en Kanban-styrelse, alla kolumnrubriker visas inte längre i styrelsen.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 23 juni 2021**

**Borttagen bruten länk i e-postmeddelanden**

_[!DNL Adobe Workfront Fusion]_

Vi har tagit bort länken till meddelandeinställningarna från [!DNL Adobe Workfront Fusion] meddelanden via e-post.
Mer information om hur du ändrar meddelandeinställningar finns i [!DNL Adobe Workfront Fusion] organisationer och team.

+++

+++**Underhållsuppdatering 17 juni 2021**

**[!UICONTROL Gantt Chart]vyn är inte tillgänglig för aktivitetsrapporten**

_Rapporter_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen öppnar en uppgiftsrapport, där du kan välja en [!UICONTROL Gantt Chart] vy saknas i rapportverktygsfältet. Om [!UICONTROL Gantt Chart] är markerat att visas som standard i rapporten. I stället visas ett listformat.

**Teckenbegränsningsfel uppstår inte vid inskickade begäranden**

_Begäranden_

När en användare befinner sig på den nya [!DNL Adobe Workfront] försök att skicka en begäran och de överskrider teckengränsen för ett fält, de kan inte skicka begäran och inget felmeddelande visas. I [!DNL Adobe Workfront Classic]visas varningen[!UICONTROL [number] characters over" and when they attempt to submit the request, they see the error message "Please check the following: Please enter no more than 2000 characters (you entered [number] characters).]&quot;

+++

+++**Underhållsuppdatering 10 juni 2021**

**Ordnade malluppgifter flyttas inte**

_Mallar_

När en användare befinner sig på den nya [!DNL Adobe Workfront] funktionen drar en malluppgift till en ny plats i en lista, antalet malluppgifter uppdateras, men ordningen ändras inte.

**Underordnade aktiviteter har inte markerats med överordnade uppgifter**

_Mallar_

När en användare väljer en överordnad uppgift i ett projekt som skapats från en mall markeras inte de underordnade uppgifterna automatiskt.

**Alla milstolpar för infogad redigering visas i en uppgiftslista**

_Projekt_

När ett projekt har en milstolpe som lagts till i det och en användare i det nya [!DNL Adobe Workfront] redigerar [!UICONTROL Milestone: Name] kolumn i uppgiftslistan visas alla milstolpesökvägar i den nedrullningsbara menyn, i stället för bara de milstolpesökvägar som har kopplats till det projektet.

+++

+++**Underhållsuppdatering 3 juni 2021**

**Fråga gör att sidan skakas**

_Rapporter_

När en användare befinner sig på den nya [!DNL Adobe Workfront] Experience kör en rapport med en uppmaning, kolumnerna i rapporten flyttas snabbt från vänster till höger.

**Vissa fraser på [!UICONTROL New proof] sidan är inte korrekt översatt**

_[!DNL Workfront Proof]_

När en användare navigerar till [!UICONTROL New proof creation] sida in [!DNL Workfront Proof] och innehållet översätts till ett annat språk än engelska, visas vissa fraser fortfarande på engelska.

**Inaktiverade och borttagna etiketter har lagts till för användare[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Deactivated] och [!UICONTROL Deleted] användaretiketter har lagts till i följande områden i [!DNL Workfront] Korrektur:

* [!UICONTROL Proof details] page
* [!UICONTROL Proofing views]
* [!UICONTROL Proofing viewer]
* [!UICONTROL Proofing workflows]
* [!UICONTROL Print comments] page
* [!UICONTROL User] page

+++


## Uppdateringar i maj 2021

+++**Underhållsuppdatering 27 maj 2021**

**[!UICONTROL Commit Date]visar uppdateringar**

_Uppgifter_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen anger en uppdatering för en aktivitet, [!UICONTROL Commit Date] visas utan att användaren behöver välja [!UICONTROL Commit Date] fält.

**[!UICONTROL More]meny som saknas i filter, vyer och grupperingar**

_Listor_

När en användare befinner sig på den nya [!DNL Adobe Workfront] upplevelsen visar filtren, vyerna eller grupperingarna för en lista, [!UICONTROL More] menyikonen saknas, vilket förhindrar att de delas eller - om de har åtkomst till det - tar bort filter, vyer eller grupperingar.

**Kopiera och klistra in ett projekt [!UICONTROL Reference Number] lägger till &quot;[!UICONTROL This]&quot;**

_Projekt_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen navigerar till ett projekt, kopierar [!UICONTROL Reference Number] från [!UICONTROL Overview] område, klistrar sedan in det, ordet &quot;[!UICONTROL This]&quot; läggs till i slutet av talet.

**[!UICONTROL Daily Digest]e-postmeddelanden skickas när de är inaktiverade**

_E-postmeddelanden_

Vissa användare tar emot [!UICONTROL Daily Digest] e-postmeddelanden när de inte har aktiverats i användarinställningarna.

**Objektet finns inte längre**

_Objekt_

När en användare befinner sig på den nya [!DNL Workfront] försök att öppna vissa objekt visas i felmeddelandet &quot;[!UICONTROL The (object) no longer exists: You may have mistyped the web address. Double check it and try entering the address again.]&quot; Objektlänken visas fortfarande i listor, senaste, favoriter, sökresultat osv., men de kan inte komma åt den och den visas inte i papperskorgen med borttagna objekt.



+++

+++**Underhållsuppdatering 20 maj 2021**

**Korrekturalternativ saknas**

_Korrektur_

När en användare överför en annan version av ett korrektur i [!DNL Workfront], [!UICONTROL Open Proof] och [!UICONTROL Proofing Workflow] länkar saknas, vilket gör att det verkar som om det är ett dokument istället för ett bevis. När dessa länkar saknas, etiketten [!UICONTROL Pending] visas och andra användare inte kan generera korrekturet när det finns i [!UICONTROL Pending] status.

**Användare som inte tar emot schemalagda rapportleveranser**

_Rapporter_

När vissa rapporter är schemalagda för rapportleverans, kanske användarna inte får rapporterna.

**Det går inte att ta bort åtkomst för layoutmallen**

_Kontrollpaneler_

När en användare öppnas [!UICONTROL Sharing] alternativ för en kontrollpanel för att ta bort åtkomst till en layoutmall, [!UICONTROL Delete] -ikonen visas bredvid layoutmallen och de kan inte ta bort åtkomsten.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 17 maj 2021**

**På kontrollpanelen för organisationer visas nu antalet aktiva scenarier korrekt**

_[!DNL Workfront Fusion]_

The [!UICONTROL Organization] instrumentpanelen visade tidigare ett tomt fält i stället för antalet scenarier som används.

**Bläddringen i datalagret visar nu kolumnrubriker**

_[!DNL Workfront Fusion]_

Datastrukturer som använde tidigare kolumnrubriker visade kolumnnamnet i [!UICONTROL data store browsing] vy.  Nu visas kolumnetiketten.  Om ingen etikett identifieras för kolumnen visas kolumnnamnet.

**Scenarioinitieringsfel påverkar inte längre webkrockdata**

_[!DNL Workfront Fusion]_

Tidigare var det ett webhock-initierat scenario (inklusive de som använder en realtidshändelse för att utlösa) som påträffade ett fel under scenarioinitieringen som skulle kunna resultera i att åtkomsten till webkrockdata skulle gå förlorad.  Om ett fel inträffar under scenarioinitieringen (t.ex. att det inte går att verifiera en anslutning) behålls webbkrokdata i webkrokkön och körningen görs automatiskt om.  Efter tre misslyckade försök inaktiveras scenariot och informationen finns kvar i kön.

**Poster i webkrokköer bearbetas nu i mindre grupper**

_[!DNL Workfront Fusion]_

Om en användare tidigare aktiverade ett inaktivt scenario som hade en associerad webbkrokkö med många poster, [!DNL Workfront Fusion] skulle försöka att bearbeta hela kön i en enda körning (om än flera cykler).  Beroende på hur många poster som har bearbetats kan detta ibland medföra att den enskilda körningen överskrider den maximala körningstiden (40 minuter).  När du nu aktiverar ett inaktivt scenario som har en associerad webbkrokkö med poster, bearbetas Workfront Fusion upp till det maximala antalet poster som identifieras i en enskild körning (vanligtvis 2 poster per körning).

**Datalager visar nu korrekt 0-värden**

_[!DNL Workfront Fusion]_

Tidigare visades datalagringsvärden på 0 som tomma. &lt;...>

+++

+++**Underhållsuppdatering 13 maj 2021**

**Den nedrullningsbara kalendern visas bakom [!UICONTROL Unassigned Work] header**

_[!UICONTROL Workload Balancer]_

När en användare navigerar till [!UICONTROL Workload Balancer] in [!DNL Workfront Classic]är datumväljarens övre del dold bakom [!UICONTROL Unassigned Work] som förhindrar användaren från att navigera till olika månader.

**Det går inte att klistra in text i det anpassade meddelandefältet**

_[!DNL Workfront Proof]_

Obs! Det här problemet verkar bara påverka [!DNL Google Chrome] webbläsaren.

När en användare skapar ett nytt korrektur i [!DNL Workfront Proof] och de försöker klistra in text från ett e-postmeddelande i [!UICONTROL Message] i [!UICONTROL Email notification] kan de inte klistra in texten.

**Fält som inte stöds visas i verktyget**

_Anpassad Forms_

När en användare skapar ett anpassat formulär och försöker skapa ett beräkningsfält med hjälp av ett dynamiskt fält, till exempel [!UICONTROL Number of Open Risks]- beräkningsrutan markerar rött och du kan inte spara ändringarna. Dynamiska fält ska inte visas i väljaren för beräknade fält.

**Förhandsgranska uppgifter i [!UICONTROL Work List] läses inte in**

_Startsida_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen tilldelas en layoutmall som innehåller anpassade fält på [!UICONTROL Home], sidan svarar inte och läser inte in uppgifter från [!UICONTROL Work List] om användarna markerar dem.

**Objekt i [!UICONTROL Work List] inte läses in i[!UICONTROL Home]**

_[!UICONTROL Home]_

När en användare klickar på ett objekt i [!UICONTROL Home Work List]visas objektets sidhuvud på den högra panelen, men informationen om objektet visas inte. Användaren ser meddelandet[!UICONTROL Pages Unresponsive.]&quot;

**Problem med RTF-fält i[!DNL Microsoft Outlook]**

_Workfront Integrations_

När en användare uppdaterar ett RTF-fält med [!DNL Workfront for Outlook] de inte kan

* Backsteg
* Kopiera text
* Klistra in text
* Skicka en begäran när alla fält är ifyllda

+++

+++**Underhållsuppdatering 6 maj 2021**

**[!UICONTROL Currency]fältet fungerar inte som förväntat**

_Listor_

När en användare försöker redigera markörenEtt aktivitetsfält i en lista kan inte spara ändringar på grund av följande problem:

* Aktivitets- och problemlistor tillåter inte indata för valutasymboler
* Visar en lista som inte tillåter inmatning av valutabförkortningar när andra språk än engelska används
* Underuppgifts- och utleveranslistor som endast tillåter valutakombinationen USD, oavsett den angivna projektvalutan

**Namnet uppdateras inte för att matcha det nya korrekturnamnet**

_Dokument_

När en användare skapar en ny version av ett korrektur och uppdaterar korrekturnamnet, är dokumentobjektet i [!DNL Workfront] behåller det ursprungliga namnet i stället för att matcha det nya korrekturnamnet.

**[!UICONTROL Business Case]knappar fungerar inte när anpassade formulär bifogas**

_Projekt_

När ett projekt i det nya [!DNL Workfront] upplevelsen skapas från en projektmall och det finns ett anpassat formulär bifogat. Användarna kan inte skicka, avvisa eller godkänna ett affärsärende.

**Arkiverade korrektur som visas på listor och rapporter**

_Korrektur_

När en användare visar sin arbetslista i [!UICONTROL Home] eller [!UICONTROL My Work], visas korrektur som redan har arkiverats i listan. Arkiverade korrektur visas också på rapporter och kontrollpaneler.

**Projekt som skapats från mall har felaktiga åtkomstinställningar**

_Projekt_

När en användare skapar ett projekt från en mall överförs inte mallens åtkomstinställningar till det nya projektet.

**Objekt i [!UICONTROL Work List] inte läses in i[!UICONTROL Home]**

_[!UICONTROL Home]_

När en användare klickar på ett objekt i [!UICONTROL Home Work List]visas objektets sidhuvud på den högra panelen, men informationen om objektet visas inte. Användaren ser meddelandet[!UICONTROL Pages Unresponsive.]&quot;

+++


## Uppdateringar i april 2021

+++**Underhållsuppdatering 29 april 2021**

**[!DNL SharePoint]integreringen autentiserar med hjälp av inloggningsuppgifter från en separat integrering**

_Workfront Integrations_

När en användare har mer än en [!DNL SharePoint] integrering, en [!DNL SharePoint] autentiseringsförsök görs att autentisera med en annan autentiseringsinformation [!DNL SharePoint] integrering.

**Det går inte att överföra eller exportera filer från [!DNL Adobe] produkter**

_Workfront Integrations_

När en användare försöker överföra eller exportera filer med [!DNL Workfront for Adobe Creative Cloud] integreringen visas felmeddelandet &quot;[!UICONTROL Cannot read property 'stages' of undefined]&quot; och inte kan ladda upp eller exportera filerna.

**Filerna visas inte i[!DNL Internet Explorer]**

_Dokument_

När en användare med [!DNL Internet Explorer] webbläsaren navigerar till [!UICONTROL Documents] ett objekts område, [!UICONTROL Documents] skärmen är tom och läser inte in filerna. För vissa användare läser skärmen in vissa filer, men antalet filer som visas matchar inte antalet som visas bredvid [!UICONTROL Documents] -avsnitt.

+++

+++**Underhållsuppdatering 22 april 2021**

**Aktiviteter som lagts till i fel ordning**

_Mallar_

När en användare lägger till en uppgift i en mall, får uppgiften inte det aktivitetsnummer han eller hon förväntar sig och uppgiften läggs till på fel plats.

**Korrektur kombineras nu till ett enda e-postmeddelande**

_Korrektur_

[!DNL Workfront] skickar nu ett e-postmeddelande för kombinerade korrektur i stället för att skicka ett e-postmeddelande för varje fil som ingår.
+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 15 april 2021**

**&quot;[!UICONTROL Scenario rejected]&quot;-fel när ett scenario körs**

_[!DNL Workfront Fusion]_

När en användare försöker köra ett scenario körs inte scenariot och användaren får meddelandet &quot;[!UICONTROL Scenario rejected.]&quot;

+++

+++**Underhållsuppdatering 15 april 2021**

**[!UICONTROL Workload Balancer]visar felaktiga planerade timmar**

_[!UICONTROL Workload Balancer]_

När en användare tittar på en uppgifts planerade timmar i [!UICONTROL Workload Balancer] värdet för de planerade timmarna inte matchar de planerade timmarna som tilldelats aktiviteten.

**Det övre navigeringsfältet visas inte i[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

När en användare navigerar till något [!DNL Workfront Proof] sidan utom kontrollpanelssidan, försvinner det övre navigeringsfältet. Användaren kan inte komma åt funktionerna i navigeringsfältet, t.ex. kontoinställningarna eller profilen.

**Förbättrade anpassade formulär**

_Egna formulär_

För att få en bättre upplevelse när du fyller i ett anpassat formulär har vi förbättrat sättet som långa anpassade fältetiketter visas på. När det finns tillräckligt med vågrätt utrymme för att visa dem i sin helhet trunkeras inte längre dessa etiketter.

+++

+++**Underhållsuppdatering 8 april 2021**

**Kan inte skapa korrektur i [!DNL Adobe Creative Cloud] integration**

_Workfront Integrations_

När en användare försöker skapa ett korrektur direkt från [!DNL Adobe Creative Cloud]genereras inte korrekturet.

+++

+++**Underhållsuppdatering 1 april 2021**

**Problem med att visa sammanfattningspanelen i[!DNL Chrome]**

_[!UICONTROL Summary]_

När en användare öppnar [!UICONTROL Summary] när du använder [!DNL Chrome] webbläsaren fungerar inte sammanfattningspanelens gränssnitt som förväntat. Användaren kan inte rulla, ikonerna kan försvinna och innehållet kan överlappa annat innehåll.

**[!UICONTROL Teams]område i [!UICONTROL Setup] inte visa alla team**

_[!UICONTROL Setup]_

När en administratör går till [!UICONTROL Teams] område på [!UICONTROL Setup]kan de bara visa team som de har skapat. Team som har skapats av andra administratörer visas inte.

**Det går inte att lägga till uppdateringar till projekt i [!UICONTROL Pending Approval] status**

_Projekt_

Om en användare försöker lägga till en uppdatering i ett projekt i [!UICONTROL Pending Approval] status, och de är inte den användare som är tilldelad att godkänna projektet, uppdateringen läggs inte till och följande meddelande visas:

Ett projekt med en[!DNL Pending Approval]Det går inte att redigera status. Du kan ändra projektet genom att ändra status.

+++


## Uppdateringar i mars 2021

+++**Underhållsuppdatering 26 mars 2021**

**Knappar i ett affärsärende visas felaktigt**

_Projekt_

När en användare visar ett affärsärende och fönstret är i helskärmsläge, [!UICONTROL Save] och [!UICONTROL Cancel] -knappar visas nära skärmens mitt, överlappande element för skiftlägen.

**Det går inte att ändra sorteringen av en rapport**

_Rapporter_

När en användare försöker ändra sorteringen av en rapport i den nya [!DNL Workfront] sorteringen ändras inte från den sortering som valdes när rapporten skapades.

**Delning har inaktiverats för nya korrektur**

_[!DNL Workfront Proof]_

När en användare har [!UICONTROL Public Sharing] som aktiveras i standardkorrekturinställningarna skapar ett korrektur och korrekturet skapas med delning inaktiverat. Andra användare kan inte se [!UICONTROL Share] eller dela korrekturet.

**&quot;[!UICONTROL Proof failed to generate]&quot; fel när korrektur skapades**

_[!DNL Workfront Proof]_

När en användare försöker skapa ett korrektur skapas inte korrekturet och användaren ser följande felmeddelande:

&quot;[!UICONTROL Proof failed to generate -- internal error]&quot;

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 25 mars 2021**

**Redundant samling eller referensfält har tagits bort från mappningspanelen**

_[!DNL Workfront Fusion]2.0_

När en användare använder en term från [!DNL Workfront] API för att välja en samling eller ett referensfält som ska inkluderas i utdata från en [!DNL Workfront] modulen visar utdata för den modulen fältet med ett kolon (till exempel [!UICONTROL owner:name]) och även i attributen (name är ett fält under owner). Fältet som är märkt med ett kolon innehåller inga data och ger felaktiga data om de mappas till en modul senare i scenariot.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 18 mars 2021**

**Projektmallsinställningarna gäller nu för projekt som skapats via [!DNL Workfront Fusion] 2.0**

_[!DNL Workfront Fusion]2.0_

När du skapar ett projekt från en mall med [!DNL Workfront Fusion] 2.0 används mallinställningarna för det nya projektet. Detta fungerar på samma sätt när du skapar ett projekt från en mall i [!DNL Workfront] program.

+++

+++**Underhållsuppdatering 18 mars 2021**

**Projektmallsinställningarna gäller nu för projekt som skapats via API**

_[!DNL Workfront]API_

När du skapar ett projekt från en mall med [!DNL Workfront] API, används mallinställningarna för det nya projektet. Detta fungerar på samma sätt när du skapar ett projekt från en mall i [!DNL Workfront] program.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 15 mars 2021**

**Delad komponent fungerar inte som förväntat**

_[!DNL Workfront Proof]_

Om fristående [!DNL Workfront Proof] konton flyttas till en delad komponent, följande funktioner kan uppstå när en användare lägger till en ny version av ett korrektur eller dokument:

* Användaren kan inte ta bort användaren [!UICONTROL Studio Proof].
* Standardmeddelandet visas inte i den nya versionen.

**Delning av offentlig länk har inte aktiverats för en ny version av ett korrektur**

_Dokument_

När en användare aktiverar delning av offentlig länk i ett korrektur och sedan överför en ny version av korrekturet, aktiveras inte delning av offentlig länk automatiskt i den nya versionen av korrekturet.

**[!UICONTROL Approve], [!UICONTROL Changes], [!UICONTROL Reject] knappar saknas i korrektur**

_[!DNL Workfront Proof]_

När en användare visar ett korrektur i korrekturläsaren visas [!UICONTROL Approve], [!UICONTROL Changes]och [!UICONTROL Reject] knappar saknas längst upp på skärmen.

**Det går inte att ändra sorteringen av en rapport**

_Rapporter_

När en användare försöker ändra sorteringen av en rapport i den nya [!DNL Workfront] sorteringen ändras inte från den sortering som valdes när rapporten skapades.

**Anpassat meddelande vid korrektur som inte överförs till den nya versionen**

_[!DNL Workfront Proof]_

När en användare bifogar ett eget meddelande till ett korrektur och sedan överför en ny version av det korrekturet, visas inte det anpassade meddelandet på det nya korrekturet.

**Användarlistan visas inte**

_Listor_

När en användare försöker visa en användarlista innehåller vyn &quot;[!UICONTROL Status Icons]&quot; visas inte listan.

**&quot;[!UICONTROL Notify recipients about this proof]&quot;, alternativ inaktiverat oavsett arbetsflödesinställningar**

_[!DNL Workfront Proof]_

När en användare skapar ett nytt korrektur och inte aktiverar[!UICONTROL Notify recipients about this proof]&quot;kan det hända att den avsedda mottagaren inte meddelas. Detta gäller även om alternativet är aktiverat i arbetsflödesinställningarna.

**Det går inte att ändra tidsramen**

_[!UICONTROL Enhanced Analytics]_

När en användare visar [!UICONTROL Enhanced analytics] och klickar på kalendern för att justera datumintervallet ändras inte datumen.

**Kan inte hämta offentligt delat dokument**

_Dokument_

När en användare klickar på en delad länk för att hämta ett dokument, hämtas inte dokumentet och användaren ser ett fel från webbläsaren som säger att sidan inte finns.

+++

+++**Underhållsuppdatering 11 mars 2021**

**Avsnitt i anpassat formulär som inte exporteras för icke-administratörer**

_Anpassad Forms_

Om ett anpassat formulär som är kopplat till ett objekt har en avsnittsbrytning som kräver något ovanför &quot;[!UICONTROL View]&quot; som behövs för att visa innehållet i avsnittet, kan inte avsnittets innehåll exporteras av någon annan än en administratör.

**Det hämtade dokumentet har ett felaktigt namn**

_[!DNL Workfront Proof]_

När en användare hämtar ett dokument från [!UICONTROL Proof viewer], har dokumentets namn som en tidigare version av dokumentet, inte den version som hämtades.

+++

+++**Underhållsuppdatering 4 mars 2021**

**Fel vid åtkomst av layoutmall**

_Layoutmallar_

När en användare har registrerat sig på den nya [!DNL Workfront] upplevelsen växlar till [!DNL Classic] upplevelse och försök att få tillgång till [!DNL Classic] layoutmall ser de felet[!UICONTROL That Page does not exist.]&quot;

**Kan inte redigera filter i[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

När en användare försöker redigera ett filter i [!UICONTROL Workload Balancer]öppnas inte filterverktyget.

**&quot;[!UICONTROL See All Notifications]&quot;-länk i e-postmeddelande dirigerar om till felaktig sida**

_E-postmeddelanden_

När en användare klickar på[!UICONTROL See All Notifications]&quot; i ett e-postmeddelande dirigeras de om till en sida med följande meddelande:

&quot;[!UICONTROL The User no longer exists. You may have mistyped the web address. Double check it and try entering the address again.]&quot;

**Användaren dirigeras inte till korrekturkommentaren som de är taggade i**

_E-postmeddelanden_

När en användare är taggad i en korrekturkommentar och klickar på [!UICONTROL Go To Proof] i ett e-postmeddelande dirigeras de till korrekturet men inte till den specifika kommentaren. Om användaren är i [!DNL Workfront Classic], dirigeras de till [!UICONTROL Document Details] sidan i stället för kommentaren i korrekturet.

**Användare som lagts till i [!DNL Workfront] scen som tar emot e-postmeddelanden**

_[!DNL Workfront Proof]_

När en användare som inte är med i arbetsflödet öppnar ett korrektur från [!DNL Workfront], skapar systemet automatiskt en scen, lägger till användaren i korrekturet och skickar en [!UICONTROL New Proof] e-postmeddelande.

**Dokumentsammanfattningspanelen gör mörkare, så att funktionsmakron inte är tillgängliga**

_Dokument_

När en användare befinner sig på en dokumentsida och håller muspekaren över dokumentsammanfattningspanelen blir panelen mörkare och kan visa andra knappar. Användaren kan inte klicka på åtgärderna i sammanfattningspanelen.

**Uppdatera prestandaändringar för strömmar**

_Uppdateringsström_

Vi har minskat antalet användaruppdateringar som visas i [!UICONTROL Updates] mellan 50 och 25 i taget för att förbättra prestandan.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 1 mars 2021**

**Nytt korrekturmeddelande skickas inte**

_[!DNL Workfront Proof]_

OBS! Problemet har åtgärdats i nya [!DNL Workfront] den 26 februari 2021.
Den har åtgärdats i [!DNL Classic] upplevelse den 1 mars 2021.

När en användare skapar ett nytt korrektur och aktiverar alternativet [!UICONTROL Notify recipients about this proof], skickas inget e-postmeddelande för att meddela mottagaren.

+++


## Uppdateringar i februari 2021

+++**Underhållsuppdatering 25 februari 2021**

**[!UICONTROL Scheduling]verktyget läses inte in i något område**

_Resurshantering_

När en användare med en apostrof i sitt användarnamn försöker få åtkomst till [!UICONTROL Scheduling] verktyg in [!DNL Workfront Classic], sidan är tom och verktyget läses aldrig in.

**Namnet ändras inte på nya korrekturversioner**

_Dokument_

När en användare befinner sig på den nya [!DNL Workfront] När du laddar upp en ny version av ett dokument med ett annat namn uppdateras inte namnet så att det matchar den senaste versionens namn.

**[!UICONTROL Document Share]fel vid borttagning av projekt**

_Projekt_

När en systemadministratörsanvändare har åtkomst till ett projekt som har kopierats och försöker ta bort det eller ta bort ett dokument i projektet, kan de inte ta bort objektet och felmeddelandet visas[!UICONTROL Document Share with primary key value(s) not found.]&quot;

**Användarrapporten använder inte alla filter**

_Rapporter_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen skapar en användarrapport med en filterregel som innehåller [!UICONTROL Top Parent ID] -fält används inga andra filterregler i rapporten.

**Beräknade fält beräknas inte om efter redigering**

_Anpassad Forms_

När en användare befinner sig på den nya [!DNL Workfront] redigerar och sparar ett anpassat formulär som innehåller beräknade fält. Dessa fält uppdateras inte.

**Dokument som tas bort när ett anpassat formulär tas bort**

_Anpassad Forms_

När en användare befinner sig på den nya [!DNL Workfront] När du tar bort ett anpassat formulär som bifogas till dokument tas även dessa dokument bort.

+++

+++**Underhållsuppdatering 18 februari 2021**

**Onödig kryssruta borttagen från [!UICONTROL Requests] area**

_Begäranden_

Vi har tagit bort kryssrutan till vänster om namnen på förfrågningarna i listan Skickat i dialogrutan [!UICONTROL Requests] område. Den här kryssrutan var inte kopplad till någon funktion, så vi tog bort den för att eliminera en förvirrande upplevelse.

**Det går inte att komma åt dokument från länkar**

_Dokument_

När en användare befinner sig på den nya [!DNL Workfront] när de klickar på vissa dokumentlänkar kan de inte komma åt dokumentet och felmeddelandet &quot;[!UICONTROL The Document no longer exists: You may have mistyped the web address. Double check it and try entering the address again.]&quot; Samma fel inträffar med [!UICONTROL View Details] länk i korrekturmeddelanden via e-post.

+++

+++**Workfront Fusion Maintenance Update den 16 februari 2021**

**[!DNL Workfront Fusion]2.0 visar felaktiga tidszoner**

_Scenarier_

Uppdateringen åtgärdade ett problem där [!DNL Fusion] 2.0 visade felaktigt användartidszoner. Användarna kan nu se sin tidszon under inmatningsfält för datum.

+++

+++**Underhållsuppdatering 11 februari 2021**

**Korrektur överförs inte till den valda mappen**

_[!DNL Workfront Proof]_

När en användare öppnar en mapp och lägger till ett nytt korrektur överförs korrekturet till allmänheten [!UICONTROL Documents] i objektet i stället för i mappen.

**För många fästa sidor gör att den övre navigeringen försvinner**

_Navigering_

När en användare har fler än 60 fasta sidor slutar den övre navigeringen att visas, vilket förhindrar användaren från att komma åt [!UICONTROL Search], [!UICONTROL Main Menu], [!UICONTROL Notifications], med mera.

**Användaren kan inte skriva text i RTF-fält**

_Listor_

När en användare försöker att infoga ett RTF-fält kan han/hon bara skriva ett enda tecken.

+++

+++**Underhållsuppdatering 4 februari 2021**

**Exporterade rapportprogram [!DNL Workfront Classic] branding**

_Rapporter_

När en användare i den nya Workfront-upplevelsen exporterar en rapport matchar logotypen som visas i den exporterade rapporten [!DNL Workfront Classic] inställningar under [!UICONTROL Setup] > [!UICONTROL System] > [!UICONTROL Branding].

+++


## Uppdateringar i januari 2021

+++**Underhållsuppdatering 28 januari 2021**

**Kommentarer visas inte[!UICONTROL on behalf of]&quot;**

_Uppdateringar_

När en [!DNL Workfront] administratören loggar in som en annan användare och de svarar på en kommentar i [!UICONTROL Updates] ett objekts område, texten[!UICONTROL on behalf of]&quot; visas inte före användarnamnet.

**Det går inte att bifoga ett dokument**

_Begäranden_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen försöker lägga till ett dokument i en ny begäran från en extern dokumentleverantör, [!UICONTROL Documents] listan läses inte in, vilket gör att användaren inte kan välja dokumentet och slutföra begäran.

**Skärmbredden utökas till höger, vilket orsakar navigeringsproblem**

_[!UICONTROL Home Calendar]_

När en användare befinner sig på den nya [!DNL Workfront] upplevelsen öppnar [!UICONTROL Home Calendar] och de har objekt som förfaller under några veckor utökas skärmen till höger så att de inte kan visa hela veckan samtidigt. Om användaren väljer ett objekt för att öppna [!UICONTROL Details] i det här läget och om de vill visa information för ett annat objekt måste de rulla till vänster, vilket stänger [!UICONTROL Details] -panelen.

**Etikett för godkännandeprocess för engångsbruk korrigerad**

_Projekt_

När en enstaka godkännandeprocess används för ett projekt i den nya [!DNL Workfront] upplevelsen, visas nu som &quot;[!UICONTROL Single-use approval process]&quot; istället för &quot;\&lt;custom>&quot; i [!UICONTROL Edit Project] box. Det här är ännu inte tillgängligt för uppgifter och problem.

**Förbättrat utseende och känsla för anpassade formulär**

_Projekt_

Vi har förbättrat utseendet och känslan av att arbeta med anpassade formulär i nya [!DNL Workfront] upplevelse för projekt.

**API-funktionaliteten för projektvaluta matchar nu funktionen i appen**

_Projekt_

Du kan inte ändra valutan för ett projekt när det redan finns ekonomisk information i projektet. Med den senaste underhållsuppdateringen matchar API-funktionerna för det här fallet nu upplevelsen i [!DNL Workfront] gränssnitt.

**Genererar inte automatiskt följande vecka**

_Tidrapporter_

När en användare navigerar till [!UICONTROL Timesheets] visas bara tidrapporten för den aktuella veckan. Tidrapporten för kommande veckor genereras inte automatiskt.

+++

+++**Underhållsuppdatering 21 januari 2021**

**Om du sorterar manuellt efter en kolumn visas alla resultat**

_Rapporter_

När en användare befinner sig på den nya [!DNL Workfront] När du klickar på en stapel i en rapports diagram, klickar du på en kolumnrubrik för att manuellt sortera resultaten för den grupperingen, visa alla rapportresultat, inte bara resultat för den ursprungligen valda grupperingen.

**&quot;[!UICONTROL Allow sharing proof via URL or embed code]&quot; ändra inställningar**

_[!DNL Workfront Proof]_

När en användare skapar ett korrektur och avmarkerar inställningen [!UICONTROL Allow sharing proof via URL or embed code]kontrolleras inställningen igen när korrekturet har genererats. Om användaren lämnar inställningen markerad avmarkeras den när korrekturet har genererats.

**[!DNL Mac]användare inte kan klistra in i textfält i korrekturläsaren**

_[!DNL Workfront Proof]_

När en användare försöker klistra in text i vissa fält i korrekturläsaren visas inte texten i fältet.

+++

+++**Underhållsuppdatering 14 januari 2021**

**Det gick inte att uppdatera inställningarna för e-postmeddelanden**

_Inställningar_

När en användare försöker uppdatera inställningarna för e-postmeddelanden kan de inte komma åt [!UICONTROL Email Notifications] och se felmeddelandet &quot;[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]&quot;

**[!UICONTROL Gantt chart]gör att vissa fält trunkeras**

_Listor_

När en användare öppnar [!UICONTROL Gantt chart] i vissa listområden, vissa fält, t.ex. [!UICONTROL Description]—trunkera texten. Användaren måste dubbelklicka på fältet för att se den fullständiga texten.

**Det går inte att skicka filer från[!UICONTROL Document Details]**

_Dokument_

När en användare befinner sig på den nya [!DNL Workfront] försöker skicka ett dokument från [!UICONTROL Document Details] visas felmeddelandet &quot;[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]&quot;

+++

+++**Underhållsuppdatering 7 januari 2021**

**Dialogrutan Delegera godkännanden stängs**

_Startsida_

När en användare försöker delegera godkännanden i [!UICONTROL Home] och klickar på ett datum stängs dialogrutan utan att något datum har valts eller så tillåts användaren att slutföra användardelegeringen.

**Problem med att flytta ett dokument till en uppgift**

_Dokument_

När en användare försöker flytta ett dokument eller korrektur i det nya dokumentet [!DNL Workfront] vissa uppgifter utanför projektet listas inte som förväntat för det överordnade projektet.

**PDF som hämtats har ett felaktigt namn**

_[!DNL Workfront Proof]_

När en användare får en nedladdningslänk via e-post ([!UICONTROL Proof] > [!UICONTROL Print Comments] > [!UICONTROL PDF]) och de exporterar filen får den nedladdade filen ett slumpmässigt nummer i stället för korrektur-ID.

+++
