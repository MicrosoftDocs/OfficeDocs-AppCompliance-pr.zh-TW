---
title: 以 salesforce.com 為 Salesforce 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于 Salesforce 的安全性和符合性資訊資訊、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d0490ea422179e064443f7fad12abb64bc6efa47
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527909"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 salesforce.com 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Salesforce |
| ID | WA104379334 |
| 支援 Office 365 用戶端 | Outlook 2013 或更新版本的 Mac Windows Outlook 2016 或更新版本 Outlook 網頁版 |
| 合作夥伴公司名稱 | salesforce.com |
| 合作夥伴網站的 URL | [https://www.salesforce.com](https://www.salesforce.com) |
| 隱私權原則的 URL | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| 使用條款的 URL | [https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC...](https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC&amp;p5=WA104379334&amp;cmu=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 salesforce.com 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| 適用於 Office 的 JavaScript API | 是 | 增益集使用 Office.js 和 EWS 的功能來複製電子郵件的內容和附件。 Outlook 使用者已決定登入 Salesforce。 在行事曆一側使用類似的功能，將約會登入到 Salesforce。 |  | 增益集使用 getUserIdentityTokenAsync 之類的功能來取得目前的 Outlook 使用者身分識別。 GetItem (.js 及 EWS) 可取得及設定目前電子郵件訊息的 AdditionalProperties 和內容。儲存至 Salesforce 記錄時，GetAttachment (EWS) ，以從 Exchange 中取得附件，並新增至成對的 Salesforce 電子郵件、UpdateItem (.js) GetFolder (.js) 來取得草稿資料夾，CreateItem (.js) ，用來建立草稿郵件。 |  |
>| Exchange Web 服務 (EWS) | 是 | 增益集使用 Office.js 和 EWS 的功能來複製電子郵件的內容和附件。 Outlook 使用者已決定登入 Salesforce。 在行事曆一側使用類似的功能，將約會登入到 Salesforce。 |  | 增益集使用 getUserIdentityTokenAsync 之類的功能來取得目前的 Outlook 使用者身分識別。 GetItem (.js 及 EWS) 可取得及設定目前電子郵件訊息的 AdditionalProperties 和內容。儲存至 Salesforce 記錄時，GetAttachment (EWS) ，以從 Exchange 中取得附件，並新增至成對的 Salesforce 電子郵件、UpdateItem (.js) GetFolder (.js) 來取得草稿資料夾，CreateItem (.js) ，用來建立草稿郵件。 |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>《安全性指南》的《安全性指南》說明 https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

