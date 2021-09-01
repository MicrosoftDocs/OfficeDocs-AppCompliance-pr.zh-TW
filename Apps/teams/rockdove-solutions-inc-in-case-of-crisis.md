---
title: RockDove 解決方案，Inc. 針對危機案例的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 08/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊，在發生危機情況時，其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4671d37d77d16004c171887f101ade7506598614
ms.sourcegitcommit: 90e6c1e10d55dc337c0884b63782cc14cf71b3c8
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/31/2021
ms.locfileid: "58836201"
---
# <a name="in-case-of-crisis"></a>在發生危機時

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月27日</p>

* <a href="https://teams.microsoft.com/l/app/cf430644-447e-4572-8467-3892596d05c7" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003194" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

RockDove 解決方案所提供的資訊（Inc.）至 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 在發生危機時 |
| ID | WA200003194 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | RockDove 解決方案，Inc.。 |
| 合作夥伴網站的 URL | [https://www.rockdovesolutions.com](https://www.rockdovesolutions.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.rockdovesolutions.com/in-case-of-crisis/in-case...](https://www.rockdovesolutions.com/in-case-of-crisis/in-case-of-crisis-platform) |
| 隱私權原則的 URL | [https://www.rockdovesolutions.com/privacy-policy](https://www.rockdovesolutions.com/privacy-policy) |
| 使用條款的 URL | [https://www.rockdovesolutions.com/terms-of-use](https://www.rockdovesolutions.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

RockDove 解決方案（Inc.）已提供此資訊。關於此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | 這會授予使用者行事曆的完整存取權。 我們的應用程式會顯示描述、會議連結，以及開始和結束日期。 我們的應用程式也可讓使用者在 outlook 行事曆上建立事件 | 以後的事件識別碼可以儲存在資料庫中 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| ReadBasic | 委託 | 提供使用者頻道的存取權。  通道的使用者清單用來選取要將檔案上傳至的頻道 | N/A | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite | 委託 | N/A | N/A | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Files.ReadWrite.All | 委託 | 我們允許使用者將檔案從問題管理上傳至 Teams | N/A | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Sites.ReadWrite.All | 委託 | 這是上傳專用通道的必要條件 | N/A | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| Team.ReadBasic.All | 委託 | 需要有小組清單，才能取得使用者所屬的通道清單。 這可讓我們查看可用的上傳通道清單。 | N/A | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| 電子郵件 | 委託 | 在驗證之後，必須取得使用者的電子郵件，才能與資料庫中的電子郵件進行比較。 如果使用者在我們的系統中沒有帳戶，我們會建立一個帳戶。 | 我們會儲存電子郵件地址，並為其建立應用程式帳戶。 | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| offline_access | 委託 | 這可讓我們重新整理圖形存取權杖 | N/A | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |
>| openid | 委託 | 透過 openid 驗證所需的許可權 | N/A | [6b4a2fee-5642-41a7-b452-d555fac690b0](https://docs.microsoft.com/microsoft-365-app-certification/azure/6b4a2fee-5642-41a7-b452-d555fac690b0) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS | 組織使用者的電子郵件地址以進行驗證和通訊 | 電子郵件地址會做為服務中的使用者名，我們會使用 AWS 做為 SMTP 應用程式的電子郵件伺服器。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>電子郵件地址會做為我們系統內的主要使用者名稱。  保留用戶端的使用者資訊時，用戶端是最新的，並會在用戶端停止更新其服務合約後移除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們為我們的客戶提供合作夥伴管理入口網站，以管理在我們服務內共用的 (insert、replace、delete、audit、封存公司資訊。

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

RockDove 解決方案（Inc.）已提供此資訊。關於此應用程式如何處理驗證、授權、application registration 最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/> |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
