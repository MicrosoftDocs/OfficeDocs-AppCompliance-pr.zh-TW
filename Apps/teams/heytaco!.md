---
title: HeyTaco 的應用程式資訊！ HeyTaco！
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: HeyTaco！的所有可用安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7b4641b33166043dd311bdd89568c9eaea4b87a1
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521636"
---
# <a name="heytaco"></a>HeyTaco！

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2020年11月3日</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

HeyTaco 所提供的資訊！ 至 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | HeyTaco！ |
| ID | WA200001346 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | HeyTaco！ |
| 合作夥伴網站的 URL | [https://www.heytaco.chat](https://www.heytaco.chat) |
| 隱私權原則的 URL | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| 使用條款的 URL | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 HeyTaco 所提供！ 關於此應用程式如何收集和儲存組織資料，以及您的組織將會對應用程式收集的資料所做的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 電子郵件 | 委託 | 用來比對使用者的資料傳輸從時差到 MS Teams | 用來比對使用者從時差到 MS 小組的資料傳輸 | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| openid | 委託 | 用於簽署人員加入 HeyTaco！ | 用於簽署人員加入 HeyTaco！ | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| profile | 委託 | 用於捕獲使用者名稱、設定檔影像、時區偏移量、租使用者識別碼及小組識別碼 | 用於捕獲使用者名稱、頭像、時區偏移量、租使用者識別碼及小組識別碼 | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 告訴使用者他們收到的是 taco，以及其來源。 | 從一個平臺 tacos 至另一個平臺的電子郵件地址 () 名稱 (供使用者) 設定檔影像 (，以在 leaderboard) 時區 (上顯示使用者設定檔影像) ，以根據租使用者匯總資料的承租人 (小組識別碼) 來聚合資料 (  |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>EUII 和 OII 未連接至任何記錄。 僅限錯誤類型和動作類型。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>HeyTaco！ 資料庫和資料備份是裝載在 Amazon Web 服務 (AWS) 上。 

Amazon 的資料中心作業已獲 ISO 27001、SOC 1 和 SOC 2/SSAE 16/ISAE 3402 (先前的 SAS 70 Type II ) 、PCI Level 1、FISMA 適中及 Sarbanes-Oxley (SOX) 。

當您透過我們的服務提交資訊時，您的資訊會受到保護，並以靜止的方式加密，並透過安全連線進行傳輸。 我們會執行各種安全性措施，以維護您個人資訊的安全性。

我們有適當的許可權存取管理，可保護我們伺服器上的資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

