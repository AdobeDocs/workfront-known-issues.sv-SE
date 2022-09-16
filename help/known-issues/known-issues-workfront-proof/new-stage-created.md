---
title: '"Korrektur: Nytt stadium har skapats eftersom deadline inte kan matcha deadline för befintligt stadium'
description: När du skapar ett nytt korrektur kan du ställa in tidsgränsen i steg om 15 minuter (10:00, 10:15, 10:30, 20:45 osv.). När en användare läggs till i ett korrektur efter att korrekturet har skapats, kan du dock bara ställa in tidsgränsen i steg om 30 minuter (10:00, 10:30, 11:00 osv.).
exl-id: b86c1c83-c647-4762-bc13-9687a7dada78
hidefromtoc: true
source-git-commit: 993b46816bed20ad7e75b7e0719f4b3b5442cabc
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 0%

---

# Korrektur: Nytt stadium har skapats eftersom deadline inte kan matcha deadline för befintligt stadium

>[!NOTE]
>
>Problemet har åtgärdats.

När du skapar ett nytt korrektur kan du ställa in tidsgränsen i steg om 15 minuter (10:00, 10:15, 10:30, 20:45 osv.). När en användare läggs till i ett korrektur efter att korrekturet har skapats, kan du dock bara ställa in tidsgränsen i steg om 30 minuter (10:00, 10:30, 11:00 osv.). Därför kan den nya användaren inte läggas till på en scen med en deadline som slutar på :15 eller :45, eftersom deadlines inte kan matchas. I stället läggs den nya användaren till på en ny scen, med en tidsgräns på 30 minuter.

**Tillfällig lösning**:

* Om du väljer en deadline för ett nytt korrektur ställer du in tidsgränsen på en tid som slutar på :00 eller :30 (10:00, 10:30, 11:00 osv.).
* Om tidsgränsen ställs in automatiskt när korrekturet skapas, ställer du in korrekturets tidsgräns manuellt till en tidpunkt som slutar på :00 eller :30 (10:00, 10:30, 11:00 osv.).
