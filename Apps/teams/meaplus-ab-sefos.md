---
title: SEFOS by Meaplus AB 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 09/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SEFOS 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 14da720eee4a70152a3239d43154f0b47b0c56ea
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414549"
---
# <a name="sefos"></a>SEFOS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月15日</p>

* <a href="https://teams.microsoft.com/l/app/a9b13f17-540f-4b08-a48c-75051b68677e" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003219" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Meaplus AB 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SEFOS |
| ID | WA200003219 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Meaplus AB |
| 合作夥伴網站的 URL | [https://www.meaplus.com](https://www.meaplus.com) |
| Teams 應用程式資訊頁面的 URL | [https://sefos.se/en/sefos-i-teams/](https://sefos.se/en/sefos-i-teams/) |
| 隱私權原則的 URL | [https://www.meaplus.com/privacy-policy/](https://www.meaplus.com/privacy-policy/) |
| 使用條款的 URL | [https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-...](https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-end_user_agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Meaplus AB 會提供此資訊，讓您瞭解此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | 代表使用者建立會議 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| 傳送郵件 | 委託 | 傳送會議邀請 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| MailboxSettings 讀取 | 委託 | 收集已驗證使用者的時區 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| 個人讀取 | 委託 | 在驗證的使用者 adressbook 中搜尋 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| User.Read | 委託 | 登入並讀取使用者設定檔 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| 電子郵件 | 委託 | 在 SEFOS 中識別使用者的電子郵件地址。 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| openid | 委託 | 簽署使用者 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| 設定檔 | 委託 | 讀取使用者設定檔 | 無 | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>不適用，這是一種分散式系統，每個組織都可以在本機安裝中控制自己的資訊。 . 

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Meaplus AB 會提供此資訊，告知此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

