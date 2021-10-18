---
title: Nulia 的應用程式資訊的運作方式 Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Nulia Works 的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d2a9f576fa7aad7ca7895d94da6987860fd1355a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430432"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2021年3月11日</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Nulia 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Nulia Works |
| ID | WA200002051 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Nulia |
| 合作夥伴網站的 URL | [https://nulia.com](https://nulia.com) |
| Teams 應用程式資訊頁面的 URL | [https://nulia.com/product](https://nulia.com/product) |
| 隱私權原則的 URL | [https://nulia.com/privacy](https://nulia.com/privacy) |
| 使用條款的 URL | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Nulia 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們計算使用者擁有的行事曆事件數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| 連絡人。已讀取 | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們計算使用者已建立的連絡人數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Files.Read.All | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們計算使用者與電腦同步處理的檔數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Group.Read.All | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們從群組中取得使用者所屬的 Teams 數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Mail.Read | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們計算使用者已建立的自訂郵件資料夾數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| MailboxSettings 讀取 | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們會看到使用者是否有外出回復集。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| 閱讀附注。 | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們計算使用者共用的筆記本數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Reports。已讀取。所有 | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們會從使用者報告一天所傳送的 Teams 郵件數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Sites.Read.All | 應用程式 | 我們使用收集的資料來評分使用者對技能和成果的進度。 我們收集跨越多個 O365 工作負載的流量計數。 | 我們儲存在 blob 儲存中收集的所有資料。 我們使用此資料來排名使用者的技能和結果進度。 例如，我們計算使用者已建立的網站集合數目。 該值會影響其技能的進度。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| User.Read | 應用程式 | 我們會顯示使用者的顯示名稱、部門和設定檔圖片。 | 我們在資料庫中儲存顯示名稱和部門，因此不需要每次都命中 Graph。 我們不會儲存設定檔圖片。 | [我們為每位客戶建立新的應用程式識別碼。例如，我們的 Nulia 租使用者使用的是 application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| 已讀取組織。全部 | 應用程式 | 我們會收集租使用者的名稱和 Yammer 基底 URL。 當使用者 &quot; &quot; 在與 Yammer 活動相關的應用程式中，按一下 [Try It] 按鈕時，我們會使用此功能來啟動 Yammer。 | 我們儲存在 blob 儲存中收集的所有資料。 例如，我們使用此功能，當使用者按一下 &quot; &quot; 與 Yammer 活動相關的應用程式中的 [嘗試 It] 按鈕時，就會開始 Yammer。 | [我們使用收集的資料來評分使用者對技能和成果的進度。我們收集跨越多個 O365 工作負載的流量計數。](https://docs.microsoft.com/microsoft-365-app-certification/azure/We use the data collected to score user progress on skills and Outcomes. We collect usage counts across multiple O365 workloads.) |


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

>我們不會控制合作夥伴系統上的資料

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Nulia 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
