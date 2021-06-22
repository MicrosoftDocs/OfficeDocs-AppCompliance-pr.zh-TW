---
title: 何謂 Publisher 認證？
author: LGerrard
ms.author: legerrar
description: Publisher 認證計畫的詳細資料
keywords: 應用程式認證憑證365問卷 appSource 發行者
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 5b49b6aa06dffc0df6a87cf1e9b0824806a90cc2
ms.sourcegitcommit: 0d46955e7b4c0e1d4208843813793c382344b2f5
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/22/2021
ms.locfileid: "53053477"
---
# <a name="what-is-publisher-attestation"></a>何謂 Publisher 認證？

Publisher證明是 Microsoft 365 App 規範計畫中的下一層。 應用程式開發人員需要完成自我評估，包含客戶或 IT 系統管理員在評估應用程式的安全性和合規性時經常提出的問題。 Microsoft 接著會發佈此資訊，以便更輕鬆及更及時評估。

> [!IMPORTANT]
> Microsoft 不會驗證所提供的資訊。 應用程式開發人員完全負責其在發佈證明中提供的資訊。 

發行者證明適用於與以下 Microsoft 平台整合的應用程式：
- Teams
- Word
- Excel
- PowerPoint 
- Outlook
- SharePoint
- Project
- OneNote
- Web 應用程式

### <a name="benefits-for-it-admins"></a>IT 系統管理員的好處
完成 IT 系統管理員的 Publisher 認證的好處包括：
-   增加組織中啟用之應用程式的安全性和合規性措施中的信賴
-   縮短查看應用程式安全性和合規性狀況的時間

### <a name="benefits-for-app-developers"></a>應用程式開發人員的優點 
為開發人員完成 Publisher 認證的好處包括： 
-   節省時間。 查看應用程式的 [Microsoft 檔] 頁面，以取得常見問題的資訊
-   加速企業組織的安全性與規範內部考核時程表
-   增加透明度
- Microsoft 不會提供這種服務，而無需額外收費
-   存放區中其他應用程式的區別
-   從 AppSource、Teams 系統管理中心及 Microsoft 系統管理中心中的專案，連結至您的 [檔] 頁面
-   開始 Microsoft 365 認證的資格


## <a name="publisher-attestation-scope"></a>Publisher證明範圍

認證程式會集中在大量問卷上，詳述應用程式的安全性、資料處理及合規性屬性。 提供的資訊涵蓋組織的 Microsoft 365 平臺中啟動應用程式時所公開的整個應用程式功能，包括下列各項：

- 資料處理：應用程式如何收集及儲存組織資料，以及組織對該資料的控制
- 安全性：應用程式保護資料及偵測和 repel 網路攻擊的通訊協定、處理常式和程式
- 合規性：此應用程式遵循必要的行業標準與規格
- 法律：應用程式對適用的法律 statues 和法規的遵守

### <a name="confirmation-criteria"></a>確認準則

證明會針對[Microsoft Cloud App Security](https://www.microsoft.com/microsoft-365/enterprise-mobility-security/cloud-app-security)所識別的80風險因素，反映應用程式的安全性、資料處理及規範慣例。 如果初始證明檔提交失敗基本的一致性測試準則，將不會核准證明。 遵循核准時，如果已報告或發現檔提交或應用程式失敗 misinformation，證明確認狀態會是 rescinded。 在上述任一情況下，開發人員將會收到相關及詳細的資訊，以協助修正程式。

### <a name="confirmation-time-frame"></a>確認時間範圍

在提交時，認證的有效期是一年。 不過，如果在過渡期間更新或修改應用程式，則開發人員必須修改並重新提交證明。

## <a name="reviewing-an-apps-publisher-attestation"></a>查看應用程式的 Publisher 認證

開發人員可以在為其應用程式建立的 Microsoft 檔頁面上，查看應用程式 Publisher 證明之結果的詳細資訊。 將會列出所有已完成 Publisher 證明或 Microsoft 365 認證的應用程式，且每個清單都會明確顯示符合性計畫中的哪一層級。

**請參閱 [MIPA](https://docs.microsoft.com/microsoft-365-app-certification/teams/iglobe-mipa-your-personal-assistant?pivots=mcas)清單，以取得已完成 Publisher 認證之應用程式的範例。** 

## <a name="learn-more"></a>深入了解

* [Microsoft 365應用程式規範計畫概述](~/overview.md)
* [何謂 Publisher 驗證](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)
* [完成 Publisher 證明](~/docs/attestation.md)  
* [何謂 Microsoft 365 認證？](~/docs/enterprise-app-certification-guide.md)
