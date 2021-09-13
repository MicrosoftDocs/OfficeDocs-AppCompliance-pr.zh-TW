---
title: AtSpoke by Townsend 大街 Labs，Inc. 的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: atSpoke 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2d72ea33577e386c61be6bcd09feeba813e9e1f5
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278195"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2020年6月3日</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Townsend 大街 Labs，Inc. 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | atSpoke |
| ID | WA200001454 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Townsend Street Labs, Inc. |
| 合作夥伴網站的 URL | [https://www.atspoke.com/](https://www.atspoke.com/) |
| 隱私權原則的 URL | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| 使用條款的 URL | [https://www.atspoke.com/terms-of-service/](https://www.atspoke.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Townsend 大街 Labs，Inc. 提供。關於此應用程式如何收集和儲存組織的資料，以及您的組織將會對應用程式收集的資料所做的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | 委託 | atSpoke 儲存 Microsoft 群組識別碼 | 允許在 atSpoke 和 Microsoft Teams 之間讀取及寫入群組資訊的功能。  | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| User.ReadWrite.All | 委託 | atSpoke 儲存使用者的電子郵件和使用者識別碼 | 允許在 atSpoke 與 Microsoft Teams 之間讀取及寫入使用者資訊的功能。 | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| offline_access | 委託 | atSpoke 未儲存任何資料。 | 這種功能用於背景同步處理。 | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 是的，我們使用協力廠商服務以取得運作效率。 Google，Inc.：儲存在邏輯磁片區、本機 Google 雲端網路中的儲存區備份、服務和 API 記錄檔或應用程式記錄檔中的資料。 記錄的事務性事件可以包含使用者識別碼 (s) 、連絡人資訊和客戶內容。 MongoDB，Inc.：儲存在雲端架構資料庫集合中的資料。 -包含使用者所要求之要求的客戶內容，回應使用者新增的要求和使用者新增的知識文章。 -使用者識別碼 (用來建立分支使用者帳戶) 的名稱、電子郵件、頭像和電話號碼。 Mailgun 技術，Inc.：使用者識別碼和聯繫資訊，用以傳送電子郵件通訊 (例如 name 和 email) 。 Twilio，Inc.：使用者電話號碼和客戶內容：透過 Twilio&#8217;s 服務（如文字、郵件內文、語音和影片媒體、影像及聲音）的使用方式來交換內容。 Mixpanel，Inc.：已傳輸的個人資料包括郵件內容中包含的名稱、電子郵件、IP 位址和個人資料。 Cloudinary，Inc.：由使用者提交的檔案型客戶內容。 Elasticsearch，Inc.：記錄的應用程式事務性事件可能包含來自客戶內容的截斷文字。 縫合，Inc.：連絡人資訊、使用資訊、訂閱者授權使用者的非傳統識別碼，以及訂閱者或其授權使用者提交至平臺的任何其他個人資料。 Mode Analytics，Inc.： User 識別碼 (s) 資訊，以提供每位使用者的 Analytics。 DataDog：已記錄應用程式的事務性事件可能包含來自客戶內容的截斷文字;記錄保留為14天。 Fullstory，Inc.：在 web 使用者介面上進行的動作錄製;包括分支的使用者帳戶，以供識別之用。 |  | 我們正在使用 Bot 架構 REST API。 我們使用此 API 來傳送和接收郵件至 askSpoke bot 服務。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 它可讓 atSpoke 同步處理使用者 Microsoft Teams 以建立使用者及定義許可權。 | atSpoke 只會儲存電子郵件，讓 Microsoft Teams 使用者能夠以有效的使用者身分登入 atSpoke。 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>包含在我們的應用程式記錄檔中，有使用者的名字和姓氏、使用者的電子郵件地址，以及 Azure 指派給使用者和群組的物件識別碼。 記錄檔只會在14天內保留，點會自動到期。 記錄存取受到保護，且只有特定人員可以存取記錄。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>應用程式資料儲存在受管理的 MongoDB 實例中。 存取受管理的服務阿特拉斯 MongoDB 資料庫是透過要求核准的標準化使用者存取要求流程進行布建。 定期使用者存取檢查會以管理簽發來執行。 我們會限制存取機密客戶資料的人員人數，而不允許直接從任何機器修改資料。 &#8232; 遠端存取此資料庫需要多重要素驗證。 使用 AES-256 位加密時，會以靜態加密資料庫及所有備份。


#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

