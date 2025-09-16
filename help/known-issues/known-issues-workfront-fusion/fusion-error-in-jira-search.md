---
title: 'Workfront Fusion: Jira Search-modulen returnerar ett fel'
description: Sökmodulen som används av den äldre Jira-anslutningen kan resultera i ett fel. Det finns en lösning
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---


# Workfront Fusion: Jira Search-modulen returnerar ett fel

>[!NOTE]
>
>Problemet beror på en förändring som Jira gjorde i sin produkt.

Sökmodulen som används av den äldre Jira-anslutningen kan resultera i följande fel:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Detta beror på en tillbakagång på Jiras sida.

Observera att:

* Endast sökmodulen påverkas. För närvarande påverkas inte andra Jira API-slutpunkter som används av Fusion-anslutningen av den här borttagningen.

* Geografisk utrullning kan orsaka inkonsekvenser. Atlassian rullar ut den här ändringen regionalt, vilket innebär att vissa Jira Cloud-instanser fortfarande har tillfälligt stöd för äldre slutpunkter. Detta kan leda till inkonsekvent beteende i olika miljöer.

**Tillfällig lösning**

Om du råkar ut för det här felet kan du ersätta sökmodulen för den äldre Jira-anslutningen med sökmodulen för den nya anslutningen. Observera att den nya anslutningen gör att du kan välja vilken API-version som ska användas. Var noga med att välja **V3** i fältet **API-version** när du skapar anslutningen.

_Först rapporterad den 15 september 2025._

