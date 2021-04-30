---
title: StarLeaf 的應用程式資訊（按 StarLeaf）
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
description: StarLeaf 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 99fa034d595c4f45dbea4d706278d1e71d258683
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092714"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月24日</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 StarLeaf 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | StarLeaf |
| ID | WA200000185 |
| 功能 | Bot，傳訊擴充功能 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | StarLeaf |
| 合作夥伴網站的 URL | [https://www.starleaf.com](https://www.starleaf.com) |
| 隱私權原則的 URL | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| 使用條款的 URL | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 StarLeaf 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 應用程式 | 我們會透過使用 Office.js 自訂屬性介面，存放會議的會議、出席者電子郵件地址和單一值擴充屬性，以及我們在會議上進行讀取和寫入的 iCalUId。 ICalUId 是用來將使用者&#8217;的 outlook 行事曆中的會議與我們服務上的視訊會議關聯。 您可以使用時間/日期和出席者，及時為服務上的適當人員提供影片會議。 SVEP 是用來與我們的 O365 增益集搭配使用，以提供一個介面，讓使用者可以在我們的服務（如錄製）上設定有關影片會議的詳細資料。 | 用於訂閱 webhook 通知，以追蹤使用者對其行事曆中的事件所做的變更，並更新我們的服務，使其保持一致。 當使用者與我們的 Teams 應用程式互動，並在我們的服務上排程會議時，也可以用來在行事曆中建立事件。 | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | 應用程式 | 我們會儲存 oauth 重新整理權杖，以供登入。 我們會儲存使用者設定檔 id，以與該使用者未來的 OAuth 嘗試進行比較，並確定我們不&#8217;t 儲存其詳細資料兩次。  | 允許使用者登入 app，並允許我們的應用程式取得使用者&#8217;的電子郵件地址，將其登入與我們的服務上的帳戶關聯。  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 如果發生技術支援問題，則 organisational 資料可能會轉接至 SalesForce，以進行案例管理。 如果使用者使用 PSTN 撥入功能，則通話會透過 Twilio、Plivo 或 Voxbone 進行傳遞。 |  | 不適用 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot 會存取小組名單，以代表透過 bot 預訂會議的使用者/主機預訂會議。 這可讓 StarLeaf 透過單一按鈕加入會議，以提供無縫的加入體驗。 | 名字、姓氏、電子郵件地址。 這可讓 StarLeaf bot 代表已與 bot 互動的使用者/主機預訂會議，並邀請團隊的其他成員參與會議。 |  |



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>可以。 記錄包括使用者名、IP 位址、通話詳細資料記錄、有關連線品質 (封包遺失、高比特) 、裝置類型、通話進度的資訊。 資訊可供技術支援小組和資深開發人員用來診斷服務問題。 資料會在90天之後 anonymised。 保護此資料的控制項會在我們的 ISO/IEC 27001 認證下進行審核。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料儲存在使用者&#8217;帳戶所在之資料中心的 StarLeaf&#8217;s 個人記錄伺服器上，並備份至相同司法轄區內的一或多個資料中心。 存取資料的方式是個別使用者帳戶，其使用的每位使用者密碼都會受到強度檢查。 StarLeaf&#8217;s 服務使用者帳戶會自動針對 HR 系統和公司 Active Directory 群組進行審核，以警示安全性與合規性小組如果發現異常。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

