---
title: Lucidchart by Lucid 軟體的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Lucidchart 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cdfec0551da7278ac92c3e24caa2664a26a89bea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552964"
---
# <a name="lucidchart"></a>Lucidchart

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/7f905be6-3226-4a4c-9c54-ab1edce3c99c" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381935" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Lucid 軟體所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Lucidchart |
| ID | WA104381935 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Lucid Software |
| 合作夥伴網站的 URL | [https://www.lucidchart.com](https://www.lucidchart.com) |
| Teams 應用程式資訊頁面的 URL | [https://lucidchart.zendesk.com/](https://lucidchart.zendesk.com/) |
| 隱私權原則的 URL | [https://lucid.co/privacy](https://lucid.co/privacy) |
| 使用條款的 URL | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Lucid 軟體會提供此資訊，此應用程式是關於此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| 電子郵件 | 委託 | 名稱和電子郵件地址。 | 電子郵件、openid 和設定檔許可權可讓 Lucidchart 為使用者產生 openid token，並取得使用者的足夠基本資訊，以便在必要時為其註冊 Lucidchart 帳戶。 為了確認從 Microsoft 傳回的資料，我們要求您取得公開金鑰以取得其回應的簽署者。 在 SSO 流程中，不會從 Microsoft 接收或傳送其他任何資料。 |  |
>| openid | 委託 | 名稱和電子郵件地址。 | 電子郵件、openid 和設定檔許可權可讓 Lucidchart 為使用者產生 openid token，並取得使用者的足夠基本資訊，以便在必要時為其註冊 Lucidchart 帳戶。 為了確認從 Microsoft 傳回的資料，我們要求您取得公開金鑰以取得其回應的簽署者。 在 SSO 流程中，不會從 Microsoft 接收或傳送其他任何資料。 |  |
>| profile | 委託 | 名稱和電子郵件地址。 | 電子郵件、openid 和設定檔許可權可讓 Lucidchart 為使用者產生 openid token，並取得使用者的足夠基本資訊，以便在必要時為其註冊 Lucidchart 帳戶。 為了確認從 Microsoft 傳回的資料，我們要求您取得公開金鑰以取得其回應的簽署者。 在 SSO 流程中，不會從 Microsoft 接收或傳送其他任何資料。 |  |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 適用於 Office 的 JavaScript API | 是 | 我們使用 Office OneDrive javascript SDK 來開啟使用 OneDrive 的 OneDrive 檔案選擇器。 () 。 我們不會產生任何存取權杖，也不會對 OneDrive APIs 自身進行任何要求。OneDrive 檔選擇器 SDK 為我們做。 我們只會看到使用者選擇的檔案名。 |  | 如果使用者使用 OneDrive 檔選擇器選取檔案，我們會儲存檔案名。 |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Lucidchart 資料會儲存在 AWS 中。 |  | 我們不會使用任何 Microsoft APIs。 我們使用 openID 取得基本的使用者資料，以執行 SSO。 我們會使用其檔案選擇器 API，但不會讓我們透過您的瀏覽器提交給我們的使用者檔案的存取權。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>出於安全性和支援的考慮，我們會記錄電子郵件和 IP 位址。 所有對記錄檔的存取都是 &amp; 在協力廠商系統中記錄的記錄，實際上是無法進行的。 存取記錄檔需要 MFA。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>Lucidchart 資料會儲存在 AWS 中。 它會在靜止時加密，並在傳輸中加密。 Lucidchart 使用最低特權和 MFA 的規則。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

