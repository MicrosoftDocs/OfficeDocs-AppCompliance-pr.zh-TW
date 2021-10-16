---
title: 以 ne 為 NE 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于 NE 的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8c0637bd18205f8c44c27ba43afd5c091361cb98
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415020"
---
# <a name="ne"></a>NE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月10日</p>

* <a href="https://teams.microsoft.com/l/app/bd4bd4f6-ec6c-42b3-b296-bf39b8b758b3" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000840" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 NE 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | NE |
| ID | WA200000840 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | NE |
| 合作夥伴網站的 URL | [https://www.ne.se](https://www.ne.se) |
| Teams 應用程式資訊頁面的 URL | [https://www.ne.se/info/om-oss/](https://www.ne.se/info/om-oss/) |
| 隱私權原則的 URL | [https://www.ne.se/info/hj%C3%A4lp/behandling-av-personuppgi...](https://www.ne.se/info/hj%C3%A4lp/behandling-av-personuppgifter/) |
| 使用條款的 URL | [https://www.ne.se/info/hj%c3%a4lp/allm%c3%a4nna-avtalsvillk...](https://www.ne.se/info/hj%c3%a4lp/allm%c3%a4nna-avtalsvillkor/fleranv%c3%a4ndare/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

這種資訊已由 NE 提供此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Oauth | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| user.com、mailchimp | 電子郵件地址、名稱、組織 | 支援聊天 bot、目標行銷、重設密碼的電子郵件 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>電子郵件地址、6個月後刪除的電子郵件地址，或使用者取消訂閱時

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>刪除、保留、編輯、審計

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

這種資訊已由 NE 提供此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

