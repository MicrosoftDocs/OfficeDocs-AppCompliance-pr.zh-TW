---
title: 由波羅的文 Amadeus 所懷舊的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用於懷舊的安全性和符合性資訊資訊、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553454"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2020年11月3日</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由波羅的文 Amadeus 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Retro |
| ID | WA200001892 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Baltic Amadeus |
| 合作夥伴網站的 URL | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| 隱私權原則的 URL | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| 使用條款的 URL | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊已由波羅的文 Amadeus 提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-------------------|:--------------------------|:--------------------------|
>| 懷舊型應用程式有它自己的 Web API，但不會被視為 Microsoft 服務。 如先前所述，它會儲存電子郵件和 Fullname，以供識別及適當的內容顯示目的。 此資料不會傳送至其他地方。 此外，懷舊具有將衝刺資料匯出為 Atlassian confluence space 的選用功能。 若要這麼做，使用者必須輸入他們的 confluence 使用者名稱和密碼。 此資料只會用來代表使用者對 confluence api 進行已驗證的要求，而且不會儲存也不會登入任何地方。 |  | 懷舊型有其自己的 Web API，也已于 azure 中註冊。 若要使用此功能，必須透過 Microsoft Identity Platform 驗證使用者。 使用者必須經過驗證，才能讓懷舊應用程式可以伺服器使用者特定內容 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot 會存取名單，以檢查加入或離開小組的成員。 根據這一點，它會從專案中新增或停用該使用者，以便使用者不再顯示在衝刺參與者清單中。 | 電子郵件和 FullName 會連結在一起，並儲存在資料庫中。 電子郵件用於使用者識別，以便顯示登入使用者的適當內容。 FullName 用於顯示 puproses，因此其他使用者可以知道他們正在評估或寫入意見反應。  |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>否。 在懷舊式應用程式中產生遙測/記錄的唯一處理程式是錯誤記錄。 錯誤記錄不包含任何 EUII 或 OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料儲存在 azure sql server 資料庫中。 它是透過懷舊式應用程式和懷舊的 bot 儲存。
根據預設，azure sql database 已啟用透明的資料加密。
資料庫已鎖定基本驗證的背後。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

