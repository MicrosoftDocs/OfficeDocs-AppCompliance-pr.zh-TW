---
title: Atlassian 的 Confluence Cloud 應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Confluence 雲端的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 965ac513d4d13a0995b992a5022bc4f7d9e44a9f
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427165"
---
# <a name="confluence-cloud"></a>Confluence Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月18日</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Atlassian 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Confluence Cloud |
| ID | WA200003113 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Atlassian |
| 合作夥伴網站的 URL | [https://www.atlassian.com](https://www.atlassian.com) |
| 隱私權原則的 URL | [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy) |
| 使用條款的 URL | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Atlassian 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 委託 | -我們已閱讀會議中的聊天室成員清單，所以我們知道會議的被邀請者清單。   -我們讀取的使用者&#8217; 名稱和電子郵件地址，我們在會議應用程式中有條件顯示。 例如，顯示正在參加會議筆記的目前使用者名稱。   -我們的應用程式會讀取使用者&#8217;的行事曆事件，讓應用程式已新增至會議，讓我們有會議標題等會議的基本資訊。 | 我們收集和儲存的內容範例包括：摘要和描述新增至 JIRA 問題、您在 Confluence 中建立的頁面、您在 Bitbucket 中建立的頁面、您的存放庫和拉取要求、您在與 Statuspage 中的事件時輸入的注釋，以及您對我們提供的任何意見反應。 內容也包含您上傳至服務的檔案和連結。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| ReadBasic | 委託 |  -我們已閱讀會議中的聊天室成員清單，所以我們知道會議的被邀請者清單。   -我們讀取的使用者&#8217; 名稱和電子郵件地址，我們在會議應用程式中有條件顯示。 例如，顯示正在參加會議筆記的目前使用者名稱。   -我們的應用程式會讀取使用者&#8217;的行事曆事件，讓應用程式已新增至會議，讓我們有會議標題等會議的基本資訊。 | 我們收集和儲存的內容範例包括：摘要和描述新增至 JIRA 問題、您在 Confluence 中建立的頁面、您在 Bitbucket 中建立的頁面、您的存放庫和拉取要求、您在與 Statuspage 中的事件時輸入的注釋，以及您對我們提供的任何意見反應。 內容也包含您上傳至服務的檔案和連結。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| User.ReadBasic.All | 委託 | -我們已閱讀會議中的聊天室成員清單，所以我們知道會議的被邀請者清單。   -我們讀取的使用者&#8217; 名稱和電子郵件地址，我們在會議應用程式中有條件顯示。 例如，顯示正在參加會議筆記的目前使用者名稱。   -我們的應用程式會讀取使用者&#8217;的行事曆事件，讓應用程式已新增至會議，讓我們有會議標題等會議的基本資訊。 | 我們收集和儲存的內容範例包括：摘要和描述新增至 JIRA 問題、您在 Confluence 中建立的頁面、您在 Bitbucket 中建立的頁面、您的存放庫和拉取要求、您在與 Statuspage 中的事件時輸入的注釋，以及您對我們提供的任何意見反應。 內容也包含您上傳至服務的檔案和連結。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| 電子郵件 | 委託 | -我們已閱讀會議中的聊天室成員清單，所以我們知道會議的被邀請者清單。   -我們讀取的使用者&#8217; 名稱和電子郵件地址，我們在會議應用程式中有條件顯示。 例如，顯示正在參加會議筆記的目前使用者名稱。   -我們的應用程式會讀取使用者&#8217;的行事曆事件，讓應用程式已新增至會議，讓我們有會議標題等會議的基本資訊。 | 我們收集和儲存的內容範例包括：摘要和描述新增至 JIRA 問題、您在 Confluence 中建立的頁面、您在 Bitbucket 中建立的頁面、您的存放庫和拉取要求、您在與 Statuspage 中的事件時輸入的注釋，以及您對我們提供的任何意見反應。 內容也包含您上傳至服務的檔案和連結。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| offline_access | 委託 | -我們已閱讀會議中的聊天室成員清單，所以我們知道會議的被邀請者清單。   -我們讀取的使用者&#8217; 名稱和電子郵件地址，我們在會議應用程式中有條件顯示。 例如，顯示正在參加會議筆記的目前使用者名稱。   -我們的應用程式會讀取使用者&#8217;的行事曆事件，讓應用程式已新增至會議，讓我們有會議標題等會議的基本資訊。 | 我們收集和儲存的內容範例包括：摘要和描述新增至 JIRA 問題、您在 Confluence 中建立的頁面、您在 Bitbucket 中建立的頁面、您的存放庫和拉取要求、您在與 Statuspage 中的事件時輸入的注釋，以及您對我們提供的任何意見反應。 內容也包含您上傳至服務的檔案和連結。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| openid | 委託 |  -我們已閱讀會議中的聊天室成員清單，所以我們知道會議的被邀請者清單。   -我們讀取的使用者&#8217; 名稱和電子郵件地址，我們在會議應用程式中有條件顯示。 例如，顯示正在參加會議筆記的目前使用者名稱。   -我們的應用程式會讀取使用者&#8217;的行事曆事件，讓應用程式已新增至會議，讓我們有會議標題等會議的基本資訊。 | 我們收集和儲存的內容範例包括：摘要和描述新增至 JIRA 問題、您在 Confluence 中建立的頁面、您在 Bitbucket 中建立的頁面、您的存放庫和拉取要求、您在與 Statuspage 中的事件時輸入的注釋，以及您對我們提供的任何意見反應。 內容也包含您上傳至服務的檔案和連結。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| 設定檔 | 委託 |  -我們已閱讀會議中的聊天室成員清單，所以我們知道會議的被邀請者清單。   -我們讀取的使用者&#8217; 名稱和電子郵件地址，我們在會議應用程式中有條件顯示。 例如，顯示正在參加會議筆記的目前使用者名稱。   -我們的應用程式會讀取使用者&#8217;的行事曆事件，讓應用程式已新增至會議，讓我們有會議標題等會議的基本資訊。 | 我們收集和儲存的內容範例包括：摘要和描述新增至 JIRA 問題、您在 Confluence 中建立的頁面、您在 Bitbucket 中建立的頁面、您的存放庫和拉取要求、您在與 Statuspage 中的事件時輸入的注釋，以及您對我們提供的任何意見反應。 內容也包含您上傳至服務的檔案和連結。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |


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

>https://www.atlassian.com/trust/privacy/how-we-handle-your-data

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Atlassian 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 否 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
