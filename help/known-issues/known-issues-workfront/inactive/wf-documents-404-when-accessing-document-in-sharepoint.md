---
title: 'Dokument: 404-fel vid åtkomst av dokument som är länkade från SharePoint'
description: När en användare försöker få åtkomst till ett dokument som är länkat via SharePoint, dirigeras de till en sida med ett 404-fel.
hidefromtoc: true
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
source-git-commit: 875945978c7bdb4a7128ade826b6fbc31da04ae9
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 0%

---

# Dokument: 404-fel vid åtkomst av dokument som är länkade från [!DNL SharePoint]

<!--Requested article. This issue is on the WF and WFP TOCs.-->

När en användare försöker få åtkomst till ett dokument som länkats via [!DNL SharePoint], tas de till en sida med följande fel:

&quot;[!UICONTROL Error 404: Page not found. This page isn't available. Try checking the URL or visit a different page.]&quot;

Detta är en känd [!DNL SharePoint] problem som inträffar när platsen har en @-symbol i länken.

**Tillfällig lösning**

[!DNL SharePoint] rekommenderar att du genererar en kort URL-adress och använder den för länken.

_Först rapporterad den 14 mars 2023._
