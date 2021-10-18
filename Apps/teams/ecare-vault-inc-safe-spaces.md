---
title: ECare Vault Inc. 的保管庫空間應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊資訊保管庫空間、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 81ba62364331fd3c3b9ff517bb8475665dd76cbe
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60426775"
---
# <a name="safe-spaces"></a>安全空間

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年7月14日</p>

* <a href="https://teams.microsoft.com/l/app/ec321cf7-ae3e-4ed4-a707-ff5c18e77313" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002691" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

ECare 保存庫 Inc. 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 安全空間 |
| ID | WA200002691 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | eCare Vault Inc. |
| 合作夥伴網站的 URL | [https://ecarevault.com](https://ecarevault.com) |
| Teams 應用程式資訊頁面的 URL | [https://ecarevault.com/ecare-vault-for-teams](https://ecarevault.com/ecare-vault-for-teams) |
| 隱私權原則的 URL | [https://ecarevault.com/ecare-vault-privacy-policy](https://ecarevault.com/ecare-vault-privacy-policy) |
| 使用條款的 URL | [https://downloads.ecarevault.com/downloads/eCare+Vault+-+Te...](https://downloads.ecarevault.com/downloads/eCare+Vault+-+Terms+of+Service.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

ECare Vault Inc. 已提供此資訊。關於此應用程式如何收集和儲存組織的資料，以及您的組織將會對應用程式所收集的資料所做的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| EduRoster 讀取 | 委託 | 使用的名稱和日期出生輸入欄位 | None-所有儲存的資料都是使用者送出的 (資料只填入欄位，然後使用者送出)  | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| Group.Read.All | 委託 | 用於取得可在應用程式中顯示的通道相關資訊 | 無來自此許可權 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| GroupMember Read。 All | 委託 | AAD用來產生 eCare Vault 小組名單的群組成員識別碼 | AAD使用者識別碼儲存為與每個成員的 eCare Vault 使用者帳戶相關聯 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read | 委託 | 用來簽署使用者的電子郵件地址和 AAD 識別碼， &amp; 並將其與 eCare Vault 使用者帳戶關聯 | 使用者帳戶的電子郵件地址和 AAD 識別碼，以及透過 Bot Framework 傳送通知給使用者 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| User.Read.All | 委託 | 名稱和、AAD 識別碼及電子郵件地址，只適用于已安裝保管庫空間之通道的成員的使用者 | 針對 eCare Vault 使用者帳戶所儲存的名稱、AAD 識別碼及電子郵件地址 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| 電子郵件 | 委託 | 僅限電子郵件地址 | 無-使用者決定提交表單，  | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| openid | 委託 | 用來簽署使用者的電子郵件地址和 AAD 識別碼， &amp; 並將其與 eCare Vault 使用者帳戶關聯 | 使用者帳戶的電子郵件地址和 AAD 識別碼，以及透過 Bot Framework 傳送通知給使用者 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |
>| 設定檔 | 委託 | 使用者的名稱是用來填入使用者的註冊畫面。 | 無直接-使用者在註冊時選擇將其名稱提交給系統 | [6919164d-b678-4c3d-a268-e6fbecc1e68d](https://docs.microsoft.com/microsoft-365-app-certification/azure/6919164d-b678-4c3d-a268-e6fbecc1e68d) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| MSAL (Microsoft 驗證端點)  | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| eCare Vault | 承租人/公司資訊、使用者登入功能變數名稱、使用者登入資訊 Microsoft Teams 小組 &amp; 通道識別碼。 | 保管庫空格是 eCare Vault 平臺的伴生應用程式。 OII 是將使用者從 Microsoft Teams 連結到公司的 eCare Vault 使用者所需的。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>所有移至協力廠商系統的資料 (不會包含任何 OII、PII 或 PHI) 會在 BAA 下傳輸，以確保 HIPAA 相容性。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

ECare Vault Inc. 已提供此資訊。關於此應用程式如何處理驗證、授權、application registration 最佳作法，以及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 否 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 是 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
