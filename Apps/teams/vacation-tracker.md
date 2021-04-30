---
title: 度假追蹤器的假期追蹤應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
description: 所有可用的假期追蹤器安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 33a6ecf06db07878a62a9b9a9edf4360f2507ee7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093565"
---
# <a name="vacation-tracker"></a>假期追蹤程式

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新：2021年2月5日</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由假期追蹤器提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 假期追蹤程式 |
| ID | WA200002167 |
| 功能 | Bot，索引標籤 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 假期追蹤程式 |
| 合作夥伴網站的 URL | [https://vacationtracker.io](https://vacationtracker.io) |
| Teams 應用程式資訊頁面的 URL | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| 隱私權原則的 URL | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| 使用條款的 URL | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

這種資訊已由假期追蹤器提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | 委託 | 當使用者設定每週或每日通知時，我們會閱讀公用通道 IDs 和名稱。 | 使用者可以選擇要接收假期追蹤器每日或每週通知的頻道。 當使用者選擇其偏好的通道時，我們會儲存通道識別碼。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| ReadBasic | 委託 | 我們會列出使用者在登入期間加入的 Microsoft Teams 小組，以允許使用者選取他們想要註冊度假追蹤的小組。 他們也可以註冊其整個組織。 | 只有在使用者以單一小組身分註冊假期追蹤器， (不是整個組織) 時，才會儲存該小組的 Microsoft Teams 小組識別碼。 我們使用 team IDs，在假期追蹤器中，將已登入的使用者與現有的帳戶連線。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | 委託 | 我們會收集基本使用者的資訊，包括其名稱、識別碼及租使用者識別碼。 我們使用此資料，將已登入的使用者連線到度假追蹤器中的組織。 | 我們儲存使用者的名稱、識別碼及租使用者識別碼。 我們使用此資料，將已登入的使用者連線到度假追蹤器中的組織。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | 委託 | 我們的使用者可以從其 Microsoft 365 組織或 Microsoft Teams 小組匯入所有使用者。 我們使用此許可權，只匯入所選 Microsoft Teams 小組或組織的授權使用者。 | 我們會儲存匯入之使用者的基本資訊，包括其名稱、電子郵件地址和使用者識別碼。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | 委託 | 我們可讓使用者從組織或其 Microsoft Teams 小組匯入其他使用者。 我們使用此許可權在匯入快顯功能表中列出可用的使用者及其電子郵件地址。 | 當使用者選取其同事匯入假期追蹤追蹤時，我們會儲存這些匯入使用者的基本資訊，包括其名稱、電子郵件地址和使用者識別碼。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| 電子郵件 | 委託 | 當使用者使用 Microsoft AAD 登入時，我們會將其電子郵件地址儲存為唯一的識別碼。 | 我們會將使用者的電子郵件儲存為唯一的識別碼。 我們不會使用這封電子郵件進行通訊，使用者可以輸入他們的公司電子郵件地址，用來在註冊期間進行通訊。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | 委託 | 我們不會使用此許可權收集任何資料。 它是用來維護我們存取權的資料存取權。 | 我們不會使用此許可權儲存任何資料。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | 委託 | 我們使用此許可權登入或註冊使用者至休假追蹤器。 我們不會使用此許可權收集任何特定的資料。 | 我們使用此許可權登入或註冊使用者至休假追蹤器。 我們不會使用此許可權儲存任何特定的資料。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| profile | 委託 | 我們會收集基本使用者的資訊，包括其名稱、識別碼及租使用者識別碼。 我們使用此資料，將已登入的使用者連線到度假追蹤器中的組織。 | 我們儲存使用者的名稱、識別碼及租使用者識別碼。 我們使用此資料，將已登入的使用者連線到度假追蹤器中的組織。 | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe、AWS、清晰、Customer.io、Segment、波幅、Google 標記管理員 |  (使用者輸入的公司名稱)  | 當使用者進行註冊時，他們會輸入公司名稱，並使用此名稱做為產品內部的組織名稱。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot 可以查看與 bot 進行通訊之使用者的基本資訊。 不過，我們不會儲存或使用此資訊。 我們只會使用使用者的識別碼、交談識別碼及傳送給我們的 bot 的郵件。 | 我們會將使用者的電子郵件地址、使用者的名稱 (于 Microsoft aad) 和使用者的設定檔相片 (中所定義的 Microsoft AAD)  | 我們使用電子郵件地址做為使用者的唯一識別碼，以及使用者的名稱和設定檔相片，以允許來自相同公司的系統管理員和核准者辨識其在我們的儀表板中的員工。  |



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>公司名稱，它會根據我們為這類資料類型的標準一年保留原則，保留並移除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>若要開始，我們收集使用者所需的最少資料量。 然後，我們會與我們的合作夥伴分享最小的可能性，最後是我們的資料保留原則，以便在一年內（如果適用）中移除所有資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由假期追蹤器提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，
<br />
- OAuth2 隱含 Flow （除非 SPA 是必要的）
<br />
- 資源擁有者密碼認證 (ROPC) 流程 | |您的應用程式是否公開任何 web APIs？ |是 | |如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ |是 | |您的應用程式是否使用預覽 APIs？ |無 | |您的應用程式使用的 APIs 是否已遭取代？ |否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
