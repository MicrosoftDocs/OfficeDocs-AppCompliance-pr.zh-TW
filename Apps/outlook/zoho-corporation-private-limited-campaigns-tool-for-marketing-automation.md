---
title: Zoho 活動工具針對市場行銷自動化的應用程式資訊，由 Zoho 公司私人限制
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zoho 活動工具的所有可用安全性和符合性資訊資訊，用於行銷自動化、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e6107ce4526c7880253d52b6cecb0898c205f57e
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252904"
---
# <a name="zoho-campaigns-tool-for-marketing-automation"></a>行銷自動化的 Zoho 活動工具

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380835" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Zoho 公司私人限制于 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 行銷自動化的 Zoho 活動工具 |
| ID | WA104380835 |
| 支援 Office 365 用戶端 | Outlook 2013 或更新版本的 Mac 上的 Windows、Outlook 2016 或更新版本 Outlook 網頁上的 |
| 合作夥伴公司名稱 | Zoho Corporation Private Limited |
| 合作夥伴網站的 URL | [https://www.zoho.com/](https://www.zoho.com/) |
| 隱私權原則的 URL | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| 使用條款的 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp; omkt = en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊由 Zoho 公司私人限制，此應用程式會針對此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 委託 | [行事曆] 識別碼會儲存為從 Zoho 活動建立該行事曆中的事件。 | 允許使用者匯入 Office365 行事曆事件至 Zoho 活動。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| ReadWrite 的行事曆 | 委託 |  | 可讓使用者將 Zoho 的促銷事件新增至 Office365 行事曆。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 連絡人。已讀取 | 委託 |  以儲存連絡人資訊。 | 可讓使用者將 Office365 連絡人匯入 Zoho 活動。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 連絡人。 ReadWrite | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| 電子郵件 | 委託 | 會儲存電子郵件以供使用者識別。 |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | 委託 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="add-in-data-access"></a>增益集資料存取

列出此應用程式在存取您組織的資料時所需的許可權、此許可權的理由和用途 (應用程式使用此資訊的情況為何？ ) ，以及應用程式是否在其資料庫中儲存任何這項資訊。

>| **Permission**  | **描述** |
>|:----------------|:----------------|
>| 讀取專案 | 此增益集可以存取使用中郵件的個人資訊，例如寄件者名稱、收件者名稱、電子郵件地址、郵件內文及附件資訊。 增益集可能會將此資料傳送給協力廠商服務。 您的信箱中的其他專案可以&#8217;t 讀取或修改。 |
>| 傳送資料 | 可以透過網際網路傳送資料 |

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

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

