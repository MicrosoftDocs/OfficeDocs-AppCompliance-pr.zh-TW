---
title: Beesy 的應用程式資訊（按 BeesApps）
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Beesy 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2d6c04408ab08da89a858987981beb3fafc30229
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411852"
---
# <a name="beesy"></a>Beesy

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月6日</p>

* <a href="https://teams.microsoft.com/l/app/03a513ab-60d8-4d27-8c9a-5182934a43bb" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001248" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 BeesApps 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Beesy |
| ID | WA200001248 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | BeesApps |
| 合作夥伴網站的 URL | [https://www.beesapps.com/](https://www.beesapps.com/) |
| 隱私權原則的 URL | [https://www.beesy.me/legal/privacypolicy_en.pdf](https://www.beesy.me/legal/privacypolicy_en.pdf) |
| 使用條款的 URL | [https://www.beesy.me/legal/termsofservice_en_v1.03.pdf](https://www.beesy.me/legal/termsofservice_en_v1.03.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 BeesApps 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | 我們只會儲存 UPN 識別碼，以與要求透過 AAD token 來檢查帳戶是否存在於我們的系統中。 | 允許使用者登入，並提供應用程式存取其 UPN 以啟用無訊息登入 | [d27f56ed-ddc7-4cf8-86ac-721b76c7d287](https://docs.microsoft.com/microsoft-365-app-certification/azure/d27f56ed-ddc7-4cf8-86ac-721b76c7d287) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 我們存取此資料以提供 bot 的內容，以直接將動作記錄到人員聊天 (我們的 bot 是虛擬的小幫手) 。 | 沒有直接從名單中儲存的資料，我們會比較團隊成員與已整合的人員，以 beesy.me 服務資料，只要符合。 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>沒有 EUII 記錄檔或 OII 記錄檔

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料儲存在專屬伺服器上，僅限系統管理員可以透過專用連線 VPN、SSL 憑證及密碼所保護的伺服器。其他伺服器透過專用 vlan layer 2 （永不是專用伺服器）進行通訊。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35940' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35940" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


