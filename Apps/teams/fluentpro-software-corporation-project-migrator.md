---
title: FluentPro 軟體公司 Project 遷移程式的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 在 CSA 星型登錄中 Project 遷移器、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊及安全性/符合性資訊的所有可用安全性和符合性資訊資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 1569bf8fe9cf8dd2e1f96e857d0a9f2a63af774a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428065"
---
# <a name="project-migrator"></a>Project Migrator

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月17日</p>

* <a href="https://teams.microsoft.com/l/app/8cd35615-e306-4b3d-8e93-17520129b60a" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003160" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

FluentPro 軟體公司所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Project Migrator |
| ID | WA200003160 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | FluentPro Software Corporation |
| 合作夥伴網站的 URL | [https://projectmigrator.com](https://projectmigrator.com) |
| Teams 應用程式資訊頁面的 URL | [https://help.fluentpro.com/147404-project-migrator](https://help.fluentpro.com/147404-project-migrator) |
| 隱私權原則的 URL | [https://projectmigrator.com/privacy-policy](https://projectmigrator.com/privacy-policy) |
| 使用條款的 URL | [https://projectmigrator.com/terms-of-use](https://projectmigrator.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 FluentPro 軟體公司提供，此應用程式是關於此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 委託 | 讀取群組及其成員資格，以便遷移至其他租使用者。 | 沒有儲存此許可權的資料。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Group.ReadWrite.All | 委託 | 群組名稱、成員、計畫及任務。 使用群組、計畫及任務資訊進行 Planner 資料移轉。 | 組名、計畫名稱和任務名稱。 用於遷移資訊的摘要。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Sites.ReadWrite.All | 委託 | 遷移 MS Planner 任務附件的 SharePoint 檔。 | 沒有儲存此許可權的資料。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | 委託 | 用來儲存毫秒規劃器遷移摘要資訊連結至帳戶的 UPN。 | UPN。 | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.ReadBasic.All | 委託 | 使用使用者資訊來遷移 MS Planner 工作指派和群組成員資格。 | 沒有儲存此許可權的資料。  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| offline_access | 委託 | 重新整理和存取權杖會使用 access 毫秒規劃器資料。 | 會儲存加密重新整理權杖，以存取 MS Planner 資料。 | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | 委託 | 名字、姓氏、公司名稱、電話、公司電子郵件。 用於註冊和驗證程式的資料。 | 名字、姓氏、公司名稱、電話、公司電子郵件、UPN。 | [c36d31a2-8de1-4eb5-9e7d-01da45244c04](https://docs.microsoft.com/microsoft-365-app-certification/azure/c36d31a2-8de1-4eb5-9e7d-01da45244c04) |


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

>https://projectmigrator.com/privacy-policy

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由 FluentPro 軟體公司提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 否 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
