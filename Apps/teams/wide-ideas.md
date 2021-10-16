---
title: 廣泛創意的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 在 CSA 星型登錄中，所有可用的安全性和符合性資訊都是廣泛的創意、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 075136dcf0c7e03d3f70461490f1b8c181478c43
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414369"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月27日</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

以廣泛的觀點提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Wide Ideas |
| ID | WA200000819 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Wide Ideas |
| 合作夥伴網站的 URL | [https://getwideideas.com](https://getwideideas.com) |
| 隱私權原則的 URL | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| 使用條款的 URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊的整體創意是關於此應用程式如何收集和儲存組織資料，以及您的組織將會透過應用程式收集的資料所提供的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 通道。建立 | 委託 | 在團隊中建立通道。  | 我們會儲存所建立之挑戰的通道識別碼。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Directory.Read.All | 委託 | 我們使用此專案列出客戶目錄中的使用者  | 不適用 | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Group.Read.All | 委託 | 我們使用此來從 Microsoft Teams 讀取及同步處理團隊。 | 我們會儲存小組和團隊成員的群組識別碼。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsAppInstallation.ReadWriteForTeam | 委託 | 這是用來自動在 Teams 中安裝應用程式  | 我們儲存安裝應用程式的團隊相關資訊 | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsTab。建立 | 委託 | 我們使用這項功能，在廣泛的創意所建立的頻道中，自動建立應用程式 (挑戰/搜尋創意) 索引標籤。 | 不適用 | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| User.Read | 委託 | 用於透過 SSO 驗證使用者，以及同步處理使用者資料 | 我們會儲存名稱、電子郵件和使用者識別碼。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Mailjet 電子郵件通知使用的電子郵件。 | email address | 若要能夠傳送電子郵件通知的活動  |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 若要在後端建立使用者，並授與存取連結至小組之內容的許可權。 | 儲存： Name-To 顯示使用者的名稱，電子郵件地址-識別使用者 | 為了管理我們後端內容的許可權 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們的記錄中存放名稱、電子郵件和 IP 號碼。 如果使用者想要刪除任何資料，組織可以將要求傳送給我們。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料儲存：所有客戶資料都儲存在 Microsoft Azure 服務中。 透過 Azure AD，使用者必須是2因數 authenticized。 已就地 (RBAC) 角色的存取權。 所有對 Microsoft Azure 的存取都是透過加密連線嚴格進行的。 所有資料在靜止時會加密。 所有服務受到 Azure 安全性中心最佳 practise 的保護。 

根據最低許可權的原則，我們也會有適當的存取原則。 


#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊的整體創意是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | MFA |
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

