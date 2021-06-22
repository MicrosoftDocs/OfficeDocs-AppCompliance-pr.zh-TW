---
ms.author: oromalle
title: Microsoft 365認證提交指南
author: orionomalley
description: Microsoft 365認證提交指南精細查看
keywords: 應用程式認證團隊 Microsoft 365 安全性符合性 m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 5e99defd75573b1335975ddc19e851c50da7721f
ms.sourcegitcommit: 0d46955e7b4c0e1d4208843813793c382344b2f5
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/22/2021
ms.locfileid: "53053447"
---
# <a name="microsoft-365-certification-submission-guide"></a><span data-ttu-id="e5d2c-104">Microsoft 365認證提交指南</span><span class="sxs-lookup"><span data-stu-id="e5d2c-104">Microsoft 365 Certification Submission Guide</span></span>

<span data-ttu-id="e5d2c-105">**本文內容：**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-105">**In this article:**</span></span>
- [<span data-ttu-id="e5d2c-106">簡介</span><span class="sxs-lookup"><span data-stu-id="e5d2c-106">Introduction</span></span>](#introduction)
- [<span data-ttu-id="e5d2c-107">必要條件</span><span class="sxs-lookup"><span data-stu-id="e5d2c-107">Prerequisites</span></span>](#prerequisites) 
- [<span data-ttu-id="e5d2c-108">Microsoft 365認證規格更新</span><span class="sxs-lookup"><span data-stu-id="e5d2c-108">Microsoft 365 Certification Specification Updates</span></span>](#microsoft-365-certification-specification-updates)
- [<span data-ttu-id="e5d2c-109">認證範圍</span><span class="sxs-lookup"><span data-stu-id="e5d2c-109">Certification Scope</span></span>](#certification-scope)
- [<span data-ttu-id="e5d2c-110">認證程式</span><span class="sxs-lookup"><span data-stu-id="e5d2c-110">Certification Process</span></span>](#certification-process)
- [<span data-ttu-id="e5d2c-111">初始檔提交</span><span class="sxs-lookup"><span data-stu-id="e5d2c-111">Initial Document submission</span></span>](#initial-document-submission) 
- [<span data-ttu-id="e5d2c-112">證據收集和評估活動</span><span class="sxs-lookup"><span data-stu-id="e5d2c-112">Evidence Collection and Assessment Activities</span></span>](#evidence-collection-and-assessment-activities)
- [<span data-ttu-id="e5d2c-113">認證準則</span><span class="sxs-lookup"><span data-stu-id="e5d2c-113">Certification Criteria</span></span>](#app-certification-criteria)
- [<span data-ttu-id="e5d2c-114">Application Security</span><span class="sxs-lookup"><span data-stu-id="e5d2c-114">Application Security</span></span>](#application-security)
- [<span data-ttu-id="e5d2c-115">運作安全性</span><span class="sxs-lookup"><span data-stu-id="e5d2c-115">Operational Security</span></span>](#operational-security) 
- [<span data-ttu-id="e5d2c-116">資料處理安全性和隱私權</span><span class="sxs-lookup"><span data-stu-id="e5d2c-116">Data Handling Security and Privacy</span></span>](#data-handling-security-and-privacy)
- [<span data-ttu-id="e5d2c-117">選用的外部規範框架審查</span><span class="sxs-lookup"><span data-stu-id="e5d2c-117">Optional External Compliance Frameworks Review</span></span>](#optional-external-compliance-frameworks-review)
- [<span data-ttu-id="e5d2c-118">附錄 A</span><span class="sxs-lookup"><span data-stu-id="e5d2c-118">Appendix A</span></span>](#appendix-a)
- [<span data-ttu-id="e5d2c-119">附錄 B</span><span class="sxs-lookup"><span data-stu-id="e5d2c-119">Appendix B</span></span>](#appendix-b) 
- [<span data-ttu-id="e5d2c-120">附錄 C</span><span class="sxs-lookup"><span data-stu-id="e5d2c-120">Appendix C</span></span>](#appendix-c) 
- [<span data-ttu-id="e5d2c-121">附錄 D</span><span class="sxs-lookup"><span data-stu-id="e5d2c-121">Appendix D</span></span>](#appendix-d) 
- [<span data-ttu-id="e5d2c-122">附錄 E</span><span class="sxs-lookup"><span data-stu-id="e5d2c-122">Appendix E</span></span>](#appendix-e) 
- [<span data-ttu-id="e5d2c-123">附錄 F</span><span class="sxs-lookup"><span data-stu-id="e5d2c-123">Appendix F</span></span>](#appendix-f) 
- [<span data-ttu-id="e5d2c-124">附錄 G </span><span class="sxs-lookup"><span data-stu-id="e5d2c-124">Appendix G </span></span>](#appendix-g)
- [<span data-ttu-id="e5d2c-125">深入了解</span><span class="sxs-lookup"><span data-stu-id="e5d2c-125">Learn more</span></span>](#learn-more) 
- [<span data-ttu-id="e5d2c-126">詞彙</span><span class="sxs-lookup"><span data-stu-id="e5d2c-126">Glossary</span></span>](#glossary) 


## <a name="introduction"></a><span data-ttu-id="e5d2c-127">簡介</span><span class="sxs-lookup"><span data-stu-id="e5d2c-127">Introduction</span></span>

<span data-ttu-id="e5d2c-128">Microsoft 365 應用程式相容性計畫的一部分，當您將協力廠商開發人員應用程式/增益集整合至 Microsoft 365 平臺時，Microsoft 365 的憑證會為企業組織提供保證及保護的安全性。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-128">Part of the Microsoft 365 App Compliance program, the Microsoft 365 Certification offers assurance and confidence to enterprise organizations that data and privacy are adequately secured and protected when integrating third-party developer apps/add-ins into the Microsoft 365 platform.</span></span> <span data-ttu-id="e5d2c-129">透過驗證的應用程式和增益集會在整個 Microsoft 365 生態系統中指定 **Microsoft 365 認證**。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-129">Applications and add-ins that pass validation will be designated **Microsoft 365 Certified** throughout the Microsoft 365 ecosystem.</span></span> 

<span data-ttu-id="e5d2c-130">加入 Microsoft 365 的憑證計畫後，您就會同意這些補充條款，並遵循任何適用于您參與 microsoft Corporation 之 Microsoft 365 認證計畫的隨附檔， ( "Microsoft"、"我們"、"us" 或 "我們" ) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-130">By participating in the Microsoft 365 Certification  program, you are agreeing to these supplemental terms and to comply with any accompanying documentation that applies to your participation in the Microsoft 365 Certification program with Microsoft Corporation ("Microsoft", "we", "us",  or "our").</span></span> <span data-ttu-id="e5d2c-131">您表示並保證我們具有授權，可代表您自己、公司和（或）其他實體接受這些 Microsoft 365 憑證補充條款。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-131">You represent and warrant to us that you have the authority to accept these Microsoft 365 Certification supplemental terms on behalf of yourself, a company, and/or other entity, as applicable.</span></span> <span data-ttu-id="e5d2c-132">我們隨時可能會變更、修改或終止這些補充字詞。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-132">We may change, amend or terminate these supplemental terms at any time.</span></span> <span data-ttu-id="e5d2c-133">在任何變更或修正之後，您繼續參與 Microsoft 365 認證計畫，表示您同意新的增補條款。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-133">Your continued participation in the Microsoft 365 Certification program after any change or amendment means you agree to the new supplemental terms.</span></span> <span data-ttu-id="e5d2c-134">如果您不同意新的附加條款，或是我們終止這些補充條款，您必須停止參與 Microsoft 365 認證計畫。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-134">If you do not agree to the new supplemental terms or if we terminate these supplemental terms, you must stop participating in the Microsoft 365 Certification program.</span></span>

<span data-ttu-id="e5d2c-135">本檔的目標是 isv (獨立軟體廠商) 提供 Microsoft 365 認證程式的必要條件、啟動程式的必要條件，以及 isv 必須具備之特定安全性控制措施的詳細資訊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-135">This document is aimed at ISVs (Independent Software Vendors) to provide information on the Microsoft 365 Certification process, prerequisites to starting the process and details of specific security controls that ISVs must have in place.</span></span>  <span data-ttu-id="e5d2c-136">Microsoft 365 應用程式規範計畫的一般資訊，可以在 [Microsoft 365 應用程式規範方案][頁面](https://docs.microsoft.com/microsoft-365-app-certification/overview)上找到。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-136">General information of the Microsoft 365 App Compliance program can be found under the Microsoft 365 App Compliance program [page](https://docs.microsoft.com/microsoft-365-app-certification/overview).</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="e5d2c-137">目前，Microsoft 365 認證限制如下：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-137">Currently, Microsoft 365 Certification is limited:</span></span>
>* <span data-ttu-id="e5d2c-138">Microsoft Teams 應用程式 (索引標籤、bot 等 ) ]。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-138">Microsoft Teams applications (Tabs, Bots, etc.) .</span></span>
>* <span data-ttu-id="e5d2c-139">Sharepoint 應用程式/增益集</span><span class="sxs-lookup"><span data-stu-id="e5d2c-139">Sharepoint Apps/Add-ins</span></span>
>* <span data-ttu-id="e5d2c-140">Office增益集 (Word、Excel、PowerPoint、Outlook、Project、OneNote) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-140">Office Add-ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)</span></span>

## <a name="prerequisites"></a><span data-ttu-id="e5d2c-141">必要條件</span><span class="sxs-lookup"><span data-stu-id="e5d2c-141">Prerequisites</span></span>

### <a name="publisher-attestation"></a><span data-ttu-id="e5d2c-142">發行者證明</span><span class="sxs-lookup"><span data-stu-id="e5d2c-142">Publisher Attestation</span></span>

<span data-ttu-id="e5d2c-143">在獎勵 Microsoft 365 認證程式之前，您必須已完成 Publisher 證明。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-143">Before being awarded the Microsoft 365 Certification process you must have completed Publisher Attestation.</span></span> <span data-ttu-id="e5d2c-144">不過，您可以在完成 Publisher 證明之前，先開始 Microsoft 365 的認證處理常式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-144">However, you may start the Microsoft 365 Certification process prior to completing Publisher Attestation.</span></span>  

### <a name="read-the-microsoft-365-certification-specification"></a><span data-ttu-id="e5d2c-145">閱讀 Microsoft 365 的憑證規格</span><span class="sxs-lookup"><span data-stu-id="e5d2c-145">Read the Microsoft 365 Certification Specification</span></span>

<span data-ttu-id="e5d2c-146">Microsoft 建議所有 isv (獨立軟體廠商) 以完整閱讀此 Microsoft 365 的憑證規格，以確保在範圍內環境和應用程式/增益集符合所有適用的控制措施。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-146">Microsoft recommends all ISVs (Independent Software Vendor) to read this Microsoft 365 Certification Specification in its entirety to ensure all applicable controls are being met by the in-scope environment and the app/add-in.</span></span> <span data-ttu-id="e5d2c-147">這會協助確保順利進行的評估處理常式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-147">This will help ensure a smooth assessment process.</span></span>

## <a name="microsoft-365-certification-specification-updates"></a><span data-ttu-id="e5d2c-148">Microsoft 365認證規格更新</span><span class="sxs-lookup"><span data-stu-id="e5d2c-148">Microsoft 365 Certification Specification Updates</span></span> 

<span data-ttu-id="e5d2c-149">大約每隔六到十二個月就會預計 Microsoft 365 憑證規格的更新。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-149">Updates to the Microsoft 365 Certification specification are anticipated approximately every six to twelve months.</span></span> <span data-ttu-id="e5d2c-150">這些更新可能會引入新的目標安全性網域和/或安全性控制。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-150">These updates might introduce new target security domains and / or security controls.</span></span> <span data-ttu-id="e5d2c-151">更新會根據開發人員的意見反應、對威脅環境所做的變更，以及在成熟時提升程式的安全性基準。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-151">Updates will be based on developer feedback, changes to the threat landscape, and to increase the security baseline of the program as it matures.</span></span> 

<span data-ttu-id="e5d2c-152">已啟動 Microsoft 365 憑證評估的 isv 可以繼續使用評估開始時有效的 Microsoft 365 憑證規格版本進行評估。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-152">ISVs that have already started the Microsoft 365 Certification assessment can continue the assessment with the version of the Microsoft 365 Certification Specification that was valid when the assessment was started.</span></span> <span data-ttu-id="e5d2c-153">所有新送出的報送（包括年度 recertification）都會針對發行的版本進行評估。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-153">All new submissions, including annual recertification, will be required to be assessed against the version published.</span></span>

> [!NOTE]
> <span data-ttu-id="e5d2c-154">您不需要遵循此 Microsoft 365 的憑證規格中的所有控制項，就能授予憑證資格。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-154">You are not required to comply with all the controls within this Microsoft 365 Certification Specification to be awarded a certification.</span></span> <span data-ttu-id="e5d2c-155">不過，傳遞的門限 (會在此 Microsoft 365 認證規格中討論的每個安全性網域) 皆不會洩漏。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-155">However, passing thresholds (which will not be disclosed) are in place for each of the security domains discussed within this Microsoft 365 Certification Specification.</span></span> <span data-ttu-id="e5d2c-156">有些控制項會 classed 為 "**Hard Fail**"，也就是說，缺乏這些安全性控制會導致評估失敗。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-156">Some controls will be classed as a ‘**Hard Fail**’ which means the lack of these security controls will result in a failed assessment.</span></span> 

## <a name="certification-scope"></a><span data-ttu-id="e5d2c-157">認證範圍</span><span class="sxs-lookup"><span data-stu-id="e5d2c-157">Certification Scope</span></span>

<span data-ttu-id="e5d2c-158">**範圍內環境** 是支援應用程式/增益集程式碼的傳遞，並支援應用程式/增益集可能會進行通訊的任何後端系統的環境。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-158">The **in-scope environment** is the environment that supports delivery of the app/add-in code and supports any backend systems that the app/add-in may be communicating with.</span></span> <span data-ttu-id="e5d2c-159">除非有足夠的分割，而且連接至環境不會影響範圍內環境的安全性，否則任何其他連接至的環境也會包含在範圍內。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-159">Any additional connected-to environments will also be included in scope unless adequate segmentation is in place AND the connected-to environments cannot impact the security of the in-scope environment.</span></span> <span data-ttu-id="e5d2c-160">任何嚴重損壞復原環境也必須包含在評估範圍內，因為在主要環境中，fulfil 服務需要任何的環境。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-160">Any disaster recovery environments will also need to be included within the scope of the assessment as these environments would be required to fulfil the service should anything happen to the primary environment.</span></span>  <span data-ttu-id="e5d2c-161">術語  **範圍內系統元件**   參考範圍內環境中所使用的 **所有** 裝置和系統。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-161">The term  **in-scope system components** reference **ALL** devices and systems that are used within the in-scope environment.</span></span> <span data-ttu-id="e5d2c-162">範圍內的元件包括（但不限於）：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-162">In-scope components include, but are not limited to:</span></span>
* <span data-ttu-id="e5d2c-163">Web 應用程式 (s) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-163">The web application(s).</span></span>
* <span data-ttu-id="e5d2c-164">伺服器。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-164">Servers.</span></span>
* <span data-ttu-id="e5d2c-165">防火牆 (或同等) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-165">Firewalls (or equivalent).</span></span>
* <span data-ttu-id="e5d2c-166">開關。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-166">Switches.</span></span>
* <span data-ttu-id="e5d2c-167">負載平衡器。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-167">Load balancers.</span></span>
* <span data-ttu-id="e5d2c-168">虛擬基礎結構。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-168">Virtual infrastructure.</span></span>
* <span data-ttu-id="e5d2c-169">雲端提供者 web 管理入口網站</span><span class="sxs-lookup"><span data-stu-id="e5d2c-169">Cloud provider web management portals</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="e5d2c-170">在範圍內環境中，必須要有 DMZ，且應用程式/增益集的支援環境必須從內部商務系統和公司環境中細分，因此只會將評估活動的範圍限制為僅限範圍內系統。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-170">The in-scope environment, must have a DMZ and the supporting environment of the app/add-in must be segmented from the internal business systems and corporate environments thus limiting the scope of the assessment activities to the in-scope systems only.</span></span> <span data-ttu-id="e5d2c-171">憑證分析員會在評估過程中驗證分割技術，以及審查滲透測試報告，該報告應該包含測試以驗證所使用之任何分割技術的有效性。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-171">Certification analysts will validate segmentation techniques during the assessment along with reviewing penetration testing reports which should have included testing to validate the effectiveness of any segmentation techniques in use.</span></span>

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a><span data-ttu-id="e5d2c-172">基礎結構即服務 (IaaS) 、平臺為服務 (PaaS) 和軟體作為服務 (SaaS) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-172">Infrastructure as a Service (IaaS), Platform as a Service (PaaS) and Software as a Service (SaaS)</span></span> 
<span data-ttu-id="e5d2c-173">其中 IaaS 和/或 PaaS 用以支援應用程式或增益集程式碼傳遞的基礎結構在「審閱」下，雲端平臺提供者會負責在整個認證過程中評估的某些安全性控制。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-173">Where IaaS and/or PaaS is used to support the infrastructure of the application or add-in code delivery under review, the Cloud platform provider will be responsible for some of the security controls assessed throughout the certification process.</span></span> <span data-ttu-id="e5d2c-174">因此，您必須將雲端平臺提供者針對 [](bookmark://pci-dss)   符合性 (AOC) 、ISO27001 或 [SOC 2](bookmark://soc-2)   Type II 報告等外部法規遵從性報告中的安全性最佳作法，以獨立外部驗證的安全性最佳作法，提供證書分析分析員。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-174">Therefore, certification analysts will need to be provided with independent external verification of security best practices by the Cloud platform provider through external compliance reports such as [PCI DSS](bookmark://pci-dss) Attestation of Compliance (AOC), ISO27001 or [SOC 2](bookmark://soc-2) Type II reports.</span></span> 

<span data-ttu-id="e5d2c-175">附錄 F 提供根據下列部署類型及應用程式/增益集 exfiltrates M365 資料時，可能適用的安全性控制措施的詳細資料：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-175">Appendix F provides details of what security controls will likely be applicable based on the following deployment types and based upon whether the app/add-in exfiltrates M365 data or not:</span></span> 
* <span data-ttu-id="e5d2c-176">ISV 主控</span><span class="sxs-lookup"><span data-stu-id="e5d2c-176">ISV Hosted</span></span> 
* <span data-ttu-id="e5d2c-177">主控 IaaS</span><span class="sxs-lookup"><span data-stu-id="e5d2c-177">IaaS Hosted</span></span> 
* <span data-ttu-id="e5d2c-178">主控 PaaS/無伺服器</span><span class="sxs-lookup"><span data-stu-id="e5d2c-178">PaaS/Serverless Hosted</span></span> 
* <span data-ttu-id="e5d2c-179">混合主控</span><span class="sxs-lookup"><span data-stu-id="e5d2c-179">Hybrid Hosted</span></span> 
* <span data-ttu-id="e5d2c-180">共用主控</span><span class="sxs-lookup"><span data-stu-id="e5d2c-180">Shared Hosted</span></span> 

<span data-ttu-id="e5d2c-181">在部署 IaaS 或 PaaS 時，您需要提供在這些部署類型中所主控的環境證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-181">Where IaaS or PaaS is deployed, you will need to provide evidence of the environment being hosted within these deployment types.</span></span>

### <a name="sampling"></a><span data-ttu-id="e5d2c-182">採樣</span><span class="sxs-lookup"><span data-stu-id="e5d2c-182">Sampling</span></span>

<span data-ttu-id="e5d2c-183">要求憑證評估的要求應該是以範圍內系統元件的範例為基礎，以考慮不同的作業系統、裝置的主要功能，以及不同的裝置類型。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-183">Requests for evidence in support of the certification assessment should be based on a sample of the in-scope system components in consideration of different operating systems, primary function of the device, and different device types.</span></span> <span data-ttu-id="e5d2c-184">在認證程式開始時，會選取適當的範例。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-184">A suitable sample will be selected at the start of the certification process.</span></span> <span data-ttu-id="e5d2c-185">下表應用作參考樣本大小的指南：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-185">The following table should be used as a guide on what the sample size may be:</span></span>

|<span data-ttu-id="e5d2c-186">人口大小</span><span class="sxs-lookup"><span data-stu-id="e5d2c-186">Population Size</span></span>              | <span data-ttu-id="e5d2c-187">範例</span><span class="sxs-lookup"><span data-stu-id="e5d2c-187">Sample</span></span>                  |
|---------------------------- |-------------------------|
|<span data-ttu-id="e5d2c-188"><5</span><span class="sxs-lookup"><span data-stu-id="e5d2c-188"><5</span></span>|<span data-ttu-id="e5d2c-189">1</span><span class="sxs-lookup"><span data-stu-id="e5d2c-189">1</span></span>|
|<span data-ttu-id="e5d2c-190">>5 & <10</span><span class="sxs-lookup"><span data-stu-id="e5d2c-190">>5 & <10</span></span>|<span data-ttu-id="e5d2c-191">第</span><span class="sxs-lookup"><span data-stu-id="e5d2c-191">2</span></span>|
|<span data-ttu-id="e5d2c-192">>9 & <25</span><span class="sxs-lookup"><span data-stu-id="e5d2c-192">>9 & <25</span></span>|<span data-ttu-id="e5d2c-193">個</span><span class="sxs-lookup"><span data-stu-id="e5d2c-193">3</span></span>|
|<span data-ttu-id="e5d2c-194">>24</span><span class="sxs-lookup"><span data-stu-id="e5d2c-194">>24</span></span>|<span data-ttu-id="e5d2c-195">4 </span><span class="sxs-lookup"><span data-stu-id="e5d2c-195">4</span></span>|

> [!NOTE]
><span data-ttu-id="e5d2c-196">如果在初始範例中所包含的裝置之間識別差異，則在評估期間可能會增加範例大小。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-196">If discrepancies are identified between devices included within the initial sample, the sample size may be increased during the assessment.</span></span> 

## <a name="certification-process"></a><span data-ttu-id="e5d2c-197">認證程式</span><span class="sxs-lookup"><span data-stu-id="e5d2c-197">Certification Process</span></span>

<span data-ttu-id="e5d2c-198">開始認證程式之前，您必須成功 scompleted Publisher 認證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-198">Before starting the certification process, you will need to have successfully scompleted your Publisher Attestation.</span></span> <span data-ttu-id="e5d2c-199">您可以使用證明回應來支援 Microsoft 365 的憑證程式，並依下列方式繼續：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-199">Your attestation responses will be used in support of the Microsoft 365 Certification process and proceeds as follows:</span></span>

1.  <span data-ttu-id="e5d2c-200">請複查您的 Publisher 證明檔，以確保它仍可讓您的目前環境準確無誤。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-200">Review your Publisher Attestation documentation to ensure it is still accurate with your current environment.</span></span>
2.  <span data-ttu-id="e5d2c-201">請參閱 Microsoft 365 憑證提交指南，以確保您可以在開始之前滿足所有控制項。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-201">Review the Microsoft 365 Certification submission guide to ensure you can meet all the controls prior to starting.</span></span>
3.  <span data-ttu-id="e5d2c-202">按一下 [夥伴中心] 中的 [開始認證]，並提交您的初始檔提交。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-202">Click ‘Start Certification’ in partner center and submit your Initial Document Submission.</span></span> <span data-ttu-id="e5d2c-203">您的答案會協助您判斷評估的範圍。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-203">Your answers here will help to determine the scope of your assessment.</span></span>
4.  <span data-ttu-id="e5d2c-204">您將會提供完整的控制項清單，供您用來提供評估的證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-204">You will be provided a complete listing of controls for which you will need to provide evidence for your assessment.</span></span>
5.  <span data-ttu-id="e5d2c-205">提交證據，表明所有範圍內的 Microsoft 365 憑證控制都已符合60天的時段。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-205">Submit evidence that demonstrates that all in-scope Microsoft 365 Certification controls have been met within a 60-day window.</span></span>
6.  <span data-ttu-id="e5d2c-206">請經常檢查您的提交，以查看您是否有需要注意的任何批註或尚未處理的要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-206">Check your submission frequently to see if you have any comments, or outstanding requests that require your attention.</span></span> <span data-ttu-id="e5d2c-207">針對每一個取得 Microsoft 365 認證的控制權，都已核准證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-207">Once evidence has been approved for every control you will be awarded a Microsoft 365 Certification.</span></span> 


> [!IMPORTANT]
> <span data-ttu-id="e5d2c-208">**提交時間範圍：** 預計評估程式應該需要30天，但前提是您可以經常檢查您的提交狀態，並且及時回應批註和補充的證據要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-208">**Submission time frame:** It is anticipated that on average the assessment process should take 30 days, provided you are able to check your submission status frequently and respond to comments and supplemental evidence requests within a timely manner.</span></span> <span data-ttu-id="e5d2c-209">開始認證程式時，最多可允許60天完成評估。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-209">Upon starting the certification process, a maximum of 60 days is permitted to complete the assessment.</span></span> <span data-ttu-id="e5d2c-210">如果所有提交在60天的時段內都未完成，則提交將會失敗，且必須重新開始該程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-210">If all submissions have not been completed within the 60-day time-period, the submission will be issued a failure and the process must start again.</span></span> <span data-ttu-id="e5d2c-211">這些結果不會變成公開的。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-211">These results will not be made public.</span></span>


## <a name="initial-document-submission"></a><span data-ttu-id="e5d2c-212">初始檔提交</span><span class="sxs-lookup"><span data-stu-id="e5d2c-212">Initial Document Submission</span></span>

<span data-ttu-id="e5d2c-213">初始檔提交會協助認證分析員執行範圍，並決定評估的範圍中的內容。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-213">The initial document submission will help certification analysts perform scoping and determine what will be in scope for your assessment.</span></span> <span data-ttu-id="e5d2c-214">之後，您將需要提交用於執行評估的支援檔和證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-214">After which you will be required to submit supporting documentation and evidence used to carry out the assessment.</span></span> <span data-ttu-id="e5d2c-215">您的初始提交必須包含下列所指定的資訊：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-215">Your initial submission must include the information specified below:</span></span>

| <span data-ttu-id="e5d2c-216">**檔 &nbsp; 概述**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-216">**Documentation&nbsp;Overview**</span></span>     |   <span data-ttu-id="e5d2c-217">**檔詳細資料**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-217">**Documentation Details**</span></span>  |
| -------------------------| -----------------------------|
|<span data-ttu-id="e5d2c-218">**應用程式/增益集描述**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-218">**App/Add-in Description**</span></span> | <span data-ttu-id="e5d2c-219">App/增益集的用途及功能的描述。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-219">A description of the app/add-in’s purpose and functionality.</span></span> <span data-ttu-id="e5d2c-220">這可讓認證分析分析員充分瞭解應用程式/增益集的功能及其用途。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-220">This should provide the certification analyst with a good understanding of how the app/add-in functions and what it is intended use is</span></span>
|<span data-ttu-id="e5d2c-221">**滲透測試報告**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-221">**Penetration Testing Report**</span></span> |<span data-ttu-id="e5d2c-222">在過去12個月內完成的滲透測試報告。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-222">A penetration testing report completed within the last 12 months.</span></span> <span data-ttu-id="e5d2c-223">此報告必須包含支援部署應用程式/新增的環境，以及支援應用程式/增益集作業的任何其他環境。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-223">This report must include the environment that supports the deployment of the app/add along with any additional environment that supports the operation of the app/add-in.</span></span> <span data-ttu-id="e5d2c-224">**附注：** 如果您不執行年度滲透測試，您可以選擇透過認證程式完成。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-224">**Note:** if you do not do annual penetration testing, you can elect to have them done through the certification process.</span></span>|
|<span data-ttu-id="e5d2c-225">**架構圖表**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-225">**Architecture diagrams**</span></span>|<span data-ttu-id="e5d2c-226">邏輯架構圖，代表應用程式/增益集的支援基礎結構的高層次概述。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-226">A logical architecture diagram representing a high-level overview of your app's / add-in’s supporting infrastructure.</span></span> <span data-ttu-id="e5d2c-227">這必須包含支援應用程式/增益集的 **所有** 主控環境和支援基礎結構。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-227">This must include **all** hosting environments and supporting infrastructure supporting the app/add-in.</span></span> <span data-ttu-id="e5d2c-228">此圖表必須說明環境內所有不同的支援系統元件，以協助認證分析員瞭解範圍內的系統，並協助判斷抽樣。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-228">This diagram MUST depict all the different supporting system components within the environment to help certification analysts understand systems in scope and help to determine sampling.</span></span> <span data-ttu-id="e5d2c-229">請另外指出使用的主控環境類型;ISV 主控、IaaS、PaaS 或混合式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-229">Please also indicate what hosting environment type is used; ISV Hosted, IaaS, PaaS, or Hybrid.</span></span> <span data-ttu-id="e5d2c-230">**附注：** 在使用 SaaS 的地方，請指出用來在環境中提供支援服務的各種 SaaS 服務。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-230">**Note:** Where SaaS is used, please indicate the various SaaS services that are used to provide the supporting services within the environment.</span></span>|
|<span data-ttu-id="e5d2c-231">**公開的足跡**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-231">**Public Footprint**</span></span> | <span data-ttu-id="e5d2c-232">詳述支援基礎結構所使用的 **所有** 公用 IP 位址和 URLs。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-232">Detailing **all** public IP Addresses and URLs used by the supporting infrastructure.</span></span> <span data-ttu-id="e5d2c-233">這必須包含為環境所指派的完整可路由 IP 範圍，除非已執行適當的分割才能分割使用中的範圍 (足夠的分割的證據) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-233">This must include the full routable IP range allocated to the environment unless adequate segmentation has been implemented to split the range in use (adequate evidence of segmentation will be required)</span></span>|
|<span data-ttu-id="e5d2c-234">**資料流程圖**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-234">**Data flow diagrams**</span></span> |<span data-ttu-id="e5d2c-235">Flow 圖詳述下列各項：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-235">Flow diagrams detailing the following:</span></span>
||<span data-ttu-id="e5d2c-236">在應用程式/增益集 (中 &#x2713; M365 資料流程，包括 [EUII](#euii) 和 [OII](#oii) ) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-236">&#x2713; M365 Data flows to and from the App / Add-in (including [EUII](#euii) and [OII](#oii) ).</span></span>|
||<span data-ttu-id="e5d2c-237">&#x2713; 在支援的基礎結構內 M365 資料流程 (適用于) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-237">&#x2713; M365 Data flows within the supporting infrastructure(where applicable)</span></span>|
||<span data-ttu-id="e5d2c-238">&#x2713; 圖表會強調儲存的位置和資料，也就是將資料傳遞給外部協力廠商的方式 (包含哪些協力廠商) 的詳細資料，以及如何透過開放/公用網路及靜態網路傳輸來保護資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-238">&#x2713; Diagrams highlighting where and what data is stored, how data is passed to external third parties(including details of what third parties) , and how data is protected in transit over open/public networks and at rest.</span></span>|
|<span data-ttu-id="e5d2c-239">**API 端點詳細資料**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-239">**API Endpoint Details**</span></span>| <span data-ttu-id="e5d2c-240">您的應用程式所使用之所有 API 端點的完整清單。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-240">A complete listing of all API Endpoints used by your app.</span></span> <span data-ttu-id="e5d2c-241">為了協助瞭解環境範圍，請在您的環境中提供 API 端點位置。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-241">To help understand the environment scope, provide API endpoint locations within your environment.</span></span>                                
|<span data-ttu-id="e5d2c-242">**Microsoft API 許可權**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-242">**Microsoft API Permissions**</span></span>| <span data-ttu-id="e5d2c-243">提供檔，詳述 **所有** 與要求的應用程式/增益集一起使用之許可權的 Microsoft APIs，以及要求的許可權的理由</span><span class="sxs-lookup"><span data-stu-id="e5d2c-243">Provide documentation detailing **ALL** the Microsoft APIs that are used along with what permissions are being requested for the app/add-in to function along with a justification for the requested permissions</span></span>|
|<span data-ttu-id="e5d2c-244">**資料儲存類型**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-244">**Data storage types**</span></span> |<span data-ttu-id="e5d2c-245">資料儲存與處理檔說明：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-245">Data storage and handling documents describing:</span></span>|
||<span data-ttu-id="e5d2c-246">&#x2713; 您的客戶 M365 資料 [EUII](#euii) 和 [OII](#oii) 正在接收及儲存的程度</span><span class="sxs-lookup"><span data-stu-id="e5d2c-246">&#x2713; To what extent is your customers M365 Data [EUII](#euii) and [OII](#oii) is being received and stored</span></span>|
||<span data-ttu-id="e5d2c-247">&#x2713; 資料保留期間。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-247">&#x2713; The data retention period.</span></span>|
||<span data-ttu-id="e5d2c-248">&#x2713; 即將捕獲客戶 M365 資料的原因。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-248">&#x2713; Why the customer M365 Data is being captured.</span></span>|
||<span data-ttu-id="e5d2c-249">儲存客戶 M365 資料的 &#x2713; (應該包含在上述) 中的資料流程圖內。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-249">&#x2713; Where customer M365 Data is stored (should be included within data flow diagrams supplied above).</span></span>|
|<span data-ttu-id="e5d2c-250">**合規性確認**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-250">**Compliance confirmation**</span></span>|<span data-ttu-id="e5d2c-251">Publisher 認證提交內包含的外部安全性框架的支援檔，或在複查 Microsoft 365 憑證控制時加以考慮。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-251">Supporting documentation for external security frameworks included within the Publisher Attestation submission or to be considered when reviewing Microsoft 365 Certification controls.</span></span> <span data-ttu-id="e5d2c-252">目前支援下列三個專案：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-252">Currently, the following three are supported:</span></span>|
||<span data-ttu-id="e5d2c-253"> (AOC) 的相容性 &#x2713; [PCI DSS](#pci-dss) 證明。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-253">&#x2713; [PCI DSS](#pci-dss) Attestation of Compliance (AOC).</span></span>|
||<span data-ttu-id="e5d2c-254">&#x2713; [SOC 2](#soc-2) Type I/type II 報告。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-254">&#x2713; [SOC 2](#soc-2) Type I/Type II reports.</span></span>|
||<span data-ttu-id="e5d2c-255">&#x2713; [ism](#isms)  /  [IEC](#iec) -1S0/IEC 27001 的適用性聲明 (SoA) 和認證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-255">&#x2713; [ISMS](#isms) / [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.</span></span>|
|<span data-ttu-id="e5d2c-256">**Web 相依性**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-256">**Web Dependencies**</span></span>|<span data-ttu-id="e5d2c-257">檔：列出使用目前執行中的應用程式/增益集所使用的所有依存關係。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-257">Documentation listing all dependencies used by the app / add-in with the current running versions.</span></span>|
|<span data-ttu-id="e5d2c-258">**軟體清查**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-258">**Software Inventory**</span></span>|<span data-ttu-id="e5d2c-259">最新的軟體清查，包含範圍內環境中所使用的所有軟體，以及版本。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-259">An up-to-date software inventory which includes all software used within the in-scope environment along with the versions.</span></span>|
|<span data-ttu-id="e5d2c-260">**硬體清單**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-260">**Hardware Inventory**</span></span>| <span data-ttu-id="e5d2c-261">支援基礎結構所使用的最新硬體清單。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-261">An up-to-date hardware inventory used by the supporting infrastructure.</span></span> <span data-ttu-id="e5d2c-262">這會在執行評估階段時用於協助抽樣。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-262">This will be used to help with sampling when performing the assessment phase.</span></span> <span data-ttu-id="e5d2c-263">如果您的環境包含 PaaS 提供所使用之服務的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-263">If your environment includes PaaS provide details of services consumed.</span></span>|

## <a name="evidence-collection-and-assessment-activities"></a><span data-ttu-id="e5d2c-264">證據收集和評估活動</span><span class="sxs-lookup"><span data-stu-id="e5d2c-264">Evidence Collection and Assessment Activities</span></span>

<span data-ttu-id="e5d2c-265">憑證分析員必須在定義的範例集內，檢查所有系統元件的證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-265">Certification analysts will need to review evidence across all system components within the defined sample set.</span></span> <span data-ttu-id="e5d2c-266">支援評估程式所需的證據類型包括下列任何或所有專案：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-266">The types of evidence required to support the assessment process include any or all the following:</span></span>

<span data-ttu-id="e5d2c-267">**證據集合**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-267">**Evidence Collection**</span></span>

* <span data-ttu-id="e5d2c-268">初始檔，在上方的 [初始檔提交](#initial-document-submission) 區段中高亮顯示</span><span class="sxs-lookup"><span data-stu-id="e5d2c-268">Initial documentation, highlighted within the [Initial Documentation Submission](#initial-document-submission) section above</span></span> 
* <span data-ttu-id="e5d2c-269">原則檔</span><span class="sxs-lookup"><span data-stu-id="e5d2c-269">Policy documents</span></span> 
* <span data-ttu-id="e5d2c-270">處理檔</span><span class="sxs-lookup"><span data-stu-id="e5d2c-270">Process documents</span></span> 
* <span data-ttu-id="e5d2c-271">系統設定</span><span class="sxs-lookup"><span data-stu-id="e5d2c-271">System configuration settings</span></span> 
* <span data-ttu-id="e5d2c-272">變更票證</span><span class="sxs-lookup"><span data-stu-id="e5d2c-272">Change tickets</span></span> 
* <span data-ttu-id="e5d2c-273">變更控制項記錄</span><span class="sxs-lookup"><span data-stu-id="e5d2c-273">Change control records</span></span> 
* <span data-ttu-id="e5d2c-274">系統報告</span><span class="sxs-lookup"><span data-stu-id="e5d2c-274">System reports</span></span>

<span data-ttu-id="e5d2c-275">將使用各種方法來收集完成評估程式所需的證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-275">Various methods will be used to collect the evidence necessary to complete the assessment process.</span></span>  <span data-ttu-id="e5d2c-276">此證據集合的格式可為：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-276">This evidence collection may be in the form of:</span></span> 
* <span data-ttu-id="e5d2c-277">文件</span><span class="sxs-lookup"><span data-stu-id="e5d2c-277">Documents</span></span> 
* <span data-ttu-id="e5d2c-278">螢幕擷取畫面</span><span class="sxs-lookup"><span data-stu-id="e5d2c-278">Screenshots</span></span> 
* <span data-ttu-id="e5d2c-279">採訪</span><span class="sxs-lookup"><span data-stu-id="e5d2c-279">Interviews</span></span> 
* <span data-ttu-id="e5d2c-280">Screensharing</span><span class="sxs-lookup"><span data-stu-id="e5d2c-280">Screensharing</span></span> 

<span data-ttu-id="e5d2c-281">使用的證據集合技術會在評估程式期間決定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-281">The evidence collection techniques used will be determined during the assessment process.</span></span> 

<span data-ttu-id="e5d2c-282">**評估活動**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-282">**Assessment Activities**</span></span>

<span data-ttu-id="e5d2c-283">憑證分析員會檢查您所提供的證據，以判斷您是否有足夠的控制此 Microsoft 365 認證規格。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-283">Certification analysts will review evidence you provide to determine if you have adequately met controls within this Microsoft 365 Certification Specification.</span></span> 

<span data-ttu-id="e5d2c-284">您應該盡可能提供 [初始檔提交](#initial-document-submission)中所述的任何或所有檔，以盡可能縮短評估所需的時間   。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-284">Where possible and to reduce the amount of time required to complete the assessment, any or all of the documentation detailed in the [Initial Documentation Submission](#initial-document-submission) should be provided in advance.</span></span>

<span data-ttu-id="e5d2c-285">憑證分析員會先從最初的檔提交和 Publisher 認證資訊中檢查提供的證據，以識別適當的查詢、採樣大小，以及如以上所述取得進一步證據的需要。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-285">Certification analysts will first review the evidence provided from the initial documentation submission and the Publisher Attestation information to identify appropriate lines of inquiry, sampling size, and the need for further evidence to be obtained as detailed above.</span></span>  <span data-ttu-id="e5d2c-286">憑證分析員會分析所有收集到的資訊，以在此 Microsoft 365 憑證規格內，如何以及是否要為您的控制會議做的結論。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-286">Certification analysts will analyze all information gathered to draw conclusions as to how and if you are meeting the controls within this Microsoft 365 Certification Specification.</span></span> 

## <a name="app-certification-criteria"></a><span data-ttu-id="e5d2c-287">應用程式認證準則</span><span class="sxs-lookup"><span data-stu-id="e5d2c-287">App Certification Criteria</span></span>

<span data-ttu-id="e5d2c-288">您的應用程式、支援基礎結構，以及支援檔將會跨下列安全網域評估：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-288">Your app, supporting infrastructure, and supporting documentation will be assessed across the following security domains:</span></span>

1. [<span data-ttu-id="e5d2c-289">**Application Security**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-289">**Application Security**</span></span>](#application-security)
1. [<span data-ttu-id="e5d2c-290">**運作安全性/安全部署**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-290">**Operational Security / Secure Deployment**</span></span>](#operational-security)
1. [<span data-ttu-id="e5d2c-291">**資料處理安全性和隱私權**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-291">**Data Handling Security and Privacy**</span></span>](#data-handling-security-and-privacy)

<span data-ttu-id="e5d2c-292">這些安全網域中的每一個都包含特定的主要控制項，包含一或多個在評估程式中評估的特定需求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-292">Each of these security domains includes specific key controls encompassing one or more specific requirements that will be evaluated as part of the assessment process.</span></span> <span data-ttu-id="e5d2c-293">為了確保所有大小的開發人員都包含 Microsoft 365 憑證，每個安全性網域都會使用計分系統進行評估，以判斷每個網域的整體分數。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-293">To ensure that Microsoft 365 Certification is inclusive to developers of all sizes, each of the security domains is assessed using a scoring system to determine an overall score from each of the domains.</span></span> <span data-ttu-id="e5d2c-294">每個 Microsoft 365 憑證控制項的分數是以 1 (低) 和 3 (高) 為基礎，而不是以該控制項的感知風險為基礎。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-294">Scores for each of the Microsoft 365 Certification controls are allocated between 1 (low) and 3 (high) based upon the perceived risk of that control not being met.</span></span> <span data-ttu-id="e5d2c-295">每個安全性網域都會有最小的百分號，以視為傳遞。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-295">Each of the security domains will have a minimum percentage mark to be deemed a pass.</span></span> <span data-ttu-id="e5d2c-296">此規格的某些元素包含一些自動失敗的準則：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-296">Certain elements of this specification include some automatic fail criteria:</span></span>

- <span data-ttu-id="e5d2c-297">API 許可權不遵循 (PoLP) 最低許可權原則。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-297">API permissions not following the principle of least privilege (PoLP).</span></span>  
- <span data-ttu-id="e5d2c-298">不需要滲透測試報告。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-298">No penetration testing report when it is required.</span></span>
- <span data-ttu-id="e5d2c-299">無反惡意程式碼防護</span><span class="sxs-lookup"><span data-stu-id="e5d2c-299">No anti-malware defenses</span></span>
- <span data-ttu-id="e5d2c-300">未使用 Multi-Factor 驗證來保護系統管理存取。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-300">Multi-Factor authentication not being used to protect administrative access.</span></span>  
- <span data-ttu-id="e5d2c-301">沒有修補程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-301">No patching processes.</span></span>  
- <span data-ttu-id="e5d2c-302">無適當的 [GDPR](#gdpr) 隱私權通知。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-302">No suitable [GDPR](#gdpr) privacy notice.</span></span>  

## <a name="application-security"></a><span data-ttu-id="e5d2c-303">Application Security</span><span class="sxs-lookup"><span data-stu-id="e5d2c-303">Application Security</span></span>

<span data-ttu-id="e5d2c-304">應用程式安全性網域著重于下列三個區域：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-304">The application security domain focuses upon the following three areas:</span></span> 
* <span data-ttu-id="e5d2c-305">GraphAPI 許可權驗證</span><span class="sxs-lookup"><span data-stu-id="e5d2c-305">GraphAPI Permission Validation</span></span> 
* <span data-ttu-id="e5d2c-306">外部連線檢查</span><span class="sxs-lookup"><span data-stu-id="e5d2c-306">External Connectivity Checks</span></span>
* <span data-ttu-id="e5d2c-307">應用程式安全性測試</span><span class="sxs-lookup"><span data-stu-id="e5d2c-307">Application Security Testing</span></span> 

### <a name="graphapi-permission-validation"></a><span data-ttu-id="e5d2c-308">GraphAPI 許可權驗證</span><span class="sxs-lookup"><span data-stu-id="e5d2c-308">GraphAPI Permission Validation</span></span>

<span data-ttu-id="e5d2c-309">GraphAPI 許可權驗證的執行是為了驗證應用程式/增益集不會要求太好的許可權。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-309">GraphAPI permission validation is carried out to validate the app/add-in does not request overly permissive permissions.</span></span> <span data-ttu-id="e5d2c-310">這是透過手動檢查要求的許可權來執行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-310">This is carried out by manually checking what permissions are requested.</span></span> <span data-ttu-id="e5d2c-311">憑證分析員會依照 Publisher 認證提交的方式參考這些檢查，並評估所要求的存取層級，以確保符合「最低許可權」作法。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-311">Certification analysts will cross reference these checks against the Publisher Attestation submission and evaluate the level of access being requested to ensure ‘least privilege’ practices are being met.</span></span> <span data-ttu-id="e5d2c-312">當憑證分析員認為未符合這些「最低許可權」做法時，認證分析員會與您展開討論，以驗證所要求之許可權的業務理由。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-312">Where certification analysts believe these ‘least privilege’ practices are not being met, certification analysts will have an open discussion with you to validate the business justification for the permissions being requested.</span></span> <span data-ttu-id="e5d2c-313">在此評審期間，任何與您的 Publisher 認證提交相關的矛盾也會取得意見反應，使您的 Publisher 證明得以更新。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-313">Any discrepancies against your Publisher Attestation submission found during this review will also get feedback so your Publisher Attestation can be updated.</span></span> 

### <a name="external-connectivity-checks"></a><span data-ttu-id="e5d2c-314">外部連線檢查</span><span class="sxs-lookup"><span data-stu-id="e5d2c-314">External Connectivity Checks</span></span>

<span data-ttu-id="e5d2c-315">在評估過程中，分析員會執行應用程式功能的輕量指導，以識別 M365 之外的連線。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-315">As part of the assessment, an Analyst will perform a light walk through of the applications functionality to identify connections outside of M365.</span></span>  <span data-ttu-id="e5d2c-316">在評估期間，將會標記並討論任何未識別為 Microsoft 或直接連線至服務的連線。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-316">Any connections which are not identified as being Microsoft or direct connections to your service will be flagged and discussed during the assessment.</span></span>

### <a name="application-security-testing"></a><span data-ttu-id="e5d2c-317">應用程式安全性測試</span><span class="sxs-lookup"><span data-stu-id="e5d2c-317">Application Security Testing</span></span>

<span data-ttu-id="e5d2c-318">在應用程式/增益集與支援環境相關聯的風險中，有足夠的複查，在應用程式/增益集的安全性中為客戶提供保證保證是必要的。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-318">An adequate review of the risks associated with your app/add-in and supporting environment is essential in providing customers with assurance in the security of the app/add-in.</span></span> <span data-ttu-id="e5d2c-319">如果您的應用程式與 Microsoft 未發佈的任何服務有任何連線，則必須執行採用滲透測試形式的應用程式安全性測試。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-319">Application security testing in the form of penetration testing MUST be carried out if your application has any connectivity to any service not published by Microsoft.</span></span> <span data-ttu-id="e5d2c-320">如果您的應用程式獨立運作，但沒有連接至任何非 Microsoft 服務或後端，則不需要滲透測試。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-320">If your app operates standalone without connectivity to any non-Microsoft service or backend, then penetration testing is not required.</span></span>


<span data-ttu-id="e5d2c-321">**滲透測試範圍**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-321">**Penetration Testing Scope**</span></span>

<span data-ttu-id="e5d2c-322">滲透測試活動 **必須** 包含支援部署應用程式/增益集的環境 (例如，應用程式/增益集程式碼的主控位置通常是資訊清單檔案中的資源) ，以及任何支援應用程式/增益集作業的其他環境 (例如，若應用程式/增益集與 Microsoft 365) 以外的其他 web 應用程式交談。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-322">Penetration testing activities **MUST** include the environment that supports the deployment of the app/add-in (for example; where the app/add-in code is hosted which will typically be the resource within the manifest file) along with any additional environment that supports the operation of the app/add-in (for example; if the app/add-in talks to other web applications outside of Microsoft 365).</span></span>  <span data-ttu-id="e5d2c-323">在定義範圍時，必須特別注意，以確保任何「連線至」系統或可能影響範圍內環境安全性的環境，也都會包含在所有滲透測試活動中。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-323">When defining the scope, care needs to be taken to ensure that any “connected-to” systems or environments that can impact upon the security of the in-scope environment is also included within ALL penetration testing activities.</span></span> 

<span data-ttu-id="e5d2c-324">使用技術從其他環境分割範圍內的環境時，滲透測試活動必須驗證說出分割技術的有效性。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-324">Where techniques are used to segment the in-scope environments from other environments, penetration testing activities MUST validate the effectiveness of said segmentation techniques.</span></span> <span data-ttu-id="e5d2c-325">這必須在滲透測試報告中詳細說明。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-325">This must be detailed within the penetration testing report.</span></span> 

<span data-ttu-id="e5d2c-326">將會檢查滲透測試報告，以確保沒有符合下列控制項中所述下列 **自動失敗準則** 的漏洞。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-326">Penetration testing reports will be reviewed to ensure there are no vulnerabilities that meet the following **automatic failure criteria** outlined in the controls below.</span></span>
 
<span data-ttu-id="e5d2c-327">**滲透測試需求**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-327">**Penetration testing Requirements**</span></span>
||<span data-ttu-id="e5d2c-328">**滲透測試控制項**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-328">**Penetration Test Controls**</span></span>|
| -------------------------|-----------------------------|
|<span data-ttu-id="e5d2c-329">**一般準則**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-329">**General Criteria**</span></span>| <span data-ttu-id="e5d2c-330">**Controls**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-330">**Controls**</span></span>|
|| <span data-ttu-id="e5d2c-331">應用程式和基礎結構滲透測試 **必須** 每年 (12 個月進行，) 且由著名的獨立公司執行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-331">Application and infrastructure penetration testing **MUST** take place annually (every 12 months) and conducted by a reputable independent company.</span></span> |
|| <span data-ttu-id="e5d2c-332">修正的嚴重和高風險弱點 **必須** 在滲透測試結束的一個月內完成，或根據所記錄的修補程式。 </span><span class="sxs-lookup"><span data-stu-id="e5d2c-332">Remediation of identified critical and high-risk vulnerabilities **MUST** be completed within one month of the conclusion of the penetration testing, or sooner depending on the documented patching process. </span></span>|
|| <span data-ttu-id="e5d2c-333"> (IP 位址、URLs、API 端點 ) 等的完整外部空間，必須包含在滲透測試範圍內，且必須在滲透測試報告中加以記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-333">The full external footprint (IP Addresses, URLs, API Endpoints, etc.) MUST be included within the scope of penetration testing and must be documented within the penetration testing report.</span></span> |
|| <span data-ttu-id="e5d2c-334">Web 應用程式滲透測試必須包含所有弱點類別;例如，最新的 OWASP Top 10 或 SANS Top 25 CWE。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-334">Web application penetration testing MUST include all vulnerability classes; for example, the most current OWASP Top 10 or SANS Top 25 CWE.</span></span> |
|| <span data-ttu-id="e5d2c-335">不需要透過滲透測試公司重新測試已識別的漏洞-修復和自我審查是足夠的，所以評估期間 **必須** 提供足夠的證據來示範足夠的修復。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-335">Retesting of identified vulnerabilities by the penetration testing company is not required — remediation and self-review is sufficient however, adequate evidence to demonstrate sufficient remediation **MUST** be provided during the assessment.</span></span>|
|<span data-ttu-id="e5d2c-336">**自動失敗準則：**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-336">**Automatic Failure Criteria:**</span></span>|<span data-ttu-id="e5d2c-337">**Controls**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-337">**Controls**</span></span>|
|| <span data-ttu-id="e5d2c-338">目前是否有不受支援的作業系統。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-338">Presence of an unsupported operating system.</span></span> |
|| <span data-ttu-id="e5d2c-339">預設值、可枚舉或 guessable 的系統管理帳戶是否存在。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-339">Presence of default, enumerable, or guessable administrative accounts.</span></span>|
|| <span data-ttu-id="e5d2c-340">目前是否存在 SQL 注入風險。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-340">Presence of SQL injection risks.</span></span>|
|| <span data-ttu-id="e5d2c-341">跨網站腳本的存在。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-341">Presence of cross-site scripting.</span></span>|
|| <span data-ttu-id="e5d2c-342">目錄遍歷 (檔案路徑) 漏洞。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-342">Presence of directory traversal (file path) vulnerabilities.</span></span>|
|| <span data-ttu-id="e5d2c-343">HTTP 弱點的存在，例如標頭回應分割、要求 smuggling 及 Desync 攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-343">Presence of HTTP vulnerabilities, e.g., Header response splitting, Request smuggling, and Desync attacks.</span></span>|
|| <span data-ttu-id="e5d2c-344">來原始程式碼洩漏 (包括 [LFI](#lfi)) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-344">Presence of source code disclosure (including [LFI](#lfi)).</span></span>|
|| <span data-ttu-id="e5d2c-345">CVSS 修補程式管理指導方針所定義的任何重要或高分數。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-345">Any critical or high score as defined by the CVSS patch management guidelines.</span></span>|
|| <span data-ttu-id="e5d2c-346">任何重要的技術弱點，可被攻擊者利用以攻破大量的 EUII 或 OUI。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-346">Any significant technical vulnerability which can be readily exploited to compromise a large amount of EUII or OUI.</span></span>|






> [!IMPORTANT]
><span data-ttu-id="e5d2c-347">報表必須能夠提供足夠的保證，您可以在 Application Security Test 規格區段中的詳細資訊中加以示範。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-347">Reports must be able to provide enough assurance that everything detailed within the Application Security Test Specification section can be demonstrated.</span></span>


<span data-ttu-id="e5d2c-348">**滲透測試需求和成本**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-348">**Penetration Testing Requirements and Cost**</span></span>

<span data-ttu-id="e5d2c-349">針對目前未參與滲透測試的 isv，滲透測試會包含在 Microsoft 365 憑證之下。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-349">For ISVs that currently do not engage in penetration testing, penetration testing is included under the Microsoft 365 Certification.</span></span> <span data-ttu-id="e5d2c-350">Microsoft 會安排並涵蓋最多12天手動測試的滲透測試成本。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-350">Microsoft will arrange and cover the cost of a penetration test for up to 12 days of manual testing.</span></span> <span data-ttu-id="e5d2c-351">滲透測試成本的計算取決於測試環境所需的天數。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-351">Penetration tests costs are calculated based on the number of days required to test the environment.</span></span> <span data-ttu-id="e5d2c-352">任何超過12天測試的費用都會成為 ISV 的責任。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-352">Any expenses exceeding 12 days of testing will be the responsibility of the ISV.</span></span> <span data-ttu-id="e5d2c-353">ISV 也會負責示範滲透測試中所識別的安全性漏洞已在取得認證之前修正，但不需要產生全新報告。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-353">The ISV will also be responsible for demonstrating that vulnerabilities identified in the penetration test have been remediated prior to a certification being awarded, but do not need to produce a clean report.</span></span>

<span data-ttu-id="e5d2c-354">在排列滲透測試之後，ISV 會負責與重新排定和取消相關的費用，如下所示：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-354">Once a penetration test is arranged, the ISV is responsible for fees associated with rescheduling and cancellations as follows:</span></span>

| <span data-ttu-id="e5d2c-355">**重新排定費用的時間**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-355">**Rescheduling Fee Timescale**</span></span> | <span data-ttu-id="e5d2c-356">**應付比例**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-356">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="e5d2c-357">在排定的開始日期之前的30天內，重新排程要求的接收時間超過30天。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-357">Re-schedule request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="e5d2c-358">0% 應付</span><span class="sxs-lookup"><span data-stu-id="e5d2c-358">0% Payable</span></span> |
| <span data-ttu-id="e5d2c-359">預定的開始日期之前，請重新排定要求的前8至30天。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-359">Re-schedule request received 8 to 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="e5d2c-360">25% 應付</span><span class="sxs-lookup"><span data-stu-id="e5d2c-360">25% Payable</span></span> |
| <span data-ttu-id="e5d2c-361">在排定的開始日期之前的2到7天內，將要求重新排定的時間設定為固定的重新預約日期。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-361">Re-schedule request received within 2 to 7 days prior to scheduled start date with a firm re-booking date.</span></span>| <span data-ttu-id="e5d2c-362">50% 應付</span><span class="sxs-lookup"><span data-stu-id="e5d2c-362">50% Payable</span></span> |
| <span data-ttu-id="e5d2c-363">在開始日期之前的2天內，重新排程要求的接收時間小於2天。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-363">Re-schedule request received less than 2 days before the start date.</span></span> | <span data-ttu-id="e5d2c-364">100% 應付</span><span class="sxs-lookup"><span data-stu-id="e5d2c-364">100% Payable</span></span> |

| <span data-ttu-id="e5d2c-365">**取消費用時間**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-365">**Cancellation Fee Timescale**</span></span> | <span data-ttu-id="e5d2c-366">**應付比例**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-366">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="e5d2c-367">在排定的開始日期之前收到超過30天的取消要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-367">Cancellation request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="e5d2c-368">25% 應付</span><span class="sxs-lookup"><span data-stu-id="e5d2c-368">25% Payable</span></span> |
| <span data-ttu-id="e5d2c-369">在排定的開始日期之前，已接收到8至30天的取消要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-369">Cancellation request received 8 to 30 days days prior to scheduled start date.</span></span> | <span data-ttu-id="e5d2c-370">50% 應付</span><span class="sxs-lookup"><span data-stu-id="e5d2c-370">50% Payable</span></span> |
| <span data-ttu-id="e5d2c-371">在排定的開始日期之前7天內收到的取消要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-371">Cancellation request received within 7 days prior to scheduled start date.</span></span> | <span data-ttu-id="e5d2c-372">90% 應付</span><span class="sxs-lookup"><span data-stu-id="e5d2c-372">90% Payable</span></span> |

## <a name="operational-security"></a><span data-ttu-id="e5d2c-373">運作安全性</span><span class="sxs-lookup"><span data-stu-id="e5d2c-373">Operational Security</span></span>

<span data-ttu-id="e5d2c-374">這個網域會以安全性最佳作法衡量應用程式的支援基礎結構和部署程式的對齊方式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-374">This domain measures the alignment of your app's supporting infrastructure and deployment processes with security best practices.</span></span>

### <a name="controls"></a><span data-ttu-id="e5d2c-375">控制措施</span><span class="sxs-lookup"><span data-stu-id="e5d2c-375">Controls</span></span>

|<span data-ttu-id="e5d2c-376">**控制系列**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-376">**Control Family**</span></span>| <span data-ttu-id="e5d2c-377">**Controls**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-377">**Controls**</span></span>|
| ------------------------|------------------------------ |
| <span data-ttu-id="e5d2c-378">**惡意程式碼保護**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-378">**Malware Protection**</span></span>|<span data-ttu-id="e5d2c-379">提供原則檔，以管理防病毒的作法與程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-379">Provide policy documentation that governs anti-virus practices and procedures.</span></span>|
||<span data-ttu-id="e5d2c-380">提供 demonstratable 證據，表明防毒軟體是在所有抽樣的系統元件上執行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-380">Provide demonstratable evidence that anti-virus software is running across all sampled system components.</span></span>|
||<span data-ttu-id="e5d2c-381">提供 demonstratable 證據，讓所有環境 (在1天) 內，都是最新的防病毒簽名。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-381">Provide demonstratable evidence that anti-virus signatures are up-to-date across all environments (within 1 day).</span></span>|
||<span data-ttu-id="e5d2c-382">提供 demonstratable 證據，以將反病毒設定為執行跨存取掃描或所有抽樣系統元件的定期掃描。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-382">Provide demonstratable evidence that anti-virus is configured  to perform on-access scanning or periodic scan across all sampled system components.</span></span> <span data-ttu-id="e5d2c-383">附注：如果未啟用存取掃描，則必須啟用最低的日常掃描及警示。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-383">Note: If on-access scanning is not enabled, then a minimum of daily scanning and alerting MUST be enabled.</span></span>|
||<span data-ttu-id="e5d2c-384">提供 demonstratable 證據，以防病毒方式設定為自動封鎖所有抽樣系統元件的惡意程式碼或隔離及警示。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-384">Provide demonstratable evidence that anti-virus is configured to automatically block malware or quarantine and alert across all sampled system components.</span></span>|
|<span data-ttu-id="e5d2c-385">**應用程式控制項**：只有在未使用傳統反惡意程式碼時才需要</span><span class="sxs-lookup"><span data-stu-id="e5d2c-385">**Application Controls**: ONLY required if traditional anti-malware is not used</span></span>|<span data-ttu-id="e5d2c-386">提供 demonstratable 證據，以在部署之前核准應用程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-386">Provide demonstratable evidence that applications are approved prior to being deployed.</span></span>|
||<span data-ttu-id="e5d2c-387">提供 demonstratable 證據，表明具有業務合理性論證的核准應用程式完整清單已存在並維持維護。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-387">Provide demonstratable evidence that a complete list of approved applications with business justification exists and is maintained.</span></span>|
||<span data-ttu-id="e5d2c-388">提供支援檔，詳述應用程式控制軟體的設定，以符合特定的應用程式控制機制。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-388">Provide supporting documentation detailing that application control software is configured to meet specific application control mechanisms.</span></span> <span data-ttu-id="e5d2c-389"> (範例：允許的清單： sample1、sample3、程式碼簽署) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-389">(Example:  Allowed listing: sample1, sample3, code signing)</span></span>|
||<span data-ttu-id="e5d2c-390">提供 demonstratable 證據，以從所有採樣的系統元件，將應用程式控制設定為已記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-390">Provide demonstratable evidence that application control is configured as documented from all sampled system components.</span></span>|
|<span data-ttu-id="e5d2c-391">**修補程式管理-風險排名**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-391">**Patch Management - Risk Ranking**</span></span>| <span data-ttu-id="e5d2c-392">提供原則檔，可控制如何識別新的安全性弱點，並指派風險分數。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-392">Supply policy documentation that governs how new security vulnerabilities are identified and assigned a risk score.</span></span>|
||<span data-ttu-id="e5d2c-393">提供如何識別新安全性弱點的證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-393">Provide evidence of how new security vulnerabilities are identified.</span></span>|
||<span data-ttu-id="e5d2c-394">提供證據，表明已發現所有的漏洞都會被指派風險排名。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-394">Provide evidence demonstrating that all vulnerabilities are assigned a risk ranking once identified.</span></span>|
|<span data-ttu-id="e5d2c-395">**修補程式 Managmeent-修補程式**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-395">**Patch Managmeent - Patching**</span></span>|<span data-ttu-id="e5d2c-396">提供原則檔，以修補內建的系統元件，其中包含嚴重、高及中等風險弱點的最小修補期限;和解除委任任何不支援的作業系統和軟體。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-396">Provide policy documentation for patching of in-scope system components that includes suitable minimal patching timeframe for critical, high, and medium risk vulnerabilities; and decommissioning of any unsupported operating systems and software.</span></span>|
||<span data-ttu-id="e5d2c-397">提供 demonstratable 證據，以修補所有抽樣的系統元件。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-397">Provide demonstratable evidence that all sampled system components are being patched.</span></span>|
||<span data-ttu-id="e5d2c-398">提供 demonstratable 證據，使其不會在環境中使用任何不支援的作業系統和軟體元件。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-398">Provide demonstratable evidence that any unsupported operating systems and software components aren't used within the environment.</span></span>|
|<span data-ttu-id="e5d2c-399">**弱點掃描**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-399">**Vulnerability scanning**</span></span>|<span data-ttu-id="e5d2c-400">提供每季基礎結構及 web 應用程式的弱點掃描報告。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-400">Provide the quarterly infrastructure and web application vulnerability scanning reports.</span></span> <span data-ttu-id="e5d2c-401">掃描必須針對整個公開的足跡執行， (IP 位址及 URLs) 和內部 IP 範圍。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-401">Scanning needs to be carried out against the entire public footprint (IP addresses and URLs) and internal IP ranges.</span></span>|
||<span data-ttu-id="e5d2c-402">提供 demonstratable 證據，修復在弱點掃描中識別的漏洞會隨著您已記錄的修補時間範圍進行修補。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-402">Provide demonstratable evidence that remediation of vulnerabilities identified during vulnerability scanning are patched in line with your documented patching timeframe.</span></span>|
|<span data-ttu-id="e5d2c-403">**防火牆**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-403">**Firewalls**</span></span>|<span data-ttu-id="e5d2c-404">提供原則檔，以控制防火牆管理的作法與程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-404">Provide policy documentation that governs firewall management practices and procedures.</span></span>|
||<span data-ttu-id="e5d2c-405">提供顯而易見的證據，指出在安裝至實際執行環境之前，會變更任何預設的系統管理認證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-405">Provide demonstrable evidence that any default administrative credentials are changed prior to installation into production environments.</span></span>|
||<span data-ttu-id="e5d2c-406">提供顯而易見的證據，表明防火牆已安裝在範圍內環境的邊界上，並安裝在周邊網路 (（也稱為 DMZ、隔離區域，以及遮罩式子網) 和內部信任網路）之間。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-406">Provide demonstrable evidence that firewalls are installed on the boundary of the in-scope environment, and installed between the perimeter network (also known as DMZ, demilitarized zone, and screened subnet) and internal trusted networks.</span></span>|
||<span data-ttu-id="e5d2c-407">提供實實在在的證據，所有公開存取均會在隔離區域 (DMZ) 中終止。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-407">Provide demonstrable evidence that all public access terminates in the demilitarized zone (DMZ).</span></span>|
||<span data-ttu-id="e5d2c-408">提供顯而易見的證據，透過防火牆所允許的所有流量都透過核准程式進行處理。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-408">Provide demonstrable evidence that all traffic permitted through the firewall goes through an approval process.</span></span>|
||<span data-ttu-id="e5d2c-409">提供顯而易見的證據，表明防火牆規則基本設定為丟棄未明確定義的流量。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-409">Provide demonstrable evidence that the firewall rule base is configured to drop traffic not explicitly defined.</span></span>|
||<span data-ttu-id="e5d2c-410">提供顯而易見的證據，使防火牆只在所有非主控台管理介面上支援強式密碼編譯。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-410">Provide demonstrable evidence that the firewall supports only strong cryptography on all non-console administrative interfaces.</span></span>|
||<span data-ttu-id="e5d2c-411">提供您執行防火牆規則檢查的 demonstratable 證據，至少每6個月。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-411">Provide demonstratable evidence that you are performing firewall rule reviews at least every 6 months.</span></span>|
|<span data-ttu-id="e5d2c-412">**Web 應用程式防火牆 (WAF)  (選用)**：額外的信用是取得下列控制的滿意。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-412">**Web Application Firewall (WAF) (OPTIONAL)**: Additional credit will be rewarded for satisfying the following controls.</span></span>|<span data-ttu-id="e5d2c-413">提供 demonstratable 證據，供 Web 應用程式防火牆 (WAF) 設定為主動監視、警示及封鎖惡意流量。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-413">Provide demonstratable evidence that the Web Application Firewall (WAF) is configured to actively monitor, alert, and block malicious traffic.</span></span>|
||<span data-ttu-id="e5d2c-414">提供 WAF 支援 SSL 卸載的實實在在證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-414">Provide demonstrable evidence that the WAF supports SSL offloading.</span></span>|
||<span data-ttu-id="e5d2c-415">提供 demonstratable 證據，WAF 會根據 OWASP 核心規則集 (3.0 或3.1 的部分或所有下列類別的漏洞加以保護) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-415">Provide demonstratable evidence that the WAF is protects against some, or all of the following classes of vulnerabilities as per the OWASP Core Rule Set (3.0 or 3.1)</span></span> |
|<span data-ttu-id="e5d2c-416">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-416">**Change Control**</span></span>|<span data-ttu-id="e5d2c-417">提供原則檔，以控制變更控制程式的處理。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-417">Provide policy documentation that governs change control processes.</span></span>|
||<span data-ttu-id="e5d2c-418">提供 demonstratable 證據，以開發和測試環境強制將職責與實際執行環境分開。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-418">Provide demonstratable evidence that development and test environments enforce separation of duties from the production environment.</span></span>|
||<span data-ttu-id="e5d2c-419">提供 demonstratable 證據，使其不會在開發或測試環境中使用敏感的實際執行資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-419">Provide demonstratable evidence that sensitive production data is not used within the development or test environments.</span></span>|
||<span data-ttu-id="e5d2c-420">提供 demonstratable 證據：記錄的變更要求包含變更的影響、後端程式的詳細資料，以及要執行的測試。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-420">Provide demonstratable evidence that documented change requests contain impact of the change, details of back-out procedures and of testing to be carried out.</span></span>|
||<span data-ttu-id="e5d2c-421">提供 demonstratable 證據，以變更要求進行授權和簽收處理常式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-421">Provide demonstratable evidence that change requests undergo an authorization and signoff process.</span></span>|
|<span data-ttu-id="e5d2c-422">**安全的軟體發展/部署**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-422">**Secure Software Development/Deployment**</span></span>| <span data-ttu-id="e5d2c-423">提供支援安全軟體發展及部署的原則和程式，包括針對一般弱點類別（如，OWASP Top 10 或 SANS Top 25 CWE）的安全的編碼最佳作法指導方針。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-423">Provide policies and procedures that support secure software development and deployment, including secure coding best practice guidance against common vulnerability classes such as, OWASP Top 10 or SANS Top 25 CWE.</span></span>|
|| <span data-ttu-id="e5d2c-424">提供 demonstratable 證據，使程式碼變更經過第二個檢閱者的審閱和授權過程。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-424">Provide demonstratable evidence that code changes undergo a review and authorization process by a second reviewer.</span></span>|
|| <span data-ttu-id="e5d2c-425">提供 demonstratable 證據，讓開發人員每年都會進行安全的軟體發展訓練。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-425">Provide demonstratable evidence that developers undergo secure software development training annually.</span></span>|
|| <span data-ttu-id="e5d2c-426">提供 demonstratable 證據，以利用多重要素驗證 (MFA) 來保護代碼存放庫。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-426">Provide demonstratable evidence that code repositories are secured with multi-factor authentication (MFA).</span></span>|
|| <span data-ttu-id="e5d2c-427">提供 demonstratable 證據，以控制存取權以保護程式碼存放庫。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-427">Provide demonstratable evidence that access controls are in place to secure code repositories.</span></span>
|<span data-ttu-id="e5d2c-428">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-428">**Account Management**</span></span>| <span data-ttu-id="e5d2c-429">提供原則檔，以控制帳戶管理的作法與程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-429">Provide policy documentation that governs account management practices and procedures.</span></span>
||<span data-ttu-id="e5d2c-430">提供 demonstratable 證據，表示每個抽樣系統元件上的預設認證為停用、移除或變更。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-430">Provide demonstratable evidence that default credentials are either disabled, removed, or changed across the sampled system components.</span></span>|
||<span data-ttu-id="e5d2c-431">提供 demonstratable 證據，以建立、修改和刪除帳戶所經過的核准程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-431">Provide demonstratable evidence that account creation, modification and deletion goes through an established approval process.</span></span>|
||<span data-ttu-id="e5d2c-432">提供 demonstratable 證據，讓程式可以停用或刪除3個月內未使用的帳戶。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-432">Provide demonstratable evidence that a process is in place to either disable or delete accounts not used within 3 months.</span></span>|
||<span data-ttu-id="e5d2c-433">提供 demonstratable 證據，以加強強式密碼原則或其他適當的緩解，以保護使用者認證的位置。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-433">Provide demonstratable evidence that a strong password policy or other suitable mitigations to protect user credentials are in place.</span></span>  <span data-ttu-id="e5d2c-434">下列專案應該用作基本的指導方針：最低密碼長度8個字元，不超過10次的帳戶鎖定閥值，至少有5個密碼的密碼記錄，強制使用強式密碼</span><span class="sxs-lookup"><span data-stu-id="e5d2c-434">The following should be used as a minimum guideline: minimum password length of 8 character, account lockout threshold of no more than 10 attempts, password history of a minimum of 5 passwords, enforcement of the use of strong password</span></span>|
|<span data-ttu-id="e5d2c-435">**入侵偵測及防護 (選用) ：** 其他信用額將會取得對下列控制措施的滿意</span><span class="sxs-lookup"><span data-stu-id="e5d2c-435">**Intrusion Detection and Prevention (OPTIONAL):** Additional credit will be rewarded for satisfying the following controls</span></span>|<span data-ttu-id="e5d2c-436">提供 demonstratable 證據，使入侵偵測及防護系統 (IDPS) 部署在範圍內的環境周邊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-436">Provide demonstratable evidence that Intrusion Detection and Prevention Systems (IDPS) is deployed at the perimeter of the in-scope environments.</span></span>|
||<span data-ttu-id="e5d2c-437">提供 demonstratable 證據，IDPS 簽章會在24小時內保留目前的 () 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-437">Provide demonstratable evidence that IDPS signatures are kept current (within 24 hours).</span></span>|
||<span data-ttu-id="e5d2c-438">提供 IDPS 設定為支援所有傳入 web 流量之 TLS 檢查的 demonstratable 證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-438">Provide demonstratable evidence that IDPS is configured to support TLS inspection of all incoming web traffic.</span></span>|
||<span data-ttu-id="e5d2c-439">提供 IDPS 所設定的 demonstratable 證據，以監視所有輸入流量流程。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-439">Provide demonstratable evidence that IDPS is configured to monitor all inbound traffic flows.</span></span>|
||<span data-ttu-id="e5d2c-440">提供 IDPS 所設定的 demonstratable 證據，以監視所有輸出流量流程。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-440">Provide demonstratable evidence that IDPS is configured to monitor all outbound traffic flows.</span></span>|
|<span data-ttu-id="e5d2c-441">**安全性事件記錄**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-441">**Security Event Logging**</span></span> |<span data-ttu-id="e5d2c-442">提供原則檔，以取得控制安全性事件記錄的最佳作法與程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-442">Provide policy documentation for best practices and procedures that governs security event logging.</span></span>|
|| <span data-ttu-id="e5d2c-443">提供 demonstratable 證據，顯示在所有抽樣系統元件之間設定安全性事件記錄，以記錄下列事件：使用者對系統元件及應用程式的存取、高許可權使用者採取的所有動作、邏輯存取嘗試失敗的邏輯帳戶建立或修改、事件記錄篡改、停用安全性工具 (例如反惡意軟體或事件記錄) 、反惡意軟體記錄 (（如已設定的更新、惡意程式碼偵測及掃描失敗）。 IDPS 及 WAF 事件（如已設定）) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-443">Provide demonstratable evidence that shows security event logging is set up across all sampled system components to log the following events: User access to system components and the application, All actions taken by a high-privileged user, Invalid logical access attempts Privileged account creation or modification, Event log tampering, Disabling of security tools (such as antimalware or event logging), Antimalware logging (such as updates, malware detection, and scan failures).,IDPS and WAF events, if configured</span></span>|
||<span data-ttu-id="e5d2c-444">提供 demonstratable 證據，記錄的安全性事件包含下列最基本資訊：使用者、事件種類、日期和時間、成功或失敗指示器、識別受影響系統的標籤</span><span class="sxs-lookup"><span data-stu-id="e5d2c-444">Provide demonstratable evidence that logged security events contain the following minimum information: User, Type of event, Date and time, Success or failure indicators, Label that identifies the affected system</span></span>|
||<span data-ttu-id="e5d2c-445">提供 demonstratable 證據，表明所有抽樣系統元件的時間都同步處理至相同的主要和次要伺服器。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-445">Provide demonstratable evidence that all sampled system components are time-synchronized to the same primary and secondary servers.</span></span>|
||<span data-ttu-id="e5d2c-446">當公開的系統正在使用中時，提供 demonstratable 證據，安全性事件記錄會傳送至不在周邊網路中的集中式記錄解決方案。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-446">Provide demonstratable evidence when public facing systems are in use that security event logs are being sent to a centralized logging solution not within the perimeter network.</span></span>|
||<span data-ttu-id="e5d2c-447">提供實實在在的證據，顯示集中式記錄解決方案已受到保護，以防未授權篡改記錄資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-447">Provide demonstrable evidence to show that the centralized logging solution is protected against unauthorized tampering of logging data.</span></span>|
||<span data-ttu-id="e5d2c-448">提供顯而易見的證據，可立即使用30天的安全性事件記錄資料，並保留90天的安全性事件記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-448">Provide demonstrable evidence that a minimum of 30 days of security event logging data is immediately available, with 90 days of security event logs being retained.</span></span>|
|<span data-ttu-id="e5d2c-449">**檢查 (記錄檔資料)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-449">**Reviewing (Log Data)**</span></span> |<span data-ttu-id="e5d2c-450">提供原則檔，以控制記錄檢查的做法和程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-450">Provide policy documentation that governs log review practices and procedures.</span></span>|
||<span data-ttu-id="e5d2c-451">提供顯而易見的證據：人工或自動化的工具會每日逐項檢查記錄，以識別可能的安全性事件。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-451">Provide demonstrable evidence that logs are reviewed on a daily basis by a human or automated tooling to identify potential security events.</span></span>|
||<span data-ttu-id="e5d2c-452">提供顯而易見的證據，表明可能的安全性事件和異常已調查並修正。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-452">Provide demonstrable evidence that potential security events and anomalies are investigated and remediated.</span></span>|
|<span data-ttu-id="e5d2c-453">**提醒**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-453">**Alerting**</span></span> | <span data-ttu-id="e5d2c-454">提供原則檔，以控制安全性事件警示的作法與程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-454">Provide policy documentation that governs security event alerting practices and procedures.</span></span>|
|| <span data-ttu-id="e5d2c-455">提供顯而易見的證據：針對下列類型的安全性事件，立即會審會觸發警示：特權帳戶建立或修改、病毒或惡意程式碼事件、事件記錄篡改、IDPS 或 WAF 事件</span><span class="sxs-lookup"><span data-stu-id="e5d2c-455">Provide demonstrable evidence that alerts are triggered for immediate triage for the following types of security events: Privileged account creation or modifications, Virus or malware events, Event log tampering, IDPS or WAF events</span></span>
|<span data-ttu-id="e5d2c-456">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-456">**Risk management**</span></span>|<span data-ttu-id="e5d2c-457">提供 demonstratable 證據，以建立正式的資訊安全性風險管理流程。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-457">Provide demonstratable evidence that a formal information security risk management process is established.</span></span>|
||<span data-ttu-id="e5d2c-458">提供實實在在的風險評估，至少每一年都會以最低的證據進行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-458">Provide demonstrable evidence that a formal risk assessment occurs annually, at a minimum.</span></span>|
||<span data-ttu-id="e5d2c-459">提供實實在在的證據，指出資訊安全風險評估包含威脅、弱點或對等專案。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-459">Provide demonstrable evidence that the information security risk assessment includes threats, vulnerabilities, or the equivalent.</span></span>|
||<span data-ttu-id="e5d2c-460">提供實實在在的證據，指出資訊安全風險評估包含影響、可能性風險矩陣或對等專案。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-460">Provide demonstrable evidence that the information security  risk assessment includes impact, likelihood risk matrix, or the equivalent.</span></span>|
||<span data-ttu-id="e5d2c-461">提供顯而易見的證據，指出資訊安全風險評估包含風險註冊與治療計畫。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-461">Provide demonstrable evidence that the information security risk assessment includes a risk register and treatment plan.</span></span>|
|<span data-ttu-id="e5d2c-462">**事件回應**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-462">**Incident response**</span></span>|<span data-ttu-id="e5d2c-463">提供安全事件回應計畫 (IRP) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-463">Provide the security incident response plan (IRP).</span></span>|
||<span data-ttu-id="e5d2c-464">提供顯而易見的證據，安全性 IRP 包含已記錄的通訊程式，可確保重要專案關係人及時獲得通知，例如付款商標和 acquirers、法規內文、主管機構、director 及客戶。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-464">Provide demonstrable evidence that the security IRP includes a documented communication process to ensure timely notification to key stakeholders, such as payment brands and acquirers, regulatory bodies, supervisory authorities, directors, and customers.</span></span>|
||<span data-ttu-id="e5d2c-465">提供顯而易見的證據，表明事件回應小組的所有成員都已完成每年訓練或表格主要練習。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-465">Provide demonstrable evidence that all member of the incident response team have completed annual training or a table top exercise.</span></span>|
||<span data-ttu-id="e5d2c-466">提供實實在在的證據，顯示安全性 IRP 會根據所學的教訓或組織變更進行更新。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-466">Provide demonstrable evidence to show the security IRP is updated based on lessons learned or organizational changes.</span></span>|

## <a name="data-handling-security-and-privacy"></a><span data-ttu-id="e5d2c-467">資料處理安全性和隱私權</span><span class="sxs-lookup"><span data-stu-id="e5d2c-467">Data Handling Security and Privacy</span></span>

<span data-ttu-id="e5d2c-468">在應用程式使用者、仲介服務和 ISV 系統之間傳輸的資料，必須透過支援最低 TLS 1.1 的 TLS 連線來保護。*請參閱*[**附錄 A**](#appendix-a)。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-468">Data in transit between the application user, intermediary services, and ISV’s systems will be required to be protected by encryption through a TLS connection supporting a minimum of TLS v1.1.*See* [**Appendix A**](#appendix-a).</span></span>

<span data-ttu-id="e5d2c-469">您的應用程式會在其中檢索及儲存 M365 資料，您必須依照 [**附錄 B**](#appendix-a)中所定義的規格來執行資料儲存加密配置。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-469">Where your application retrieves and stores M365 data you will be required to implement a data storage encryption scheme that follows the specification as defined in [**Appendix B**](#appendix-a).</span></span>

### <a name="controls"></a><span data-ttu-id="e5d2c-470">控制措施</span><span class="sxs-lookup"><span data-stu-id="e5d2c-470">Controls</span></span>

|<span data-ttu-id="e5d2c-471">**控制系列**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-471">**Control Family**</span></span>| <span data-ttu-id="e5d2c-472">**Controls**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-472">**Controls**</span></span> |
| -----------------------|-------------------------------- |
|<span data-ttu-id="e5d2c-473">**傳輸中的資料**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-473">**Data in Transit**</span></span>| <span data-ttu-id="e5d2c-474">提供 TLS 設定符合或超過[tls 設定檔設定需求](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#appendix-a)內之加密需求的 demonstratable 證據</span><span class="sxs-lookup"><span data-stu-id="e5d2c-474">Provide demonstratable evidence that TLS configuration meets or exceeds the encryption requirements within the [TLS profile configuration requirements](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#appendix-a)</span></span>|
||<span data-ttu-id="e5d2c-475">提供 demonstratable 證據，以在所有用來處理 web 要求的公開服務間停用 TLS 壓縮。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-475">Provide demonstratable evidence that TLS compression is disabled across all public-facing services that handle web requests.</span></span>|
||<span data-ttu-id="e5d2c-476">提供 demonstratable 證據，以在所有網站上啟用 TLS HTTP 嚴格傳輸安全性並設定為 >= 15552000。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-476">Provide demonstratable evidence that TLS HTTP strict transport security is enabled and configured to >= 15552000 across all sites.</span></span>|
|<span data-ttu-id="e5d2c-477">**靜態資料**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-477">**Data at Rest**</span></span>| <span data-ttu-id="e5d2c-478">提供 demonstratable 證據：靜態的資料會以加密設定檔需求進行內嵌加密，例如，使用 AES、Blowfish、TDES 和加密金鑰大小的128位和256位等加密演算法。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-478">Provide demonstratable evidence that data at rest is encrypted inline with the encryption profile requirements, using encryption algorithms such as AES, Blowfish, TDES and encryption key sizes of 128-bit, and 256-bit.</span></span>|
||<span data-ttu-id="e5d2c-479">提供 demonstratable 證據，讓雜湊函數或郵件驗證 (HMAC SHA1) 只用于保護靜態內嵌的資料與加密設定檔需求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-479">Provide demonstratable evidence that hash function or message authentication (HMAC-SHA1) is only used to protect data at rest inline with encryption profile requirements.</span></span>|
||<span data-ttu-id="e5d2c-480">提供庫存以顯示所有儲存的資料，包括用來保護資料的儲存位置和加密。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-480">Provide an inventory showing all stored data, including storage location and encryption used to protect the data.</span></span>|
|<span data-ttu-id="e5d2c-481">**資料保留與處置**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-481">**Data Retention and Disposal**</span></span>|<span data-ttu-id="e5d2c-482">提供 demonstratable 證據，以正式建立已核准和記錄的資料保留期間。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-482">Provide demonstratable evidence that an approved and documented data retention period is formally established.</span></span>|
||<span data-ttu-id="e5d2c-483">提供 demonstratable 證據，保留的資料符合定義的保留期間。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-483">Provide demonstratable evidence that retained data matches defined retention period.</span></span>|
||<span data-ttu-id="e5d2c-484">提供 demonstratable 證據，以進行處理以安全地刪除保留期間內的資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-484">Provide demonstratable evidence that processes are in place to securely delete data after its retention period.</span></span>|
|<span data-ttu-id="e5d2c-485">**資料存取管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-485">**Data Access Management**</span></span>|<span data-ttu-id="e5d2c-486">提供可存取資料或加密金鑰（包括業務理由）的所有個人清單。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-486">Provide a list of all individuals with access to data or encryption keys, including the business justification.</span></span>|
||<span data-ttu-id="e5d2c-487">提供 demonstratable 證據，讓具有資料或加密金鑰存取權的人員獲得正式核准，以詳述其工作職能所需的許可權。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-487">Provide demonstratable evidence that the sampled individuals who have access to data or encryption keys were formally approved, detailing privileges required for their job function.</span></span>|
||<span data-ttu-id="e5d2c-488">提供 demonstratable 證據，讓具有資料或加密金鑰存取權的使用者，只具備核准中包含的許可權。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-488">Provide demonstratable evidence that the sampled individuals who have access to data or encryption keys only have the privileges included in the approval.</span></span>|
||<span data-ttu-id="e5d2c-489">提供客戶資料共用所在的所有協力廠商清單。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-489">Provide a list of all third-parties that customer data is shared with.</span></span>|
||<span data-ttu-id="e5d2c-490">提供 demonstratable 證據，讓所有協力廠商消耗的客戶資料都有共用協定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-490">Provide demonstratable evidence that all third-parties consuming customer data have sharing agreements in place.</span></span>|
|<span data-ttu-id="e5d2c-491">**GDPR** (（如果適用）) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-491">**GDPR** (If Applicable)</span></span>| <span data-ttu-id="e5d2c-492">提供已記錄的主體存取要求 (SAR) 處理常式，並提供證據，證明資料主體能夠提出 SARs。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-492">Provide a documented subject access request (SAR) process and provide evidence demonstrating that data subjects are able to raise SARs.</span></span>|
||<span data-ttu-id="e5d2c-493">提供 demonstratable 證據，您可以在回應 SAR 時，識別資料主體之資料的所有位置。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-493">Provide demonstratable evidence that you are able to identify all locations of data subjects' data when responding to a SAR.</span></span>|
||<span data-ttu-id="e5d2c-494">您維護的隱私權應包含公司詳細資料 (名稱、位址等。) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-494">You maintain a privacy notice which should contain the companies details (Name, Address, etc..).</span></span>|
||<span data-ttu-id="e5d2c-495">您應維護隱私權通知，以說明所處理的個人資料類型。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-495">You maintain a privacy notice which should explain the types of personal data being processed.</span></span>|
||<span data-ttu-id="e5d2c-496">您應維護隱私權通知，以解釋處理個人資料的 lawfulness。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-496">You maintain a privacy notice which should explain the lawfulness of processing personal data</span></span>|
||<span data-ttu-id="e5d2c-497">您會維護隱私權通知，以詳細說明資料主體的許可權：向右瞭解資料主體的許可權、存取權、存取權，以及限制處理的權利、限制處理的權利、資料可攜性、正確地進行決策的權利，包括分析。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-497">You maintain a privacy notice which explains in details the data subject's rights: Right to be informed, Right of access by the data subject, Right to erasure, Right to restriction of processing, Right to data portability, Right to object, Rights in relation to automated decision-making, including profiling.</span></span>|
|| <span data-ttu-id="e5d2c-498">您會維護隱私權通知，以說明保留個人資料的時間。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-498">You maintain a privacy notice which should explain how long personal data will be kept for.</span></span>|

## <a name="optional-external-compliance-frameworks-review"></a><span data-ttu-id="e5d2c-499">選用的外部規範框架審查</span><span class="sxs-lookup"><span data-stu-id="e5d2c-499">Optional External Compliance Frameworks Review</span></span>

<span data-ttu-id="e5d2c-500">雖然這不是必要的，但如果您目前正遵循 ISO 27001、PCI DSS 或 SOC2，您可以選擇使用這些憑證來滿足某些 Microsoft 365 的證書控制。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-500">Although it is not required, if you are currently in compliance with ISO 27001, PCI DSS, or SOC2, you can elect to use these certifications to satisfy some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="e5d2c-501">憑證分析員會嘗試將現有的外部安全性框架與 Microsoft 365 的憑證規格對齊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-501">Certification analysts will try to align existing external security frameworks to the Microsoft 365 Certification specification.</span></span> <span data-ttu-id="e5d2c-502">不過，如果支援檔無法保證評估的 Microsoft 365 認證控制項已評估為外部安全性框架的一部分審核/評估，您將需要提供目前所說的控制項的額外證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-502">However, if supporting documentation is unable to provide assurance that Microsoft 365 Certification controls were assessed as part of the external security frameworks audit/assessment you will need to provide additional evidence of the said controls being in place.</span></span>

<span data-ttu-id="e5d2c-503">檔必須充分示範 Microsoft 365 憑證的範圍內環境會包含在這些外部安全性框架的範圍內。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-503">Documentation must adequately demonstrate that the in-scope environment for the Microsoft 365 Certification was included within the scope of these external security frameworks.</span></span> <span data-ttu-id="e5d2c-504">透過接受由著名的外部協力廠商公司所執行的有效憑證證據，便可驗證這些安全性框架。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-504">Validation of these security frameworks will be fulfilled by accepting evidence of valid certifications conducted by reputable external third-party companies.</span></span> <span data-ttu-id="e5d2c-505">這些著名的公司必須是相關規範計畫的國際資格鑒定主體的成員。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-505">These reputable companies must be members of international accreditation bodies for relevant compliance programs.</span></span> <span data-ttu-id="e5d2c-506">請參閱 iso 27001 和合格的安全性評估者的 ISO 憑證和合規性標準。) PCI DSS 的 (QSA。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-506">See ISO Certification and Conformity Standards for ISO 27001 and Qualified Security Assessors (QSA) for PCI DSS.</span></span>

<span data-ttu-id="e5d2c-507">下表著重于此驗證程式的一部分，強調認證分析員所需的外部框架和檔：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-507">The following table highlights the external frameworks and documentation required by certification analysts as part of this validation process:</span></span>

| <span data-ttu-id="e5d2c-508">**Standard**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-508">**Standard**</span></span> | <span data-ttu-id="e5d2c-509">**需求**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-509">**Requirements**</span></span> |
| ----- | ----- |
| <span data-ttu-id="e5d2c-510">**[ISO 27001](#iso-27001)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-510">**[ISO 27001](#iso-27001)**</span></span> | <span data-ttu-id="e5d2c-511"> (SOA) 且所發出的 ISO 27001 憑證複本是 **公開的公開** 版本。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-511">A public facing version of the **Statement of Applicability** (SOA) and a copy of the ISO 27001 certificate issued will be required.</span></span>  <span data-ttu-id="e5d2c-512">SOA 會摘要您在每個114資訊安全性控制上的位置，並將用來識別 ISO 27001 憑證中的任何不滿意的控制項排除。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-512">The SOA summarizes your position on each of the 114 information security controls and  will be used to identify if any exclusion of controls that are not satisfactorily detailed in the ISO 27001 certificate.</span></span> <span data-ttu-id="e5d2c-513">如果不能透過檢查 SOA 的公開版本來判斷這種情況，當 ISO 27001 將用來驗證某些 Microsoft 365 的憑證規格控制時，分析員可能需要存取完整的 soa。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-513">If this can't be determined by reviewing the public facing version of the SOA, the analyst might need access to the full SOA if ISO 27001 will be used to validate some of the Microsoft 365 Certification Specification controls.</span></span>  <span data-ttu-id="e5d2c-514">除了驗證 ISO 27001 評估活動的範圍之外，分析員也會依照上述所述，確認審計公司的合法性。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-514">In addition to validating the scope of the ISO 27001 assessment activities, the analysts will also confirm the validity of the audit company as described above.</span></span>|
|<span data-ttu-id="e5d2c-515">**[PCI DSS](#pci-dss)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-515">**[PCI DSS](#pci-dss)**</span></span>| <span data-ttu-id="e5d2c-516">必須提供有效 **的等級1證明規範** (AOC) 檔，才能明確識別範圍內的應用程式和系統元件。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-516">A valid **Level 1 Attestation of Compliance** (AOC) document must be provided clearly identifying the in-scope application and system components.</span></span>  <span data-ttu-id="e5d2c-517">「自我評估 AOC」 **不** 會接受為會議安全性最佳作法的證據。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-517">A self-assessment AOC **will not** be accepted as evidence of meeting security best practices.</span></span> <span data-ttu-id="e5d2c-518">AOC 將用來判斷哪個 Microsoft 365 憑證規格控制已評估並確認為 PCI DSS 評估的一部分。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-518">The AOC will be used to determine which of the Microsoft 365 Certification Specification controls have been evaluated and confirmed as part of the PCI DSS assessment.</span></span>|
|<span data-ttu-id="e5d2c-519">**[SOC 2](#soc-2)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-519">**[SOC 2](#soc-2)**</span></span>|<span data-ttu-id="e5d2c-520">**SOC 2 (Type I 或 type II)** report 必須是目前 (于過去15個月內發行的時間，以及最近27個月內所宣告的時間週期) ，以當作此 Microsoft 365 憑證規格內任何評估控制項使用的符合性。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-520">The **SOC 2 (Type I or Type II)** report must be current (issued within the last 15 months and the declared time period started within the last 27 months) to be used as evidence of conformity with any of the assessment controls within this Microsoft 365 Certification Specification.</span></span>|

<span data-ttu-id="e5d2c-521">如果外部安全性框架已包含在 Publisher 認證中，則認證分析人員必須在 Microsoft 365 認證評估中檢查這些安全性合規性框架是否有效。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-521">If external security frameworks have been included within the Publisher Attestation, certification analysts will need to check the validity of those security compliance frameworks as part of the Microsoft 365 Certification assessment.</span></span>

|<span data-ttu-id="e5d2c-522">**框架**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-522">**Framework**</span></span> | <span data-ttu-id="e5d2c-523">**其他考量**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-523">**Additional considerations**</span></span> |
|-------------- | --------------------|
|<span data-ttu-id="e5d2c-524">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="e5d2c-524">ISO 27001</span></span>| <span data-ttu-id="e5d2c-525">[**附錄 C**](#appendix-c)：證據集合– ISO 27001 的增量。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-525">[**Appendix C**](#appendix-c): Evidence Collection – Deltas for ISO 27001.</span></span>|
|<span data-ttu-id="e5d2c-526">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="e5d2c-526">PCI DSS</span></span> | <span data-ttu-id="e5d2c-527">[**附錄 D**](#appendix-d)：證據集合– PCI DSS 的增量。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-527">[**Appendix D**](#appendix-d): Evidence Collection – Deltas for PCI DSS.</span></span>|
|<span data-ttu-id="e5d2c-528">SOC 2</span><span class="sxs-lookup"><span data-stu-id="e5d2c-528">SOC 2</span></span>| <span data-ttu-id="e5d2c-529">[**附錄 E**](#appendix-e)： SOC 2 的證據集合–增量。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-529">[**Appendix E**](#appendix-e): Evidence Collection – Deltas for SOC 2.</span></span>|

> [!NOTE]
> <span data-ttu-id="e5d2c-530">雖然上述的外部安全性標準/框架可以提交為證據，以符合部分 Microsoft 365 的憑證控制，但傳遞 Microsoft 365 認證並不表示您會成功地透過這些標準/框架進行審核。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-530">Although the above-mentioned external security standards/frameworks can be submitted as evidence to meet some of the Microsoft 365 Certification controls, passing the Microsoft 365 Certification doesn't mean that you will successfully pass an audit against those standards/frameworks.</span></span> <span data-ttu-id="e5d2c-531">Microsoft 365 憑證規格只是那些安全標準/框架的小型子集，可讓 Microsoft 取得安全性狀況的保證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-531">The Microsoft 365 Certification Specification is only a small subset of those security standards/frameworks that allows Microsoft to gain a level of assurance in reference to your security posture.</span></span>


### <a name="requirements-to-use-external-compliance-frameworks"></a><span data-ttu-id="e5d2c-532">使用外部規範框架的需求</span><span class="sxs-lookup"><span data-stu-id="e5d2c-532">Requirements to use external compliance frameworks</span></span>

<span data-ttu-id="e5d2c-533">&#x2713; 應用程式/增益集支援環境 **和** 任何支援的商務程式都 **必須** 包含在任何支援的外部安全性合規性框架範圍內，且必須在提供的檔中明確指出。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-533">&#x2713; The App/Add-in supporting environment **AND** any supporting business processes **MUST** be included within the scope of any supported external security compliance frameworks and must be clearly indicated in supplied documentation.</span></span>

<span data-ttu-id="e5d2c-534">&#x2713; 支援的外部安全性合規性框架 **必須** 是最新的，亦即在過去的12個月內 (或在15months 中（如果重新評估目前正在進行中），而且可提供證據) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-534">&#x2713; Supported external security compliance frameworks **MUST** be current, i.e. within the past 12 months (or within 15months if the re-assessment is currently being carried out and evidence can be provided).</span></span>

<span data-ttu-id="e5d2c-535">&#x2713; 支援的外部安全性合規性框架 **必須** 由獨立于資格鑒定的公司執行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-535">&#x2713; Supported external security compliance frameworks **MUST** be carried out by an independent accredited company.</span></span>

## <a name="appendix-a"></a><span data-ttu-id="e5d2c-536">附錄 A</span><span class="sxs-lookup"><span data-stu-id="e5d2c-536">Appendix A</span></span>

### <a name="tls-profile-configuration-requirements"></a><span data-ttu-id="e5d2c-537">TLS 設定檔設定需求</span><span class="sxs-lookup"><span data-stu-id="e5d2c-537">TLS Profile configuration requirements</span></span>

<span data-ttu-id="e5d2c-538">所有網路流量（不論是在虛擬網路、雲端服務或資料中心內）都必須受到至少 TLS 1.1 版的保護， (TLS 1.2 \* 為建議) 或其他適用的通訊協定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-538">All network traffic, whether within a virtual network, cloud service, or a data center, must be protected with a minimum of TLS v1.1 (TLS v1.2+ is recommended) or other applicable protocol.</span></span> <span data-ttu-id="e5d2c-539">此要求的例外狀況如下：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-539">Exceptions to this requirement are:</span></span>

* <span data-ttu-id="e5d2c-540">**HTTP 對 HTTPS 重新導向**。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-540">**HTTP-to-HTTPS redirect**.</span></span> <span data-ttu-id="e5d2c-541">您的應用程式可以透過 HTTP 回應，將用戶端重新導向至 HTTPS，但回應不能包含任何機密資料 (cookie、標頭、內容) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-541">Your app can respond over HTTP to redirect clients to HTTPS, but the response must not contain any sensitive data (cookies, headers, content).</span></span> <span data-ttu-id="e5d2c-542">允許除重新導向 HTTPS 和回應健康情況探查以外的其他 HTTP 回應。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-542">No other HTTP responses other than redirects to HTTPS and responding to health probes are allowed.</span></span> <span data-ttu-id="e5d2c-543">請參閱下列。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-543">See below.</span></span>
* <span data-ttu-id="e5d2c-544">**狀況探查**。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-544">**Health probes**.</span></span> <span data-ttu-id="e5d2c-545">**只有當** 檢查者不支援 HTTPS 狀況探查時，您的應用程式才可以透過 HTTP 回應健康情況探查。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-545">Your app can respond to health probes over HTTP **only if** HTTPS health probes are not supported by the checking party.</span></span>
* <span data-ttu-id="e5d2c-546">**憑證存取**。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-546">**Certificate access**.</span></span> <span data-ttu-id="e5d2c-547">您可以存取 CRL、OCSP 和 AIA 端點，以取得憑證驗證和吊銷檢查的目的，可透過 HTTP 進行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-547">Access to CRL, OCSP, and AIA endpoints for the purposes of certificate validation and revocation checking is allowed over HTTP.</span></span>
* <span data-ttu-id="e5d2c-548">**本機通訊**。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-548">**Local communications**.</span></span> <span data-ttu-id="e5d2c-549">您的應用程式可以使用 HTTP (或其他非受保護的通訊協定) ，以進行未留下作業系統的通訊（e）。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-549">Your app can use HTTP (or other non-protected protocols) for communications that do not leave the operating system, e.</span></span> <span data-ttu-id="e5d2c-550">g.</span><span class="sxs-lookup"><span data-stu-id="e5d2c-550">g.</span></span> <span data-ttu-id="e5d2c-551">連接到在 localhost 上公開的網頁伺服器端點。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-551">connecting to a web server endpoint exposed on localhost.</span></span>

<span data-ttu-id="e5d2c-552">**必須** 停用 TLS 壓縮。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-552">TLS Compression **MUST** be disabled.</span></span>

## <a name="appendix-b"></a><span data-ttu-id="e5d2c-553">附錄 B</span><span class="sxs-lookup"><span data-stu-id="e5d2c-553">Appendix B</span></span>

### <a name="encryption-profile-configuration-requirements"></a><span data-ttu-id="e5d2c-554">加密設定檔設定需求</span><span class="sxs-lookup"><span data-stu-id="e5d2c-554">Encryption Profile Configuration Requirements</span></span>

<span data-ttu-id="e5d2c-555">只允許加密的基元和參數，如下所示：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-555">Only cryptographic primitives and parameters are permitted as follows:</span></span>

### <a name="symmetric-cryptography"></a><span data-ttu-id="e5d2c-556">對稱密碼編譯</span><span class="sxs-lookup"><span data-stu-id="e5d2c-556">Symmetric cryptography</span></span>

<span data-ttu-id="e5d2c-557">**加密**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-557">**Encryption**</span></span>

<span data-ttu-id="e5d2c-558">&emsp;&#x2713; 只允許 AES、BitLocker、Blowfish 或 TDES。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-558">&emsp;&#x2713; Only AES, BitLocker, Blowfish or TDES are allowed.</span></span> <span data-ttu-id="e5d2c-559">任何支援的金鑰長度 >= 128 允許 (128、192及 256 bits) 而且可用於 256 () 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-559">Any of the supported key lengths >=128 are allowed (128, 192, and 256 bits) and may be used (256-bit keys are recommended).</span></span>

<span data-ttu-id="e5d2c-560">&emsp; 僅允許&#x2713; CBC 模式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-560">&emsp;&#x2713; Only CBC mode is allowed.</span></span> <span data-ttu-id="e5d2c-561">每個加密作業都必須使用全新的、隨機產生的初始化向量 (IV) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-561">Every encryption operation must use a fresh, randomly generated initialization vector (IV).</span></span>

<span data-ttu-id="e5d2c-562">&emsp;**不** 允許使用 stream 密碼的&#x2713; （例如 RC4）。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-562">&emsp;&#x2713; Use of stream ciphers, such as RC4, **IS NOT** allowed.</span></span>

<span data-ttu-id="e5d2c-563">**雜湊函數**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-563">**Hash functions**</span></span>

<span data-ttu-id="e5d2c-564">&emsp;&#x2713; 所有新的程式碼都必須使用 SHA-256、SHA-1-384 或 512 SHA-1 (共同稱為 SHA-2) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-564">&emsp;&#x2713; All new code must use SHA-256, SHA-384, or SHA-512 (collectively referred to as SHA-2).</span></span> <span data-ttu-id="e5d2c-565">輸出可能會被截斷為小於128位數</span><span class="sxs-lookup"><span data-stu-id="e5d2c-565">Output may be truncated to no less than 128 bits</span></span>

<span data-ttu-id="e5d2c-566">&emsp;&#x2713; SHA-1 只能用於相容性的考慮。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-566">&emsp;&#x2713; SHA-1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="e5d2c-567">&emsp; 不允許&#x2713; 使用 MD5、MD4、MD2 及其他雜湊函數，即使是非加密應用程式也是一樣。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-567">&emsp;&#x2713; Use of MD5, MD4, MD2 and other hash functions IS NOT allowed, even for non-cryptographic applications.</span></span>

<span data-ttu-id="e5d2c-568">**郵件驗證**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-568">**Message authentication**</span></span>

<span data-ttu-id="e5d2c-569">&emsp;&#x2713; 所有新的程式碼都必須使用 HMAC 與其中一個已核准的雜湊函數。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-569">&emsp;&#x2713; All new code MUST use HMAC with one of the approved hash functions.</span></span> <span data-ttu-id="e5d2c-570">HMAC 的輸出可能會截斷成小於128位。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-570">Output of HMAC may be truncated to no less than 128 bits.</span></span>

<span data-ttu-id="e5d2c-571">&emsp;&#x2713; HMAC SHA1 只能用於相容性原因。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-571">&emsp;&#x2713; HMAC-SHA1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="e5d2c-572">&emsp;&#x2713; HMAC 機碼至少必須是128位。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-572">&emsp;&#x2713; HMAC key MUST be at least 128 bits.</span></span> <span data-ttu-id="e5d2c-573">建議使用256位金鑰。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-573">256-bit keys are recommended.</span></span>

### <a name="asymmetric-algorithms"></a><span data-ttu-id="e5d2c-574">非對稱演算法</span><span class="sxs-lookup"><span data-stu-id="e5d2c-574">Asymmetric algorithms</span></span>

<span data-ttu-id="e5d2c-575">**加密**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-575">**Encryption**</span></span>

<span data-ttu-id="e5d2c-576">&emsp; 允許&#x2713; RSA。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-576">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="e5d2c-577">索引鍵 **必須** 至少要有2048位，且必須使用 OAEP 襯距。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-577">Key **MUST** be at least 2048 bits and OAEP padding must be used.</span></span> <span data-ttu-id="e5d2c-578">僅允許對相容性原因使用 PKCS 填充。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-578">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="e5d2c-579">**簽章**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-579">**Signatures**</span></span>

<span data-ttu-id="e5d2c-580">&emsp; 允許&#x2713; RSA。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-580">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="e5d2c-581">機碼 **必須** 至少要有2048位，且必須使用 PSS 的襯距。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-581">Key **MUST** be at least 2048 bits and PSS padding must be used.</span></span> <span data-ttu-id="e5d2c-582">僅允許對相容性原因使用 PKCS 填充。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-582">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="e5d2c-583">&emsp; 允許&#x2713;ECDSA。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-583">&emsp;&#x2713;ECDSA is allowed.</span></span> <span data-ttu-id="e5d2c-584">機碼 **必須** 至少是256位。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-584">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="e5d2c-585">必須使用 NIST P-256、P-384 或 P-521 曲線。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-585">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="e5d2c-586">**機碼 Exchange**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-586">**Key Exchange**</span></span>

<span data-ttu-id="e5d2c-587">&emsp; 允許&#x2713; ECDH。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-587">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="e5d2c-588">機碼 **必須** 至少是256位。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-588">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="e5d2c-589">必須使用 NIST P-256、P-384 或 P-521 曲線。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-589">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="e5d2c-590">&emsp; 允許&#x2713; ECDH。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-590">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="e5d2c-591">機碼 **必須** 至少是256位。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-591">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="e5d2c-592">必須使用 NIST P-256、P-384 或 P-521 曲線。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-592">NIST P-256, P-384 or P-521 curve must be used.</span></span>

## <a name="appendix-c"></a><span data-ttu-id="e5d2c-593">附錄 C</span><span class="sxs-lookup"><span data-stu-id="e5d2c-593">Appendix C</span></span>

### <a name="evidence-collection--delta-for-iso-27001"></a><span data-ttu-id="e5d2c-594">證據收集– ISO 27001 的 Delta</span><span class="sxs-lookup"><span data-stu-id="e5d2c-594">Evidence Collection – Delta for ISO 27001</span></span>

<span data-ttu-id="e5d2c-595">在您已獲得 ISO27001 合規性的情況下，下列 delta (間距) 並未全部在 ISO 27001 中涵蓋，至少需要在此 Microsoft 365 認證中查看。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-595">Where you have already attained ISO27001 compliance, the following delta’s (gaps) not wholly covered by ISO 27001 will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="e5d2c-596">在您的 Microsoft 365 認證評估中，認證分析員會判斷是否有任何對應的 iso 27001 控制項未納入 iso 27001 評估中，也可能會決定要包含的控制項範例，以提供進一步的保證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-596">As part of your Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped ISO 27001 controls were not included as part of the ISO 27001 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="e5d2c-597">ISO 27001 缺少的任何需求，都必須包含在您的 Microsoft 365 認證評估活動中。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-597">Any requirements missing from the ISO 27001 will need to be included within your Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="e5d2c-598">**惡意程式碼防護–反病毒**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-598">**Malware Protection – Anti Virus**</span></span>

<span data-ttu-id="e5d2c-599">如果惡意程式碼保護是使用應用程式控制，且在 ISO 27001 內 attested，則不需要進一步調查。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-599">If malware protection is in place using application control and is attested to within ISO 27001 Report no further investigation is necessary.</span></span> <span data-ttu-id="e5d2c-600">如果沒有任何應用程式控制，認證分析程式將需要識別並評估應用程式控制機制的證據，以防止在環境內引爆惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-600">If no application control is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="e5d2c-601">這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-601">This will require you to:</span></span>

* <span data-ttu-id="e5d2c-602">示範防毒軟體是在所有抽樣的系統元件上執行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-602">Demonstrate that anti-virus software is running across all sampled system components.</span></span>

* <span data-ttu-id="e5d2c-603">示範如何在所有抽樣系統元件上設定防病毒，以自動封鎖惡意程式碼，隔離 & 警示或警示。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-603">Demonstrate that anti-virus is configured across all sampled system components to either automatically block malware, to quarantine & alert or to alert.</span></span>

* <span data-ttu-id="e5d2c-604">防毒軟體 **必須** 設定為記錄所有活動。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-604">Anti-virus software **MUST** be configured to log all activities.</span></span>

<span data-ttu-id="e5d2c-605">**修補程式管理–修補程式**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-605">**Patch Management – Patching**</span></span>

<span data-ttu-id="e5d2c-606">因為 ISO 27001 審計並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-606">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-607">不支援廠商的軟體元件和作業系統， **不得** 在環境內使用。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-607">Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="e5d2c-608">支援的原則必須已到位，以確保從環境中移除不受支援的軟體元件/作業系統，以及識別何時必須使用軟體元件的處理常式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-608">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place</span></span>

<span data-ttu-id="e5d2c-609">**弱點掃描**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-609">**Vulnerability Scanning**</span></span>  

<span data-ttu-id="e5d2c-610">因為 ISO 27001 審計並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-610">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-611">示範執行每季內部及外部漏洞掃描的情況。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-611">Demonstrate that quarterly internal and external vulnerability scanning is conducted.</span></span>

* <span data-ttu-id="e5d2c-612">確認支援檔根據風險排名及符合下列專案的規格，針對弱點修正進行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-612">Confirm supporting documentation is in place for vulnerability remediation based on risk ranking and in line with the specification as follows:</span></span>
 
 <span data-ttu-id="e5d2c-613">&#x2713; 以內部掃描的風險排名，線上修正所有重要及 Highs 風險問題。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-613">&#x2713; Fix all Critical and Highs risk issues in-line with the risk ranking for Internal scanning.</span></span>
 
 <span data-ttu-id="e5d2c-614">&#x2713; 針對外部掃描的風險排名，修正所有重要、Highs 及中型風險的問題。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-614">&#x2713; Fix all Critical, Highs and Medium risk issues in-line with the risk ranking for external scanning.</span></span>
 
 <span data-ttu-id="e5d2c-615">&#x2713; 示範修復會以已記載的漏洞修正原則進行線上。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-615">&#x2713; Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="e5d2c-616">**防火牆–防火牆 (或同等技術)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-616">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="e5d2c-617">因為 ISO 27001 審計並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-617">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-618">示範防火牆是安裝在範圍內環境的邊界上。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-618">Demonstrate that firewalls are installed on the boundary of the in-scope environment.</span></span>

* <span data-ttu-id="e5d2c-619">示範如何在 DMZ 和信任的網路之間安裝防火牆。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-619">Demonstrate that firewalls are installed between the DMZ and trusted networks.</span></span>

*   <span data-ttu-id="e5d2c-620">示範所有公用存取會在 DMZ 中終止。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-620">Demonstrate that all public access terminates in the DMZ.</span></span>

*   <span data-ttu-id="e5d2c-621">示範在安裝到 live 環境之前，會變更預設的系統管理認證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-621">Demonstrate that default administrative credentials are changed prior to installation into the live environment.</span></span>

*   <span data-ttu-id="e5d2c-622">示範透過防火牆 (s) 所允許的所有流量，都是透過授權程式來進行，以取得業務理由的所有流量的檔。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-622">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

*   <span data-ttu-id="e5d2c-623">示範所有防火牆皆已設定為丟棄未明確定義的流量。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-623">Demonstrate that all firewalls are configured to drop traffic not explicitly defined.</span></span>

*   <span data-ttu-id="e5d2c-624">示範防火牆只支援所有非主控台管理介面上的強式密碼編譯。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-624">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

*   <span data-ttu-id="e5d2c-625">示範防火牆對網際網路支援 MFA 所公開的非主控台管理介面。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-625">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

*   <span data-ttu-id="e5d2c-626">示範至少每6個月執行防火牆規則檢查</span><span class="sxs-lookup"><span data-stu-id="e5d2c-626">Demonstrate that firewall rule reviews are conducted at least every 6 months</span></span>

<span data-ttu-id="e5d2c-627">**防火牆– Web 應用程式防火牆 (WAF)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-627">**Firewall – Web Application Firewalls (WAF)**</span></span>  

<span data-ttu-id="e5d2c-628">如果部署了 WAF，則會提供額外的信用，以協助防範大量 web 應用程式威脅，以及應用程式可以公開的漏洞。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-628">Additional credit will be provided if a WAF is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="e5d2c-629">當出現 WAF 或類似的情況時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-629">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-630">示範 WAF 已設定為作用中的防禦模式，或使用警示進行監視。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-630">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="e5d2c-631">示範 WAF 已設定為支援 SSL 卸載。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-631">Demonstrate the WAF is configured to support SSL Offloading.</span></span>

* <span data-ttu-id="e5d2c-632">設定為依據 OWASP Core Rule Set (3.0 或 3.1) ，以防範下列大多數的攻擊類型：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-632">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="e5d2c-633">&#x2713; 通訊協定和編碼的問題。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-633">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="e5d2c-634">&#x2713; 頁首注入、要求 smuggling 及回應分割。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-634">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="e5d2c-635">&#x2713; 檔和路徑遍歷攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-635">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="e5d2c-636">&#x2713; Remote file 包含 (RFI) 攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-636">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="e5d2c-637">&#x2713; 遠端程式碼執行攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-637">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="e5d2c-638">&#x2713; PHP 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-638">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="e5d2c-639">&#x2713; 跨網站腳本攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-639">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="e5d2c-640">&#x2713; SQL 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-640">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="e5d2c-641">&#x2713; 會話 fixation 攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-641">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="e5d2c-642">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-642">**Change Control**</span></span>

<span data-ttu-id="e5d2c-643">因為 ISO 27001 審計並未特別評估變更要求程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-643">As ISO 27001 audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-644">示範變更要求包含下列詳細資料：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-644">Demonstrate that change requests have the following details:</span></span>

<span data-ttu-id="e5d2c-645">&#x2713; 記錄的影響。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-645">&#x2713; Documented impact.</span></span>

<span data-ttu-id="e5d2c-646">&#x2713; 要執行之功能測試的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-646">&#x2713; Details of what functionality testing is to be conducted.</span></span>

<span data-ttu-id="e5d2c-647">&#x2713; 任何後向外程式的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-647">&#x2713; Details of any back-out procedures.</span></span>

* <span data-ttu-id="e5d2c-648">示範執行變更之後所進行的功能測試。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-648">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="e5d2c-649">示範進行功能測試後，已登出變更要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-649">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="e5d2c-650">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-650">**Account Management**</span></span>

<span data-ttu-id="e5d2c-651">因為 ISO 27001 審計並未特別評估帳戶管理程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-651">As ISO 27001 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="e5d2c-652">示範如何執行 &#x2713;，以減輕重新顯示攻擊 (例如，MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-652">Demonstrate how &#x2713;s are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>
*   <span data-ttu-id="e5d2c-653">示範如何停用或刪除3個月內尚未使用的帳戶。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-653">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>
*   <span data-ttu-id="e5d2c-654">您必須設定 &#x2713; 或其他適當的緩解措施，以保護使用者認證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-654">&#x2713;  or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="e5d2c-655">下列最小密碼原則應使用為指導方針：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-655">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="e5d2c-656">&#x2713; 長度為8個字元的最小密碼長度。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-656">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="e5d2c-657">&#x2713; 超過10次嘗試的帳戶鎖定閾值。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-657">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>
 
<span data-ttu-id="e5d2c-658">&#x2713; 至少五個密碼的密碼歷史記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-658">&#x2713; Password history of a minimum of five passwords.</span></span>
 
<span data-ttu-id="e5d2c-659">&#x2713; 採用強式密碼的強制執行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-659">&#x2713; Enforcement of the use of strong passwords.</span></span>
 
*   <span data-ttu-id="e5d2c-660">示範 MFA 是針對所有遠端存取解決方案進行設定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-660">Demonstrate that MFA is configured for all remote access solutions.</span></span>

*   <span data-ttu-id="e5d2c-661">示範如何在所有遠端存取解決方案上設定增強式加密。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-661">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

*   <span data-ttu-id="e5d2c-662">公用 DNS 的管理位於範圍外的環境之外，所有能夠進行 DNS 修改的使用者帳戶都必須設定為使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-662">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="e5d2c-663">**侵入偵測及防護 (選用)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-663">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="e5d2c-664">當 ISO 27001 審核未特別評估入侵偵測和防護服務的某些元素 (IDPS) 程式，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-664">As ISO 27001 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="e5d2c-665">IDPS **應該** 在支援的環境周邊部署。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-665">IDPS **SHOULD** be deployed at the perimeter of the supporting environment.</span></span>

*   <span data-ttu-id="e5d2c-666">IDPS 簽章 **應** 保留在過去一天內的最新狀態。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-666">IDPS signatures **SHOULD** be kept current, within the past day.</span></span>

*   <span data-ttu-id="e5d2c-667">IDPS **應** 針對 TLS 檢查進行設定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-667">IDPS **SHOULD** be configured for TLS inspection.</span></span>

*   <span data-ttu-id="e5d2c-668">IDPS **應** 針對所有輸入和輸出流量進行設定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-668">IDPS **SHOULD** be configured for ALL inbound and outbound traffic.</span></span>

*   <span data-ttu-id="e5d2c-669">**應該** 設定 IDPS 以進行警示。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-669">IDPS **SHOULD** be configured for alerting.</span></span>

<span data-ttu-id="e5d2c-670">**事件記錄**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-670">**Event Logging**</span></span>

<span data-ttu-id="e5d2c-671">因為 ISO 27001 審計並未特別評估安全性事件記錄處理常式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-671">As ISO 27001 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-672">示範公開面向的系統會登入集中式記錄解決方案，而不是在 DMZ 內。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-672">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="e5d2c-673">示範最少30天的記錄資料是否可以立即可用，保留90天。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-673">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days being retained.</span></span>

<span data-ttu-id="e5d2c-674">**檢查 (記錄資料)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-674">**Reviewing (Logging Data)**</span></span>

<span data-ttu-id="e5d2c-675">因為 ISO 27001 審計並未特別評估此類別的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-675">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

*   <span data-ttu-id="e5d2c-676">示範每日記錄檢查的執行方式，以及如何識別例外狀況和異常的識別方式，以顯示如何處理這些狀況。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-676">Demonstrate how daily log reviews are conducted and how exceptions and anomalies are identified showing how these are handled.</span></span>

<span data-ttu-id="e5d2c-677">**提醒**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-677">**Alerting**</span></span>

<span data-ttu-id="e5d2c-678">因為 ISO 27001 審計並未特別評估此類別的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-678">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-679">示範如何設定安全性事件，以觸發立即會審的警示。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-679">Demonstrate how security events are configured to trigger alerts for immediate triage.</span></span>

* <span data-ttu-id="e5d2c-680">示範員工如何提供24/7，以回應安全性警示。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-680">Demonstrate how staff are available 24/7 to respond to security alerts.</span></span>

<span data-ttu-id="e5d2c-681">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-681">**Risk Management**</span></span>

<span data-ttu-id="e5d2c-682">因為 ISO 27001 審計並未特別評估風險評估程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-682">As ISO 27001 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-683">示範是否已建立正式的風險管理流程。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-683">Demonstrate that a formal risk management process is established.</span></span>

<span data-ttu-id="e5d2c-684">**事件回應**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-684">**Incident Response**</span></span>

<span data-ttu-id="e5d2c-685">因為 ISO 27001 審計並未特別評估事件回應原則和程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-685">As ISO 27001 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

*   <span data-ttu-id="e5d2c-686">示範事件回應計畫/套裝程式括：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-686">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="e5d2c-687">&#x2713; 預期威脅模型的特定回應程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-687">&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="e5d2c-688">&#x2713; 的事件處理功能會對應至 NIST Cybersecurity Framework (識別、保護、偵測、回應、復原) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-688">&#x2713; Incident handling capabilities aligning to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>
 
<span data-ttu-id="e5d2c-689">&#x2713; IRP 涵蓋範圍內系統。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-689">&#x2713; The IRP covers the in-scope systems.</span></span>
 
<span data-ttu-id="e5d2c-690">&#x2713; 事件回應小組的年度訓練。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-690">&#x2713; Annual training for the incident response team.</span></span>

## <a name="appendix-d"></a><span data-ttu-id="e5d2c-691">附錄 D</span><span class="sxs-lookup"><span data-stu-id="e5d2c-691">Appendix D</span></span>

### <a name="evidence-collection--deltas-for-pci-dss"></a><span data-ttu-id="e5d2c-692">證據集合– PCI DSS 的增量</span><span class="sxs-lookup"><span data-stu-id="e5d2c-692">Evidence Collection – Deltas for PCI DSS</span></span>

<span data-ttu-id="e5d2c-693">在您已具備 pci dss 相容性的情況下，下列差異的 (間距) 尚未完全涵蓋 pci dss，至少需要在此 Microsoft 365 認證中查看。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-693">Where you have already attained PCI DSS compliance, the following delta’s (gaps) not wholly covered by PCI DSS will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="e5d2c-694">作為 Microsoft 365 憑證評估的一部分，認證分析員會判斷是否有任何對應的 pci dss 控制項未包含在 PCI DSS 評估中，也可能會決定要包含的控制項範例，以提供進一步的保證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-694">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped PCI DSS controls were not included as part of the PCI DSS assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="e5d2c-695">PCI DSS 中缺少的任何需求，都必須納入 Microsoft 365 認證評估活動。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-695">Any requirements missing from the PCI DSS will need to be included into the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="e5d2c-696">**惡意程式碼保護-應用程式控制**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-696">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="e5d2c-697">如果透過使用防病毒進行惡意程式碼保護，且 attested 至 PCI DSS 報告中，則不需要進一步調查。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-697">If malware protection is in place through use of anti-virus and is attested to within PCI DSS Report no further investigation is necessary.</span></span> <span data-ttu-id="e5d2c-698">如果沒有任何防毒軟體，認證分析人員必須識別並評估應用程式控制機制的證據，以防止在環境內引爆惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-698">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="e5d2c-699">這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-699">This will require you to:</span></span> 

*   <span data-ttu-id="e5d2c-700">示範如何進行應用程式核准，並確認已完成此作業。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-700">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="e5d2c-701">示範存在業務合理性論證的核准應用程式完整清單。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-701">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="e5d2c-702">提供或示範支援檔，以詳述如何設定應用程式控制軟體，以符合特定的應用程式控制機制 (例如 whitelisting、程式碼簽署等 ) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-702">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

*   <span data-ttu-id="e5d2c-703">示範所有抽樣的系統元件，應用程式控制設定為已記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-703">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="e5d2c-704">**修補程式管理–風險排名**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-704">**Patch Management – Risk Ranking**</span></span>

<span data-ttu-id="e5d2c-705">因為 PCI DSS 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-705">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-706">示範風險排名如何進行中的安全。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-706">Demonstrate how risk ranking of vulnerabilities is conducted.</span></span>

<span data-ttu-id="e5d2c-707">**弱點掃描**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-707">**Vulnerability Scanning**</span></span>

<span data-ttu-id="e5d2c-708">因為 PCI DSS 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-708">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-709">示範如何使用已記錄的漏洞修正原則即時進行修復。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-709">Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="e5d2c-710">**防火牆–防火牆 (或同等技術)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-710">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="e5d2c-711">因為 PCI DSS 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-711">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-712">示範防火牆只支援所有非主控台管理介面上的強式密碼編譯。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-712">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

* <span data-ttu-id="e5d2c-713">示範防火牆對網際網路支援 MFA 所公開的非主控台管理介面。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-713">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

<span data-ttu-id="e5d2c-714">如果部署的 Web 應用程式防火牆 (WAF) ，將會提供額外的信用，以協助防範大量 Web 應用程式威脅，以及應用程式可能公開的漏洞。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-714">Additional credit will be provided if a Web Application Firewall (WAF) s deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="e5d2c-715">當出現 WAF 或類似的情況時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-715">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-716">示範 WAF 已設定為作用中的防禦模式，或使用警示進行監視。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-716">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="e5d2c-717">示範 WAF 已設定為支援 SSL 卸載。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-717">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="e5d2c-718">設定為依據 OWASP Core Rule Set (3.0 或 3.1) ，以防範下列大多數的攻擊類型：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-718">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="e5d2c-719">&#x2713; 通訊協定和編碼的問題。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-719">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="e5d2c-720">&#x2713; 頁首注入、要求 smuggling 及回應分割。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-720">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="e5d2c-721">&#x2713; 檔和路徑遍歷攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-721">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="e5d2c-722">&#x2713; Remote file 包含 (RFI) 攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-722">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="e5d2c-723">&#x2713; 遠端程式碼執行攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-723">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="e5d2c-724">&#x2713; PHP 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-724">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="e5d2c-725">&#x2713; 跨網站腳本攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-725">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="e5d2c-726">&#x2713; SQL 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-726">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="e5d2c-727">&#x2713; 會話 fixation 攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-727">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="e5d2c-728">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-728">**Change Control**</span></span>

<span data-ttu-id="e5d2c-729">因為 PCI DSS 審核並未特別評估變更要求程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-729">As PCI DSS audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-730">示範變更要求會在實際執行環境中提出之前引發。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-730">Demonstrate that change requests are raised before being made in production environments.</span></span>

* <span data-ttu-id="e5d2c-731">示範在實際執行之前，必須先取得變更的授權。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-731">Demonstrate that changes are authorized before going into production.</span></span>

* <span data-ttu-id="e5d2c-732">示範執行變更之後所進行的功能測試。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-732">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="e5d2c-733">示範進行功能測試後，已登出變更要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-733">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="e5d2c-734">**安全的軟體發展/部署**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-734">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="e5d2c-735">因為 PCI DSS 審核並未特別存取安全軟體發展和部署程式的某些元素，所以這需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-735">As PCI DSS audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

* <span data-ttu-id="e5d2c-736">程式碼存放庫必須由 MFA 保護。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-736">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="e5d2c-737">必須有足夠的存取控制，才能保護代碼存放庫，避免惡意的程式碼修改。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-737">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="e5d2c-738">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-738">**Account Management**</span></span>

<span data-ttu-id="e5d2c-739">因為 PCI DSS 審核並未特別評估帳戶管理程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-739">As PCI DSS audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-740">示範授權機制的實施方式，以減輕重新顯示攻擊 (例如，MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-740">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

* <span data-ttu-id="e5d2c-741">必須設定強式密碼原則或其他適當的緩解措施，以保護使用者認證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-741">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="e5d2c-742">下列最小密碼原則應使用為指導方針：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-742">The following minimum password policy should be used as a guideline:</span></span> 

<span data-ttu-id="e5d2c-743">&#x2713; 長度為8個字元的最小密碼長度。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-743">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="e5d2c-744">&#x2713; 超過10次嘗試的帳戶鎖定閾值。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-744">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="e5d2c-745">&#x2713; 至少五個密碼的密碼歷史記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-745">&#x2713; Password history of a minimum of five passwords.</span></span>

<span data-ttu-id="e5d2c-746">&#x2713; 採用強式密碼的強制執行。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-746">&#x2713; Enforcement of the use of strong passwords.</span></span>

* <span data-ttu-id="e5d2c-747">示範如何在所有遠端存取解決方案上設定增強式加密。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-747">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

* <span data-ttu-id="e5d2c-748">公用 DNS 的管理位於範圍外的環境之外，所有能夠進行 DNS 修改的使用者帳戶都必須設定為使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-748">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="e5d2c-749">**侵入偵測及防護 (選用)**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-749">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="e5d2c-750">因為 PCI DSS 審核並未特別評估入侵偵測及防護服務 (IDPS) 程式的某些要素，所以這需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-750">As PCI DSS audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-751">IDPS 應針對 TLS 檢查進行設定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-751">IDPS SHOULD be configured for TLS inspection.</span></span>

*   <span data-ttu-id="e5d2c-752">IDPS 應針對所有輸入和輸出流量進行設定。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-752">IDPS SHOULD be configured for ALL inbound and outbound traffic.</span></span>

<span data-ttu-id="e5d2c-753">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-753">**Risk Management**</span></span>

<span data-ttu-id="e5d2c-754">因為 PCI DSS 審核並未特別評估風險評估程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-754">As PCI DSS audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-755">示範風險評估包含影響和可能性清單。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-755">Demonstrate the risk assessment includes impact and likelihood matrices.</span></span>

<span data-ttu-id="e5d2c-756">**事件回應**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-756">**Incident Response**</span></span>

<span data-ttu-id="e5d2c-757">因為 PCI DSS 審核並未特別評估事件回應原則和程式的某些要素，所以需要開發人員進行下列作業：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-757">As PCI DSS audits don't specifically assess some elements of incident response policies and processes, this will require the developer to:</span></span>

* <span data-ttu-id="e5d2c-758">示範事件處理功能，使其符合 NIST Cybersecurity Framework (識別、保護、偵測、回應、復原) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-758">Demonstrate Incident handling capabilities align to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>

## <a name="appendix-e"></a><span data-ttu-id="e5d2c-759">附錄 E</span><span class="sxs-lookup"><span data-stu-id="e5d2c-759">Appendix E</span></span>

### <a name="evidence-collection---deltas-for-soc-2"></a><span data-ttu-id="e5d2c-760">證據收集-SOC 2 的增量</span><span class="sxs-lookup"><span data-stu-id="e5d2c-760">Evidence Collection - Deltas for SOC 2</span></span>

<span data-ttu-id="e5d2c-761">在您已具備 soc 2 相容性的情況下，下列差異的 (間距) 尚未完全涵蓋為此 Microsoft 365 認證的一部分。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-761">Where you have already attained SOC 2 compliance, the following delta’s (gaps) not wholly covered by SOC 2 will need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="e5d2c-762">在「Microsoft 365 憑證評估」中，認證分析員會判斷是否有任何對應的 soc 2 控制項未納入于 SOC 2 評估中，也可以決定要包含的控制項範例，以提供進一步的保證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-762">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped SOC 2 controls were not included as part of your SOC 2 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="e5d2c-763">SOC 2 評估中遺漏的任何需求，都必須納入 Microsoft 365 認證評估活動中。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-763">Any requirements missing from your SOC 2 assessment will need to be included as part of the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="e5d2c-764">**惡意程式碼保護-應用程式控制**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-764">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="e5d2c-765">如果惡意程式碼防護是透過使用防毒程式所進行的，且是在 SOC 2 報表內 attested，則不需要進一步調查。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-765">If malware protection is in place through use of anti-virus and is attested to within your SOC 2 report no further investigation is necessary.</span></span> <span data-ttu-id="e5d2c-766">如果沒有任何防毒軟體，認證分析人員必須識別並評估應用程式控制機制的證據，以防止在環境內引爆惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-766">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="e5d2c-767">這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-767">This will require you to:</span></span>

* <span data-ttu-id="e5d2c-768">提供或示範支援檔，以詳述如何設定應用程式控制軟體，以符合特定的應用程式控制機制 (例如 whitelisting、程式碼簽署等 ) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-768">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

* <span data-ttu-id="e5d2c-769">示範如何進行應用程式核准，並確認已完成此作業。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-769">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="e5d2c-770">示範存在業務合理性論證的核准應用程式完整清單。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-770">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="e5d2c-771">示範所有抽樣的系統元件，應用程式控制設定為已記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-771">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="e5d2c-772">**修補程式管理–修補程式**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-772">**Patch Management – Patching**</span></span>

<span data-ttu-id="e5d2c-773">因為 SOC 2 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-773">As SOC 2 audits do not specifically assess this category, this will require you to:</span></span>

*   <span data-ttu-id="e5d2c-774">所有低、中、高或嚴重問題，都必須在正常的修補使用中視窗內修補。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-774">Any Low, Medium, High, or Critical issue must be patched within normal patching activity windows.</span></span>

*   <span data-ttu-id="e5d2c-775">不支援廠商的軟體元件和作業系統，不得在環境內使用。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-775">Software components and operating systems no longer supported by the vendor MUST not be used within the environment.</span></span> <span data-ttu-id="e5d2c-776">支援的原則必須已到位，以確保會從環境中移除不受支援的軟體元件/作業系統，以及識別何時必須使用軟體元件的程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-776">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>

<span data-ttu-id="e5d2c-777">**防火牆–防火牆**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-777">**Firewall – Firewalls**</span></span>

<span data-ttu-id="e5d2c-778">當 SOC 2 審核未特別評估變更控制至防火牆存取控制清單，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-778">As SOC 2 audits do not specifically assess change controls to firewall access control lists, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-779">示範透過防火牆 (s) 所允許的所有流量，都是透過授權程式來進行，以取得業務理由的所有流量的檔。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-779">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

* <span data-ttu-id="e5d2c-780">示範防火牆規則檢查是否至少每六個月執行一次。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-780">Demonstrate that firewall rule reviews are conducted at least every six months.</span></span>

<span data-ttu-id="e5d2c-781">如果已部署 Web 應用程式防火牆 (WAF) 或類似，則會提供額外的信用，以協助防範大量 Web 應用程式威脅，以及應用程式可以公開的漏洞。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-781">Additional credit will be provided if a Web Application Firewall (WAF) or similar is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="e5d2c-782">當出現 WAF 或類似的情況時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-782">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-783">示範 WAF 已設定為作用中的防禦模式，或使用警示進行監視。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-783">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="e5d2c-784">示範 WAF 已設定為支援 SSL 卸載。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-784">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="e5d2c-785">設定為依照 OWASP Core Rule Set ( (3.0 或 3.1) ，以防範下列大多數的攻擊類型：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-785">Is configured as per the OWASP Core Rule Set ((3.0 or 3.1) to protect against the majority of the following attack types:</span></span>

<span data-ttu-id="e5d2c-786">&emsp;&#x2713; 通訊協定和編碼的問題。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-786">&emsp;&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="e5d2c-787">&emsp;&#x2713; 頁首注入、要求 smuggling 及回應分割。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-787">&emsp;&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="e5d2c-788">&emsp;&#x2713; 檔和路徑遍歷攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-788">&emsp;&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="e5d2c-789">&emsp;&#x2713; Remote file 包含 (RFI) 攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-789">&emsp;&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="e5d2c-790">&emsp;&#x2713; 遠端程式碼執行攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-790">&emsp;&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="e5d2c-791">&emsp;&#x2713; PHP 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-791">&emsp;&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="e5d2c-792">&emsp;&#x2713; 跨網站腳本攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-792">&emsp;&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="e5d2c-793">&emsp;&#x2713; SQL 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-793">&emsp;&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="e5d2c-794">&emsp;&#x2713; 會話 fixation 攻擊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-794">&emsp;&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="e5d2c-795">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-795">**Change Control**</span></span>

<span data-ttu-id="e5d2c-796">當 SOC 2 審核並未特別評估變更要求程式的某些元素時，這需要開發人員進行下列作業：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-796">As SOC 2 audits don't specifically assess some elements of Change Request processes, this will require the developer to:</span></span>

* <span data-ttu-id="e5d2c-797">示範如何將開發/測試環境與實際執行的工作環境分開，以加強責任。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-797">Demonstrate how development / test environments are separate from the production environment enforcing separation of duties.</span></span>

* <span data-ttu-id="e5d2c-798">示範如何在開發/測試環境中使用即時資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-798">Demonstrate how live data isn't used within the development / test environments.</span></span>

* <span data-ttu-id="e5d2c-799">示範執行變更之後所進行的功能測試。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-799">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="e5d2c-800">示範進行功能測試後，已登出變更要求。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-800">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="e5d2c-801">**安全的軟體發展/部署**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-801">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="e5d2c-802">當 SOC 2 審核未特別存取安全軟體發展和部署程式的某些元素時，這需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-802">As SOC 2 audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

*   <span data-ttu-id="e5d2c-803">您必須已建立並記錄軟體發展程式，以涵蓋整個軟體發展週期。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-803">You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>

*   <span data-ttu-id="e5d2c-804">開發人員必須至少一年為安全的軟體編碼訓練。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-804">Developers MUST undergo secure software coding training at least annually.</span></span>

*   <span data-ttu-id="e5d2c-805">程式碼存放庫必須由 MFA 保護。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-805">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="e5d2c-806">必須有足夠的存取控制，才能保護代碼存放庫，避免惡意的程式碼修改。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-806">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="e5d2c-807">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-807">**Account Management**</span></span>

<span data-ttu-id="e5d2c-808">因為 SOC2 的審計並未特別評估帳戶管理程式的某些要素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-808">As SOC2 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="e5d2c-809">示範授權機制的實施方式，以減輕重新顯示攻擊 (例如，MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-809">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

*   <span data-ttu-id="e5d2c-810">示範如何停用或刪除3個月內尚未使用的帳戶。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-810">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>

*   <span data-ttu-id="e5d2c-811">必須設定強式密碼原則或其他適當的緩解措施，以保護使用者認證。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-811">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="e5d2c-812">下列最小密碼原則應使用為指導方針：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-812">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="e5d2c-813">&emsp;&#x2713; 長度為8個字元的最小密碼長度。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-813">&emsp;&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="e5d2c-814">&emsp;&#x2713; 超過10次嘗試的帳戶鎖定閾值。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-814">&emsp;&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="e5d2c-815">&emsp; 至少要有5個密碼的&#x2713; 密碼記錄。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-815">&emsp;&#x2713; Password history of a minimum of 5 passwords.</span></span>

<span data-ttu-id="e5d2c-816">&emsp;&#x2713; 使用強式密碼的強制執行</span><span class="sxs-lookup"><span data-stu-id="e5d2c-816">&emsp;&#x2713; Enforcement of the use of strong passwords</span></span>

*   <span data-ttu-id="e5d2c-817">示範是否要將唯一的使用者帳戶發佈給所有使用者。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-817">Demonstrate that unique user accounts are issued to all users.</span></span>

*   <span data-ttu-id="e5d2c-818">公用 DNS 的管理位於範圍外的環境之外，所有能夠進行 DNS 修改的使用者帳戶都必須設定為使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-818">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="e5d2c-819">**入侵偵測及防護 (選用) 。**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-819">**Intrusion Detection and Prevention (OPTIONAL).**</span></span>

<span data-ttu-id="e5d2c-820">當 SOC 2 審核未特別評估入侵偵測和防護服務的某些元素 (IDPS) 程式時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-820">As SOC 2 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="e5d2c-821">IDPS 簽章應保持在最新狀態，在過去一天內</span><span class="sxs-lookup"><span data-stu-id="e5d2c-821">IDPS signatures SHOULD be kept current, within the past day</span></span>

*   <span data-ttu-id="e5d2c-822">應該針對 TLS 檢查設定 IDPS</span><span class="sxs-lookup"><span data-stu-id="e5d2c-822">IDPS SHOULD be configured for TLS inspection</span></span>

*   <span data-ttu-id="e5d2c-823">IDPS 應針對所有輸入和輸出流量進行設定</span><span class="sxs-lookup"><span data-stu-id="e5d2c-823">IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span>

<span data-ttu-id="e5d2c-824">**事件記錄**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-824">**Event Logging**</span></span>

<span data-ttu-id="e5d2c-825">當 SOC 2 審核未特別評估安全性事件記錄處理常式的某些元素時，這需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-825">As SOC 2 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-826">示範如何在範例集內的所有系統元件上設定下列系統，以記錄下列事件</span><span class="sxs-lookup"><span data-stu-id="e5d2c-826">Demonstrate how, on all system components within the sample set the following system are configured to log the following events</span></span>

<span data-ttu-id="e5d2c-827">&emsp;&#x2713; 使用者對系統元件及應用程式 (s) 的存取權。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-827">&emsp;&#x2713; User access to system components and the application(s).</span></span>

<span data-ttu-id="e5d2c-828">&emsp;&#x2713; 高許可權使用者採取的所有動作。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-828">&emsp;&#x2713; All actions taken by a high privileged user.</span></span>

<span data-ttu-id="e5d2c-829">&emsp;&#x2713; 不正確邏輯存取嘗試。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-829">&emsp;&#x2713; Invalid logical access attempts.</span></span>

<span data-ttu-id="e5d2c-830">示範記錄的事件包含;下列資訊至少會有：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-830">Demonstrate that logged events contain; at a minimum, the following information:</span></span>

<span data-ttu-id="e5d2c-831">&emsp;&#x2713; 使用者。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-831">&emsp;&#x2713; User.</span></span>

<span data-ttu-id="e5d2c-832">&emsp;&#x2713; 事件種類。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-832">&emsp;&#x2713; Type of Event.</span></span>

<span data-ttu-id="e5d2c-833">&emsp;&#x2713; 日期和時間。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-833">&emsp;&#x2713; Date and Time.</span></span>

<span data-ttu-id="e5d2c-834">&emsp;&#x2713; 成功/失敗指示器。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-834">&emsp;&#x2713; Success/Failure indicator.</span></span>

<span data-ttu-id="e5d2c-835">&emsp; 用以識別受影響系統的&#x2713; 標籤。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-835">&emsp;&#x2713; Label to identify the affected system.</span></span>

*   <span data-ttu-id="e5d2c-836">示範範例集內的所有系統元件皆已設定為使用時間同步處理，而且這些元件與主要/次要時間伺服器相同。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-836">Demonstrate that all system components within the sample set are configured to utilize time-synchronization and that these are the same as the primary/secondary time servers.</span></span>

* <span data-ttu-id="e5d2c-837">示範公開面向的系統會登入集中式記錄解決方案，而不是在 DMZ 內。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-837">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

*   <span data-ttu-id="e5d2c-838">示範公開面向的系統會登入集中式記錄解決方案，而不是在 DMZ 內。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-838">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="e5d2c-839">示範集中式記錄解決方案如何受到保護，以防未經授權篡改記錄資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-839">Demonstrate how the centralized logging solution is protected from unauthorized tampering of logging data.</span></span>

* <span data-ttu-id="e5d2c-840">示範最少30天的記錄資料如何立即可用，保留90天或更長的時間。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-840">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days’ or more being retained.</span></span>

<span data-ttu-id="e5d2c-841">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-841">**Risk Management**</span></span>

<span data-ttu-id="e5d2c-842">因為 SOC2 的審計並未特別評估風險評估程式的某些要素，所以這會需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-842">As SOC2 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-843">示範是否至少一年執行正式的風險評估。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-843">Demonstrate that a formal risk assessment is conducted at least annually.</span></span>

<span data-ttu-id="e5d2c-844">*事件回應。*</span><span class="sxs-lookup"><span data-stu-id="e5d2c-844">*Incident Response.*</span></span>

<span data-ttu-id="e5d2c-845">因為 SOC2 的審計並未特別評估事件回應原則和程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-845">As SOC2 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

* <span data-ttu-id="e5d2c-846">示範事件回應計畫/套裝程式括：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-846">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="e5d2c-847">&emsp;&#x2713; 預期威脅模型的特定回應程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-847">&emsp;&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="e5d2c-848">&emsp;&#x2713; 記錄的通訊處理常式，以確保重要的專案關係人 (付款商標/acquirers、法規內文、主管機關、董事、客戶等的及時通知。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-848">&emsp;&#x2713; Documented communications process to ensure timely notification of key stakeholders (payment brands/acquirers, regulatory bodies, supervisory authorities, directors, customers, etc.</span></span>

## <a name="appendix-f"></a><span data-ttu-id="e5d2c-849">附錄 F</span><span class="sxs-lookup"><span data-stu-id="e5d2c-849">Appendix F</span></span>

### <a name="hosting-deployment-types"></a><span data-ttu-id="e5d2c-850">裝載部署類型</span><span class="sxs-lookup"><span data-stu-id="e5d2c-850">Hosting Deployment Types</span></span>

<span data-ttu-id="e5d2c-851">Microsoft 承認您會在不同的主控環境中部署應用程式及儲存應用程式/增益集程式碼。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-851">Microsoft acknowledges you will deploy applications and store app/add-in code within different hosting environments.</span></span> <span data-ttu-id="e5d2c-852">Microsoft 365 憑證中某些安全性控制措施的整體責任將取決於所使用的主控環境。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-852">The overall responsibilities of some of the security controls within the Microsoft 365 Certification will depend on the hosting environment being used.</span></span> <span data-ttu-id="e5d2c-853">附錄 F 查看常見的部署類型，並根據評估程式中評估的安全性控制來對應這些類型。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-853">Appendix F looks at common deployment types and maps these against the security controls that are evaluated as part of the assessment process.</span></span> <span data-ttu-id="e5d2c-854">已識別下列主控部署類型：</span><span class="sxs-lookup"><span data-stu-id="e5d2c-854">The following hosting deployment types have been identified:</span></span>

|<span data-ttu-id="e5d2c-855">主控類型</span><span class="sxs-lookup"><span data-stu-id="e5d2c-855">Hosting Types</span></span>  |<span data-ttu-id="e5d2c-856">描述</span><span class="sxs-lookup"><span data-stu-id="e5d2c-856">Description</span></span>  |
|-----|------|
|<span data-ttu-id="e5d2c-857">**ISV 主控**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-857">**ISV Hosted**</span></span>|<span data-ttu-id="e5d2c-858">ISV 主控類型可定義為您負責用來支援應用程式/增益集環境的基礎結構。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-858">ISV hosted types can be defined as where you are responsible for the infrastructure used to support the app/add-in environment.</span></span> <span data-ttu-id="e5d2c-859">這可以實際位於您自己的資料中心或具有共同位置服務的協力廠商資料中心。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-859">This can be physically located within your own data centers or third-party data centers with a co-location service.</span></span> <span data-ttu-id="e5d2c-860">最後，您擁有對支援基礎結構和作業環境的完全擁有權和系統管理控制權。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-860">Ultimately, you have full ownership and administrative control over the supporting infrastructure and operating environment.</span></span>|
|<span data-ttu-id="e5d2c-861">**基礎結構即服務 (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span><span class="sxs-lookup"><span data-stu-id="e5d2c-861">**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span></span>|<span data-ttu-id="e5d2c-862">基礎結構即服務是一種服務，可讓雲端服務提供者代之實體支援基礎結構由雲端服務提供者 (CSP) 加以管理及維護。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-862">Infrastructure as a Service is a service that is provided whereby the physical supporting infrastructure is managed and maintained on their behalf by the cloud service provider (CSP).</span></span> <span data-ttu-id="e5d2c-863">通常，網路、儲存、實體伺服器及虛擬化基礎結構都是 CSP 的責任。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-863">Typically, networking, storage, physical servers, and the virtualization infrastructure is all the responsibility of the CSP.</span></span> <span data-ttu-id="e5d2c-864">作業系統、中介軟體、執行時間、資料和應用程式是您的責任。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-864">The Operating System, Middleware, Runtime, Data and Applications are the responsibilities of you.</span></span> <span data-ttu-id="e5d2c-865">此外，協力廠商也會管理及維護 Firewalling 功能，但防火牆規則基底的維護通常仍是消費者責任。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-865">Firewalling capabilities would also be managed and maintained by the third-party, however maintenance of the firewall rule base would usually be still the consumers responsibility.</span></span>|
|<span data-ttu-id="e5d2c-866">**平臺為服務/無伺服器 (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span><span class="sxs-lookup"><span data-stu-id="e5d2c-866">**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span></span>| <span data-ttu-id="e5d2c-867">透過平臺即服務，您可以使用受管理的平臺，以呈現可使用的服務。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-867">With Platform as a Service, you are provisioned with a managed platform presenting a service that can be consumed.</span></span> <span data-ttu-id="e5d2c-868">您不需要執行 sysadmin 功能，因為作業系統及支援的基礎結構是由 CSP 所管理。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-868">You do not need to perform sysadmin functions as the operating system and supporting infrastructure is managed by the CSP.</span></span> <span data-ttu-id="e5d2c-869">這通常是在組織不想要展示 web 服務，而是可專注于在雲端管理 web 服務上建立 web 應用程式時，使用。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-869">This would typically be used when organizations do not want to be concerned with presenting a web service and instead can concentrate on creating the web application source code and publishing the web application on the cloud managed web services.</span></span>  <span data-ttu-id="e5d2c-870">另一個範例可能是資料庫服務，其中會為資料庫提供連線，但是支援基礎結構和資料庫應用程式會從消費者中抽象出來。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-870">Another example may be a database service where connectivity is given to a database, however the supporting infrastructure and database application is abstracted from the consumer.</span></span>   <span data-ttu-id="e5d2c-871">**附注：「無伺服器」和「PaaS」類似，目的在於 Microsoft 365 憑證裝載部署類型的 [無伺服器] 和 [PasS] 視為相同。**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-871">**Note: Serverless and PaaS are similar so for the purpose of the Microsoft 365 Certification Hosting Deployment Type's Serverless and PasS are deemed the same**</span></span>|
|<span data-ttu-id="e5d2c-872">**混合主控**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-872">**Hybrid Hosted**</span></span>|<span data-ttu-id="e5d2c-873">使用混合式主控類型時，您可以使用多個主控類型來支援支援環境的各個部分。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-873">With the hybrid hosted type, you may utilize multiple hosted types to support various parts of the supporting environment.</span></span> <span data-ttu-id="e5d2c-874">在多個 M365 堆疊中使用應用程式/增益集的情況可能更多。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-874">This may be more the case where apps/add-ins are utilized across multiple M365 stacks.</span></span> <span data-ttu-id="e5d2c-875">雖然 Microsoft 365 憑證會支援跨多個 M365 服務的應用程式/附加元件的開發，但在應用程式/增益集之間的整個 () 支援環境，都必須依每個適用的「主控型類型對應」進行評估。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-875">Although the Microsoft 365 Certification will support where apps/add-ons across multiple M365 services are developed, an assessment of the entire (across app/add-ins) supporting environment would need to be assessed in line with each of the applicable "Hosted Type Mappings".</span></span> <span data-ttu-id="e5d2c-876">在某些情況下，您可能會利用針對單一增益集的不同主控類型，在其中執行這項功能時，準則的適用性必須仍然遵循各種主控類型的「主控類型對應」準則。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-876">Occasionally, you may utilize different hosted types for a single add-in, where this is being carried out, applicability of criteria will need to still follow the "Hosted Type Mappings" criteria across the various hosted types.</span></span>|
|<span data-ttu-id="e5d2c-877">**共用主控**</span><span class="sxs-lookup"><span data-stu-id="e5d2c-877">**Shared Hosting**</span></span>|<span data-ttu-id="e5d2c-878">共用主機是指在由多個個人消費者共用的平臺內主控環境的所在位置。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-878">Shared hosting is where you are hosting the environment within a platform that shared by multiple individual consumers.</span></span> <span data-ttu-id="e5d2c-879">因為採用雲端，所以未寫入 Microsoft 365 憑證規格，因此共用主控不是常見的。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-879">The Microsoft 365 Certification Specification was not written to account for this due to the adoption of cloud, shared hosting is not common.</span></span> <span data-ttu-id="e5d2c-880">如果您認為使用的是，請與 Microsoft 聯繫，因為需要建立額外的需求，以考慮此類型的主機類型下的其他風險。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-880">If you believe this is being used please contact Microsoft as additional requirements will need to be created to account for the additional risks under this type of hosting type.</span></span>|


## <a name="appendix-g"></a><span data-ttu-id="e5d2c-881">附錄 G</span><span class="sxs-lookup"><span data-stu-id="e5d2c-881">Appendix G</span></span>

### <a name="microsoft-365-certification-process-workflow"></a><span data-ttu-id="e5d2c-882">Microsoft 365證書處理常式工作流程</span><span class="sxs-lookup"><span data-stu-id="e5d2c-882">Microsoft 365 Certification Process Workflow</span></span>

![工作流程](ProcessFlow.jpg)

## <a name="learn-more"></a><span data-ttu-id="e5d2c-884">深入了解</span><span class="sxs-lookup"><span data-stu-id="e5d2c-884">Learn more</span></span>

[<span data-ttu-id="e5d2c-885">Microsoft 365應用程式規範計畫概述</span><span class="sxs-lookup"><span data-stu-id="e5d2c-885">Microsoft 365 App Compliance Program Overview</span></span>](~/overview.md)  
[<span data-ttu-id="e5d2c-886">何謂 Microsoft 365 App Publisher 認證？</span><span class="sxs-lookup"><span data-stu-id="e5d2c-886">What is Microsoft 365 App Publisher Attestation?</span></span>](~/docs/attestation.md)  
[<span data-ttu-id="e5d2c-887">何謂 Microsoft 365 認證？</span><span class="sxs-lookup"><span data-stu-id="e5d2c-887">What is Microsoft 365 Certification?</span></span>](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a><span data-ttu-id="e5d2c-888">詞彙</span><span class="sxs-lookup"><span data-stu-id="e5d2c-888">Glossary</span></span>

### <a name="aia"></a><span data-ttu-id="e5d2c-889">友邦 保險</span><span class="sxs-lookup"><span data-stu-id="e5d2c-889">AIA</span></span>

<span data-ttu-id="e5d2c-890">\* 授權資訊存取是用來尋找發證憑證授權憑證的服務位置描述項。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-890">\*Authority Information Access is a service location descriptor used to find the certificate of the issuing certificate authority.</span></span>

### <a name="crl"></a><span data-ttu-id="e5d2c-891">Crl</span><span class="sxs-lookup"><span data-stu-id="e5d2c-891">CRL</span></span>

<span data-ttu-id="e5d2c-892">[\* 憑證吊銷清單] 提供一種方法，可讓安全通訊端層 (SSL) 端點，以確認從遠端主機收到的憑證是有效且可靠的。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-892">\*Certificate Revocation List provide a means for a Secure Sockets Layer (SSL) endpoint to verify that a certificate received from a remote host is valid and trustworthy.</span></span>

### <a name="cvss-score"></a><span data-ttu-id="e5d2c-893">CVSS 分數</span><span class="sxs-lookup"><span data-stu-id="e5d2c-893">CVSS score</span></span>

<span data-ttu-id="e5d2c-894">[\* 常見弱點計分系統是一種已發佈的標準，可衡量弱點，並根據其嚴重性計算數值分數。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-894">\*Common Vulnerability Scoring System is a published standard that measures vulnerability and calculates a numerical score based on its severity.</span></span>

### <a name="cvss-patch-management-guidelines"></a><span data-ttu-id="e5d2c-895">CVSS 修補程式管理指導方針</span><span class="sxs-lookup"><span data-stu-id="e5d2c-895">CVSS patch management guidelines</span></span>

* <span data-ttu-id="e5d2c-896">重大 (9.0-10.0) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-896">Critical (9.0 - 10.0)</span></span>
* <span data-ttu-id="e5d2c-897">高 (7.0-8.9) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-897">High (7.0 - 8.9)</span></span>
* <span data-ttu-id="e5d2c-898">中型 (4.0-6.9) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-898">Medium (4.0 - 6.9)</span></span>
* <span data-ttu-id="e5d2c-899">低 (0.0-3.9) </span><span class="sxs-lookup"><span data-stu-id="e5d2c-899">Low (0.0 - 3.9)</span></span>

### <a name="dmz"></a><span data-ttu-id="e5d2c-900">Dmz</span><span class="sxs-lookup"><span data-stu-id="e5d2c-900">DMZ</span></span>

<span data-ttu-id="e5d2c-901">\* 「網路隔離區域」是一種實體或邏輯的內部網路，可直接與外部或非 propriety 網路互動，同時保持主機內部、私人網路的獨立和獨立。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-901">\*Demilitarized zone is a physical or logical intermediate network that interacts directly external or non-propriety networks while keeping the host's internal, private network separate and isolated.</span></span>

### <a name="euii"></a><span data-ttu-id="e5d2c-902">EUII</span><span class="sxs-lookup"><span data-stu-id="e5d2c-902">EUII</span></span>

<span data-ttu-id="e5d2c-903">*使用者識別資訊*。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-903">*End-user identifiable information*.</span></span>

### <a name="gdpr"></a><span data-ttu-id="e5d2c-904">GDPR</span><span class="sxs-lookup"><span data-stu-id="e5d2c-904">GDPR</span></span>

<span data-ttu-id="e5d2c-905">\* 一般資料保護規定是歐盟 (歐盟) 隱私權和資料保護法規的所有歐盟公民的資料，不論您的應用程式網站位於何處。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-905">\*General Data Protection Regulation is a European Union (EU) privacy and data protection regulation for all EU citizens’ data regardless of where your application site is located.</span></span>

### <a name="hsts"></a><span data-ttu-id="e5d2c-906">HSTS</span><span class="sxs-lookup"><span data-stu-id="e5d2c-906">HSTS</span></span>

<span data-ttu-id="e5d2c-907">\* HTTP Strict Transport Security 利用 HTTP 回應標頭指示網頁瀏覽器僅透過 HTTPS 存取內容。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-907">\*HTTP Strict Transport Security utilizes a HTTP response header instructing the web browser to only access content over HTTPS.</span></span>  <span data-ttu-id="e5d2c-908">這是為了防範降級攻擊和 cookie 劫持所設計。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-908">This is designed to protect against downgrade attacks and cookie hijacking.</span></span>

### <a name="iec"></a><span data-ttu-id="e5d2c-909">Iec</span><span class="sxs-lookup"><span data-stu-id="e5d2c-909">IEC</span></span>

<span data-ttu-id="e5d2c-910">\* 國際 Electrotechnical 傭金。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-910">\*International Electrotechnical Commission.</span></span>

### <a name="isms"></a><span data-ttu-id="e5d2c-911">主義</span><span class="sxs-lookup"><span data-stu-id="e5d2c-911">ISMS</span></span>

<span data-ttu-id="e5d2c-912">\* 資訊安全性管理系統。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-912">\*Information Security Management System.</span></span>

### <a name="isv"></a><span data-ttu-id="e5d2c-913">ISV</span><span class="sxs-lookup"><span data-stu-id="e5d2c-913">ISV</span></span>

<span data-ttu-id="e5d2c-914">獨立的安全性廠商是一個人和組織，可在協力廠商軟體和硬體平臺上開發、投放及銷售軟體。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-914">Independent Security Vendors are individuals and organizations who develop, market and sell software that runs on third-party software and hardware platforms.</span></span>

### <a name="iso-27001"></a><span data-ttu-id="e5d2c-915">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="e5d2c-915">ISO 27001</span></span>

<span data-ttu-id="e5d2c-916">組織中的所有技術控制措施的資訊安全性管理系統規格架構。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-916">An information security management system specification framework for all technical controls in an organizations risk management policies and procedures processes.</span></span>

### <a name="lfi"></a><span data-ttu-id="e5d2c-917">LFI</span><span class="sxs-lookup"><span data-stu-id="e5d2c-917">LFI</span></span>

<span data-ttu-id="e5d2c-918">*本機檔包含* 可讓攻擊者透過網頁瀏覽器在伺服器上包含檔案。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-918">*Local File Inclusion* allows an attacker to include files on a server through the web browser.</span></span>

### <a name="nist"></a><span data-ttu-id="e5d2c-919">Nist</span><span class="sxs-lookup"><span data-stu-id="e5d2c-919">NIST</span></span>

<span data-ttu-id="e5d2c-920">*國家安全局* 的國家標準 (NIST) 中，美國 Commerce 的非規章機關為我們提供的私營部門組織提供指導，以評估和核准其阻止、偵測及回應網路攻擊的能力。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-920">The *National Institute of Standards* (NIST), a non-regulatory agency of the U.S. Department of Commerce  provides guidance for private sector organizations in the US to assess and approve their ability to prevent, detect, and respond to cyber attacks.</span></span>

### <a name="non-significant-changes"></a><span data-ttu-id="e5d2c-921">非重大變更</span><span class="sxs-lookup"><span data-stu-id="e5d2c-921">Non-Significant changes</span></span>

* <span data-ttu-id="e5d2c-922">次要錯誤修正。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-922">Minor Bug fixes.</span></span>
* <span data-ttu-id="e5d2c-923">次要效能增強。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-923">Minor performance improvements.</span></span>
* <span data-ttu-id="e5d2c-924">作業系統/文件庫/用戶端與伺服器應用程式。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-924">Operating systems/libraries/client and server application patches.</span></span>

### <a name="ocsp"></a><span data-ttu-id="e5d2c-925">OCSP</span><span class="sxs-lookup"><span data-stu-id="e5d2c-925">OCSP</span></span>

<span data-ttu-id="e5d2c-926">*線上憑證狀態通訊協定* 是用來檢查 x.509 數位憑證的吊銷狀態。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-926">*Online Certificate Status Protocol* is used to check the revocation status of X.509 digital certificates.</span></span>

### <a name="oii"></a><span data-ttu-id="e5d2c-927">OII</span><span class="sxs-lookup"><span data-stu-id="e5d2c-927">OII</span></span>

<span data-ttu-id="e5d2c-928">*組織識別資訊*。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-928">*Organizational identifiable information*.</span></span>

### <a name="owasp"></a><span data-ttu-id="e5d2c-929">OWASP</span><span class="sxs-lookup"><span data-stu-id="e5d2c-929">OWASP</span></span>

<span data-ttu-id="e5d2c-930">*開啟 Web 應用程式安全性 Project*。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-930">*Open Web Application Security Project*.</span></span>

### <a name="pci-dss"></a><span data-ttu-id="e5d2c-931">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="e5d2c-931">PCI DSS</span></span>

<span data-ttu-id="e5d2c-932">*支付卡行業資料安全性標準*-維護全球持卡人資料之安全性標準的組織。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-932">*Payment Card Industry Data Security Standard*, an organization that maintains standards for the safety of cardholder data worldwide.</span></span>

### <a name="pen-testing"></a><span data-ttu-id="e5d2c-933">畫筆測試</span><span class="sxs-lookup"><span data-stu-id="e5d2c-933">Pen testing</span></span>

<span data-ttu-id="e5d2c-934">*滲透測試* 是一種測試 web 應用程式的方法，它會類比惡意攻擊，以找出攻擊者可能會利用的安全性弱點。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-934">*Penetration testing* is a method of testing a web app by simulating malicious attacks to find security vulnerabilities that an attacker could exploit.</span></span>

### <a name="saml"></a><span data-ttu-id="e5d2c-935">Saml</span><span class="sxs-lookup"><span data-stu-id="e5d2c-935">SAML</span></span>

<span data-ttu-id="e5d2c-936">*安全性聲明標記語言* 是一種開放的標準，用來交換使用者、身分識別提供者和服務提供者之間的驗證和授權資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-936">*Security Assertion Markup Language* is s an open standard for exchanging authentication and authorization data between the user, the identity provider and the service provider.</span></span>

### <a name="sensitive-data"></a><span data-ttu-id="e5d2c-937">機密資料</span><span class="sxs-lookup"><span data-stu-id="e5d2c-937">Sensitive Data</span></span>

* <span data-ttu-id="e5d2c-938">存取控制資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-938">Access control data.</span></span>
* <span data-ttu-id="e5d2c-939">客戶內容。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-939">Customer content.</span></span>
* <span data-ttu-id="e5d2c-940">使用者身分識別資訊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-940">End-user identity information.</span></span>
* <span data-ttu-id="e5d2c-941">支援資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-941">Support data.</span></span>
* <span data-ttu-id="e5d2c-942">公用個人資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-942">Public personal data.</span></span>
* <span data-ttu-id="e5d2c-943">使用者 pseudonymous 資訊。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-943">End-user pseudonymous information.</span></span>

### <a name="significant-changes"></a><span data-ttu-id="e5d2c-944">重大變更</span><span class="sxs-lookup"><span data-stu-id="e5d2c-944">Significant changes</span></span>

* <span data-ttu-id="e5d2c-945">主控環境的重新安置。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-945">Relocation of the hosting environment.</span></span>
* <span data-ttu-id="e5d2c-946">支援基礎結構的主要升級;例如，實施新的防火牆，主要升級至正面服務等等。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-946">Major upgrades to the supporting infrastructure; for example, implementation of a new firewall, major upgrades to front facing services, etc.</span></span>
* <span data-ttu-id="e5d2c-947">您的應用程式新增功能和/or 擴充功能。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-947">Addition of capabilities and /or extensions to your app.</span></span>
* <span data-ttu-id="e5d2c-948">更新您的應用程式，以捕獲其他的敏感性資料。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-948">Updates to your app that capture additional sensitive Data.</span></span>
* <span data-ttu-id="e5d2c-949">對應用程式的資料流程或授權模型所做的變更</span><span class="sxs-lookup"><span data-stu-id="e5d2c-949">Changes to your app's data flows or authorization models</span></span>
* <span data-ttu-id="e5d2c-950">加入 API 端點或 API 端點函數。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-950">Addition of API endpoints or API endpoint functions.</span></span>

### <a name="soc-2"></a><span data-ttu-id="e5d2c-951">SOC 2</span><span class="sxs-lookup"><span data-stu-id="e5d2c-951">SOC 2</span></span>

<span data-ttu-id="e5d2c-952">*服務組織控制 2*：由五個信任服務原則組成的技術審核程式，可確保服務提供者安全地管理組織之用戶端的資料與隱私權。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-952">*Service Organization Control 2*, a technical auditing procedure comprised of five Trust Service Principles to ensure that service providers securely manage the data and privacy for an organization's clients.</span></span>

### <a name="ssl"></a><span data-ttu-id="e5d2c-953">Ssl</span><span class="sxs-lookup"><span data-stu-id="e5d2c-953">SSL</span></span>

<span data-ttu-id="e5d2c-954">*安全通訊端層*。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-954">*Secure Sockets Layer*.</span></span>

### <a name="tls"></a><span data-ttu-id="e5d2c-955">TLS</span><span class="sxs-lookup"><span data-stu-id="e5d2c-955">TLS</span></span>

<span data-ttu-id="e5d2c-956">*傳輸層安全性*。</span><span class="sxs-lookup"><span data-stu-id="e5d2c-956">*Transport Layer Security*.</span></span>
