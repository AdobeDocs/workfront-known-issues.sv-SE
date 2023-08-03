---
title: "Projekt/problem: Projektet löser inte problemet på rätt sätt"
description: "När en användare ändrar status för ett projekt som är det objekt som löser ett problem ändras status för problemet till en status som inte matchar samma nyckel som statusen för projektet."
hidefromtoc: true
feature: Projects
source-git-commit: f2ac5034ba97c996e84b94caac80d7686a924c36
workflow-type: tm+mt
source-wordcount: '112'
ht-degree: 0%

---


# Projekt/problem: Felet har inte lösts korrekt i projektet

>[!NOTE]
>
>Detta problem korrigerades den 3 augusti 2023.

När en användare ändrar status för ett projekt som är det lösta objektet för ett problem, ändras ärendestatusen till en status som inte matchar samma nyckel som statusen för projektet.

**Tillfällig lösning**

Ta bort den matchande relationen och ange statusvärdena oberoende av varandra.

_Först rapporterad den 17 juli 2023._
