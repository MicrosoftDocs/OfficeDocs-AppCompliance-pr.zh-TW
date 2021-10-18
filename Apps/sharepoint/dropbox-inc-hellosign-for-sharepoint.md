---
title: HelloSign 的應用程式資訊，由 Dropbox inc. SharePoint。
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: HelloSign SharePoint 的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: fb96325377e779b0bb933aef7238baa38e0c9380
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428416"
---
# <a name="hellosign-for-sharepoint"></a>SharePoint 的 HelloSign

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月3日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003245" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Dropbox inc. 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SharePoint 的 HelloSign |
| ID | WA200003245 |
| 支援 Office 365 用戶端 | SharePoint 2013 或更新版本 |
| 合作夥伴公司名稱 | Dropbox公司。 |
| 合作夥伴網站的 URL | [https://hellosign.com](https://hellosign.com) |
| 隱私權原則的 URL | [https://www.hellosign.com/privacy](https://www.hellosign.com/privacy) |
| 使用條款的 URL | [https://hellosign.com/terms](https://hellosign.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Dropbox inc. 提供。關於此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | 應用程式 | 這會搭配使用。 ReadWrite，可將 HelloSign 簽章檔案寫回 SharePoint 網站。 | 我們不會儲存與此範圍相關的任何資料 | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| Sites.ReadWrite.All | 應用程式 | 這會搭配檔案使用。 ReadWrite，將 HelloSign 簽章檔案寫回 SharePoint 網站。 | 我們不會儲存與此範圍相關的任何資料 | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| User.Read | 委託 | 用來識別應用程式中之使用者的電子郵件 | 根據電子郵件，用來與我們的 HelloSign 帳戶進行交叉參考的電子郵件 | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePointAPI | 是 | 電子郵件、租使用者識別碼及網站識別碼 | 用於識別和驗證目的 | 電子郵件、租使用者識別碼、網站識別碼 | 用於識別和驗證目的 |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://www.hellosign.com/subprocessors | 電子郵件、租使用者識別碼、網站識別碼 | JN 專案，Inc. HelloSign (&#8220;HelloSign&#8221;) 使用特定 subprocessors 協助提供服務。 我們使用的服務提供者可以儲存和處理您和您的使用者的個人資料 (每個 &#8220;Sub-Processor&#8221;) 。 此頁面提供這些材料子處理器之身分識別、位置及角色的重要資訊。 在此頁面上使用的詞彙，但未定義在我們的服務合約條款中規定的意義 (&#8220;合約&#8221;) 。 |



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們為位於合作夥伴系統中的資料，提供了刪除、保留及記錄功能

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Dropbox inc. 提供此資訊。關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
