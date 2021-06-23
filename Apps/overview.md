---
title: Microsoft 365 應用程式合規性程式
author: LGerrard
ms.author: Legerrar
description: 程式簡介和概觀
keywords: Microsoft 365 m365 應用程式發行者證明憑證
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: fd06ecd028876a862fa3938253817fae3ff0fea0
ms.sourcegitcommit: 0d46955e7b4c0e1d4208843813793c382344b2f5
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/22/2021
ms.locfileid: "53053437"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 應用程式合規性程式

Microsoft 365 應用程式合規性程式透過三層漸進式方法來實現應用程式安全性與合規性。 每個層次都建立在下一個層面之上 – 這個分層程式讓使用者在使用 Microsoft 365 生態系統中的應用程式時，擁有所需的信心。 目前，程式中的所有層面都是自願的，由應用程式開發人員自行決定是否完成。 

我們的使命宣言：Microsoft 客戶對執行其組織的應用程式完全信任。

  ![三層漸進式方法來實現應用程式合規性](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>發行者驗證

[發行者驗證](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)可幫助管理員和使用者了解與 Microsoft 身分識別平台整合的應用程式開發人員的確實性。 當應用程式被標記為已完成發行者驗證，這表示發行者已使用Microsoft 合作夥伴網絡帳戶驗證了自己的身份，該帳戶已完成驗證流程，並將此 MPN 帳戶與他們的應用程式註冊連結。
發行者驗證會套用至符合以下條件的應用程式：  
- 使用 OAuth 2.0 和 OpenID Connect 讓使用者登入，以及使用服務端 API (例如 Microsoft Graph) 請求存取資料。 
- 在 Azure AD 中註冊為多租用戶。  

> [!IMPORTANT]
> 發行者驗證不排除應用程式開發人員開始或完成發行者證明或Microsoft 365 憑證。 如果不適用於應用程式，則可以跳過驗證，並且可以啟動證明。

## <a name="publisher-attestation"></a>發行者證明

[發行者證明](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)為開發人員提供一個地方，讓他們分享有關其應用程式服務的一般資訊、資料處理及安全性和合規性資訊。 這減少了 IT 管理員直接與應用程式發行者合作的需求。 可以在同一個地方以一致的格式找到所有完成發行者證明的應用程式，還有做出明智決定所需的所有資訊。 目標是使其更容易並加快應用程式採用的流程，同時確保客戶在他們的租用戶中使用的應用程式符合其組織標準。

發行者證明適用於與以下 Microsoft 平台整合的應用程式：
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote
- Web App

> [!IMPORTANT]
> Microsoft 不會驗證提供的資訊。開發人員僅會確認證明文件和相應應用程式效能資料的真實性、準確性和完整性。 

## <a name="microsoft-365-certification"></a>Microsoft 365 憑證
[Microsoft 365 憑證](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)為組織提供了保證和信心，確保在使用 Microsoft Teams 應用程式時資料和隱私得到充分保護。 憑證會確認應用程式解決方案與 Microsoft 技術兼容，符合雲端 App 安全性最佳做法，以及得到 Microsoft 的支援。在此流程中，應用程式開發人員會與第三方評定者合作，以驗證組織的安全性及合規性標準。 Microsoft 365 認證適用於符合發行者證明資格的相同應用程式。 


