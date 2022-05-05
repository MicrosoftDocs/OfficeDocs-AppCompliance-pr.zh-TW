---
title: Office2SharePoint 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Office2SharePoint 的所有可用安全性與合規性資訊、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9d063ac1a7cee57ef2bee185ed43a2c3385c06c2
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225002"
---
# <a name="application-information-for-office2sharepoint"></a>Office2SharePoint 的應用程式資訊

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員更新日期：2021 年 6 月 22 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.o2s" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

iGlobe 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Office2SharePoint |
| ID | 17859280.o2s |
| 合作夥伴公司名稱 | iGlobe |
| 合作夥伴網站的 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 隱私權原則的 URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 使用規定 URL | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

iGlobe 已提供此資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>| **權限**  | **委派/應用程式)  (許可權類型** | **是否收集資料？收集它的理由為何？** | **是否儲存資料？儲存它的理由為何？** | **Azure AD應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 允許應用程式具有與登入使用者相同的目錄資訊存取權。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 檢查許可權，並取得網站和清單。 建立資料夾、取得檔案並儲存檔案。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 檢查許可權，並取得網站和清單。 建立資料夾、取得檔案並儲存檔案。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 取得使用者群組網站。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 若要存取選取的郵件，並取得附件。 從郵件或從SharePoint或群組網站新增到郵件。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 允許應用程式代表登入的使用者建立或刪除所有網站集合中的文件庫和清單。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 若要讓使用者SharePoint網站。 從選取的郵件取得檔案並儲存附件。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | 委託 | 應用程式資料庫中不會儲存任何資料。 | 若要取得SharePoint清單、程式庫和檔案。 若要將檔案儲存至清單SharePoint。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | 委託 | 應用程式資料庫中不會儲存任何資料。 | 若要讓使用者SharePoint網站、OneDrive和群組網站。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 進行資料存取

建置在 Microsoft 365 上的應用程式和增益集可能會使用 Microsoft Graph 以外的其他 Microsoft API 來收集或處理組織可識別的資訊， (OII) 。 列出此應用程式使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集的 OII 為何？** | **收集 OII 的理由？** | **是否儲存 OII？** | **儲存 OII 的理由為何？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS。AccessAsUser.All | 否 |  |  |  |  |
>| Exchange - Mail.ReadWrite | 否 |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | 否 |  |  |  |  |
>| SharePoint- AllSites.Manage | 否 |  |  |  |  |
>| SharePoint - AllSites.Write | 否 |  |  |  |  |
>| SharePoint - MyFiles.Write | 否 |  |  |  |  |
>| SharePoint - User.Read.All | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>不使用非Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>iGlobe 會收集資料以有效地運作，並提供我們產品和服務的最佳體驗。 針對授權：收集來管理貴組織&#8217;授權帳戶的資料，例如當您部署免費增益集、建立試用訂閱或購買訂用帳戶時。 收集下列資訊。 財務用途：公司名稱和位址已訂閱的使用者：使用者名稱和電子郵件

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>所有應用程式資料都位於客戶自己的租使用者上，並由租使用者系統管理員控制，作為Office 365中的所有其他服務。 增益集中不會儲存任何應用程式資料。 新式增益集會在沙箱化瀏覽器中執行，&#8220;跨進程&#8221;。 增益集只能存取使用者正在使用的資料。 它會使用Microsoft 服務與使用者資料互動。

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

iGlobe 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳做法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已檢閱並符合Microsoft 身分識別平臺整合檢查清單中所述的所有適用最佳做法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 安全性預設值和任何其他常見原則，例如封鎖舊版驗證* 需要系統管理員的 MFA* 需要 Azure 管理的 MFA* 需要所有使用者的 MFA* |
| 您的應用程式是否要求案例的最低許可權許可權？ | 是 |
| 您應用程式的靜態註冊許可權是否能正確反映應用程式以動態和累加方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租使用者？ | 是 |
| 您的應用程式是否有機密用戶端？ | 是 |
| 您是否擁有為應用程式註冊的所有重新導向統一資源識別項 (URI) ？ | 是 |
| 您的應用程式是否公開任何 Web API？ | 否 |
| 您的應用程式是否使用預覽 API？ | 否 |
| 您的應用程式是否使用已被取代的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
