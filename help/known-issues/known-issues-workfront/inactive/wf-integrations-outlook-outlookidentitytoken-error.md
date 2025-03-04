---
title: 'Integreringar: outlookIdentityToken-fel vid användning av Workfront för Outlook'
description: När en användare använder integreringen med Workfront för Outlook kan ett fel uppstå.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Integreringar: outlookIdentityToken-fel vid användning av Workfront för Outlook

När en användare använder integreringen med Workfront för Outlook kan följande fel uppstå:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Tillfällig lösning**


För att åtgärda det här felet måste du aktivera Microsoft 365-token för din organisation. Eftersom detta måste göras i Microsoft 365 kan Workfront inte aktivera dessa tokens för din organisation.

Instruktioner om hur du aktiverar tidigare Microsoft 365-token finns i [Aktivera eller inaktivera tidigare Exchange Online-token](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) i Microsoft-dokumentationen.

Mer information om äldre token finns i [Kan jag aktivera gamla token i Exchange Online igen?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) i Microsoft-dokumentationen.


_Först rapporterad den 3 mars 2025, 2024._
