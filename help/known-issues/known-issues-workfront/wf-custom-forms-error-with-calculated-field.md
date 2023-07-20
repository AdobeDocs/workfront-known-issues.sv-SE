---
title: 'Anpassade formulär: Hoppfel vid inställning av ett beräkningsfält'
description: När en användare skapar eller redigerar ett beräknat fält i ett anpassat formulär och inkluderar ett anpassat fält i det beräknade fältets uttryck, anses uttrycket vara ogiltigt. Knappen Spara är inaktiverad och användaren kan inte navigera bort från det anpassade fältet. Dessutom ser användaren ett meddelande under fältet.
hidefromtoc: true
feature: Custom Forms
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
source-git-commit: 2a41264d6f477f51eaeda6ae3675b1a6d816249c
workflow-type: tm+mt
source-wordcount: '156'
ht-degree: 0%

---

# Anpassade formulär: &quot;[!UICONTROL Whoops]&quot; fel vid inställning av beräkningsfält

<!--Requested: Do not delete without approval from Alex Beach-->

>[!NOTE]
>
>Problemet korrigerades den 12 januari 2023

När en användare skapar eller redigerar ett beräknat fält i ett anpassat formulär och inkluderar ett anpassat fält i det beräknade fältets uttryck, anses uttrycket vara ogiltigt. The [!UICONTROL Save] är inaktiverad och användaren kan inte navigera bort från det anpassade fältet. Dessutom ser användaren följande meddelande under fältet:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Om du tar bort det anpassade fältet från uttrycket kan användaren spara och navigera bort från fältet.

_Först rapporterad den 11 oktober 2022._
