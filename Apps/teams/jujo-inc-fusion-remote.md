---
title: Jujo Inc. 的融合遠端應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和合規性資訊，用於融合的遠端、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b920e0fa93512c7cc9429b02dcecd9c0e3fe27b6
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521494"
---
# <a name="fusion-remote"></a>Fusion Remote

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2020年10月12日</p>

* <a href="https://teams.microsoft.com/l/app/efc5c93b-304e-48ae-a695-2edd81bf45fb" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001422" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Jujo Inc. 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Fusion Remote |
| ID | WA200001422 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Jujo Inc. |
| 合作夥伴網站的 URL | [https://www.jujotech.com](https://www.jujotech.com) |
| 隱私權原則的 URL | [https://www.jujothech.com/privacy-policy](https://www.jujothech.com/privacy-policy) |
| 使用條款的 URL | [https://www.jujotech.com/terms-of-use](https://www.jujotech.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Jujo Inc. 提供。關於此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | 委託 | 讀取使用者檔 | 讀取使用者檔 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.Read.All | 委託 | 讀取使用者可以存取的所有檔案 | 讀取使用者可以存取的所有檔案 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| 已讀取。選取 | 委託 | 讀取使用者選取的檔案 | 讀取使用者選取的檔案 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.ReadWrite | 委託 | 擁有使用者檔案的完整存取權 | 擁有使用者檔案的完整存取權 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| Files.ReadWrite.All | 委託 | 具有使用者可以存取的所有檔案的完整存取權 | 具有使用者可以存取的所有檔案的完整存取權 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| ReadWrite。 AppFolder | 委託 | 可以完全存取應用程式的資料夾 (預覽)  | 可以完全存取應用程式的資料夾 (預覽)  | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| ReadWrite。選取 | 委託 | 讀取及寫入使用者選取的檔案 | 讀取及寫入使用者選取的檔案 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.Read | 委託 | 登入並讀取使用者設定檔 | 登入並讀取使用者設定檔 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.Read.All | 委託 | 讀取所有使用者的完整設定檔 | 讀取所有使用者的完整設定檔 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.ReadBasic.All | 委託 | 讀取所有使用者的基本設定檔 | 讀取所有使用者的基本設定檔 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.ReadWrite | 委託 | 使用者設定檔的讀取和寫入權限 | 使用者設定檔的讀取和寫入權限 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| User.ReadWrite.All | 委託 | 讀取和寫入所有使用者的完整設定檔 | 讀取和寫入所有使用者的完整設定檔 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| offline_access | 委託 | 維護您有權存取資料的存取權限 | 維護您有權存取資料的存取權限 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |
>| openid | 委託 | 在中簽署使用者 | 在中簽署使用者 | [238d0bd1-fa0a-4bb6-be82-97f7f9ee590e](https://docs.microsoft.com/microsoft-365-app-certification/azure/238d0bd1-fa0a-4bb6-be82-97f7f9ee590e) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 會議名單 | 未儲存在 DB 中的資料 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料會在傳輸和靜止時加密。 PMA 是使用中的，系統管理員帳戶只可從有限的白名單 IPs 存取

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36077' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36077" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

