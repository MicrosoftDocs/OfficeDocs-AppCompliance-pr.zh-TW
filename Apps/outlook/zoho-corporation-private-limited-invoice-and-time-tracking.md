---
title: 發票和時間追蹤的應用程式資訊 Zoho 發票（按 Zoho 公司私人有限）
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于發票和時間追蹤的安全性和符合性資訊資訊 Zoho 發票、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 65d71d027c2101c5332a9070e641300e77a39081
ms.sourcegitcommit: b7ef94cf5fb12f6730a8688834ceee4f8fe8e0da
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/25/2022
ms.locfileid: "64461366"
---
# <a name="invoice-and-time-tracking---zoho-invoice"></a>Zoho 發票的發票和時間追蹤

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381067" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Zoho 公司私人限制于 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Zoho 發票的發票和時間追蹤 |
| ID | WA104381067 |
| 支援 Office 365 用戶端 | Outlook 2013 或更新版本的 Mac Windows Outlook 2016 或更新版本 Outlook 網頁版 |
| 合作夥伴公司名稱 | Zoho Corporation Private Limited |
| 合作夥伴網站的 URL | [https://www.zoho.com/](https://www.zoho.com/) |
| 隱私權原則的 URL | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| 使用條款的 URL | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊由 Zoho 公司私人限制，此應用程式會針對此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](/graph/permissions-reference)。

>| **權限**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 連絡人。已讀取 | 委託 |  |  允許使用者與 Zoho 發票同步處理 Office365 連絡人。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Mail.Read | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 傳送郵件 | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Export。所有 | 委託 |  | 允許使用者匯出所有使用者相關資訊。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | 委託 |  | 允許使用者登入和讀取使用者設定檔。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委託 |  | 允許使用者將 Office365 使用者匯入 Zoho。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 電子郵件 | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 設定檔 | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們不會收集遙測和記錄檔中的 EUII/PII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>只有在使用者同意後，才會回遷資料。 透過隔離 &amp; 的專屬網路提供對伺服器的邏輯存取，且具有高安全性和監控。 這個網路受到防火牆、2要素驗證及 Kerberos Authent 的保護。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security 資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28305" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

