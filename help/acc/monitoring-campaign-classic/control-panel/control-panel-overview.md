---
title: Kontrollpanelen
seo-title: Kontrollpanelen
description: På Kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och IP-adresser för tillåtelselista.
seo-description: På Kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och IP-adresser för tillåtelselista.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 4%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Termerna&quot;[!UICONTROL whitelist]&quot; och&quot;[!UICONTROL blacklist]&quot; har ersatts med&quot;[!UICONTROL allow list]&quot; och&quot;[!UICONTROL block list]&quot;i dokumentationen för Adobe Campaign.
>Vissa förekomster av dessa termer kan fortfarande finnas i produktgränssnittet, alternativnamn, intern kod samt självstudievideor. De kommer att ersättas i kommande versioner av Kontrollpanelen.

Med [!UICONTROL Control Panel] den kan Adobe Campaign-administratörer övervaka nyckelresurser och utföra administrativa uppgifter, som att hantera SFTP-lagring per instans eller [!UICONTROL allow list] IP-adresser.

## Åtkomst [!UICONTROL Control Panel]

Gå till startsidan för Kontrollpanelen: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   eller
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > **[!UICONTROL Control Panel]card **

   eller

* Direkt från webbadressen: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Förutsättningar

Innan du börjar, slutför du följande krav:

### Bekräfta [!DNL IMS Org ID]

Du måste känna din [!DNL IMS org ID]. I följande video beskrivs var du kan söka efter instansens [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Kontroll[!DNL IMS Org ID](00:26 min)*

### Administratörsrättigheter

Administratörsrättigheter krävs för åtkomst till [!UICONTROL Control Panel].
I följande video förklaras hur du lägger till en administratör i en Campaign-instans

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Så här lägger du till en administratör i produktprofilen&quot;[!UICONTROL Administrators]&quot; för att kunna använda[!UICONTROL Control Panel](01:03 min)*

## [!UICONTROL Control Panel] självstudiekurser

* **Hantera SFTP-servrar**

   *Lär dig hur du övervakar serverkapaciteten, IP-adresserna och lägger till SSH-nycklar[!UICONTROL allow list]*

   * [Övervaka serverkapacitet, tillåt listning av IP-adresser och lägga till SSH-nycklar](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Generera en SSH-nyckel](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Ansluta till en SFTP-server](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Delegera underdomäner](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Lär dig hur du delegerar en underdomän till[!UICONTROL Adobe Campaign]*

* **[Lägger till SSL-certifikat](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Lär dig hur du kan lägga till ett SSL-certifikat för att skydda dina underdomäner med hjälp av Kontrollpanelen.*

* **[Hantera SSL-certifikat](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *Lär dig hur du kan visa SSL-certifikatstatusen för dina underdomäner, samt begära förnyelser.*

* **[Lägga till URL-behörigheter](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *hur du lägger till vissa externa URL:er i listan över auktoriserade URL:er, så att instansen kan ansluta till dem.*

* **[Tillåtelselista med IP-adresser för åtkomst till instanser](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Lär dig hur du konfigurerar nya anslutningar till dina instanser med[!UICONTROL allow listing]IP-adressintervall.*

* **[Hantera Google TXT-poster](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Lär dig hur du lägger till[!DNL Google TXT]platsverifieringspost i alla dina underdomäner som används för att skicka e-post till[!DNL GMAIL]adresser via[!UICONTROL Campaign Control Panel].*

* **GPG-nyckelhantering**

   *Lär dig hur du skapar och installerar ett nyckelpar för offentlig/privat nyckel på en angiven Campaign-instans för kryptering av utgående data, samt importerar och installerar en offentlig nyckel på en Campaign-instans för dekryptering av inkommande data:*

   * [Generera och installera GPG-nycklar för datakryptering](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Kryptera data med en GPG-nyckel](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Dekrypterar data](./gpg-key-management/decrypting-data.md)

* **[Felsöka kontrollpanelen](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Förstå hur du felsöker[!UICONTROL Control Panel]*

## Ytterligare resurser

* [Hjälpcenter för kontrollpanelen](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html)
