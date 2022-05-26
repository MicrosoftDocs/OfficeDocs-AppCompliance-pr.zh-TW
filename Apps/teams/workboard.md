---
title: Workboard by Workboard 的應用程式資訊
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 檢閱 Workboard、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊的所有可用安全性與合規性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ccf27f1fa0c6db96446fc0fa7afc686fe2a49e20
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/26/2022
ms.locfileid: "65688098"
---
# <a name="application-information-for-workboard"></a>Workboard 的應用程式資訊

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次由開發人員更新日期：2021 年 6 月 4 日</p>

* <a href="https://teams.microsoft.com/l/app/28d0282b-3cd2-49f0-90bb-a016843750c6" target="_blank">在Teams存放區中檢視</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381599" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Workboard 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Workboard |
| ID | WA104381599 |
| 支援Office 365用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Workboard |
| 合作夥伴網站的 URL | [https://www.workboard.com](https://www.workboard.com) |
| Teams應用程式資訊頁面的 URL | [https://www.workboard.com/microsoft/](https://www.workboard.com/microsoft/) |
| 隱私權原則的 URL | [https://www.workboard.com/license/privacy-policy.html](https://www.workboard.com/license/privacy-policy.html) |
| 使用規定 URL | [https://www.workboard.com/license/terms_of_use_v1.php](https://www.workboard.com/license/terms_of_use_v1.php) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊由 Workboard 提供，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>| **權限**  | **委派/應用程式 (許可權類型)** | **是否收集資料？收集它的理由為何？** | **是否儲存資料？儲存它的理由為何？** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | 電子郵件地址和使用者的識別碼。  它是用來將使用者對應至 WorkBoard 的使用者識別碼 | WorkBoard 只會將使用者的身分識別儲存在其資料庫中 | [User.Read](/graph/permissions-reference#user-permissions) |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>不使用非Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 Bot 存取資料

如果此應用程式包含 Bot 或訊息擴充功能，它可以存取使用者可識別的資訊 (EUII) ：名冊 (名字、姓氏、顯示名稱、電子郵件地址) 加入小組中的任何小組成員或聊天。 此應用程式是否使用此功能？

>| **存取 EUII 的理由為何？**  | **EUII 是否儲存在資料庫 (的) 中？** | **儲存 EUII 的理由為何？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 使用者識別碼用於由 WorkBord 傳送至 Teams 的主動式通知 | 使用者電子郵件地址和識別碼 | 用來將使用者對應至 WorkBoard 的使用者識別碼 |


#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>應用程式遙測或記錄中不會出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>WorkBoard 不會將組織資料儲存在合作夥伴的系統中

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/29004" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊已由 Workboard 提供，說明此應用程式如何處理驗證、授權、應用程式註冊最佳做法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已檢閱並符合Microsoft 身分識別平臺整合檢查清單中所述的所有適用最佳做法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | WorkBoard 已實作自己的存取原則，這些原則會在應用程式內強制執行。  使用者的組織、小組和身分識別可用來判斷存取權限。 |
| 您的應用程式是否要求案例的最低許可權許可權？ | 是 |
| 您應用程式的靜態註冊許可權是否能正確反映應用程式以動態和累加方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租使用者？ | 是 |
| 您的應用程式是否有機密用戶端？ | 否 |
| 您是否擁有為應用程式註冊的所有重新導向統一資源識別項 (URI) ？ | 是 |
| 您的應用程式是否公開任何 Web API？ | 是 |
| 只有在用戶端應用程式收到適當的同意時，您的許可權模型才允許呼叫成功嗎？ | 是 |
| 您的應用程式是否使用預覽 API？ | 否 |
| 您的應用程式是否使用已被取代的 API？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
