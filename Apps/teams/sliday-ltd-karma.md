---
title: Karma by Sliday 有限公司的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Karma 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 781e9e6fd3ece314f2175fc23c116e6cf2a2b6b6
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430151"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Sliday 有限公司提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Karma |
| ID | WA104381640 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Sliday LTD |
| 合作夥伴網站的 URL | [https://sliday.com](https://sliday.com) |
| Teams 應用程式資訊頁面的 URL | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| 隱私權原則的 URL | [https://karmabot.readme.io/docs/privacy-policy-for-microsof...](https://karmabot.readme.io/docs/privacy-policy-for-microsoft-teams) |
| 使用條款的 URL | [https://karmabot.readme.io/docs/terms-and-conditions](https://karmabot.readme.io/docs/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Sliday 有限公司會提供此資訊，告知有關此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 應用程式 | 名字、姓氏及公司電子郵件地址。系統管理員報告的名字和姓氏。用於通訊的電子郵件地址，Karma、計費目的及 herarchy。 | 系統管理員同意顯示名稱。登入和讀取使用者設定檔。管理員同意描述。允許使用者登入 app，並允許此應用程式讀取登入使用者的設定檔。 它也可讓應用程式讀取已登入使用者的基本公司資訊。使用者同意顯示 nameSign 您在和閱讀您的設定檔。使用者同意描述。可讓您使用您的組織帳戶登入應用程式，並讓應用程式閱讀您的設定檔。 它也可讓應用程式讀取基本公司資訊。 | [9ff28b02-ccc5-4cac-9d17-4cf6987c371f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9ff28b02-ccc5-4cac-9d17-4cf6987c371f) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 「名字」、「姓氏」和「公司的電子郵件地址」名字、「系統管理」的「系統管理員隸屬于」的名字。 Karma 的通訊。 名單是計費目的所需的，可將大量使用者分割成不同的 departaments。 | 「名字」、「姓氏」和「公司的電子郵件地址」名字和「系統管理」報告的名字。 Karma、計費目的和 Karma 使用者階層中的通訊電子郵件地址。 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們會將租使用者識別碼和使用者識別碼儲存在記錄檔中。 兩者皆無法辨識。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>1. **是否已部署任何 DLP 解決方案？如何執行什麼以避免資料洩漏？**

是，資料會在傳輸和靜止時加密。

2. **您執行哪些類型的機制，以確保資料完整性針對錯誤、損毀或誤用以及其控制頻率進行保護**

所有伺服器都執行硬體 RAID，具有不同的 RAID 層級，但在每個案例中，都需要多個磁片磁碟機故障，才會發生資料遺失。 我們會有額外的安全性，而且同時具有自動和手動備份。 資料庫會每日自動備份並儲存7天。
Vm 會每週自動備份並儲存1個月。

**快照和備份儲存在內部的非公開可見網路上。**

3. **說明如何確保客戶的資料與多承租人解決方案中的其他客戶正確隔離，以及如何控制非實際執行環境中未複製或使用的實際執行資料**

儲存在不同的資料庫中。

4. **您建議哪些類型的加密 (演算法、通訊協定、金鑰長度) 傳輸中的資料和靜態資料**

所有傳輸中的資料都是以 TLS 或 SSL 加密。 HTTP 是由 SSL 加密的 TLS 1.2 或 TLS 1.3 資料庫流量所加密。

資料儲存在 US 資料中心的數位海運雲端中心。

5. **說明如何管理唯一的加密金鑰 (處理、儲存、使用狀況、RACI、SOD) 供您自行使用，以及每個承租人。**

由數位海運處理。

6. **描述存取管理程式在提供者結束時，指出如何及時移除不再需要的存取，以及您如何控制工作角色的許可權是否夠用。同時描述重新驗證程式及其執行頻率**

我們使用雙因素驗證來存取控制台。 只有3個人可以存取這種情況，我們每月變更密碼，保留存取記錄，並確保使用者不再與我們一起移除其帳戶從平臺移除。

7. **提供在您結束時所執行的程式，以管理共用識別碼 (例如 root、Sys、System 等等 ) 、Group IDs (一般帳戶（屬於同一個小組的數個個體），例如) 和本機帳戶。說明如何限制、記錄及監視特權帳戶的使用方式和存取安全裝置 (例如，虛擬機器器、防火牆、弱點掃描程式、網路嗅探器、APIs 等 ) 、如何確保使用者變更小組或離開後，就無法再存取群組識別碼，以及這類 IDs 的可追溯性層級。**

我們使用1Password 共用共用識別碼&#8217;s，每當共用資源從共用密碼庫存取時，我們就會有個別的活動摘要。 除非絕對必要，否則請不要使用共用帳戶，而是使用個別帳戶。 無法透過共用登入來存取 Karma 資料庫的任何資訊。 2FA 是用來存取1Password，以取回個別登入。

8. **描述處理方式，以確定及監控責任劃分方式及控制頻率。**

我們會執行每月會議，涵蓋責任劃分、專用登入的重要性，以及可能的所有登入2FA。

我們的 SIEM 包含：防火牆記錄、網頁伺服器記錄檔和應用程式記錄。 SIEM 是在每天和接收時進行分析。 記錄會保留1個月，然後在該時間之後安全移除。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

