---
title: CodeTwo 的應用程式資訊，由 CodeTwo Office 365 的電子郵件簽名
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CodeTwo Microsoft Cloud App Security Office 365 的電子郵件簽章的所有可用安全性和符合性資訊資訊，其資料處理原則，其應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 13a8b7200513d09c77416ea93be55178c9b2a762
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413154"
---
# <a name="codetwo-email-signatures-for-office-365"></a>CodeTwo Office 365 的電子郵件簽名

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月2日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 CodeTwo 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | CodeTwo Office 365 的電子郵件簽名 |
| ID | codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69 |
| 合作夥伴公司名稱 | CodeTwo |
| 合作夥伴網站的 URL | [https://www.codetwo.com](https://www.codetwo.com) |
| 隱私權原則的 URL | [https://www.codetwo.com/regulations/privacy](https://www.codetwo.com/regulations/privacy) |
| 使用條款的 URL | [https://www.codetwo.com/license-agreement](https://www.codetwo.com/license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 CodeTwo 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | 允許使用者登入 app，並允許此應用程式讀取登入使用者的設定檔。 它也可讓應用程式讀取已登入使用者的基本組織資訊。 | 不儲存任何資料。 | [2a93620e-4345-4e3b-9bae-0195f08aab69](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a93620e-4345-4e3b-9bae-0195f08aab69) |
>| User.Read | 委託 | 允許使用者登入 app，並允許此應用程式讀取登入使用者的設定檔。 它也可讓應用程式讀取已登入使用者的基本公司資訊。 | 不儲存任何資料。 | [7afd058a-f568-4496-96b1-28d06ab3500f](https://docs.microsoft.com/microsoft-365-app-certification/azure/7afd058a-f568-4496-96b1-28d06ab3500f) |
>| Directory.AccessAsUser.All | 委託 | 允許此應用程式存取目錄中的資訊，以登入的使用者。 | 不儲存任何資料。 | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| Directory.Read.All | 包括 | 允許此應用程式讀取組織中的資料&#8217;s 目錄，例如使用者、群組和應用程式。 | 不儲存任何資料。 | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.ReadBasic.All | 委託 | 允許此應用程式代表登入的使用者讀取組織中其他使用者的基本配置檔案屬性集。 這包括顯示名稱、名字和姓氏、電子郵件地址及照片。 資訊可用於自動為使用者個人化電子郵件簽名。 | 不儲存任何資料。 | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.Read | 委託 | 允許使用者登入 app，並允許此應用程式讀取登入使用者的設定檔。 它也可讓應用程式讀取已登入使用者的基本公司資訊。 用於向 CodeTwo 服務註冊使用者。 | 不儲存任何資料。 | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| 電子郵件 | 委託 | 允許此應用程式讀取您的使用者的主要電子郵件地址。 用於向 CodeTwo 服務註冊使用者。 | 不儲存任何資料。 | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| offline_access | 委託 | 讓應用程式可以查看和更新您可存取的資料，即使使用者目前並未使用此應用程式也是一樣。 這不會給應用程式提供任何其他許可權。 | 不儲存任何資料。 | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| openid | 委託 | 允許使用者利用其工作或學校帳戶登入應用程式，並讓應用程式可以查看基本的使用者設定檔資訊。 用於向 CodeTwo 服務註冊使用者。 | 不儲存任何資料。 | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| 設定檔 | 委託 | 讓應用程式可以查看您的使用者基本設定檔 (名稱、圖片、使用者名稱) 。 用於向 CodeTwo 服務註冊使用者。 | 不儲存任何資料。 | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>客戶可以透過 CodeTwo 系統管理員面板，存取和修正其連絡人 &amp; 組織資料和服務設定。 他們也可以透過專用表單 (聯繫 CodeTwo 資訊安全小組 https://www.codetwo.com/form/security-officer/) ，以執行 CodeTwo 條款和隱私權 (中所述的任何權利， https://www.codetwo.com/regulations/privacy) 亦即存取資料、修正的資料、擦除和限制處理、提款同意和對物件進行處理的權利。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

CodeTwo 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

