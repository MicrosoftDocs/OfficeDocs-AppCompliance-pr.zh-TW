---
title: Monday.com 的應用程式資訊（按 monday.com）
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
description: monday.com 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cf4fc476626fe4f623c6941cc2da096ec2a1ae41
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092774"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年9月28日</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 monday.com 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | monday.com |
| ID | WA200001798 |
| 功能 | Bot，索引標籤，傳訊擴充功能 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | monday.com |
| 合作夥伴網站的 URL | [https://monday.com](https://monday.com) |
| 隱私權原則的 URL | [https://monday.com/privacy](https://monday.com/privacy) |
| 使用條款的 URL | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 monday.com 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com 會使用下列子處理器，以取得其服務的效能： &#160;https://monday.com/terms/subprocessors |  | monday.com 未使用 APIs。 我們會使用下列 Microsoft framework 來取得服務 (的效能，如上述回應所述) ： &#8216;botbuilder&#8217; &#8216;botframework-連接器&#8217; &#8216; @micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>monday.com 會儲存應用程式記錄檔，其中包含使用者在有限的時段內產生的內容，讓我們的 R &amp; D 人員能夠疑難排解錯誤及使用者報告的問題。 包含 IP 位址的安全性記錄會保留較長的時間，每個資料保留原則都會保留一段時間。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>monday.com 服務主控于北弗吉尼亞州的 AWS 基礎結構，以及在不同地區建立的 DR 網站。 某些備份資料儲存在 GCP (US，多地區) 。 存取 monday.com 服務是由使用者組織的系統管理員所控制，且是透過使用下列功能來完成：
- 使用者類型
- 帳戶層級許可權
- Workspaces
- 版塊類型
- 董事會層級許可權
- 欄層級許可權 monday.com 支援下列驗證方法：
- Credentials
- Pro 計畫) Google SSO (
- Enterprise) 計畫的 Okta、OneLogin 和自訂 SAML 2.0 (，可透過簡訊或驗證器應用程式透過平臺的系統管理員面板，由帳戶管理員選擇啟用。
所有靜態資料都是使用 AES-256 加密。 所有在開啟的網路中傳輸的資料，都是以 TLS 1.3 (TLS 1.2，至少) 進行加密。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

