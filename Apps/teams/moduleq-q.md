---
title: Q 的應用程式資訊 ModuleQ
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于 Q 的安全性和符合性資訊資訊、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2bdf876ddb9ab17d9fa8616edda8b849e0d85df7
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281746"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2020年3月17日</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 ModuleQ 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Q |
| ID | WA104381433 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | ModuleQ |
| 合作夥伴網站的 URL | [https://moduleq.com](https://moduleq.com) |
| 隱私權原則的 URL | [https://moduleq.com/privacy-policy](https://moduleq.com/privacy-policy) |
| 使用條款的 URL | [https://moduleq.com/terms-of-service](https://moduleq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 ModuleQ 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 應用程式 | 儲存會議資料，但不包括郵件內文和任何附件 | 允許應用程式讀取使用者的行事曆事件，以便智慧瞭解使用者的業務優先順序。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | 委託 | 無 | 允許此應用程式在小組中互動以共用內容。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | 應用程式 | 儲存電子郵件資料，但不包括郵件內文和任何附件 | 允許應用程式讀取使用者的郵件，以便智慧瞭解使用者的業務優先順序 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | 委託 | 使用者電子郵件和驗證權杖 | 允許使用者使用 ModuleQ 帳戶登入及連結其 Office 365 帳戶 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | 委託 | 無 | 允許此應用程式取得使用者所屬的 Teams 清單。 僅用於共用  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們會記錄內部使用者 GUID 和組織名稱及網域。 目前沒有任何「封存」或「刪除」控制。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料會根據其功能，在多個 microservices 中儲存在 Microsoft Azure 雲端。 所有使用者識別的資料都是加密用戶端，並在傳輸儲存之前，使用 AES-256 加密。 透過資深管理的核准，工程師可以查看資料進行調試的目的。 存取資料是透過內部 VPN 來控制。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

