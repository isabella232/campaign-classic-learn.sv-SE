---
title: Komma igång med push-meddelanden för Android – inledning
description: I den här självstudiekursen visas steg för steg hur du skickar push-meddelanden från Adobe Campaign och tar emot dessa meddelanden i din Android-app.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
source-git-commit: 13f7ab2dd41216a603a22f181dc4d06302c5918a
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Komma igång med push-meddelanden för Android – inledning

Adobe Campaign låter dig skicka personaliserade och segmenterade [!DNL push]-meddelanden till mobila [!DNL iOS]- och [!DNL Android]-enheter I den här självstudiekursen får du hjälp med att skicka [!DNL push]-meddelanden från Adobe Campaign till en [!DNL Android]-app.

## Förhandskrav

Innan du kan börja måste du ha följande:

1) **Mobil Android-app**

   Den här självstudiekursen omfattar inte de detaljerade steg som krävs för att konfigurera den mobila appen. Du måste ha en mobil **[!DNL Android]-app med [!DNL Campaign SDK] integrerat**.

   Du hittar en detaljerad beskrivning över stegen som krävs i produktdokumentationen:

   [Integrera Campaign SDK i den mobila applikationen](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=sv)

   Du kan också använda Experience Platform Mobile SDK. Titta på självstudievideon för mer information:

   [Konfigurera push-kanalen med Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=sv)

2) **[!DNL Mobile App channel]-paket installerat**

   [!DNL Mobile App channel]-paketet måste installeras på din instans i [!DNL Campaign]. Följande video förklarar hur du kontrollerar om [!DNL Mobile App channel] är installerat på din instans och hur du installerar det om så inte är fallet.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on)

## Översikt över självstudiekurser

Vi vill skicka ett personaliserat [!DNL push]-reklammeddelande till prenumeranterna av den mobila appen [!DNL Neotrip] för [!DNL Android]. Appen [!DNL Neotrip] har konfigurerats med [!DNL Campaign SDK] och vi har sett till att [!DNL Mobile App channel] är aktiverat på vår instans i [!DNL Campaign].

Följande konfigurationssteg krävs:

### Steg 1: utöka appens prenumerationsschema för att anpassa [!DNL push]-meddelanden

Eftersom vi vill anpassa [!DNL push]-meddelandet utökar vi först [programmets prenumerationsschema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) för att kunna spara de personaliseringsvärden som vi får från appen när användaren prenumererar på tjänsten.

### Steg 2: konfigurera Android-tjänsten och skapa den mobila appen i Campaign

Därefter måste vi [konfigurera Android-tjänsten och skapa den mobila appen i Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). I det här steget definierar vi appen [!DNL Neotrip] som mål för push-meddelandet.

### Steg 3: konfigurera och skicka push-meddelandet

Sedan är vi redo att [konfigurera och skicka push-meddelandet](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Starta självstudiekursen

Steg 1: [utöka appens prenumerationsschema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
