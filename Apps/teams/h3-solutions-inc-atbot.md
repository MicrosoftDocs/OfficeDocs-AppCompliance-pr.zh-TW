---
title: 以 H3 解決方案，Inc. 為 AtBot 的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: AtBot 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4280f34bdcd960664e77e95541d7ede3102608cf
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093732"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 H3 解決方案（Inc.）提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | AtBot |
| ID | WA104381219 |
| 功能 | Bot |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | H3 Solutions， Inc. |
| 合作夥伴網站的 URL | [https://atbot.io](https://atbot.io) |
| Teams 應用程式資訊頁面的 URL | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| 隱私權原則的 URL | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| 使用條款的 URL | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 H3 解決方案（Inc.）提供。關於此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | 應用程式 | AAD 群組名稱、AAD 群組 GUID、UPN | 列舉 AAD 群組，以允許 bot 技能的安全性調整。 列舉使用者能夠套用授權。 列舉要新增為系統管理員/參與者的使用者 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | 委託 | AAD 群組名稱、AAD 群組 GUID、UPN | 列舉 AAD 群組，以允許 bot 技能的安全性調整。 列舉使用者能夠套用授權。 列舉要新增為系統管理員/參與者的使用者 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| 個人讀取 | 委託 | 否 | 從 Flow 列舉「取得人員」動作中的人員。  允許 bot 從 Microsoft Graph 中的/People 端點中取得人員。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | 委託 | 租使用者識別碼（UPN） | 讓我們能夠存取使用者&#8217;s 租使用者識別碼和 UPN，以允許我們將所建立的流量/邏輯應用程式，與建立它們的使用者關聯。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| 電子郵件 | 委託 | 否 | 讓我們能夠存取使用者的電子郵件地址。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | 委託 | 存取/重新整理權杖。 | 允許我們使用重新整理權杖，讓使用者保持登入。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | 委託 | 否 | 允許使用者登入。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| profile | 委託 | UPN | 存取使用者的 UPN。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 在 bot 產生的聊天訊息中建立提及 | 否 |  |



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>租使用者識別碼，使用 Application Insights 的 UPN，我們的記錄會持續達90天，然後才會自動封存。 (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>管理員可以刪除可以包含 AAD 群組名稱/Guid 的 bot 設定。
取消服務後，將會從授權資料庫中移除所有的 Upn。
請參閱 Data Residency 下的「Azure 服務」。  許多透過使用 AtBot 所產生的客戶特定資料，都是儲存在客戶的承租人中，因此該承租人的系統管理員可以完全控制其資料。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

