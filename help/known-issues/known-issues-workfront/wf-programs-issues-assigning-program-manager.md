---
title: "Program: Problem vid tilldelning av programägare"
description: "När en användare skapar ett program och tilldelar en programägare uppstår problemen som beskrivs i den här artikeln."
hidefromtoc: true
source-git-commit: ef589b0430dcc32edde3348960fe3116c863d25e
workflow-type: tm+mt
source-wordcount: '86'
ht-degree: 0%

---


# Program: Problem vid tilldelning av en [!UICONTROL Program Owner]

>[!NOTE]
>
>Problemet löstes den 7 november 2022.

När en användare skapar ett program och tilldelar [!UICONTROL Program Owner]uppstår följande problem:

* Användaren ser felet &quot;[!UICONTROL 500: Database error: BizContext.commit failed! /attask/api-internal/PRGM/(Program ID)]&quot;
* När användaren tittar på delningen för programmet ser de att den nya [!UICONTROL Program Owner] har lagts till, men all ärvd behörighet att programmet har tagits bort.

_Först rapporterad den 16 september 2022._

