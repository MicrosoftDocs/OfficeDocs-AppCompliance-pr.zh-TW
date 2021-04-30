---
title: 由 Zoho 公司私人限制之 Zoho 衝刺（Sprint）的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Zoho 衝刺（sprint）登錄中所有可用的安全性和符合性資訊，針對衝刺（其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及安全性/符合性資訊）。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 861b7f60df8eb44df5e67129b6be6d66851413f7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094227"
---
# <a name="zoho-sprints"></a>Zoho Sprints

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/153059f1-912e-45d6-a13a-037675d66974" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000188" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Zoho 公司私人限制于 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Zoho Sprints |
| ID | WA200000188 |
| 功能 | 索引標籤 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Zoho Corporation Private Limited |
| 合作夥伴網站的 URL | [https://www.zoho.com/sprints/](https://www.zoho.com/sprints/) |
| 隱私權原則的 URL | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| 使用條款的 URL | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊由 Zoho 公司私人限制，此應用程式會針對此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 委託 | 已儲存 alendar 資料夾識別碼，以將連絡人從 Zoho 衝刺同步處理至 Microsoft &amp; （反之亦然）。 |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 連絡人。 ReadWrite | 委託 | [連絡人] 資料夾識別碼會儲存，以同步處理連絡人。 |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 已讀取。選取 | 委託 | 儲存 UserPrincipalName 以供使用者識別。 | 讀取使用者選取的檔案 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | 委託 |  | 登入並讀取使用者設定檔 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委託 |  | 允許使用者將 Office365 使用者匯入 Zoho 衝刺（Sprint）。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 電子郵件 | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 委託 |  | 維護您有權存取資料的存取權限 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們不會收集遙測和記錄檔中的 EUII/PII。 我們有適當的腳本可供您尋找及警示，以修正任何看得見的資料。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>客戶可以使用 certaat 限制，在 Rest) 上，選取需要透過 EAR (加密來加密的資料。預設會將密碼散列。 透過隔離的專屬網路提供對伺服器的邏輯存取 &amp; ，且具有高安全性，而且


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35375" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

