---
title: Felsöka kontrollpanelen
description: Med kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och tillåtslista IP-adresser.
feature: 'Kontrollpanelen  '
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
exl-id: 016e8b77-20df-4ca5-b5e7-fe2f3e7ba7a3
source-git-commit: 77e4a26811f7c7b814a7d8060bbb0f84196caed4
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 42%

---

# Felsöka [!UICONTROL Control Panel]

## Logga in och hemsida

### Symptom: Det går inte att logga in i Experience Cloud

**Vad du ska göra:**
Användaren måste hitta sitt IMS-org-ID (xxx). Administratören måste lägga till användaren i produktprofilen&quot;Campaign-xxx-Admins&quot; för varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som användare.

### Symptom: Länkar i Experience Cloud Home för åtkomst till [!UICONTROL Control Panel] visas inte för en användare

**Orsak:**
Användare kan inte se länkarna förrän de har lagts till som användare i produktprofilen  _Campaign-xxx-Administrators/Admin_.

**Vad du ska göra:**
Administratören måste lägga till användaren i produktprofilen  _Campaign-xxx-_  Adminsför varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som användare.

### Symptom: En instans visas inte i [!UICONTROL Control Panel]

**Orsak:**
Den mest troliga användaren måste läggas till som en  ** userProduct Profile  _Campaign-xxx-Administrators/_ Adminfor den instans som saknas

**Vad du ska göra:**
Administratören måste lägga till användaren i produktprofilen  _Campaign-xxx-_  Adminsför varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som&quot;användare&quot;.

### Användbara videor

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Kontrollera ett IMS-organisations-ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Så här lägger du till en administratör i produktprofilen administratörer för att kunna använda [!UICONTROL Control panel] (01:03 min)*

### Användbar dokumentation

* [Lär känna kontrollpanelen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=sv)
* [Hantera behörigheter i [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Upprätta en anslutning till en SFTP-server (klient eller API)

För anslutning till SFTP-servrar krävs:

* [!UICONTROL Allow listing]-IP-adressen som används för anslutning till SFTP-servern
* Privat/offentlig nyckel som måste registreras hos Adobe Campaign
* Om du vill ansluta till SFTP-servern direkt behöver du också SFTP-klientprogramvara

### Användbar dokumentation {#helpful-docs}

* [Logga in på SFTP-servern](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
