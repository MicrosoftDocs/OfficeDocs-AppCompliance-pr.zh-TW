---
title: AVA 的應用程式資訊，Inc. AvePoint，Inc.。
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: AVA 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 462181d4ba98d11e5aeae15a4827c6138bc80924
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53522066"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2020年3月23日</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

AvePoint，Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | AVA |
| ID | WA104381883 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | AvePoint, Inc. |
| 合作夥伴網站的 URL | [https://www.avepoint.com/](https://www.avepoint.com/) |
| Teams 應用程式資訊頁面的 URL | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| 隱私權原則的 URL | [https://www.avepoint.com/company/privacy-policy/](https://www.avepoint.com/company/privacy-policy/) |
| 使用條款的 URL | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 AvePoint，Inc. 提供。關於此應用程式如何收集和儲存組織資料，以及您的組織將會透過應用程式收集的資料所用的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 共用 | 委託 | 無 | 搜尋使用者的電子郵件，並將電子郵件移至指定的資料夾 | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.Read | 委託 |  使用者的存取權杖-用於搜尋及還原使用者的資料 | 允許使用者登入並將存取權杖授與應用程式 | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.ReadWrite | 委託 | DisplayName，UserPrincipalName，JobTitle，Organization，Country，MySiteUrl-record 使用此應用程式之使用者的基本資訊 | 取得使用者的基本設定檔資訊 | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePointREST APIs | 是 | 使用者個人網站的回收中的搜尋檔案，並還原這些檔案。 需要 AllSites。管理許可權。 |  | 無 |  |

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

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

