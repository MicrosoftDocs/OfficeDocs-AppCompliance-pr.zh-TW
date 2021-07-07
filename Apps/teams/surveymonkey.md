---
title: SurveyMonkey 的應用程式資訊（按 SurveyMonkey）
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SurveyMonkey 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: daf5de5437a08ca8b748157a5e136bbe7b114122
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/02/2021
ms.locfileid: "53280815"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 SurveyMonkey 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SurveyMonkey |
| ID | WA104381088 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | SurveyMonkey |
| 合作夥伴網站的 URL | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| Teams 應用程式資訊頁面的 URL | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| 隱私權原則的 URL | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| 使用條款的 URL | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 SurveyMonkey 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 委託 | 否 | 若要提供群組/頻道清單，以與其共用調查 |  |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 只會在 SurveyMonkey 中儲存 MS 使用者識別碼，以便與小組使用者關聯回應與調查。 |  | 針對團隊，我們使用 [建立] 中的 Microsoft Teams javascript SDK，進行調查和調查結果任務模組模式。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 我們呼叫 v3/交談/{識別碼}/pagedmembers 以檢查是否已將應用程式新增至小組並取得成員計數。 它只是用於內部的使用追蹤，我們只會查看聊天名單的大小，其他資訊也會被忽略。 | 是的，聊天的大小會儲存 (單一整數)  |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>EUII-每當調查取得回應時，即會建立成功/失敗記錄，而且我們嘗試透過連接器將該回應傳送給 Teams，此記錄會包含資料庫中的 user_id、survey_id integration_id (，可用於查詢 ms 團隊識別碼、ms 使用者識別碼) 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們的主要資料中心位於拉斯維加斯的內華達州，NV 和我們的次要資料中心位於聖克拉拉的加州。 SurveyMonkey 擁有並運作其所有的伺服器和基礎結構在這些位置。 我們也為加拿大的某些 SurveyMonkey Enterprise 客戶提供加拿大的資料派駐服務。 所有資料在靜止時使用 TDE 與 AES256 加密，而且傳輸中的資料是以 TLS 1.2 加密。

SurveyMonkey 使用中央使用者驗證，以維護身分識別與存取管理。 這個系統會管理任何和所有公司、生產基礎結構、系統和服務的所有驗證及授權。 嚴格的存取原則會以每季維護和逐項查看。 這種檢查包含但不限於：使用者存取清單、原則群組和協力廠商存取評論。 若要存取我們的實際執行環境 (例如，若要取得特權帳戶) 、需要取得管理員核准、完成一些必要的培訓，以及取得我們的安全小組的核准。 在這個階段中，會布建其他 VPN 帳戶，這會將 &#8216;一般&#8217; 帳戶與 &#8216;特權&#8217; 帳戶區分開來。

只允許公司簽發的裝置存取我們的產品網路。 在安裝之前，所有無線廠商預設值都會變更，包括但不限於預設無線加密金鑰、密碼及 SNMP 群組字串。 您需要2FA 和 VPN，以遠端方式執行。 我們的公司辦公室有個別的 wifi 網路可用於來賓存取。

所有服務、通訊協定及允許的埠都必須有記錄的業務理由和核准，包括對那些以不安全的通訊協定所執行的安全性功能的使用。 路由器和防火牆會設定為將 IP 披露限制在未授權或非預期的各方，並且限制對 DMZ 防火牆內之 IP 位址的內送網際網路存取，且至少每六個月會檢查一次路由器規則集。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

