---
title: "Hem: Uppgifter i projekt med statusen Godkänd eller Planering ingår inte i Mina uppgifter eller Hemarbetslista"
description: "Aktiviteter från projekt som har statusen Godkänd eller Planering visas inte i Hem. Det finns en lösning."
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 0%

---


# Hem: Uppgifter i projekt med statusen Godkänd eller Planering ingår inte i Mina uppgifter eller Hemarbetslista

Uppgifter från projekt som har statusen Godkänd eller Planering visas inte i följande områden:

* Klassiskt hem: Arbetslista
* Nytt hem: Widgeten Mina uppgifter

Detta beror på att uppgifter från projekt i dessa statusar för närvarande ingår i artikelfrågegränsen för 2000, men de visas inte i Mina uppgifter eller Arbetslista för hemmet. Detta kan skapa en situation där en användare som har färre än 2 000 uppgifter inte kan se dessa uppgifter.

**Tillfällig lösning**

Skapa en anpassad uppdragsrapport som innehåller följande textlägesfilter:

När tilldelningen är AWAITING_ACCEPTANCE inkluderar du AKTUELLA|GODKÄNDA projekt:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

När tilldelningen är ACCEPTERAD inkluderar du AKTUELLA|GODKÄNDA|PLANERINGSprojekt:

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_Först rapporterad den 6 november 2023._
