---
title: PagerDuty by PagerDuty，Inc. 的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: PagerDuty 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7c929966d7ab24f4e353ced553ea89737d5b7058
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430171"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月27日</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

PagerDuty，Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | PagerDuty |
| ID | WA200001637 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | PagerDuty, Inc. |
| 合作夥伴網站的 URL | [https://www.pagerduty.com](https://www.pagerduty.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| 隱私權原則的 URL | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| 使用條款的 URL | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

PagerDuty，Inc. 已提供此資訊。關於此應用程式如何收集和儲存組織的資料，以及您的組織將會透過應用程式收集的資料所產生的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings ReadWrite | 委託 | 從會議建立/取得回應，我們使用的欄位如下： join_web_url、audioConferencing。 需要這些欄位來顯示使用者在會議中連線的會議或替代方式的連結。 | 儲存： join_web_url、audioConferencing。 需要這些欄位來顯示使用者在會議中連線的會議或替代方式的連結。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | 委託 | 使用將 pagerduty 應用程式新增至聊天。 | 使用將 pagerduty 應用程式新增至聊天。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation ReadWriteForTeam 所有 | 委託 | 使用將 pagerduty 應用程式新增至聊天。 | 使用將 pagerduty 應用程式新增至聊天。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab ReadWrite。 | 委託 | 使用將 pagerduty 應用程式新增為會議中的索引標籤 | 使用將 pagerduty 應用程式新增為會議中的索引標籤 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | 委託 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | 委託 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| 電子郵件 | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是取得使用者和線上會議資訊的必要條件 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是 requred 用來取得使用者和線上會議的資訊 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是 requred，以取得使用者的相關資訊，以及建立/取得線上會議 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| 設定檔 | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是 requred，以取得使用者的相關資訊，以及建立/取得線上會議 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings ReadWrite | 委託 | 從會議建立/取得回應，我們使用的欄位如下： join_web_url、audioConferencing。 需要這些欄位來顯示使用者在會議中連線的會議或替代方式的連結。 | 儲存： join_web_url、audioConferencing。 需要這些欄位來顯示使用者在會議中連線的會議或替代方式的連結。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | 委託 | 使用將 pagerduty 應用程式新增至聊天。 | 使用將 pagerduty 應用程式新增至聊天。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation ReadForTeam 所有 | 委託 | 使用將 pagerduty 應用程式新增至聊天。 | 使用將 pagerduty 應用程式新增至聊天。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab ReadWrite。 | 委託 | 使用將 pagerduty 應用程式新增為會議中的索引標籤 | 使用將 pagerduty 應用程式新增為會議中的索引標籤 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | 委託 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | 委託 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | 使用資料：識別碼、userPrincipalName。它是用來讓 microsoft 團隊使用者將他們新增至會議做為參與者 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| 電子郵件 | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是取得使用者和線上會議資訊的必要條件 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是取得使用者和線上會議資訊的必要條件 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是 requred，以取得使用者的相關資訊，以及建立/取得線上會議 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| 設定檔 | 委託 | 使用授權和權杖要求。 使用資料： access_token、refresh_token、expires_in、範圍 | access_token、refresh_token、expires_in、範圍。 此資料是 requred，以取得使用者的相關資訊，以及建立/取得線上會議 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 資料 PagerDuty 維護僅限監控產品及 PII 資訊中的機器資料限制為：公司電子郵件地址、名字、姓氏和電話號碼。 您可以在以下位置找到具有該資料存取權的子處理器清單： https://www.pagerduty.com/subprocessors/ | 資料 PagerDuty 維護僅限監控產品及 PII 資訊中的機器資料限制為：公司電子郵件地址、名字、姓氏和電話號碼。 您可以在以下位置找到具有該資料存取權的子處理器清單： https://www.pagerduty.com/subprocessors/ | 資料 PagerDuty 維護僅限監控產品及 PII 資訊中的機器資料限制為：公司電子郵件地址、名字、姓氏和電話號碼。 您可以在以下位置找到具有該資料存取權的子處理器清單：您 https://www.pagerduty.com/subprocessors/ 可以在以下位置找到資料隱私權的詳細資訊： https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>PagerDuty 所需的資料安全性標準，至少必須與我們用來傳輸資料的所有廠商所維護的資料安全性標準一樣嚴格，包括已簽署 DPA 形式的合約義務。 您可以在以下位置找到資料安全性標準的詳細資訊： https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

PagerDuty，Inc. 已提供此資訊。關於此應用程式如何處理驗證、授權、application registration 最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
