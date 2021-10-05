---
title: MyOKR by SOE 技術所用的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: myOKR 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 94d5b0056961f509423819a04160e87bb4b5e3e0
ms.sourcegitcommit: e339fa9776aae99797dbc1f0a28932e71b4eb823
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/05/2021
ms.locfileid: "60131727"
---
# <a name="myokr"></a>myOKR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月18日</p>

* <a href="https://teams.microsoft.com/l/app/c0b70874-2c95-4be7-a0cb-0d893e25a2a3" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003308" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

SOE 技術所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | myOKR |
| ID | WA200003308 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | SOE 技術 |
| 合作夥伴網站的 URL | [https://www.myokr.co](https://www.myokr.co) |
| Teams 應用程式資訊頁面的 URL | [https://www.myokr.co](https://www.myokr.co) |
| 隱私權原則的 URL | [https://www.myokr.co/privacy](https://www.myokr.co/privacy) |
| 使用條款的 URL | [https://www.myokr.co/terms](https://www.myokr.co/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊已透過 SOE 技術提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | 取得使用者行事曆的詳細資料，以在使用者行事曆中建立1:1 會議、更新或刪除 myOKR 平臺所建立，以及顯示閒置時間槽 | 在 myOKR 平臺中建立的會議，我們會在資料庫中儲存已建立的行事曆識別碼及加入 URL。 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read | 委託 | 我們使用使用者 azure 物件識別碼，讓使用者使用 Microsoft 驗證針對電子郵件登入 myOKR 應用程式 | 使用者電子郵件和 azure 主動物件識別碼 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read.All | 應用程式 | 以 myOKR 平臺同步使用者資訊，並根據不同的使用者削減（如位置、部門經理），將 myOKR 應用程式分析顯示為系統管理員 &amp; | 我們在 myOKR 系統中儲存使用者識別碼、名稱、電子郵件、部門、標題和管理員資訊 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| offline_access | 委託 | 使用者的 Azure active directory 識別碼 | 我們使用離線存取在使用者行事曆中建立週期性會議 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| openid | 委託 | 我們使用使用者 azure 物件識別碼，使用 Microsoft 驗證讓使用者登入 myOKR 應用程式 | 使用者 active azure id 是針對電子郵件儲存 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 使用者 Active Azure 目錄識別碼是根據使用者的電子郵件儲存，以由 bot 傳送主動型郵件。 | 電子郵件、名稱、管理員資訊、職稱、使用者 Azure Active Directory 識別碼  | MyOKR 應用程式會使用此資訊來建立使用者帳戶、允許管理員在 platfrom 上查看其 reportee 詳細資料、允許系統管理員根據部門、位置和主管來查看整體分析和報告 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>組織 SPOC 會在 intimation 中向我們寄出服務，並且在30天之後，將其資料刪除30天之後。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

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

此資訊是由 SOE 技術提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
