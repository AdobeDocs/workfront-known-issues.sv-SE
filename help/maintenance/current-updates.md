---
title: Workfront Maintenance Updates
description: Underhållsuppdateringar för [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 441062239d07963454e1cc57e4dff54e0c5a06bb
workflow-type: tm+mt
source-wordcount: '1018'
ht-degree: 0%

---

# [!DNL Workfront] Underhållsuppdateringar

Följande underhållsuppdateringar gjordes 2023.

>[!NOTE]
>
>Uppdateringarna innehåller även andra mindre eller mindre viktiga felkorrigeringar. [!DNL Workfront] Supporten meddelar dig när ett ärende som du har skickat har åtgärdats.

Underhållsuppdateringar före 2023 finns på [Tidigare underhållsuppdateringar](#previous-maintenance-updates)

## Uppdateringar i januari 2023

+++**Underhållsuppdatering 26 januari 2023**

**Fel när begäran skickades från[!DNL Outlook]**

_Integreringar_

När en användare försöker skicka en begäran med bilagor från en [!DNL Outlook] e-post, en eller flera bilagor överförs inte och användaren ser följande fel:

&quot;[!UICONTROL The following error occurred: File with handle xxxx does not exist.]&quot;

Detta inträffar endast när en tilldelning görs för den nya begäran, antingen via begärandekön eller manuellt när begäran skapas.

**Ny version av Desktop Proofing Viewer**

_Korrektur_

För att åtgärda ett problem med frysning i Desktop Proofing Viewer har vi distribuerat en ny version av Desktop Proofing Viewer. Användare som redan har installerat Desktop Proofing Viewer får den här uppdateringen automatiskt.

Användarna kan även manuellt välja den senaste versionen. Mer information finns i [Installera Desktop Proofing Viewer](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Föregående version: 2.1.19
* Ny version: 2.1.20

**Användaren kan inte redigera sin egen användarinställning**

_Användare_

När en användare med en licens för Arbete, Granska eller Begäran försöker redigera sina egna användarinställningar, är popup-fönstret som öppnas tomt och användaren kan inte göra några ändringar. Användaren måste uppdatera sidan för att kunna stänga popup-fönstret.

+++

+++**Underhållsuppdatering 19 januari 2023**

**Intagskolumnfilter kan nu delas**

_Varumärkena_

När intagskolumnens funktion släpptes till Boards kunde filter för att ställa in intagskolumnen bara ses av den person som skapade dessa filter. Nu kan skaparen dela filtren med andra användare eller team.

**Fästfunktionen är tillgänglig i [!UICONTROL More] meny**

_Navigering_

Följande funktioner är nu tillgängliga i [!UICONTROL More] för stift, i produktionsmiljön:

* Byter namn på punkter
* Ändra ordning på punkter i [!UICONTROL More] meny
* Flytta ut ett häftstift från [!UICONTROL More] (när du gör det flyttas det sista stiftet i det övre navigeringsfältet till [!UICONTROL More] meny)

+++

+++**Underhållsuppdatering 18 januari 2023**

**Uttryck med jokertecken är inte giltiga i anpassade fält**

_Anpassad Forms_

När en användare använder ett jokertecken som \$$TODAY eller $$NOW tillsammans med en modifierare (till exempel&quot;-30d&quot;) i ett anpassat fält, accepterar inte valideraren jokertecknet som giltigt. Jokertecken utan modifierare betraktas som giltiga.

**[!UICONTROL Workload Balancer]visar timmar som inte är associerade med ett projekt/en uppgift/utleverans**

_[!UICONTROL Workload Balancer]_

När en användare tittar på [!UICONTROL Workload Balancer]ser de timmar som loggats för en användare som inte är kopplad till något projekt, någon uppgift eller något problem, och de loggas inte heller som [!UICONTROL General] timmar. Dessa timmar kan endast visas i vyn 4 veckor eller 6 veckor.

+++

+++**[!DNL Adobe Workfront Fusion]Underhållsuppdatering (snabbkorrigering) 12 januari 2023**

**404 fel på [!DNL Workfront] moduler**

_Workfront Fusion_

När ett scenario körs [!DNL Workfront] modulen returnerar ett 404-fel.

Detta har rapporterats i följande moduler:

* [!UICONTROL Read a record]

+++

+++**Underhållsuppdatering (snabbkorrigering) 12 januari 2023**

**&quot;[!UICONTROL Whoops]&quot; fel vid inställning av beräkningsfält**

_Anpassad Forms_

När en användare skapar eller redigerar ett beräknat fält i ett anpassat formulär och inkluderar ett anpassat fält i det beräknade fältets uttryck, anses uttrycket vara ogiltigt. The [!UICONTROL Save] är inaktiverad och användaren kan inte navigera bort från det anpassade fältet. Dessutom ser användaren följande meddelande under fältet:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Om du tar bort det anpassade fältet från uttrycket kan användaren spara och navigera bort från fältet.

**Det går inte att ange åtkomstnivåer**

_Användare_

När en användare försöker ändra åtkomstnivån för en annan användare är åtkomstnivåerna nedtonade och användaren kan inte ändra dem. Detta inträffar även om användaren som försöker göra ändringen är systemadministratör.

+++

+++**Underhållsuppdatering 12 januari 2023**

**Ctrl+F eller Cmd+F fungerar inte som väntat i listrutor**

_Anpassad Forms_

När en användare fyller i ett anpassat formulär och söker i en listruta med Ctrl+F eller Cmd+F och sedan försöker hoppa till nästa förekomst av sökningen, återgår listrutan till början av listan i stället för att hoppa till nästa förekomst av sökningen. Detta inträffar när en listruta är inställd på att tillåta flera val.

**[!UICONTROL Edit Report]skärmen är tom**

_Rapporter_

När en användare visar en rapport och försöker redigera rapporten, visas användaren på en tom skärm och kan inte redigera rapporten.

**Indragna uppgifter förblir inte indragna**

_Uppgifter_

När en användare visar en uppgiftslista och drar in en uppgift återgår uppgiften omedelbart till det ursprungliga (indraget) läget.

+++

+++**Underhållsuppdatering 5 januari 2023**

**Fästfunktionen är tillgänglig i [!UICONTROL More] meny**

_Navigering_

Följande funktioner är nu tillgängliga i [!UICONTROL More] meny för punkter, endast i förhandsvisningsmiljön:

* Byter namn på punkter
* Ändra ordning på punkter i [!UICONTROL More] meny
* Flytta ut ett häftstift från [!UICONTROL More] (när du gör det flyttas det sista stiftet i det övre navigeringsfältet till [!UICONTROL More] meny)

**Begränsningen för projektgruppen har tagits bort från möjligheten att lägga till användare i projektteamet**

_Team_

Vi har tagit bort den begränsning som innebar att användare som måste läggas till i ett projektteam måste finnas i den grupp som är kopplad till projektet. Nu kan du lägga till alla aktiva användare i ett projektteam, oavsett vilka grupper de tillhör.

**Nya informationsikoner för tidrapporter, tidrapportprofiler och tidrapportinställningar**

>[!NOTE]
>
>Uppdateringen släpptes till förhandsvisningsmiljön den 3 november 2022 och är nu tillgänglig i Production

_Workfront_

Vi har lagt till flera informationsikoner i följande inställningar:

* Kryssrutan&quot;Kan redigera tid&quot; när du skapar eller redigerar en tidrapportprofil eller en tidrapportprofil för att ange att godkännare när den är aktiverad även kan skicka, öppna eller redigera tidrapporten, såvida inte administratören begränsar dessa åtgärder under Inställningar för tidrapport i dialogrutan Inställningar.
* &quot;Begränsa redigering av tidrapporter till ägare och administratörer&quot; i inställningsområdet för tidrapport och timinställningar för att ange att följande användare även kan redigera tidrapporterna när de är inaktiverade: användare med administrativ åtkomst till tidrapporter och timmar, tidrapportgodkännare som kan redigera tid och tidrapportägarnas chefer.

Observera att funktionaliteten för de här inställningarna inte har ändrats och att bara informationsikonerna har lagts till för att göra inställningarna tydligare.

+++

## Tidigare underhållsuppdateringar

Information om tidigare underhållsuppdateringar finns här:

* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2022](2022-updates.md)
* [[!DNL Workfront] Underhållsuppdateringsarkiv - 2021](2021-updates.md)
