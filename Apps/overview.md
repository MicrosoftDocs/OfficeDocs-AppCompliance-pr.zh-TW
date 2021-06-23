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
# <a name="microsoft-365-app-compliance-program"></a><span data-ttu-id="fcf0d-104">Microsoft 365 應用程式合規性程式</span><span class="sxs-lookup"><span data-stu-id="fcf0d-104">Microsoft 365 App Compliance Program</span></span>

<span data-ttu-id="fcf0d-105">Microsoft 365 應用程式合規性程式透過三層漸進式方法來實現應用程式安全性與合規性。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-105">The Microsoft 365 App Compliance Program, is a three tier approach to app security and compliance.</span></span> <span data-ttu-id="fcf0d-106">每個層次都建立在下一個層面之上 – 這個分層程式讓使用者在使用 Microsoft 365 生態系統中的應用程式時，擁有所需的信心。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-106">Each tier builds upon the next – offering a layered program to give users the confidence they need while using apps in the Microsoft 365 ecosystem.</span></span> <span data-ttu-id="fcf0d-107">目前，程式中的所有層面都是自願的，由應用程式開發人員自行決定是否完成。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-107">Currently all tiers in the program are voluntary and are completed at the app developers discretion.</span></span> 

<span data-ttu-id="fcf0d-108">我們的使命宣言：Microsoft 客戶對執行其組織的應用程式完全信任。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-108">Our mission statement: Microsoft customers have complete trust in the applications that run their organizations.</span></span>

  ![三層漸進式方法來實現應用程式合規性](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a><span data-ttu-id="fcf0d-110">發行者驗證</span><span class="sxs-lookup"><span data-stu-id="fcf0d-110">Publisher Verification</span></span>

<span data-ttu-id="fcf0d-111">[發行者驗證](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)可幫助管理員和使用者了解與 Microsoft 身分識別平台整合的應用程式開發人員的確實性。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-111">[Publisher Verification](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) helps admins and users understand the authenticity of app developers integrating with the Microsoft identity platform.</span></span> <span data-ttu-id="fcf0d-112">當應用程式被標記為已完成發行者驗證，這表示發行者已使用Microsoft 合作夥伴網絡帳戶驗證了自己的身份，該帳戶已完成驗證流程，並將此 MPN 帳戶與他們的應用程式註冊連結。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-112">When an app is marked as publisher verified, it means that the publisher has verified their identity using a Microsoft Partner Network account that has completed the verification process and has associated this MPN account with their application registration.</span></span>
<span data-ttu-id="fcf0d-113">發行者驗證會套用至符合以下條件的應用程式：</span><span class="sxs-lookup"><span data-stu-id="fcf0d-113">Publisher Verification applies to apps that meet the following conditions:</span></span>  
- <span data-ttu-id="fcf0d-114">使用 OAuth 2.0 和 OpenID Connect 讓使用者登入，以及使用服務端 API (例如 Microsoft Graph) 請求存取資料。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-114">Using OAuth 2.0 and OpenID Connect to sign users in and request access to data using service-side APIs such as Microsoft Graph.</span></span> 
- <span data-ttu-id="fcf0d-115">在 Azure AD 中註冊為多租用戶。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-115">Registered in Azure AD as multi-tenant.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="fcf0d-116">發行者驗證不排除應用程式開發人員開始或完成發行者證明或Microsoft 365 憑證。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-116">Publisher Verification does not preclude an app developer from starting or completing Publisher Attestation or Microsoft 365 Certification.</span></span> <span data-ttu-id="fcf0d-117">如果不適用於應用程式，則可以跳過驗證，並且可以啟動證明。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-117">If it does not apply to the app verification may be skipped and the attestation can be started.</span></span>

## <a name="publisher-attestation"></a><span data-ttu-id="fcf0d-118">發行者證明</span><span class="sxs-lookup"><span data-stu-id="fcf0d-118">Publisher Attestation</span></span>

<span data-ttu-id="fcf0d-119">[發行者證明](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)為開發人員提供一個地方，讓他們分享有關其應用程式服務的一般資訊、資料處理及安全性和合規性資訊。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-119">[Publisher Attestation](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) is where developers share general, data handling, and security and compliance information about their app service.</span></span> <span data-ttu-id="fcf0d-120">這減少了 IT 管理員直接與應用程式發行者合作的需求。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-120">This reduces the need for IT admins to work directly with app publishers.</span></span> <span data-ttu-id="fcf0d-121">可以在同一個地方以一致的格式找到所有完成發行者證明的應用程式，還有做出明智決定所需的所有資訊。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-121">All the information needed to make an informed decision can be found for all apps that have completed the publisher attestation in one place and in a consistent format.</span></span> <span data-ttu-id="fcf0d-122">目標是使其更容易並加快應用程式採用的流程，同時確保客戶在他們的租用戶中使用的應用程式符合其組織標準。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-122">The goal is to make it easier and speed up the process of app adoption while assuring customers that the apps they use in their tenants meets their organizational standards.</span></span>

<span data-ttu-id="fcf0d-123">發行者證明適用於與以下 Microsoft 平台整合的應用程式：</span><span class="sxs-lookup"><span data-stu-id="fcf0d-123">Publisher Attestation applies to apps that integrate with these Microsoft platforms:</span></span>
-   <span data-ttu-id="fcf0d-124">Teams</span><span class="sxs-lookup"><span data-stu-id="fcf0d-124">Teams</span></span>
-   <span data-ttu-id="fcf0d-125">Word</span><span class="sxs-lookup"><span data-stu-id="fcf0d-125">Word</span></span>
-   <span data-ttu-id="fcf0d-126">Excel</span><span class="sxs-lookup"><span data-stu-id="fcf0d-126">Excel</span></span>
-   <span data-ttu-id="fcf0d-127">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fcf0d-127">PowerPoint</span></span> 
-   <span data-ttu-id="fcf0d-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="fcf0d-128">Outlook</span></span>
- <span data-ttu-id="fcf0d-129">SharePoint</span><span class="sxs-lookup"><span data-stu-id="fcf0d-129">SharePoint</span></span>
- <span data-ttu-id="fcf0d-130">Project</span><span class="sxs-lookup"><span data-stu-id="fcf0d-130">Project</span></span>
- <span data-ttu-id="fcf0d-131">OneNote</span><span class="sxs-lookup"><span data-stu-id="fcf0d-131">OneNote</span></span>
- <span data-ttu-id="fcf0d-132">Web App</span><span class="sxs-lookup"><span data-stu-id="fcf0d-132">Web Apps</span></span>

> [!IMPORTANT]
> <span data-ttu-id="fcf0d-p105">Microsoft 不會驗證提供的資訊。開發人員僅會確認證明文件和相應應用程式效能資料的真實性、準確性和完整性。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-p105">Microsoft does not validate the information provided. The developer, solely affirms the veracity, accuracy, and integrity of the attestation documentation and corresponding app performance data.</span></span> 

## <a name="microsoft-365-certification"></a><span data-ttu-id="fcf0d-135">Microsoft 365 憑證</span><span class="sxs-lookup"><span data-stu-id="fcf0d-135">Microsoft 365 Certification</span></span>
<span data-ttu-id="fcf0d-136">[Microsoft 365 憑證](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)為組織提供了保證和信心，確保在使用 Microsoft Teams 應用程式時資料和隱私得到充分保護。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-136">The [Microsoft 365 Certification](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) offers assurance and confidence to organizations that data and privacy are adequately secured and protected when using Microsoft Teams apps.</span></span> <span data-ttu-id="fcf0d-137">憑證會確認應用程式解決方案與 Microsoft 技術兼容，符合雲端 App 安全性最佳做法，以及得到 Microsoft 的支援。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-137">Certification confirms that an app solution is compatible with Microsoft technologies, compliant with cloud app security best practices, and supported by Microsoft.</span></span><span data-ttu-id="fcf0d-138">在此流程中，應用程式開發人員會與第三方評定者合作，以驗證組織的安全性及合規性標準。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-138"> During this process, app developers work with a third-party assessor to validate organizational security and compliance standards.</span></span> <span data-ttu-id="fcf0d-139">Microsoft 365 認證適用於符合發行者證明資格的相同應用程式。</span><span class="sxs-lookup"><span data-stu-id="fcf0d-139">Microsoft 365 Certification applies to the same apps that qualify for the Publisher Attestation.</span></span> 


