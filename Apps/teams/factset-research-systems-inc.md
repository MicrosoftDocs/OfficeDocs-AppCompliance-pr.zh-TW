---
title: FactSet by FactSet 調研系統 Inc. 的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 09/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: FactSet 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 98d1ef93eb2b64da517c47306d1779b40d1a6c83
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785408"
---
# <a name="factset"></a>FactSet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年9月23日</p>

* <a href="https://teams.microsoft.com/l/app/95fb5da0-6ced-4247-9d62-294f8fcb75df" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002146" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

FactSet 調查系統 Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | FactSet |
| ID | WA200002146 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | FactSet 調查系統 Inc.。 |
| 合作夥伴網站的 URL | [https://www.factset.com](https://www.factset.com) |
| 隱私權原則的 URL | [https://www.factset.com/privacy](https://www.factset.com/privacy) |
| 使用條款的 URL | [https://www.factset.com/hubfs/Misc/FactSet%20Teams%20Terms%...](https://www.factset.com/hubfs/Misc/FactSet%20Teams%20Terms%20of%20Use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

FactSet 調研系統 Inc. 已提供此資訊。關於此應用程式如何收集和儲存組織資料，以及您的組織將會對應用程式所收集的資料所做的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 應用程式 | 用於驗證及記錄的名稱和電子郵件、用於主動訊息傳送的交談識別碼 | 用於驗證及記錄的名稱和電子郵件、用於主動訊息傳送的交談識別碼 | [95fb5da0-6ced-4247-9d62-294f8fcb75df](https://docs.microsoft.com/microsoft-365-app-certification/azure/95fb5da0-6ced-4247-9d62-294f8fcb75df) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 用於驗證及記錄以及使用者支援的電子郵件和名稱。 | 電子郵件和名稱 | 用於驗證及記錄以及使用者支援的電子郵件和名稱。 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>FactSet 記錄中的使用者身分識別、E-Mail、名稱、使用狀況資料。 記錄有30天保留原則，而且會儲存資料庫&#160;，直到卸載應用程式為止。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>不適用

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

FactSet 調查系統 Inc. 已提供此資訊。關於此應用程式如何處理驗證、授權、application registration 最佳作法，以及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
