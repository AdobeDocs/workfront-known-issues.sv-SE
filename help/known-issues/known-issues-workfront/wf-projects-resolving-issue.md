---
title: "Projekt/ärenden: Projektet löser inte problemet korrekt"
description: "När en användare ändrar status för ett projekt som är det objekt som löser ett problem ändras status för problemet till en status som inte matchar samma nyckel som statusen för projektet."
hidefromtoc: true
feature: Projects
source-git-commit: 3d2c392fdb9cdf2eb7ea46cd4444895bc45a5b7d
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 0%

---


# Projekt/problem: Projektet löser inte problemet korrekt

När en användare ändrar status för ett projekt som är det lösta objektet för ett problem, ändras ärendestatusen till en status som inte matchar samma nyckel som statusen för projektet.

**Tillfällig lösning**

Ta bort den matchande relationen och ange statusvärdena oberoende av varandra.

_Först rapporterad den 17 juli 2023._
