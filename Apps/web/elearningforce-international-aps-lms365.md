---
title: LMS365 by ELEARNINGFORCE 國際 Ap 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: LMS365 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7cb2fc4ab5acf706edc367c3455385f00480ff9b
ms.sourcegitcommit: ddedb98532d7cef5cff47b137aa0ad87494b163d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/02/2022
ms.locfileid: "64623195"
---
# <a name="lms365"></a>LMS365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員的更新日期：2021年6月23日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

透過 ELEARNINGFORCE 國際 Ap 的資訊提供給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | LMS365 |
| ID | elearningforce.lms365_spfx |
| 合作夥伴公司名稱 | 國際 Ap ELEARNINGFORCE |
| 合作夥伴網站的 URL | [https://www.elearningforce.com](https://www.elearningforce.com) |
| 隱私權原則的 URL | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| 使用條款的 URL | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊的提供方式是 ELEARNINGFORCE 國際 Ap，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何 [Microsoft Graph 許可權](/graph/permissions-reference) 。

>| **權限**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember Read。 All | 應用程式 | 無 | 允許應用程式展開 AD 群組成員，以向課程註冊使用者群組所需的成員。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| 傳送郵件 | 委託 | 無 | 在設定電子郵件帳戶以進行通知時，會動態要求許可權。 允許應用程式傳送通知電子郵件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement 讀取的目錄 | 應用程式 | 無 | 允許應用程式在租使用者布建期間取得 SharePoint 網域。 網域用於 URL 構造。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| 使用者. Invite。 | 委託 | 無 | 允許應用程式代表目前登入的使用者邀請外部使用者 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | 委託 | 無 | 登入和讀取使用者設定檔。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 委託 | 無 | 允許應用程式讀取目前登入使用者的完整設定檔。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 應用程式 | 允許應用程式讀取完整的使用者設定檔。 &#8217; 管理員建立階層報告&#8217;所需的使用者。 | 下列個人資料儲存在專用資料庫中，供各個客戶用於 Learner 應用程式中的管理 &amp; 管理員儀表板功能。 帳戶名稱、使用者顯示名稱、電子郵件地址、部門、職稱、Office、國家、城市、管理員識別碼/電子郵件 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| 設定檔 | 委託 | 無 | View user 的基本設定檔。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

在 Microsoft 365 上建的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs 來收集或處理組織識別資訊 (OII) 。 列出此應用程式所使用之 Microsoft Graph 以外的任何 Microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>使用非 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>是的，我們使用 Insights 記錄分析遙測/記錄，只用于疑難排解，並在其後已刪除所有資料的90天保留原則。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>LMS365 已配備清除功能，可移除用戶端 LMS365 資料庫中的任何個人資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security 資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

ELEARNINGFORCE 國際性的 Ap 會提供此資訊，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已透過 Microsoft identity platform 整合檢查清單中所述的所有適用的最佳作法，加以檢查及編譯？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 裝置平臺、裝置狀態、用戶端應用程式 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 否 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
