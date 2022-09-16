---
title: 'Anpassade formulär: Det går inte att redigera anpassade formulär på grund av en felaktig teckengräns för beskrivande textfält'
description: När en användare försöker redigera ett anpassat formulär och det anpassade formuläret har ett beskrivande textfält som innehåller fler än 512 tecken, kan användaren inte spara ändringarna i det anpassade formuläret.
exl-id: c224c4d1-4003-45fd-9f9e-0e55af1317e9
hidefromtoc: true
source-git-commit: de7f66f7acba1a0ac32a1257b2e643a767eae7fb
workflow-type: tm+mt
source-wordcount: '124'
ht-degree: 0%

---

# Anpassade formulär: Det går inte att redigera anpassade formulär på grund av en felaktig teckengräns för beskrivande textfält

>[!NOTE]
>
> Detta problem korrigerades den 11 augusti 2022.

När en användare försöker redigera ett anpassat formulär och det anpassade formuläret har ett [!UICONTROL Descriptive text] fält som innehåller fler än 512 tecken kan användaren inte spara ändringarna i det anpassade formuläret och ser följande fel:

&quot;[!UICONTROL The following fields are invalid: (Field) is too long, max 512]&quot;

Detta påverkar [!UICONTROL Descriptive text] fält som tidigare har fungerat bra trots att de innehåller fler än 512 tecken.


_Först rapporterad den 20 juli 2022._
