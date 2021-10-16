---
title: Enterprise 數位機器的 FormMachines 應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: FormMachines 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: be8e514f248b177d0b09e856d5537e770d50220c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411047"
---
# <a name="formmachines"></a>FormMachines

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新：2021年7月5日</p>

* <a href="https://teams.microsoft.com/l/app/54d8b826-3e30-4589-a77a-ed99cfbbb4c9" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001217" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Enterprise 的數位機器所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | FormMachines |
| ID | WA200001217 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 企業數位電腦 |
| 合作夥伴網站的 URL | [https://www.formmachines.com](https://www.formmachines.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.FormMachines.com](https://www.FormMachines.com) |
| 隱私權原則的 URL | [https://www.formmachines.com/dist/docs#/statements_and_agre...](https://www.formmachines.com/dist/docs#/statements_and_agreements/privacy) |
| 使用條款的 URL | [https://www.formmachines.com/dist/docs#/statements_and_agre...](https://www.formmachines.com/dist/docs#/statements_and_agreements/terms_of_service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

這種資訊已透過 Enterprise 數位機器來提供，此應用程式會如何收集和儲存組織的資料，以及您的組織將會透過應用程式收集的資料所產生的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>此應用程式不會使用 Microsoft Graph。


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>在我們的錯誤記錄檔中，我們通常只會記錄與錯誤有關的資訊。 不過，為了協助特定客戶，我們可能會找出相關的網域，但不是客戶本身。 線上查看錯誤記錄，未下載和查看。 在90天后會自動刪除錯誤記錄檔。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>資料儲存在以 Azure 為基礎的資料中心。 在 DB/BLOB 中，用戶端提供的資料（如範本和報送）已加密。 檔案附件儲存于私人 Azure BLOB 容器中，使用者必須先進行驗證，才能進行存取。 我們有最多兩個系統管理員可以存取我們的實際執行資產，以進行疑難排解和部署。 這兩個系統管理員帳戶會以不同方式將所有其他帳戶分割。 系統管理存取權的數目不會超過兩個。 

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是透過 Enterprise 數位機器提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

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
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

