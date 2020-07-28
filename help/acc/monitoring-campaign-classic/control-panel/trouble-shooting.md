---
title: Kontrollpanelen Felsökning
description: På Kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och IP-adresser för tillåtelselista.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 1%

---


# Felsökning [!UICONTROL Control Panel]

## Inloggning och hemsida

### Symptom: Det går inte att logga in på Experience Cloud

**Så här gör du:**
Användaren måste hitta sitt IMS-organisations-ID (xxx). Administratören måste lägga till användaren i produktprofilen&quot;Campaign-xxx-Admins&quot; för varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser kan han eller hon fortfarande behöva lägga till sig själv som användare.

### Symptom: Länkar i Experience Cloud Hem som du vill få åtkomst till visas [!UICONTROL Control Panel] inte för en användare

**Orsak:**
Användarna kan inte se länkarna förrän de läggs till som användare i produktprofilen&quot;Campaign-xxx-Administrators/Admin&quot;

**Så här gör du:**
Administratören måste lägga till användaren i produktprofilen&quot;Campaign-xxx-Admins&quot; för varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser kan han eller hon fortfarande behöva lägga till sig själv som&quot;användare&quot;.

### Symptom: En instans visas inte i listan [!UICONTROL Control Panel]

**Orsak:**
Den mest troliga användaren måste läggas till som en användarproduktprofil,&quot;Campaign-xxx-Administrators/Admin&quot;, för den instans som saknas

**Så här gör du:**
Administratören måste lägga till användaren i produktprofilen&quot;Campaign-xxx-Admins&quot; för varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser kan han eller hon fortfarande behöva lägga till sig själv som&quot;användare&quot;.

### Användbara videor

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Kontrollera IMS-organisations-ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Så här lägger du till en administratör i produktprofiladministratörerna för att kunna använda[!UICONTROL Control panel](01:03 min)*

### Användbar dokumentation

* [Upptäck Kontrollpanelen](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [Hantera behörigheter för [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Upprättar anslutning till SFTP-server (klient eller API)

Anslutning till SFTP-servrar kräver:

* [!UICONTROL Allow listing] IP-adressen som du ansluter till SFTP-servern från
* Privat/offentligt nyckelpar som måste registreras i Adobe Campaign
* Om du ansluter till SFTP-servern direkt behöver du också SFTP-klientprogramvara

### Användbar dokumentation

* [Logga in på SFTP-servern](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

