---
title: 'Anpassade formulär: Det går inte att använda fältet i beräkningen om fältnamnet innehåller citattecken eller en apostrof'
description: När en användare skapar ett beräknat fältuttryck och försöker inkludera ett typhuvudfält som har ett namn med ett apostrof- eller citattecken, accepteras inte beräkningen och användaren ser meddelandet Detta är ett ogiltigt anpassat uttryck. Försök igen.
hidefromtoc: true
feature: Custom Forms
exl-id: 7caa6b7a-87ab-40e8-aea2-05b41583a375
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---

# Anpassade formulär: Det går inte att använda fältet i beräkningen om fältnamnet innehåller apostrofer eller citattecken

>[!NOTE]
>
>Problemet korrigerades den 2 mars 2023.

När en användare skapar ett beräknat fältuttryck och försöker inkludera ett typhuvudfält som har ett namn med ett `'` eller `"`, beräkningen godkänns inte och användaren ser meddelandet &quot;[!UICONTROL This is an invalid custom expression, please try again.]&quot;

Problemet finns bara med typsnittsfält. Textfält med `'` eller `"` i namnet kan användas i uttryck för beräknade fält utan problem.

_Först rapporterad den 10 november 2022._
