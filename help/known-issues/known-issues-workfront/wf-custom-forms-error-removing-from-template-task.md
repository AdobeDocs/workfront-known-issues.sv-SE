---
title: "Anpassade formulär: Det går inte att lägga till eller ta bort anpassade formulär gruppvis i malluppgifter"
description: "Om en användare försöker att lägga till eller ta bort ett anpassat formulär gruppvis i en mallåtgärd läggs inte formuläret till eller tas bort, och användaren ser ett fel."
hidefromtoc: true
feature: Custom Forms
source-git-commit: 41df80641db82b225753338d8564e12b90566c40
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 0%

---


# Anpassade formulär: Det går inte att lägga till eller ta bort anpassade formulär gruppvis i malluppgifter

Om en användare försöker att lägga till eller ta bort ett anpassat formulär gruppvis i en mallåtgärd läggs inte formuläret till eller tas bort, och användaren ser följande fel:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

Om användaren hittar mallen med angivet GUID och sedan försöker lägga till eller ta bort anpassade formulär i resten av malluppgifterna, kommer felet att inträffa igen med ett annat templateID.

Anpassade formulär kan läggas till eller tas bort i en enda mallåtgärd. Det här felet gäller endast för masstillägg och borttagning.

_Först rapporterad den 10 november 2023._
