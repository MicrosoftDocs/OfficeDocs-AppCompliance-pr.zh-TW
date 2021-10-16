---
title: Senso 的應用程式資訊（按 Senso）
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Senso 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c517e652c97ba8a74cbadd9b6121084dd40c5394
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414459"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月2日</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Senso 提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Senso |
| ID | WA200002571 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Senso |
| 合作夥伴網站的 URL | [https://www.senso.cloud](https://www.senso.cloud) |
| Teams 應用程式資訊頁面的 URL | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| 隱私權原則的 URL | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| 使用條款的 URL | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Senso 提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadBasic | 應用程式 | 閱讀所有通道的通道名稱和描述，以識別標示違規的位置。   | 當侵犯者的名稱 (從) 時，收件者的 name () 的收件者 (、通道名稱、日期、時間及來自該聊天室通道的訊息，都是為了提供違規內容的記錄。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember Read。 All | 應用程式 | 讀取所有通道的成員清單和聊天訊息。 | 當侵犯者的名稱 (從) 時，收件者的 name () 的收件者 (、通道名稱、日期、時間及來自該聊天室通道的訊息，都是為了提供違規內容的記錄。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage Read。 All | 應用程式 | 讀取所有通道郵件 | 當侵犯者的名稱 (從) 時，收件者的 name () 的收件者 (、通道名稱、日期、時間及來自該聊天室通道的訊息，都是為了提供違規內容的記錄。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| 已閱讀的聊天室。所有 | 應用程式 | 讀取所有聊天訊息 | 當侵犯者的名稱 (從) 時，收件者的 name () 的收件者 (、通道名稱、日期、時間及來自該聊天室通道的訊息，都是為了提供違規內容的記錄。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | 應用程式 | 讀取目錄資料 | 當侵犯者的名稱 (從) 時，收件者的 name () 的收件者 (、通道名稱、日期、時間及來自該聊天室通道的訊息，都是為了提供違規內容的記錄。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | 應用程式 | 讀取所有網站集合中的檔案 | 當侵犯者的名稱 (從) 時，收件者的 name () 的收件者 (、通道名稱、日期、時間及來自該聊天室通道的訊息，都是為了提供違規內容的記錄。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | 委託 | 登入並讀取使用者設定檔 | 用於單一登入 | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | 應用程式 | 讀取所有使用者的完整設定檔 | 當侵犯者的名稱 (從) 時，收件者的 name () 的收件者 (、通道名稱、日期、時間及來自該聊天室通道的訊息，都是為了提供違規內容的記錄。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud 會使用下列子處理器，以取得其服務的效能： https://www.senso.cloud/privacy-policy/ 第5節。 個人資料的披露。 | 與協力廠商帳戶和協力廠商提供者分享的資料類型，會在 [資料表 (] 的 [righthand] 欄中設定出來 https://www.senso.cloud/privacy-policy/) 。 | 處理每個元件的法律是以合約效能為基礎，以與您或必要 (的合約效能為基礎，以供公司、封存資料、管理與 IT 服務、網路安全性等運作，以防止欺詐和資料被破壞。 例如，若要將帳單連絡人通知傳送給客戶，則必須有商務郵寄地址、電子郵件地址，或如果是信用卡付費，則 access 客戶支援時，需要提供資訊以提升支援票證。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud 會使用下列子處理器，以取得其服務的效能： https://www.senso.cloud/privacy-policy/ 第5節。 個人資料的披露。 | 與協力廠商帳戶和協力廠商提供者分享的資料類型，會在 [資料表 (] 的 [righthand] 欄中設定出來 https://www.senso.cloud/privacy-policy/) 。 | 處理每個元件的法律是以合約效能為基礎，以與您或必要 (的合約效能為基礎，以供公司、封存資料、管理與 IT 服務、網路安全性等運作，以防止欺詐和資料被破壞。 例如，若要將帳單連絡人通知傳送給客戶，則必須有商務郵寄地址、電子郵件地址，或如果是信用卡付費，則 access 客戶支援時，需要提供資訊以提升支援票證。 |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>Senso 會根據關鍵字及影像威脅偵測庫來監視聊天訊息。  如果發生相符，我們會針對違規觸發器記錄下列資訊：使用者可供查看的時間與日期、網站識別碼、片語/Image、嚴重性、寄件者、頻道 Name,Status 及觸發程式庫。  我們只會在必要時保留 PII，以 fulfil 我們收集的目的，包括為了滿足任何法律、運作、會計或報告需求的目的。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>對資深開發人員、IP 鎖定、2要素驗證和審核追蹤的有限存取權。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Senso 此資訊的提供方式是關於此應用程式如何處理驗證、授權、應用程式註冊最佳作法和其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 以角色為基礎的存取權限 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

