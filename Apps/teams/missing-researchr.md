---
title: KBE&#26666;&#24335;&#20250;&#31038;重新架設的應用程式資訊
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ResearcHR、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中安全性/合規性資訊的所有可用安全性與合規性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229007"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員更新日期：2021 年 8 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">在Teams存放區中檢視</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

KBE&#26666;&#24335;&#20250;&#31038; 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | researcHR |
| ID | WA200002557 |
| 支援Office 365用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | KBE&#26666;&#24335;&#20250;&#31038; |
| 合作夥伴網站的 URL | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| Teams應用程式資訊頁面的 URL | [https://app.researchr.work](https://app.researchr.work) |
| 隱私權原則的 URL | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| 使用規定 URL | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

KBE&#26666;&#24335;&#20250;&#31038; 提供這項資訊，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 進行資料存取

列出此應用程式[所需的任何 Microsoft Graph](/graph/permissions-reference)許可權。

>| **權限**  | **委派/應用程式 (許可權類型)** | **是否收集資料？收集它的理由為何？** | **是否儲存資料？儲存它的理由為何？** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | 應用程式 | 我們使用此範圍來允許 Bot 在Teams用戶端上建立新通道。 請參閱：/graph/api/channel-post | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | 應用程式 | 我們使用此範圍來取得通道識別碼和名稱，以在我們的網站上顯示這些資料。 請參閱：/graph/api/channel-list | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | 應用程式 | 我們使用此範圍來取得通道識別碼和名稱，以在我們的網站上顯示這些資料。 請參閱：/graph/api/channel-list | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | 應用程式 | 我們使用此範圍來取得小組成員，讓使用者可以在我們的網站上看到其小組成員。 請參閱：/graph/api/group-list-members | 我們不會將這些資料儲存在 out 資料庫上。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | 應用程式 | 我們使用此範圍來取得使用者加入的頻道，讓使用者可以在我們的網站上看到其已加入的小組。 請參閱：/graph/api/user-list-joinedteams | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | 委託 | 我們使用此範圍來啟用 OAuth 登入，並收集使用者的AAD識別碼、存取權杖和重新整理權杖。 請參閱：/graph/auth-v2-user | 我們會將使用者的AAD識別碼、存取權杖和重新整理權杖儲存在資料庫中，讓使用者可以使用 OAuth 登入我們的網站。 | [82df726e-0de2-46af-b4f1-0645fd95fc97]。。/azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md)  |
>| offline_access | 委託 | 我們使用此範圍來取得重新整理權杖，以便在沒有任何使用者互動的情況下重新整理已驗證使用者的存取權杖。 請參閱：/azure/active-directory/develop/v2-permissions-and-consent#offline_access | 我們會將重新整理權杖儲存在資料庫中，以便在沒有任何使用者互動的情況下重新整理存取權杖。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


#### <a name="non-microsoft-services-used"></a>未使用Microsoft 服務

如果應用程式與非 Microsoft 服務傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、傳輸的資料，並包含應用程式需要傳輸此資訊的理由。

>不使用非Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 Bot 存取資料

如果此應用程式包含 Bot 或訊息擴充功能，它可以存取使用者可識別的資訊 (EUII) ：名冊 (名字、姓氏、顯示名稱、電子郵件地址) 加入小組中的任何小組成員或聊天。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織標識資訊 (OII) 或使用者可識別資訊 (EUII) 是否會出現在此應用程式的遙測或記錄中？ 如果是，請描述儲存哪些資料，以及保留和移除原則為何？

>應用程式遙測或記錄中不會出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>合作夥伴所儲存資料的組織控制

描述組織的系統管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、稽核、封存、使用者原則等。

>資料庫中的所有資料都會加密。 資料庫資料的備份將會根據我們的內部操作原則進行備份並儲存一段時間。 如果使用者取消此服務，我們會不延遲刪除使用者的使用者資訊，但必須履行法律規定之儲存義務的必要範圍除外。 以下是詳細資料。 https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>人為檢閱組織資訊

人類是否參與檢閱或分析任何組織可識別的資訊 (OII) 此應用程式所收集或儲存的資料？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新索引標籤中檢視</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

KBE&#26666;&#24335;&#20250;&#31038; 提供此資訊，說明此應用程式如何處理驗證、授權、應用程式註冊最佳做法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
