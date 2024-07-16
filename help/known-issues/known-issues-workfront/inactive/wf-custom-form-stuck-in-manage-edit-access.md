---
title: 'Anpassade formulär: Egna formulär som kan användas på flera objekt kräver behörighet att hantera eller redigera fält'
description: När en användare skapar ett formulär med korsobjekt som bara tillåter hanterings- eller redigeringsåtkomst, och sedan tar bort den objekttypen, kräver det anpassade formuläret fortfarande behörighet att redigera fälten. Det finns ingen visuell indikation på att fälten kräver behörigheten Hantera eller Redigera och det finns inget sätt att återställa formuläret.
hidefromtoc: true
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
source-git-commit: 688d728782638489aacc76a1a12c38ab12215f8e
workflow-type: tm+mt
source-wordcount: '178'
ht-degree: 0%

---

# Anpassade formulär: Egna formulär för flera objekt kräver [!UICONTROL Manage]- eller [!UICONTROL Edit]-åtkomst för att redigera fält

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>Problemet har stängts

När en användare skapar ett formulär med korsobjekt som bara tillåter [!UICONTROL Manage] eller [!UICONTROL Edit] åtkomst, och sedan tar bort den objekttypen, fortsätter det anpassade formuläret att kräva [!UICONTROL Manage] - eller [!UICONTROL Edit]-åtkomst för att redigera fälten. Det finns ingen visuell indikation på att fälten kräver behörigheten Hantera eller Redigera och det finns inget sätt att återställa formuläret.

**Tillfällig lösning**

1. Lägg till en avsnittsbrytning i formuläret med standardvärden om det fylls i med.
2. Flytta avsnittsbrytningen till formulärets överkant.
3. Spara formuläret.
4. Ta bort avsnittsbrytningen som just lagts till och spara om formuläret.

_Först rapporterad den 9 november 2022._
