---
title: 由開發人員 InStation 的應用程式資訊 Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: InStation 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552244"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月6日</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Invillia 至 Microsoft 的開發人員提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | InStation |
| ID | WA200001701 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Developers Invillia |
| 合作夥伴網站的 URL | [https://instation.invillia.com/](https://instation.invillia.com/) |
| 隱私權原則的 URL | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| 使用條款的 URL | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由開發人員提供的 Invillia，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings Read。 All | 委託 | 儲存區：識別碼、join_url、join_web_url 及 chat_id。 允許應用程式建立會議 | 儲存區：識別碼、join_url、join_web_url 及 chat_id。 允許應用程式建立會議 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings ReadWrite。 | 委託 | 儲存區：識別碼、join_url、join_web_url 及 chat_id。 允許應用程式建立會議 | 儲存區：識別碼、join_url、join_web_url 及 chat_id。 允許應用程式建立會議 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| 顯示狀態。讀取 | 委託 | 允許此應用程式在第一步登入組織 | 活動和可用性。 允許此應用程式捕獲使用者狀態; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| 目前狀態為 [已讀取]。 | 委託 | 允許此應用程式在第一步登入組織， | 活動和可用性。 允許此應用程式捕獲使用者狀態; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | 委託 | 儲存：識別碼、郵件、顯示名稱、姓和圖片。 允許此應用程式搜尋使用者資料; | 儲存：識別碼、郵件、顯示名稱、姓和圖片。 允許此應用程式搜尋使用者資料; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | 委託 | 儲存：識別碼、郵件、顯示名稱、姓和圖片。 允許此應用程式搜尋使用者資料; | 儲存：識別碼、郵件、顯示名稱、姓和圖片。 允許此應用程式搜尋使用者資料; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| 電子郵件 | 委託 | 允許此應用程式在第一次登入時，對系統管理員&#180;基本資訊進行記錄 | 允許此應用程式在第一次登入時，對系統管理員&#180;基本資訊進行記錄 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | 委託 | 儲存區： token 和重新整理權杖。 允許此應用程式在 MS token 上執行重新整理 | 儲存區： token 和重新整理權杖。 允許此應用程式在 MS token 上執行重新整理 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | 委託 | 允許此應用程式在第一步登入組織 | 允許此應用程式在第一步登入組織 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| profile | 委託 | 允許此應用程式在第一次登入時，捕獲管理員&#180;基本資訊; | 允許此應用程式在第一次登入時，捕獲管理員&#180;基本資訊; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們只會儲存應用程式內的使用者使用方式記錄。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們只會儲存應用程式內的使用者使用方式記錄。 無機密，不需要加密，而且僅自己們的特定系統管理員才能存取此資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

