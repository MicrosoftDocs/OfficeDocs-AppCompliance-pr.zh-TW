---
title: MailClark 的應用程式資訊（按 MailClark）
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: MailClark 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9d21ca3fe09b49a66725b0e7195fe08836d3d125
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552954"
---
# <a name="mailclark"></a>MailClark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/64f174e8-7e14-4b48-871e-2fb7b17be302" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381679" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 MailClark 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | MailClark |
| ID | WA104381679 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | MailClark |
| 合作夥伴網站的 URL | [https://mailclark.ai/microsoft-teams-integration](https://mailclark.ai/microsoft-teams-integration) |
| Teams 應用程式資訊頁面的 URL | [https://mailclark.ai/support](https://mailclark.ai/support) |
| 隱私權原則的 URL | [https://mailclark.ai/privacy](https://mailclark.ai/privacy) |
| 使用條款的 URL | [https://mailclark.ai/tos](https://mailclark.ai/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 MailClark 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 郵件。 ReadWrite | 應用程式 |  | 已閱讀：若要訂閱內送電子郵件的推播通知。 撰寫：建立草稿。 |  |
>| 傳送郵件 | 應用程式 |  | 以傳送草稿。 |  |
>| User.Read | 應用程式 | 帳戶詳細資料，例如電子郵件地址。 | 來識別帳戶。 |  |
>| offline_access | 應用程式 | 重新整理權杖 | 在帳戶中斷連線之前，更新驗證。 |  |
>| openid | 應用程式 |  | 需要驗證。 |  |
>| profile | 應用程式 |  | 以驗證使用者。 |  |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 將人員指派給交談 | 名字、姓氏、顯示名稱、電子郵件地址 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>租使用者識別碼、使用者識別碼 (電子郵件地址) 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>GDPR 合規性的一部分，系統管理員可以要求刪除、資料存取等等 (請參閱法律 tab 以取得詳細資料) 。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35675' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35675" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

