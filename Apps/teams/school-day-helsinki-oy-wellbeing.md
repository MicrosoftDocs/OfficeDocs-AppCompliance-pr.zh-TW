---
title: School day Wellbeing （按學年）赫爾辛基 Oy 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用於 School Day Wellbeing 的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ff37e7b9bb25090f65793d99c5ff994fc6af6d65
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60440726"
---
# <a name="school-day-wellbeing"></a>School Day Wellbeing

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2021年10月12日</p>

* <a href="https://teams.microsoft.com/l/app/7caaa66b-34b0-4c15-a65d-dba6edf0c8fd" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001430" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

School Day 赫爾辛基 Oy 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | School Day Wellbeing |
| ID | WA200001430 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | School Day Helsinki Oy |
| 合作夥伴網站的 URL | [https://www.schoolday.com](https://www.schoolday.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.schoolday.com/en/resources/faq](https://www.schoolday.com/en/resources/faq) |
| 隱私權原則的 URL | [https://www.schoolday.com/privacy](https://www.schoolday.com/privacy) |
| 使用條款的 URL | [https://www.schoolday.com/eula](https://www.schoolday.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

這種資訊已由 School Day 赫爾辛基 Oy 提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember Read。 All | 委託 | 組名和群組成員資格。 教師的使用者可以從他們的群組中將學生新增至 School Day。 | 群組名稱，群組成員。 您可以根據 O365 群組，將 School 命名為一的群組。 群組成員會以學生的身分新增至此類別。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| Team.ReadBasic.All | 委託 | 當教師使用者想要從其小組和群組中新增學生時，會使用小組名稱。 | 小組名稱不會儲存在 School Day 中。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.Read | 委託 | 使用者電子郵件、名稱和識別碼都是用於使用者管理和驗證。 | 會儲存使用者電子郵件、名稱和權杖，以供使用者管理和驗證之用。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.ReadBasic.All | 委託 | 要用於使用者虛擬人偶的使用者設定檔圖片。 | 不儲存使用者設定檔圖片。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| 電子郵件 | 委託 | 會收集使用者電子郵件以進行帳戶驗證。 | 會儲存使用者電子郵件，以建立帳戶和/或驗證目的。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| offline_access | 委託 | 驗證-存取權杖重新整理。 更順暢的使用者體驗。 | 用於驗證目的的存取權杖。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| openid | 委託 | OpenID 登入之使用者的唯一識別碼。  | 出於驗證的目的，會儲存使用者的唯一識別碼。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| 設定檔 | 委託 | 使用者管理和驗證目的的慣用使用者名稱和物件識別碼。 | 用於使用者管理和驗證目的的物件識別碼。 | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| 沈浸式閱讀程式 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>使用者帳戶，群組使用者屬於，wellbeing 問題答案資料。 一旦刪除帳戶後，就會在90天內移除資料。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>組織管理員可以透過 School Day 系統管理員工具控制 (CRUD) 的資料。 

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由 School Day 赫爾辛基 Oy 提供，此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
