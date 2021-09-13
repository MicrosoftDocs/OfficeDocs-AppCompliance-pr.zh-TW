---
title: CSOD 的應用程式資訊透過基礎 OnDemand 來瞭解
ms.author: elmalova
author: elenamalova
ms.date: 07/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于 CSOD 的安全性和合規性資訊資訊，都是在 CSA 星型登錄中瞭解，其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 2064ed00ba6306d86a09b3eff9dc6e56c8d1cc40
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283883"
---
# <a name="csod-learn"></a>CSOD Learn

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年7月1日</p>

* <a href="https://teams.microsoft.com/l/app/81726ee9-4d27-47ad-8b22-08147c6f8613" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003020" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由基礎 OnDemand 向 Microsoft 提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | CSOD Learn |
| ID | WA200003020 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Cornerstone OnDemand |
| 合作夥伴網站的 URL | [https://www.cornerstoneondemand.com](https://www.cornerstoneondemand.com) |
| 隱私權原則的 URL | [https://www.cornerstoneondemand.com/client-privacy-policy/](https://www.cornerstoneondemand.com/client-privacy-policy/) |
| 使用條款的 URL | [https://www.microsoft.com/en-us/microsoft-teams/group-chat-...](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊已透過基礎 OnDemand 提供，關於此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 組織資料是在 CSOD 服務和 Microsoft 之間共用。 如需詳細資訊，請參閱 CSOD 的合約條款。 | 組織資料是在 CSOD 服務和 Microsoft 之間共用。 如需詳細資訊，請參閱 CSOD 的合約條款。 | CSOD 服務不會使用 Graph APIs。 我們使用 Microsoft framework botbuilder ^ 4.9.2 來取得服務的效能。 OII 資料是由服務使用，用以識別 CSOD 服務消費者。 如需詳細資訊，請參閱 CSOD 的合約條款。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 請參閱 CSOD 的合約條款，以取得此方面的資訊 | 終端使用者 aadObjectId 對應至 CSOD 使用者內部識別碼 | 請參閱 CSOD 的合約條款，以取得此方面的資訊 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>CSOD service 會儲存應用程式記錄檔，其中包含使用者與應用程式互動的時間有限的時段，可疑難排解錯誤及使用者報告的問題。 個別記錄語句是由使用者內部 lms 使用者識別碼、在 CSOD service 內設定的組織名稱以及執行的適當動作所組成。 v

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>存取 CSOD 服務是由使用者組織的系統管理員所控制。 如需詳細資訊，請參閱 CSOD 的合約條款。

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

有關此應用程式如何處理驗證、授權、application registration 最佳作法及其他身分識別準則的基石 OnDemand 已提供此資訊。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
