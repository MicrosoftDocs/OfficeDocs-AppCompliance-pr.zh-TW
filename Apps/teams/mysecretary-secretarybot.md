---
title: SecretaryBot 的應用程式資訊（按 MySecretary）
ms.author: elmalova
author: elenamalova
ms.date: 04/30/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SecretaryBot 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f3f373b4d507e96e12c77e8c9aef3228138095a8
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430442"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 MySecretary 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SecretaryBot |
| ID | WA104381085 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | MySecretary |
| 合作夥伴網站的 URL | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| Teams 應用程式資訊頁面的 URL | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| 隱私權原則的 URL | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| 使用條款的 URL | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 MySecretary 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 已讀取行事曆。共用 | 委託 |  | 提取使用者及其同事的閒置時間資訊。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| ReadWrite 的行事曆 | 委託 |  | 傳送會議要求，而不是使用者。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings 讀取 | 委託 | 儲存語言以顯示正確的 langage。 將時區儲存為可正確地呼叫 MS Graph calendar API | 提取使用者的語言和時區設定。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| 個人讀取 | 委託 |  | 嘗試尋找與使用者有牢固關係的同事。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | 委託 | 儲存使用者分析的使用者名稱、城市、國家及語言。 儲存電子郵件以與客戶聯繫。 我們從未使用過的電子郵件地址，但可用於支援。 | 嘗試尋找使用者的國家及慣用語言。 用於 MailboxSettings 備份。請參閱。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| 電子郵件 | 委託 | 請參閱上述內容。 | 儲存電子郵件。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | 委託 |  | OpenID 驗證。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| 設定檔 | 委託 | 儲存 OID 以在 MS identity system 中識別使用者的唯一識別碼。 | 取得使用者名稱及 OID。 嘗試使用 OID 在未來 Outlook 增益集。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 使用此 infromation 排程小組會議 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>OII 或 EUII 資料會顯示在遙測或記錄檔中。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們還沒有為使用者提供 adminstrative 控制權，但是如果使用者要求我們刪除資料，則可以遵循他們的要求。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

