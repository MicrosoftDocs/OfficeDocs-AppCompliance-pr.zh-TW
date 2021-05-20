---
title: Solutions2Share 的應用程式資訊 Teams 管理員 GmbH
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Teams 管理員的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f941df5497b74f3558a56c0407456b42f3b2095d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552764"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Solutions2Share GmbH 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Teams Manager |
| ID | WA200000764 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Solutions2Share GmbH |
| 合作夥伴網站的 URL | [https://www.teams-manager.com](https://www.teams-manager.com) |
| 隱私權原則的 URL | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| 使用條款的 URL | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Solutions2Share GmbH 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 包括 | 我們正在儲存 TenantID 和 TeamId，以對應範本。  | 允許列出所有 Teams，也可建立 Teams。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| ReadWrite。 | 應用程式 | 無 | 允許此應用程式將筆記本新增至核准的小組。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read | 委託 | 無 | 允許使用者登入並提供其 UPN 的應用程式存取權，以啟用無訊息登入。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read.All | 包括 | 我們會儲存在 [核准者/admin] 區段中輸入的使用者識別碼。 | 列出所有使用者，以在應用程式內的 [人員選擇] 中顯示這些使用者。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.ReadBasic.All | 委託 | 無 | 列出所有使用者，以在應用程式內的 [人員選擇] 中顯示這些使用者。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們正在登入 Azure 記錄分析，並使用其封存/保留原則。
我們正在記錄租使用者識別碼和團隊識別碼，以找出問題，並協助客戶解決問題。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們有存取控制的規範和工作處理程式。 所有使用者相關資料和權杖都會加密。 資料儲存在 Azure SQL Database。 我們正在使用防火牆，只允許系統) 間的特定 ip (受保護的 IP 範圍的連線。 我們已于 Azure 中啟用 PMA) 的特殊許可權存取 (管理。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

