---
title: Hi5 的應用程式資訊（按 Hi5Technologies）
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Hi5 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 983f86210f224bc492f54a7ab65192dee5b4ad6c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552114"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2020年11月3日</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Hi5Technologies 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Hi5 |
| ID | WA200001610 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Hi5Technologies |
| 合作夥伴網站的 URL | [https://www.get5.io/](https://www.get5.io/) |
| 隱私權原則的 URL | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| 使用條款的 URL | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Hi5Technologies 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委託 | 我們只會將使用者會話資訊從 Teams 儲存，使用者必須透過新增通知來核准此資訊， (可以隨時) 。 不會儲存其他資訊。 | 針對伺服器進行 SSO 登入和驗證所需 | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| 電子郵件 | 委託 | 我們只會將使用者會話資訊從 Teams 儲存，使用者必須透過新增通知來核准此資訊， (可以隨時) 。 不會儲存其他資訊。 | 針對伺服器進行 SSO 登入和驗證所需 | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| offline_access | 委託 | 我們只會將使用者會話資訊從 Teams 儲存，使用者必須透過新增通知來核准此資訊， (可以隨時) 。 不會儲存其他資訊。 | 維護使用者看到正確的資訊，而且我們可以將正確的資訊傳送給加入相同公司/工作區的其他人。 | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| openid | 委託 | 我們只會將使用者會話資訊從 Teams 儲存，使用者必須透過新增通知來核准此資訊， (可以隨時) 。 不會儲存其他資訊。 | 針對伺服器進行 SSO 登入和驗證所需 | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| profile | 委託 | 我們只會將使用者會話資訊從 Teams 儲存，使用者必須透過新增通知來核准此資訊， (可以隨時) 。 不會儲存其他資訊。 | 針對伺服器進行 SSO 登入和驗證所需 | 7cb50e3e-0427-409e-90d2-638eb28217c3 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 在頻道中通知使用者他們已獲得 Hi5 | 未儲存任何資訊，使用者將會在通道中發回的卡片只是 @。 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>否，Hi5 只會在 iFramed 中，而且會安全地儲存所有資料。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們使用 OAuth，並提供三種登入選項：
- Googles SSO (OAuth) 。
- Microsoft SSO (OAuth) 。
- 我們自己的加密，是 SHA 和 AES 加密的組合。
一旦驗證並登入，您的許可權等級就會授與您存取 Hi5 平臺內授權的區段。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

