---
title: Studi.ly 的應用程式資訊，依 inLogic-Office 儲存區
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Studi.ly 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26a89739809e0d398db2a823bd714aa06a2d210d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553054"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年8月24日</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

inLogic-Office Store 所提供的資訊至 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | Studi.ly |
| ID | WA200001668 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | inLogic-Office Store |
| 合作夥伴網站的 URL | [https://www.studi.ly](https://www.studi.ly) |
| 隱私權原則的 URL | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| 使用條款的 URL | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

inLogic-Office Store 會提供此資訊，讓您瞭解此應用程式如何收集及儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ReadWrite 的行事曆 | 委託 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | 委託 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 在 [工作分派和材料的群組中寫入目錄]。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | 應用程式 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 在 [工作分派和材料的群組中寫入目錄]。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster Read。 All | 應用程式 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。 我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 閱讀教育課程、學校、成員和條款。取得租使用者的所有類別和學校，以進行應用程式資料庫的同步處理。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | 委託 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 閱讀教育課程、學校、成員和條款。取得租使用者的所有類別和學校，以進行應用程式資料庫的同步處理。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster ReadWrite。 | 應用程式 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 閱讀教育課程、學校、成員和條款。取得租使用者的所有類別和學校，以進行應用程式資料庫的同步處理。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | 委託 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 從一個磁片磁碟機 ReadWrite 檔案 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | 委託 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 此許可權允許此應用程式取得租使用者群組的不同 claender 事件。、主旨、開始、結束、擴充 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | 包括 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 此許可權允許此應用程式取得租使用者群組的不同 claender 事件。、主旨、開始、結束、擴充 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member Read。隱藏 | 應用程式 |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | 包括 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 從一個磁片磁碟機 ReadWrite 檔案 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | 委託 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 讀取使用者資訊 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | 委託 | 我們在 api 中儲存教育版 api 中的課程、學校和成員及字詞資訊，因為如果我們每次都從圖形 api 取得應用程式的速度很慢，我們就會需要它。我們會在以時間為基礎的事件從教育 api 將其同步處理至資料庫。 | 讀取使用者資訊 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>未存取 EUII。


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>記錄中不會顯示任何這類資料

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>它會儲存在 Azure cosmos 資料庫中，且預設可搭配 cosmos 資料庫使用的任何加密和儲存，都適用于此應用程式。

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

