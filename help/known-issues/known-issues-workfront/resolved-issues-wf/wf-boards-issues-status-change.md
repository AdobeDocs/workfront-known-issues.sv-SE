---
title: '"Varor: Problem med statusändringar för länkade objekt på kortplatser'
description: Olika problem har rapporterats om funktionen för statusändring när ett kort flyttas mellan kolumner på anslagstavlor.
exl-id: b01ff757-72df-4378-8576-a7490b05ef73
hidefromtoc: true
source-git-commit: 453eef770b0f31990946c746e677fb453d0be94b
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# [!UICONTROL Boards]: Problem med [!UICONTROL Status change] funktioner för länkade objekt i [!UICONTROL Boards] kort

>[!NOTE]
>
>Problemet korrigerades den 1 augusti 2022.

Följande problem har rapporterats angående [!UICONTROL Status change] funktionalitet när du flyttar ett kort mellan kolumner på [!UICONTROL Boards]:

* När du visar ett kort på [!UICONTROL Boards], [!DNL Workfront] Arbetsobjektet som är länkat till kortet visar en status. När arbetsuppgiften öppnas i [!DNL Workfront]är den visade statusen inte densamma som den som visas på kortet.
* När ett kort flyttas från en kolumn till en annan ändras inte statusen för ett objekt som är länkat till kortet så att det återspeglar [!UICONTROL Status change] inställningar för kolumnerna.
* När ett kort flyttas från en kolumn till en annan öppnas kortet [!UICONTROL Saving updates] pekaren högst upp på kortet fortsätter snurra oändligt. Om en användare försöker ändra status medan den här rotationsrutan är aktiv, svarar inte alternativen i listrutan för statusändring.

_Först rapporterad den 20 juli 2022._
