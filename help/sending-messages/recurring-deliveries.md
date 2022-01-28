---
title: Konfigurera återkommande och kontinuerliga e-postkampanjer
description: Lär dig hur du ställer in en återkommande och kontinuerlig leverans och förstå skillnaderna mellan de två metoderna.
feature: Workflows, Campaigns
kt: 1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 7d63f43c26182bd7ffb618392463283da0b3d307
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 51%

---

# Konfigurera återkommande och kontinuerliga e-postkampanjer

I den här självstudiekursen beskrivs hur du ställer in en återkommande och kontinuerlig leverans och skillnaderna mellan de två metoderna.

## Återkommande och kontinuerlig leveransspårning {#recurring-and-continuous-delivery-tracking}

De återkommande och kontinuerliga leveranserna skiljer sig åt när det gäller hur kontaktdata hanteras:

* The **kontinuerlig leverans** Med kan du lägga till nya mottagare i en befintlig leverans och undvika att du måste skapa en ny leverans varje gång en ny mottagare läggs till. Du kan uppdatera den kreativa informationen direkt i kampanjarbetsflödet och den uppdaterar mallen i leveransmallens resursmapp.

   En kontinuerlig leverans skapar en enda leverans- och leveranslogg (broadLog) och spårningsloggar som refererar till att en leverans läggs till varje gång den körs.

   ![Kontinuerlig leverans](/help/assets/delivery_continuous.jpg)

* A **återkommande leverans** skapar en ny leveransinstans varje gång den körs. Om arbetsflödet till exempel är schemalagt att köras en gång i veckan resulterar det i 52 leveranser efter ett år. Det innebär också att de breda loggarna och spårningsloggarna separeras av varje leveransinstans.

   ![Återkommande leverans](/help/assets/delivery_recurring.jpg)

## Så ställer du in en återkommande leverans {#how-to-set-up-a-recurring-delivery}

I den här videon förklaras hur du konfigurerar en återkommande leverans och en schemaläggningsaktivitet.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Så ställer du in en kontinuerlig leverans {#how-to-set-up-a-continuous-delivery}

Den här videon visar hur du konfigurerar en kontinuerlig leverans med en stegvis frågeställning.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)
