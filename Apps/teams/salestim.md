---
title: SalesTim 的應用程式資訊（按 SalesTim）
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: SalesTim 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b15cf2f87b6707b6fa82dfc3968444d7cad85e8a
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59278602"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員更新：2020年10月27日</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 SalesTim 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | SalesTim |
| ID | WA200001393 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | SalesTim |
| 合作夥伴網站的 URL | [https://www.salestim.com/](https://www.salestim.com/) |
| 隱私權原則的 URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 使用條款的 URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 SalesTim 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog ReadWrite。 | 委託 | 不 | 允許此應用程式在公司應用程式目錄中安裝及更新其自有的套件。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | 委託 | 我們&#8217;將部分使用者 IDs 只儲存，而不是設定檔資料。 | 可讓使用者選取應用程式中不同位置的其他使用者，例如在工作流程中選取 [核准者]。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | 委託 | 我們&#8217;只會&#8217;儲存群組/小組 IDs，我們不會儲存任何群組/小組內容。 | 允許此應用程式建立群組，代表登入的使用者讀取所有群組屬性和成員資格。 此外，允許群組擁有者管理其群組，並允許群組成員更新群組內容。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| 傳送郵件 | 委託 | 我們&#8217;將此動作的中繼資料儲存在一起，例如通知日期、收件者 (ID 只) 、要求識別碼。 | 允許此應用程式在核准工作流程中傳送通知電子郵件。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Sites.ReadWrite.All | 委託 | 我們正在使用一些 azure 服務來儲存資料，尤其是 azure 上的 Redis，以及 Cosmos DB | 可讓應用程式在小組布建過程中，管理與小組相關的磁片磁碟機 (檔案和資料夾) 。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | 委託 | 我們&#8217;將部分使用者 IDs 只儲存，而不是設定檔資料。 | 允許此應用程式讀取所有使用者的完整配置檔案屬性、報告及管理員。 在目標物件處理過程中尤其使用它，以根據目前的使用者設定檔來篩選部分內容。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offlineaccess | 委託 | 否 | 允許應用程式以使用者身分執行某些背景作業和動作。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 我們正在使用 Intercom 作為主要支援應用程式。 Intercom 可能包含一些基本的使用者設定檔資訊，如下所述： https://developers.salestim.com/platform/datamanagement.html#support-data |  | 我們正在使用 GitHub APIs 自動從我們的實際執行環境產生問題。 我們也會將部分技術記錄儲存在 GitHub (，如下所述： https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) 。 這些問題和記錄可能包含一些基本的使用者設定檔資訊。 每個15days 都會自動刪除這些問題和記錄。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>以下說明所有收集的資料： https://developers.salestim.com/platform/datamanagement.html#application-data 如所述，記錄暫時儲存15天，然後自動刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>大部分的資料都是儲存在 Azure Cosmos DB 中。
存取實際執行環境只限于兩人，而這些系統管理員帳戶是 MFA。
這些帳戶是專屬的，不同于我們公司的帳戶。
在目前所使用的所有 Azure 服務中，會將資料加密。
透過我們 GitHub 環境中的專門受保護分支（只有兩個人可以核准變更），即可自動部署至實際執行環境。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

