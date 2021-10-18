---
title: CalendarHero by CalendarHero Inc. 的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CalendarHero 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d21943d1e10de86c82a3b0c814fa12f9513cbf74
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429391"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2020年3月17日</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 CalendarHero Inc. 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | CalendarHero |
| ID | WA200000150 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | CalendarHero Inc |
| 合作夥伴網站的 URL | [https://zoom.ai](https://zoom.ai) |
| Teams 應用程式資訊頁面的 URL | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| 隱私權原則的 URL | [https://zoom.ai/privacy-policy](https://zoom.ai/privacy-policy) |
| 使用條款的 URL | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

CalendarHero Inc. 已提供此資訊，供 Inc. 使用此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 包括 | 會議會在 Azure 的 mongoDB 中快取，但會加密描述。 | 存取使用者的行事曆事件。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| 連絡人。 ReadWrite | 包括 | 連絡人的名稱和電子郵件地址。 | 請閱讀使用者的連絡人 (，讓我們可以邀請他們加入會議) 。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | 包括 | 群組名稱和成員。 |  (選用) 「讀取公司使用者群組」 (可使用群組進行排程) 。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | 包括 | 連絡人的電子郵件/名稱、互動的頻率/recency。 |  (選用) 是用來將電子郵件中繼資料讀取至使用者最重要的連絡人 (透過機器學習) 。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings ReadWrite | 包括 | 使用者的時區。 | 使用者的時區。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read.All | 包括 | &amp;以連絡人) 儲存的使用者名稱電子郵件 (。 |  (選用) 讀取公司使用者 (，以與同事排程)  | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | 應用程式 | 否 | 我們需要在使用者可以隨時讀寫，而不會顯示使用者。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 匯入名稱/同事的電子郵件，讓我們的會議助理 bot 可以排程會議 | 名稱 &amp; 電子郵件。 兩者都是儲存在我們的資料庫中，以供快速查閱及部分名稱查閱 (例如。 與 Joe P) 會面 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>使用者和/或連絡人的電子郵件地址是用來將事件記錄至 LogDNA，我們的記錄提供者。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>所有資料都是儲存在以魁北克城市（加拿大）為單位的 MS Azure 雲端資料中心。 有幾個欄位已使用 AES256 加密。 只有透過使用者/服務層級認證的工程師和後端伺服器可以存取資料庫。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

