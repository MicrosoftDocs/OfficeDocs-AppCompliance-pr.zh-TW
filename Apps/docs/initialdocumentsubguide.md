---
ms.author: oromalle
title: Microsoft 365認證 - 初始檔提交指南
author: orionomalley
manager: tonybal
description: 初始檔提交是認證評估前階段的一部分。
keywords: 應用程式認證小組Microsoft 365安全性合規性 m365 初始檔提交
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 8cb7ac4711b7399ae24b76794c251e3cae845e94
ms.sourcegitcommit: a615b7893956a0737e30e477d2870fd99e514ea5
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/20/2022
ms.locfileid: "65618579"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365憑證 - 初始檔提交指南

初始檔提交是認證評估前階段的一部分。 提供的資訊會為認證分析師提供識別哪些控制項和系統元件將在評量範圍內所需的背景。 本檔僅作為初始檔提交預期的範例。 您提供的檔會根據解決方案的架構、實作和管理方式而有所不同。

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>用來執行應用程式的裝載環境或服務模型為何？
- 基礎結構即服務 (IaaS) 是雲端服務模型，您的雲端服務提供者會在其中裝載基礎結構元件，但 ISV 仍負責個別部署和管理元件，例如虛擬機器/作業系統、資料存放區和網路元件。 例如 Azure 虛擬機器和 Azure 磁片儲存體。
- 平臺即服務 (PaaS) 是雲端服務模型，其中的基礎結構元件是由雲端服務提供者管理。 ISV 只負責部署自己的應用程式和服務。 例如Azure App服務、Azure Functions和Azure CDN。
- 在此內容中裝載的 ISV 表示未使用雲端服務提供者。 ISV 會在內部部署獨立管理自己的伺服器、磁片和網路。
- 此內容中的混合式表示使用上述其中一個模型。 例如，某些 ISV 可能會選擇使用 IaaS 服務和 PaaS 服務的混合來支援其應用程式，或者它們可能有一些內部部署 ISV 託管元件，並將其他元件外包給雲端服務提供者。 如果您使用其中一個以上的服務模型，請選取 [混合式]。

## <a name="penetration-test-report"></a>滲透測試報告

請包含完整滲透測試報告，其中包含過去 12 個月內已完成的日期。 
-   此報告必須從手動滲透測試產生，它不能是自動化掃描/測試控管的輸出。
-   此報告必須包含支援部署應用程式/新增的環境，以及支援應用程式/增益集作業的任何其他環境。


## <a name="system-component-inventory"></a>系統元件清查

支援基礎結構所使用之所有系統元件的更新 Inventroy。 這會用來協助您在執行評定階段時進行取樣。 如果您的環境包含 PaaS，如果您可以提供所取用之所有 PaaS 服務的詳細資料，這會很有用。

**注意：** IaaS/PaaS 不會有任何位於 ISV 控制項下的硬體。  在此情況下，請提供所有虛擬資源的清單或螢幕擷取畫面。

**範例：**

|資產名稱|資產類型|描述|製造商|Model|
|---|---|---|---|---|
|D212|Windows機|虛擬機器|不適用|不適用|
|LT101|筆記型電腦|工作站|Microsoft|Surface 3|
|C2938|參數|參數|不適用|不適用|
|LXM2|Linux 機器|測試機器|不適用|不適用|


## <a name="software-inventory"></a>軟體清查

所有軟體資產的最新清查，包括範圍內環境中使用的所有軟體，以及版本。

**範例：**

|軟體|Publisher|版本|用途|
|---|---|---|---|
|Windows 伺服器|Microsoft 2016 |組建 14393|生產環境的伺服器作業系統|
|Linux Ubuntu|不適用|16.04 (Xenial) |在 DMZ 內使用的伺服器作業系統。|
|ESXi|Vmware|6.5.0 (組建13004031) |用來支援虛擬伺服器。|
|Mysql (Windows) |不適用|8.0.2.1|用來儲存聊天記錄的資料庫伺服器。|
|Tomcat|Apache|7.0.92|客戶入口網站。|
|IIS|Microsoft|10.0|支援 API。|


## <a name="third-party-dependencies"></a>協力廠商相依性

列出應用程式/增益集與目前執行中版本使用之所有相依性的檔。

**範例：**

|Web 相依性|使用中的目前版本|
|----|----|
|Jquery|3.5.1|
|反應|16.13.1|
|引導|4.5.2|
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>公用 IP 位址

詳細說明支援基礎結構使用的所有公用 IP 位址和 URL。 這必須包含配置給環境的完整可路由 IP 範圍，除非已實作適當的分割來分割使用中的範圍 () 需要有適當的分割辨識項。

**範例：**

|URL|IP 位址|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/A (Jump Server) |40.113.200.200|


## <a name="resource-endpoints"></a>資源端點

API 名稱端點位址 Contoso 客戶 API https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso 檔案 APIhttps://filesapi.contoso.com

完整列出您的應用程式所使用的所有 API 端點，包括內部開發和外部資源端點。 若要協助瞭解環境範圍，請在您的環境中提供 API 端點位置。

**範例：**

|API 名稱|  端點位址|
|-|-|
|Contoso 客戶 API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso 檔案 API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>架構圖表

邏輯架構圖，代表應用程式/增益集支援基礎結構的高階概觀。 這必須包含所有裝載環境和支援支援應用程式/增益集的基礎結構。 此圖表必須描述環境中所有不同的支援系統元件，以協助認證分析師瞭解範圍內的系統，並協助判斷取樣。 也請指出使用何種裝載環境類型;ISV Hosted、IaaS、PaaS 或混合式。 使用 PaaS 的位置，請指出用來在環境中提供支援服務的各種 PaaS 服務。

![架構圖表](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>資料Flow圖

Flow詳細說明下列各項的圖表：
-   在應用程式/增益集 (中來回的資料流程，包括客戶資料) 。
-   在適用的情況下，支援基礎結構 (內的資料流程) 
-   圖表醒目提示儲存資料的位置和內容、如何將資料傳遞給外部協力廠商 (包括協力廠商) 的詳細資料，以及如何透過開放/公用網路和待用網路保護傳輸中的資料。

![資料Flow圖](../media/Dataflowdiagram.png)

## <a name="external-certifications-soc2-pci-dss-iso27001---optional"></a>外部認證 (SOC2、PCI DSS、ISO27001) - 選擇性

如果您已經取得 SOC2、PCI DSS 或 ISO27001 認證，且在過去 12 個月內發出的報告超過所認證應用程式的完整範圍和支援環境，您可以在初始檔提交期間提交。 我們將嘗試利用它來滿足控制項子集，並加速您的評量。 不過，這不需要取得Microsoft 365認證。 

