---
title: MyHub 的應用程式資訊，inc. AvePoint，inc.。
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: MyHub 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 391c44f4f1d06742d1002b713f5f24f69db7d01e
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52253184"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開發人員上次更新日期：2020年12月21日</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

AvePoint，inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | MyHub |
| ID | WA200000726 |
| 功能 | Bot，索引標籤 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | AvePoint, Inc. |
| 合作夥伴網站的 URL | [https://www.avepoint.com](https://www.avepoint.com) |
| 隱私權原則的 URL | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| 使用條款的 URL | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 AvePoint，inc. 提供。關於此應用程式如何收集和儲存組織資料，以及您的組織將會透過應用程式收集的資料所用的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | 包括 | 從資料處理的觀點來儲存應用程式設定資料 | 讀取目錄資料 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Group.ReadWrite.All | 包括 | 從資料處理的觀點來儲存應用程式設定資料 | 讀取和寫入所有群組 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| 傳送郵件 | 委託 | 從資料處理的觀點來儲存應用程式設定資料 | 以使用者的身分傳送郵件 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Reports。已讀取。所有 | 應用程式 | 從資料處理的觀點來儲存應用程式設定資料 | 讀取所有使用方式報告 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| FullControl 所有 | 應用程式 | 從資料處理的觀點來儲存應用程式設定資料 | 具有所有網站集合的完全控制許可權 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.Read.All | 應用程式 | 從資料處理的觀點來儲存應用程式設定資料 | 讀取所有網站集合中的專案  | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.ReadWrite.All | 委託 | 從資料處理的觀點來儲存應用程式設定資料 | 編輯或刪除所有網站集合中的專案 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| User.Read.All | 包括 | 從資料處理的觀點來儲存應用程式設定資料 | &#8217; 完整設定檔讀取所有使用者 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>是的，使用者的電子郵件和租使用者識別碼會出現在記錄檔中。 記錄會儲存在安全的位置，而且只有經過授權的人員才能在疑難排解期間存取。 出於安全性審核目的，記錄會在60天之後封存，並將在一年後刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>應用程式的資料儲存在 Azure SQL Database 和 Azure 儲存體中。 已啟用 Azure SQL 和 Azure 儲存體加密。
只有授權的系統管理員可以存取資料。 需要 MFA 才能讓系統管理員登入。 會審核作業。 [IP whitelisting] 也用來限制資料的存取權。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

