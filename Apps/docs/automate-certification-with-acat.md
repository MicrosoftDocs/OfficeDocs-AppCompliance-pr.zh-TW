---
title: 使用適用于 Microsoft 365 的應用程式合規性自動化工具自動化Microsoft 365認證
description: 使用適用于 Microsoft 365 (ACAT 的應用程式合規性自動化工具) 將Microsoft 365認證自動化。
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: c81ccf3626d6039333f52a487e98233364f7174e
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433398"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>使用適用于 Microsoft 365 的應用程式合規性自動化工具自動化Microsoft 365認證

適用于 Microsoft 365 (ACAT 的應用程式合規性自動化工具) 與Microsoft 365應用程式合規性計畫共同作業，以符合Microsoft 365認證的一些必要控制項。 本文將協助您開始使用 ACAT，並使用合規性評定搭配Microsoft 365認證。

> [!IMPORTANT]
> ACAT 目前處於私人預覽狀態。 如果您想要加入私人預覽計畫，請 [在這裡](https://aka.ms/acat/private/signup)註冊。

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>建立您的第一個合規性報告以將 ACAT 上線

ACAT 可讓您專注于應用程式的合規性，或應用程式 (的特定環境，例如生產環境、預備環境等) 。 它可讓您建立 **合規性報告** ，您可以在其中根據應用程式的雲端基礎結構或應用程式的特定環境來定義合規性界限。

> [!IMPORTANT]
> 由於 ACAT 處於私人預覽狀態，因此您無法直接在中 *https://portal.azure.com* 搜尋。 請使用下列選項來啟動 ACAT。

- 搜尋並啟動 ***應用程式合規性自動化工具，以在Azure 入口網站*** 中 [Microsoft 365](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D&microsoft_azure_marketplace_ItemHideKey=Microsoft_Azure_AppComplianceAutomationHidden)，或直接使用 [ACAT 的深層連結](https://portal.azure.com/#blade/Microsoft_Azure_AppComplianceAutomation/AcatMenuBlade/overview)啟動。
- 從左側移至 ***[報*** 表]。

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="建立合規性報告":::
   移至 [報告] 以建立新的合規性報告 :::image-end:::

- 選 ***取 [建立新的報表*** ] 以開始建立第一個具有適當設定的合規性報告。 
    - **基本概念**
        - **報表名稱**：合規性報告的名稱是必要的，而且不能在租使用者內重複。 它可以是數位、字母和底線的組合。 建議您將有意義的名稱與合規性報告搭配使用，例如，指出特定應用程式或環境。
        - **觸發時間**：ACAT 會每日產生合規性報告的合規性評估。 此組態可用來指定何時應觸發產生。 
        - **選取訂** 用帳戶：在私人預覽版中，ACAT 可讓您選擇特定訂用帳戶中的 Azure 資源，以定義合規性報告的範圍。 您可以根據雲端基礎結構選擇適當的訂用帳戶。 如果您的應用程式訂用帳戶不在清單中，您必須向系統管理員要求許可權。 
        - **選取資源**：指定訂用帳戶之後，請根據您的雲端基礎結構選取適當的資源。 預設會自動選取所有資源。 您也可以依篩選 (例如資源群組、標記等) 來搜尋資源，然後選取資源。 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="基本設定":::
       合規性報告的基本組態 :::image-end:::

    - **Microsoft 365認證**：Microsoft 365認證設定在建立期間是選擇性的。  您可以在稍後開始發佈應用程式後進行設定。
        - **供應專案 GUID**：供應專案 GUID 是 [Microsoft 合作夥伴網路](https://partner.microsoft.com/dashboard)中市集供應專案的唯一識別碼。 選取 *[深入瞭解* ] 以取得如何取得唯一識別碼的逐步指示。
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="Microsoft 365認證設定":::
       關於Microsoft 365認證的設定:::image-end:::

確認設定並建立合規性報告之後，ACAT 會自動從下列來源收集合規性相關資料。 

- 為您的訂[用帳戶](https://azure.microsoft.com/services/defender-for-cloud/)啟用適用於雲端的 Microsoft Defender (免費層) 。 
- 為您的訂用帳戶啟用一些自訂原則。 

> [!NOTE]
> 如果建立成功，ACAT 會從第二天開始收集並產生合規性報告的合規性評估。 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>使用您的合規性報告稽核合規性評估

透過 ACAT，您可以輕鬆地瞭解合規性報告的執行時間狀態，並稽核合規性評估。 

- 從左側移至 ***[報*** 表]。 您可以取得現有合規性報告的簡短摘要。
    - **執行時間狀態**：執行時間狀態指出 ACAT 是否仍會在最後一代中正確管理合規性報告。 執行時間狀態有三種狀態。 
        - **作用** 中：合規性報告持續且成功執行。 
        - **失敗**：ACAT 無法產生上一代此合規性報告的合規性評估。 此狀態可能會因為多種原因而發生，例如，您的訂用帳戶中設定不正確，以封鎖路由傳送至 ACAT 的合規性資料、ACAT 發生系統失敗或中斷等。 
        - **已停** 用：此合規性報告會在您手動暫停)  (停用。 此功能未在私人預覽中啟用。 
    - **上次觸發時間** 和 **下一個觸發時間**：ACAT 會每日產生合規性報告的合規性評估。 *上次觸發時間* 表示觸發最後一代的時間， *而 [下一個觸發時間* ] 則表示即將產生之層代的觸發時間。 
    - **Microsoft 365認證**：瞭解Microsoft 365認證控制項的合規性報告狀態。 Microsoft 365認證合規性狀態的三個狀態包括：
        - **通過**：完全自動化的Microsoft 365認證控制沒有失敗。
        - **失敗**：偵測到完全自動化Microsoft 365認證控制項的客戶責任失敗。
        - **手動**：此狀態包含兩種控制項： *部分自動化的手動控* 件，由 ACAT 部分自動化，但仍需要一些手動工作來收集合規性辨識項，以及需要手動完整手動收集合規性辨識項 *的手動控* 件。 ACAT 會自動化部分自動化部分自動化控制的客戶責任。 您可以使用其合規性狀態進行參考，但無法直接用於Microsoft 365認證稽核。
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="合規性報告清單":::
       現有合規性報告的清單。
    :::image-end:::

除了學習現有合規性報告的高階摘要，您也可以在 ACAT 中向您的小組稽核合規性評估詳細資料。 按一下報表名稱，以取得特定合規性報告的合規性評估詳細資料。 ACAT 會如下所示顯示詳細資料。

- **設定**：您可以使用 設定 變更合規性報告 *的設定*。 在私人預覽版中，您可以變更Microsoft 365認證相關設定。 
- **下載報告**：ACAT 可讓您以可與合作夥伴共用以共同作業的格式，將合規性報告的評定下載為 csv 檔案。
    - **雲端基礎結構清查**：此檔案包含此合規性報告的資源詳細資料。 它可用來描述應用程式的雲端清查。 
    - **Microsoft 365認證合規性評定**：此檔案包含來自Microsoft 365認證控制檢視的合規性報告合規性評估。 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="合規性報告工具列":::
    合規性報告的工具列。
:::image-end:::

- **基本資訊**：本節會指出合規性報告的狀態和設定。 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="合規性報告基本資訊":::
    合規性報告的基本資訊。
:::image-end:::

- **評量結果**
    - Microsoft 365認證控制項的合規性狀態分為五個類別。 
        - **通過**：完全自動化的Microsoft 365認證控制沒有失敗。
        - **失敗**：偵測到完全自動化Microsoft 365認證控制項的客戶責任失敗。
        - **通過 - 需要其他辨** 識項：部分自動化Microsoft 365認證控制項沒有任何失敗。 您仍然需要手動收集控制項的其他辨識項。
        - **失敗 - 需要其他辨識** 項：針對部分自動化Microsoft 365認證控制偵測到客戶責任失敗。
        - **手動控制**：ACAT 不會將Microsoft 365認證控制的任何客戶責任自動化。 
    - 合規性評定是由Microsoft 365認證控制系列和控制項所組織。 
        - 深入瞭解合規性控制項的詳細資料，以及如何按一下控制項名稱來收集手動控制的合規性辨識項。 
        - 當您展開完全自動化控制項和部分自動化控制項時，您可以深入瞭解該控制項的客戶責任合規性詳細資料。 
        - 針對每個客戶責任，您也可以按一下 [動作] 按鈕，探索相關資源的合規性狀態和失敗資源的補救步驟。 
            - **狀況不良的資源**：您必須遵循補救步驟來修正狀況不良的資源。 
            - **不適用的資源**：您必須追蹤 N/A 原因來設定資源，然後 ACAT 可以收集資源的合規性評估。

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="合規性報告評定":::
    合規性報告的合規性評估。
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>使用您的第一個合規性報告搭配 Microsoft r365 認證稽核

在使用合規性報告與Microsoft 365認證之前，您必須設定供應專案 GUID，以將合規性報告與您的市集供應專案產生關聯。 其中有兩個選項： 

- 在合規性報告的建立過程中，*請在 [* 認證] 索引標籤Microsoft 365設定供應專案 GUID。 
- 如果已建立合規性報告，請移至此合規性報告的 *設定*，以設定供應專案 GUID。

設定供應專案 GUID 之後，請移至 [Microsoft 合作夥伴網路](https://partner.microsoft.com/dashboard) 以啟動應用程式合規性。 *初始檔* 是Microsoft 365認證的第一個階段。 在這個階段中，如果您針對是否使用 ACAT 的問題選擇 [ *是* ]，您可以為此稽核選擇適當的合規性報告。 Microsoft 365認證會自動將完全自動化控制項的合規性評估提交給稽核員，以節省您的時間和精力。 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>取得合規性報告的高階概觀 

概 ***觀*** 可讓您進一步瞭解合規性報告的高階狀態。 

- **合規性報告執行時間狀態**：此概觀會提供合規性報告執行時間狀態的統計資料。
    - **作用** 中：合規性報告持續且成功執行。 
    - **失敗**：ACAT 在最後一代中無法產生此合規性報告的合規性評估。 此狀態可能會因為數個原因而發生，例如，您的訂用帳戶中設定不正確，以封鎖路由傳送至 ACAT 的合規性資料、ACAT 發生系統失敗或中斷等。 
    - **已停** 用：此合規性報告會在您手動暫停)  (停用。 此功能未在私人預覽中啟用。 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="執行時間狀態概觀":::
    合規性報告執行時間狀態的概觀。
:::image-end:::

- **主動式法規合規性報告**：此概觀將為您提供每個 *作用* 中合規性報告的合規性結果統計資料。
    - **通過**：完全自動化的Microsoft 365認證控制沒有失敗。
    - **失敗**：偵測到完全自動化Microsoft 365認證控制項的客戶責任失敗。
    - **手動**：此狀態包含兩種控制項： *部分自動化的手動控* 件，由 ACAT 部分自動化，但仍需要一些手動工作來收集合規性辨識項，以及需要手動完整手動收集合規性辨識項 *的手動控* 件。 ACAT 會自動化部分自動化部分自動化控制的客戶責任。 您可以使用其合規性狀態進行參考，但無法直接用於Microsoft 365認證稽核。

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="合規性狀態概觀":::
    作用中合規性報告的合規性狀態概觀。
:::image-end:::

## <a name="troubleshooting"></a>疑難排解 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>為什麼因為授權錯誤而建立的合規性報告失敗？ 

建立合規性報告時，ACAT 會設定環境與您的訂用帳戶自動收集合規性資料，而此動作需要訂用帳戶的特定許可權。 您可以檢查您的訂用帳戶許可權，如下所示。 

- 在 Azure 入口網站 中搜尋並啟動 **訂**[用帳戶](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)。
- 移至您要用來建立合規性報告的訂用帳戶。 
- 移至左側 **IAM)  (存取控制** 。 
- 選 **取 [檢視我的存取權** ] 以檢查您的許可權。
    - 如果您的組織使用 [Azure 內建角色](/azure/role-based-access-control/built-in-roles)，您的角色指派應該至少包含下列其中一個角色：
        - [資源原則參與者](/azure/role-based-access-control/built-in-roles#resource-policy-contributor)[和安全性系統管理員](/azure/role-based-access-control/built-in-roles#security-admin)
        - 其他具有較高許可權的角色指派 (例如擁有 [者](/azure/role-based-access-control/built-in-roles#owner)等) 

### <a name="how-to-report-an-acat-issue-or-warning"></a>如何報告 ACAT 問題或警告？ 

當您在 ACAT 中遇到問題，而且想要連絡 [ACAT 私人預覽計畫](mailto:acatprivatepreview@microsoft.com) 以取得協助時，我們需要您的協助來收集辨識項，以進一步瞭解您的案例。

- 取得 ACAT 錯誤或警告的詳細資料
    - 移至Azure 入口網站頂端 **的通知**[。](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)
    - 在 **活動記錄中選取 [更多事件]** 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-activitylog.png" alt-text="ACAT 通知":::
        移至活動記錄以檢查 ACAT 通知。
    :::image-end:::
    
    - 適當地變更 **時間範圍** ，以篩選掉活動記錄檔中的 ACAT 錯誤或警告。 
    - 找出您的 ACAT 錯誤或警告，選取以取得詳細資料，並將詳細資料儲存為檔案。
    
- 檢查您的訂用帳戶是否已由 ACAT 正確設定。 
    - 在 Azure 入口網站 中搜尋並啟動 **訂**[用帳戶](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)。
    - 移至您要用來建立合規性報告的訂用帳戶。 
    - 選 **取 [資源提供者** ] 以檢查這些提供者的狀態是否 *為 [已註冊]*。
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - 返回 [Azure 入口網站，](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)然後啟動 **Resource Graph Explorer**。
    - 選 **取 [新增查詢]**
    - 執行此查詢以檢查原則指派，並將結果下載為 CSV。 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - 執行此查詢以檢查自動化，並將結果下載為 CSV。

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - 執行此查詢以檢查評量，並將結果下載為 CSV。 您必須將預留位置 ***your-subscriptionId*** 取代為您想要查詢的特定訂用帳戶。

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```