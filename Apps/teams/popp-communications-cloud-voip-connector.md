---
title: POPP Cloud VoIP Connector 的應用程式資訊（透過 POPP 通訊）
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于 POPP 雲端 VoIP 連接器的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c13790c3baa08d584343e9d504251e3920204b22
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60438722"
---
# <a name="popp-cloud-voip-connector"></a>POPP Cloud VoIP Connector

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年9月20日</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

POPP 與 Microsoft 的通訊所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | POPP Cloud VoIP Connector |
| ID | WA200003306 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | POPP Communications |
| 合作夥伴網站的 URL | [https://popp.com](https://popp.com) |
| 隱私權原則的 URL | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| 使用條款的 URL | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊已透過 POPP 相關資訊提供此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember Read。 All | 委託 | 使用者 IDs 及顯示目前通道之成員的名稱。 應用程式會使用這種方式，向使用者呈現要呼叫的通道成員清單。 | Metaswitch 不會儲存此資料。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| 聊天室讀取 | 委託 |  收集或使用的資料為何？ 新增論證，以收集或使用資料。 使用者 IDs 及顯示目前交談的成員名稱。 應用程式會使用這種方式，向使用者呈現要呼叫的聊天成員清單。 | Metaswitch 不會儲存此資料。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember Read。 All | 委託 | 使用者 IDs 及顯示目前小組成員的名稱。 應用程式會使用這種方式，向使用者呈現要呼叫的小組成員清單。 | Metaswitch 不會儲存此資料。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | 委託 |  收集或使用的資料為何？ 新增論證，以收集或使用資料。 使用者的商務和行動電話號碼。 這是必要的動作，才能啟動這些號碼的撥打電話。 |   Metaswitch 不會儲存此資料 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | 委託 | 使用者的授權權杖，用來授權應用程式，以存取其所列的其他 Graph API 端點。 | Metaswitch 不會儲存此資料。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>使用其他 Microsoft APIs 的資料存取權

以 Microsoft 365 為基礎的應用程式和增益集可能會使用 microsoft Graph 以外的其他 Microsoft APIs，來收集或處理組織識別資訊 (OII) 。 列出此應用程式使用的 microsoft Graph 以外的任何 microsoft APIs。

>| **API** |  **是否 OII 收集？** |  **收集的 OII 是什麼？** | **收集 OII 的理由？** | **OII 是否儲存？** | **儲存 OII 的理由？** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft 身分識別平臺 | 否 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Metaswitch 網路和 POPP 通訊 | 下列 OII 會轉接至 MCT Hosted Bot 伺服器： Azure AD 租使用者識別碼小組 IDs 通道/聊天 IDs 郵件內容也會傳輸，其中可能包含 OII 下列 OII 可能會轉接至 CommPortal JSON API 電話：商務群組中的使用者人數電子郵件地址的網域的使用者 IP 位址 | 新增理由以供您需要 OII 應用&#8217;程式的主要目的，以協助通話。 若使用者嘗試撥打電話，必須提供此資訊，才能登入其 CommPortal 帳戶，並將來電關聯回正確的使用者。  傳輸至 MCT Hosted Bot 伺服器的 OII 是內置於 Bot Framework API 中，該 API 是用來與 Teams 進行整合，而且無法避免。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| App&#8217;主要目的是協助通話。 如果使用者嘗試撥打電話，必須為通話中的所有各方提供 EUII，以便在正確的電話語音使用者之間建立通話。 | 否 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>Metaswitch 和 POPP 不會將資料儲存在立即需要從 CommPortal Web 載入 MCT 網頁的時間。 不會保留資料，而且會立即移除。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是透過 POPP 有關此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則的通訊而提供。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 否 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 用於驗證的 MSAL 程式庫自動提供此類支援範圍的條件式存取原則。  |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 否 |
| 您的應用程式有機密用戶端嗎？ | 否 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/><br/> |
| 您的應用程式是否公開任何 web APIs？ | 否 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
