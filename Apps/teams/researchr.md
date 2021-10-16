---
title: ResearcHR by KBE 的應用程式資訊&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
ms.date: 08/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: researcHR 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: bc174eb69b69cdf2d04c27bc4649f18111d87811
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412803"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月5日</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 KBE&#26666;&#24335;&#20250;&#31038; 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | researcHR |
| ID | WA200002557 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | KBE&#26666;&#24335;&#20250;&#31038; |
| 合作夥伴網站的 URL | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| Teams 應用程式資訊頁面的 URL | [https://app.researchr.work](https://app.researchr.work) |
| 隱私權原則的 URL | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| 使用條款的 URL | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 KBE&#26666;&#24335;&#20250;&#31038; 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 通道。建立 | 應用程式 | 我們使用此範圍，讓 bot 在 Teams 用戶端上建立新通道。 看到： https://docs.microsoft.com/en-us/graph/api/channel-post | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Directory.Read.All | 應用程式 | 我們使用此範圍來取得通道 IDs 和名稱，以在我們的網站上顯示這些資料。 看到： https://docs.microsoft.com/en-us/graph/api/channel-list | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Group.Read.All | 應用程式 | 我們使用此範圍來取得通道 IDs 和名稱，以在我們的網站上顯示這些資料。 看到： https://docs.microsoft.com/en-us/graph/api/channel-list | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Team.ReadBasic.All | 應用程式 | 我們使用此範圍來取得小組成員，讓使用者可以在網站上看到他們的小組成員。 看到： https://docs.microsoft.com/en-us/graph/api/group-list-members | 我們不會將這些資料儲存在資料庫上。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.Read.All | 應用程式 | 我們使用此範圍來取得使用者的加入頻道，讓使用者可以在我們的網站上看到其加入的團隊。 看到： https://docs.microsoft.com/en-us/graph/api/user-list-joinedteams | 我們不會將這些資料儲存在資料庫中。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.ReadBasic.All | 委託 | 我們使用此範圍來啟用 OAuth 登入，並收集使用者的 AAD 識別碼、存取權杖和重新整理權杖。 看到： https://docs.microsoft.com/en-us/graph/auth-v2-user | 我們會將使用者的 AAD 識別碼、存取權杖和重新整理權杖儲存在資料庫中，讓使用者能夠使用 OAuth 登入我們的網站。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| offline_access | 委託 | 我們使用此範圍來取得重新整理權杖，讓我們可以重新整理 authed 使用者的存取權杖，而不需要任何使用者互動。 看到： https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#offline_access | 我們會在資料庫中儲存重新整理權杖，讓我們可重新整理存取權杖，而不需要任何使用者互動。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>會加密資料庫中的所有資料。 資料庫資料的備份會在一段時間內，依照我們的內部運作原則進行存放和儲存。 當使用者取消此服務時，我們將會刪除使用者的使用者資訊，但不會有延遲，除非履行法律所規定的儲存義務所需的程度。 以下是詳細資料。 https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由 KBE&#26666;&#24335;&#20250;&#31038; 提供，此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

