---
title: 閃電工具閃電線的應用程式資訊（閃電工具）
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有適用于閃電工具閃電的安全性和符合性資訊資訊，其資料處理原則，其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9f597f25df7b000d3d98a2dfbc4fe3c34fef7842
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430523"
---
# <a name="lightning-tools-lightning-conductor"></a>閃電工具閃電線

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2021年7月12日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001926" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

由閃電工具提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 閃電工具閃電線 |
| ID | WA200001926 |
| 支援 Office 365 用戶端 | SharePoint 2016 或更新版本 |
| 合作夥伴公司名稱 | 閃電工具 |
| 合作夥伴網站的 URL | [https://lightningtools.com](https://lightningtools.com) |
| 隱私權原則的 URL | [https://lightningtools.com/lightning-conductor-cswp-privacy...](https://lightningtools.com/lightning-conductor-cswp-privacy-policy) |
| 使用條款的 URL | [https://lightningtools.com/lightning-tools-lightning-conduc...](https://lightningtools.com/lightning-tools-lightning-conductor-client-side-web-part-software-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

這種資訊已由閃電工具提供，此應用程式會如何收集和儲存組織資料，以及您的組織將會擁有該應用程式所收集資料的控制項。

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

列出此應用程式所需的任何[Microsoft Graph 許可權](https://docs.microsoft.com/graph/permissions-reference)。

>| **Permission**  | **委派/應用程式的許可權 (類型)** | **資料是否已收集？要收集的理由？** | **資料是否已儲存？儲存的理由** | **Azure AD應用程式識別碼** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 應用程式 | 在行事曆資訊中查詢及報告 | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| 連絡人。已讀取 | 應用程式 | 未收集或儲存任何資料。 資料是用來顯示目前使用者連絡人的 DisplayName | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Directory.Read.All | 應用程式 | 顯示閃電導線中的使用者 | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Files.Read.All | 應用程式 | 顯示閃電導線中的 OneDrive 檔案 | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Mail.Read | 應用程式 | 如果閃電導線中的查詢顯示來自目前使用者信箱的郵件 | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| 已讀取的人員。所有 | 應用程式 | 若要將使用者查詢為網站成員，請在閃電線中顯示 [人員] 視圖。 | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| 目前狀態為 [已讀取]。 | 應用程式 | 顯示人員卡片中的使用者目前狀態 | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Sites.Read.All | 應用程式 | 列舉閃電樹狀檢視中的網站 | 閃電線不會使用資料庫或儲存區資料。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |


#### <a name="non-microsoft-services-used"></a>未使用的 Microsoft 服務

若應用程式使用非 Microsoft 服務來傳輸或共用組織資料，請列出應用程式使用的非 Microsoft 服務、要傳輸的資料，並包含有關應用程式傳送此資訊的原因的理由。

>不會使用非 Microsoft 服務。



#### <a name="telemetry-data"></a>遙測資料

任何組織識別資訊 (OII) 或使用者身分識別資訊 (EUII) 是否會出現在這個應用程式的遙測或記錄檔中？ 如果是，請描述要儲存的資料，以及保留和移除原則為何？

>應用程式遙測或記錄中未出現 OII 或 EUII。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>夥伴所儲存資料的組織控制項

說明組織管理員如何在合作夥伴系統中控制其資訊？例如刪除、保留、審核、封存、使用者原則等等。

>應用程式中的資料位於客戶承租人內。 閃電工具不會儲存或處理客戶租使用者以外的任何資料。 

#### <a name="human-review-of-organizational-information"></a>組織資訊的人工檢查

參與審閱或分析任何組織身分識別資訊 (OII) 由此應用程式收集或儲存的資料嗎？

>是

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>身分識別資訊

此資訊是由閃電工具提供，此應用程式會如何處理驗證、授權、應用程式註冊最佳作法及其他身分識別準則。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要與 Microsoft 識別平臺 (Azure AD) 整合？  | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
