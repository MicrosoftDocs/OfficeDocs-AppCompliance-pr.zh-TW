---
title: 適用于 Microsoft 365 的應用程式合規性自動化工具
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: 適用于Microsoft 365的應用程式合規性自動化工具概觀
keywords: 應用程式認證自動化Microsoft 365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: debd3c9e2ecd1538446d09f5019ea995260345fd
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433397"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>適用于 Microsoft 365 的應用程式合規性自動化工具
在本文中，您將瞭解適用于 Microsoft 365 (ACAT) 的應用程式合規性自動化工具是什麼，以及它如何簡化合規性並取得Microsoft 365認證。

> [!IMPORTANT]
> ACAT 目前處於 *私人預覽狀態* 。 如果您想要加入私人預覽計畫，請 [連絡 acatprivatepreview@microsoft.com](mailto:acatprivatepreview@microsoft.com)。

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>什麼是適用于 Microsoft 365 的應用程式合規性自動化工具
適用于 Microsoft 365 (ACAT) 的應用程式合規性自動化工具是 Azure 入口網站中的一項服務，可協助簡化任何取用Microsoft 365客戶資料並透過合作夥伴中心發佈之應用程式的合規性旅程。 適用于Microsoft 365的應用程式合規性自動化工具是以應用程式為中心的合規性自動化工具，可協助您以更輕鬆且便利的方式完成Microsoft 365認證。 在私人預覽版中，ACAT 適用于在 Azure 上執行的應用程式。

使用此工具，您將能快速定義應用程式的合規性界限、自動監視合規性結果，並更輕鬆地完成合規性稽核。 合規性界限是雲端基礎結構，可支援應用程式的傳遞，以及應用程式可能與之通訊的任何後端系統。

除了提供更快速的Microsoft 365認證追蹤之外，ACAT 還可協助您在各種Microsoft 365應用程式的合規性案例中：

- Microsoft 365認證責任的詳細檢視和補救步驟。
- 自動每日報告可協助您持續取得合規性結果。
- 安全性與合規性最佳做法，可作為應用程式生命週期早期階段的指引。

## <a name="benefits-of-acat"></a>ACAT 的優點
以應用程式為中心的合規性旅程圖。
- ACAT 會每天報告應用程式雲端環境的合規性狀態，您可以與目前的雲端基礎結構合規性策略整合。
- 即使在應用程式開發階段，開發人員也可以叫用 ACAT。

加速取得Microsoft 365認證的程式。
- ACAT 會將特定Microsoft 365認證控制項完全自動化。
- Microsoft 正在積極開發持續成長的自動化清單。

與Microsoft 365認證工作流程的原生整合。
- ACAT 與合作夥伴中心完全整合，以Microsoft 365認證用途。

## <a name="concepts-of-acat"></a>ACAT 的概念
### <a name="regulatory-compliance-report"></a>法規合規性報告 
在 ACAT 中，您可以為其建立合規性報告來稽核應用程式的合規性狀態。 您可以藉由指定建置應用程式的 Azure 資源，來定義應用程式的合規性界限。 根據不同的開發環境和階段，為一個應用程式建立多個報表。

建立報表之後，ACAT 會開始收集預先定義觸發時間的合規性資料，然後為您產生合規性結果作為報告。 同時，ACAT 會持續監視合規性報告的合規性變更，直到您選擇刪除報表為止。

### <a name="microsoft-365-certification-control-results"></a>Microsoft 365認證控制結果
在法規合規性報告中，合規性結果會依控制群組織，並以 ACAT 標示其對應狀態：
- **通過**：完全自動化的Microsoft 365認證控制沒有失敗。
- **失敗**：偵測到完全自動化Microsoft 365認證控制項的客戶責任失敗。
- **通過 - 需要其他辨** 識項：*部分自動化* Microsoft 365認證控制項沒有任何失敗。
- **失敗 - 需要其他辨識** 項：針對 *部分自動化* 的Microsoft 365認證控制偵測到客戶責任失敗。
- **手動控制**：ACAT 不會將Microsoft 365認證控制的任何客戶責任自動化。

### <a name="customer-responsibility"></a>客戶責任
有一組客戶責任與每個需要滿足的控制項相關聯。 這些是您在下列領域中所保留的責任：資料、端點、帳戶、存取管理等等。

ACAT 會收集每個客戶責任的資料，並傳回其評定結果。 它也會為您提供補救動作，這是我們的指導方針，可協助您與Microsoft 365認證標準一致。


## <a name="faq"></a>常見問題集
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>什麼是手動控制項和部分自動化控制項？
每個合規性控制都與一組客戶責任相關聯，ACAT 會收集其合規性資料。 不過，ACAT 目前並未涵蓋所有Microsoft 365認證的控制項， (需要持續努力擴充涵蓋範圍) 。 針對部分自動化控制項，ACAT 會將部分客戶責任自動化。 您可以使用其合規性狀態進行參考，但無法直接用於Microsoft 365認證稽核。 針對手動控制，ACAT 目前不會將任何客戶責任自動化。

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>我根據補救建議進行了建議的變更，但控制項仍然失敗
在您採取動作來解決失敗之後，您必須等候 ACAT 擷取重新整理的評定結果，以更新控制狀態。 評量會在預先設定的觸發時間每隔 24 小時執行一次。

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>如何在認證程式中使用合規性報告？
ACAT 與[合作夥伴中心](https://partner.microsoft.com/dashboard)緊密整合，以完成您的Microsoft 365認證旅程。 在合規性報告建立期間，您可以編輯Microsoft 365認證組態，也就是供應專案 GUID。 在建立期間是選擇性的，您可以稍後在開始發佈應用程式時進行設定。

## <a name="learn-more"></a>深入了解

* [使用 ACAT 入門](https://aka.ms/acat/getstarted)
* [深入瞭解Microsoft 365認證](https://aka.ms/acat/m365cert)
