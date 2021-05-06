---
title: Wrike for Wrike inc. Office 檔的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Wrike 的所有可用安全性和符合性資訊資訊，針對 Office 檔、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c1304a161377b80c0248229aa1ef92f4f15e19d9
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251402"
---
# <a name="wrike-for-office-documents"></a>Office 檔的 Wrike

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員更新：2020年3月23日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Wrike Inc. 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Office 檔的 Wrike |
| ID | WA104379841 |
| 支援 Office 365 用戶端 | Excel 2016 或更新版本于 Windows、Word 2013 或更新版本上 Windows、PowerPoint 2013 或更新版本上 Windows、Excel 2016 或更新 mac、Excel 網頁版、Word 2016 或更新 mac 上 Word 網頁版 |
| 合作夥伴公司名稱 | Wrike Inc. |
| 合作夥伴網站的 URL | [https://wrike.com/](https://wrike.com/) |
| 隱私權原則的 URL | [https://www.wrike.com/privacy](https://www.wrike.com/privacy) |
| 使用條款的 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp; omkt = en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Wrike Inc. 提供。關於此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| 適用於 Office 的 JavaScript API | 是 | 增益集會使用 Office.js API，以與 Office 應用程式整合。 |  | 不會在 Wrike 的資料庫中儲存組織資料。 |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike 與下列廠商的整合可以存取部分資料： Marketo 是電子郵件潛在客戶捕獲服務-僅提供其名稱和電子郵件。 「推廣」是以雲端為基礎的銷售合約，只會提供他們的名稱和電子郵件。 Salesforce CRM 系統-具有連絡人資訊和帳單 (沒有機密資料) 客戶的資訊。 Zuora-帳單和開具發票的客戶。 所有廠商都有一個 DPA 到位。 |  | 我們使用 JS Office API，但我們不會收集/處理/處理/儲存任何組織資訊。 |



#### <a name="add-in-data-access"></a>增益集資料存取

列出此應用程式在存取您組織的資料時所需的許可權、此許可權的理由和用途 (應用程式使用此資訊的情況為何？ ) ，以及應用程式是否在其資料庫中儲存任何這項資訊。

>| **Permission**  | **描述** |
>|:----------------|:----------------|
>| ReadWrite 檔 | 可以讀取和變更您的檔 |
>| 傳送資料 | 可以透過網際網路傳送資料 |

#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>Wrike 具有多承租人架構，可透過客戶的中繼資料，以邏輯方式 segregates 客戶&#8217; 資料。 根據特定 Wrike 帳戶中以角色為基礎的訪問規則，此中繼資料會與特定承租人和其存取權限相關聯。 資料會以邏輯方式隔離及隔離，而且只有透過應用程式才可以存取資料，以確保安全性和隱私權。 應用層級的安全性會封鎖承租人，以存取或修改其他租使用者所擁有的應用程式資料。 Wrike 的應用程式具有大量驗證、角色型的存取控制、授權，以及資料共用和控制機制 (請參閱 https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles ， https://help.wrike.com/hc/en-us/articles/209602969) 只允許授權使用者的資料存取。 此外，在檔案儲存中透過 web 應用程式與 API 上傳至 Wrike server 的使用者檔案，也會套用靜態加密。檔案會自動使用 AES 256 位加密進行加密。 此外，所有伺服器都會以檔案系統加密加密，而且 Wrike 會提供 Wrike 鎖定增益集，以供客戶管理的加密金鑰使用，請參閱 https://www.wrike.com/add-on-wrike-lock/ 和 https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock 。 Wrike 提供了審核和報告功能，可讓系統管理員進行完整的安全性檢查，同時可以深入瞭解在其 Wrike 帳戶中發生的情形，也可以在中找到更多詳細資料 https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports 。 最後，Wrike 提供的功能可讓存取角色的細微追蹤，以協助客戶完全審核現有資料共用。請參閱詳細資料 https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports 。
可以在兩種情況中考慮存取客戶資料：
- Wrike 支援小組存取：在進行疑難排解或驗證問題時，需要支援存取您的帳戶;只有您可以授與存取權。 這項功能是由系統產生的安全性權杖所組成，您可以將其提供給我們的支援小組使用，讓支援人員深入瞭解如何在有限的時間內解決您的問題。 這種系統性方法可確保 Wrike 中儲存的資料的其他機密性。
- Wrike 操作團隊的存取權： Wrike 運作小組負責維護和支援實際執行環境，包括監控、修補和更新、將新的組建交付至實際執行等。在此案例中，絕對不會同時禁止從程式及技術層面進行存取，而且強烈的授權控制（包括但不限於 VPN）2FA 和個人憑證已存在，此外也會以使用 HIDS (主機型入侵偵測) 系統的詳細資料加以監控，Wrike 操作安全性小組也會加以監控。 如果 Amazon KMS (Wrike 鎖定功能) ，客戶資料會儲存在 Wrike 資料庫中，因此 Wrike 操作小組無法直接或間接使用資料，因為資料可以利用 access 的 Amazon 的 Amazon KMS 進行解密，該資料只會由客戶進行管理及控制。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

