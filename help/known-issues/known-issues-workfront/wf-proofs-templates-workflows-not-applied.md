---
title: "Korrektur: Korrektur som skapats från integreringsresurser har inte mallar och arbetsflöden som de ska använda korrekt"
description: ''''
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 90ce6128-4521-476d-ba85-c51b86bbeb7d
source-git-commit: dbc4e4ecd9e7b2a6d01b43f46a3c2fd128c1d1dc
workflow-type: tm+mt
source-wordcount: '94'
ht-degree: 0%

---

# Korrektur: Korrektur som skapats från integreringsresurser har inte mallar och arbetsflöden som används korrekt

>[!NOTE]
>
>Problemet korrigerades den 18 april 2024.

När en användare skapar ett korrektur av en resurs från en integrering (en extern dokumentleverantör som är länkad till Workfront) och använder en mall eller ett automatiserat arbetsflöde, tillämpas inte en del av mallen eller arbetsflödeselementen på korrekturet.

Följande element har rapporterats som felaktiga i skapade korrektur:

* Deadlines
* Godkännandeinställningar
* E-postmeddelanden (skickas inte)

_Först rapporterad den 28 februari 2024._
