---
title: MindMeister 的應用程式資訊（按 MeisterLabs GmbH）
ms.author: elmalova
author: elenamalova
ms.date: 10/31/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: MindMeister 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6b36f41be86496cdca75a77d9564b2c13e5536b3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413705"
---
# <a name="mindmeister"></a>MindMeister

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/b66766e5-61ce-4001-b2e6-6817710d6d02" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381116" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 MeisterLabs GmbH 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | MindMeister |
| ID | WA104381116 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | MeisterLabs GmbH |
| 合作夥伴網站的 URL | [https://www.mindmeister.com](https://www.mindmeister.com) |
| Teams 應用程式資訊頁面的 URL | [https://support.mindmeister.com/](https://support.mindmeister.com/) |
| 隱私權原則的 URL | [https://www.mindmeister.com/privacy](https://www.mindmeister.com/privacy) |
| 使用條款的 URL | [https://www.mindmeister.com/terms](https://www.mindmeister.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 MeisterLabs GmbH 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | AADID、租使用者識別碼、email、displayName-用以識別應用程式內的每一位使用者，以及可以連結 MindMeister 特定資料與 Microsoft 使用者 (（即哪些對應屬於哪個使用者) ）。 | 允許使用者登入並提供其 UPN 的應用程式存取權，以啟用無訊息登入。 | [d312ff80-0c2b-42ad-887b-c6392bcf6353](https://docs.microsoft.com/microsoft-365-app-certification/azure/d312ff80-0c2b-42ad-887b-c6392bcf6353) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 識別 MindMeister 中已有連結的 Teams 使用者，並通知他們已安裝 bot。 | 我們不會儲存任何小組名單的資料 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>在某些情況下，我們會記錄使用者 HTTP 要求，包括使用者 IDs，但記錄會在7天之後刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料儲存在德國的安全伺服器上。 對此資料的存取權僅限於許多組織管理員，且具有2FA 強制存取權。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20874' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20874" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


