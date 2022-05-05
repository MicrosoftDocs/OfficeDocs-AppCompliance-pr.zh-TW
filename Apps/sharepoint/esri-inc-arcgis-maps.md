---
title: ArcGIS 地圖概觀
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ArcGIS 地圖的所有可用安全性與合規性資訊、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ae6a908d70cb8714676832c6dacee5f189f73998
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225147"
---
# <a name="arcgis-maps-overview"></a>ArcGIS 地圖概觀

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員更新日期：2021 年 7 月 21 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003118" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Esri， Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | ArcGIS 地圖 |
| ID | WA200003118 |
| 支援Office 365用戶端 | SharePoint 2016 或更新版本 |
| 合作夥伴公司名稱 | Esri， Inc. |
| 合作夥伴網站的 URL | [https://www.esri.com](https://www.esri.com) |
| 隱私權原則的 URL | [https://www.esri.com/legal/privacy-arcgis](https://www.esri.com/legal/privacy-arcgis) |
| 使用規定 URL | [https://www.esri.com/en-us/legal/terms/master-agreement-pro...](https://www.esri.com/en-us/legal/terms/master-agreement-product) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Esri， Inc. 已提供此資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>不使用非Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>應用程式遙測或記錄中不會出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>客戶系統管理員可以控制其使用者對組織或專案層級資料的存取。 讀取或寫入資料之前，會先針對存取控制清單檢查要求。 傳輸至終端使用者和外部服務的資料會使用僅限 TLS 1.2) 的 HTTPS (加密。

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/27233' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/27233" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Esri， Inc. 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳做法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已檢閱並符合Microsoft 身分識別平臺整合檢查清單中所述的所有適用最佳做法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | ArcGIS Online 依賴角色型存取控制 (RBAC) 模型。 解決方案中的所有使用者都必須擁有獲授與其存取權的角色。 |
| 您的應用程式是否要求案例的最低許可權許可權？ | 是 |
| 您應用程式的靜態註冊許可權是否能正確反映應用程式以動態和累加方式要求的許可權？ | 否 |
| 您的應用程式是否支援多租使用者？ | 是 |
| 您的應用程式是否有機密用戶端？ | 是 |
| 您是否擁有為應用程式註冊的所有重新導向統一資源識別項 (URI) ？ | 是 |
| 您的應用程式是否公開任何 Web API？ | 是 |
| 只有在用戶端應用程式收到適當的同意時，您的許可權模型才允許呼叫成功嗎？ | 是 |
| 您的應用程式是否使用預覽 API？ | 否 |
| 您的應用程式是否使用已被取代的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
