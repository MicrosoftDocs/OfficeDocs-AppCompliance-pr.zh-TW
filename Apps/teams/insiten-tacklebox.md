---
title: TackleBox 的應用程式資訊（按 Insiten）
ms.author: elmalova
author: elenamalova
ms.date: 01/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: TackleBox 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f141d645dddf16f57f5ba8097cd1924f7e561462
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252513"
---
# <a name="tacklebox"></a>TackleBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年1月12日</p>

* <a href="https://teams.microsoft.com/l/app/dc37dab6-b497-4259-9aad-e40bfa023796" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002310" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Insiten 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | TackleBox |
| ID | WA200002310 |
| 功能 | 索引標籤，連接器 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Insiten |
| 合作夥伴網站的 URL | [https://tacklebox.app/](https://tacklebox.app/) |
| Teams 應用程式資訊頁面的 URL | [https://tacklebox.app](https://tacklebox.app) |
| 隱私權原則的 URL | [https://tacklebox.app/privacy/](https://tacklebox.app/privacy/) |
| 使用條款的 URL | [https://tacklebox.app/terms/](https://tacklebox.app/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Insiten 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 委託 | 允許使用者流覽其 OneDrive 磁片磁碟機、資料夾及檔案;將檔案連結到 TackleBox;讀取 Excel 檔案，以自動解壓縮圖表、圖表、表格、列印範圍及命名範圍;使用下列 Excel 視覺效果建立及更新 PowerPoint 檔案 | 磁片磁碟機識別碼、資料夾識別碼、檔案識別碼、View 連結、建立者、建立日期、修改者、修改日期、版本識別碼、檔案名 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| Sites.Read.All | 委託 | 允許使用者流覽及連結位於私人 Teams 通道的 Excel 檔案 | 無 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| User.Read | 委託 | 允許此應用程式讀取已登入使用者的設定檔，並檢索其電子郵件地址以取得通知 | 電子郵件 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| openid | 委託 | 允許使用者使用 Microsoft 365 帳戶登入我們的應用程式 | 使用者的租使用者識別碼及物件識別碼 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |
>| profile | 委託 | 允許應用程式顯示使用者的基本設定檔 (名稱、使用者名稱) 以 faciliate 共同作業 | UPN、名字、姓氏 | 485936ec-d15d-4a17-9f7d-2eeb5ea43b94 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>電子郵件地址和帳戶名稱。 停用帳戶和相關的使用者詳細資料會在3個月後清除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>不適用-所有資料都儲存在 Microsoft Azure

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35957" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Insiten 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

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
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
