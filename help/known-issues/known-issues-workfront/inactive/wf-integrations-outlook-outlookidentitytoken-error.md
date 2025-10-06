---
title: 'Integreringar: outlookIdentityToken-fel vid användning av Workfront för Outlook'
description: När en användare använder integreringen med Workfront för Outlook kan ett fel uppstå.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---

# Integreringar: outlookIdentityToken-fel vid användning av Workfront för Outlook

>[!NOTE]
>
>Integreringen med Workfront för Outlook är inte längre tillgänglig. Den här artikeln kommer att tas bort inom den närmaste framtiden.

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
