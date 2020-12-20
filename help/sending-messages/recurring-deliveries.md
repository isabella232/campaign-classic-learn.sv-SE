---
title: Konfigurera återkommande och kontinuerliga e-postkampanjer
description: I den här självstudiekursen beskrivs hur du ställer in en återkommande och kontinuerlig leverans och skillnaderna mellan de två metoderna i Adobe Campaign Classic (ACC).
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 5%

---


# Konfigurera återkommande och kontinuerliga e-postkampanjer

I den här självstudiekursen beskrivs hur du ställer in en återkommande och kontinuerlig leverans och skillnaderna mellan de två metoderna.

## Återkommande och kontinuerlig leveransspårning {#recurring-and-continuous-delivery-tracking}

De återkommande och kontinuerliga leveranserna skiljer sig åt när det gäller hur kontaktdata hanteras:

* Med **kontinuerlig leverans** kan du lägga till nya mottagare till en befintlig leverans och undvika att du måste skapa en ny leverans varje gång en ny mottagare läggs till. Du kan uppdatera den kreativa informationen direkt i kampanjarbetsflödet och den uppdaterar mallen i leveransmallens resursmapp.

   En kontinuerlig leverans skapar en enda leverans- och leveranslogg (broadLog) och spårningsloggar som refererar till att en leverans läggs till varje gång den körs.

![Kontinuerlig leverans](/help/assets/delivery_continuous.jpg)

* En **återkommande leverans** skapar en ny leveransinstans varje gång den körs. Om arbetsflödet till exempel är schemalagt att köras en gång i veckan resulterar det i 52 leveranser efter ett år. Det innebär också att de breda loggarna och spårningsloggarna separeras av varje leveransinstans.

![Återkommande leverans](/help/assets/delivery_recurring.jpg)

## Så ställer man in en återkommande leverans {#how-to-set-up-a-recurring-delivery}

I den här videon förklaras hur du konfigurerar en återkommande leverans och en schemaläggningsaktivitet.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Så ställer man in en kontinuerlig leverans {#how-to-set-up-a-continuous-delivery}

I den här videon visas hur du konfigurerar en kontinuerlig leverans med en stegvis fråga.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Ytterligare resurser

[Skapa en återkommande leverans i ett målarbetsflöde](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)