---
title: Neelix 的應用程式資訊（依 Neelix.IO）
ms.author: elmalova
author: elenamalova
ms.date: 07/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Neelix 的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 74f41c23436f1bfc47db6fea7dfca2e8b12731bb
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404320"
---
# <a name="neelixteam"></a>Neelix 團隊

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年7月10日</p>

* <a href="https://teams.microsoft.com/l/app/bed170ee-dbd7-4efa-b48e-b0937ded1689" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003047" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Neelix.IO 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Neelix 團隊 |
| ID | WA200003047 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Neelix.IO |
| 合作夥伴網站的 URL | [https://www.neelix.team](https://www.neelix.team) |
| Teams 應用程式資訊頁面的 URL | [https://www.neelix.team](https://www.neelix.team) |
| 隱私權原則的 URL | [https://www.neelix.team/data-security-policy](https://www.neelix.team/data-security-policy) |
| 使用條款的 URL | [https://www.neelix.io/terms-of-use-en](https://www.neelix.io/terms-of-use-en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Neelix.IO 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **權限**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadBasic | 委託 | 應用程式會使用通道識別碼及名稱，為使用者提供從 MS Treams 傳送意見反應時管理其預設首選項的方便性。 | 會儲存通道識別碼及名稱，以用於使用者方便性的預設值管理 | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| Team.ReadBasic.All | 委託 | app 使用小組識別碼及名稱，為使用者提供從 MS Treams 傳送意見反應時管理其預設首選項的方便性。 | 會儲存小組識別碼和名稱。 這種資料可讓我們設定便利的預設值，以允許更快速的意見反應表單完成。 | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| 電子郵件 | 委託 | 電子郵件會在 Neelix 內做為使用者註冊的一部分使用。 初次註冊後，電子郵件會用於通知。  | 電子郵件會儲存在使用者設定檔中。 電子郵件也用來檢查使用者不會嘗試透過其他的 oauth 通道使用相同的電子郵件。 | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| offline_access | 委託 | 用於取得重新整理權杖 |  會儲存重新整理權杖，以便取得新的訪問權杖 | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| 設定檔 | 委託 | 使用 Neelix 註冊時，使用者名稱是用來建立使用者帳戶。  | 使用者名稱是儲存在使用者帳戶中。 這是使用者在其小組雜誌中的其他小組成員 recognised 時所需的。 使用者可以更新儲存在 Neelix 中的名稱。 | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| User.Read | 委託 | Bot 應用程式會使用使用者。已讀取，以便能夠傳送資訊使用者，讓 Neelix core platform 能夠識別使用者 | 資訊未儲存 | [bed170ee-dbd7-4efa-b48e-b0937ded1689](https://docs.microsoft.com/microsoft-365-app-certification/azure/bed170ee-dbd7-4efa-b48e-b0937ded1689) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft 身分識別平臺 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 租使用者識別碼會傳送至在 Google 雲端平臺中執行的後端服務 | 租使用者識別碼 | 租使用者識別碼的目的是用於在 oauth 期間進行使用者識別 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 應用程式使用使用者識別碼，以根據註冊至 Neelix 平臺的資訊來識別使用者 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>租使用者識別碼會記錄在系統記錄檔中。 記錄保留原則為30天。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>最終使用者原則、GDPR 規範程式、帳戶取消和資料 Acrichival 程式

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

Neelix.IO 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

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
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
