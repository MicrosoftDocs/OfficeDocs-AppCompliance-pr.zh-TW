---
title: 透過 Witivio 學習的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊資訊，以瞭解資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 724ecb5bd0eb5365ea06af4fda0b51b4fd23b157
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52253244"
---
# <a name="learn"></a>了解

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2020年3月31日</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Witivio 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 了解 |
| ID | WA200001308 |
| 功能 | Bot，索引標籤 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Witivio |
| 合作夥伴網站的 URL | [https://www.witivio.com/learn](https://www.witivio.com/learn) |
| 隱私權原則的 URL | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| 使用條款的 URL | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Witivio 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委託 | 不適用 | 我們會收集授權的 UPN 和 AAD 識別碼。 | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| User.ReadBasic.All | 委託 | 不適用 | 我們會收集授權的 UPN 和 AAD 識別碼。 | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| openid | 委託 | 不適用 | 我們會收集授權的 UPN 和 AAD 識別碼。 | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| profile | 委託 | 不適用 | 我們會收集授權的 UPN 和 AAD 識別碼。 | 8c5c0060-2892-4355-b0db-661f206028a9 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 我們使用下列： 1) 授權 (授與對 bot 的存取權) ，2) 偵測 firstname，以提供友好 UX，3) 來管理 bot 之商務系統管理員的 chatlogs。 | N/A。 或 bot 只為個人 |  |



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>Bot 的遙測包含 UPN 和 AAD 識別碼 fr 診斷。
只有生產/執行系統管理員才能存取生產遙測。 記錄檔會儲存在90天內，而且可以在專屬入口網站 support.witivio.com 或透過電子郵件傳送至 dpo@witivio.com 時，加以刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>Witivio 只會使用在北歐地區部署的 Azure 元件。 我們使用 application 真知灼見和 Cosmos DB 進行資料分析和儲存。
Witivio 對所有使用者（包括系統管理員）使用 MFA。 系統管理員有 (工作站) 的使用者帳戶，以及存取 Azure ressources 的許可權帳戶。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

