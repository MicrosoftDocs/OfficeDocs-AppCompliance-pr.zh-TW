---
title: SHL 的應用程式資訊（按 SHL）
ms.author: elmalova
author: elenamalova
ms.date: 06/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SHL 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5c5b98779e7c038d809a8ecaee60fee1cdf0ca71
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278327"
---
# <a name="shl"></a>SHL

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月25日</p>

* <a href="https://teams.microsoft.com/l/app/0c52adc0-18a0-45ca-b6ee-154cf1ef87e2" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002887" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 SHL 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SHL |
| ID | WA200002887 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | SHL |
| 合作夥伴網站的 URL | [https://shl.com](https://shl.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.shl.com/en/about/](https://www.shl.com/en/about/) |
| 隱私權原則的 URL | [https://www.shl.com/en/privacy/administrator-data-protectio...](https://www.shl.com/en/privacy/administrator-data-protection-notice/) |
| 使用條款的 URL | [https://www.shl.com/en/terms-of-service/](https://www.shl.com/en/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 SHL 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 已讀取行事曆。共用 | 委託 | 可用的共用行事曆插槽 | NA | [afd2c390-8b78-40fa-913b-7fc5911e884a](https://docs.microsoft.com/microsoft-365-app-certification/azure/afd2c390-8b78-40fa-913b-7fc5911e884a) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 我們會將資料傳送到我們自己的應用程式的服務， (Talentcentral： https://talentcentral.eu.shl.com/admin) | EUII： Microsoft 團隊使用者名稱和團隊使用者識別碼 | Teams 應用程式中的使用者名稱是用於另一個應用程式，此應用程式會在其中觸發具有使用者名稱的電子郵件。 而且使用者識別碼會保留為識別碼，並將其對應至應用程式&#8217;s 使用者識別碼。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Teams 應用程式中的使用者名稱是用於另一個應用程式，此應用程式會在其中觸發具有使用者名稱的電子郵件。 而且使用者識別碼會保留為識別碼，並與我們的應用程式對應&#8217;s 使用者識別碼 | Microsoft 團隊使用者名稱和團隊使用者識別碼 | Teams 應用程式中的使用者名稱是用於另一個應用程式，此應用程式會在其中觸發具有使用者名稱的電子郵件。 而且使用者識別碼會保留為識別碼，並與我們的應用程式對應&#8217;s 使用者識別碼 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們不會控制資料，只會處理資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

SHL 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
