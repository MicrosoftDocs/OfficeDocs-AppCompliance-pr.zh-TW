---
title: LiveTiles 的應用程式資訊
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊資訊可取得，其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c58462500079df7f7b8b2736eec9289443df4a4c
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753742"
---
# <a name="reach"></a>達到

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2021年3月22日</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 LiveTiles 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 達到 |
| ID | WA200002045 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | LiveTiles |
| 合作夥伴網站的 URL | [https://livetilesglobal.com](https://livetilesglobal.com) |
| Teams 應用程式資訊頁面的 URL | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| 隱私權原則的 URL | [https://livetilesglobal.com/privacy-policy/](https://livetilesglobal.com/privacy-policy/) |
| 使用條款的 URL | [https://livetilesglobal.com/eula/](https://livetilesglobal.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 LiveTiles 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **權限**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | 應用程式 | 無 | 無 | [a7c1920d-3ac0-42db-9757-078a2b321fd8 ](../azure/a7c1920d-3ac0-42db-9757-078a2b321fd8.md ) |
>| User.Read | 委託 | 使用者 DisplayName、使用者電子郵件地址、UPN。 必要允許使用者登入 app 並取得登錄使用者的基本資訊，例如顯示名稱。 電子郵件地址是用來傳送電子郵件通知。  | 使用者 DisplayName、使用者電子郵件地址、UPN。 必要允許使用者登入 app 並取得登錄使用者的基本資訊，例如顯示名稱。 電子郵件地址是用來傳送電子郵件通知。  | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| User.ReadBasic.All | 委託 | 使用者 DisplayName，使用者電子郵件地址，UPN，使用者部門，使用者職稱，使用者行動電話號碼，使用者商務電話號碼，使用者 Office 位置。 必要以允許使用者在應用程式 (中搜尋其他使用者) ，並查看其他使用者的基本設定檔和連絡人資訊。  | 無 | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| Directory.Read.All | 應用程式 | 群組成員資格，目錄中的 AD 群組。 使用者的群組成員資格儲存在快取中，以將對 Microsoft Graph API 的呼叫降至最低。 必要以允許使用者搜尋 Active Directory 群組。 此外，此許可權是必要的應用程式，以便在後端的 web 工作中解析使用者的 AD 群組成員資格。 | 使用者的群組成員資格。 使用者的群組成員資格儲存在快取中，以將對 Microsoft Graph API 的呼叫降至最低。 必要以允許使用者搜尋 Active Directory 群組。 此外，此許可權是必要的應用程式，以便在後端的 web 工作中解析使用者的 AD 群組成員資格。  | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |
>| User.Read.All | 應用程式 | 從使用者設定檔中檢索的資料，取決於應用程式中指定的物件目標功能設定。 需要讓應用程式在未登入的使用者中讀取使用者設定檔。 應用程式中的資訊設定目標功能需要讀取設定檔資料，因此會根據特定的配置檔案屬性值，向特定使用者顯示資訊。  | 無 | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| SendGrid, OneSignal | 電子郵件地址、顯示名稱 | 透過電子郵件和行動推播通知傳送通知給使用者 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>電子郵件地址（UPN）。 超過60天保留（已移除）

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>系統管理員可以聯繫支援人員以取得任何查詢

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security 資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

LiveTiles 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 否 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 多重要素驗證，限制使用者位置和 IP 範圍 |
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
