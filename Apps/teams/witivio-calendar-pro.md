---
title: Witivio 的行事曆應用程式資訊 Pro
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的 [行事曆] 安全性和符合性資訊資訊，如「行事曆」 Pro、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 89731f0dcdbcd6fcb8d27588179189a0d634284b
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279626"
---
# <a name="calendar-pro"></a>行事曆 Pro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年9月2日</p>

* <a href="https://teams.microsoft.com/l/app/19a29a41-cbca-4152-a2af-dd9728ea35f1" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002152" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Witivio 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 行事曆 Pro |
| ID | WA200002152 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Witivio |
| 合作夥伴網站的 URL | [https://www.witivio.com](https://www.witivio.com) |
| 隱私權原則的 URL | [https://www.teams-pro.com/en/privacy-policy/](https://www.teams-pro.com/en/privacy-policy/) |
| 使用條款的 URL | [https://www.teams-pro.com/en/terms-of-use/](https://www.teams-pro.com/en/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Witivio 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | 使用資料 | 資料是用來顯示 UI 中的資訊 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| User.ReadBasic.All | 委託 | 使用資料 | 資料可用來列出人員以啟用人員選擇器 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| 電子郵件 | 委託 | 使用電子郵件 | 電子郵件用來識別 UI 中的使用者 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| offline_access | 委託 | 使用資料 | 離線存取可用於啟用 SSO 與 Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| openid | 委託 | 驗證 | OpenID 用於使用 Microsoft Teams 進行驗證 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| 設定檔 | 委託 | 使用資料 | 設定檔用於啟用 SSO 與 Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>遙測包含用於診斷的 UPN 和 AAD 識別碼。 只有生產/執行系統管理員才能存取生產遙測。 記錄檔會儲存在90天內，並且可以在 dpo@witivio.com 上以電子郵件要求刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>Witivio 只會使用部署于北歐地區的 Microsoft Azure 元件。 我們使用 application 真知灼見和 Cosmos DB 進行資料分析和儲存。 Witivio 對所有使用者（包括系統管理員）使用 MFA。 系統管理員有 (工作站) 的使用者帳戶，以及存取 Azure ressources 的許可權帳戶。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Witivio 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | ,<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/> |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
