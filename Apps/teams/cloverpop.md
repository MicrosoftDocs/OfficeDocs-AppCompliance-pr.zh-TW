---
title: Cloverpop 的應用程式資訊（按 Cloverpop）
ms.author: elmalova
author: elenamalova
ms.date: 08/04/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Cloverpop 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 28d424f384d8b16ff70e7d00f366c3a0f89f64b5
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412513"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月24日</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Cloverpop 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Cloverpop |
| ID | WA200001803 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Cloverpop |
| 合作夥伴網站的 URL | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| 隱私權原則的 URL | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| 使用條款的 URL | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Cloverpop 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | 儲存類似的使用者資料。 email，oid，givenName，familyName，使用者頭像，使用者物件識別碼。組織識別碼 (tenantId) ，組織顯示名稱，也是存放在我們的側面團隊/管道名稱、識別碼、小組成員。 當使用者建立並與其互動時，我們會將此資料與建立該資料的使用者、小組和組織相關聯。 我們也需要在人類友好 UX 中顯示此擁有權，因此會儲存顯示資訊，例如使用者&#8217;的頭像。 | 允許使用者登入並提供其 UPN 的應用程式存取權，以啟用無訊息登入&#8221;-電子郵件、名稱、oid、tid、givenName、姓、familyName、使用者頭像 (photo) 、組織 displayName | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| openid | 委託 | 儲存類似的使用者資料。 email，oid，givenName，familyName，使用者頭像，使用者物件識別碼。組織識別碼 (tenantId) ，組織顯示名稱，也是存放在我們的側面團隊/管道名稱、識別碼、小組成員。 當使用者建立並與其互動時，我們會將此資料與建立該資料的使用者、小組和組織相關聯。 我們也需要在人類友好 UX 中顯示此擁有權，因此會儲存顯示資訊，例如使用者&#8217;的頭像。 | 若要在 web 應用程式上使用 Teams&#8221; 來執行 &#8220;登入。 | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| 設定檔 | 委託 | 儲存類似的使用者資料。 email，oid，givenName，familyName，使用者頭像，使用者物件識別碼。組織識別碼 (tenantId) ，組織顯示名稱，也是存放在我們的側面團隊/管道名稱、識別碼、小組成員。 當使用者建立並與其互動時，我們會將此資料與建立該資料的使用者、小組和組織相關聯。 我們也需要在人類友好 UX 中顯示此擁有權，因此會儲存顯示資訊，例如使用者&#8217;的頭像。 | 若要在 web 應用程式上使用 Teams&#8221; 來執行 &#8220;登入。 | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 我們會存取第一個/最後一個/顯示名稱資料，以準確顯示特定使用者針對決策所採取的動作。 我們會使用電子郵件地址做為資料庫中每個使用者的唯一識別碼，因為我們可讓每位使用者隸屬于多個組織。 我們只會存取此資料與我們的應用程式互動時，例如，如果他們回應投票。 | 我們會儲存第一個/最後一個/顯示名稱資料，以準確顯示特定使用者針對決策所採取的動作。  我們會儲存電子郵件地址，因為我們會將其當作 db 中每位使用者的唯一識別碼，讓每一位使用者都屬於多個組織。 我們只會儲存此資料與我們的應用程式互動時，例如，如果他們回應投票。 我們的決策資料應為決策的記錄系統，因此請務必儲存資料，以識別每個使用者對該決策的參與。 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>是。
當我們的應用程式與小組進行互動時，我們的記錄會顯示小組識別碼。
我們將實際執行記錄的存取許可權制于所有以美國為基礎的三個 founders

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>Cloverpop 應用程式是使用 Ruby on Rails，主控于 Heroku PaaS (平臺上，作為服務) ，其利用 AWS 來進行雲端基礎結構。 Heroku 和 AWS 都有可存取的 SOC 報告。 我們的應用程式使用 PostgreSQL 在 rest 資料儲存區進行加密，而且是一個多租使用者環境。
 
我們所有的程式碼都有為其撰寫的自動化測試，包含資料存取安全性。 每個組建都會經歷嚴格的安全性審核程式碼和手動 QA 測試程式，也包括透過可用使用者動作進行使用者驗證及資料存取的檢查。 我們的實際執行環境和所有其他環境（如開發和測試）之間有明確的分隔。
 
只有選取的人員才能存取實際執行環境和資料庫：公司 founders，以及少量的經員工，其已完成背景檢查，且具有定量需求 (例如客戶支援) 。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


