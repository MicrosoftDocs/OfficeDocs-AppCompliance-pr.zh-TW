---
title: ServiceDesk Plus Cloud 的應用程式資訊，由 Zoho 公司私人有限
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: ServiceDesk Plus Cloud 的所有可用安全性和符合性資訊資訊，也就是其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a1c561d7ce78573f7000f7a710467c53f662e64c
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251622"
---
# <a name="servicedesk-plus-cloud"></a>ServiceDesk Plus Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/04fdcea1-3511-499c-966d-099d59aef45f" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000037" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Zoho 公司私人限制于 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | ServiceDesk Plus Cloud |
| ID | WA200000037 |
| 功能 | Bot，索引標籤，傳訊擴充功能 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Zoho Corporation Private Limited |
| 合作夥伴網站的 URL | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| Teams 應用程式資訊頁面的 URL | [https://help.sdpondemand.com/servicedeskplus_cloud_for_teams](https://help.sdpondemand.com/servicedeskplus_cloud_for_teams) |
| 隱私權原則的 URL | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| 使用條款的 URL | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊由 Zoho 公司私人限制，此應用程式會針對此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 應用程式 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 已讀取。選取 | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | 委託 | 使用者的電子郵件識別碼。 | 允許使用者登入並提供其 UPN 的應用程式存取權，以啟用無提示登入。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | 應用程式 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委託 | 電子郵件識別碼、名稱、員工識別碼、職稱、電話、行動、網站、部門、地區設定、使用者的設定檔照片。 | 可讓您從 Azure Active Directory 匯入使用者的基本資訊。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 電子郵件 | 委託 | 使用者的電子郵件識別碼。 | View user 的電子郵件地址。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 委託 |  | 保留您已授予其存取權的資料存取權。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | 委託 |  | View user 的基本設定檔。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>在遙測/記錄中未收集 EUII/PII。 我們有適當的腳本，可供您尋找模式及警示以進行修正

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>所有資料在靜止時會加密。 只有經過授權的人員才能存取仍受保護的系統，並在所有類型的 access 完全進行審核。 對存取進行 MFA 就地，授權帳戶會維護在公司目錄及主機中


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

