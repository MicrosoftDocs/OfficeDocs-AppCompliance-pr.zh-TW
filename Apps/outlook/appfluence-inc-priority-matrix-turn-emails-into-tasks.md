---
title: 優先順序清單的應用程式資訊-依 Appfluence Inc. 將電子郵件變成任務
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 所有可用的安全性和符合性資訊的優先順序清單-將電子郵件變成任務、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3f4ba1a7f888c576ae7a87286488d7b5f06037a2
ms.sourcegitcommit: 84c041bf4c0e79f1f3a14c4885ca5acd8709b129
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/06/2021
ms.locfileid: "52258990"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>優先順序清單-將電子郵件變成任務

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開發人員上次更新：2021年4月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Appfluence Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 優先順序清單-將電子郵件變成任務 |
| ID | WA104381735 |
| 支援 Office 365 用戶端 | Outlook 2016 或更新版本的 Mac 上的 outlook 2016 或更新版本、Outlook on iOS、Android 上的 outlook、Outlook 網頁版 |
| 合作夥伴公司名稱 | Appfluence Inc |
| 合作夥伴網站的 URL | [https://appfluence.com/](https://appfluence.com/) |
| 隱私權原則的 URL | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| 使用條款的 URL | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Appfluence Inc. 已提供此資訊，供 Inc. 使用此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何 [Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference) 。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 委託 | 只有在將新使用者新增至帳戶時，才會儲存電子郵件。 | 在 [建立新帳戶] 中，我們使用此功能建議其他小組成員。 | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | 委託 | 只有在將新使用者新增至帳戶時，才會儲存電子郵件。 | 在 [建立新帳戶] 中，我們使用此功能建議其他小組成員。 | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | 委託 | 我們會儲存登入權杖，以便代表使用者執行要求 | 重新整理權杖，而不 bothering 使用者。 小組) 的 (優先順序矩陣 | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | 委託 | 除非使用者明確且故意會建立連結至原始檔案的優先順序矩陣專案，否則不會儲存任何檔案資訊。 | 在我們的 web 應用程式中提供的一對一功能 (，而且我們的 Outlook/小組增益集) ，我們使用此功能，強調我們系統中兩個使用者共用的 SharePoint/OneDrive 檔案，成為協助會議和整體共同作業的方式。 | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | 委託 | 基本的使用者設定檔資訊 (顯示名稱、名字、姓氏、電子郵件、頭像) 由我們儲存。 | 取得使用者的名稱，電子郵件，虛擬化，以與我們的帳戶進行個人化。 | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | 委託 | 我們會儲存 SSO 連線，以指出使用者的登入模式。 | 若要透過單一登入登入使用者。 | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | 委託 | 少量的行事曆事件會變成儲存在我們系統中的任務。 | 讀取行事曆事件，使其可顯示在我們的1:1 視圖中。 同時初始化新帳戶。  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | 委託 | 我們會儲存系統中建立的任務，並提供原始郵件的連結。 | 在 Outlook 增益集中使用，以將電子郵件變成工作，並在1:1 視圖中顯示共用工作。 | d76f016f-52c7-41b5-835b-900361d7040c |
>| 工作。讀取 | 委託 | 有些 Outlook/Planner 工作會在我們的系統中複寫，以協助新的使用者。 | 我們會以其圖形工作來引導新的使用者帳戶。 | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>使用非 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不使用非 Microsoft 服務。



#### <a name="add-in-data-access"></a>增益集資料存取

列出此應用程式在存取您組織的資料時所需的許可權、此許可權的理由和用途 (應用程式使用此資訊的情況為何？ ) ，以及應用程式是否在其資料庫中儲存任何這項資訊。

>| **Permission**  | **描述** |
>|:----------------|:----------------|
>| ReadWrite 信箱 | 此增益集可以讀取或修改您信箱中任何專案的內容，並建立新的專案。 它可以存取任何郵件或行事曆專案中的個人資訊，例如正文、主旨、寄件者、收件者或附件。 它可能會將此資料傳送給協力廠商服務。 |
>| 傳送資料 | 可以透過網際網路傳送資料 |

#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>是的，我們會使用使用者的電子郵件作為其系統中的唯一識別碼，並用於追蹤應用程式錯誤，並追蹤系統中 (下載、登入、應用程式版本等) 中的關鍵事件，讓客戶服務小組能夠對客戶查詢提供提示回應。 在 GDPR 合規性的一部分中，我們會在刪除要求的2周內刪除所有客戶資料，雖然在實際執行這項作業的情況下，我們會在同一天進行這項作業。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>應用程式資料會安全地儲存在加密資料庫中，且存取權僅限於一小小組管理員。 為了進一步保護存取，我們強制實施2要素驗證、限制存取一組受控的 IP 位址，以及在其專屬專用子網中找出資料庫，直接從開放的網際網路存取。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catalog 的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security 資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Appfluence Inc. 已提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已透過 Microsoft identity platform 整合檢查清單中所述的所有適用的最佳作法，加以檢查及編譯？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
