---
title: Felsöka kontrollpanelen
description: Med kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och tillåtslista IP-adresser.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 51bfeb7f53cc68b78080ae7106ab8188cb78adb6
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 100%

---


# Felsöka [!UICONTROL Control Panel]

## Logga in och hemsida

### Symptom: Det går inte att logga in på Experience Cloud

**Så här gör du:**
Användaren måste hitta sitt IMS-organisations-ID (xxx). Administratören måste lägga till användaren i produktprofilen &quot;Campaign-xxx-Admins&quot; för varje instans som denne vill hantera. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som användare.

### Symptom: Länkar i Experience Cloud Home för åtkomst till [!UICONTROL Control Panel] visas inte för en användare

**Orsak:**
Användare kan inte se länkarna förrän de har lagts till som användare i produktprofilen _Campaign-xxx-Administrators/Admin_.

**Så här gör du:**
Administratören måste lägga till användaren i produktprofilen _Campaign-xxx-Admins_ för varje instans som denne vill hantera. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som &quot;användare&quot;.

### Symptom: En instans visas inte i [!UICONTROL Control Panel]

**Orsak:**
Troligtvis måste användaren läggas till som en &quot;användare&quot; i produktprofilen _Campaign-xxx-Administrators/Admin_ i den instans som saknas

**Så här gör du:**
Administratören måste lägga till användaren i produktprofilen _Campaign-xxx-Admins_ för varje instans som denne vill hantera. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som &quot;användare&quot;.

### Användbara videor

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Kontrollera ett IMS-organisations-ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Så här lägger du till en administratör i produktprofilen administratörer för att kunna använda[!UICONTROL Control panel] (01:03 min)*

### Användbar dokumentation

* [Lär känna kontrollpanelen](https://helpx.adobe.com/se/campaign/kb/control-panel-overview.html)
* [Hantera behörigheter i [!UICONTROL Control Panel]](https://helpx.adobe.com/se/campaign/kb/control-panel-access.html)

## Upprätta en anslutning till en SFTP-server (klient eller API)

För anslutning till SFTP-servrar krävs:

* [!UICONTROL Allow listing]-IP-adressen som används för anslutning till SFTP-servern
* ett privat/offentligt nyckelpar som måste registreras i Adobe Campaign
* Om du ansluter till SFTP-servern direkt behöver du även en SFTP-klientprogramvara

### Användbar dokumentation

* [Logga in på SFTP-servern](https://helpx.adobe.com/se/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

