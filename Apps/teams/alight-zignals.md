---
title: Zignals 的應用程式資訊（按 Alight）
ms.author: elmalova
author: elenamalova
ms.date: 08/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zignals 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 313529eecfcf1e8e129bb22cb5ee4c7b53b9e2c5
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279270"
---
# <a name="zignals"></a>Zignals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月17日</p>

* <a href="https://teams.microsoft.com/l/app/a0b58ca7-958d-4343-a2dc-a75f2eeb0953" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003201" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Alight 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Zignals |
| ID | WA200003201 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Alight |
| 合作夥伴網站的 URL | [https://www.alight.eu](https://www.alight.eu) |
| Teams 應用程式資訊頁面的 URL | [https://zignals.eu/zignals-support/](https://zignals.eu/zignals-support/) |
| 隱私權原則的 URL | [https://www.zignals.eu/privacy-policy-zignals-for-teams/](https://www.zignals.eu/privacy-policy-zignals-for-teams/) |
| 使用條款的 URL | [https://zignals.eu/terms](https://zignals.eu/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Alight 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 委託 | 在我的 &quot; 會議區域中 &quot; ，我們會取得目前和未來的使用者會議。 | 不會在應用程式資料庫中儲存任何資訊。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Sites.ReadWrite.All | 委託 | 我們會取得所有使用者的 SharePoint 網站，並將其顯示在我的團隊合作區域中，並 &quot; &quot; 取得所有使用者的 SharePoint 任務，並將其顯示在「我的工作」區域中 &quot; &quot; 。 | 不會在應用程式資料庫中儲存任何資訊。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| 工作。 ReadWrite | 委託 | 我們會閱讀使用者的 Planner 並 To Do 工作，並將其顯示在 [我的工作] 區域中 &quot; &quot; 。 | 不會在應用程式資料庫中儲存任何資訊。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Team.ReadBasic.All | 委託 | 我們會取得使用者的加入小組，並將其顯示在「 &quot; 我的團隊合作」 &quot; 區域中。 | 不會在應用程式資料庫中儲存任何資訊。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadBasic.All | 委託 | 在 [我的文件] 區域中，我們會顯示其共同 &quot; &quot; 合作的使用者。 | 不會在應用程式資料庫中儲存任何資訊。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadWrite | 委託 | 使用者的最近檔會顯示在「我的檔」區域中 &quot; &quot; 。 使用者的最愛應用程式會在 MS Graph 中儲存為架構擴充。 在圖形中讀取及寫入資料時，需要此許可權等級。 | 不會在應用程式資料庫中儲存任何資訊。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| 電子郵件 | 委託 | 取得使用者電子郵件 (標準毫秒 Teams 範圍)  | 不是儲存在我們的 DB | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| offline_access | 委託 | 標準毫秒 Teams 範圍 | 不是儲存在我們的 DB | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| openid | 委託 | 登入使用者。 | 不會在應用程式資料庫中儲存任何資訊。 | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| 設定檔 | 委託 | 登入處理常式毫秒 Teams | 不是儲存在我們的 DB | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>僅將資料儲存在 Azure。 在這裡，我們使用系統管理員介面來控制資料 (包括刪除、審計等等 ) 

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

Alight 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
