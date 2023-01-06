---
title: "Anpassade formulär: Det går inte att använda fältet i beräkningen om fältnamnet innehåller citattecken eller en apostrof"
description: "När en användare skapar ett beräknat fältuttryck och försöker ta med ett typsnittsfält som har ett namn med apostrof eller citattecken, accepteras inte beräkningen och användaren ser meddelandet Detta är ett ogiltigt anpassat uttryck. Försök igen."
hidefromtoc: true
source-git-commit: 254339d1baa9d8d7825e851aeafc9b27b1a1b669
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---


# Anpassade formulär: Det går inte att använda fältet i beräkningen om fältnamnet innehåller apostrofer eller citattecken

>[!NOTE]
>
>Produktgruppen håller på att utvärdera den här problemlösningen, vilket kan kräva produktförbättringar. Produktförbättringarna presenteras i produktmeddelandena och inte i underhållsuppdateringarna.

När en användare skapar ett beräknat fältuttryck och försöker inkludera ett typhuvudfält som har ett namn med ett `'` eller `"`, beräkningen godkänns inte och användaren ser meddelandet &quot;[!UICONTROL This is an invalid custom expression, please try again.]&quot;

Problemet finns bara med typsnittsfält. Textfält med `'` eller `"` i namnet kan användas i uttryck för beräknade fält utan problem.

_Först rapporterad den 10 november 2022._

