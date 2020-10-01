---
title: Konfigurera valideringsarbetsflöden i Adobe Campaign Classic
seo-title: Konfigurera valideringsarbetsflöden i Adobe Campaign Classic
description: Adobe Campaign erbjuder flera sätt för marknadsförare att granska och tillhandahålla leveransinnehåll, kampanjmål, dataextrahering och budgetgodkännanden. I den här självstudiekursen beskrivs hur du konfigurerar olika arbetsflöden för godkännandevalidering.
seo-description: Den här videon förklarar hur du konfigurerar och använder en leveransmall i ACCAdobe Campaign innehåller flera alternativ för marknadsförare som kan granska och tillhandahålla leveransinnehåll, kampanjmål, dataextrahering och budgetgodkännanden. I den här självstudiekursen beskrivs hur du konfigurerar olika arbetsflöden för godkännandevalidering.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Konfigurera valideringsarbetsflöden i Adobe Campaign Classic

Adobe Campaign erbjuder flera sätt för marknadsförare att granska och tillhandahålla leveransinnehåll, kampanjmål, dataextrahering och budgetgodkännanden.

I den här självstudiekursen beskrivs hur du konfigurerar olika arbetsflöden för godkännandevalidering.

## Förutsättning {#prerequisite}

Innan godkännandestegen aktiveras måste marknadsföringsteamet definiera enskilda granskare:

* Adobe Campaign granskarroll inom en godkännandeaktivitet kan antingen vara en enskild granskare (Operator) eller en grupp med granskare (Operator role).
* Grupper för granskare och granskare måste tidigare konfigureras i Adobe Campaign med en administratörsroll. Detta gör att kampanjutvecklare kan välja granskarna som godkännare i en kampanj eller leverans.

## Konfigurera godkännanden för kampanjer  {#configuring-approvals-for-campaigns}

Om ni har samma uppsättning granskare för alla leveranser i ert kampanjarbetsflöde skulle ni utnyttja [!DNL Campaign] godkännandefunktionerna. Genom att ställa in godkännanden och granskare på kampanjnivå kommer godkännandeaktiviteterna och granskarna att flyttas ned till varje leveransaktivitet i arbetsflödet när arbetsflödet har körts.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Konfigurera godkännanden för leveranser  {#configuring-approvals-for-deliveries}

Du kan också konfigurera godkännanden på leveransnivå. Om stegen för leveransgodkännande och granskarna skiljer sig från stegen för kampanjgodkännande och granskarna, kommer leveransinställningarna att åsidosätta kampanjinställningarna.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Konfigurera en godkännandeaktivitet  {#configuring-an-approval-activity}

Till skillnad från leverans- eller kampanjgodkännandena gör godkännandeaktiviteten det möjligt att skapa en godkännandeprocess i ett arbetsflöde. På så sätt kan logiken för målval godkännas innan leveransen startas. Det tillåter även godkännande på flera nivåer i arbetsflödet vid behov.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
