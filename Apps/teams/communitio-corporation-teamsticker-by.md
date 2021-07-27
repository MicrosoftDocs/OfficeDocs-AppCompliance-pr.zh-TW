---
title: 由 Communitio Corporation Communitio 的 TeamSticker 應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 01/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: TeamSticker by Communitio 的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 871c410b520fc7b8697942a4921104329a239338
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521856"
---
# <a name="teamsticker-by-communitio"></a>Communitio 的 TeamSticker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年1月5日</p>

* <a href="https://teams.microsoft.com/l/app/bceca1f0-723f-44d0-b732-b3506c0a641d" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000894" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Communitio Corporation 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Communitio 的 TeamSticker |
| ID | WA200000894 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Communitio Corporation |
| 合作夥伴網站的 URL | [https://www.teamsuite.biz](https://www.teamsuite.biz) |
| Teams 應用程式資訊頁面的 URL | [https://www.teamsuite.biz/feature/](https://www.teamsuite.biz/feature/) |
| 隱私權原則的 URL | [https://www.teamsuite.biz/privacy/](https://www.teamsuite.biz/privacy/) |
| 使用條款的 URL | [https://www.teamsuite.biz/terms/](https://www.teamsuite.biz/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Communitio Corporation 已提供此資訊，讓您瞭解此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 聊天室 ReadWrite | 應用程式 |  因為應用程式會發佈到聊天。 | 應用程式不會儲存任何資料。 | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| Group.ReadWrite.All | 包括 | 應用程式收集群組識別碼和群組名稱。 | 應用程式會儲存群組識別碼和名稱一對。 | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| User.Read | 委託 | 應用程式會收集使用者的設定檔影像。 | 應用程式會儲存使用者的設定檔影像以顯示使用者圖示。 | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| User.Read.All | 包括 | Application 會收集使用者的 objectId/電子郵件/名稱，以尋找要傳送卡片的使用者。 | 在此情況下，應用程式不會儲存任何資料。 | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| offline_access | 委託 | Application 收集使用者的 api token 以使用 User。 Read/User. All in background。 | 應用程式會將使用者的 api 權杖儲存為使用使用者。讀取/使用者。讀取。所有的背景。 | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| openid | 委託 | 未收集任何資料。 | 應用程式會使用此許可權，透過 openid 登入。 | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| profile | 委託 | 應用程式會收集使用者的 objectId/電子郵件/名稱。 | 應用程式會儲存使用者的 objectId/電子郵件/名稱。 | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>|  Bot 架構 REST API | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 因為具有使用者的許可權。請參閱 All。 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>不適用

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Communitio Corporation 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 否 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
