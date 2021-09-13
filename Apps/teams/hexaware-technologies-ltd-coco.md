---
title: COCO by Hexaware 技術有限公司的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: COCO 中所有可用的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8a25a95b277f41f30477182c9eec0b3b25b9351e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59279218"
---
# <a name="coco"></a>COCO

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>上次於開發人員的更新日期：2020年6月23日</p>

* <a href="https://teams.microsoft.com/l/app/c3f021f9-1fe2-44c7-972e-58f3cd0e7762" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001468" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由 Hexaware 技術公司所提供的資訊給 Microsoft：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | COCO |
| ID | WA200001468 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Hexaware Technologies Ltd. |
| 合作夥伴網站的 URL | [https://hexaware.com](https://hexaware.com) |
| 隱私權原則的 URL | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf) |
| 使用條款的 URL | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf#page=6) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊是由 Hexaware 技術公司所提供。關於此應用程式如何收集和儲存組織的資料，以及您的組織將會對應用程式所收集的資料所做的控制。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD 應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | 委託 | 無 | 登入使用者的存取目錄 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.Read.All | 應用程式 | 無 | 讀取目錄資料 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| Directory.ReadWrite.All | 委託 | 無 | 讀取和寫入目錄資料 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read | 委託 | 無 | 登入並讀取使用者設定檔 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.Read.All | 應用程式 | 無 | 讀取所有使用者的完整設定檔 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| User.ReadWrite.All | 委託 | 無 | 讀取和寫入所有使用者的完整設定檔 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |
>| openid | 委託 | 無 | 在中簽署使用者 | [82eb2bf2-969c-46da-9e89-1db59ac4fbb3](https://docs.microsoft.com/microsoft-365-app-certification/azure/82eb2bf2-969c-46da-9e89-1db59ac4fbb3) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。

#### <a name="data-access-via-bots"></a>透過 bot 的資料存取

如果此應用程式包含 bot 或郵件擴充，可以存取使用者識別資訊 (EUII) ： (名單中的「名字」、「姓氏」、「顯示名稱」、「電子郵件地址」) 的任何小組成員或加入的交談。 此應用程式是否使用此功能？

>| **存取 EUII 的理由？**  | **EUII 是儲存在資料庫 (s) 中嗎？** | **儲存 EUII 的理由？** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 維護會話資料 | 名稱、電子郵件識別碼 |  |


#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>NA

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

<iframe height='1020' title='Microsoft Cloud App Security資訊' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906" target="_blank">在新的索引標籤中查看</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

