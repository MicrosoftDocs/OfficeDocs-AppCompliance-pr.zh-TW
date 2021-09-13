---
title: CoffeePals 的應用程式資訊（按 Carnduff Co）
ms.author: elmalova
author: elenamalova
ms.date: 07/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CoffeePals 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2f058ef9ce4f3d19644a6223c394afefa257085b
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278894"
---
# <a name="coffeepals"></a>CoffeePals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年7月9日</p>

* <a href="https://teams.microsoft.com/l/app/0905c41d-9f67-4ab7-8d94-4e2da3d2ff08" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003040" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Carnduff 與 Microsoft 共同提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | CoffeePals |
| ID | WA200003040 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Carnduff Co |
| 合作夥伴網站的 URL | [https://coffeepals.co](https://coffeepals.co) |
| Teams 應用程式資訊頁面的 URL | [https://coffeepals.co/product](https://coffeepals.co/product) |
| 隱私權原則的 URL | [https://coffeepals.co/privacy](https://coffeepals.co/privacy) |
| 使用條款的 URL | [https://coffeepals.co/terms-of-service](https://coffeepals.co/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Carnduff 相關提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Analytics、Stripe、Mailchimp、Heroku、MongoDB 阿特拉斯、AWS、Logentries | 使用者的電子郵件地址、支付資訊 (由 stripe) 、名字和姓氏來處理 | 我們已付費應用程式，因此需要信用卡資訊和連絡人資訊。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 我們存取其名稱，以在郵件中，參考與使用者一起輸入咖啡和儲存電子郵件地址的郵件，將其登入 web 應用程式，以收集付款。 使用其名稱可讓體驗更具個人化，我們會使用電子郵件地址做為唯一的識別碼，並將其傳送到登入的連結。 | 電子郵件地址、名字和姓氏。 | 會儲存資料，因此不需要在每次需要時都要對其進行比對，以進行比對，郵件和登入使用者。 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>如果有來自錯誤的資料遺失，我們便可以修改系統中的資料。 我們也可以在客戶提出要求時，新增及移除資料。 我們遵循中的嚴格資料保護通訊協定概要 https://coffeepals.co/security 。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41839' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41839" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊已透過 Carnduff 相關資訊共同提供此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
