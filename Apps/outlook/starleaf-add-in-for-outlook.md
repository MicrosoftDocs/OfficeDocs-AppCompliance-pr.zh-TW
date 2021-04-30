---
title: StarLeaf 的應用程式資訊，由 StarLeaf Outlook 的增益集
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
description: StarLeaf 增益集 Outlook 的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ac1b9b979d9b6f8706e77baf22a73a784950eeaa
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094036"
---
# <a name="starleaf-add-in-for-outlook"></a>Outlook 的 StarLeaf 增益集

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月24日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 StarLeaf 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Outlook 的 StarLeaf 增益集 |
| ID | WA104381343 |
| 支援 Office 365 用戶端 | Outlook 2013 或更新版本的 Mac 上的 Windows、Outlook 2016 或更新版本 Outlook 網頁上的 |
| 合作夥伴公司名稱 | StarLeaf |
| 合作夥伴網站的 URL | [https://www.starleaf.com/](https://www.starleaf.com/) |
| 隱私權原則的 URL | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| 使用條款的 URL | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 StarLeaf 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 應用程式 | 我們會透過使用 Office.js 自訂屬性介面，存放會議的會議、出席者電子郵件地址和單一值擴充屬性，以及我們在會議上進行讀取和寫入的 iCalUId。 ICalUId 是用來將使用者&#8217;的 outlook 行事曆中的會議與我們服務上的視訊會議關聯。 您可以使用時間/日期和出席者，及時為服務上的適當人員提供影片會議。 SVEP 是用來與我們的 O365 增益集搭配使用，以提供一個介面，讓使用者可以在我們的服務（如錄製）上設定有關影片會議的詳細資料。 | 用於訂閱 webhook 通知，以追蹤使用者對其行事曆中的事件所做的變更，並更新我們的服務，使其保持一致。 當使用者與我們的 Teams 應用程式互動，並在我們的服務上排程會議時，也可以用來在行事曆中建立事件。 | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | 應用程式 | 我們會儲存 oauth 重新整理權杖，以供登入。 我們會儲存使用者設定檔 id，以與該使用者未來的 OAuth 嘗試進行比較，並確定我們不&#8217;t 儲存其詳細資料兩次。  | 允許使用者登入 app，並允許我們的應用程式取得使用者&#8217;的電子郵件地址，將其登入與我們的服務上的帳戶關聯。  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 如果發生技術支援問題，則 organisational 資料可能會轉接至 SalesForce，以進行案例管理。 如果使用者使用 PSTN 撥入功能，則通話會透過 Twilio、Plivo 或 Voxbone 進行傳遞。 |  | 不適用 |



#### <a name="add-in-data-access"></a>增益集資料存取

列出此應用程式在存取您組織的資料時所需的許可權、此許可權的理由和用途 (應用程式使用此資訊的情況為何？ ) ，以及應用程式是否在其資料庫中儲存任何這項資訊。

>| **Permission**  | **描述** |
>|:----------------|:----------------|
>| ReadWrite 專案 | 此增益集可以存取及修改使用中郵件中的個人資訊，例如本文、主旨、寄件者、收件者及附件資訊。 它可能會將此資料傳送給協力廠商服務。 您的信箱中的其他專案可以&#8217;t 讀取或修改。 |
>| 傳送資料 | 可以透過網際網路傳送資料 |

#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>可以。 記錄包括使用者名、IP 位址、通話詳細資料記錄、有關連線品質 (封包遺失、高比特) 、裝置類型、通話進度的資訊。 資訊可供技術支援小組和資深開發人員用來診斷服務問題。 資料會在90天之後 anonymised。 保護此資料的控制項會在我們的 ISO/IEC 27001 認證下進行審核。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料儲存在使用者&#8217;帳戶所在之資料中心的 StarLeaf&#8217;s 個人記錄伺服器上，並備份至相同司法轄區內的一或多個資料中心。 存取資料的方式是個別使用者帳戶，其使用的每位使用者密碼都會受到強度檢查。 StarLeaf&#8217;s 服務使用者帳戶會自動針對 HR 系統和公司 Active Directory 群組進行審核，以警示安全性與合規性小組如果發現異常。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

