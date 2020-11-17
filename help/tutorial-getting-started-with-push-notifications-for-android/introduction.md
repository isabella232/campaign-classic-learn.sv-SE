---
title: Självstudie Komma igång med push-meddelanden för Android - introduktion
description: I den här självstudiekursen får du hjälp med att skicka push-meddelanden från Adobe Campaign och ta emot dessa meddelanden i din Android-app.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 217b0ec1b6f5c5e17009f1103d69726aa57dcaa4
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 0%

---


# Självstudie Komma igång med push-meddelanden för Android - introduktion

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

I den här självstudiekursen får du hjälp med att skicka [!DNL push] meddelanden från Adobe Campaign till en [!DNL Android] app.

## Förhandskrav

Innan du kan börja måste du uppfylla följande krav:

1) MobilprogramDen här självstudiekursen innehåller inte de detaljerade steg som krävs för att konfigurera mobilprogrammet. Du måste ha ett **[!DNL Android]mobilprogram med det[!DNL Campaign SDK]** integrerade.

   * Du hittar en detaljerad beskrivning av de steg som krävs i [Integrera Campaign SDK i mobilappen](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html).

   * Du kan också använda Experience Platform Mobile SDK. Mer information finns i videon [Konfigurera push-kanalen med självstudiekursen Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) .

2) Paket för mobilappskanal har installerats

   Du måste ha mobilappskanalpaketet installerat på din instans. I följande video förklaras hur du kontrollerar om mobilappskanalen är installerad på din instans och, om inte, hur du installerar den.

   [!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Självstudiekurs

Vi vill skicka ett personligt reklamutskick till prenumeranterna på Neotrip- [!DNL Android] mobilappen. Neotrip-appen är konfigurerad med Campaign SDK och vi har sett till att mobilappskanalen aktiveras i vår Campaign-instans.

Följande konfigurationssteg krävs:

### Steg 1: Utöka programmets prenumerationsschema för att anpassa push-meddelanden

Eftersom vi vill anpassa push-meddelandet [utökar vi först appprenumerationsschemat](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) så att vi kan lagra de personaliseringsvärden som vi får från appen när användaren prenumererar på tjänsten.

### Steg 2: Konfigurera Android-tjänsten och skapa mobilappsprogrammet i Campaign

Därefter måste vi [konfigurera Android-tjänsten och skapa mobilappsprogrammet i Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). I det här steget ska vi definiera Neotrip-appen som mål för push-meddelandet.

### Steg 3: Konfigurera och skicka push-meddelanden

Sedan är vi redo att [konfigurera och skicka push-meddelandet](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Starta självstudiekursen

**[Steg 1: Utöka programmets prenumerationsschema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
