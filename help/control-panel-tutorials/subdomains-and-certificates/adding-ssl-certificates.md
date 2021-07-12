---
title: Lägga till SSL-certifikat
description: Lär dig hur du lägger till SSL-certifikat för att skydda dina underdomäner.
feature: 'Kontrollpanelen  '
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/adding-ssl-certificates.html
exl-id: 9ba485fb-be26-4f3c-a9de-844fecaec20d
source-git-commit: da757603c597453ef6b7195329b5b44ab6e5c77d
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 89%

---

# Lägga till SSL-certifikat

Med [!UICONTROL Control Panel] i Adobe Campaign kan du lägga till SSL-certifikat för att skydda underdomänerna.

## Komma åt hantering av underdomäner på kontrollpanelen

För att få åtkomst till hantering av underdomäner på kontrollpanelen ska du gå du till:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: **[!DNL Campaign]** > kortet **[!UICONTROL Control Panel]** > kortet **[!UICONTROL Subdomains & Certificates]**

   eller
* Direkt från webbadressen: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Stegvis lägga till SSL-certifikat

Att lägga till SSL-certifikat kräver tre steg:

### 1. Skapa en begäran om certifikatsignering

Begäran om certifikatsignering (CSR) krävs för köp av ett SSL-certifikat. Det måste skapas för instansen och de underdomäner som ska skyddas.

I videon nedan förklaras hur du skapar en begäran om certifikatsignering på kontrollpanelen.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*Skapa en begäran om certifikatsignering (02:36 min)*

### 2. Köpa SSL-certifikat

När du har fått en begäran om certifikatsignering måste du köpa SSL-certifikatet från en certifikatutfärdare som är godkänd av din organisation.

### 3. Installera SSL-certifikat

När du har fått SSL-certifikatet måste det installeras för de underdomäner som ska skyddas.

I videon nedan förklaras hur du installerar SSL-certifikat i [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*Installera SSL-certifikat (01:25 min)*

## Ytterligare resurser

* [Fullständig underdomändelegering (video)](./subdomain-delegation.md)
* [Förnya en underdomäns SSL-certifikat (dokumentation)](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)