---
title: Aster 的應用程式資訊（按 Aster）
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Aster 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 10fcbb93f3d6e7b8c851b1f1ecaf63a57f4d1204
ms.sourcegitcommit: 874e586a5a9a5eb0c5c5aae0c59f7c75c0742ec4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/01/2021
ms.locfileid: "60080893"
---
# <a name="aster"></a>紫苑

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年9月28日</p>

* <a href="https://teams.microsoft.com/l/app/2d8e8042-66df-4605-8c3a-9ca8962f3e99" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002379" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Aster 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 紫苑 |
| ID | WA200002379 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 紫苑 |
| 合作夥伴網站的 URL | [https://asterapp.co](https://asterapp.co) |
| Teams 應用程式資訊頁面的 URL | [https://asterapp.co/solution/](https://asterapp.co/solution/) |
| 隱私權原則的 URL | [https://asterapp.co/politique-de-confidentialite/](https://asterapp.co/politique-de-confidentialite/) |
| 使用條款的 URL | [https://asterapp.co/conditions-generales/](https://asterapp.co/conditions-generales/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Aster 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 委託 | 傳送 Sharepoint 檔之 Planner 任務的目錄清單 | 無 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Group.ReadWrite.All | 委託 | 在現有或建立的群組中傳送 Sharepoint 檔的 Planner 任務的群組清單 | 無 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| ReadWrite。 | 委託 | 在 OneNote 中寫入的附注內容 | 無 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| ReadWrite 共同作業 | 委託 | Tasks、assignation、期限 | 同步處理 Graph API 任務與 Aster 工作的所有資料 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| User.Read | 委託 | 用於識別使用者的使用者電子郵件 | Assignations 中的使用者電子郵件範例（範例） | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| offline_access | 委託 | 未收集任何資料，僅供 seemlessly 重新整理權杖 | 無 | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 以人為 personnalized 的方式與使用者通訊 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>會記錄所有存取，並以使用者電子郵件來識別

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>RGPD 合約

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

Aster 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 否 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
