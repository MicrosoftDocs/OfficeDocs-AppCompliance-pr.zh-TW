---
title: MIPA 的應用程式資訊-您的個人助理 iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/06/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: 所有適用于 MIPA 的安全性和符合性資訊資訊-您的個人助理、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 243a39894b36ea470d25d4145169ecd6f2a27c75
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252533"
---
# <a name="mipa---your-personal-assistant"></a>MIPA - 您的個人助理

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員的更新日期：2020年11月6日</p>

* <a href="https://teams.microsoft.com/l/app/eec9d2db-2325-43f5-83c7-eac7c5253a87" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000148" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 iGlobe 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | MIPA - 您的個人助理 |
| ID | WA200000148 |
| 功能 | Bot，索引標籤，傳訊擴充功能 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | iGlobe |
| 合作夥伴網站的 URL | [https://mipa.iglobe.dk/](https://mipa.iglobe.dk/) |
| Teams 應用程式資訊頁面的 URL | [https://mipa.iglobe.dk/Support](https://mipa.iglobe.dk/Support) |
| 隱私權原則的 URL | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| 使用條款的 URL | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 iGlobe 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 委託 | 不會儲存應用程式資料庫中的資料。 | 閱讀和更新日曆 entires | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| 連絡人。 ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 閱讀和更新日曆 entires | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.AccessAsUser.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 任務、讀取使用者最近及共用的檔案。 以檢查使用者是否有同意，以及具有使用 API 的存取權。 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Directory.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 工作、讀取使用者最近及共用檔案，以取得 SharePoint 清單、文件庫及檔案。 將檔案儲存至 SharePoint 清單。 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Files.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 工作、讀取使用者最近及共用檔案，以取得 SharePoint 清單、文件庫及檔案。 將檔案儲存至 SharePoint 清單。 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.Read.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 工作、讀取使用者最近及共用檔案，以取得 SharePoint 清單、文件庫及檔案。 將檔案儲存至 SharePoint 清單。 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| Group.ReadWrite.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取、更新、建立 Panner 工作、讀取使用者最近及共用檔案，以取得 SharePoint 清單、文件庫及檔案。 將檔案儲存至 SharePoint 清單。 整合至 iGlobe CRM Office 365 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| 郵件。 ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取和更新已標記的郵件 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| MailboxSettings ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 閱讀和更新 entires、讀取和更新已標記的郵件、讀取和更新 Outlook To Do entires | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| 工作。 ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取和更新日曆 entires、讀取和更新 Outlook 以執行 Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取和更新日曆 entires、讀取和更新 Outlook 以執行 Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.Read.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取和更新日曆 entires、讀取和更新 Outlook 以執行 Entreies、讀取、更新、建立 Panner 任務 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadBasic.All | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取和更新日曆 entires、讀取和更新 Outlook 以執行 Entreies、讀取、更新、建立 Panner 任務 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| User.ReadWrite | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取和更新日曆 entires、讀取和更新 Outlook 以執行 Entreies | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| 電子郵件 | 委託 | 不會儲存應用程式資料庫中的資料。 | 允許此應用程式讀取您的使用者的主要電子郵件地址 ( 以取得 SSO) 。 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| offline_access | 委託 | 不會儲存應用程式資料庫中的資料。 | 讓應用程式可以查看和更新您可存取的資料，即使使用者目前並未使用此應用程式也是一樣。 這不會讓應用程式 ( SSO) 的任何額外許可權。 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| openid | 委託 | 不會儲存應用程式資料庫中的資料。 | 允許使用者利用其工作或學校帳戶登入應用程式，並可讓應用程式查看基本的使用者設定檔資訊 (，以供 SSO) 使用。 | e854ea05-68ab-4204-babe-db4a784fb4d16 |
>| profile | 委託 | 不會儲存應用程式資料庫中的資料。 | 讀取和更新日曆 entires、讀取和更新 Outlook 以執行 Entreies、讀取、更新、建立 Panner 任務 | e854ea05-68ab-4204-babe-db4a784fb4d16 |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange-行事曆 ReadWrite 所有 | 否 |  |  |  |  |
>| Exchange-EWS。AccessAsUser。 All | 否 |  |  |  |  |
>| Exchange-郵件讀取 | 否 |  |  |  |  |
>| Exchange-ReadWrite 所有 | 否 |  |  |  |  |
>| Exchange-MailboxSettings。讀取 | 否 |  |  |  |  |
>| Exchange-MailboxSettings ReadWrite | 否 |  |  |  |  |
>| Exchange-Tasks ReadWrite | 否 |  |  |  |  |
>| SharePoint-MyFiles。讀取 | 否 |  |  |  |  |
>| SharePoint-MyFiles。寫入 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。



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
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 否 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
