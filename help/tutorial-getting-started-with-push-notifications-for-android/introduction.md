---
title: Komma igång med push-meddelanden för Android - introduktion
description: I den här självstudiekursen får du hjälp med att skicka push-meddelanden från Adobe Campaign och ta emot dessa meddelanden i din Android-app.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 2%

---


# Komma igång med push-meddelanden för Android - introduktion

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. I den här självstudiekursen får du hjälp med att skicka [!DNL push] meddelanden från Adobe Campaign till en [!DNL Android] app.

## Förhandskrav

Innan du kan börja måste du ha följande:

1) **Android-mobilprogram**

   Den här självstudiekursen omfattar inte de detaljerade steg som krävs för att konfigurera mobilprogrammet. Du måste ha ett **[!DNL Android]mobilprogram med det [!DNL Campaign SDK] integrerade**.

   Du hittar en detaljerad beskrivning av stegen som krävs i produktdokumentationen:

   [Integrera Campaign SDK i den mobila applikationen](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   Du kan också använda Experience Platform Mobile SDK. Titta på självstudievideon om du vill veta mer:

   [Konfigurera push-kanalen med Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]paket installerat**

   Paketet [!DNL Mobile App channel] måste installeras på din [!DNL Campaign] instans. I följande video förklaras hur du kontrollerar om [!DNL Mobile App channel] filen är installerad på din instans och om inte, hur du installerar den.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Översikt över självstudiekurser

Vi vill skicka ett personligt kampanjmeddelande [!DNL push] till prenumeranterna på [!DNL Neotrip] [!DNL Android] mobilappen. Appen är konfigurerad med [!DNL Neotrip] programmet [!DNL Campaign SDK] och vi har sett till att [!DNL Mobile App channel] är aktiverad i vår [!DNL Campaign] instans.

Följande konfigurationssteg krävs:

### Steg 1: Utöka programmets prenumerationsschema för att anpassa [!DNL push] meddelanden

Eftersom vi vill anpassa [!DNL push] meddelandet [utökar vi först appprenumerationsschemat](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) så att vi kan lagra de personaliseringsvärden vi får från appen när användaren prenumererar på tjänsten.

### Steg 2: Konfigurera Android-tjänsten och skapa mobilprogrammet i Campaign

Därefter måste vi [konfigurera Android-tjänsten och skapa mobilappen i Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). I det här steget ska vi definiera [!DNL Neotrip] programmet som mål för push-meddelandet.

### Steg 3: Konfigurera och skicka push-meddelanden

Sedan är vi redo att [konfigurera och skicka push-meddelandet](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Starta självstudiekursen

Steg 1: [Utöka programmets prenumerationsschema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
