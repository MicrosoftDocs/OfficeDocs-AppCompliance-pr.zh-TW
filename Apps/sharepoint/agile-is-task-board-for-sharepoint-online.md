---
title: 以敏捷的方式 SharePoint 線上的敏捷工作面板應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 09/30/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可供 SharePoint 線上運作的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 34526c1037ee220cabfecf6dd06fac93bb0e4952
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412102"
---
# <a name="agile-task-board-for-sharepoint-online"></a>線上 SharePoint 的敏捷工作面板

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2020年11月3日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002087" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

敏捷所提供的資訊-對 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 線上 SharePoint 的敏捷工作面板 |
| ID | WA200002087 |
| 支援 Office 365 用戶端 | SharePoint 2016 或更新版本 |
| 合作夥伴公司名稱 | Agile-IS |
| 合作夥伴網站的 URL | [https://www.agile-is.de](https://www.agile-is.de) |
| 隱私權原則的 URL | [https://www.agile-is.de/en/telemetry](https://www.agile-is.de/en/telemetry) |
| 使用條款的 URL | [https://www.agile-is.de/en/termsofuse](https://www.agile-is.de/en/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊已由 Agile 提供，其是關於此應用程式如何收集和儲存組織資料，以及您的組織將會對應用程式收集的資料所產生的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們會收集 application insights 遙測資料中的功能變數名稱和雜湊的使用者識別碼。 在每個應用程式實例內，可以控制和關閉遙測資料的傳輸。 後續刪除資料必須由美國要求。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>應用程式會將 SharePoint 線上清單和文件庫中的所有資料儲存在應用程式各自實例執行所在的相同網站上。 存取此資料的控制權取決於客戶的承租人設定。 

為了進行授權控制，網域和 UPN 會轉移到 Azure 中主控的服務。 這種資訊會受到 Azure AD 驗證的保護。


#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36140' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36140" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


