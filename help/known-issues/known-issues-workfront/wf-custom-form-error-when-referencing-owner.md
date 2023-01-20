---
title: 'Anpassade formulär: Ogiltigt meddelande om anpassat uttryck när ägaren refereras i ett beräknat fält'
description: '"När en användare lägger till ett beräknat fält i ett anpassat formulär på problemnivå och försöker lägga till en referens till en ägare (t.ex. "ownerID"), sparas inte fältet och användaren ser följande meddelande: Det här är ett ogiltigt kunduttryck, försök igen.'''
hidefromtoc: true
exl-id: 254f1fae-0784-4332-99a1-cc1895c50896
source-git-commit: db076ee06c75e2d8a185b539ef54779aa0ec0630
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 0%

---

# Anpassade formulär: &quot;[!UICONTROL Invalid custom expression]&quot; när det refereras till &quot;[!UICONTROL owner]&quot; i ett beräkningsfält

>[!NOTE]
>
>Produktgruppen håller på att utvärdera den här problemlösningen, vilket kan kräva produktförbättringar. Produktförbättringarna presenteras i produktmeddelandena och inte i underhållsuppdateringarna.

<!--
>[!NOTE]
>
>This issue was fixed on December 1, 2022.
-->

När en användare lägger till ett beräknat fält i ett anpassat formulär på problemnivå och försöker lägga till en referens till ett[!UICONTROL owner]&quot; (t.ex. `ownerID`) sparas inte fältet och användaren ser följande meddelande:

&quot;[!UICONTROL This is an invalid customer expression, please try again.]&quot;

Detta inträffar även när uttrycket är giltigt.

_Först rapporterad den 8 november 2022._
