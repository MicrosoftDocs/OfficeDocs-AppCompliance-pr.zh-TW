---
title: 使用 Jira 向前移動工作所需的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 06/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊，可在 Jira 中向前移動工作、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7120519c2ecb0643465760677b2bef895b1e2f4d
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521273"
---
# <a name="move-work-forward-with-jira"></a>使用 Jira 推展工作進度

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月10日</p>

* <a href="https://teams.microsoft.com/l/app/79ca2e8f-dd2c-40d5-897e-1b22d41038fe" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002855" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

將工作轉寄給 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 使用 Jira 推展工作進度 |
| ID | WA200002855 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 推展工作進度 |
| 合作夥伴網站的 URL | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.moveworkforward.com/product/microsoft-teams-jir...](https://www.moveworkforward.com/product/microsoft-teams-jira-connector) |
| 隱私權原則的 URL | [https://www.moveworkforward.com/privacy-policy](https://www.moveworkforward.com/privacy-policy) |
| 使用條款的 URL | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊的移動方式是向前移動，以瞭解此應用程式如何收集和儲存組織資料，以及您的組織將對該應用程式所收集的資料所進行的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 通道。建立 | 委託 | 用於建立問題討論通道。 | 新建立之通道的 web url 會儲存在 Jira 中，以供快速存取 Microsoft Teams 討論通道。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| ReadBasic | 委託 | 通道名稱和 id 是用來將 Jira 中的通知傳送至 Microsoft Teams。 | 通道識別碼及名稱是儲存來設定從 Jira 到 Microsoft Teams 的通知。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| ReadBasic | 委託 | 使用此許可權可讓使用者在 Jira 中選取這其中一個加入的團隊。 | 要在 Jira 的 [設定畫面] 中顯示的團隊識別碼和名稱。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| TeamsAppInstallation.ReadForTeam | 委託 | Teams 小組中的應用程式閱讀已安裝。 設定傳送至 Microsoft Teams 時，應用程式可以使用已安裝的 Bot 傳送至 Teams。 | 無 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| User.Read | 委託 | 可讓使用者建立與同事的討論通道，並在通道郵件中提及 @-提及 | 無 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| 電子郵件 | 委託 | 電子郵件是用來比對 Atlassian 和 Microsoft 使用者 | 不會儲存電子郵件。 僅在對應程式期間使用。 | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 安裝應用程式時以名稱 Greet 使用者。 符合 Microsoft Teams 和 Atlassian 使用者。 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們記錄租使用者 url，該 url 儲存在最多5天的記錄中。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們只會使用提供嚴格資料隱私權保證的服務。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊已透過向前移動，瞭解此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
