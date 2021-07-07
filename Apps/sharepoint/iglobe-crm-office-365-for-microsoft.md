---
title: iGlobe 的 iGlobe CRM Office 365 Microsoft Office 365 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: 所有適用于 Microsoft Office 365 的 iGlobe CRM Office 365 的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: bdc9b8367c251e17fc055f0a3466e74b97215bbd
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281505"
---
# <a name="iglobe-crm-office-365-for-microsoft-office-365"></a>iGlobe Microsoft Office 365 的 CRM Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員的更新日期：2020年11月17日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379222" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 iGlobe 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | iGlobe Microsoft Office 365 的 CRM Office 365 |
| ID | WA104379222 |
| 支援 Office 365 用戶端 | SharePoint 2013 或更新版本 |
| 合作夥伴公司名稱 | iGlobe |
| 合作夥伴網站的 URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| 隱私權原則的 URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 使用條款的 URL | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 iGlobe 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 委託 | 不會儲存應用程式資料庫中的資料。 | 從 canlendar 中的 dreating 會議報表至 iGlobe 時，可以存取使用者行事曆 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| 連絡人。 ReadWrite | 委託 |  Directory.AccessAsUser.All | 允許此應用程式存取目錄中的資訊，以登入的使用者。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 檢查許可權並取得網站和清單。 建立資料夾、取得檔及儲存檔案。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 允許此應用程式存取目錄中的資訊，以登入的使用者。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 工作、讀取使用者最近及共用檔案，以取得 SharePoint 清單、文件庫及檔案。 將檔案和資料儲存至 SharePoint 清單。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 工作、讀取使用者最近及共用檔案，以取得 SharePoint 清單、文件庫及檔案。 將檔案儲存至 SharePoint 清單。 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 工作、讀取使用者最近及共用檔案，以取得 SharePoint 清單、文件庫及檔案。 將檔案儲存至 SharePoint 清單。 整合至 iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| 郵件。 ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | Svae eamil 至 iGlobe CRM，並從 iGlobe 取得 informatiopn 至新的電子 amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| 管理的網站。所有 | 委託 | 不會儲存應用程式資料庫中的資料。 | 在 iGlobe CRM 中建立、編輯和刪除專案與清單 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 在 iGlobe CRM 中讀取專案 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 |  在 iGlobe CRM 中編輯和刪除專案與清單 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| 工作。 ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 從 iGlobe CRM 建立 planner 任務 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | 委託 | 不會儲存應用程式資料庫中的資料。 | 若要取得 speficic 使用者 iGlobe CRM 的資訊 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange-行事曆 ReadWrite 所有 | 否 |  |  |  |  |
>| Exchange-Mail。 Read。 All | 否 |  |  |  |  |
>| Exchange-連絡人。讀取 | 否 |  |  |  |  |
>| Exchange-EWS。AccessAsUser。 All | 否 |  |  |  |  |
>| Exchange-Tasks ReadWrite | 否 |  |  |  |  |
>| SharePoint-AllSites。管理 | 否 |  |  |  |  |
>| SharePoint-AllSites。讀取 | 否 |  |  |  |  |
>|  SharePoint-AllSites。寫入 | 否 |  |  |  |  |
>| SharePoint-MyFiles。寫入 | 否 |  |  |  |  |
>| SharePoint 網站。全部管理 | 否 |  |  |  |  |
>| SharePoint-Sites。 Read。 All | 否 |  |  |  |  |
>| SharePoint ReadWrite 所有 | 否 |  |  |  |  |
>| SharePoint-搜尋。所有 | 否 |  |  |  |  |
>|  SharePoint-TermStore。 | 否 |  |  |  |  |
>| SharePoint-TermStore ReadWrite 所有 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>iGlobe 收集資料，以有效運作並為您提供我們產品和服務的最佳體驗。 若要取得授權：收集以管理組織&#8217;s 授權帳戶的資料，例如，當您部署免費的增益集、建立試用訂閱或購買訂閱。 會收集下列資訊。 
- 針對財務目的：公司名稱和位址
- 訂閱的使用者：使用者名稱和電子郵件

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>所有資料都在客戶的自有承租人上。 不會儲存應用程式資料。 現代增益集會在沙箱瀏覽器中執行，&#8220;進程外&#8221;。 它會使用 Microsoft 服務與使用者資料互動。 增益集可能只會存取使用者所使用的資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

IGlobe 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 安全性預設值以及封鎖舊版驗證的任何其他常見原則需要對管理員進行 MFA * 需要 mfa for Azure management * 需要對所有使用者進行 MFA * |
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
