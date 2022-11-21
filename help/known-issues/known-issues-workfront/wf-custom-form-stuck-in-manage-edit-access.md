---
title: "Anpassade formulär: Egna formulär för flera objekt kräver behörighet att hantera eller redigera för att redigera fält"
description: "När en användare skapar ett formulär med korsobjekt som bara tillåter behörigheten Hantera eller Redigera och sedan tar bort den objekttypen, kräver det anpassade formuläret fortfarande behörighet att redigera fälten. Det finns ingen visuell indikation på att fälten kräver behörigheten Hantera eller Redigera och det finns inget sätt att återställa formuläret."
hidefromtoc: true
source-git-commit: be498327ea7bb2a49be0fc65e53806ddb217aa8c
workflow-type: tm+mt
source-wordcount: '178'
ht-degree: 0%

---


# Anpassade formulär: Egna formulär för flera objekt kräver [!UICONTROL Manage] eller [!UICONTROL Edit] behörighet att redigera fält

>[!NOTE]
>
>Problemet har stängts

När en användare skapar ett formulär med korsobjekt som bara tillåter [!UICONTROL Manage] eller [!UICONTROL Edit] åtkomst, och sedan tar bort den objekttypen, fortsätter det anpassade formuläret att kräva [!UICONTROL Manage] eller [!UICONTROL Edit] behörighet att redigera fälten. Det finns ingen visuell indikation på att fälten kräver behörigheten Hantera eller Redigera och det finns inget sätt att återställa formuläret.

**Tillfällig lösning**

1. Lägg till en avsnittsbrytning i formuläret med standardvärden om det fylls i med.
2. Flytta avsnittsbrytningen till formulärets överkant.
3. Spara formuläret.
4. Ta bort avsnittsbrytningen som just lagts till och spara om formuläret.

_Först rapporterad den 9 november 2022._

