---
title: 內容選擇器的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 內容選擇器的所有可用安全性與合規性資訊、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3c477a04e970c4290ee3552b3d7730de24a52a96
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225001"
---
# <a name="application-information-for-content-chooser-by-officeatwork"></a>依 officeatwork 之內容選擇器的應用程式資訊

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員更新日期：2021 年 6 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.content-chooser" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Officeatwork 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 內容選擇器 |
| ID | officeatwork-ag.content-chooser |
| 合作夥伴公司名稱 | officeatwork |
| 合作夥伴網站的 URL | [https://www.officeatwork.com](https://www.officeatwork.com) |
| 隱私權原則的 URL | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| 使用規定 URL | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Officeatwork 已提供此資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>| **權限**  | **委派/應用程式)  (許可權類型** | **是否收集資料？收集它的理由為何？** | **是否儲存資料？儲存它的理由為何？** | **Azure AD應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 委託 | 未儲存任何資料。 | 我的最愛：能夠讀取和寫入資料給使用者OneDrive。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Files.ReadWrite.All | 委託 | 未儲存任何資料。 | OneDrive：能夠讀取和寫入資料給使用者OneDrive。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Group.ReadWrite.All | 委託 | 未儲存任何資料。 | Teams：能夠讀取和寫入資料至群組。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| GroupMember.Read.All | 委託 | 未儲存任何資料。 | SharePoint Online - 安全性群組支援：允許應用程式列出群組、讀取基本群組屬性，以及讀取已登入使用者可存取之所有群組的成員資格 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| Sites.Read.All | 委託 | 未儲存任何資料。 | SharePoint Online：啟用從 SharePoint Online 讀取資料的功能。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| User.Read | 委託 | 未儲存任何資料。 | 按一下：讓 officeatwork 應用程式讀取使用者的基本屬性。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| User.Read.All | 委託 | 未儲存任何資料。 | Teams：找出使用者所屬的群組。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| offline_access | 委託 | 未儲存任何資料。 | 單一登入：若要透過重新整理權杖啟用自動登入，使用者必須在每次啟動 officeatwork 應用程式時手動登入。 此範圍僅適用于未啟用 SSO 的主應用程式。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| openid | 委託 | 未儲存任何資料。 | 登入：讓使用者使用其組織和/或 Microsoft 帳戶登入 officeatwork 應用程式。 | edb24f8f-38af-4b3e-9475-0da243678d5a |
>| 設定檔 | 委託 | 未儲存任何資料。 | 登入：在 officeatwork 應用程式中顯示已登入的使用者。 這有助於確保/確認使用者用來登入 officeatwork 應用程式的帳戶。 | edb24f8f-38af-4b3e-9475-0da243678d5a |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 進行資料存取

建置在 Microsoft 365 上的應用程式和增益集可能會使用 Microsoft Graph 以外的其他 Microsoft API 來收集或處理組織可識別的資訊， (OII) 。 列出此應用程式使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集的 OII 為何？** | **收集 OII 的理由？** | **是否儲存 OII？** | **儲存 OII 的理由為何？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint REST API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>不使用非Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>是，事件包含 oid 和 tenantId，並會傳送至 Azure AppInsights。 事件會在 90 天后自動刪除。 如果客戶想要刪除此資料，他們可以使用隱私權聲明中提供的連結來起始該資料的刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>應用程式設定資料 (功能旗標、組織顯示名稱、tenantId、系統管理員 oids 清單) 會儲存在 Azure Cosmos DB 實例中， (每個租使用者一個檔案) 。 資料庫檔案會加密，且只能存取選取的 officeatwork 工程師和支援人員。 客戶可以使用系統管理中心 Web 應用程式來存取及操作 officeatwork 應用程式設定資料。

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35751' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35751" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Officeatwork 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳做法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已檢閱並符合Microsoft 身分識別平臺整合檢查清單中所述的所有適用最佳做法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 安全性預設 |
| 您的應用程式是否要求案例的最低許可權許可權？ | 是 |
| 您應用程式的靜態註冊許可權是否能正確反映應用程式以動態和累加方式要求的許可權？ | 否 |
| 您的應用程式是否支援多租使用者？ | 是 |
| 您的應用程式是否有機密用戶端？ | 是 |
| 您是否擁有為應用程式註冊的所有重新導向統一資源識別項 (URI) ？ | 是 |
| 針對您的應用程式，您要避免使用什麼？ | - 萬用字元重新導向 URI，<br/>- OAuth2 隱含Flow，除非 SPA 需要<br/>- 資源擁有者密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 Web API？ | 否 |
| 您的應用程式是否使用預覽 API？ | 否 |
| 您的應用程式是否使用已被取代的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
