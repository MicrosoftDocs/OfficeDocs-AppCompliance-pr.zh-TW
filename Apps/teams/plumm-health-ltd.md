---
title: Plumm by Plumm Health 有限公司的應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Plumm 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8fef6e74339b611b06d39e6bbe32f9661e20656c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429871"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年8月18日</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Plumm Health 公司所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Plumm |
| ID | WA200003326 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Plumm Health LTD |
| 合作夥伴網站的 URL | [https://www.plummhealth.com](https://www.plummhealth.com) |
| Teams 應用程式資訊頁面的 URL | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| 隱私權原則的 URL | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| 使用條款的 URL | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

Plumm 健康情況公司會提供此資訊，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | 應用程式 | 我們會在此許可權中使用 userID。 這是根據服務的使用方式，用來將必要的通知傳送給使用者。 這對於使用者在其應用程式上收到其帳戶的適當通知很重要。 | 在此許可權中，我們不會將任何資料儲存在資料庫中。 實際上，我們使用使用者識別碼，根據其使用方式將適當的通知傳送給每個個別使用者。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation ReadWriteForUser 所有 | 應用程式 | 我們會使用此許可權取得安裝識別碼。 這對我們來說很重要，因為您可以為每個個別使用者傳送適當和正確的通知。 | 使用此許可權時，我們不會儲存應用程式中的任何資料。 我們不需要它，因為我們只需要在執行時間取得 userID，即可取得安裝 ID。 這是在執行時間動態取得，因此不需要儲存安裝識別碼。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | 委託 | 我們會透過此許可權來收集使用者的名稱、圖片和電子郵件。 這是必要的，讓我們能夠識別個別的使用者，而這些資料點應顯示任何必要的地方，例如個別的設定檔頁面面和電子郵件/通知通訊。 | 此許可權可讓我們的應用程式查看我們的使用者基本設定檔 (名稱、圖片、電子郵件) 。 此資料將用來顯示使用者在其應用程式帳戶上的名稱和（或）設定檔圖片與我們的電子郵件通訊和/或通知。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | 應用程式 | 此許可權允許我們的應用程式讀取未登入使用者的使用者設定檔。 在此，我們目前正在收集名稱、設定檔圖片和電子郵件。 這是必要的，讓我們能夠識別個別的使用者，而這些資料點應顯示任何必要的地方，例如個別的設定檔頁面面和電子郵件/通知通訊。 | 此許可權可讓我們的應用程式查看我們的使用者基本設定檔 (名稱、圖片、電子郵件) 。 此資料將用來顯示使用者在其應用程式帳戶上的名稱和（或）設定檔圖片與我們的電子郵件通訊和/或通知。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| 電子郵件 | 委託 | 會收集使用者的電子郵件識別碼。 我們需要這項資料，以授與使用者存取權給我們的服務，並登入我們的應用程式，並在此電子郵件識別碼上收到有關其帳戶和服務的通知。  | 電子郵件識別碼會儲存在資料庫中。 我們需要儲存電子郵件識別碼，以唯一識別使用者、讓他們能夠存取我們的應用程式、協助他們登入，並協助他們接收與我們帳戶有關的通知。 例如，具有電子郵件識別碼的使用者 &quot; 在 &quot; 登入至使用此電子郵件識別碼的 Teams 時，將可以存取我們的應用程式和服務。 根據使用狀況，我們可以在他/她的電子郵件識別碼中將通知傳送給此使用者。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | 委託 | 針對此許可權，我們不會收集任何資料。  | 針對此許可權，我們不會收集任何資料。 此許可權可讓使用者使用其工作電子郵件識別碼登入我們的應用程式，並讓應用程式可以查看基本的使用者設定檔資訊。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| 設定檔 | 委託 | 我們會透過此許可權來收集使用者的名稱、圖片和電子郵件。 這是必要的，讓我們能夠識別個別的使用者，而這些資料點應顯示任何必要的地方，例如個別的設定檔頁面面和電子郵件/通知通訊。 | 此許可權可讓我們的應用程式查看我們的使用者基本設定檔 (名稱、圖片、電子郵件) 。 此資料將用來顯示使用者在其應用程式帳戶上的名稱和（或）設定檔圖片與我們的電子郵件通訊和/或通知。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>| **所有非 Microsoft 服務 OII 會轉接至** |  **哪一個 OII 會轉接？** | **傳輸 OII 的理由？** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 對講機 | 名字、姓氏、電子郵件 | Intercom 是我們的 CRM，可協助我們管理我們所有使用者的交流。 這就是為什麼我們需要將使用者的名字、姓氏和電子郵件識別碼傳送給 CRM，讓適當的訊息/電子郵件可以傳送給使用者。 |

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>我們會儲存服務使用方式資料，例如使用的 therapy 會話數目、查看的課程、meditations 的查看、會話日期等等。我們保留使用者的資料，直到使用者特別要求其帳戶被刪除或「遺忘」。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>我們會透過我們的伺服器管理傳送至 CRM 的資料。 運作所需的最少資料會傳送至 CRM (Intercom) 。 Plumm 可完全控制傳遞給 CRM 的資料、Intercom 上的資料保留，以及刪除。 以下是複查 Intercom 之客戶資料原則的連結： https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

Plumm 健康情況公司會提供此資訊，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？  | 是 |
| 您的應用程式是否使用 MSAL (Microsoft 驗證程式庫) 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否要求最小許可權許可權給您的案例？ | 是 |
| 您的應用程式的靜態註冊許可權是否要準確反映您的應用程式將動態和以增量方式要求的許可權？ | 是 |
| 您的應用程式是否支援多租賃？ | 否 |
| 您的應用程式有機密用戶端嗎？ | 是 |
| 您是否擁有為您的應用程式註冊的所有重新導向統一資源識別元 (URI) ？ | 是 |
| 您的應用程式，您避免使用什麼？ | ,<br/><br/>-Resource 物主密碼認證 (ROPC) 流程 |
| 您的應用程式是否公開任何 web APIs？ | 是 |
| 如果用戶端應用程式收到適當的同意，您的許可權模型是否只允許通話成功？ | 是 |
| 您的應用程式是否使用預覽 APIs？ | 否 |
| 您的應用程式使用的 APIs 是否已遭取代？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
