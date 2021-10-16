---
title: IsLucid 的應用程式資訊，由 UAB Lucid 協定
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: isLucid 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7270fa4f4a08ca820d1fe7452dea13fb107f2294
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414900"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月9日</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

UAB Lucid 合約所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | isLucid |
| ID | WA200002385 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | UAB Lucid 協定 |
| 合作夥伴網站的 URL | [https://islucid.com](https://islucid.com) |
| Teams 應用程式資訊頁面的 URL | [https://islucid.com](https://islucid.com) |
| 隱私權原則的 URL | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| 使用條款的 URL | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 UAB Lucid 合約所提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AccessMedia 所有 | 包括 | 透過個別呼叫的使用者特別同意 (初始化的方式) 存取音訊資料流程。 音訊資料流程會轉寄給使用者，以取得進一步的功能。 | 應用程式會在 Azure (blob 儲存區上的個別容器中存放，並分別) 資訊和相關的中繼資料，為每個用戶端 Cosmos DB。 這是為使用者提供會議資訊的進一步存取，使用者使用該應用程式，且是在特定會議中。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| JoinGroupCall 所有 | 包括 | 透過個別呼叫的使用者特別同意 (初始化的方式) 存取音訊資料流程。 音訊資料流程會轉寄給使用者，以取得進一步的功能。 | 應用程式會在 Azure (blob 儲存區上的個別容器中存放，並分別) 資訊和相關的中繼資料，為每個用戶端 Cosmos DB。 這是為使用者提供會議資訊的進一步存取，使用者使用該應用程式，且是在特定會議中。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | 包括 | 當使用者使用與 Microsoft Planner 的整合，以從來電建立工作並自動儲存于 MS Planner 時，isLucid 會收集該使用者可用的群組、計畫、代理人。 若沒有此許可權，使用者就無法使用 isLucid 來建立工作。 | 任務標題、任務建立者、任務時間戳記、任務描述已儲存，讓使用者可以存取從特定會議進行的工作歷程記錄。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings Read。 All | 包括 | 應用程式會收集會議標題，讓使用者稍後在會議完成時 () 可以更輕鬆地找到先前的記錄和工作。 | 會議標題、會議的時間戳記、會議召集人 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| 工作。 ReadWrite | 包括 | 當使用者使用與 Microsoft Planner 的整合，以從來電建立工作並自動儲存于 MS Planner 時，isLucid 會收集該使用者可用的群組、計畫、代理人。 若沒有此許可權，使用者就無法使用 isLucid 來建立工作。 | 任務標題、任務建立者、任務時間戳記、任務描述已儲存，讓使用者可以存取從特定會議進行的工作歷程記錄。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | 包括 | 當使用者使用與 Microsoft Planner 的整合，以從來電建立工作並自動儲存于 MS Planner 時，isLucid 會收集該使用者可用的群組、計畫、代理人。 若沒有此許可權，使用者就無法使用 isLucid 來建立工作。 | 任務標題、任務建立者、任務時間戳記、任務描述已儲存，讓使用者可以存取從特定會議進行的工作歷程記錄。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | 包括 | 為使用者提供 Azure Active Directory 登入功能所收集的使用者識別碼（租使用者識別碼） | 用於進一步 rights management 的使用者識別碼、租使用者識別碼 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | 新註冊使用者的 Name、姓、Email 和電話號碼 | 我們使用 Hubspot CRM 維護銷售相關資訊 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Bot 啟用將音訊資料流程傳送至語音服務。 若要提供可讀取的方式，我們需要將音訊與使用者 (揚聲器) 產生關聯。 沒有提供這類資訊記錄是無用的 | Name、姓、狀態（如果是來賓帳戶或 Microsoft one） | Bot 啟用將音訊資料流程傳送至語音服務。 若要提供可讀取的方式，我們需要將音訊與使用者 (揚聲器) 產生關聯。 會議參與者資訊也適用于讓使用者看到的，即出席會議的人員。 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>使用我們服務的使用者正在產生記錄。 在 [腳本會議參與者] 中 (名稱，surnames) 呈現。 通話期間可能會提及任何可能的專案。 只要使用者使用我們的服務，我們就會將此資料儲存在使用者。 在用戶端使用我們後，在30天內就會銷毀所有相關聯的資料。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>當用戶端購買 isLucid 做為主控方案時，我們不會控制用戶端上的任何資料。 針對 SaaS 方案，我們可讓使用者取消使用我們的服務，然後刪除與該夥伴相關聯 Cosmos DB isntance。 我們正在將資訊傳送至規範 API 的程式也是

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由 UAB Lucid 合約提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

