---
title: Kontrollpanelen
seo-title: Kontrollpanelen
description: Med kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och tillåtelselista IP-adresser.
seo-description: Med kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och tillåtslista IP-adresser.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 76%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Termerna ”[!UICONTROL whitelist]” och ”[!UICONTROL blacklist]” har ersatts med ”[!UICONTROL allow list]” och ”[!UICONTROL block list]” i dokumentationen för Adobe Campaign.
>Vissa förekomster av dessa termer kan fortfarande finnas i produktgränssnittet, namn på alternativ, intern kod samt självstudievideor. De ersätts i kommande versioner av kontrollpanelen.

Med [!UICONTROL Control Panel] kan administratörer i Adobe Campaign övervaka nyckelresurser och utföra administrativa uppgifter såsom att hantera SFTP-lagringen per instans eller [!UICONTROL allow list]-IP-adresser.

## Komma åt [!UICONTROL Control Panel]

Gå till Experience Cloud Home på: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com) för att komma åt kontrollpanelen:

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   eller
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > **[!UICONTROL Control Panel]-kort **

   eller

* Direkt från webbadressen: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Förhandskrav

Slutför följande förhandskrav innan du börjar:

### Bekräfta [!DNL IMS Org ID]

Du måste känna till ditt [!DNL IMS org ID]. I följande video beskrivs var du kan hitta instansens [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Kontrollera[!DNL IMS Org ID](00:26 min)*

### Administratörsrättigheter

Administratörsrättigheter krävs för åtkomst till [!UICONTROL Control Panel].
I följande video förklaras hur du lägger till en administratör i en instans i Campaign

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Så här lägger du till en administratör i produktprofilen &quot;[!UICONTROL Administrators]&quot; för att kunna använda[!UICONTROL Control Panel](01:03 min)*

## [!UICONTROL Control Panel] självstudiekurser

* **Hantera SFTP-servrar**

   *Lär dig hur du övervakar serverkapaciteten, IP-adresserna och lägger till SSH-nycklar[!UICONTROL allow list]*

   * [Övervaka serverkapacitet, tillåtslista IP-adresser och lägga till SSH-nycklar](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Generera en SSH-nyckel](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Ansluta till en SFTP-server](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Delegera underdomäner](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Läs mer om hur du helt delegerar en underdomän till[!UICONTROL Adobe Campaign]*

* **[Lägga till SSL-certifikat](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Lär dig hur du kan lägga till ett SSL-certifikat för att skydda dina underdomäner med hjälp av Kontrollpanelen.*

* **[Lägga till URL-behörigheter](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *hur du lägger till vissa externa URL:er i listan över auktoriserade URL:er, så att instansen kan ansluta till dem.*

* **[Tillåtelselista med IP-adresser för åtkomst till instanser](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Lär dig hur du konfigurerar nya anslutningar till dina instanser med[!UICONTROL allow listing]IP-adressintervall.*

* **[Hantera Google TXT-poster](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Lär dig hur du lägger till[!DNL Google TXT]platsverifieringspost i alla dina underdomäner som används för att skicka e-post till[!DNL GMAIL]adresser via[!UICONTROL Campaign Control Panel].*

* **Hantera GPG-nycklar**

   *Läs mer om hur du skapar och installerar ett offentligt/privat nyckelpar på en angiven instans i Campaign för att kryptera utgående data. Samt även hur du importerar och installerar en offentlig nyckel på en instans i Campaign för att dekryptera inkommande data:*

   * [Generera och installera GPG-nycklar för datakryptering](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Kryptera data med en GPG-nyckel](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Dekryptera data](./gpg-key-management/decrypting-data.md)

* **[Felsöka kontrollpanelen](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Förstå hur du felsöker[!UICONTROL Control Panel]*

## Ytterligare resurser

* [Hjälpcenter för kontrollpanelen](https://docs.adobe.com/content/help/sv-SE/control-panel/using/control-panel-home.html)
