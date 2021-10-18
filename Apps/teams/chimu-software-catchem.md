---
title: CatchEm by Chimu 軟體的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CatchEm 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ba7936c4896fa9c6fc77eee773b6c52bec0af19d
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60435547"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年3月27日</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Chimu 軟體所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | CatchEm |
| ID | WA200002639 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Chimu Software |
| 合作夥伴網站的 URL | [https://chimusoftware.com](https://chimusoftware.com) |
| Teams 應用程式資訊頁面的 URL | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| 隱私權原則的 URL | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| 使用條款的 URL | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Chimu 軟體會提供此資訊，此應用程式是關於此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadBasic | 委託 | 需要有此許可權才能決定應用程式使用者的連絡人。 AadObjectId：唯一識別使用者。 TenantId：判斷使用者是否為內部或外部的連絡人。 DisplayName，GivenName，姓：識別應用程式使用者的連絡人。 Email，UserPrincipalName：協助區分相同名稱的連絡人，並允許 &quot; 按一下聊天 &quot; 功能。 啟用 &quot; 點擊聊天功能的最新聊天 &quot; ID: | 需要有此許可權才能決定應用程式使用者的連絡人。 AadObjectId：唯一識別使用者。 TenantId：判斷使用者是否為內部或外部的連絡人。 DisplayName，GivenName，姓：識別應用程式使用者的連絡人。 Email，UserPrincipalName：協助區分相同名稱的連絡人，並允許 &quot; 按一下聊天 &quot; 功能。 啟用 &quot; 點擊聊天功能的最新聊天 &quot; ID: | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| 個人讀取 | 委託 | 可提高外部連絡人的資料準確性。 DisplayName：識別應用程式使用者的連絡人。 | 可提高外部連絡人的資料準確性。 DisplayName：識別應用程式使用者的連絡人。 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| 目前狀態為 [已讀取]。 | 委託 | 連絡人的目前狀態 | 不適用 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsActivity.Send | 包括 | 當連絡人的狀態變更時，將通知傳送給使用者 | 不適用 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsAppInstallation.ReadWriteSelfForUser | 委託 | 啟用應用程式的自動更新 | 不適用 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.Read | 委託 | AadObjectId：唯一識別使用者。 TenantId：判斷使用者是否為內部或外部的連絡人。 DisplayName，GivenName，姓：識別應用程式使用者的連絡人。 電子郵件、IM 位址、UserPrincipalName：協助區分相同名稱的連絡人，並允許 &quot; 按一下聊天 &quot; 功能。 CompanyName，Country： Analytics。 AccountEnabled，DeletedDateTime：自動刪除停用使用者的使用者資料 | AadObjectId：唯一識別使用者。 TenantId：判斷使用者是否為內部或外部的連絡人。 DisplayName，GivenName，姓：識別應用程式使用者的連絡人。 電子郵件、IM 位址、UserPrincipalName：協助區分相同名稱的連絡人，並允許 &quot; 按一下聊天 &quot; 功能。 CompanyName，Country： Analytics。 AccountEnabled，DeletedDateTime：自動刪除停用使用者的使用者資料 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.ReadBasic.All | 委託 | 以改善內部連絡人的資料準確性。 AadObjectId：唯一識別使用者。 TenantId：判斷使用者是否為內部或外部的連絡人。 DisplayName，GivenName，姓：識別應用程式使用者的連絡人。 Email，UserPrincipalName：協助區分相同名稱的連絡人，並允許 &quot; 按一下聊天 &quot; 功能。 | 以改善內部連絡人的資料準確性。 AadObjectId：唯一識別使用者。 TenantId：判斷使用者是否為內部或外部的連絡人。 DisplayName，GivenName，姓：識別應用程式使用者的連絡人。 Email，UserPrincipalName：協助區分相同名稱的連絡人，並允許 &quot; 按一下聊天 &quot; 功能。 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| offline_access | 委託 | Graph 的安全性權杖，可讓應用程式在使用者未使用應用程式的情況下，通知連絡人目前狀態變更和更新連絡人清單 | Graph 安全性權杖 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| &quot;來自郵件功能的標記 &quot; 需要使用連絡人的顯示名稱，向應用程式使用者顯示。 | 連絡人的顯示名稱 | 若要能夠將連絡人的名稱傳回應用程式使用者 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>不適用

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Chimu 軟體會提供此資訊，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 否 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
