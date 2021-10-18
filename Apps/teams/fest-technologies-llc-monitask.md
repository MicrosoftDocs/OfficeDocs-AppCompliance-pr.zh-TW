---
title: Monitask by FEST 技術的應用程式資訊，LLC
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Monitask 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 1d97a2413b4025c999ef071e59afe79b4638e5db
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428286"
---
# <a name="monitask"></a>Monitask

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月23日</p>

* <a href="https://teams.microsoft.com/l/app/0b49493f-fc40-49e1-9e3b-6515588af2b5" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002986" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

FEST 技術所提供的資訊，LLC 至 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Monitask |
| ID | WA200002986 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | FEST Technologies, LLC |
| 合作夥伴網站的 URL | [https://www.monitask.com](https://www.monitask.com) |
| 隱私權原則的 URL | [https://www.monitask.com/en/home/privacypolicy](https://www.monitask.com/en/home/privacypolicy) |
| 使用條款的 URL | [https://www.monitask.com/en/home/termsofservice](https://www.monitask.com/en/home/termsofservice) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 FEST 技術所提供，LLC 是此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| EUII 是在 Monitask user 和 MS Teams 使用者之間找到相符項所必需的 | ms Teams 使用者識別碼、毫秒 Teams Bot 交談識別碼、ms Teams AadObjectId | MS Teams 使用者識別碼，以在與 bot 的交談的上下文中尋找 Monitask 使用者和 MS Teams 使用者之間的相符性;需要有 Bot 交談識別碼才能從 Monitask 傳送至使用者的「每日」報告」;ms Teams AadObjectId 是必要的，可在 MS Teams 的「Tab」內容中尋找 Monitask user 和 ms Teams 使用者之間的相符性。  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>MS Teams 使用者識別碼和交談識別碼會儲存在記錄檔中。 記錄檔會儲存在 Azure Application Insights 90 天內

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們有完全控制儲存的資料

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

FEST 技術會提供此資訊，LLC 關於此應用程式如何處理驗證、授權、application registration 最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
