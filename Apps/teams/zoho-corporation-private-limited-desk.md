---
title: Zoho 服務台的應用程式資訊，由 Zoho 公司私人限制
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zoho 書桌的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e76f0cce92e7aa5bac28df505613ec461a3fc06
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528349"
---
# <a name="zoho-desk"></a>Zoho Desk

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/091ec948-c0ee-4d56-aa9e-51c3d8316a9c" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382044" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Zoho 公司私人限制于 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Zoho Desk |
| ID | WA104382044 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Zoho Corporation Private Limited |
| 合作夥伴網站的 URL | [https://www.zoho.com/desk](https://www.zoho.com/desk) |
| Teams 應用程式資訊頁面的 URL | [https://help.zoho.com/portal/kb/zoho-desk](https://help.zoho.com/portal/kb/zoho-desk) |
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
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | 委託 |  | 讀取使用者檔案。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.Read.All | 委託 |  | 讀取使用者可以存取的所有檔案。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | 委託 |  | 登入和讀取使用者設定檔。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.ReadBasic.All | 委託 |  | 讀取所有使用者的基本設定檔。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| 電子郵件 | 委託 |  | View user 的電子郵件地址。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | 委託 |  | 保留您已授予其存取權的資料存取權。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | 委託 |  | View user 的基本設定檔。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>1) 使用者介面中的選項可刪除實體，Zoho 書桌內部的系統管理員和代理套裝程式含刪除選項可執行此程式。2) 我們也會有一些選項可供系統管理員針對其用途匯出及實現。  3) 我們會在後端繼續進行審計，在客戶要求上可以提供此資訊。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

