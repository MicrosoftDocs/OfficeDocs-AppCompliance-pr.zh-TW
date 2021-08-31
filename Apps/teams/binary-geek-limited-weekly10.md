---
title: Weekly10 依二進位 Geek 限制的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Weekly10 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3a1456ccf706a9588f82e38ea35e5e37f8098b9b
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673060"
---
# <a name="weekly10"></a>Weekly10

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月19日</p>

* <a href="https://teams.microsoft.com/l/app/c80cee99-d17f-4b2d-a2a4-57652ffd2a4b" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001441" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

二進位 Geek 提供的資訊僅限 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Weekly10 |
| ID | WA200001441 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 二進位 Geek 限制 |
| 合作夥伴網站的 URL | [https://www.weekly10.com](https://www.weekly10.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.weekly10.com/integrations/microsoft-teams/](https://www.weekly10.com/integrations/microsoft-teams/) |
| 隱私權原則的 URL | [https://www.weekly10.com/terms/privacy](https://www.weekly10.com/terms/privacy) |
| 使用條款的 URL | [https://www.weekly10.com/terms/customer](https://www.weekly10.com/terms/customer) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由二進位 Geek 提供的，此應用程式會限制此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **權限**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 應用程式 | 將使用者從 Azure AD 同步到 Weekly10 (選用)  | 使用者身分識別資料：使用者主要名稱、電子郵件、名字、姓氏和主管。 | [2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb](https://docs.microsoft.com/microsoft-365-app-certification/azure/2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb) |
>| ReadWrite 的行事曆 | 應用程式 | 檢查員工可用性和自動預約會議 (選用) 。 | 員工的使用時間 (不詳細資料) 和會議已預約對該會議的參照。 這項資料可用於瞭解員工是否已脫銷，以順利員工體驗，並將會議預訂1：1s 或績效審查。 | [494610b2-b490-4f54-8384-312d6f9b4869](https://docs.microsoft.com/microsoft-365-app-certification/azure/494610b2-b490-4f54-8384-312d6f9b4869) |
>| User.Read | 委託 | Azure AD 上用於 SSO 目的的使用者驗證。 | 除了權杖資訊之外，不會保留任何額外的資料。 | [6fd1421e-89e8-4a8b-bd01-9397656a50d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fd1421e-89e8-4a8b-bd01-9397656a50d5) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 我們只會存取個人的 Teams 使用者識別碼。 這表示 bot 可以在該使用者的特定方式中回應。 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>在報告的錯誤或問題事件中的組織名稱和使用者名稱。 記錄檔的儲存格式為30天，然後刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>位於 Weekly10 中的所有資料都可以由指定的系統管理員控制。 變更 Weekly10 中的原則時，會直接影響用戶端資料) 所在 Microsoft Azure (中的資料。

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

此資訊是由二進位 Geek 提供，此應用程式會限制此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
