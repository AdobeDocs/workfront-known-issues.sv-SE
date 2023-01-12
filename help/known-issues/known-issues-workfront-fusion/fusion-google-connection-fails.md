---
title: '"Workfront Fusion: Kan inte skapa anslutning till Google'
description: När en användare försöker skapa en anslutning i någon av Google-anslutningarna (till exempel Google Sheets eller Google Drive) skapas inte anslutningen och användaren ser olika felmeddelanden.
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '93'
ht-degree: 0%

---

# [!DNL Workfront Fusion]: Kan inte skapa anslutning till [!DNL Google]

>[!NOTE]
>
>Problemet korrigerades den 9 januari 2023.

När en användare försöker skapa en anslutning i någon av [!DNL Google] anslutningar (t.ex. [!DNL Google Sheets] eller [!DNL Google Drive]) visas ett fönster öppet med följande fel:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

När användaren stänger det här fönstret misslyckas anslutningen med följande fel i [!DNL Fusion]:

&quot;[!UICONTROL Error: The request failed due to the failure of a prevoius request. No access token specified.]&quot;

_Först rapporterad den 21 november 2022._
