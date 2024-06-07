---
title: 'Nytt hem: Widget-filter och grupperingsstandardvärden följer inte layoutmallen'
description: När en användare visar widgeten Mina projekt, Mina uppgifter eller Mina problem i den nya hemupplevelsen, är standardfiltret och standardgrupperingen för den widgeten inte standardinställningen i layoutmallen som tilldelats den användaren.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# Nytt [!UICONTROL Home]: Widget-filter och grupperingsstandardvärden följer inte layoutmallen

>[!NOTE]
>
>Problemet har stängts eftersom det fungerar som det ska.

När en användare tittar på [!UICONTROL My Projects], [!UICONTROL My Tasks], eller [!UICONTROL My Issues] widgeten i den nya [!UICONTROL Home] standardfiltret och grupperingen för den widgeten är inte standardinställningen i layoutmallen som tilldelats den användaren.

**Tillfällig lösning**:

När du använder Nytt hem är det viktigt att komma ihåg att användarinställningarna (inställningarna) prioriteras. Det innebär att om du anger ett standardfilter eller en standardgruppering för en viss widget med hjälp av en layoutmall kanske det inte börjar gälla omedelbart på grund av befintliga användarinställningar. Om du vill använda det nya filtret eller grupperingen kan du eller användaren behöva återställa inställningarna. Detta kan du göra genom att lägga till `/resetUser` till din URL.

_Först rapporterad den 3 januari 2024._
