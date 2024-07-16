---
title: "Workfront Fusion: Output formatting for dates"
description: När datum anges som strängar kan datumet skrivas ut som en UTC- eller ISO-sträng. Detta beror på logiken i en mappningspanel.
hidefromtoc: true
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 7aba3a4ce3e0436a8fd9850197bc44da9dafe347
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---

# Workfront Fusion: Utdataformatering

När datum anges som strängar kan datumet skrivas ut som en UTC- eller ISO-sträng. Detta beror på logiken i en mappningspanel:

* Om ett datum i en funktion är kopplat till en sträng kommer strängen att skrivas ut i formatet **UTC**.
* Om datumet inte är kopplat till en funktion kommer det att skrivas ut som en **ISO-sträng**.

Kunder bör använda funktionerna `toString` (för ISO) eller `formatDate` för att säkerställa att utdata har det format de behöver.
