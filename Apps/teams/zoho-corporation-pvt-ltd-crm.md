---
title: Zoho Corporation Pvt 有限公司的 Zoho CRM 應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zoho CRM 的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7228520de3cc4a7e77880a5d2a4a556f2082f99e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428456"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Zoho Corporation Pvt 有限公司提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Zoho CRM |
| ID | WA104382094 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Zoho Corporation Pvt Ltd |
| 合作夥伴網站的 URL | [https://www.zoho.com/](https://www.zoho.com/) |
| Teams 應用程式資訊頁面的 URL | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| 隱私權原則的 URL | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| 使用條款的 URL | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Zoho Corporation Pvt 公司提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | [行事曆] 資料夾識別碼會儲存，以將連絡人從 Zoho CRM 同步處理至 Microsoft &amp; 。 儲存諸如 event_name、event_location、participant_details 的行事曆資訊。 | 允許使用者與 Zoho CRM 同步處理 Office365 事件。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| 連絡人。 ReadWrite | 委託 | [連絡人] 資料夾識別碼會儲存為將連絡人從 Zoho CRM 同步處理至 Microsoft， &amp; 反之亦然。 會儲存 first_name、last_name、電子郵件地址等連絡人資訊。 | 允許使用者與 Zoho CRM 同步處理 Office365 連絡人。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read | 委託 |  | 可讓使用者將 Office365 檔案匯入 Zoho CRM。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read.All | 委託 |  | 可讓使用者將 Office365 檔案匯入 Zoho CRM。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| 已讀取。選取 | 委託 | 儲存 UserPrincipalName 以供使用者識別 | 可讓使用者將 Office365 檔案匯入 Zoho CRM。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.ReadBasic.All | 委託 | 如 first_name、last_name、電子郵件地址等使用者屬性。 | 讀取所有使用者的基本設定檔 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| 電子郵件 | 委託 | 為使用者 indentification 儲存 UserPrincipaName | View user 的電子郵件地址 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| offline_access | 委託 |  | 維護您有權存取資料的存取權限 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| 設定檔 | 委託 |  | View user 的基本設定檔 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |


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

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

