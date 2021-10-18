---
title: 以 88 Ventures 為限之提醒的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 在 CSA 星型登錄中，所有可用的安全性和符合性資訊資訊，其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 895830def92409d04bd92f165668a15eba8995ce
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428386"
---
# <a name="remind"></a>提醒

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2020年9月28日</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

88 Ventures 提供的資訊限制于 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 提醒 |
| ID | WA200001444 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 88 Ventures Limited |
| 合作夥伴網站的 URL | [https://moonbearapp.com](https://moonbearapp.com) |
| 隱私權原則的 URL | [https://teamsreminder.app/#privacy](https://teamsreminder.app/#privacy) |
| 使用條款的 URL | [https://teamsreminder.app/#terms](https://teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 88 Ventures 提供的，此應用程式會限制此應用程式如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 委託 | 資料庫中沒有儲存的資訊 | 允許系統管理員為已設定公開提醒的使用者流覽組織的使用者目錄 | [88546d4f-9973-4716-98e4-cd181c04bc2d](https://docs.microsoft.com/microsoft-365-app-certification/azure/88546d4f-9973-4716-98e4-cd181c04bc2d) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>|  (1) 當使用者在郵件上設定提醒時，bot 會嘗試取得最初傳送郵件的人員名稱，以在使用者設定另一個通道或聊天室成員的提醒時，在使用者的提醒清單 (2) 中，該 bot 會嘗試取得身分識別 (使用者或 bot) 以及所述使用者的名稱，以將其顯示在使用者的提醒清單 |  (1) 當使用者在郵件上設定提醒時，bot 會嘗試取得最初傳送郵件的人員名稱，以在使用者設定另一個通道或聊天室成員的提醒時，在使用者的提醒清單 (2) 中，該 bot 會嘗試取得身分識別 (使用者或 bot) 以及所述使用者的名稱，以將其顯示在使用者的提醒清單 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>使用遙測或記錄功能時，不會共用任何 EEUI 和 OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>靜態加密、兩個要素驗證 (2FA) ，以限制存取我們 IT 基礎結構及客戶資料，以及系統之間受保護的 IP 範圍

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>否

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

