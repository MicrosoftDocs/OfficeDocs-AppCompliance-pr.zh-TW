---
title: Smartsheet 的應用程式資訊（按 Smartsheet）
ms.author: elmalova
author: elenamalova
ms.date: 11/11/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Smartsheet 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d8bbe31189a44c240bc648670a0a04e0b5fce6ec
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429060"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Smartsheet 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Smartsheet |
| ID | WA104380975 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Smartsheet |
| 合作夥伴網站的 URL | [https://www.smartsheet.com](https://www.smartsheet.com) |
| Teams 應用程式資訊頁面的 URL | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| 隱私權原則的 URL | [https://www.smartsheet/legal/privacy](https://www.smartsheet/legal/privacy) |
| 使用條款的 URL | [https://Default 使用者合約： https://www.smartsheet.com/.. 。](https://Default User Agreement: https://www.smartsheet.com/legal/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Smartsheet 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog ReadWrite。 | 委託 | 無。 | 允許我們的應用程式代表使用者安裝應用程式。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Directory.Read.All | 委託 | tenantId 用於檢索顯示在 UI 中的資訊。 | 可讓我們讀取此租使用者使用的應用程式，以便檢查我們是否需要為他們安裝應用程式。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.Read.All | 委託 | teamId/groupId for message 傳遞。 | 允許我們的應用程式讀取有關群組的基本資訊 (或 Teams 小組) 和交談。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| Group.ReadWrite.All | 委託 | teamId/groupId for message 傳遞。 | 允許我們的應用程式在團隊中開始新的交談。 此許可權也包括上述讀取。除了技術原因之外，我們還需要這項範圍。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| User.Read.All | 委託 | userId. | 允許我們在驗證程式期間讀取使用者的基本資訊。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |
>| offline_access | 委託 | refreshToken. | 允許我們的應用程式在使用此應用程式時，代表使用者接收重新整理權杖並重新整理驗證權杖。 | [c68947ae-a07f-44ce-9a13-7b559251731d](https://docs.microsoft.com/microsoft-365-app-certification/azure/c68947ae-a07f-44ce-9a13-7b559251731d) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Bot Framework APIs | 是 | 我們使用 Bot Framework API 將郵件當做小組應用程式的應用程式來傳遞。 Smartsheet 儲存 userId 資訊，以追蹤 Smartsheet bot 所交談的人員。 |  | 無 |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Smartsheet 會將實際執行資料中心環境中以靜止狀態存放的資訊儲存在使用 Equinix 和 AWS S3 進行的實際執行資料中心環境內，我們將客戶附件儲存于私人加密的存放桶中。 |  | 我們使用 bot framework API 將郵件當做小組應用程式的應用程式來傳遞。 Smartsheet 儲存 userId 資訊，以追蹤 Smartsheet bot 所交談的人員。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Smartsheet 會使用它來協助追蹤 bot 的交談情況。 在初始驗證流程中，我們會在 Smartsheet 通知系統中為使用者建立 bot 記錄。 | 針對 Teams bot 的 Smartsheet，我們會從 Teams 中儲存使用者電子郵件和 userId，以協助追蹤 bot 的交談。  Smartsheet 儲存 tenantIds 以協助列出使用者屬於目錄中的群組，以及 groupIds 以進行郵件傳遞。 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>否

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>Smartsheet 會加密所有儲存的使用者資訊，而且我們的系統管理員必須使用2FA。 Smartsheet 以 no view SaaS 提供者的身分運作，而且根據預設，我們不會複習客戶選擇要上傳或輸入平臺的內容。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

