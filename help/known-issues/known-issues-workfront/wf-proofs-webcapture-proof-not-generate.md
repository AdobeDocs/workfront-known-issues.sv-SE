---
title: 'Korrektur: Webbfångstkorrektur genererar inte'
description: När en användare försöker skapa ett skärmkorrektur skapas inte korrekturet korrekt.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 0%

---

# Korrektur: Webbfångstkorrektur genererar inte

>[!NOTE]
>
>Problemet har stängts eftersom det fungerar som det ska. Se lösningen nedan.

När en användare försöker skapa ett skärmkorrektur skapas inte korrekturet korrekt.

**Tillfällig lösning**

Problemet orsakas av långa korrekturgenereringstider för vissa PDF-filer. Om du vill öka genereringstimeout från standardvärdet 30 sekunder redigerar du egenskapen nedan i Bearbeta inställningar på kontonivån i Korrekturadministratör:

`WebCaptureNavigationTimeout -> 120`

_Först rapporterad den 3 oktober 2024._
