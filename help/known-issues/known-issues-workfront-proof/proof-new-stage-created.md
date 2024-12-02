---
title: 'Korrektur: Ny fas har skapats eftersom deadline inte kan matcha deadline för befintlig fas'
description: När du skapar ett nytt korrektur kan du ställa in tidsgränsen i steg om 15 minuter (10:00, 10:15, 10:30, 20:45 osv.). När en användare läggs till i ett korrektur efter att korrekturet har skapats, kan du dock bara ställa in tidsgränsen i steg om 30 minuter (10:00, 10:30, 11:00 osv.).
hidefromtoc: true
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 0%

---

# Korrektur: Ny fas har skapats eftersom deadline inte kan matcha deadline för befintlig fas

<!--Requested article-->

När du skapar ett nytt korrektur kan du ställa in tidsgränsen i steg om 15 minuter (10:00, 10:15, 10:30, 20:45 osv.). När en användare läggs till i ett korrektur efter att korrekturet har skapats, kan du dock bara ställa in tidsgränsen i steg om 30 minuter (10:00, 10:30, 11:00 osv.). Därför kan den nya användaren inte läggas till på en scen med en deadline som slutar på :15 eller :45, eftersom deadlines inte kan matchas. I stället läggs den nya användaren till på en ny scen, med en tidsgräns på 30 minuter.

**Lösning**:

* Om du väljer en deadline för ett nytt korrektur ställer du in tidsgränsen på en tid som slutar på :00 eller :30 (10:00, 10:30, 11:00 osv.).
* Om tidsgränsen ställs in automatiskt när korrekturet skapas, ställer du in korrekturets tidsgräns manuellt till en tidpunkt som slutar på :00 eller :30 (10:00, 10:30, 11:00 osv.).
