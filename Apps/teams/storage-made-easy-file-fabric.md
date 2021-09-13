---
title: 儲存體所做的檔案架構應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/30/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 在 CSA 星型登錄中，檔案 Fabric 的所有可用安全性和符合性資訊資訊，其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3070723eecc0e7dda11aff31da6b20a785f558b5
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278797"
---
# <a name="file-fabric"></a>File Fabric

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月30日</p>

* <a href="https://teams.microsoft.com/l/app/bd063a87-1e4d-42cf-baea-8cab71839e35" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003017" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

儲存體所提供的資訊，便於 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | File Fabric |
| ID | WA200003017 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Storage Made Easy |
| 合作夥伴網站的 URL | [https://storagemadeeasy.com](https://storagemadeeasy.com) |
| Teams 應用程式資訊頁面的 URL | [https://docs.storagemadeeasy.com/microsoft-teams](https://docs.storagemadeeasy.com/microsoft-teams) |
| 隱私權原則的 URL | [https://www.storagemadeeasy.com/privacy](https://www.storagemadeeasy.com/privacy) |
| 使用條款的 URL | [https://www.storagemadeeasy.com/terms](https://www.storagemadeeasy.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊的提供方式儲存體非常簡單，讓此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite | 應用程式 | 使用者透過應用程式下載、上傳或編輯指定的檔案時，可讀取或寫入檔案資料。 | 未儲存檔資料。 | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |
>| Sites.ReadWrite.All | 應用程式 | 針對所有使用者&#8217;的檔案和資料夾收集的中繼資料，提供所有檔服務的同盟查看。 | 緩存的中繼資料可提供更快的流覽和搜尋。 | [0752d800-857f-49bd-87eb-e60985516c67](https://docs.microsoft.com/microsoft-365-app-certification/azure/0752d800-857f-49bd-87eb-e60985516c67) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Azure Blob 儲存體 | 是 | 物件中繼資料和資料 | 針對所有使用者&#8217;的檔案和資料夾收集的中繼資料，提供所有檔服務的同盟查看。 當使用者透過應用程式下載、上傳或編輯指定的物件時，可讀取或寫入的物件。 | 物件中繼資料儲存 | 緩存的中繼資料可提供更快的流覽和搜尋。 |
>| Office 網頁版 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 使用者可驗證並聯機至所控制的任何儲存服務。 | 會針對同盟流覽及搜尋快取檔案和物件中繼資料。 當讀取和更新特定檔案或物件時，會傳輸資料。 | 中繼資料提供儲存體的同盟查看。 資料傳輸允許 secure 通用存取。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>每個 GDPR 的資料處理協定

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

此資訊的提供方式儲存體非常簡單，讓此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
