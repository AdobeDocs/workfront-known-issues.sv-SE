---
title: "Projekt/uppgifter/ärenden: Tidslinjen räknar inte om"
description: "När en jämn händelse inträffar som borde utlösa en tidslinjeberäkning, beräknas inte tidslinjen om. Detta påverkar omberäkningar som sker vid ändringar och schemalagda omberäkningar. Detta kan påverka noggrannheten för belastningsutjämnaren."
hidefromtoc: true
source-git-commit: 7fd6a2604bf2e5b9e4bb69b1e3f242ebf761f180
workflow-type: tm+mt
source-wordcount: '94'
ht-degree: 0%

---


# Projekt/uppgifter/problem: Tidslinjen räknar inte om

>[!NOTE]
>
>Problemet korrigerades den 13 juli 2023.

När en jämn händelse inträffar som ska utlösa en tidslinjeberäkning, beräknas inte tidslinjen om. Detta påverkar omberäkningar som sker vid ändringar och schemalagda omberäkningar. Detta kan påverka noggrannheten för belastningsutjämnaren.

**Tillfällig lösning**

Beräkna tidslinjer manuellt.

_Först rapporterad den 15 mars 2023._

