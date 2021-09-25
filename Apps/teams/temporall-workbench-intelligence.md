---
title: Temporall 的工作臺智慧應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 09/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于工作臺智慧的安全性和符合性資訊資訊、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bf2a249e9eb0cf8e572158d9b393b49fc81153ff
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785405"
---
# <a name="workbench-intelligence"></a>工作臺智慧

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年9月22日</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Temporall 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 工作臺智慧 |
| ID | WA200002705 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Temporall |
| 合作夥伴網站的 URL | [https://www.temporall.com](https://www.temporall.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| 隱私權原則的 URL | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| 使用條款的 URL | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Temporall 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog Read。 All | 委託 | 取得已安裝的小組應用程式清單，以取得已知的外部識別碼的本機應用程式識別碼。 | 本機應用程式識別碼。在不同的承租人上安裝應用程式時，必須能夠識別應用程式。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ReadBasic | 應用程式 | 通道識別碼 &amp; 名稱。 理由：允許加入/離開通道以同步處理郵件活動。  | 從取得通道傳回的原始資料物件。 理由： Temporall 工作臺可讓使用者根據通道來篩選和 categorise 資料。 這個原始資料會儲存為具有原始物件的參照。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage Read。 All | 應用程式 | 郵件活動 &amp; 類型和寄件者 &amp; 目標。 從這些路由接收的資料：/teams/$ {teamId}/channels/$ {channelId}/messages/teams/$ {teamId}/channels/$ {channelId}/messages/$ {messageId}。 理由：能夠計算 &amp; 郵件活動的衡量值報告。 這會形成我們 organisational 網路分析模組的核心，讓他們能夠在使用者小組之間繪製活動圖表 &amp; 。 | 我們偵測新訊息/回復/反應/提及的數量會 &amp; 儲存這些度量，以及傳回的 raw message 物件。 資料是我們核心功能的一部分所要求。 對郵件資料執行分析時，需要將其儲存至資料庫以取得最佳效能-這也會減少對相同資料通話的需求。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | 應用程式 | ClientId、使用者清單、組織及子通道清單。 理由：將同步處理 &amp; 使用者讀入 Temporall 工作臺所需 | 使用者名稱、電子郵件、圖示、會話參考。 理由： &#160;Temporall 工作臺允許使用者根據通道來篩選和 categorise 資料。 組織資料儲存在安裝之後重新連接至小組 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | 應用程式 | 群組識別碼 &amp; 名稱。 理由：將應用程式安裝到每個群組/通道 | 組識別碼 &amp; 名稱，以及用於參考的 raw 資料物件。 理由： Temporall 工作臺可讓使用者根據群組/小組篩選和 categorise 資料。 這個原始資料會儲存為具有原始物件的參照。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember Read。 All | 應用程式 | 使用者對團隊的成員資格。 理由：允許與 Temporall 工作臺的 Teams 中的所有使用者同步處理 | 電子郵件地址、名稱和姓氏。 理由：允許以電子郵件同步處理使用者的團隊中的使用者與 Temporall 工作臺中的使用者。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation ReadWriteForTeam 所有 | 應用程式 | 讀取為小組安裝的應用程式清單。 理由：檢查是否已安裝應用程式，否則請先安裝應用程式，才能透過圖形 api 取得郵件活動 | 不適用 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation ReadWriteForUser 所有 | 應用程式 | 已安裝應用程式的閱讀清單。 檢查是否已安裝應用程式，否則請透過問捲進行安裝以與使用者接洽 | NA | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | 委託 | 基本使用者 &amp; 公司資訊。 理由：用來 categorise 使用者的郵件活動，允許 bot 參與主動訊息。 | 使用者名稱、電子郵件、圖示、會話參考。 理由：允許我們的 bot 主動傳送郵件給具有相關資訊的使用者。 群組使用者的資料顯示 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud | LDAP 資訊 | 我們的平臺位於 Google Cloud 平臺上 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>https://temporall.com/privacy-policy/

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

Temporall 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
