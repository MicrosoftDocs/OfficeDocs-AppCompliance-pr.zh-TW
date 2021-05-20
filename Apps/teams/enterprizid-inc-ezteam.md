---
title: EzTeam by EnterprizID Inc. 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ezTeam 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553174"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2021年2月24日</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 EnterprizID Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | ezTeam |
| ID | WA200002546 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | EnterprizID Inc |
| 合作夥伴網站的 URL | [https://enterprizid.com](https://enterprizid.com) |
| Teams 應用程式資訊頁面的 URL | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| 隱私權原則的 URL | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| 使用條款的 URL | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

EnterprizID Inc. 已提供此資訊，供 Inc. 使用此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog Read。 All | 委託 | 可在 Teams 使用的應用程式清單，讓我們可以在 Teams 要求建立程式上顯示它 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application。 Read。 All | 委託 | 允許此應用程式代表已登入的使用者讀取應用程式和服務主體。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | 委託 | 允許此應用程式存取目錄中的資訊，以登入的使用者。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | 委託 | 允許此應用程式讀取組織目錄中的資料，例如使用者、群組和應用程式。 | Teams擁有權和成員資格資訊  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | 應用程式 | 允許此應用程式讀取組織目錄中的資料，例如使用者、群組和應用程式，而無需登入的使用者。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | 委託 | 允許此應用程式讀取及寫入您組織的目錄中的資料，例如使用者和群組 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | 應用程式 | 允許此應用程式讀取及寫入您組織的目錄中的資料，例如使用者和群組，而不需要登入的使用者。 不允許刪除使用者或群組。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | 應用程式 | 允許此應用程式在未登入的使用者中讀取所有網站集合中的所有檔案。 | 使用者管理下的資料量（GB） | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group。建立 | 應用程式 | 允許此應用程式建立沒有登入使用者的群組。 | 新的群組屬性詳細資料。 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | 委託 | 允許應用程式列出群組，並代表登入的使用者讀取其屬性及所有群組成員資格。 用於判斷我的 Teams  | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | 應用程式 | 允許此應用程式讀取群組屬性和成員資格，並讀取所有群組的行事曆和交談，而不需要登入的使用者。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | 委託 | 允許此應用程式代表登入的使用者建立群組，以及讀取所有群組屬性和成員資格。  | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | 應用程式 | 允許此應用程式建立群組、讀取所有群組屬性和成員資格、更新群組屬性和成員資格，以及刪除群組。 也可讓應用程式讀取及寫入群組行事曆中和交談。  | 小組的最後一個活動。 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember Read。 All | 應用程式 | 允許應用程式讀取所有群組的成員資格和基本群組內容，而無需登入的使用者。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember ReadWrite。 | 應用程式 | 允許此應用程式列出群組、讀取基本屬性、讀取和更新此應用程式沒有登入使用者存取權的群組成員資格。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| 已讀取的人員。所有 | 應用程式 | 允許此應用程式讀取任何使用者的相關人員得分清單，而不需要登入的使用者。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports。已讀取。所有 | 委託 | 允許應用程式代表已登入的使用者讀取所有服務使用方式報告。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports。已讀取。所有 | 應用程式 | 允許應用程式讀取所有未登入使用者的服務使用方式報告。 | 每個群組的最後一個使用者活動 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | 應用程式 | 允許此應用程式在未登入使用者的情況下，建立、讀取、更新及刪除所有網站集合中的檔和清單專案。 | 依每個使用者大小的前10個網站 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | 委託 | 允許使用者登入 app，並允許此應用程式讀取登入使用者的設定檔。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | 應用程式 | 允許應用程式讀取使用者設定檔，而無需登入的使用者。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | 委託 | 讓應用程式可以查看和更新您可存取的資料，即使使用者目前並未使用此應用程式也是一樣。  | Bot 通知 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | 委託 | 允許使用者利用其工作或學校帳戶登入應用程式，並讓應用程式可以查看基本的使用者設定檔資訊。 | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| profile | 委託 | 讓應用程式可以查看您的使用者基本設定檔 (名稱、圖片、使用者名稱)  | 不適用 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 歡迎訊息、核准和證明處理常式通知 | 我們確實會儲存識別碼的顯示名稱  | 我們的工具可讓使用者建立不同服務專案的要求，並儲存申請者的顯示名稱。 要求會跟隨核准工作流程，而且我們需要核准者顯示名稱，才能在要求詳細資料中顯示。 此外，在小組認證程式的成員中，我們會列出成員的顯示名稱。 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>EndUser 和組織的完整名稱。 保留和移除原則可以在 [ https://enterprizid.com/privacy-policy &quot; 個人資料保留] &quot; 區段中找到。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們已于 Azure 中啟用 PMA) 的特殊許可權存取 (管理，且具有連線至資源之許可權的身分識別，可使用2FA 提高安全性。 我們使用 Azure 做為雲端合作夥伴提供者，並對 Azure 的使用條款進行規定

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

EnterprizID Inc. 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 否 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
