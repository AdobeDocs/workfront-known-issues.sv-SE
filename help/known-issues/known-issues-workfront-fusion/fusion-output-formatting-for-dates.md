---
title: "Workfront Fusion: Output formatting for dates"
description: "När datum anges som strängar kan datumet skrivas ut som en UTC eller en ISO-sträng. Det beror på logiken i en mappningspanel."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion: Utdataformatering

När datum anges som strängar kan datumet skrivas ut som en UTC- eller ISO-sträng. Detta beror på logiken i en mappningspanel:

* Om ett datum i en funktion är kopplat till en sträng kommer strängen att skrivas ut i **UTC** format.
* Om datumet inte är kopplat till en funktion kommer det att skrivas ut som en **ISO-sträng**.

Kunderna bör använda `toString` (för ISO) eller `formatDate` funktioner för att säkerställa att utdata har det format de behöver.
