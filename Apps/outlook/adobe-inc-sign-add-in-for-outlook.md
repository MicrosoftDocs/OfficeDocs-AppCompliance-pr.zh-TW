---
title: adobe inc. 的 adobe Sign Add-In Outlook 的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 02/22/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: 所有適用于 Outlook 的 Adobe 簽署 Add-In 的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6f4fc90e6ec7953e2f399022e701119e2db24b6b
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526499"
---
# <a name="adobe-sign-add-in-for-outlook"></a>Outlook 的 Adobe Sign Add-In

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員更新：2021年2月22日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381158" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Adobe Inc. 所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Outlook 的 Adobe Sign Add-In |
| ID | WA104381158 |
| 支援 Office 365 用戶端 | Outlook 2013 或更新版本的 Mac Windows Outlook 2016 或更新版本 Outlook 網頁版 |
| 合作夥伴公司名稱 | Adobe Inc.。 |
| 合作夥伴網站的 URL | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| 隱私權原則的 URL | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| 使用條款的 URL | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Adobe Inc. 已提供此資訊。關於此應用程式如何收集和儲存組織的資料，以及您的組織將會對應用程式所收集的資料所做的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| 郵件。 ReadWrite | 委託 | 若要將附加的檔、寄件者和收件者電子郵件，以及郵件內容從電子郵件寫入為 Adobe sign，以進行簽章簽名。 這是為了儲存使用者時間，以 Adobe 符號重新輸入這些欄位。 在簽署合約後，我們會自動撰寫新的電子郵件，讓使用者傳送電子郵件通知給收件者交易已完成。 | Adobe 簽署會將附件儲存為臨時檔案，其到期期限為24小時。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| 個人讀取 | 委託 | 若要在 [傳送以供簽章經驗] 中自動填滿電子郵件地址 &quot; &quot; ，請輸入一些初始字母，不需要使用者輸入整個電子郵件。 | Adobe 簽署只會將收件者的電子郵件和 displayName 儲存在協定中。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| User.Read | 委託 | 若要讀取使用者的設定檔並比對其設定檔 (基本上，他們的電子郵件和 userId) 到資料庫，讓他們可以使用 Adobe Sign。 | 若要讀取使用者的設定檔並比對其設定檔 (基本上，他們的電子郵件和 userId) 到資料庫，讓他們可以使用 Adobe Sign。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| offline_access | 委託 | 若要在目前的憑證到期時重新整理存取權杖。 例如，當使用者在 [ &quot; 傳送簽名 &quot; ] 視窗中並保持停用狀態的時間過長時，當使用者使用中時，我們需要重新整理新的權杖。 | 若要在目前的憑證到期時重新整理存取權杖。 例如，當使用者在 [ &quot; 傳送簽名 &quot; ] 視窗中並保持停用狀態的時間過長時，當使用者使用中時，我們需要重新整理新的權杖。 | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |
>| openid | 委託 | 電子郵件和 UserId。 若要為使用者簽署，以確保其同意使用 Adobe Sign app 的許可權。  | Email 是 Adobe Sign 中使用者的唯一識別碼。 我們會儲存電子郵件識別碼，以便將該使用者的所有活動對應至其 Adobe 簽署記錄。  | [72d5ac5d-a427-408b-907d-72da3f33ddd1](https://docs.microsoft.com/microsoft-365-app-certification/azure/72d5ac5d-a427-408b-907d-72da3f33ddd1) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們的記錄檔包含的資訊足以識別並修正客戶問題。 記錄會在90天內保留，並且限制存取。 在使用者離線時，用於驗證的資料庫儲存區雜湊識別資訊。 資料庫保留原則為自上次使用的30天

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們在 Microsoft Outlook 應用程式的系統中，我們沒有任何客戶系統管理員互動。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Adobe Inc. 已提供此資訊。此應用程式如何處理驗證、授權、application 註冊最佳作法，以及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 否 |
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
