---
title: DisasterTech 的應用程式資訊 DisasterTech 骰子
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: DisasterTech 骰子的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: fd0c7aeda8b245db0b222ffcfd4d59deb3d0374d
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411067"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月24日</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 DisasterTech 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | DisasterTech DICE |
| ID | WA200001909 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | DisasterTech |
| 合作夥伴網站的 URL | [https://www.disastertech.com](https://www.disastertech.com) |
| 隱私權原則的 URL | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| 使用條款的 URL | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 DisasterTech 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | 儲存以用於建立存取權的使用者電子郵件地址，以及用以識別使用者名稱的使用者名稱 | 允許使用者登入並提供其 UPN 的應用程式存取權，以啟用無訊息登入，以及 Teams 登入，也可以建立使用者名稱和電子郵件地址。 | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| 電子郵件 | 委託 | 無 | Teams 單一 Sign-On 是必要的 | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| offline_access | 委託 | 無 | Teams 單一 Sign-On 是必要的 | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| openid | 委託 | 無 | Teams 單一 Sign-On 是必要的 | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| 設定檔 | 委託 | 無 | Teams 單一 Sign-On 是必要的。 | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們會將使用者名稱、名字和姓氏儲存于 Azure 所主控的 PostgreSQL 資料庫中，以允許使用者在應用程式中共同作業。 這些控制項是只有「只有「嚴重的技術」員工才能直接存取資料庫。 當使用者從應用程式中移除時，我們會封存此資訊。 使用者可以隨時保留從系統移除其個人資料的權利。 不過，移除這類資訊也會禁止使用此應用程式。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>應用程式資料儲存在 Azure 的 PostgreSQL 資料庫中，該資料庫在靜止時會加密。 沒有使用者可以直接存取資料庫或後端 API。 所有的 API 通話都會以 Active Directory 存取權杖加以保護。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


