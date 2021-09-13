---
title: 以平方方式連線的版塊應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 07/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 在 CSA 星型登錄中，所有適用于主機板連線的安全性和合規性資訊資訊，以及其資料處理原則、Microsoft Cloud App Security 應用程式目錄資訊，以及安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c04b8be94b4d9a6367c8baa2b3370d82c2bdff5c
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279705"
---
# <a name="board-connect"></a>版面連結

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新：2021年7月5日</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

將平方的資訊提供給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 版面連結 |
| ID | WA200001955 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 使用方形 |
| 合作夥伴網站的 URL | [https://engagesq.com](https://engagesq.com) |
| Teams 應用程式資訊頁面的 URL | [https://boardconnect.app](https://boardconnect.app) |
| 隱私權原則的 URL | [https://boardconnect.app/privacy/](https://boardconnect.app/privacy/) |
| 使用條款的 URL | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊的提供方式是使用平方，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | 若要讓應用程式更新使用者行事曆，以反映透過應用程式提交的其董事會會議出席回應回應。 | Azure 資料表存放區中不會儲存任何資料 | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| Group.ReadWrite.All | 委託 | 若要允許此應用程式建立、更新和刪除群組行事曆事件。 | 我們會儲存群組的識別碼，以及租使用者識別碼，以供您在授權的觀點內加以儲存和使用，讓我們能夠驗證該組織是否授權使用連線。 我們也會使用此方法，追蹤在租使用者中有多少應用程式已與我們的授權模式一起內嵌。 | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| 管理的網站。所有 | 委託 | 若要允許此應用程式建立清單和文件庫，管理清單專案並管理小組網站集合上的檔。 | 無 | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.Read | 委託 | 允許使用者登入應用程式，並讓應用程式讀取目前登入使用者的設定檔。 | 未將此端點中的資料儲存在 azure 資料表存放區中 | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| User.ReadBasic.All | 委託 | 若要讓應用程式代表登入的使用者讀取其他使用者的基本配置檔案屬性集合，以便在應用程式中顯示。 這包括顯示名稱、名字和姓氏、電子郵件地址及照片。 | 無，資料不會儲存在 azure 資料表存放區中 | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |
>| offline_access | 委託 | 若要讓應用程式取得重新整理權杖，可在目前的更新權杖到期時，用來取得新的訪問權杖。 | 無，資料不會儲存在 azure 資料表存放區中 | [4a6873f6-8360-4023-bd6f-2923d1eb2e94](https://docs.microsoft.com/microsoft-365-app-certification/azure/4a6873f6-8360-4023-bd6f-2923d1eb2e94) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>2FA 適用于所有系統管理員，只有兩部接洽使用者可以存取

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊的提供方式是讓平方和此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 否 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/> |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
