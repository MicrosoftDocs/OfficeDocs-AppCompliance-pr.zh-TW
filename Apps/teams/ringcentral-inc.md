---
title: RingCentral by RingCentral，Inc. 的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 05/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: RingCentral 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bb0787720195363368e3d822e45f173acee67870
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59277780"
---
# <a name="ringcentral"></a>RingCentral

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員于下列：2021年5月18日更新</p>

* <a href="https://teams.microsoft.com/l/app/2f285d77-896a-4c5f-901e-0902316003b5" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000135" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

RingCentral，Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | RingCentral |
| ID | WA200000135 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | RingCentral, Inc. |
| 合作夥伴網站的 URL | [https://www.ringcentral.com](https://www.ringcentral.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.ringcentral.com/apps/ringcentral-for-microsoft-...](https://www.ringcentral.com/apps/ringcentral-for-microsoft-teams) |
| 隱私權原則的 URL | [https://www.ringcentral.com/legal/privacy-notice.html](https://www.ringcentral.com/legal/privacy-notice.html) |
| 使用條款的 URL | [https://www.ringcentral.com/legal/last-update-October-15-20...](https://www.ringcentral.com/legal/last-update-October-15-2019/eulatos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

RingCentral，Inc. 已提供此資訊。關於此應用程式如何收集和儲存組織的資料，以及您的組織將會透過應用程式收集的資料所產生的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 |  允許應用程式透過他們的行事曆傳送會議邀請事件 | 無 | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| offline_access | 委託 |  允許應用程式取得並更新 oauth 權杖 |  存取 MS Graph API 的存取權杖和重新整理權杖 | [ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/ 0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read | 委託 |  允許此應用程式讀取使用者&#8217;基本設定檔 (電子郵件、名稱) ，以便在我們的結束中執行連絡人相符。 並可讓使用者使用 RingCentral 帳戶登入並連結其 O365 帳戶 |  電子郵件、名字、姓氏 | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |
>| User.Read.All | 委託 | 允許應用程式使用電話號碼讀取使用者的完整設定檔，以便撥打我們的服務電話。 | 無 | [0dd4bfdf-dc86-4f05-9991-a14bc0144ebf](https://docs.microsoft.com/microsoft-365-app-certification/azure/0dd4bfdf-dc86-4f05-9991-a14bc0144ebf) |


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

>在我們使用另一個組織的地方，我們仍會控制您的個人資訊。而且我們有嚴格的控制措施，以確保其&#8217;受到適當保護。 最後，上一節將說明您的個人資訊共用至其他組織、政府系及法律強制機關的情況。  當我們與其他組織共用您的資訊時，我們&#8217;會確定它&#8217;受保護的，盡可能是合理的。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11833" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

RingCentral，Inc. 已提供此資訊。關於此應用程式如何處理驗證、授權、application registration 最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
