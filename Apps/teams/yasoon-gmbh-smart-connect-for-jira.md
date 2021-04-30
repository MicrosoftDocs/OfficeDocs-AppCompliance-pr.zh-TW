---
title: Jira 的應用程式資訊，由 yasoon GmbH 的智慧連線
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2021
ms.topic: article
ms.service: attestation
description: 所有適用于 Jira 之 Smart 連線的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f0e3091eab95575c3a8ecc1c977d71fc29c4cbab
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093526"
---
# <a name="smart-connect-for-jira"></a>Jira 的 Smart Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年1月22日</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 yasoon GmbH 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Jira 的 Smart Connect |
| ID | WA200002055 |
| 功能 | Bot，傳訊擴充功能 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | yasoon GmbH |
| 合作夥伴網站的 URL | [https://yasoon.com](https://yasoon.com) |
| Teams 應用程式資訊頁面的 URL | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| 隱私權原則的 URL | [https://yasoon.com/privacy-policy-services](https://yasoon.com/privacy-policy-services) |
| 使用條款的 URL | [https://yasoon.com/terms-of-use](https://yasoon.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 yasoon GmbH 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadBasic | 委託 | 使用此許可權可讓使用者在 Jira 中選取此連接通道的其中一個。 | 用於快取目的的通道識別碼 | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage Read。群組 | 應用程式 | 允許此應用程式在 Jira 中顯示連結的通道訊息。 | 連結郵件至 Jira 問題的郵件 IDs | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelMessage 傳送 | 委託 | 不使用任何資料，此 API 是用來讓使用者從 Jira 回復通道郵件。 | 無 | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ChannelSettings Read。群組 | 應用程式 | 用於查閱通道的詳細資訊。 | 無 | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| 聊天室 ReadWrite | 委託 | 用於允許使用者新增新的回復到聊天，以及從 Jira 查看聊天訊息。 | 無 | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| Member Read。 Group | 應用程式 | 用於許可權檢查，可讓應用程式驗證使用者的小組成員資格。 | 無 | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| ReadBasic | 委託 | 使用此許可權可讓使用者在 Jira 中選取這其中一個加入的團隊。 | 用於快取目的的團隊 IDs | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| TeamSettings Read。群組 | 應用程式 | 允許應用程式讀取小組設定，以考慮某些預設值。 | 無 | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |
>| User.ReadBasic.All | 委託 | 允許使用者選取通道郵件中的「同事」至「@-提及」 | 無 | 89d5ca9f-d63b-4885-bd30-6e7433c1540c |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 您可以在以下位置看到 Atlassian Jira 和可能的承包商： https://go.yasoon.com/contractors | 郵件中繼資料 (識別碼、時間戳記) 、使用者及組織中繼資料 (使用者識別碼、組織識別碼) 和使用者電子郵件地址 | 支援應用程式功能 (例如，使用 Office) 帳戶來比對 Atlassian 帳戶，並啟用我們的支援以更快地疑難排解問題。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 使用使用者 Atlassian Jira 帳戶符合使用者 Teams 帳戶 | 否 |  |



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

> (識別碼的使用者中繼資料) 

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

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由 yasoon GmbH 提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，
<br />
- OAuth2 隱含 Flow （除非 SPA 是必要的）
<br />
- 資源擁有者密碼認證 (ROPC) 流程 | |您的應用程式是否公開任何 web APIs？ |無 | |您的應用程式是否使用預覽 APIs？ |是 | |您的應用程式使用的 APIs 是否已遭取代？ |否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
