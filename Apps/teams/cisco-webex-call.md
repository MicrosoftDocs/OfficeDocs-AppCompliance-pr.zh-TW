---
title: Cisco 的 Webex 呼叫應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 01/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于 Webex 呼叫的安全性和符合性資訊資訊、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 50ff8ddaab9be9b66da02156761931de44770340
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414729"
---
# <a name="webex-call"></a>Webex Call

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年1月4日</p>

* <a href="https://teams.microsoft.com/l/app/0924e969-85d8-4acb-8687-faacd6abd228" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001495" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Cisco 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Webex Call |
| ID | WA200001495 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Cisco |
| 合作夥伴網站的 URL | [https://www.cisco.com](https://www.cisco.com) |
| 隱私權原則的 URL | [https://www.cisco.com/c/en/us/about/legal/privacy.html](https://www.cisco.com/c/en/us/about/legal/privacy.html) |
| 使用條款的 URL | [https://www.cisco.com/c/en/us/products/universal-cloud-agre...](https://www.cisco.com/c/en/us/products/universal-cloud-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Cisco 已提供此資訊，是由 Cisco 針對此應用程式如何收集和儲存組織資料，以及您的組織將透過應用程式收集的資料所提供的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 聊天室讀取 | 委託 | 取得聊天成員，以利用 Cisco WebEx 呼叫私人聊天中的其他成員 | 應用程式不會儲存其資料庫中的任何資料 | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| 連絡人。已讀取 | 委託 | 取得使用者連絡人，讓使用者可以使用 Cisco WebEx 呼叫連絡人 | 應用程式不會儲存其資料庫中的任何資料 | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.Read | 委託 | 取得使用者的電子郵件、電話，讓他們可以啟動 Cisco WebEx 呼叫電子郵件或電話 | 應用程式不會儲存其資料庫中的任何資料 | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.ReadBasic.All | 委託 | 取得使用者的電子郵件、電話，讓他們可以啟動 Cisco WebEx 呼叫電子郵件或電話 | 應用程式不會儲存其資料庫中的任何資料 | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.ReadWrite | 委託 | 此許可權可將速度撥號資訊儲存至使用者分機 | 應用程式不會儲存其資料庫中的任何資料  | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 此郵件分機會閱讀聊天成員的電子郵件，讓使用者可以使用 Cisco WebEx 呼叫它們 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>此應用程式未儲存任何使用者資料

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Cisco 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

