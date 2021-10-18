---
title: Solutions2Share 的應用程式資訊 Teams 管理員 GmbH
ms.author: elmalova
author: elenamalova
ms.date: 09/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Teams 管理員的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bd7be587324879df814c495f4f88d2ed8deddf30
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60423090"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年9月24日</p>

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
| 合作夥伴網站的 URL | [https://teams-manager.com](https://teams-manager.com) |
| Teams 應用程式資訊頁面的 URL | [https://teams-manager.com](https://teams-manager.com) |
| 隱私權原則的 URL | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| 使用條款的 URL | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Solutions2Share GmbH 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | 包括 | 我們正在儲存 TenantID 和 TeamId，以對應範本。  | 允許列出所有 Teams，也可建立 Teams。 | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| ReadWrite。 | 應用程式 | 無 | 允許此應用程式將筆記本新增至核准的小組。 | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read | 委託 | 無 | 允許使用者登入並提供其 UPN 的應用程式存取權，以啟用無訊息登入。 | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read.All | 包括 | 我們會儲存在 [核准者/admin] 區段中輸入的使用者識別碼。 | 列出所有使用者，以在應用程式內的 [人員選擇] 中顯示這些使用者。 | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.ReadBasic.All | 委託 | 無 | 列出所有使用者，以在應用程式內的 [人員選擇] 中顯示這些使用者。 | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |


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

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由 Solutions2Share GmbH 提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 否 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/> |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
