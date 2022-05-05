---
title: Sheetgo by SHEETGO EUROPE SL 的應用程式資訊
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Sheetgo 的所有可用安全性與合規性資訊、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9cbad6d4fcd5f6e081187af10c3c8a69de7122ba
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225307"
---
# <a name="sheetgo"></a>Sheetgo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員更新日期：2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">在Teams存放區中檢視</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002067" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

SHEETGO EUROPE SL 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Sheetgo |
| ID | WA200002067 |
| 支援Office 365用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | SHEETGO EUROPE SL |
| 合作夥伴網站的 URL | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| 隱私權原則的 URL | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| 使用規定 URL | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

SHEETGO EUROPE SL 已提供此資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>| **所有非Microsoft 服務 OII 都會傳輸至** |  **哪些 OII 會傳輸？** | **傳輸 OII 的理由為何？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB：記錄系統和使用者資料以便運作，Google BigQuery：記錄系統記錄使用量、Google Firestore：維護及協調微服務狀態的系統 Stripe：付款系統 |  | 這些應用程式不會使用其他 Microsoft API |

#### <a name="data-access-via-bots"></a>透過 Bot 存取資料

如果此應用程式包含 Bot 或訊息擴充功能，它可以存取使用者可識別的資訊 (EUII) ：名冊 (名字、姓氏、顯示名稱、電子郵件地址) 加入小組中的任何小組成員或聊天。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>遙測/記錄僅包含使用者的電子郵件地址作為使用者可識別的資訊。 當使用者要求時，應用程式支援小組會執行內部自動常式，以模糊遙測/記錄之間的電子郵件地址，並讓使用者資料無法再識別。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>MongoDB：記錄系統和使用者資料以運作 Google BigQuery：記錄系統記錄使用量 Google Firestore：維護及協調微服務狀態的系統。 此服務傳輸的唯一重要資料是使用 AES256 Stripe：付款系統加密的使用者認證。
 
傳輸中的所有資料都會使用 HTTPS 進行安全連線，而所有敏感性資料都會使用 AES256 加密

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

