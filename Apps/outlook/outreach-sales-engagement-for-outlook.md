---
title: 透過推廣 Outlook 的推廣銷售專案應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊，針對 Outlook 的「推廣」銷售人員，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 6a009dbc5c075f99bb71105834f3f5208ed91dea
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279278"
---
# <a name="outreach-sales-engagement-for-outlook"></a>Outlook 的推廣銷售專案

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月14日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381052" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

透過推廣資訊提供給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Outlook 的推廣銷售專案 |
| ID | WA104381052 |
| 支援 Office 365 用戶端 | Outlook 2013 或更新版本的 Mac Windows Outlook 2016 或更新版本 Outlook 網頁版 |
| 合作夥伴公司名稱 | 外 展 |
| 合作夥伴網站的 URL | [https://www.outreach.io](https://www.outreach.io) |
| 隱私權原則的 URL | [https://www.outreach.io/legal/privacy-policy/](https://www.outreach.io/legal/privacy-policy/) |
| 使用條款的 URL | [https://www.outreach.io/terms](https://www.outreach.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊已透過有關此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項的進一步推廣，提供此資訊。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook增益集 API、EWS API、O36 REST API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Salesforce CRM | 與 Salesforce 整合的整合允許兩個服務之間的有限資料集的安全雙向同步處理包含;組織名稱、電子郵件地址和使用者名稱。 | 「推廣」的智慧雙方向同步處理可確保兩個系統中的資料之間完全逼真度。 所有在 &#8212; 通話、電子郵件等 &#8212; 中執行的活動都會自動登入，並且衝突解決會偵測並解決衝突，以保持資料 pristine。 它可在 Salesforce Aloha 和閃電版中運作。 |



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>「推廣」不會將保留期間套用至我們的客戶&#8217;s 資料。 推廣會做為資料處理者，如此一來，就不會變更我們的客戶&#8217;的資料，而不需要其明確的許可權。 根據我們的 MSA 和 DPA，所有客戶資料在業務關係結束之後都會遭到刪除（以60天為單位）。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>「推廣」（適用于合約和法規原因）也是必要為所有使用新的客戶提供及時通知，或對 subprocessor 進行變更。 對於大部分的「推廣」客戶而言，這是30天的期限。 不過，我們有幾個客戶使用60和90天的通知需求。 在合法要求的新子流程通知已傳送給所有客戶，且所需的時間範圍已傳送給所有客戶，否則不會傳輸客戶資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊已透過有關此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則的進一步推廣所提供。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
