---
title: Office檔應用程式資訊的 Wrike
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: 適用于 Office 檔、其資料處理原則、其Microsoft Cloud App Security應用程式類別目錄資訊，以及 CSA STAR 登錄中安全性/合規性資訊之 Wrike 的所有可用安全性與合規性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d91cf614ca0e3b52eae4b626baf15e038c29f51b
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784532"
---
# <a name="wrike-for-office-documents-application-information"></a>Office檔應用程式資訊的 Wrike

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次由開發人員更新日期：2020 年 3 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Wrike Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Office檔的 Wrike |
| ID | WA104379841 |
| 支援Office 365用戶端 | Excel 2016 Windows上的 Windows、Word 2013 或更新版本、Windows上的 PowerPoint 2013 或更新版本、Mac 上的 Excel 2016 或更新版本、Mac 上的 Excel 網頁版、Word 2016 或更新版本，mac 上的 Word 網頁版、PowerPoint 2016 或更新版本，PowerPoint 網頁版 |
| 合作夥伴公司名稱 | Wrike Inc. |
| 合作夥伴網站的 URL | [https://www.wrike.com/](https://www.wrike.com/) |
| 隱私權原則的 URL | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| 使用規定 URL | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Wrike Inc. 已提供此資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>此應用程式不會使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft API 進行資料存取

建置在 Microsoft 365 上的應用程式和增益集可能會使用 Microsoft Graph 以外的其他 Microsoft API 來收集或處理組織可識別的資訊， (OII) 。 列出此應用程式使用的 Microsoft Graph以外的任何 Microsoft API。

>| **API** |  **是否已收集 OII？** |  **收集的 OII 為何？** | **收集 OII 的理由？** | **是否儲存 OII？** | **儲存 OII 的理由為何？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 適用於 Office 的 JavaScript API | 是 | 增益集會使用Office.js API 來與Office應用程式整合。 |  | Wrike 的資料庫中不會儲存任何組織資料。 |  |

#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>| **所有非Microsoft 服務 OII 都會傳輸至** |  **哪些 OII 會傳輸？** | **傳輸 OII 的理由為何？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike 與下列可存取某些資料的廠商整合：Marketo 是電子郵件潛在客戶擷取服務 -只有名稱和電子郵件會提供給他們。 拓展是以雲端為基礎的銷售業務開發 - 只會提供名稱和電子郵件給他們。 Salesforce CRM 系統 - 具有連絡人資訊和計費 (沒有敏感性資料) 客戶的資訊。 Zuora - 計費和開立發票客戶。 所有廠商都已備妥 DPA。 |  | 我們使用 JS Office API，但我們不會收集/處理/儲存任何組織資訊。 |



#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>Wrike 具有多租使用者架構，可根據客戶中繼資料，透過存取控制，以邏輯方式隔離客戶&#8217;資料。 此中繼資料會根據特定 Wrike 帳戶內的角色型存取規則，與特定租使用者及其存取權限相關聯。 資料在邏輯上是隔離和隔離的，而且只能透過應用程式存取資料，以確保安全性和隱私權。 應用層級的安全性會封鎖租使用者存取或修改另一個租使用者所擁有的應用程式資料。 Wrike 的應用程式具有廣泛的驗證、角色型存取控制、授權，以及資料共用和控制機制， (查看 https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles 並 https://help.wrike.com/hc/en-us/articles/209602969) 僅允許授權使用者的資料存取。 此外，透過 Web 應用程式和 API，將待用加密套用至檔案儲存體中 Wrike 伺服器的使用者檔案;檔案會使用 AES 256 位加密自動加密。 此外，所有伺服器都會使用檔案系統加密進行待用加密，此外，Wrike 也提供 Wrike Lock 增益集供客戶管理的加密金鑰使用，請參閱 https://www.wrike.com/add-on-wrike-lock/ 和 https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock 。 作為額外的資料安全性層級，Wrike 提供稽核和報告功能，可讓系統管理員進行完整的安全性檢閱，同時能夠提高其 Wrike 帳戶中所發生情況的可見度，您可以在 找到更多詳細資料。 https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports 最後，Wrike 提供的功能可讓您更細微地追蹤存取角色，以協助客戶完整稽核現有的資料共用，請參閱 的詳細資料 https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports 。
在兩種情況下，可以考慮存取客戶資料：
- Wrike 支援小組的存取權：若要進行疑難排解或驗證問題，需要支援人員才能存取您的帳戶;該存取權只能由您授與。 系統產生的安全性權杖會啟用此功能，而您提供超出範圍給我們的支援小組，讓支援人員在有限的時間內更深入地解決您的問題。 此系統方法可確保儲存在 Wrike 中的資料具有額外的機密性。
- Wrike 作業小組的存取權：Wrike 作業小組負責維護和支援生產環境，包括監視、修補和更新、將新組建傳遞至生產環境等等。在此情況下，嚴格禁止程式和技術層面的存取，並備妥強式授權控制，包括但不限 VPN、2FA 和個人憑證，此外，也會使用 HIDS (主機型入侵偵測系統) 並由 Wrike 作業安全性小組檢閱，以詳細方式監視它。 如果 Amazon KMS (Wrike 鎖定功能) ，客戶資料會以加密方式儲存在 Wrike 資料庫中，因此 Wrike 作業小組無法直接或間接取得資料，因為資料可以使用客戶 Amazon KMS的存取來解密，而該存取僅由客戶管理及控制。

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

