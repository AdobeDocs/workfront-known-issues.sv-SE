---
title: Workfront Maintenance Updates for 2021
description: Historik över underhållsuppdateringar för 2021 för  [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
feature: Get Started with Workfront
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '9003'
ht-degree: 0%

---

# Underhållsuppdateringar för 2021 [!DNL Workfront]

Följande underhållsuppdateringar gjordes 2021:

## Uppdateringar i december 2021

+++**Underhållsuppdatering 23 december 2021**

**Nya aktiviteter får som standard en felaktig aktivitetsbegränsning**

_Uppgifter_

När en användare skapar en ny aktivitet med knappen [!UICONTROL New Task] och alternativet [!UICONTROL New Task Default Start] Date är inställt på [!UICONTROL Today], ställs aktivitetsbegränsningen för den skapade aktiviteten in på [!UICONTROL As soon as possible] i stället för [!UICONTROL Start no earlier than]. Detta kan också inträffa när du använder projektmallar.

**Öppningsschema i området [!UICONTROL Groups] leder till en tom sida**

_Konfigurera_

När en användare visar grupper i området [!UICONTROL Setup] och försöker öppna, redigera eller kopiera ett schema, öppnas inte schemat och användaren ser en tom sida.

**Ändringarna visas inte när vänsternavigering ändras**

_Navigering_

När en användare försöker ändra ordningen på den vänstra navigeringspanelen genom att dra ett objekt, visas objektet på sin tidigare plats när användaren släpper det. Om användaren uppdaterar sidan visas den nya ordningen på den vänstra panelen.

**Länk för att skicka ett begärt dokument leder till en tom sida.**

_Dokument_

När en användare tar emot en begäran om att skicka ett dokument och klickar på länken till objektet där dokumentet begärdes, leder länken till en tom sida. Detta kan inträffa när du klickar på en länk i ett e-postmeddelande eller i ett meddelande i appen.

**[!UICONTROL Workload Balancer]visar 0 timmar allokerade**

_[!UICONTROL Workload Balancer]_

När en användare visar [!UICONTROL Workload Balancer] och har inställningen [!UICONTROL Show projected dates] aktiverad, visas eventuella datum i framtiden som 0 timmar.

**Korrektur försvinner ibland från mappar**

_[!DNL Workfront Proof]_

När en användare som är inloggad på [!DNL Workfront Proof] visar en mapp visas mappen som tom. Om användaren checkar tillbaka senare visas korrektur.

+++

+++**Underhållsuppdatering 16 december 2021**

**Om du klickar på ett meddelande i meddelandelistan blir sidan tom**

_Meddelanden_

När en användare öppnar sin lista med meddelanden från ikonen [!UICONTROL Notifications], klickar på ett meddelande, visas de på en tom sida och meddelandet visas inte.

**Panelen Sammanfattning visar [!UICONTROL No selection] när aktiviteten är markerad**

_Uppgifter_

När en användare öppnar en dokumentsammanfattning i området [!UICONTROL Documents] i ett projekt går han/hon till uppgiftslistan, väljer en aktivitet och försöker öppna aktivitetssammanfattningen, uppgiftssammanfattningen visas inte och användaren ser följande meddelande:

[!UICONTROL No selection. Select a document in the list to view details.]

I meddelandet omnämns dokument även om användaren finns i uppgiftslistan.

**[!UICONTROL Unassigned Work]läser inte in**

_[!UICONTROL Workload Balancer]_

När en användare i [!UICONTROL Workload Balancer] skapar ett filter med fältet [!UICONTROL Assignment:Role ID] läses inte området [!UICONTROL Unassigned Work] in.

**Koppling av mall med alternativet [!UICONTROL Customize and attach] rensar anpassade fältvärden**

_Projekt_

Om en användare kopplar en mall till ett projekt med alternativet [!UICONTROL Customize and attach] och projektet redan har ett anpassat formulär kopplat till sig, överförs inte de anpassade fältvärdena och måste anges manuellt igen. Detta inträffar även när mallen innehåller samma anpassade formulär.

+++

+++**Underhållsuppdatering (snabbkorrigering) 10 december 2021**

**[!UICONTROL Whoops]-fel vid koppling av mall till befintligt projekt**

_Projekt_

När en användare försöker koppla en mall till ett befintligt projekt bifogas inte mallen och användaren ser följande fel:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

+++

+++**Underhållsuppdatering 9 december 2021**


**Den komprimerade vänstra navigeringspanelen utökas vid sidinläsning**

_Navigering_

När en användare har angett att den vänstra navigeringen ska komprimeras och sedan uppdateras en sida, expanderas den vänstra navigeringen på den nya sidan. Den vänstra navigeringen utökas också om användaren öppnar en sida på en ny flik.

**[!UICONTROL Workload Balancer]visar 0 timmar allokerade**

_[!UICONTROL Workload Balancer]_

När en användare visar [!UICONTROL Workload Balancer] och har inställningen [!UICONTROL Show projected dates] aktiverad, visas eventuella datum i framtiden som 0 timmar.

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

**Extra snedstreck läggs till när URL:en skrivs manuellt**

_Begäranden_

När en användare fyller i en begäran och börjar skriva in en URL manuellt, läggs ett extra snedstreck till i början av URL:en. Användaren kan inte ta bort snedstrecket.

**Det går inte att ta bort anpassade avsnitt från den vänstra navigeringspanelen**

_Navigering_

När en användare försöker ta bort ett anpassat avsnitt från den vänstra navigeringspanelen genom att klicka på X bredvid avsnittet, tas inte avsnittet bort.

**Ej tilldelat arbete läses inte in**

_[!UICONTROL Workload Balancer]_

När en användare i [!UICONTROL Workload Balancer] skapar ett filter med fältet [!UICONTROL Assignment:Role ID] läses inte området [!UICONTROL Unassigned Work] in.

**Sidor läses inte in i vissa webbläsare**

_[!DNL Workfront]_

När en användare arbetar i [!DNL Workfront] läses sidorna inte in och användaren ser följande felmeddelande:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

Detta har rapporterats i

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Det här felet inträffar slumpmässigt och kan påverka alla områden i [!DNL Workfront].

+++


## Uppdateringar i november 2021

+++**Underhållsuppdatering 18 november 2021**

**[!DNL Workfront]för [!DNL Jira] [!UICONTROL Invalid clientID or clientSecret]-fel vid inloggning**

_Workfront-integreringar_

Användare har loggats ut från [!DNL Jira] för Workfront-integrering. När en användare försöker logga in i [!DNL Workfront for Jira]-integreringen kan de inte logga in och följande fel visas:

[!UICONTROL Invalid clientID or clientSecret]

**Anpassat formulär som är kopplat till begäran uppdateras inte när ett nytt köämne väljs**

_Begäranden_

När en användare skapar en begäran och väljer ett köämne som automatiskt kopplar ett anpassat formulär till begäran och sedan väljer ett annat köämne, förblir det anpassade formuläret från det första köämnet kopplat till begäran.

**Ikonerna visas felaktigt**

_[!DNL Workfront]_

Ikonbilderna visas felaktigt. Detta har rapporterats i många områden över [!UICONTROL Workfront].

**Aktiviteter exporteras inte till PDF när alternativet &quot;Andra storlekar&quot; har valts.**

_Uppgifter_

Om en användare försöker exportera en uppgiftslista till PDF och väljer alternativet [!UICONTROL Other Sizes] kan användaren välja en storlek och klicka på [!UICONTROL Export], men listan exporteras inte. Det finns inget felmeddelande och inget annat som tyder på att exporten misslyckades.

**Bildindikatorn visas inte i e-postmeddelanden**

_Meddelanden_

När en användare lägger till en bild i en uppdatering och ett e-postmeddelande skickas till mottagaren av uppdateringen, innehåller e-postmeddelandet ingen indikator på att det finns en bild i uppdateringen.

**Sidor läses inte in i vissa webbläsare**

_[!DNL Workfront]_

När en användare arbetar i [!DNL Workfront] läses sidorna inte in och användaren ser följande felmeddelande:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

Detta har rapporterats i

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Felet inträffar slumpmässigt och kan påverka alla delar av Workfront.

+++

+++**Underhållsuppdatering 11 november 2021**

**Problem med dokumentintegreringar, tom sida i popup-fönstret för dokumentöverföring från[!DNL Google Drive*]*

_Dokument_

När en användare försöker lägga till ett nytt dokument till [!DNL Workfront] från [!DNL Google Drive] med hjälp av [!UICONTROL Add New] >[!UICONTROL From [!DNL Google Drive]] är popup-skärmen för överföring tom.

**Det går inte att använda mer än ett filter i arbetsbelastningsutjämnaren**

_[!UICONTROL Workload Balancer]_

När en användare försöker använda mer än ett filter i [!UICONTROL Workload Balancer] ser de följande problem:

* Om användaren väljer två filter tillämpas bara det undre filtret.
* Om användaren väljer mer än två filter visas inga resultat.

**[!UICONTROL Project Folders]-dokumenthuvudet saknas i projektdokumentområdet**

_Projekt_

När en användare är i ett projekt och visar projektdokumenten saknas rubriken [!UICONTROL Project Folders] i den vänstra navigeringen. Pilen finns fortfarande kvar och användaren kan välja en mapp.

**Kolumner på Kanban-tavlan är för breda och kan inte justeras**

_Agile_

När en användare visar en Kanban-panel med flera kolumner är kolumnerna för breda och användaren måste rulla för att visa eller flytta kort till kolumnerna längst till höger. Kolumnbredderna kan inte justeras, så användaren kan inte göra kolumnerna mindre så att alla är synliga på skärmen samtidigt.

**Förbättrat gränssnitt för att skapa ett nytt team**

_Team_

Att skapa team är nu mer intuitivt med nya visuella ledtrådar. När du väljer ikonen [!UICONTROL Switch Teams] på en gruppsida har länken [!UICONTROL Create New Team] en ikon som anger [!UICONTROL new], och länken separeras från resten av listan så att den inte ser ut som ett teamnamn. Det här gränssnittet är detsamma för både flexibla och icke-flexibla team.

+++

+++**Underhållsuppdatering 4 november 2021**

**Nya aktiviteter får som standard en felaktig aktivitetsbegränsning**

_Uppgifter_

När en användare skapar en ny aktivitet med knappen [!UICONTROL New Task] och alternativet för standardstartdatum för ny aktivitet har angetts till [!UICONTROL Today], anges aktivitetsbegränsningen för den skapade aktiviteten till [!UICONTROL As soon as possible] i stället för [!UICONTROL Start no earlier than].

**Fält visas inte på Agile-artikelkort**

_Agile_

När en användare visar ett Agile-storyboard visas bara fälten [!UICONTROL Description] och [!UICONTROL Status]. Andra fält, inklusive anpassade fält, visas inte.

**Korten återgår till den ursprungliga kolumnen innan de flyttas till den nya kolumnen**

_Agile_

När en användare drar ett kort till en ny kolumn på storyboard kan användaren se kortet som dras. När användaren släpper kortet i den nya kolumnen visas kortet kort i den ursprungliga kolumnen innan det visas i den nya kolumnen.

**Värden är inte tillgängliga för anpassat fält i filter**

_[!UICONTROL Workload Balancer]_

När en användare försöker skapa ett filter med hjälp av ett anpassat fält visas inte värdet för det anpassade fältet och kan inte anges i filtret.

**Sidorna läses inte in i [!DNL Firefox] webbläsaren**

_[!DNL Workfront]_

När en användare arbetar i [!DNL Workfront] med en [!DNL Firefox]-webbläsare läses inte sidorna in och användaren ser följande felmeddelande:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

Det här felet inträffar slumpmässigt och kan påverka alla områden i [!DNL Workfront].

**Datumrelaterat fel vid skapande av projekt från mall.**

_Mallar_

Om en användare skapar ett projekt från en mall och anger schemaläge till [!UICONTROL Start Date], väljer sedan en aktivitetsbegränsning när användaren försöker skapa projektet, skapas inte projektet och användaren ser ett felmeddelande baserat på aktivitetsbegränsningen.

Dialogrutan **[!UICONTROL Export Gantt Chart]svarar inte**

_Gantt-schema_

Om en användare i den nya [!DNL Workfront]-upplevelsen försöker exportera [!UICONTROL Gantt Chart] och väljer alternativet [!UICONTROL What I See], exporteras inte [!UICONTROL Gantt Chart] och dialogrutan svarar inte. Användaren kan inte stänga eller klicka utanför dialogrutan.

**Ikonerna visas felaktigt**

_[!DNL Workfront]_

Ikonbilderna visas felaktigt. Detta har rapporterats i följande fall:

* Bilder för jobbroller eller grupper när ett objekt delas
* Vänster- och högerikoner i kalenderrapporter
* Sorteringsikoner i rapportkolumner

**Lägg till kryssrutor i begäranden i avsnittet [!UICONTROL Submitted] i området [!UICONTROL Requests]**

_Begäranden_

Vi har lagt till kryssrutor till vänster om begärandenamnen i [!UICONTROL Submitted list] i området [!UICONTROL Requests]. Detta gör det enklare att markera en begäran och visa ytterligare information.

**Anpassade kvartal stöds nu i filtren för arbetsbelastningsutjämning**

_[!UICONTROL Workload Balancer]_

Filtren i [!UICONTROL Workload Balancer] har nu stöd för anpassade kvartal.

**Uppdaterad filteroperator för fältet Varaktighet i filtren för arbetsbelastningsutjämning**

_[!UICONTROL Workload Balancer]_

Filteroperatorerna har uppdaterats när [!UICONTROL Workload Balancer]-områdena filtreras efter [!UICONTROL Duration].

+++


## Uppdateringar i oktober 2021

+++**Underhållsuppdatering 28 oktober 2021**

**[!UICONTROL Home]och [!UICONTROL My Work] visar tom sida**

_[!UICONTROL Home]/[!UICONTROL My Work]_

När en användare navigerar till [!UICONTROL Home] eller Mitt arbete visas sidan som tom.

**Det går inte att visa eller redigera [!UICONTROL Topic Group] information**

_Begäranden_

När en användare försöker visa eller redigera informationen för en ämnesgrupp, visar sidan som öppnas [!UICONTROL Topic Group Detail] i sidhuvudet, men är annars tom

**Tomma obligatoriska alternativknappar fylls i automatiskt**

_Begäranden_

När en användare skickar en begäran med ett obligatoriskt alternativknappsfält och användaren inte har valt ett värde för det fältet innan begäran skickas, väljs det första värdet automatiskt när begäran skickas.

+++

+++**Underhållsuppdatering 21 oktober 2021**

**Det går inte att lägga till ett filter i[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

När en användare i [!UICONTROL Workload Balancer] försöker lägga till ett filter öppnas panelen [!UICONTROL Add filter], men innehållet i panelen läses inte in och användaren kan inte lägga till filtret.

**Agile Scrum board visar inte artiklar**

_Agile_

När en användare försöker visa Scrum board i ett teams iteration, visas trumman som tom.

**Krusningsrutan är tom när filter används**

_Agile_

När en användare försöker visa ett Scrum-artikelkort med något filter förutom filtret [!UICONTROL All Team], visas en tom skärm. Användaren kan inte växla tillbaka till filtret [!UICONTROL All Team].

**Listor visas bara på ett litet område på skärmen**

_Listor_

När en användare försöker visa en lista när han/hon använder en [!DNL Safari]-webbläsare på en/ett [!DNL Mac] med [!DNL Big Sur OS] visas listan bara på ett litet område på skärmen. Användaren kan bläddra igenom listan, men området kan vara så litet att listan är svår eller omöjlig att läsa.

**Tomma obligatoriska alternativknappar fylls i automatiskt**

_Begäranden_

När en användare skickar en begäran med ett obligatoriskt alternativknappsfält och användaren inte har valt ett värde för det fältet innan begäran skickas, väljs det första värdet automatiskt när begäran skickas.

+++

+++**Underhållsuppdatering (snabbkorrigering) 21 oktober 2021**

**[!UICONTROL Home]och [!UICONTROL My Work] visar tom sida**

_[!UICONTROL Home]/[!UICONTROL My Work]_

När en användare navigerar till [!UICONTROL Home] eller [!UICONTROL My Work] visas sidan som tom.

+++

+++**Underhållsuppdatering 20 oktober 2021**

**[!UICONTROL Workload Balancer]har angetts som standardalternativ för schemaläggning**

_[!UICONTROL Workload Balancer]_

Om en användare som har [!UICONTROL Scheduler] inställt som standard använder den ser de att [!UICONTROL Workload Balancer] har angetts som standard.

+++

+++**Underhållsuppdatering (snabbkorrigering) 19 oktober 2021**

**Det går inte att tilldela en begäran när den skapas**

_Begäranden_

När en användare i den nya [!DNL Workfront]-upplevelsen skapar en begäran och försöker tilldela en användare genom att skriva sitt namn i fältet [!UICONTROL Assignments], visas inte den nedrullningsbara listan och användaren kan inte välja namnet på den som tilldelats.

**Krusningsrutan är tom när filter används**

_Agile_

När en användare försöker visa ett Scrum-artikelkort med något filter förutom filtret [!UICONTROL All Team], visas en tom skärm. Användaren kan inte växla tillbaka till filtret [!UICONTROL All Team].

+++

+++**Underhållsuppdatering 14 oktober 2021**

**Mallar som är gemensamma för hela systemet visas inte**

_Mallar_

När en användare skapar ett projekt och försöker använda en mall som har delats av hela systemet, kan användaren inte se mallen i listan över tillgängliga mallar och kan inte använda mallen.

**Fel när projekt skapades från mallar**

_Mallar_

När en användare försöker skapa ett projekt från en mall som innehåller ett anpassat formulär med ett avsnitt som bara är synligt för administratörer, kan användaren inte skapa projektet och följande meddelande visas:

[!UICONTROL Category with primary key value(s) "xxxxxxxxxxxxxxxx" not found]

**Uppdaterade länkar för kopiering och flyttning av uppgifter**

_Uppgifter_

Länkarna för kopiering och flyttning av uppgifter har uppdaterats till [!UICONTROL Copy to] och [!UICONTROL Move to] både på uppgiftssidan och i en uppgiftslista.

**Ta bort gräns för jobbrollssökning när faktureringssatser åsidosätts för ett projekt**

Jobbroller

Obs! Den här uppdateringen finns för närvarande i förhandsvisningsmiljön och kommer att finnas i Production i version 2.1. Mer information finns i&quot;Versionsöversikt 2.1&quot;.

Om du åsidosätter faktureringsfrekvenser för jobbroller i ett projekt söks nu alla jobbroller i systemet igenom.

Tidigare sökte [!DNL Workfront] efter jobbroller i de första 2000 rollerna i alfabetisk ordning.

+++

+++**Underhållsuppdatering 7 oktober 2021**

**[!UICONTROL In-app notifications disappear from]meddelandecenter**

_Meddelanden_

När en användare tittar på meddelandecentret visas inte längre några tidigare synliga meddelanden. I vissa fall kan meddelandet försvinna innan användaren ser det.

**Meddelanden visas inte på [!UICONTROL All Announcements]-sidan**

_Meddelanden_

När en användare öppnar sidan [!UICONTROL All Announcements] från området [!UICONTROL Notifications] visas inga meddelanden i följande områden:

* [!UICONTROL Inbox]
* [!UICONTROL Favorites]
* [!UICONTROL Drafts]
* [!UICONTROL Deleted]

**Fel vid tilldelning i[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

När en användare försöker göra en tilldelning från [!UICONTROL Workload Balancer] tilldelas inte arbetet och användaren ser följande fel:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

+++


## Uppdateringar i september 2021

+++**Underhållsuppdatering 30 september 2021**

**Fel vid navigering snabbt till eller från[!UICONTROL Home]**

_Startsida_

När en användare snabbt navigerar till eller från [!UICONTROL Home], läses sidan inte in och användaren ser följande fel:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

Detta kan också inträffa vid navigering till [!UICONTROL Home] via en stift.

+++

+++**Underhållsuppdatering 23 september 2021**

**[!UICONTROL Access Denied]fel vid visning av biljetter som skickats till[!DNL Workfront]**

_Problem_

När en användare har skickat en biljett till [!DNL Workfront] och försöker visa biljetten visas följande fel:

[!UICONTROL Access Denied: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Affärsärendesammanfattning visar felaktiga värden**

_Projekt_

När en användare tittar på sammanfattningspanelen [!UICONTROL Business Case] återspeglar de värden som visas inte värdena i de enskilda [!UICONTROL Business Case] -avsnitten.

**Kolumnrubriker är inte i linje med kolumner i listor**

_Konfigurera_

När en användare befinner sig i området [!UICONTROL Setup] och visar en lista, t.ex. [!UICONTROL Custom Forms] eller [!UICONTROL Access Levels], motsvarar inte kolumnrubrikerna i listan kolumnerna i listan.

**Användare utan rätt delningsbehörighet kan bifoga anpassade formulär till objekt**

_Anpassad Forms_

När ett anpassat formulär i den nya [!DNL Adobe Workfront]-upplevelsen är inställd på att vara synligt i hela systemet, kan alla användare koppla det anpassade formuläret till ett objekt. De bör dock bara kunna visa det anpassade formuläret och inte kunna bifoga det till ett objekt om det inte har delats specifikt med dem.

+++

+++**Underhållsuppdatering 16 september 2021**

**Kan inte redigera grupper**

_Grupper_

När en användare försöker redigera eller ta bort en grupp, redigeras eller tas inte gruppen bort och användaren ser följande meddelande:

[!UICONTROL Let's try that again. Group with primary key value(s) "(Group's ID)" not found]

**[!UICONTROL Portfolio Optimizer]visar inte projekt**

_Portfolio_

När en användare försöker visa projekt i [!UICONTROL Portfolio Optimizer] visas inte projektlistan och användaren kan därför inte interagera med projekten.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 10 september 2021**

**Datum och tid markerat som UTC vid redigering av infogad**

_Listor_

När en användare redigerar ett datum eller en tid textbundet (i en lista med objekt) markeras datumet och tiden som UTC. Datum och tid har inte angetts i UTC i [!DNL Workfront]. Det här problemet påverkar bara visningen, inte själva informationen.

**Textfärgen visas inte korrekt när villkorlig formatering används**

_Rapporter_

När en användare visar en rapport med villkorsstyrd formatering som ändrar textfärgen, visas textfärgen som oförändrad.

+++

+++**Underhållsuppdatering 9 september 2021**

**Problem visas inte med probleminformation**

_Startsida_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen väljer ett problem i [!UICONTROL Work List] visas vissa fält i förhandsvisningen i den högra panelen som om inga värden har angetts. Om du navigerar till problemet och visar [!UICONTROL Issue Details] har dessa fält värden angetts.

**Användare behöver Contribute-behörighet för att kunna visa avsnittet [!UICONTROL Approvals] i den nya Workfront Experience**

_Godkännanden_

Användarna behöver [!UICONTROL Contribute] behörigheter för ett objekt för att kunna visa avsnittet [!UICONTROL Approvals] i den nya [!DNL Workfront]-upplevelsen. De behöver bara [!UICONTROL View] behörigheter för att visa fliken [!UICONTROL Approvals] när det finns en godkännandeprocess för objektet.

**[!UICONTROL Whoops]-fel vid användning av filter**

_Listor_

När en användare försöker använda något av följande filter:

* [!UICONTROL All Projects]
* [!UICONTROL Projects I'm On]
* [!UICONTROL My Current Tasks]

listan blir tom och användaren ser följande fel:

[!UICONTROL Let's try that again.]

**[!UICONTROL Tasks]-avsnittet blir tomt när infogad** redigeras

_Mallar_

När en användare försöker att infoga redigeringsåtgärder i en mall med hjälp av en vy som innehåller fältet [!UICONTROL Assign To: Name] och tilldelningen innehåller en användare, blir avsnittet [!UICONTROL Tasks] tomt och användaren kan inte redigera malluppgifterna.

**Kan inte exportera[!UICONTROL Portfolio Optimizer]**

_Portfolio_

När en användare försöker exportera [!UICONTROL Portfolio Optimizer] och klickar på något av exportalternativen, exporteras inte [!UICONTROL Portfolio Optimizer].

**Meddelanden skickas inte för svar**

_Meddelanden_

När en användare svarar på en uppdatering i [!DNL Workfront] får andra användare i kommentarstråden inga meddelanden.

**Ändringar av anpassade data orsakar fördröjning**

_Anpassade fält_

När en användare ändrar anpassade data som utlöser ändringar av andra visade data, läses ändringarna in långsamt.

**Ikonen [!UICONTROL Collapse or Expand All] för gruppering visas inte**

_Rapportering_

Ikonen [!UICONTROL Collapse or Expand All] visas inte i huvudet i en lista eller rapport när grupperingar används i listan eller rapporten.

Alternativen **[!UICONTROL Check]och [!UICONTROL Cancel] visas inte när aktivitetsallokeringar ändras**

_[!UICONTROL Workload Balancer]_

När en användare försöker ändra uppgiftstilldelningen för en aktivitet och tidsramen för den uppgiften sträcker sig till eller utanför kanten av den synliga sidan, visas inte knapparna [!UICONTROL Check] och [!UICONTROL Cancel] och användaren kan inte spara eller avbryta allokeringsändringarna.

**Om du lägger till ett anpassat fält i [!UICONTROL Home] saknas fältdata**

_[!UICONTROL Home]_

När ett anpassat fält läggs till i [!UICONTROL Home] börjar andra fält att saknas och visas felaktigt.

**Det går inte att visa länkade objekt när du är inloggad som en annan användare**

_Integrationer_

Om en administratör försökte visa länkade objekt från en extern leverantör när han var inloggad som en annan användare, kunde han/hon inte öppna de länkade mapparna och kunde inte visa objekten.

+++

+++**Underhållsuppdatering 2 september 2021**

**Det går inte att fästa den anpassade instrumentpanelen**

_Instrumentpaneler_

När en användare försöker fästa en anpassad kontrollpanel fästs inte instrumentpanelen och användaren ser följande fel:

[!UICONTROL Something went wrong while pinning. Please contact [!DNL Workfront] so we can fix this.]

**[!DNL Workfront Proof]utskriftssammanfattning är tom**

[!DNL Workfront Proof]

När en användare öppnar utskriftssammanfattningen för att skriva ut ett korrektur visas rubriken, men själva sammanfattningen är tom.

+++


## Uppdateringar i augusti 2021

+++**Underhållsuppdatering 26 augusti 2021**

**I [!DNL Safari] finns en mörkgrå bakgrund i kolumnrubrikernas text**

_Listor_

I webbläsaren [!DNL Safari] finns det en mörkgrå bakgrund i kolumnrubriker som markerar texten. Detta är inte något problem med andra webbläsare som stöds.

**Oväntat fel vid inställning av föregående aktiviteter**

_Uppgifter_

När en användare försöker ange en aktivitet som en föregångare med hjälp av en infogad redigering, ställs föregående aktivitet inte in och användaren ser följande meddelande:

[!UICONTROL An unexpected error happened]

+++

+++**Underhållsuppdatering 19 augusti 2021**

**Sparade filter saknas efter att du har valt ett filter som inte innehåller några problem**

_Listor_

Sparade filter saknas i en lista med problem efter att du har valt ett filter som inte visar några resultat.

**Problem visas inte med probleminformation**

_[!UICONTROL Home]sammanfattning_

När en användare i [!DNL Adobe Workfront Classic] väljer ett problem i [!UICONTROL Work List] visas vissa fält som saknar värden i förhandsvisningen på den högra panelen. Om du navigerar till problemet och visar [!UICONTROL Issue Details] har dessa fält värden angetts.

+++

+++**Underhållsuppdatering 12 augusti 2021**

**Det går inte att anpassa den flexibla vyn i projektet**

_Agile_

När en användare försöker anpassa en tidigare flexibel vy i ett projekt stängs fönstret och användaren kan inte redigera vyn.

**Namnet ändras inte för nya dokumentversioner**

_Dokument_

När en användare överför en ny version av ett dokument uppdateras inte dokumentnamnet så att det matchar den senaste versionens namn.

**Föregående ikon blir inte grön när föregångaren är klar.**

_Uppgifter_

När en aktivitet har en föregående aktivitet och den föregående aktiviteten är slutförd, blir ikonen för föregående aktivitet inte grön.

När ett anpassat formulär i den nya [!DNL Adobe Workfront]-upplevelsen är inställd på att vara synligt i hela systemet, kan alla användare koppla det anpassade formuläret till ett objekt. De bör dock bara kunna visa det anpassade formuläret och inte kunna bifoga det till ett objekt om det inte har delats specifikt med dem.

+++

+++**Underhållsuppdatering (snabbkorrigering) 6 augusti 2021**

**Det går inte att välja kalendrar i [!DNL Outloo]k-kalenderinställningarna**

_Startsida_

När en användare i den nya [!DNL Workfront]-upplevelsen visar sin [!DNL Outlook]-kalender hemma och öppnar inställningarna, saknas kryssrutorna för att välja kalendrar. Om användaren klickar på var kryssrutan skulle vara svarar kalendern som om kryssrutan var där.

**Det går inte att återauktorisera eller verifiera anslutningen till[!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] användare med scenarier som ansluter till [!UICONTROL Webdam] bör vara medvetna om att [!UICONTROL Webdam]-anslutningar kräver manuell omautentisering var 14:e dag. API:t [!UICONTROL Webdam] stöder för närvarande inte automatisk omauktorisering.

+++

+++**Underhållsuppdatering 5 augusti 2021**

**Det går inte att interagera med dokumentet på [!UICONTROL Summary panel] - eller [!UICONTROL More]-menyn**

_Dokument_

När en användare i den nya [!DNL Workfront]-upplevelsen visar ett dokument och försöker göra ett val på menyn [!UICONTROL Summary panel] eller [!UICONTROL More] avmarkeras dokumentet, vilket gör att menyn [!UICONTROL Summary panel] eller [!UICONTROL More] inte visas.

Knappen **[!UICONTROL New Request]saknas**

_Begäranden_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen går till sidan [!UICONTROL Requests] visas inte knappen [!UICONTROL New Request] och de kan inte skicka en begäran.

**Användare utan rätt delningsbehörighet kan bifoga anpassade formulär till objekt**

_Anpassad Forms_

När ett anpassat formulär i den nya [!DNL Adobe Workfront]-upplevelsen är inställd på att vara synligt i hela systemet, kan alla användare koppla det anpassade formuläret till ett objekt. De bör dock bara kunna visa det anpassade formuläret och inte kunna bifoga det till ett objekt om det inte har delats specifikt med dem.

**Det går inte att ändra korrekturinställningar när ett nytt korrektur skapas**

_[!DNL Workfront Proof]_

När en användare skapar ett nytt korrektur och försöker ändra inställningarna, återställs inställningen till en tidigare inställning.

**[!UICONTROL Story Board]läses inte in korrekt**

_Agile_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen navigerar till en [!UICONTROL Story Board] kan det ta upp till 10 sekunder att läsa in anslagstavlan. Förseningen med inläsningen beror på att systemet läser in alla kort när det bara ska läsa in 50 kort åt gången.

+++


## Uppdateringar i juli 2021

+++**Underhållsuppdatering (snabbkorrigering) den 29 juli 2021**

**Det gick inte att överföra nytt korrektur eller ny korrekturversion**

_[!DNL Workfront Proof]_

När en användare försöker överföra ett nytt korrektur eller en ny version av ett korrektur i den klassiska [!DNL Workfront]-upplevelsen, är den nya korrektursidan eller den nya versionen tom och användaren kan inte överföra korrekturet eller versionen.

+++

+++**Underhållsuppdatering 29 juli 2021**

**[!UICONTROL Proof Activity]och [!UICONTROL Proof Viewer Settings] sidor är alltid tillgängliga**

_[!DNL Workfront Proof]_

Sidorna [!UICONTROL Proof Activity] och [!UICONTROL Proof Viewer] Inställningar visas nu alltid, även om användaren inte har tillgång till att uppdatera sidorna.

Tidigare var inte alltid sidorna [!UICONTROL Proof Activity] och [!UICONTROL Proof Viewer Settings] till vänster synliga när en användare med en anpassad behörighetskontroll navigerade till ett dokument.

**Felmeddelande när alternativet [!UICONTROL Percentage] för[!UICONTROL Allocated hours]** används

_[!UICONTROL Workload Balancer]_

När en användare väljer alternativet [!UICONTROL Percentage] för [!UICONTROL Allocated hours] och det finns arbeten i avsnittet [!UICONTROL Unassigned work] ser användaren följande fel:

[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

+++

+++**Underhållsuppdatering 22 juli 2021**

**Nya namn på korrekturversioner klipps ut**

_[!DNL Workfront Proof]_

När en användare i [!DNL Adobe Workfront Classic] överför en ny version av ett korrektur som innehåller en punkt i filnamnet, avbryts filnamnet vid slutet.

+++

+++**Underhållsuppdatering (snabbkorrigering) 19 juli 2021**

**Fel vid navigering till projekt, tidrapporter, aktiviteter eller program**

När en användare försöker navigera till projekt, tidrapporter, aktiviteter eller program i den nya [!DNL Adobe Workfront]-upplevelsen visas felmeddelandet [!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

+++

+++**Underhållsuppdatering 15 juli 2021**

**Standardprioriteten för nya begäranden är felaktig**

_Begäranden_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen skapar en begäran, uppfyller begäran inte standardprioriteten som angetts i [!UICONTROL Project Preferences] och kan inte justera prioriteten innan den skickas.

**[!UICONTROL Go to proof]-länken leder inte till kommentaren**

_E-postmeddelanden_

När en användare får ett e-postmeddelande om en korrekturkommentar och klickar på [!UICONTROL Go to proof] dirigeras de till fel kommentar i korrekturet eller så dirigeras de inte till någon kommentar alls.

**RTF-fältvärden som inte överförs efter konvertering av ett problem till en aktivitet**

_Anpassad Forms_

När en användare konverterar en utgåva till en uppgift och utgåvan har ett bifogat anpassat formulär med ett värde som anges i ett textfält med formatering av RTF, överförs inte värdet i textfältet efter konverteringen.

**Anpassade fältvärden ändras efter markering**

_[!DNL Workfront Proof]_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen skapar ett nytt korrektur och anger ett värde i vissa anpassade fält på ett korrektur, återställs värdet i vissa tidigare fält till standardvärdena i stället för det värde som användaren angav.

**[!UICONTROL Assign to]-typhuvud fungerar inte**

_[!UICONTROL Home]_

När en användare i [!DNL Adobe Workfront Classic] skapar ett projekt, en aktivitet eller en begäran från området [!UICONTROL Home] fyller inte typsnittsfältet [!UICONTROL Assign to] i användarnamnen.

**Timmars avrundning felaktigt**

_Tidrapporter_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen navigerar till [!UICONTROL Timesheets] > [!UICONTROL All Timesheets] ser de att det totala antalet timmar för vissa tidrapporter avrundas till en decimal i stället för i steg om 0,25, men det totala antalet timmar visas korrekt i den enskilda tidrapporten. I området Alla tidrapporter visar till exempel en tidrapport totalt 44,8 timmar, men när du öppnar tidrapporten visas totalt 44,75 timmar.

**Det går inte att delegera godkännanden**

_[!UICONTROL Home]_

När en användare i [!DNL Adobe Workfront Classic] klickar på [!UICONTROL Delegate My Approvals] i området [!UICONTROL Home] och börjar skriva namnet på den användare som han/hon försöker delegera till, visas inga resultat i listan [!UICONTROL typeahead] och användaren kan inte välja någon användare.

Vyn **[!UICONTROL Gantt Chart]är inte tillgänglig för aktivitetsrapporter**

_Rapporter_

Obs! Detta påverkar även projektrapporter.

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen öppnar en uppgiftsrapport saknas alternativet att välja en [!UICONTROL Gantt Chart]-vy i rapportverktygsfältet. Om vyn [!UICONTROL Gantt Chart] är markerad att visas som standard i rapporten visas i stället ett listformat.

**Om du klickar på [!UICONTROL See More] i rapporten läses ingenting in**

_Instrumentpaneler_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen visar en rapport på en instrumentpanel och klickar på knappen [!UICONTROL See More] händer ingenting och de kan inte visa alla objekt i rapporten.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 1 juli 2021**

**Kopiering av moduler fungerar inte**

_[!DNL Adobe Workfront Fusion]_

När en användare markerar flera moduler och försöker kopiera och klistra in dem, klistras inte modulerna in.

+++

+++**Underhållsuppdatering 1 juli 2021**

**Färguppsättningen för kort respekteras inte**

_Kanban_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen anger specifika kortfärger i teaminställningarna återspeglas inte dessa färger på Kanban-korten.

**Det går inte att klistra in text i det anpassade meddelandefältet**

_[!DNL Workfront Proof]_

När en användare skapar ett nytt korrektur i [!UICONTROL Web Proofing Viewer] och försöker klistra in text i fältet [!UICONTROL Message] i avsnittet [!UICONTROL Email notification], kan de inte klistra in texten. Det här händer bara när texten har styckeformatering och det finns en styckebrytning.

**Begäranden skickas med tomma obligatoriska fält**

_Begäranden_

När en användare gör en begäran och skickar den, skickas ingen information i obligatoriska fält tillsammans med begäran.

Knappen **[!UICONTROL New Request]saknas**

_Begäranden_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen går till sidan [!UICONTROL Requests] visas inte knappen [!UICONTROL New Request] och de kan inte skicka en begäran.

**Det uppstod ett fel när ett anpassat formulär skulle expanderas**

_Projekt_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen försöker expandera ett anpassat formulär som är kopplat till ett projekt, kan de inte öppna det anpassade formuläret och felmeddelandet [!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]  som uppdateras på sidan löser inte problemet.

Varumärkningen **[!DNL Adobe Workfront]visas nu i e-postmeddelanden från meddelandecentret**

E-post

När varumärket [!DNL Adobe Workfront] introduceras i hela programmet har följande uppdateringar gjorts i meddelandena från meddelandecentret:

* [!DNL Adobe Workfront]-lejonet lades till i huvudinnehållsområdet.
* [!DNL Adobe Workfront]-logotypen lades till i sidfoten.

I framtiden kommer den här profileringen att visas på fler typer av e-postmeddelanden från Workfront.

+++


## Uppdateringar i juni 2021

+++**Underhållsuppdatering 24 juni 2021**

**Kan inte redigera ett team**

_Agile_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen klickar på [!UICONTROL Edit] för att öppna [!DNL Edit] Team-sidan för ett Agile-team läses sidan in först, sedan försvinner inställningarna och den blir tom.

**Data har tagits bort från den skickade begäran**

_Begäranden_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen fyller i en begäran, saknar den skickade begäran de angivna värdena för vissa anpassade fält, ibland även fält som är obligatoriska.

**Kolumner visas inte**

_Kanban_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen lägger till en anpassad [!UICONTROL Additional Fields]-kolumn i en Kanban-styrelse, visas inte alla kolumnrubriker.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering 23 juni 2021**

**Borttagen bruten länk i meddelandena**

_[!DNL Adobe Workfront Fusion]_

Vi har tagit bort länken till meddelandeinställningarna från [!DNL Adobe Workfront Fusion] e-postmeddelanden.
Mer information om hur du ändrar meddelandeinställningar finns i [!DNL Adobe Workfront Fusion] organisationer och team.

+++

+++**Underhållsuppdatering 17 juni 2021**

Vyn **[!UICONTROL Gantt Chart]är inte tillgänglig för aktivitetsrapporten**

_Rapporter_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen öppnar en uppgiftsrapport saknas alternativet att välja en [!UICONTROL Gantt Chart]-vy i rapportverktygsfältet. Om vyn [!UICONTROL Gantt Chart] är markerad att visas som standard i rapporten visas i stället ett listformat.

**Teckenbegränsningsfel uppstår inte vid inskickade begäranden**

_Begäranden_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen försöker skicka en begäran och de överskrider teckengränsen för ett fält, kan de inte skicka begäran och inget felmeddelande visas. I [!DNL Adobe Workfront Classic] ser användaren varningen [!UICONTROL [number] characters over" and when they attempt to submit the request, they see the error message "Please check the following: Please enter no more than 2000 characters (you entered [number] characters).]

+++

+++**Underhållsuppdatering 10 juni 2021**

**Ordnade malluppgifter flyttas inte**

_Mallar_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen drar en malluppgift till en ny plats i en lista uppdateras antalet malluppgifter, men ordningen ändras inte.

**Underordnade aktiviteter är inte markerade med överordnade aktiviteter**

_Mallar_

När en användare väljer en överordnad uppgift i ett projekt som skapats från en mall markeras inte de underordnade uppgifterna automatiskt.

**Alla milstolpar för infogad redigering i en uppgiftslista visar alla milstolpar**

_Projekt_

När ett projekt har en milstolpe tillagd och en användare i den nya [!DNL Adobe Workfront]-upplevelsen infogar en infogad [!UICONTROL Milestone: Name]-kolumn i aktivitetslistan, visas alla milstolpsökvägar i listrutan i stället för bara milstolpsökvägarna som har kopplats till det projektet.

+++

+++**Underhållsuppdatering 3 juni 2021**

**Fråga gör att sidan skakas**

_Rapporter_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen kör en rapport med en fråga, flyttas kolumnerna i rapporten snabbt från vänster till höger.

**Vissa fraser på sidan [!UICONTROL New proof] översätts inte korrekt**

_[!DNL Workfront Proof]_

När en användare navigerar till sidan [!UICONTROL New proof creation] i [!DNL Workfront Proof] och innehållet översätts till ett annat språk än engelska, visas vissa fraser fortfarande på engelska.

**Etiketter som har inaktiverats och tagits bort har lagts till för användare[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Deactivated] och [!UICONTROL Deleted] användaretiketter har lagts till i följande områden i [!DNL Workfront] Korrektur:

* [!UICONTROL Proof details] sida
* [!UICONTROL Proofing views]
* [!UICONTROL Proofing viewer]
* [!UICONTROL Proofing workflows]
* [!UICONTROL Print comments] sida
* [!UICONTROL User] sida

+++


## Uppdateringar i maj 2021

+++**Underhållsuppdatering 27 maj 2021**

**[!UICONTROL Commit Date]-kalendern visas för uppdateringar**

_Uppgifter_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen anger en uppdatering för en uppgift, visas [!UICONTROL Commit Date]-kalendern utan att användaren behöver markera fältet [!UICONTROL Commit Date].

**[!UICONTROL More]-menyn saknas i filter, vyer och grupperingar**

_Listor_

När en användare i den nya [!DNL Adobe Workfront]-upplevelsen visar filter, vyer eller grupperingar för en lista saknas menyikonen [!UICONTROL More] , vilket förhindrar att användaren delar eller - om han eller hon har åtkomst till den - tar bort filter, vyer eller grupperingar.

**Kopiera och klistra in ett projekt [!UICONTROL Reference Number] lägger till [!UICONTROL This]**

_Projekt_

När en användare i den nya [!DNL Workfront]-upplevelsen navigerar till ett projekt, kopierar [!UICONTROL Reference Number] från [!UICONTROL Overview]-området och klistrar in det, läggs ordet [!UICONTROL This] till i slutet av talet.

**[!UICONTROL Daily Digest]e-postmeddelanden skickas när de är inaktiverade**

_E-postmeddelanden_

Vissa användare får [!UICONTROL Daily Digest] e-postmeddelanden när de inte har aktiverats i sina användarinställningar.

**Objektet finns inte längre, fel**

_Objekt_

När en användare i den nya [!DNL Workfront]-upplevelsen försöker öppna vissa objekt visas felmeddelandet [!UICONTROL The (object) no longer exists: You may have mistyped the web address. Double check it and try entering the address again.]. Objektlänken visas fortfarande i listor, senaste händelser, favoriter, sökresultat osv., men de kan inte komma åt den och den visas inte i papperskorgen med borttagna objekt.



+++

+++**Underhållsuppdatering 20 maj 2021**

**Korrekturalternativ saknas**

_Korrektur_

När en användare överför en annan version av ett korrektur i [!DNL Workfront] saknas länkarna [!UICONTROL Open Proof] och [!UICONTROL Proofing Workflow], vilket gör att det verkar som om det är ett dokument i stället för ett korrektur. När länkarna saknas visas etiketten [!UICONTROL Pending] också och andra användare kan inte generera korrekturet när den har statusen [!UICONTROL Pending].

**Användare som inte tar emot schemalagda rapportleveranser**

_Rapporter_

När vissa rapporter är schemalagda för rapportleverans, kanske användarna inte får rapporterna.

**Det går inte att ta bort åtkomst för layoutmallen**

_Instrumentpaneler_

När en användare öppnar [!UICONTROL Sharing] alternativ för en kontrollpanel för att ta bort åtkomst för en layoutmall visas ingen [!UICONTROL Delete]-ikon bredvid layoutmallen och användaren kan inte ta bort åtkomst.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 17 maj 2021**

**Organisationsinstrumentpanelen visar nu antalet aktiva scenarier korrekt**

_[!DNL Workfront Fusion]_

Instrumentpanelen [!UICONTROL Organization] visade tidigare ett tomt fält i stället för antalet scenarier som används.

**Bläddring i datalagret visar nu kolumnrubriker**

_[!DNL Workfront Fusion]_

Datastrukturer som använde kolumnrubriker tidigare visade kolumnnamnet i vyn [!UICONTROL data store browsing].  Nu visas kolumnetiketten.  Om ingen etikett identifieras för kolumnen visas kolumnnamnet.

**Scenarioinitieringsfel påverkar inte längre webkrockdata**

_[!DNL Workfront Fusion]_

Tidigare var det ett webhock-initierat scenario (inklusive de som använder en realtidshändelse för att utlösa) som påträffade ett fel under scenarioinitieringen som skulle kunna resultera i att åtkomsten till webkrockdata skulle gå förlorad.  Om ett fel inträffar under scenarioinitieringen (t.ex. att det inte går att verifiera en anslutning) behålls webbkrokdata i webkrokkön och körningen görs automatiskt om.  Efter tre misslyckade försök inaktiveras scenariot och informationen finns kvar i kön.

**Poster i webkrokköer bearbetas nu i mindre grupper**

_[!DNL Workfront Fusion]_

Tidigare, om en användare aktiverade ett inaktivt scenario med en associerad webkrok med många poster, skulle [!DNL Workfront Fusion] försöka att bearbeta hela kön i en enda körning (om än flera cykler).  Beroende på hur många poster som har bearbetats kan detta ibland medföra att den enskilda körningen överskrider den maximala körningstiden (40 minuter).  När du nu aktiverar ett inaktivt scenario som har en associerad webbkrokkö med poster, bearbetas Workfront Fusion upp till det maximala antalet poster som identifieras i en enskild körning (vanligtvis 2 poster per körning).

**Datalager visar nu korrekt 0-värden**

_[!DNL Workfront Fusion]_

Tidigare visades datalagringsvärden på 0 som tomma. &lt;...>

+++

+++**Underhållsuppdatering 13 maj 2021**

**Nedrullningsbar kalender visas bakom [!UICONTROL Unassigned Work] header**

_[!UICONTROL Workload Balancer]_

När en användare navigerar till [!UICONTROL Workload Balancer] i [!DNL Workfront Classic] döljs datumväljarens överkant bakom rubriken [!UICONTROL Unassigned Work], vilket förhindrar användaren från att navigera till olika månader.

**Det går inte att klistra in text i det anpassade meddelandefältet**

_[!DNL Workfront Proof]_

Obs! Det här problemet verkar bara påverka webbläsaren [!DNL Google Chrome] för tillfället.

När en användare skapar ett nytt korrektur i [!DNL Workfront Proof] och försöker klistra in text från ett e-postmeddelande i fältet [!UICONTROL Message] i avsnittet [!UICONTROL Email notification], kan de inte klistra in texten.

**Fält som inte stöds visas i verktyget**

_Anpassad Forms_

När en användare skapar ett anpassat formulär och försöker skapa ett beräkningsfält med ett dynamiskt fält, t.ex. [!UICONTROL Number of Open Risks], markeras den röda beräkningsrutan och du kan inte spara ändringarna. Dynamiska fält ska inte visas i väljaren för beräknade fält.

**Förhandsgranska för aktiviteter i [!UICONTROL Work List] läses inte in**

_Startsida_

När en användare i den nya [!DNL Workfront]-upplevelsen tilldelas en layoutmall som innehåller anpassade fält på [!UICONTROL Home] svarar inte sidan och läser inte in uppgifter från [!UICONTROL Work List] om användarna väljer dem.

**Objekt i [!UICONTROL Work List] läses inte in i[!UICONTROL Home]**

_[!UICONTROL Home]_

När en användare klickar på ett objekt i [!UICONTROL Home Work List] visas objektets rubrik på den högra panelen, men informationen om objektet visas inte. Användaren ser meddelandet [!UICONTROL Pages Unresponsive.] till slut

**Problem med RTF-fält i[!DNL Microsoft Outlook]**

_Workfront-integreringar_

När en användare uppdaterar ett RTF-fält med integreringen [!DNL Workfront for Outlook] kan de inte:

* Backsteg
* Kopiera text
* Klistra in text
* Skicka en begäran när alla fält är ifyllda

+++

+++**Underhållsuppdatering 6 maj 2021**

Fältet **[!UICONTROL Currency]fungerar inte som förväntat**

_Listor_

När en användare försöker redigera fältet Aktuellaktivitet i en lista kan de inte spara ändringar på grund av följande problem:

* Aktivitets- och problemlistor tillåter inte indata för valutasymboler
* Visar en lista som inte tillåter inmatning av valutabförkortningar när andra språk än engelska används
* Underuppgifts- och utleveranslistor som endast tillåter valutakombinationen USD, oavsett den angivna projektvalutan

**Namnet uppdateras inte så att det matchar det nya korrekturnamnet**

_Dokument_

När en användare skapar en ny version av ett korrektur och uppdaterar korrekturnamnet, behåller dokumentobjektet i [!DNL Workfront] det ursprungliga namnet i stället för att matcha det nya korrekturnamnet.

**[!UICONTROL Business Case]-knappar fungerar inte när anpassade formulär bifogas**

_Projekt_

När ett projekt i den nya [!DNL Workfront]-upplevelsen skapas från en projektmall och det finns ett anpassat formulär bifogat, kan användarna inte skicka, avvisa eller godkänna ett affärsärende.

**Arkiverade korrektur som visas i listor och rapporter**

_Korrektur_

När en användare visar sin arbetslista i [!UICONTROL Home] eller [!UICONTROL My Work] visas korrektur som redan har arkiverats i listan. Arkiverade korrektur visas också på rapporter och kontrollpaneler.

**Projekt som skapats från mallen har felaktiga åtkomstinställningar**

_Projekt_

När en användare skapar ett projekt från en mall överförs inte mallens åtkomstinställningar till det nya projektet.

**Objekt i [!UICONTROL Work List] läses inte in i[!UICONTROL Home]**

_[!UICONTROL Home]_

När en användare klickar på ett objekt i [!UICONTROL Home Work List] visas objektets rubrik på den högra panelen, men informationen om objektet visas inte. Användaren ser meddelandet [!UICONTROL Pages Unresponsive.] till slut

+++


## Uppdateringar i april 2021

+++**Underhållsuppdatering 29 april 2021**

Integrationen **[!DNL SharePoint]autentiserar med hjälp av autentiseringsuppgifter från en separat integrering**

_Workfront-integreringar_

När en användare har mer än en [!DNL SharePoint]-integrering försöker en [!DNL SharePoint]-autentisering autentisera med autentiseringsuppgifterna för en annan [!DNL SharePoint]-integrering.

**Det går inte att överföra eller exportera filer från [!DNL Adobe] products**

_Workfront-integreringar_

När en användare försöker överföra eller exportera filer med hjälp av [!DNL Workfront for Adobe Creative Cloud]-integreringen visas felmeddelandet [!UICONTROL Cannot read property 'stages' of undefined] och kan inte överföra eller exportera filerna.

**Filerna är inte synliga i[!DNL Internet Explorer]**

_Dokument_

När en användare med en [!DNL Internet Explorer]-webbläsare navigerar till [!UICONTROL Documents]-området för ett objekt är [!UICONTROL Documents]-skärmen tom och läser inte in filerna. För vissa användare läser skärmen in vissa filer, men antalet filer som visas matchar inte antalet som visas bredvid avsnittet [!UICONTROL Documents].

+++

+++**Underhållsuppdatering 22 april 2021**

**Uppgifter har lagts till i fel ordning**

_Mallar_

När en användare lägger till en uppgift i en mall, får uppgiften inte det aktivitetsnummer han eller hon förväntar sig och uppgiften läggs till på fel plats.

**Korrektur kombineras nu till ett enda e-postmeddelande**

_Korrektur_

[!DNL Workfront] skickar nu ett e-postmeddelande för kombinerade korrektur i stället för att skicka ett e-postmeddelande för varje fil som ingår.
+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 15 april 2021**

**[!UICONTROL Scenario rejected]-fel vid körning av scenario**

_[!DNL Workfront Fusion]_

När en användare försöker köra ett scenario körs inte scenariot och användaren får meddelandet [!UICONTROL Scenario rejected.]

+++

+++**Underhållsuppdatering 15 april 2021**

**[!UICONTROL Workload Balancer]visar felaktiga planerade timmar**

_[!UICONTROL Workload Balancer]_

När en användare tittar på en uppgifts planerade timmar i [!UICONTROL Workload Balancer] matchar värdet för de planerade timmarna inte de planerade timmarna som tilldelats aktiviteten.

**Det övre navigeringsfältet visas inte i[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

När en användare navigerar till någon annan [!DNL Workfront Proof]-sida än kontrollpanelssidan, försvinner det övre navigeringsfältet. Användaren kan inte komma åt funktionerna i navigeringsfältet, t.ex. kontoinställningarna eller profilen.

**Förbättrade anpassade formulär**

_Anpassade formulär_

För att få en bättre upplevelse när du fyller i ett anpassat formulär har vi förbättrat hur långa anpassade fältetiketter visas. När det finns tillräckligt med vågrätt utrymme för att visa dem i sin helhet trunkeras inte längre dessa etiketter.

+++

+++**Underhållsuppdatering 8 april 2021**

**Det går inte att skapa korrektur i [!DNL Adobe Creative Cloud] integration**

_Workfront-integreringar_

När en användare försöker skapa ett korrektur direkt från [!DNL Adobe Creative Cloud] genereras inte korrekturet.

+++

+++**Underhållsuppdatering 1 april 2021**

**Problem med att visa sammanfattningspanelen i[!DNL Chrome]**

_[!UICONTROL Summary]_

När en användare öppnar panelen [!UICONTROL Summary] när han eller hon använder webbläsaren [!DNL Chrome] beter sig sammanfattningspanelens gränssnitt inte som förväntat. Användaren kan inte rulla, ikonerna kan försvinna och innehållet kan överlappa annat innehåll.

Området **[!UICONTROL Teams]i [!UICONTROL Setup] visar inte alla team**

_[!UICONTROL Setup]_

När en administratör går till [!UICONTROL Teams]-området för [!UICONTROL Setup] kan de bara visa team som de har skapat. Team som har skapats av andra administratörer visas inte.

**Det går inte att lägga till uppdateringar i projektet med [!UICONTROL Pending Approval] status**

_Projekt_

Om en användare försöker lägga till en uppdatering i ett projekt med statusen [!UICONTROL Pending Approval], och de inte är den användare som har tilldelats behörigheten att godkänna projektet, läggs uppdateringen inte till och följande meddelande visas:

Ett projekt med statusen [!DNL Pending Approval] kan inte redigeras. Du kan ändra projektet genom att ändra status.

+++


## Uppdateringar i mars 2021

+++**Underhållsuppdatering 26 mars 2021**

**Knappar i ett affärsärende visas felaktigt**

_Projekt_

När en användare visar ett affärsärende och fönstret är i helskärmsläge visas knapparna [!UICONTROL Save] och [!UICONTROL Cancel] nära skärmens mitt, med överlappande element för affärscase.

**Det går inte att ändra sortering för en rapport**

_Rapporter_

När en användare försöker ändra sorteringen av en rapport i den nya [!DNL Workfront]-upplevelsen ändras inte sorteringen från den sortering som valdes när rapporten skapades.

**Delning inaktiverad för nya korrektur**

_[!DNL Workfront Proof]_

När en användare som har [!UICONTROL Public Sharing] aktiverat i standardkorrekturinställningarna skapar ett korrektur skapas korrekturet med delning inaktiverat. Andra användare kan inte se knappen [!UICONTROL Share] eller dela korrekturet.

**[!UICONTROL Proof failed to generate]-fel vid skapande av korrektur**

_[!DNL Workfront Proof]_

När en användare försöker skapa ett korrektur skapas inte korrekturet och användaren ser följande felmeddelande:

[!UICONTROL Proof failed to generate -- internal error]

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 25 mars 2021**

**Den redundanta samlingen eller referensfältet har tagits bort från mappningspanelen**

_[!DNL Workfront Fusion]2.0_

När en användare använder en term från API:t [!DNL Workfront] för att välja en samling eller ett referensfält som ska inkluderas i utdata från en [!DNL Workfront]-modul, visar utdata för den modulen det fältet med ett kolon (till exempel [!UICONTROL owner:name]) och även i attributen (namnet är ett fält under ägare). Fältet som är märkt med ett kolon innehåller inga data och ger felaktiga data om de mappas till en modul senare i scenariot.

+++

+++**[!DNL Workfront Fusion]Underhållsuppdatering 18 mars 2021**

**Projektmallsinställningarna gäller nu för projekt som skapats med [!DNL Workfront Fusion] 2.0**

_[!DNL Workfront Fusion]2.0_

När du skapar ett projekt från en mall med hjälp av [!DNL Workfront Fusion] 2.0 används mallinställningarna för det nya projektet. Detta fungerar på samma sätt när du skapar ett projekt från en mall i programmet [!DNL Workfront].

+++

+++**Underhållsuppdatering 18 mars 2021**

**Projektmallsinställningarna gäller nu för projekt som skapats med API:t**

_[!DNL Workfront]API_

När du skapar ett projekt från en mall med API:t [!DNL Workfront] används mallinställningarna på det nya projektet. Detta fungerar på samma sätt när du skapar ett projekt från en mall i programmet [!DNL Workfront].

+++

+++**Underhållsuppdatering (snabbkorrigering) den 15 mars 2021**

**Delad komponent fungerar inte som förväntat**

_[!DNL Workfront Proof]_

Om fristående [!DNL Workfront Proof]-konton flyttas till en delad komponent kan följande funktioner uppstå när en användare lägger till en ny version av ett korrektur eller dokument:

* Användaren kan inte ta bort användaren [!UICONTROL Studio Proof].
* Standardmeddelandet visas inte i den nya versionen.

**Delning av offentlig länk är inte aktiverat i en ny version av ett korrektur**

_Dokument_

När en användare aktiverar delning av offentlig länk i ett korrektur och sedan överför en ny version av korrekturet, aktiveras inte delning av offentlig länk automatiskt i den nya versionen av korrekturet.

**[!UICONTROL Approve], [!UICONTROL Changes], [!UICONTROL Reject] knappar saknas i korrektur**

_[!DNL Workfront Proof]_

När en användare visar ett korrektur i korrekturläsaren saknas knapparna [!UICONTROL Approve], [!UICONTROL Changes] och [!UICONTROL Reject] högst upp på skärmen.

**Det går inte att ändra sortering för en rapport**

_Rapporter_

När en användare försöker ändra sorteringen av en rapport i den nya [!DNL Workfront]-upplevelsen ändras inte sorteringen från den sortering som valdes när rapporten skapades.

**Anpassat meddelande vid korrektur som inte överförs till den nya versionen**

_[!DNL Workfront Proof]_

När en användare bifogar ett eget meddelande till ett korrektur och sedan överför en ny version av det korrekturet, visas inte det anpassade meddelandet på det nya korrekturet.

**Användarlistan visas inte**

_Listor_

När en användare försöker visa en användarlista och vyn innehåller kolumnen [!UICONTROL Status Icons] visas inte listan.

Alternativet **[!UICONTROL Notify recipients about this proof] är inaktiverat oavsett arbetsflödesinställningar**

_[!DNL Workfront Proof]_

När en användare skapar ett nytt korrektur och inte aktiverar alternativet [!UICONTROL Notify recipients about this proof] manuellt, meddelas inte den avsedda mottagaren. Detta gäller även om alternativet är aktiverat i arbetsflödesinställningarna.

**Det går inte att ändra tidsramen**

_[!UICONTROL Enhanced Analytics]_

När en användare tittar på [!UICONTROL Enhanced analytics] och klickar på kalendern för att justera datumintervallet ändras inte datumen.

**Det går inte att hämta offentligt delat dokument**

_Dokument_

När en användare klickar på en delad länk för att hämta ett dokument, hämtas inte dokumentet och användaren ser ett fel från webbläsaren som säger att sidan inte finns.

+++

+++**Underhållsuppdatering 11 mars 2021**

**Avsnitt i anpassat formulär exporteras inte för icke-administratörer**

_Anpassad Forms_

Om ett anpassat formulär som är kopplat till ett objekt har en avsnittsbrytning som kräver åtkomst över [!UICONTROL View] som krävs för att visa innehållet i avsnittet, kan inte avsnittets innehåll exporteras av någon annan än en administratör.

**Det hämtade dokumentet har felaktigt namn**

_[!DNL Workfront Proof]_

När en användare hämtar ett dokument från [!UICONTROL Proof viewer] har dokumentets namn som en tidigare version av dokumentet, inte den version som hämtades.

+++

+++**Underhållsuppdatering 4 mars 2021**

**Fel vid åtkomst av layoutmall**

_Layoutmallar_

När en användare som är registrerad i den nya [!DNL Workfront]-upplevelsen växlar till [!DNL Classic]-upplevelsen och försöker få åtkomst till en [!DNL Classic]-layoutmall visas felet [!UICONTROL That Page does not exist.]

**Kan inte redigera filter i[!UICONTROL Workload Balancer]**

_[!UICONTROL Workload Balancer]_

När en användare försöker redigera ett filter i [!UICONTROL Workload Balancer] öppnas inte filterverktyget.

Länken **[!UICONTROL See All Notifications] i e-postmeddelanden dirigeras om till en felaktig sida**

_E-postmeddelanden_

När en användare klickar på länken [!UICONTROL See All Notifications] i ett e-postmeddelande dirigeras de om till en sida med följande meddelande:

[!UICONTROL The User no longer exists. You may have mistyped the web address. Double check it and try entering the address again.]

**Användaren dirigeras inte till korrekturkommentaren som de är taggade i**

_E-postmeddelanden_

När en användare är taggad i en korrekturkommentar och klickar på länken [!UICONTROL Go To Proof] i ett e-postmeddelande dirigeras de till korrekturet, men inte till den specifika kommentaren. Om användaren är i [!DNL Workfront Classic] dirigeras de till sidan [!UICONTROL Document Details] i stället för till kommentaren i korrekturet.

**Användare har lagts till i [!DNL Workfront]-scenen som tar emot e-postmeddelanden**

_[!DNL Workfront Proof]_

När en användare som inte är med i arbetsflödet öppnar ett korrektur från [!DNL Workfront] skapar systemet automatiskt en fas, lägger till användaren i korrekturet och skickar ett [!UICONTROL New Proof]-e-postmeddelande.

**Panelen Dokumentsammanfattning blir mörkare, åtgärder blir inte tillgängliga**

_Dokument_

När en användare befinner sig på en dokumentsida och håller muspekaren över dokumentsammanfattningspanelen blir panelen mörkare och kan visa andra knappar. Användaren kan inte klicka på åtgärderna i sammanfattningspanelen.

**Uppdatera strömprestandaändringar**

_Uppdatera ström_

Vi har minskat antalet användaruppdateringar som visas på fliken [!UICONTROL Updates] från 50 till 25 i taget för att förbättra prestandan.

+++

+++**Underhållsuppdatering (snabbkorrigering) den 1 mars 2021**

**Inga nya korrekturmeddelanden skickas**

_[!DNL Workfront Proof]_

OBS! Det här problemet löstes i den nya [!DNL Workfront]-upplevelsen den 26 februari 2021.
Den korrigerades i [!DNL Classic]-upplevelsen den 1 mars 2021.

När en användare skapar ett nytt korrektur och aktiverar alternativet [!UICONTROL Notify recipients about this proof] skickas inget e-postmeddelande för att meddela mottagaren.

+++


## Uppdateringar i februari 2021

+++**Underhållsuppdatering 25 februari 2021**

Verktyget **[!UICONTROL Scheduling]läses inte in i något område**

_Resurshantering_

När en användare med en apostrof i användarnamnet försöker få åtkomst till verktyget [!UICONTROL Scheduling] i [!DNL Workfront Classic] är sidan tom och verktyget läses aldrig in.

**Namnet ändras inte för nya korrekturversioner**

_Dokument_

När en användare i den nya [!DNL Workfront]-upplevelsen överför en ny version av ett dokument med ett annat namn uppdateras inte namnet så att det matchar den senaste versionens namn.

**[!UICONTROL Document Share]-fel vid borttagning av projekt**

_Projekt_

När en systemadministratörsanvändare har åtkomst till ett projekt som har kopierats och de försöker ta bort det eller ta bort ett dokument i projektet, kan de inte ta bort objektet och felmeddelandet [!UICONTROL Document Share with primary key value(s) not found.] visas

**Användarrapporten tillämpar inte alla filter**

_Rapporter_

När en användare i den nya [!DNL Workfront]-upplevelsen skapar en användarrapport med en filterregel som innehåller fältet [!UICONTROL Top Parent ID], tillämpas inga andra filterregler i rapporten.

**Beräknade fält beräknas inte om efter redigering**

_Anpassad Forms_

När en användare i den nya [!DNL Workfront]-versionen redigerar och sparar ett anpassat formulär som innehåller beräknade fält uppdateras inte dessa fält.

**Dokument som tas bort när anpassat formulär tas bort**

_Anpassad Forms_

När en användare i den nya [!DNL Workfront]-funktionen tar bort ett anpassat formulär som är kopplat till dokument, tas även dessa dokument bort.

+++

+++**Underhållsuppdatering 18 februari 2021**

**Kryssrutan som inte behövs har tagits bort från [!UICONTROL Requests] område**

_Begäranden_

Vi har tagit bort kryssrutan till vänster om namnen på förfrågningarna i listan Skickat i området [!UICONTROL Requests]. Den här kryssrutan var inte kopplad till någon funktion, så vi tog bort den för att eliminera en förvirrande upplevelse.

**Det går inte att komma åt dokument från länkar**

_Dokument_

När en användare i den nya [!DNL Workfront]-upplevelsen klickar på vissa dokumentlänkar, kan de inte komma åt dokumentet och felmeddelandet [!UICONTROL The Document no longer exists: You may have mistyped the web address. Double check it and try entering the address again.] visas. Samma fel inträffar med länken [!UICONTROL View Details] i korrekturmeddelanden via e-post.

+++

+++**Workfront Fusion Maintenance Update den 16 februari 2021**

**[!DNL Workfront Fusion]2.0 visar felaktiga tidszoner**

_Scenarier_

Uppdateringen åtgärdade ett problem där [!DNL Fusion] 2.0 felaktigt visade användartidszoner. Användarna kan nu se sin tidszon under inmatningsfält för datum.

+++

+++**Underhållsuppdatering 11 februari 2021**

**Korrektur överförs inte till den valda mappen**

_[!DNL Workfront Proof]_

När en användare öppnar en mapp och lägger till ett nytt korrektur överförs korrekturet till objektets allmänna [!UICONTROL Documents]-område i stället för till inom mappen.

**För många fästa sidor gör att den övre navigeringen försvinner**

_Navigering_

När en användare har fler än 60 fasta sidor slutar den övre navigeringen att visas, vilket förhindrar användaren från att komma åt [!UICONTROL Search], [!UICONTROL Main Menu], [!UICONTROL Notifications] med mera.

**Användaren kan inte skriva text i RTF-fält**

_Listor_

När en användare försöker att infoga ett RTF-fält kan han/hon bara skriva ett enda tecken.

+++

+++**Underhållsuppdatering 4 februari 2021**

**Exporterad rapport visar [!DNL Workfront Classic] branding**

_Rapporter_

När en användare i den nya Workfront-upplevelsen exporterar en rapport matchar logotypen som visas i den exporterade rapporten de [!DNL Workfront Classic]-inställningar som finns under [!UICONTROL Setup] > [!UICONTROL System] > [!UICONTROL Branding].

+++


## Uppdateringar i januari 2021

+++**Underhållsuppdatering 28 januari 2021**

**Kommentarerna visar inte [!UICONTROL on behalf of]**

_Uppdateringar_

När en [!DNL Workfront]-administratör loggar in som en annan användare och svarar på en kommentar i [!UICONTROL Updates] -området i ett objekt, visas inte texten [!UICONTROL on behalf of] före användarnamnet.

**Det går inte att bifoga ett dokument**

_Begäranden_

När en användare i den nya [!DNL Workfront]-upplevelsen försöker lägga till ett dokument i en ny begäran från en extern dokumentleverantör, läses inte listan [!UICONTROL Documents] in, vilket förhindrar användaren från att välja dokumentet och slutföra begäran.

**Skärmbredden utökas till höger, vilket orsakar navigeringsproblem**

_[!UICONTROL Home Calendar]_

När en användare i den nya [!DNL Workfront]-upplevelsen öppnar [!UICONTROL Home Calendar] och har objekt som förfaller några veckor, expanderar skärmen till höger och förhindrar dem från att visa hela veckan samtidigt. Om användaren väljer ett objekt för att öppna panelen [!UICONTROL Details] i det här läget och vill visa information för ett annat objekt, måste användaren rulla till vänster, vilket stänger panelen [!UICONTROL Details].

**Etikett för godkännandeprocess för enstaka användning har korrigerats**

_Projekt_

När du använder en godkännandeprocess för ett projekt med en enstaka användning i den nya [!DNL Workfront]-upplevelsen visas den nu som [!UICONTROL Single-use approval process] i stället för som \&lt;Anpassad\> i rutan [!UICONTROL Edit Project]. Det här är ännu inte tillgängligt för uppgifter och problem.

**Förbättrat utseende för anpassade formulär**

_Projekt_

Vi har förbättrat utseendet och känslan av att arbeta med anpassade formulär i den nya [!DNL Workfront]-upplevelsen för projekt.

**API-funktionaliteten för projektvalutan matchar nu funktionen i appen**

_Projekt_

Du kan inte ändra valutan för ett projekt när det redan finns ekonomisk information i projektet. Med den senaste underhållsuppdateringen matchar API-funktionen för det här fallet nu upplevelsen i gränssnittet [!DNL Workfront].

**Genererar inte automatiskt följande vecka**

_Tidrapporter_

När en användare navigerar till området [!UICONTROL Timesheets] ser de bara tidrapporten för den aktuella veckan. Tidrapporten för kommande veckor genereras inte automatiskt.

+++

+++**Underhållsuppdatering 21 januari 2021**

**Om du sorterar manuellt efter en kolumn visas alla resultat**

_Rapporter_

När en användare i den nya [!DNL Workfront]-upplevelsen klickar på en stapel i ett rapportdiagram, klickar sedan på en kolumnrubrik för att manuellt sortera resultaten för den grupperingen, visas alla rapportresultat, inte bara resultat för den ursprungligen valda grupperingen.

Inställningen **[!UICONTROL Allow sharing proof via URL or embed code] ändras**

_[!DNL Workfront Proof]_

När en användare skapar ett korrektur och avmarkerar inställningen [!UICONTROL Allow sharing proof via URL or embed code] kontrolleras inställningen igen när korrekturet har genererats. Om användaren lämnar inställningen markerad avmarkeras den när korrekturet har genererats.

**[!DNL Mac]användare kan inte klistra in i textfält i korrekturläsaren**

_[!DNL Workfront Proof]_

När en användare försöker klistra in text i vissa fält i korrekturläsaren visas inte texten i fältet.

+++

+++**Underhållsuppdatering 14 januari 2021**

**Det går inte att uppdatera inställningarna för e-postmeddelanden**

_Konfigurera_

När en användare försöker uppdatera inställningarna för e-postmeddelanden kan de inte komma åt området [!UICONTROL Email Notifications] och se felmeddelandet [!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**[!UICONTROL Gantt chart]gör att vissa fält trunkeras**

_Listor_

När en användare öppnar [!UICONTROL Gantt chart] i vissa listområden kortas texten av vissa fält, t.ex. [!UICONTROL Description]. Användaren måste dubbelklicka på fältet för att se den fullständiga texten.

**Det går inte att skicka filer från[!UICONTROL Document Details]**

_Dokument_

När en användare i den nya [!DNL Workfront]-upplevelsen försöker skicka ett dokument från sidan [!UICONTROL Document Details] visas felmeddelandet [!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]

+++

+++**Underhållsuppdatering 7 januari 2021**

**Dialogrutan Delegera godkännanden stängs**

_Startsida_

När en användare försöker delegera godkännanden i [!UICONTROL Home] och klickar på ett datum stängs dialogrutan utan att datumet har valts eller användaren tillåts att slutföra användardelegeringen.

**Problem med att flytta ett dokument till en uppgift**

_Dokument_

När en användare försöker flytta ett dokument eller ett korrektur i den nya [!DNL Workfront]-upplevelsen, visas inte de överordnade projekten som förväntat för vissa uppgifter utanför projektet.

**Det hämtade PDF har felaktigt namn**

_[!DNL Workfront Proof]_

När en användare får en nedladdningslänk via e-post ([!UICONTROL Proof] > [!UICONTROL Print Comments] > [!UICONTROL PDF]) och exporterar filen, får den nedladdade filen ett slumpmässigt namn i stället för korrektur-ID.

+++
