---
title: Felsöka kontrollpanelen
description: På Kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och tillåtslista IP-adresser.
feature: 'Kontrollpanelen  '
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 42%

---


# Felsöka [!UICONTROL Control Panel]

## Logga in och hemsida

### Symptom: Det går inte att logga in i Experience Cloud

**Vad du ska göra:**
Användaren måste hitta sitt IMS-org-ID (xxx). Administratören måste lägga till användaren i produktprofilen&quot;Campaign-xxx-Admins&quot; för varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som användare.

### Symptom: Länkar i Experience Cloud Home för åtkomst till [!UICONTROL Control Panel] visas inte för en användare

**Orsak:**
Användare kan inte se länkarna förrän de har lagts till som användare i produktprofilen _Campaign-xxx-Administrators/Admin_.

**Vad du ska göra:**
Administratören måste lägga till användaren i produktprofilen  _Campaign-xxx-_  Adminsför varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som &quot;användare.

### Symptom: En instans visas inte i [!UICONTROL Control Panel]

**Orsak:Den**
mest troliga användaren måste läggas till som en&quot;användare&quot;-produktprofil  _Campaign-xxx-Administrators/_ Adminför den instans som saknas

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
* Om du ansluter till SFTP-servern direkt behöver du SFTP-klientprogramvara

### Användbar dokumentation {#helpful-docs}

* [Logga in på SFTP-servern](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

