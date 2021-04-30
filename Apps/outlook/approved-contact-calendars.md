---
title: 經核准連絡人的已核准連絡人行事曆應用程式資訊
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: 所有可用的安全性和符合性資訊，如核准的連絡人行事曆、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 37da37f6e5cad32ce97c4da537bc9ff7bd9d81a4
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094092"
---
# <a name="approved-contact-calendars"></a>核准的連絡人行事曆

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次於開發人員更新：2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

核准的連絡人所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 核准的連絡人行事曆 |
| ID | WA104380294 |
| 支援 Office 365 用戶端 | Outlook 2013 或更新版本的 Mac 上的 Windows、Outlook 2016 或更新版本 Outlook 網頁上的 |
| 合作夥伴公司名稱 | 已核准的連絡人 |
| 合作夥伴網站的 URL | [https://approvedcontact.com/](https://approvedcontact.com/) |
| 隱私權原則的 URL | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| 使用條款的 URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp; omkt = en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊已透過核准的連絡人提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 委託 | 在行事曆 BOT 中，我們會儲存使用者空閒/忙碌時間，以找出多個人的閒置時間。  | 我們讀取及比較空閒/忙碌時間及排程會議。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| 連絡人。已讀取 | 委託 | 是的，我們會儲存連絡人資訊。 | 匯入及同步處理連絡人。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | 委託 | 是 | 基本設定檔資訊。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | 委託 | 否 | 用於查看共同工作者的設定檔，以及比較閒置時間和排程會議室。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | 委託 | 是的，離線使用者的空閒/忙碌時間。 | 當使用者未使用網站時，請致電 Graph。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| openid | 委託 | 否 | Office 365Sso。 | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="add-in-data-access"></a>增益集資料存取

列出此應用程式在存取您組織的資料時所需的許可權、此許可權的理由和用途 (應用程式使用此資訊的情況為何？ ) ，以及應用程式是否在其資料庫中儲存任何這項資訊。

>| **Permission**  | **描述** |
>|:----------------|:----------------|
>| ReadWrite 專案 | 此增益集可以存取及修改使用中郵件中的個人資訊，例如本文、主旨、寄件者、收件者及附件資訊。 它可能會將此資料傳送給協力廠商服務。 您的信箱中的其他專案可以&#8217;t 讀取或修改。 |
>| 傳送資料 | 可以透過網際網路傳送資料 |

#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>是的，我們會記錄用來將授權購買連線至商業 Appsource 的電子郵件地址。 我們提供從我們的記錄中刪除此資訊的功能。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>只有開發人員才能存取我們的記錄檔。 我們強制2FA 存取所有開發平臺。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

