---
title: InCaseIT 的應用程式資訊，Pilotech 為
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: InCaseIT 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 424df0e4c31f8a35c4d2e095f9f95c618274fa23
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429891"
---
# <a name="incaseit"></a>InCaseIT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月3日</p>

* <a href="https://teams.microsoft.com/l/app/4420b597-c1d5-4d40-ba81-2b2a78575c81" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003265" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Pilotech 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | InCaseIT |
| ID | WA200003265 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Pilotech AS |
| 合作夥伴網站的 URL | [https://incaseit.com](https://incaseit.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/introduction-to-incaseit-version-2-0) |
| 隱私權原則的 URL | [https://www.incaseit.com/privacy-policy/](https://www.incaseit.com/privacy-policy/) |
| 使用條款的 URL | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/1-4-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Pilotech 提供此資訊的方式，就是此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | 唯一使用的資料是使用者可讓應用程式使用存取權杖來呼叫 Graph API 的明確確認。 | 我們的應用程式只會儲存排程會議的連結，以方便使用者的會議協助工具。  例子。 1. 建立排程的 Teams 會議。 2. 在資料庫3中儲存會議連結。 使用應用程式中按鈕的會議連結，以便於會議中輕鬆存取。 | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| OnlineMeetings ReadWrite | 委託 | 唯一使用的資料是使用者可讓應用程式使用存取權杖來呼叫 Graph API 的明確確認。 | 我們的應用程式只會儲存線上會議的連結，以方便使用者的會議協助工具。  例子。 1. 建立 Teams 線上會議。 2. 在資料庫3中儲存會議連結。 使用應用程式中按鈕的會議連結，以便於會議中輕鬆存取。 | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| User.Read | 委託 | 唯一使用的資料是使用者可讓應用程式使用存取權杖來呼叫 Graph API 的明確確認。 | 使用者未儲存任何資料。讀取權限。 | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>EUII 可能會出現在應用程式記錄中，當危機期間向內部危機管理小組傳送通訊時。 記錄的移除原則是，我們會儲存最多3個月的記錄檔。 不過，您可以在需要時刪除要求。 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們的所有協力廠商和 subvendors 都有資料保護協定，可確保遵守將位置當作資料處理器和資料子處理器的 GDPR 管理法規。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Pilotech 提供此資訊的方式，就是此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/> |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
