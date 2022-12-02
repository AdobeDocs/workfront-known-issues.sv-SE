---
title: "Listor: Inline-redigeringsfel per användare orsakar inga felmeddelanden"
description: "När en användare infogar redigering av ett objekt och gör ett fel som ska skapa ett felmeddelande, visas inget felmeddelande. Själva felet sparas inte i Workfront, vilket betyder att data inte påverkas, men det beror på att ett felmeddelande saknas."
hidefromtoc: true
source-git-commit: 2951a566384274e5f32544dd8be1872f3850af94
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---


# Listor: Inline-redigeringsfel per användare orsakar inga felmeddelanden

>[!NOTE]
>
>Problemet korrigerades den 1 december 2022.

När en användare infogar redigering av ett objekt och gör ett fel som ska skapa ett felmeddelande, visas inget felmeddelande. Själva felet sparas inte i Workfront, vilket betyder att data inte påverkas, men det beror på att ett felmeddelande saknas.

Detta har rapporterats i följande situationer:

* Föregående: En föregående slinga skapas, till exempel tilldelas en uppgift till sig själv
* Datum: Ett omöjligt datum har angetts, till exempel ett slutförandedatum som är tidigare än startdatumet eller som ligger efter projektets slutförandedatum

_Först rapporterad den 26 oktober 2022._

