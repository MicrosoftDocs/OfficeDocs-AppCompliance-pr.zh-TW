---
title: 依決策決定的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可供決策的安全性和符合性資訊資訊、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 19a710fc8edbcb5243b81755ce3d61e8bcaa5b25
ms.sourcegitcommit: 3660f89e183c638979a31c295ac059daa6c387dd
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/18/2021
ms.locfileid: "58391878"
---
# <a name="decisions"></a>決定

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員的更新日期：2021年6月2日</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

依決策提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 決定 |
| ID | WA104381880 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 決定 |
| 合作夥伴網站的 URL | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| 隱私權原則的 URL | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| 使用條款的 URL | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是透過相關決策提供的，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **權限**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ReadWrite 的行事曆 | 委託 | 用於從使用者&#8217;的行事曆讀取資訊，以啟用會議清單和搜尋等功能。 當專案從決策中刪除時，也可讓使用者選擇從行事曆刪除特定會議。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| 聊天室 ReadWrite | 委託 | 用來傳送投票的決議決策，並直接對 Microsoft Teams 會議聊天建立個別議程專案的發言人清單。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | 委託 | 用於在註冊時收集 Office 365 租使用者的基本資訊，例如租使用者名稱和驗證的網域。 驗證群組成員資格也是必要的。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | 委託 | 用於讀取與使用者共用的檔案，以將這些檔案合併至 PDF 會議簿。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | 委託 | 用來為使用者提供個人檔批註的支援。 批註的檔案是私下儲存在使用者&#8217;s 商務用 OneDrive 中。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | 委託 | 用於在 Office 365 群組中建立資料夾結構，以供會議議程、相關檔案和群組交談&#8217;s SharePoint 網站。   附注：決策的使用者永遠不會存取任何資源 (例如，群組) 尚未存取組織 Office 365 租使用者的許可權。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| 傳送郵件 | 委託 | 用來允許使用者決定傳送會議參與者通知，例如議事日程更新，以及共同撰寫者的會議連結。 電子郵件會移至會議參與者或會議擁有者所選取的通訊群組清單。 所有傳送的通知和電子郵件都會以決策使用者的方式積極完成。  附注：這不會讓使用者透過決策來存取其收件匣。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings 讀取 | 委託 | 用於識別使用者&#8217;的語言喜好設定。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| 記事。 ReadWrite | 委託 | 用於為會議設定私人筆記本，以做筆記並準備備註和問題。 您也可以將群組會議紀要儲存在其共用 OneNote 筆記本中（應該是群組選擇使用 OneNote。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | 委託 | 用於建立會議資訊的私人通道中的資料夾結構。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| 工作。 ReadWrite | 委託 | 用於將工作和決策同步處理至 Microsoft Planner。 它也可讓使用者將工作和決策匯出至 Excel。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | 委託 | 需要以程式設計方式在聊天中安裝決策應用程式。 在為會議經驗新增 [決策] 索引標籤之前，必須先這麼做。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation ReadWriteForUser 所有 | 委託 | 需要以程式設計方式在聊天中安裝決策應用程式。 在為會議經驗新增 [決策] 索引標籤之前，必須先這麼做。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab。建立 | 委託 | 需要在 Teams 中新增 [會議/通道] 索引標籤。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab Read。 All | 委託 | 需要檢查是否已安裝索引標籤。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | 委託 | 用來顯示群組成員和外部參與者的名字和姓氏、相片和電子郵件地址。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| 設定檔 | 委託 | 用於登入。 | 客戶資料會儲存在客戶&#8217;s Office 365 承租人中，而且所有客戶資料只會在客戶裝置上處理。 決策資料庫只會維護客戶 Office 365 承租人中物件的參照，而不是實際的資料。 如需詳細資訊，請參閱 https://www.meetingdecisions.com/security-and-privacy 。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


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

>使用軟體時，客戶所提供的資料僅可供客戶使用。  服務是在 Microsoft Office 365 雲端服務和 Microsoft Azure 上傳遞。 所有客戶資料都儲存在客戶 Microsoft Office 365 承租人中。 所有儲存或處理于服務上的資料都是匿名的，且對個別人員不可追蹤。 如此一來，決策將不會代表客戶儲存、收集或處理個人資料。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是透過相關決策提供，此應用程式如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 是 |
| 列出支援的原則類型 | 全部 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 是 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | -萬用字元重新導向 URIs，<br/>-OAuth2 隱含 Flow （除非 SPA 是必要的）<br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
