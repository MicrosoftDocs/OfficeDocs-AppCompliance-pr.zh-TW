---
title: iPlanner 的應用程式資訊，由 iGlobe Office 365 Planner 的報表工具
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: iPlanner 報告工具的所有可用安全性和符合性資訊資訊 Office 365 Planner、其資料處理原則、Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548763"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Office 365 Planner 的 iPlanner 報告工具

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 iGlobe 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Office 365 Planner 的 iPlanner 報告工具 |
| ID | WA104380686 |
| 支援 Office 365 用戶端 | Mac 上 Windows、Excel 網頁版、Excel 2016 或更新版本上的 Excel 2016 或更新版本 |
| 合作夥伴公司名稱 | iGlobe |
| 合作夥伴網站的 URL | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| 隱私權原則的 URL | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| 使用條款的 URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 iGlobe 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 委託 | 不會儲存應用程式資料庫中的資料。 | 在任務到期日的使用者&#8217;的行事曆中建立行事曆專案。 |  |
>| Directory.AccessAsUser.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 以檢查使用者是否有同意，以及具有使用 API 的存取權。 |  |
>| Directory.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 若要取得 planner 工作 Outlook To Do，已標記的電子郵件並進行更新。 以建立新的 Planner 任務。 |  |
>| Files.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 以附件方式存取檔案，並將檔案上傳至任務。 |  |
>| Group.Read.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 以取得計畫清單並更新任務。 |  |
>| Group.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 若要取得 planner 任務並新增任務更新桶和泳道線。 |  |
>| Mail.Read | 委託 | 不會儲存應用程式資料庫中的資料。 | 若要取得 planner 工作 Outlook To Do、已標記的電子郵件並加以更新，可供使用者讀取。 若要建立新的 Planner 任務 |  |
>| 郵件。 ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 以顯示郵件及傳送郵件。 |  |
>| ReadWrite。 | 委託 | 不會儲存應用程式資料庫中的資料。 | 從選取的郵件中取得郵件主體。 允許此應用程式從選取的電子郵件中取得資訊，讓您可以將描述欄位複製到工作描述中，並允許將附件從郵件或郵件本身儲存至任務。 傳送通知。 |  |
>| 工作。 ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 若要取得登入使用者 Outlook To Do 並更新使用者。請參閱，以取得 planner 工作 Outlook To Do、已標記的電子郵件並加以更新。 以建立新的 Planner 任務。 |  |
>| User.Read | 委託 | 不會儲存應用程式資料庫中的資料。 | 登入並讀取使用者設定檔 |  |


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

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

