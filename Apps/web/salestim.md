---
title: SalesTim 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SalesTim 的所有可用安全性與合規性資訊、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9fce7871fc306b19170cddb2d1524ef7a82a01f4
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2022
ms.locfileid: "65222434"
---
# <a name="application-information-for-salestim-by-salestim"></a>SalesTim by SalesTim 的應用程式資訊

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員更新日期：2021 年 6 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

SalesTim 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SalesTim |
| ID | salestim.salestim |
| 合作夥伴公司名稱 | SalesTim |
| 合作夥伴網站的 URL | [https://salestim.com](https://salestim.com) |
| 隱私權原則的 URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 使用規定 URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

SalesTim 已提供此資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>| **權限**  | **委派/應用程式)  (許可權類型** | **是否收集資料？收集它的理由為何？** | **是否儲存資料？儲存它的理由為何？** | **Azure AD應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 委託 | 不 | 允許應用程式在公司應用程式目錄中安裝及更新自己的套件。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | 委託 | 我們&#8217;只儲存某些使用者識別碼，而不是設定檔資料。 | 允許使用者在應用程式的不同位置選取其他使用者，例如在工作流程中選取核准者。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | 委託 | 我們&#8217;只重新儲存群組/小組識別碼，&#8217;不會儲存任何群組/小組內容。 | 允許應用程式建立群組，並代表登入的使用者讀取所有群組屬性和成員資格。 此外，也可讓群組擁有者管理其群組，並允許群組成員更新群組內容。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | 委託 | 我們&#8217;重新儲存此動作的中繼資料，例如通知日期、僅限) 的收件者 (識別碼、要求識別碼。 | 允許應用程式在核准工作流程期間傳送通知電子郵件。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | 委託 | 我們使用一些 Azure 服務來儲存資料，特別是 Azure 和 Cosmos DB 上的 Redis | 在小組布建程式期間，可讓應用程式管理與小組相關聯)  (檔案和資料夾的磁片磁碟機。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | 委託 | 我們&#8217;只儲存某些使用者識別碼，而不是設定檔資料。 | 可讓應用程式讀取任何使用者的一組完整配置檔案屬性、報表及管理員。 它特別在目標物件程式期間使用，以根據目前的使用者設定檔篩選某些內容。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | 委託 | 否 | 允許應用程式以使用者身分執行一些背景作業和動作。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>| **所有非Microsoft 服務 OII 都會傳輸至** |  **哪些 OII 會傳輸？** | **傳輸 OII 的理由為何？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 我們使用 Intercom 作為主要支援應用程式。 Intercom 可能包含一些基本的使用者設定檔資訊，如下所述： https://developers.salestim.com/platform/datamanagement.html#support-data | 公司名稱 | 我們使用GitHub API 從生產環境自動產生問題。 我們也會將一些技術記錄儲存在GitHub (中，如下所述： https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) 。 這些問題和記錄可能包含一些基本的使用者設定檔資訊。 每隔 15 天就會自動刪除這些問題和記錄。 |



#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>這裡會說明收集的所有資料： https://developers.salestim.com/platform/datamanagement.html#application-data 如所述，記錄會暫時儲存 15 天，然後自動刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>大部分的資料都會儲存在 Azure Cosmos DB 中。
生產環境的存取許可權制為兩個人，而這些系統管理員帳戶會強制執行 MFA。
這些帳戶是專用帳戶，與我們的公司帳戶不同。
待用資料會在我們所使用的所有 Azure 服務中加密。
生產環境的部署會透過我們GitHub環境中的專用受保護分支自動化，其中只有兩個人可以核准變更。

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

SalesTim 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳做法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已檢閱並符合Microsoft 身分識別平臺整合檢查清單中所述的所有適用最佳做法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | MFA、位置條件 |
| 您的應用程式是否要求案例的最低許可權許可權？ | 是 |
| 您應用程式的靜態註冊許可權是否能正確反映應用程式以動態和累加方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租使用者？ | 是 |
| 您的應用程式是否有機密用戶端？ | 是 |
| 您是否擁有為應用程式註冊的所有重新導向統一資源識別項 (URI) ？ | 是 |
| 針對您的應用程式，您要避免使用什麼？ | ,<br/>- OAuth2 隱含Flow，除非 SPA 需要<br/> |
| 您的應用程式是否公開任何 Web API？ | 是 |
| 只有在用戶端應用程式收到適當的同意時，您的許可權模型才允許呼叫成功嗎？ | 是 |
| 您的應用程式是否使用預覽 API？ | 否 |
| 您的應用程式是否使用已被取代的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
