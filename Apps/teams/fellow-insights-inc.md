---
title: Insights Inc. 對同事的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 在 CSA 星型登錄中，所有可用的安全性和符合性資訊資訊，如其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 581b41bdf80bcbdd77bb3406b35556308a13b8f9
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525637"
---
# <a name="fellow"></a>Fellow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新：2021年5月21日</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Insights inc. 對 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Fellow |
| ID | WA200002576 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Fellow Insights Inc |
| 合作夥伴網站的 URL | [https://fellow.app](https://fellow.app) |
| 隱私權原則的 URL | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| 使用條款的 URL | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由相關的 Insights inc. 提供此應用程式如何收集和儲存組織資料，以及您的組織將會對應用程式所收集的資料所做的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 包括 | 與使用者的行事曆相連，讓他們能夠對資料做筆記。 | 「同事」會儲存使用者主要行事曆的所有事件資料。 不會儲存附件。 這是在同事內使用，以提供以行事曆為基礎的記事經驗。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| ReadBasic | 委託 | 我們會收集使用者是其成員的通道名稱，以便向他們顯示可傳送附注的頻道清單。 | 我們快取使用者所屬的通道名稱和 IDs，以便允許使用者將附注從其他人傳送至指定的頻道。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | 應用程式 | 只有在整個組織執行系統管理員安裝時，才會收集此資料。 我們使用目錄資料來同步處理使用者清單，並自動布建帳戶。 | 如果且僅限系統管理員從使用者內部的工作區設定中執行整個組織的安裝，系統管理員可以選擇啟用所有使用者從 Azure AD 自動同步處理 (自動布建) 。 在此情況下，我們會將使用者資訊（例如 ID、名稱、電子郵件、管理員和群組成員資格）儲存在 (，以) 小組管理功能。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | 應用程式 | 只有在整個組織執行系統管理員安裝時，才會收集此資料。 我們使用目錄資料來同步處理使用者清單，並自動布建帳戶。 | 如果且僅限系統管理員從使用者內部的工作區設定中執行整個組織的安裝，系統管理員可以選擇啟用所有使用者從 Azure AD 自動同步處理 (自動布建) 。 在此情況下，我們會將使用者資訊（例如 ID、名稱、電子郵件、管理員和群組成員資格）儲存在 (，以) 小組管理功能。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| 個人讀取 | 委託 | 會收集使用者的連絡人，在特定連絡人 displayNames 和電子郵件地址。 這是在同事內使用，提供邀請邀請加入附注/共用附注的使用者清單。 | 會收集使用者的連絡人，在特定連絡人 displayNames 和電子郵件地址。 這是在同事內使用，提供邀請邀請加入附注/共用附注的使用者清單。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| 已讀取的人員。所有 | 應用程式 | 只有在整個組織執行系統管理員安裝時，才會收集此資料。 會收集使用者的連絡人，在特定連絡人 displayNames 和電子郵件地址。 這是在同事內使用，提供邀請邀請加入附注/共用附注的使用者清單。 | 如果且僅限系統管理員從使用者內部的工作區設定中執行整個組織的安裝，系統管理員可以選擇啟用所有使用者從 Azure AD 自動同步處理 (自動布建) 。 在此情況下，會收集使用者的連絡人，在特定連絡人 displayNames 和電子郵件地址。 這是在同事內使用，提供邀請邀請加入附注/共用附注的使用者清單。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| ReadBasic | 委託 | 會收集使用者所屬的小組清單。 這是為了讓使用者能夠將記事從同事傳送給小組的目的。 | 我們快取使用者隸屬的小組名稱和 IDs，以允許使用者將附注從同事傳送至指定的小組頻道。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | 委託 | 收集基本的使用者資訊。 使用者名稱、電子郵件、職稱。 此資訊用於建立使用者帳戶及公司帳戶的同事。 | 儲存基本使用者資訊。 使用者名稱、電子郵件、職稱。 此資訊用於維護使用者帳戶和公司帳戶。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | 應用程式 | 只有在整個組織執行系統管理員安裝時，才會收集此資料。 我們使用目錄資料來同步處理使用者清單，並自動布建帳戶。 | 如果且僅限系統管理員從使用者內部的工作區設定中執行整個組織的安裝，系統管理員可以選擇啟用所有使用者從 Azure AD 自動同步處理 (自動布建) 。 在此情況下，我們會將使用者資訊（例如 ID、名稱、電子郵件、管理員和群組成員資格）儲存在 (，以) 小組管理功能。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | 委託 | 使用者的重新整理權杖，以維持透過其他範圍所收集的資料存取權。 | 使用者的重新整理權杖會儲存在資料庫中。 這種方式是在背景中用於同步處理事件，以行事曆的記事經驗，以及在排程事件上進行記事的通知。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>「同事」是由使用者直接提供的資訊，包含個人資料。 同事也會儲存協力廠商系統的部分資訊，例如 OAuth 資料、行事歷數據和 PII （如 name &amp; email）。 我們會無限期保留所有資料，並針對其收集的目的，以不限法律允許。 我們會在先前收到要求的使用者要求時，安全地刪除此資訊。 記錄資料會保留30天。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>所有資料傳送都會透過安全 APIs 傳送至後端系統。 根據 AICPA 定義的 SOC 2 framework，其他許多控制措施可確保系統的安全性和機密性。 同事的控制會進行年度審計，以確保持續的相容性。 SOC 2 報告可以在要求和 NDA 時共用。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊已由相關 Insights inc. 提供此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | ,<br/><br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
