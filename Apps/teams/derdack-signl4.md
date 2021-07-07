---
title: SIGNL4 的應用程式資訊（按 Derdack SIGNL4）
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: SIGNL4 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 425c0738b5628f959ba81e5682c22afe6774cfba
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281325"
---
# <a name="signl4"></a>SIGNL4

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月6日</p>

* <a href="https://teams.microsoft.com/l/app/bd19c878-00b7-47cd-9b65-74a2def84427" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001239" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Derdack SIGNL4 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SIGNL4 |
| ID | WA200001239 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Derdack SIGNL4 |
| 合作夥伴網站的 URL | [https://www.derdack.com](https://www.derdack.com) |
| 隱私權原則的 URL | [https://www.signl4.com/privacy-policy/](https://www.signl4.com/privacy-policy/) |
| 使用條款的 URL | [https://www.signl4.com/terms_of_use/](https://www.signl4.com/terms_of_use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Derdack SIGNL4 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Recurly、電子郵件地址、電子郵件地址是在使用此應用程式時，向客戶傳送帳單通知時所需的電子郵件地址。 Twilio、電話號碼、透過 SMS 文字郵件傳送提醒的警示內容 |  | Azure 管理 API 會收集 Azure 監視器警示，因為系統會傳送這些警示的通知，所以發生收集。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>電子郵件地址資訊會包含在記錄檔中。 其他由組織提交的警示內容資料也可能會包含在記錄檔中。 若要避免這種情況，組織可以終止應用程式中的帳戶。
記錄中的資料是客戶 ma 對應用程式的支援和疑難排解問題所需的。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料會儲存在歐洲的 Azure 資料中心。 管理員可以存取。 使用 AAD 驗證的2FA。 存取儲存體帳戶的金鑰也可以用來管理存取。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

