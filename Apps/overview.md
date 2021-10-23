---
title: Microsoft 365 應用程式合規性程式
author: LGerrard
ms.author: Legerrar
description: 程式簡介和概觀
keywords: Microsoft 365 m365 應用程式發行者證明憑證
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: e36bee4289de320d264a8a5e55c7bc20a4ea803b
ms.sourcegitcommit: cab3c02db1b748f3502714d89bd9b65408fd9f54
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/22/2021
ms.locfileid: "60545765"
---
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 應用程式合規性程式

Microsoft 365 應用程式合規性計畫是應用程式安全性與合規性的雙步驟方法，並包含發行者驗證與 Microsoft 365 認證。 每個層次都建立在下一個層面之上 – 這個分層程式讓使用者在使用 Microsoft 365 生態系統中的應用程式時，擁有所需的信心。  

我們的使命：提供 Microsoft 客戶完全信任執行其組織應用程式的方法。

![2 層漸進式方法來實現應用程式合規性](media/Microsoft365AppComplianceBanner.png)

## <a name="publisher-verification"></a>發行者驗證

[發行者驗證](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)可幫助管理員和使用者了解與 Microsoft 身分識別平台整合的應用程式開發人員的確實性。 當應用程式被標記為已完成發行者驗證，這表示發行者已使用Microsoft 合作夥伴網絡帳戶驗證了自己的身份，該帳戶已完成驗證流程，並將此 MPN 帳戶與他們的應用程式註冊連結。
發行者驗證會套用至符合以下條件的應用程式：  
- 使用 OAuth 2.0 和 OpenID Connect 讓使用者登入，以及使用服務端 API (例如 Microsoft Graph) 請求存取資料。 
- 在 Azure AD 中註冊為多租用戶。  

> [!IMPORTANT]
> 發行者驗證不排除應用程式開發人員開始或完成發行者證明或Microsoft 365 憑證。 如果不適用於應用程式，則可以跳過驗證，並且可以啟動證明。

## <a name="microsoft-365-certification"></a>Microsoft 365 憑證
Microsoft 365 認證程序分為兩個階段：**證明** 與 **認證**。
1.  **認證** 包括填寫一份對客戶至關重要的關於應用程式安全性、資料處理和合規性屬性的問卷。 然後，所有資訊以一致、易於閱讀的格式發佈在一個位置。 目標是加快應用程式採用的流程，同時確保客戶在他們的租用戶中使用的應用程式符合其組織標準。
1.  **認證** 涉及應用程式對一組衍生自領先行業標準架構的控制項進行徹底稽核。 在取得憑證之前，系統會要求 ISV 提供證據，證明其符合各項控制要求。 目標是向客戶保證，他們可以信任已取得 Microsoft 365 認證的應用程式具有强大的安全性與合規性做法，以保護其資料安全性與隱私權。


Microsoft 365 憑證適用於 WebApps，以及與下列 Microsoft 產品整合的所有應用程式:
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

### <a name="get-started"></a>開始使用
- [如何完成發行者驗證](https://docs.microsoft.com/en-us/azure/active-directory/develop/mark-app-as-publisher-verified)
- [如何完成 Microsoft 365 認證](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification)

