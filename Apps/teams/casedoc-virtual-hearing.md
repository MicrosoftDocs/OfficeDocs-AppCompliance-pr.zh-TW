---
title: Casedoc 的 Casedoc 虛擬聽覺應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Casedoc 虛擬聽覺的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 49c51cff0f00b33f25b22eb73bde4382be10c6ba
ms.sourcegitcommit: b97ed9e84303967085e6f3f93c80f7b97110194c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/29/2021
ms.locfileid: "59992143"
---
# <a name="casedoc-virtual-hearing"></a>Casedoc 虛擬聽覺

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年9月28日</p>

* <a href="https://teams.microsoft.com/l/app/3e701664-cc46-49e4-b356-1a7ac6500998" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003164" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Casedoc 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Casedoc 虛擬聽覺 |
| ID | WA200003164 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Casedoc |
| 合作夥伴網站的 URL | [https://www.casedoc.com](https://www.casedoc.com) |
| Teams 應用程式資訊頁面的 URL | [https://casedoc.com/virtual-hearing-for-teams/](https://casedoc.com/virtual-hearing-for-teams/) |
| 隱私權原則的 URL | [https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Priv...](https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Privacy_Policy_2021.pdf) |
| 使用條款的 URL | [https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Cust...](https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Customer_Agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Casedoc 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog ReadWrite。 | 委託 | 要新增至會議索引標籤的查閱應用程式 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| ReadWrite 的行事曆 | 應用程式 | 查閱清單使用者行事曆事件，用來顯示來自應用程式中事件的會議清單和資料。 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Directory.ReadWrite.All | 應用程式 | 未收集任何資料 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Files.ReadWrite.All | 應用程式 | 列出應用程式上傳的檔案 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Group.ReadWrite.All | 應用程式 | 未收集任何資料 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| MailboxSettings 讀取 | 應用程式 | 使用者郵件設定，時區。 用於為使用者顯示正確的時區 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| OnlineMeetings ReadWrite | 委託 | 會議資料已讀取和儲存，用來在應用程式中顯示會議資料 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadForUser | 委託 | 為使用者安裝的清單應用程式，用來將應用程式新增至會議] 索引標籤。 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadWriteForUser | 委託 | 用於將應用程式新增至會議] 索引標籤。 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab。建立 | 委託 | 用於將索引標籤新增至會議。 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab ReadWrite。 | 委託 | 用於將索引標籤新增至會議。 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| User.Read.All | 應用程式 | 用於為使用者尋找會議。 | 不儲存資料 | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>根據每個 ISM 原則進行的審計記錄、保留（ISO 27001）

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>不適用

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

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

Casedoc 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/> |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
