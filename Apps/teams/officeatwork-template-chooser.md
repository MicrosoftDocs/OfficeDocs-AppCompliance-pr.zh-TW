---
title: 透過 officeatwork 的範本選擇器的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 12/08/2020
ms.topic: article
ms.service: attestation
description: 所有可用的安全性和符合性資訊，如範本選擇、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 49ead47e2f995d928d8b22c92b9dd3e6ddfc216c
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094164"
---
# <a name="template-chooser"></a>範本選擇程式

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員更新：2020年12月8日</p>

* <a href="https://teams.microsoft.com/l/app/13d1defc-6301-4e62-9c53-3361db865183" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000110" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 officeatwork 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 範本選擇程式 |
| ID | WA200000110 |
| 功能 | 索引標籤 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | officeatwork |
| 合作夥伴網站的 URL | [https://links.officeatwork.com/officeatwork-home](https://links.officeatwork.com/officeatwork-home) |
| Teams 應用程式資訊頁面的 URL | [https://links.officeatwork.com/officeatwork-apps](https://links.officeatwork.com/officeatwork-apps) |
| 隱私權原則的 URL | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| 使用條款的 URL | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 officeatwork 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 委託 | 不儲存任何資料。 | 「我的我的最愛」：能夠讀取及寫入資料至使用者 OneDrive;OneDrive：能夠在使用者 OneDrive 中讀取及寫入資料。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Group.ReadWrite.All | 委託 | 不儲存任何資料。 | Teams：能夠讀取及寫入群組中的資料。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| GroupMember Read。 All | 委託 | 不儲存任何資料。 | SharePoint線上：允許從 SharePoint 線上讀取資料的使用者許可權。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| Sites.Read.All | 委託 | 不儲存任何資料。 | SharePoint線上：啟用從 SharePoint 線上讀取資料。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read | 委託 | 不儲存任何資料。 | 共同作業：讓 officeatwork 應用程式讀取使用者的基本屬性。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| User.Read.All | 委託 | 不儲存任何資料。 | Teams：找出使用者所屬的群組。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| offline_access | 委託 | 不儲存任何資料。 | In：若要透過重新整理來啟用自動登入，使用者必須在每次啟動 officeatwork 應用程式時手動登入。 只有在啟用非 SSO 的主應用程式時，才需要此範圍。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| openid | 委託 | 不儲存任何資料。 | In：讓使用者能夠利用其組織和/或 Microsoft 帳戶登入 officeatwork 應用程式 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |
>| profile | 委託 | 不儲存任何資料。 | In：用於顯示 officeatwork 應用程式中已登入的使用者。 這有助於保證/確認使用者用來登入 officeatwork 應用程式的帳戶。 | dae2eacf-3eb5-4440-baff-984fbd5cae68 |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePointREST APIs | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>是的，事件包括 oid 和 tenantId，而且會傳送至 Azure AppInsights。 事件會在90天后自動刪除。 如果客戶想要刪除此資料，可使用隱私權聲明中提供的連結，以啟動對該資料的刪除。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>「應用程式設定」資料 (功能旗標、組織顯示名稱、tenantId、系統管理員 oid) 清單會儲存在 Azure Cosmos DB 實例中 (每個租使用者) 一個檔案。 資料庫檔案已加密，且存取權僅限於選取的 officeatwork 工程師和支援人員。 客戶可以使用系統管理中心 Web App 來存取及操縱 officeatwork 應用程式設定資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35385" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Officeatwork 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 安全性預設 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 否 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，
<br />
- OAuth2 隱含 Flow （除非 SPA 是必要的）
<br />
- 資源擁有者密碼認證 (ROPC) 流程 | |您的應用程式是否公開任何 web APIs？ |無 | |您的應用程式是否使用預覽 APIs？ |無 | |您的應用程式使用的 APIs 是否已遭取代？ |否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
