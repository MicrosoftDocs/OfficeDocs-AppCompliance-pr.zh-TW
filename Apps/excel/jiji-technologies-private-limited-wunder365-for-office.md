---
title: Wunder365 的應用程式資訊，由 JiJi 技術私人有限使用 Office
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Wunder365 Office 的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 22da4d3ff5dbfc02a1d9609b1d618a9d1b4d939c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414217"
---
# <a name="wunder365-for-office"></a>Office 的 Wunder365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2020月15日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001529" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

JiJi 技術所提供的資訊私人限制于 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Office 的 Wunder365 |
| ID | WA200001529 |
| 支援 Office 365 用戶端 | Excel 2016 或更新版本的 mac 上，Excel 2013 或更新版本上 Windows、Excel 網頁版、Word 2016 或更新 mac、Word 網頁版、Word 2013 或更新版本 Windows，OneNote 網頁版 |
| 合作夥伴公司名稱 | JiJi 技術私人有限 |
| 合作夥伴網站的 URL | [https://www.jijitechnologies.com](https://www.jijitechnologies.com) |
| 隱私權原則的 URL | [https://www.wunder365.com/office-addin-privacy-policy](https://www.wunder365.com/office-addin-privacy-policy) |
| 使用條款的 URL | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 JiJi 技術所提供，其私人限制此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | 委託 | 未儲存任何資料。 | 若要取得取得/更新 Planner 的工作，請在小組通道中發佈任務更新 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| 傳送郵件 | 委託 | 未儲存任何資料。 | 允許應用程式傳送電子郵件通知給使用者 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| offline_access | 委託 | 未儲存任何資料。 | 讓使用者保持登入。 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| openid | 委託 | 未儲存任何資料。 | 允許使用者以 organisational 帳戶登入 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| 設定檔 | 委託 | UPN，使用者識別碼，電子郵件識別碼，授權驗證的租使用者識別碼，免費授權。 | 允許使用者以 organisational 帳戶登入 | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們正在登入 Azure Application Insights。 我們正在記錄租使用者識別碼和使用者的電子郵件識別碼，以找出問題，並協助客戶解決問題。


#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>所有 Web 應用程式和儲存體資源都位於未連接到公司 AAD 的訂閱中，但只有具備資源存取權的系統管理員。 這些系統管理員需要2FA。 


#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由 JiJi 技術提供，其私人限制此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 需要具有系統管理角色之使用者的多重要素驗證，需要針對 Azure 管理工作執行多重要素驗證，以封鎖使用者嘗試使用舊版驗證通訊協定的登入，要求 Azure AD Multi-Factor 驗證登錄的信任位置，封鎖或授與特定位置的存取權，以封鎖危險登入行為 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

