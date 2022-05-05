---
title: LMS365 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: LMS365、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊的所有可用安全性與合規性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224987"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>ELEARNINGFORCE International Aps 的 LMS365 應用程式資訊

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次由開發人員更新日期：2021 年 6 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

ELEARNINGFORCE International Aps 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | LMS365 |
| ID | elearningforce.lms365_spfx |
| 合作夥伴公司名稱 | ELEARNINGFORCE International Aps |
| 合作夥伴網站的 URL | [https://www.elearningforce.com](https://www.elearningforce.com) |
| 隱私權原則的 URL | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| 使用規定 URL | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

ELEARNINGFORCE 國際 Aps 已提供此資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>| **權限**  | **委派/應用程式)  (許可權類型** | **是否收集資料？收集它的理由為何？** | **是否儲存資料？儲存它的理由為何？** | **Azure AD應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | 應用程式 | 無 | 允許應用程式擴充 AD 群組成員，這是將使用者群組註冊至課程所需的成員。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | 委託 | 無 | 設定電子郵件帳戶以取得通知時，會動態要求許可權。 允許應用程式傳送通知電子郵件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | 應用程式 | 無 | 允許應用程式在租使用者布建期間取得SharePoint網域。 網域用於 URL 建構。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | 委託 | 無 | 允許應用程式代表目前登入的使用者邀請外部使用者 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | 委託 | 無 | 登入和讀取使用者設定檔。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 委託 | 無 | 允許應用程式讀取目前登入使用者的完整設定檔。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 應用程式 | 允許應用程式讀取完整的使用者設定檔。 &#8217;需要讀取使用者&#8217;管理員來建置階層報告。 | 下列個人資料會儲存在專用資料庫中，供個別客戶用於應用程式內的 Learner Management &amp; Manager 儀表板功能。 帳戶名稱、使用者顯示名稱、電子郵件地址、部門、職稱、Office、國家/地區、城市、經理識別碼/電子郵件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| 設定檔 | 委託 | 無 | 檢視使用者的基本設定檔。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 進行資料存取

建置在 Microsoft 365 上的應用程式和增益集可能會使用 Microsoft Graph 以外的其他 Microsoft API 來收集或處理組織可識別的資訊， (OII) 。 列出此應用程式使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集的 OII 為何？** | **收集 OII 的理由？** | **是否儲存 OII？** | **儲存 OII 的理由為何？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>不使用非Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>是，我們會使用Insights Log Analytics 遙測/記錄，這些遙測/記錄僅用於疑難排解，並具有 90 天的保留原則，之後會刪除所有資料。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>LMS365 配備清除函式，可從用戶端 LMS365 資料庫移除任何個人資料。

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

ELEARNINGFORCE 國際 Aps 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳做法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已檢閱並符合Microsoft 身分識別平臺整合檢查清單中所述的所有適用最佳做法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 裝置平臺、裝置狀態、用戶端應用程式 |
| 您的應用程式是否要求案例的最低許可權許可權？ | 是 |
| 您應用程式的靜態註冊許可權是否能正確反映應用程式以動態和累加方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租使用者？ | 是 |
| 您的應用程式是否有機密用戶端？ | 否 |
| 您是否擁有為應用程式註冊的所有重新導向統一資源識別項 (URI) ？ | 是 |
| 您的應用程式是否公開任何 Web API？ | 是 |
| 只有在用戶端應用程式收到適當的同意時，您的許可權模型才允許呼叫成功嗎？ | 是 |
| 您的應用程式是否使用預覽 API？ | 否 |
| 您的應用程式是否使用已被取代的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
