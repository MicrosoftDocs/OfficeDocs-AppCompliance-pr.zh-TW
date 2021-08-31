---
title: Arrangr by Arrangr，Inc. 的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Arrangr 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3ccc0e501a899fcb5dc613c254de9aa62911d023
ms.sourcegitcommit: 78e63c8004c49fa95d80618b9fee424f1084e43d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/19/2021
ms.locfileid: "58404316"
---
# <a name="arrangr"></a>Arrangr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月15日</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Arrangr，Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Arrangr |
| ID | WA200002975 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Arrangr，Inc.。 |
| 合作夥伴網站的 URL | [https://arrangr.com](https://arrangr.com) |
| Teams 應用程式資訊頁面的 URL | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| 隱私權原則的 URL | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| 使用條款的 URL | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Arrangr，Inc. 已提供此資訊。關於此應用程式如何收集和儲存組織的資料，以及您的組織將會透過應用程式收集的資料所產生的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **權限**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | 我們會收集使用者行事曆的名稱，以及其行事曆事件的詳細資料，以協助排程會議。 | 我們會儲存與其相連之任何行事曆的名稱，讓他們可以查看和變更他們所連接的行事曆。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ReadBasic | 委託 | 收集使用者可使用的頻道清單，讓我們可以向他們顯示其通道的清單，以供他們挑選共用 Arrangr 邀請的人。 | 我們不會將資訊儲存在使用者的頻道上 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage 傳送 | 委託 | 此許可權是用來代表使用者將 Arrangr 邀請傳送到小組通道。 它不會用來收集資料。 | 使用此許可權收集的資料不會儲存。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| 聊天室 ReadWrite | 委託 | 此許可權是用來代表使用者將 Arrangr 邀請傳送至 Teams 聊天。 此許可權不會用來收集資料。 | 使用此許可權收集的資料不會儲存。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage 傳送 | 委託 | 此許可權可用來代表使用者將 Arrangr 邀請傳送至1:1 和群組聊天。 它不會用來收集資料。 | 使用此許可權收集的資料不會儲存。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings ReadWrite | 委託 | Arrangr 會收集使用此許可權產生之流程中 Microsoft Teams 的會議連結。 我們會為使用者產生 Teams 會議，讓他們在 Arrangr 上排列 Teams 通話。 | 我們會儲存會議連結，讓他們可以與適當的團體共用，以加入會議。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| 個人讀取 | 委託 | 我們會收集與使用者相關之人員的名稱和電子郵件。 如此一來，我們便可輕鬆讓使用者將其選擇為 Arrangr 邀請的收件者。 | 如果使用者最後選取透過此 API 提供的收件者，則會儲存該收件者的名稱和電子郵件，以便進行會議，以及讓使用者在今後將其選擇為收件者。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | 委託 | 我們會收集使用者 Teams 的名稱，讓他們可以選擇要連接至 Arrangr 的 Teams，以及想要共用 Arrangr 邀請的團隊。 | Arrangr 會儲存使用者已選擇連結至 Arrangr 的 Teams 名稱，因此我們可以在其設定中顯示這些 Teams，然後在決定要共用 Arrangr 邀請的位置時，讓他們從這些 Teams 中進行選取。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | 委託 | 我們讀取的是使用者的 Teams 帳戶中是否已安裝了我們的應用程式，以便他們是否要安裝應用程式，並讓我們為他們安裝應用程式。 | 我們不會儲存透過此許可權收集的資料。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| 設定檔 | 委託 | 名稱和電子郵件地址 | 名稱和電子郵件地址，以便向使用者顯示其連線至服務的帳戶。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | 是 | 名稱、電子郵件、行事曆名稱，行事曆事件資訊 | 我們會收集此資訊，讓使用者將其行事曆連線至 Arrangr，以協助排程會議 | 名稱、電子郵件、行事曆名稱 | 我們會儲存此資訊，以便讓使用者向使用者顯示其已連線到服務的帳戶和行事曆。 |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud，SendGrid，Stripe，Quaderno | Google Cloud 會儲存所有使用者資料、使用者名稱和電子郵件與 SendGrid 共用，以便將電子郵件傳送給使用者、帶區接收使用者名稱、電子郵件，以及支付資訊以用於處理付款。 Quaderno 會接收使用者名稱、電子郵件及地理資訊，以協助與加值稅相容。 | 需要 Google Cloud 來儲存資料，以記住使用者，並提供他們選擇要儲存在 Arrangr 中的資訊。 若要將電子郵件傳送給我們的使用，我們必須提供其電子郵件地址給 SendGrid。 若要收集付款，我們必須處理其在 Stripe 中的付款資訊，但不會將其支付資訊儲存在自己的伺服器上。 需要有 Quaderno 才能計算銷售稅，並確定我們仍遵循銷售稅法規。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 使用者將使用我們的郵件擴充，安排與其他人的會議。 我們需要為使用者顯示其登入的帳戶，而且我們必須能夠將其所傳送的邀請與正確的 Arrangr 使用者關聯。 | 使用者名稱、電子郵件及通訊資訊。 | 需要這項資訊才能協調多方間的會議，以及分享連線和會議的詳細資料。 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們會透過其 API 來控制 Google Cloud 資料儲存中儲存的資料，並可刪除我們需要的任何資料。 我們的使用者可以要求移除其帳戶和刪除其資料。

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

Arrangr，Inc. 已提供此資訊。關於此應用程式如何處理驗證、授權、application registration 最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
