---
title: 'Layoutmallar: Layoutmallar orsakar inkonsekvenser i rapporter'
description: Layoutmallar från den klassiska Workfront-upplevelsen är inte längre tillgängliga i Workfront-gränssnittet, men kan ändå påverka Workfront-data. Detta kan orsaka inkonsekvenser i fält som påverkas av layoutmallar (som Delas med) i rapporter eller instrumentpaneler.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 2631a7a9cd6c07feae192cb0e29f168929fc9f3c
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 0%

---

# Layoutmallar: Layoutmallar orsakar inkonsekvenser i rapporter

<!--Live for workaround-->

Layoutmallar från Classic [!DNL Workfront] upplevelsen är inte längre tillgänglig i [!DNL Workfront] gränssnitt, men kan fortfarande påverka [!DNL Workfront] data. Detta kan orsaka inkonsekvenser i fält som påverkas av layoutmallar (som [!UICONTROL Shared with]) på rapporter eller kontrollpaneler.

**Tillfällig lösning**

Ta bort klassiska layoutmallar med ett API-anrop. Du måste vara inloggad på Workfront.

>[!NOTE]
>
>Mallar för global layout och systemlayout kan inte tas bort.

1. Leta reda på layoutmallen som du vill ta bort med följande API-anrop:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Observera ID:t för layoutmallen som du vill ta bort.
1. Hitta ditt sessions-ID med följande API-anrop:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Dela aldrig ditt sessions-ID med någon.

1. Infoga layoutmallens ID och sessions-ID i följande API-anrop:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Klistra in API-anropet från steg 4 i URL-fältet i webbläsaren och tryck på Retur.

   Då tas layoutmallen bort.
