---
title: 動態信號的應用程式資訊（透過動態信號）
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊資訊，如動態信號、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d25efd4a6dffac1dde98995505e5ca913a8e4501
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60435607"
---
# <a name="dynamic-signal"></a>動態訊號

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Microsoft 提供的動態信號資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 動態訊號 |
| ID | WA200000102 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 動態訊號 |
| 合作夥伴網站的 URL | [https://www.dynamicsignal.com](https://www.dynamicsignal.com) |
| Teams 應用程式資訊頁面的 URL | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| 隱私權原則的 URL | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| 使用條款的 URL | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是透過動態信號提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委託 | 動態信號會將使用者從 Azure AD 同步處理至其平臺，以允許即時簡化及停用使用者。 資料會儲存在動態信號內，以允許使用者在同步處理的情況下使用該應用程式。 | 特定使用者的讀取權限，可同步處理動態信號平臺使用者與 Azure AD。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| User.Read.All | 委託 | 動態信號會將使用者從 Azure AD 同步處理至其平臺，以允許即時簡化及停用使用者。 資料會儲存在動態信號內，以允許使用者在同步處理的情況下使用該應用程式。 | 特定使用者的讀取權限，可同步處理動態信號平臺使用者與 Azure AD。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| offline_access | 委託 | 動態信號會將使用者從 Azure AD 同步處理至其平臺，以允許即時簡化及停用使用者。 資料會儲存在動態信號內，以允許使用者在同步處理的情況下使用該應用程式。 | 保留對租使用者群組和團隊的存取權。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| openid | 委託 | 動態信號會將使用者從 Azure AD 同步處理至其平臺，以允許即時簡化及停用使用者。 資料會儲存在動態信號內，以允許使用者在同步處理的情況下使用該應用程式。 | 使用動態信號應用程式驗證使用者。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| openid using 使用 openid 目錄。 readwrite。對租使用者的網域和群組的所有存取權，將應用程式新增至小組 offline_access 保留租使用者群組和小組的存取權 | openid 允許獨立驗證。 目錄 readwrite。對租使用者的網域和群組的所有存取權，將應用程式新增至小組 offline_access 繼續存取租使用者的群組和小組注意：動態信號的應用程式會使用小組 bot，將動態信號內所建立的群組和許可權套用至 Teams，這樣，在動態信號內使用的使用者便可以存取相同的群組和 Teams 中的使用者。 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>動態信號應用程式和平臺使用使用者資訊，促進與 Microsoft Teams 的整合。 在動態信號平臺內具有適當許可權的使用者可使用此資訊。 相關資訊為 [名稱]、[顯示名稱] 和 [電子郵件]。 此資訊會依照具有動態信號授權的各個組織原則，儲存在動態信號平臺記錄中。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>註冊期間收集的 PII 資料，以及儲存在動態信號平臺內的資料包括：名字、姓氏、電子郵件/識別碼，以及由品牌和/或代理人合作夥伴設定的任何自訂欄位。 當成員使用 Facebook 註冊時，有些公開的使用者資料會呈現給動態信號平臺，以預先填滿的資料。 此資料包括名稱、位置和照片。 使用者可以控制在社區的 bio 頁面上，向使用者呈現哪些資訊和資料。 成員可以選擇載入個人或商標照片、連線社交帳戶/通道，以及程式中要顯示在 [bio] 頁面中的使用/點。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

