---
title: "Resurshantering: Felaktiga ekonomiska beräkningar på grund av problem med jobbroller"
description: "Timmar och ekonomiska beräkningar kan vara felaktiga, vilket ger en kostnad på 0 trots att timmar är inloggade i en jobbroll som har en kostnadstariff."
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---


# Resurshantering: Felaktiga ekonomiska beräkningar på grund av problem med jobbroller

>[!NOTE]
>
>Problemet korrigerades den 8 februari 2024.

Timmar- och finansberäkningar kan vara felaktiga, vilket ger en kostnad på 0 även om timmar är inloggade i en jobbroll som har en kostnadstariff.

Detta beror på att jobbroller automatiskt skapar dubblettfrekvenser utan start- eller slutdatum. Eftersom de inte har några start- eller slutdatum behandlas de som värdet 0 när finansiella beräkningar körs.

**Tillfällig lösning**

1. Kontrollera att dina tidigare korrekta data har sparats.
1. Ta bort dubblettfrekvenser utan start- eller slutdatum.
1. Räkna om ekonomin.

_Först rapporterad den 18 januari 2023._
