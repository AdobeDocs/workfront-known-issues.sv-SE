---
title: "Listor: Inline-redigeringsfel per användare orsakar inga felmeddelanden"
description: "När en användare infogar redigering av ett objekt och gör ett fel som ska skapa ett felmeddelande, visas inget felmeddelande. Själva felet sparas inte i Workfront, vilket betyder att data inte påverkas, men det beror på att ett felmeddelande saknas."
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 0%

---


# Listor: Inline-redigeringsfel per användare orsakar inga felmeddelanden

När en användare infogar redigering av ett objekt och gör ett fel som ska skapa ett felmeddelande, visas inget felmeddelande. Själva felet sparas inte i Workfront, vilket betyder att data inte påverkas, men det beror på att ett felmeddelande saknas.

Detta har rapporterats i följande situationer:

* Föregående: En föregående slinga skapas, till exempel tilldelas en uppgift till sig själv
* Datum: Ett omöjligt datum har angetts, till exempel ett slutförandedatum som är tidigare än startdatumet eller som ligger efter projektets slutförandedatum

_Först rapporterad den 26 oktober 2022._

