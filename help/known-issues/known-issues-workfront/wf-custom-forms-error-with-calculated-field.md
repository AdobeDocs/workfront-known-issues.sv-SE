---
title: 'Anpassade formulär: Hoppfel vid inställning av ett beräkningsfält'
description: När en användare skapar eller redigerar ett beräknat fält i ett anpassat formulär och inkluderar ett anpassat fält i det beräknade fältets uttryck, anses uttrycket vara ogiltigt. Knappen Spara är inaktiverad och användaren kan inte navigera bort från det anpassade fältet. Dessutom ser användaren ett meddelande under fältet.
hidefromtoc: true
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
source-git-commit: 25b7ec9e953eca2f439a2625ba4ca58514703d1e
workflow-type: tm+mt
source-wordcount: '156'
ht-degree: 0%

---

# Anpassade formulär: &quot;[!UICONTROL Whoops]&quot; fel vid inställning av beräkningsfält

>[!NOTE]
>
>Problemet korrigerades den 12 januari 2023

När en användare skapar eller redigerar ett beräknat fält i ett anpassat formulär och inkluderar ett anpassat fält i det beräknade fältets uttryck, anses uttrycket vara ogiltigt. The [!UICONTROL Save] är inaktiverad och användaren kan inte navigera bort från det anpassade fältet. Dessutom ser användaren följande meddelande under fältet:

&quot;[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]&quot;

Om du tar bort det anpassade fältet från uttrycket kan användaren spara och navigera bort från fältet.

_Först rapporterad den 11 oktober 2022._