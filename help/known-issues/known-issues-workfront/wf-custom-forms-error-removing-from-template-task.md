---
title: 'Anpassade formulär: Det går inte att lägga till eller ta bort anpassade formulär gruppvis i malluppgifter'
description: Om en användare försöker att lägga till eller ta bort ett anpassat formulär gruppvis i en mallåtgärd läggs inte formuläret till eller tas bort, och användaren ser ett fel.
hidefromtoc: true
feature: Custom Forms
exl-id: e9014f67-2098-46e4-a301-6a742a0c2ddb
source-git-commit: d3d6529fea8f2d020f4920ee5b2bda723f348cc2
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 0%

---

# Anpassade formulär: Det går inte att lägga till eller ta bort anpassade formulär gruppvis i malluppgifter

>[!NOTE]
>
>Problemet korrigerades den 18 januari 2024.

Om en användare försöker att lägga till eller ta bort ett anpassat formulär gruppvis i en mallåtgärd läggs inte formuläret till eller tas bort, och användaren ser följande fel:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

Om användaren hittar mallen med angivet GUID och sedan försöker lägga till eller ta bort anpassade formulär i resten av malluppgifterna, kommer felet att inträffa igen med ett annat templateID.

Anpassade formulär kan läggas till eller tas bort i en enda mallåtgärd. Det här felet gäller endast för masstillägg och borttagning.

_Först rapporterad den 10 november 2023._
