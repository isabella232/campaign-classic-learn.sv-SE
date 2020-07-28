---
title: Lägger till SSL-certifikat
description: Med Kontrollpanelen i Adobe Campaign kan du lägga till SSL-certifikat för att skydda dina underdomäner.
feature: SSL Certificates
topics: Control Panel
kt: 4219
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 4%

---


# Lägger till SSL-certifikat

Med Kontrollpanelen i Adobe Campaign kan du lägga till SSL-certifikat för att skydda dina underdomäner.

## Åtkomst till hantering av underdomäner på Kontrollpanelen

Gå till följande för att få åtkomst till hantering av underdomäner på Kontrollpanelen:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: Campaign > **Control Panel** card > **Subdomains &amp; Certificates** card

   eller
* Direkt från webbadressen: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Steg för att lägga till SSL-certifikat

För att lägga till SSL-certifikat krävs tre steg:

### 1. Generera begäranden om certifikatsignering

CSR (Certificate Signing Request) krävs för köp av ett SSL-certifikat. Jag måste skapas för instansen och de underdomäner som du tänker skydda.

I videon nedan beskrivs hur du skapar en CSR-fil (Certificate Signing Request) på Kontrollpanelen.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)
*Generera begäranden om certifikatsignering (02:36 min)*

### 2. Köp SSL-certifikat

När du har fått CSR måste du köpa SSL-certifikatet från en certifikatutfärdare som är godkänd av din organisation.

### 3. Installera SSL-certifikat

När du har fått SSL-certifikatet måste det installeras för de underdomäner som du planerar att skydda.

I videon nedan beskrivs hur du installerar SSL-certifikat på Kontrollpanelen.

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)
*Installera SSL-certifikat (01:25 min)*

## Ytterligare resurser

* [Delegera underdomäner](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)
* [Underdomäner och certifikat - dokumentation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)
