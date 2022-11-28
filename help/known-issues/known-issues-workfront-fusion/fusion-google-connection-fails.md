---
title: "Workfront Fusion: Kan inte skapa anslutning till Google"
description: "När en användare försöker skapa en anslutning i någon av Google-anslutningarna (till exempel Google Sheets eller Google Drive) skapas inte anslutningen och användaren ser olika felmeddelanden."
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '87'
ht-degree: 0%

---


# [!DNL Workfront Fusion]: Kan inte skapa anslutning till [!DNL Google]

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

