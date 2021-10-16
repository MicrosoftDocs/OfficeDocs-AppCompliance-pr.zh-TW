---
title: SalesTim 的應用程式資訊（按 SalesTim）
ms.author: elmalova
author: elenamalova
ms.date: 10/09/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: SalesTim 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9d0d5a3653bdbb15f1c2d5946db3325881c57e67
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412763"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員更新：2021年10月9日</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 SalesTim 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SalesTim |
| ID | WA200001393 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | SalesTim |
| 合作夥伴網站的 URL | [https://www.salestim.com](https://www.salestim.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.salestim.com](https://www.salestim.com) |
| 隱私權原則的 URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 使用條款的 URL | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 SalesTim 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember ReadWrite。 | 委託 | 由我們的成員資格原則邀請到通道的使用者識別碼 | 受我們的成員資格原則邀請到通道的使用者識別碼會儲存在我們的審計追蹤中。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | 委託 | 使用者識別碼。 可讓使用者選取應用程式中不同位置的其他使用者，例如在工作流程中選取 [核准者]。 | 使用者識別碼。 可讓使用者選取應用程式中不同位置的其他使用者，例如在工作流程中選取 [核准者]。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | 包括 | 我們&#8217;只會&#8217;儲存群組/小組 IDs，我們不會儲存任何群組/小組內容。 允許此應用程式建立群組，代表登入的使用者讀取所有群組屬性和成員資格。 此外，允許群組擁有者管理其群組，並允許群組成員更新群組內容。 | 我們&#8217;只會&#8217;儲存群組/小組 IDs，我們不會儲存任何群組/小組內容。 允許此應用程式建立群組，代表登入的使用者讀取所有群組屬性和成員資格。 此外，允許群組擁有者管理其群組，並允許群組成員更新群組內容。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| 傳送郵件 | 委託 | 使用者 IDs。 我們&#8217;將此動作的中繼資料儲存在一起，例如通知日期、收件者、要求識別碼。 | 使用者 IDs。 我們&#8217;將此動作的中繼資料儲存在一起，例如通知日期、收件者、要求識別碼。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | 包括 | 使用者識別碼和設定檔資料。 可讓使用者選取應用程式中不同位置的其他使用者，例如在工作流程中選取 [核准者]。 | 使用者識別碼。 可讓使用者選取應用程式中不同位置的其他使用者，例如在工作流程中選取 [核准者]。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offline_access | 委託 | 重新整理權杖。 允許應用程式以使用者身分執行某些背景作業和動作。 | 重新整理權杖。 允許應用程式以使用者身分執行某些背景作業和動作。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Marketplace | 是 | 租使用者識別碼 | 用來管理我們的客戶訂閱 | 租使用者識別碼 | 用來管理我們的客戶訂閱 |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 我們正在使用 Intercom 做為我們的主要客戶支援應用程式。  | 租使用者識別碼 | 我們正在使用組織的租使用者識別碼，將客戶支援要求與特定的 Microsoft 365 環境關聯。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>以下說明所有收集的資料： https://developers.salestim.com/platform/datamanagement.html#application-data 如所述，記錄暫時儲存15天，然後自動刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們正在套用保留原則做為每月 &quot; 客戶記錄處置評審的一部分 &quot; 。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

SalesTim 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 多重要素驗證。 僅允許 Intune 註冊的裝置存取特定服務。 限制使用者位置和 IP 範圍 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

