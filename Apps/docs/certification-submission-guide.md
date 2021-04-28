---
ms.author: oromalle
title: Microsoft 365 認證提交指南
author: orionomalley
description: Microsoft 365 認證提交指南精細查看
keywords: 應用程式認證團隊 Microsoft 365 安全性符合性 m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/28/2021
ms.locfileid: "52070925"
---
# <a name="microsoft-365-certification-submission-guide"></a><span data-ttu-id="d019f-104">Microsoft 365 認證提交指南</span><span class="sxs-lookup"><span data-stu-id="d019f-104">Microsoft 365 Certification Submission Guide</span></span>

<span data-ttu-id="d019f-105">**本文內容：**</span><span class="sxs-lookup"><span data-stu-id="d019f-105">**In this article:**</span></span>
- [<span data-ttu-id="d019f-106">簡介</span><span class="sxs-lookup"><span data-stu-id="d019f-106">Introduction</span></span>](#introduction)
- [<span data-ttu-id="d019f-107">必要條件</span><span class="sxs-lookup"><span data-stu-id="d019f-107">Prerequisites</span></span>](#prerequisites) 
- [<span data-ttu-id="d019f-108">Microsoft 365 認證規格更新</span><span class="sxs-lookup"><span data-stu-id="d019f-108">Microsoft 365 Certification Specification Updates</span></span>](#microsoft-365-certification-specification-updates)
- [<span data-ttu-id="d019f-109">認證範圍</span><span class="sxs-lookup"><span data-stu-id="d019f-109">Certification Scope</span></span>](#certification-scope)
- [<span data-ttu-id="d019f-110">認證程式</span><span class="sxs-lookup"><span data-stu-id="d019f-110">Certification Process</span></span>](#certification-process)
- [<span data-ttu-id="d019f-111">規範證據</span><span class="sxs-lookup"><span data-stu-id="d019f-111">Compliance Evidence</span></span>](#compliance-evidence) 
- [<span data-ttu-id="d019f-112">初始檔提交</span><span class="sxs-lookup"><span data-stu-id="d019f-112">Initial Document submission</span></span>](#initial-document-submission) 
- [<span data-ttu-id="d019f-113">證據收集和評估活動</span><span class="sxs-lookup"><span data-stu-id="d019f-113">Evidence Collection and Assessment Activities</span></span>](#evidence-collection-and-assessment-activities)
- [<span data-ttu-id="d019f-114">認證準則</span><span class="sxs-lookup"><span data-stu-id="d019f-114">Certification Criteria</span></span>](#app-certification-criteria)
- [<span data-ttu-id="d019f-115">Application Security</span><span class="sxs-lookup"><span data-stu-id="d019f-115">Application Security</span></span>](#application-security)
- [<span data-ttu-id="d019f-116">運作安全性</span><span class="sxs-lookup"><span data-stu-id="d019f-116">Operational Security</span></span>](#operational-security) 
- [<span data-ttu-id="d019f-117">資料處理安全性和隱私權</span><span class="sxs-lookup"><span data-stu-id="d019f-117">Data Handling Security and Privacy</span></span>](#data-handling-security-and-privacy)
- [<span data-ttu-id="d019f-118">選用的外部規範框架審查</span><span class="sxs-lookup"><span data-stu-id="d019f-118">Optional External Compliance Frameworks Review</span></span>](#optional-external-compliance-frameworks-review)
- [<span data-ttu-id="d019f-119">附錄 A</span><span class="sxs-lookup"><span data-stu-id="d019f-119">Appendix A</span></span>](#appendix-a)
- [<span data-ttu-id="d019f-120">附錄 B</span><span class="sxs-lookup"><span data-stu-id="d019f-120">Appendix B</span></span>](#appendix-b) 
- [<span data-ttu-id="d019f-121">附錄 C</span><span class="sxs-lookup"><span data-stu-id="d019f-121">Appendix C</span></span>](#appendix-c) 
- [<span data-ttu-id="d019f-122">附錄 D</span><span class="sxs-lookup"><span data-stu-id="d019f-122">Appendix D</span></span>](#appendix-d) 
- [<span data-ttu-id="d019f-123">附錄 E</span><span class="sxs-lookup"><span data-stu-id="d019f-123">Appendix E</span></span>](#appendix-e) 
- [<span data-ttu-id="d019f-124">附錄 F</span><span class="sxs-lookup"><span data-stu-id="d019f-124">Appendix F</span></span>](#appendix-f) 
- [<span data-ttu-id="d019f-125">附錄 G </span><span class="sxs-lookup"><span data-stu-id="d019f-125">Appendix G </span></span>](#appendix-g)
- [<span data-ttu-id="d019f-126">深入了解</span><span class="sxs-lookup"><span data-stu-id="d019f-126">Learn more</span></span>](#learn-more) 
- [<span data-ttu-id="d019f-127">詞彙</span><span class="sxs-lookup"><span data-stu-id="d019f-127">Glossary</span></span>](#glossary) 


## <a name="introduction"></a><span data-ttu-id="d019f-128">簡介</span><span class="sxs-lookup"><span data-stu-id="d019f-128">Introduction</span></span>

<span data-ttu-id="d019f-129">Microsoft 365 應用程式相容性計畫的一部分，當您將協力廠商開發人員應用程式/增益集整合至 Microsoft 365 平臺時，Microsoft 365 憑證會為企業組織提供保證及保護的安全性。</span><span class="sxs-lookup"><span data-stu-id="d019f-129">Part of the Microsoft 365 App Compliance program, the Microsoft 365 Certification offers assurance and confidence to enterprise organizations that data and privacy are adequately secured and protected when integrating third-party developer apps/add-ins into the Microsoft 365 platform.</span></span> <span data-ttu-id="d019f-130">透過驗證的應用程式和增益集會在整個 Microsoft 365 生態系統中指定為 **microsoft 365 認證** 。</span><span class="sxs-lookup"><span data-stu-id="d019f-130">Applications and add-ins that pass validation will be designated **Microsoft 365 Certified** throughout the Microsoft 365 ecosystem.</span></span> 

<span data-ttu-id="d019f-131">加入 Microsoft 365 認證計畫後，您就會同意這些補充條款，並遵循任何365適用于 microsoft Corporation ( "Microsoft"、"我們"、"us" 或 "我們" ) 的隨附檔。</span><span class="sxs-lookup"><span data-stu-id="d019f-131">By participating in the Microsoft 365 Certification  program, you are agreeing to these supplemental terms and to comply with any accompanying documentation that applies to your participation in the Microsoft 365 Certification program with Microsoft Corporation ("Microsoft", "we", "us",  or "our").</span></span> <span data-ttu-id="d019f-132">您表示並保證我們有權代表您自己、公司和/或其他實體接受這些 Microsoft 365 認證補充條款（如適用）。</span><span class="sxs-lookup"><span data-stu-id="d019f-132">You represent and warrant to us that you have the authority to accept these Microsoft 365 Certification supplemental terms on behalf of yourself, a company, and/or other entity, as applicable.</span></span> <span data-ttu-id="d019f-133">我們隨時可能會變更、修改或終止這些補充字詞。</span><span class="sxs-lookup"><span data-stu-id="d019f-133">We may change, amend or terminate these supplemental terms at any time.</span></span> <span data-ttu-id="d019f-134">在任何變更或修正之後，您繼續參與 Microsoft 365 認證計畫，表示您同意新的附加條款。</span><span class="sxs-lookup"><span data-stu-id="d019f-134">Your continued participation in the Microsoft 365 Certification program after any change or amendment means you agree to the new supplemental terms.</span></span> <span data-ttu-id="d019f-135">如果您不同意新的附加條款，或是我們終止這些補充條款，您必須停止參與 Microsoft 365 認證計畫。</span><span class="sxs-lookup"><span data-stu-id="d019f-135">If you do not agree to the new supplemental terms or if we terminate these supplemental terms, you must stop participating in the Microsoft 365 Certification program.</span></span>

<span data-ttu-id="d019f-136">本檔的目標是 Isv (獨立軟體廠商) 提供 Microsoft 365 認證程式的必要資訊、啟動程式的必要條件，以及 Isv 必須具備之特定安全性控制措施的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-136">This document is aimed at ISVs (Independent Software Vendors) to provide information on the Microsoft 365 Certification process, prerequisites to starting the process and details of specific security controls that ISVs must have in place.</span></span>  <span data-ttu-id="d019f-137">Microsoft 365 應用程式規範計畫的一般資訊，可以在 Microsoft 365 應用程式規範方案 [頁面](https://docs.microsoft.com/microsoft-365-app-certification/overview)上找到。</span><span class="sxs-lookup"><span data-stu-id="d019f-137">General information of the Microsoft 365 App Compliance program can be found under the Microsoft 365 App Compliance program [page](https://docs.microsoft.com/microsoft-365-app-certification/overview).</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="d019f-138">目前 Microsoft 365 的認證有限：</span><span class="sxs-lookup"><span data-stu-id="d019f-138">Currently, Microsoft 365 Certification is limited:</span></span>
>* <span data-ttu-id="d019f-139">Microsoft 小組應用程式 (的索引標籤、Bot 等等 ) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-139">Microsoft Teams applications (Tabs, Bots, etc.) .</span></span>
>* <span data-ttu-id="d019f-140">Sharepoint 應用程式/增益集</span><span class="sxs-lookup"><span data-stu-id="d019f-140">Sharepoint Apps/Add-ins</span></span>
>* <span data-ttu-id="d019f-141">Office 增益集 (Word、Excel、PowerPoint、Outlook、Project、OneNote) </span><span class="sxs-lookup"><span data-stu-id="d019f-141">Office Add-ins (Word, Excel, PowerPoint, Outlook, Project, OneNote)</span></span>

## <a name="prerequisites"></a><span data-ttu-id="d019f-142">必要條件</span><span class="sxs-lookup"><span data-stu-id="d019f-142">Prerequisites</span></span>

### <a name="publisher-attestation"></a><span data-ttu-id="d019f-143">發行者證明</span><span class="sxs-lookup"><span data-stu-id="d019f-143">Publisher Attestation</span></span>

<span data-ttu-id="d019f-144">在獎勵 Microsoft 365 認證程式之前，您必須已完成發行者證明。</span><span class="sxs-lookup"><span data-stu-id="d019f-144">Before being awarded the Microsoft 365 Certification process you must have completed Publisher Attestation.</span></span> <span data-ttu-id="d019f-145">不過，您可以在完成發行者證明之前，先啟動 Microsoft 365 認證程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-145">However, you may start the Microsoft 365 Certification process prior to completing Publisher Attestation.</span></span>  

### <a name="read-the-microsoft-365-certification-specification"></a><span data-ttu-id="d019f-146">閱讀 Microsoft 365 證書規格</span><span class="sxs-lookup"><span data-stu-id="d019f-146">Read the Microsoft 365 Certification Specification</span></span>

<span data-ttu-id="d019f-147">Microsoft 建議所有 Isv (獨立軟體廠商) 閱讀此 Microsoft 365 的憑證規格，以確保範圍內環境和應用程式/增益集符合所有適用的控制項。</span><span class="sxs-lookup"><span data-stu-id="d019f-147">Microsoft recommends all ISVs (Independent Software Vendor) to read this Microsoft 365 Certification Specification in its entirety to ensure all applicable controls are being met by the in-scope environment and the app/add-in.</span></span> <span data-ttu-id="d019f-148">這會協助確保順利進行的評估處理常式。</span><span class="sxs-lookup"><span data-stu-id="d019f-148">This will help ensure a smooth assessment process.</span></span>

## <a name="microsoft-365-certification-specification-updates"></a><span data-ttu-id="d019f-149">Microsoft 365 認證規格更新</span><span class="sxs-lookup"><span data-stu-id="d019f-149">Microsoft 365 Certification Specification Updates</span></span> 

<span data-ttu-id="d019f-150">大約每隔六到十二個月就會預見 Microsoft 365 認證規格的更新。</span><span class="sxs-lookup"><span data-stu-id="d019f-150">Updates to the Microsoft 365 Certification specification are anticipated approximately every six to twelve months.</span></span> <span data-ttu-id="d019f-151">這些更新可能會引入新的目標安全性網域和/或安全性控制。</span><span class="sxs-lookup"><span data-stu-id="d019f-151">These updates might introduce new target security domains and / or security controls.</span></span> <span data-ttu-id="d019f-152">更新會根據開發人員的意見反應、對威脅環境所做的變更，以及在成熟時提升程式的安全性基準。</span><span class="sxs-lookup"><span data-stu-id="d019f-152">Updates will be based on developer feedback, changes to the threat landscape, and to increase the security baseline of the program as it matures.</span></span> 

<span data-ttu-id="d019f-153">已啟動 Microsoft 365 認證評估的 Isv 可以繼續使用評估開始時有效的 Microsoft 365 證書規格版本進行評估。</span><span class="sxs-lookup"><span data-stu-id="d019f-153">ISVs that have already started the Microsoft 365 Certification assessment can continue the assessment with the version of the Microsoft 365 Certification Specification that was valid when the assessment was started.</span></span> <span data-ttu-id="d019f-154">所有新送出的報送（包括年度 recertification）都會針對發行的版本進行評估。</span><span class="sxs-lookup"><span data-stu-id="d019f-154">All new submissions, including annual recertification, will be required to be assessed against the version published.</span></span>

> [!NOTE]
> <span data-ttu-id="d019f-155">您不需要遵循此 Microsoft 365 憑證規格中的所有控制項，即可獎勵憑證。</span><span class="sxs-lookup"><span data-stu-id="d019f-155">You are not required to comply with all the controls within this Microsoft 365 Certification Specification to be awarded a certification.</span></span> <span data-ttu-id="d019f-156">不過，傳遞的臨界值 (，將不會在此 Microsoft 365 憑證規格中所討論的每個安全性網域) 就地公開。</span><span class="sxs-lookup"><span data-stu-id="d019f-156">However, passing thresholds (which will not be disclosed) are in place for each of the security domains discussed within this Microsoft 365 Certification Specification.</span></span> <span data-ttu-id="d019f-157">有些控制項會 classed 為 "**Hard Fail**"，也就是說，缺乏這些安全性控制會導致評估失敗。</span><span class="sxs-lookup"><span data-stu-id="d019f-157">Some controls will be classed as a ‘**Hard Fail**’ which means the lack of these security controls will result in a failed assessment.</span></span> 

## <a name="certification-scope"></a><span data-ttu-id="d019f-158">認證範圍</span><span class="sxs-lookup"><span data-stu-id="d019f-158">Certification Scope</span></span>

<span data-ttu-id="d019f-159">**範圍內環境** 是支援應用程式/增益集程式碼的傳遞，並支援應用程式/增益集可能會進行通訊的任何後端系統的環境。</span><span class="sxs-lookup"><span data-stu-id="d019f-159">The **in-scope environment** is the environment that supports delivery of the app/add-in code and supports any backend systems that the app/add-in may be communicating with.</span></span> <span data-ttu-id="d019f-160">除非有足夠的分割，而且連接至環境不會影響範圍內環境的安全性，否則任何其他連接至的環境也會包含在範圍內。</span><span class="sxs-lookup"><span data-stu-id="d019f-160">Any additional connected-to environments will also be included in scope unless adequate segmentation is in place AND the connected-to environments cannot impact the security of the in-scope environment.</span></span> <span data-ttu-id="d019f-161">任何嚴重損壞復原環境也必須包含在評估範圍內，因為在主要環境中，fulfil 服務需要任何的環境。</span><span class="sxs-lookup"><span data-stu-id="d019f-161">Any disaster recovery environments will also need to be included within the scope of the assessment as these environments would be required to fulfil the service should anything happen to the primary environment.</span></span>  <span data-ttu-id="d019f-162">術語  **範圍內系統元件**   參考範圍內環境中所使用的 **所有** 裝置和系統。</span><span class="sxs-lookup"><span data-stu-id="d019f-162">The term  **in-scope system components** reference **ALL** devices and systems that are used within the in-scope environment.</span></span> <span data-ttu-id="d019f-163">範圍內的元件包括（但不限於）：</span><span class="sxs-lookup"><span data-stu-id="d019f-163">In-scope components include, but are not limited to:</span></span>
* <span data-ttu-id="d019f-164">Web 應用程式 (s) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-164">The web application(s).</span></span>
* <span data-ttu-id="d019f-165">伺服器。</span><span class="sxs-lookup"><span data-stu-id="d019f-165">Servers.</span></span>
* <span data-ttu-id="d019f-166">防火牆 (或同等) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-166">Firewalls (or equivalent).</span></span>
* <span data-ttu-id="d019f-167">開關。</span><span class="sxs-lookup"><span data-stu-id="d019f-167">Switches.</span></span>
* <span data-ttu-id="d019f-168">負載平衡器。</span><span class="sxs-lookup"><span data-stu-id="d019f-168">Load balancers.</span></span>
* <span data-ttu-id="d019f-169">虛擬基礎結構。</span><span class="sxs-lookup"><span data-stu-id="d019f-169">Virtual infrastructure.</span></span>
* <span data-ttu-id="d019f-170">雲端提供者 web 管理入口網站</span><span class="sxs-lookup"><span data-stu-id="d019f-170">Cloud provider web management portals</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="d019f-171">在範圍內環境中，必須要有 DMZ，且應用程式/增益集的支援環境必須從內部商務系統和公司環境中細分，因此只會將評估活動的範圍限制為僅限範圍內系統。</span><span class="sxs-lookup"><span data-stu-id="d019f-171">The in-scope environment, must have a DMZ and the supporting environment of the app/add-in must be segmented from the internal business systems and corporate environments thus limiting the scope of the assessment activities to the in-scope systems only.</span></span> <span data-ttu-id="d019f-172">憑證分析員會在評估過程中驗證分割技術，以及審查滲透測試報告，該報告應該包含測試以驗證所使用之任何分割技術的有效性。</span><span class="sxs-lookup"><span data-stu-id="d019f-172">Certification analysts will validate segmentation techniques during the assessment along with reviewing penetration testing reports which should have included testing to validate the effectiveness of any segmentation techniques in use.</span></span>

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a><span data-ttu-id="d019f-173">基礎結構即服務 (IaaS) 、平臺為服務 (PaaS) 和軟體作為服務 (SaaS) </span><span class="sxs-lookup"><span data-stu-id="d019f-173">Infrastructure as a Service (IaaS), Platform as a Service (PaaS) and Software as a Service (SaaS)</span></span> 
<span data-ttu-id="d019f-174">其中 IaaS 和/或 PaaS 用以支援應用程式或增益集程式碼傳遞的基礎結構在「審閱」下，雲端平臺提供者會負責在整個認證過程中評估的某些安全性控制。</span><span class="sxs-lookup"><span data-stu-id="d019f-174">Where IaaS and/or PaaS is used to support the infrastructure of the application or add-in code delivery under review, the Cloud platform provider will be responsible for some of the security controls assessed throughout the certification process.</span></span> <span data-ttu-id="d019f-175">因此，您必須將雲端平臺提供者針對 [](bookmark://pci-dss)   符合性 (AOC) 、ISO27001 或 [SOC 2](bookmark://soc-2)   Type II 報告等外部法規遵從性報告中的安全性最佳作法，以獨立外部驗證的安全性最佳作法，提供證書分析分析員。</span><span class="sxs-lookup"><span data-stu-id="d019f-175">Therefore, certification analysts will need to be provided with independent external verification of security best practices by the Cloud platform provider through external compliance reports such as [PCI DSS](bookmark://pci-dss) Attestation of Compliance (AOC), ISO27001 or [SOC 2](bookmark://soc-2) Type II reports.</span></span> 

<span data-ttu-id="d019f-176">附錄 F 提供根據下列部署類型及應用程式/增益集 exfiltrates M365 資料時，可能適用的安全性控制措施的詳細資料：</span><span class="sxs-lookup"><span data-stu-id="d019f-176">Appendix F provides details of what security controls will likely be applicable based on the following deployment types and based upon whether the app/add-in exfiltrates M365 data or not:</span></span> 
* <span data-ttu-id="d019f-177">ISV 主控</span><span class="sxs-lookup"><span data-stu-id="d019f-177">ISV Hosted</span></span> 
* <span data-ttu-id="d019f-178">主控 IaaS</span><span class="sxs-lookup"><span data-stu-id="d019f-178">IaaS Hosted</span></span> 
* <span data-ttu-id="d019f-179">主控 PaaS/無伺服器</span><span class="sxs-lookup"><span data-stu-id="d019f-179">PaaS/Serverless Hosted</span></span> 
* <span data-ttu-id="d019f-180">混合主控</span><span class="sxs-lookup"><span data-stu-id="d019f-180">Hybrid Hosted</span></span> 
* <span data-ttu-id="d019f-181">共用主控</span><span class="sxs-lookup"><span data-stu-id="d019f-181">Shared Hosted</span></span> 

<span data-ttu-id="d019f-182">在部署 IaaS 或 PaaS 時，您需要提供在這些部署類型中所主控的環境證據。</span><span class="sxs-lookup"><span data-stu-id="d019f-182">Where IaaS or PaaS is deployed, you will need to provide evidence of the environment being hosted within these deployment types.</span></span>

### <a name="sampling"></a><span data-ttu-id="d019f-183">採樣</span><span class="sxs-lookup"><span data-stu-id="d019f-183">Sampling</span></span>

<span data-ttu-id="d019f-184">要求憑證評估的要求應該是以範圍內系統元件的範例為基礎，以考慮不同的作業系統、裝置的主要功能，以及不同的裝置類型。</span><span class="sxs-lookup"><span data-stu-id="d019f-184">Requests for evidence in support of the certification assessment should be based on a sample of the in-scope system components in consideration of different operating systems, primary function of the device, and different device types.</span></span> <span data-ttu-id="d019f-185">在認證程式開始時，會選取適當的範例。</span><span class="sxs-lookup"><span data-stu-id="d019f-185">A suitable sample will be selected at the start of the certification process.</span></span> <span data-ttu-id="d019f-186">下表應用作參考樣本大小的指南：</span><span class="sxs-lookup"><span data-stu-id="d019f-186">The following table should be used as a guide on what the sample size may be:</span></span>

|<span data-ttu-id="d019f-187">人口大小</span><span class="sxs-lookup"><span data-stu-id="d019f-187">Population Size</span></span>              | <span data-ttu-id="d019f-188">範例</span><span class="sxs-lookup"><span data-stu-id="d019f-188">Sample</span></span>                  |
|---------------------------- |-------------------------|
|<span data-ttu-id="d019f-189"><5</span><span class="sxs-lookup"><span data-stu-id="d019f-189"><5</span></span>|<span data-ttu-id="d019f-190">1</span><span class="sxs-lookup"><span data-stu-id="d019f-190">1</span></span>|
|<span data-ttu-id="d019f-191">>5 & <10</span><span class="sxs-lookup"><span data-stu-id="d019f-191">>5 & <10</span></span>|<span data-ttu-id="d019f-192">第</span><span class="sxs-lookup"><span data-stu-id="d019f-192">2</span></span>|
|<span data-ttu-id="d019f-193">>9 & <25</span><span class="sxs-lookup"><span data-stu-id="d019f-193">>9 & <25</span></span>|<span data-ttu-id="d019f-194">個</span><span class="sxs-lookup"><span data-stu-id="d019f-194">3</span></span>|
|<span data-ttu-id="d019f-195">>24</span><span class="sxs-lookup"><span data-stu-id="d019f-195">>24</span></span>|<span data-ttu-id="d019f-196">4 </span><span class="sxs-lookup"><span data-stu-id="d019f-196">4</span></span>|

> [!NOTE]
><span data-ttu-id="d019f-197">如果在初始範例中所包含的裝置之間識別差異，則在評估期間可能會增加範例大小。</span><span class="sxs-lookup"><span data-stu-id="d019f-197">If discrepancies are identified between devices included within the initial sample, the sample size may be increased during the assessment.</span></span> 

## <a name="certification-process"></a><span data-ttu-id="d019f-198">認證程式</span><span class="sxs-lookup"><span data-stu-id="d019f-198">Certification Process</span></span>

<span data-ttu-id="d019f-199">開始認證程式之前，您需要成功啟動或完成發行者證明。</span><span class="sxs-lookup"><span data-stu-id="d019f-199">Before starting the certification process, you would need to have successfully started or completed your Publisher Attestation.</span></span> <span data-ttu-id="d019f-200">您可以使用證明回應，以支援 Microsoft 365 認證程式，並依下列方式繼續：</span><span class="sxs-lookup"><span data-stu-id="d019f-200">Your attestation responses will be used in support of the Microsoft 365 Certification process and proceeds as follows:</span></span> 

1. <span data-ttu-id="d019f-201">檢查您的發行者證明檔，以確保與您目前的環境一致</span><span class="sxs-lookup"><span data-stu-id="d019f-201">Review your Publisher Attestation documentation to ensure alignment with your current environment</span></span> 
2. <span data-ttu-id="d019f-202">透過電子郵件傳送 Microsoft 365 認證的要求 <AppCert@microsoft.com></span><span class="sxs-lookup"><span data-stu-id="d019f-202">Request to progress to the Microsoft 365 Certification by emailing <AppCert@microsoft.com></span></span> 
3. <span data-ttu-id="d019f-203">認證分析員會在開始 Microsoft 365 認證程式之前開啟一個對話方塊</span><span class="sxs-lookup"><span data-stu-id="d019f-203">Certification analysts will open a dialogue before starting the Microsoft 365 Certification process</span></span>   
4. <span data-ttu-id="d019f-204">提交您的 [初始檔提交](#initial-document-submission)</span><span class="sxs-lookup"><span data-stu-id="d019f-204">Submit your [Initial Document Submission](#initial-document-submission)</span></span>
5. <span data-ttu-id="d019f-205">認證分析員會提供必要證據的控制項清單，該清單正式啟動 Microsoft 365 證書處理常式</span><span class="sxs-lookup"><span data-stu-id="d019f-205">Certification analyst will provide a listing of controls for which evidence is required, which formally starts the Microsoft 365 Certification process</span></span>
6. <span data-ttu-id="d019f-206">提交證據，表明所有範圍內的 Microsoft 365 證書控制都已符合60一天的範圍，以完成 Microsoft 365 認證</span><span class="sxs-lookup"><span data-stu-id="d019f-206">Submit evidence that demonstrates that all in-scope Microsoft 365 Certification controls have been met within a 60-day window to complete Microsoft 365 Certification</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="d019f-207">**提交時間範圍：** 預計平均評估程式應該需要15天，但前提是您可以及時回應證據要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-207">**Submission time frame:** It is anticipated that on average the assessment process should take 15 days, provided you are able to respond to evidence requests within a timely manner.</span></span> <span data-ttu-id="d019f-208">Microsoft 建議您確定已讀取此認證提交指南，並且確信您可以符合其內所設定的控制措施，而且您可以在開始認證程式之前提供足夠的證據。</span><span class="sxs-lookup"><span data-stu-id="d019f-208">Microsoft recommends that you ensure this certification submission guide has been read and be confident that you can meet the controls set out within it, and you can provide enough evidence before starting the certification process.</span></span> <span data-ttu-id="d019f-209">在啟動認證程式時，最多可以有60天的時間來完成評估，否則已經收集的證據會變成陳舊。</span><span class="sxs-lookup"><span data-stu-id="d019f-209">Upon starting the certification process, a maximum of 60 days is permitted to complete the assessment, otherwise evidence already collected becomes stale.</span></span> <span data-ttu-id="d019f-210">如果在60天的時段後，就不會達到成功的評估，提交將會失敗，且必須重新開始進行處理。</span><span class="sxs-lookup"><span data-stu-id="d019f-210">If, after the 60-day time-period, a successful assessment is not reached, the submission will be issued a fail and the process must start again.</span></span> <span data-ttu-id="d019f-211">若由於無法符合 Microsoft 365 憑證規格，或是已到達60一天的時間內，但未提供足夠的證據，所以 Microsoft 不會公開失敗的結果。</span><span class="sxs-lookup"><span data-stu-id="d019f-211">If a fail is issued due to failing to meet the Microsoft 365 Certification Specification or because the 60-day time-period is reached and enough evidence is not provided, failing results will not be made public by Microsoft.</span></span> 

## <a name="compliance-evidence"></a><span data-ttu-id="d019f-212">規範證據</span><span class="sxs-lookup"><span data-stu-id="d019f-212">Compliance Evidence</span></span>

<span data-ttu-id="d019f-213">雖然這不是必要的，但如果您目前與其他外部安全性架構相容，您可以選擇使用這些認證，以滿足一些 Microsoft 365 認證控制項。</span><span class="sxs-lookup"><span data-stu-id="d019f-213">Although it is not required, if you are currently in compliance with other external security frameworks, you can elect to use these certifications to satisfy some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="d019f-214">憑證分析員會檢查任何支援的外部安全性框架的範圍和安全性控制範圍，以判斷哪些控制項可以從 Microsoft 365 認證評估中排除，提供外部安全性框架的範圍包括 Microsoft 365 認證評估的範圍內環境。</span><span class="sxs-lookup"><span data-stu-id="d019f-214">Certification analysts will review the scope and security control coverage of any supported external security frameworks to determine which controls can be excluded from the Microsoft 365 Certification assessment, providing the scope of the external security frameworks include the in-scope environments for the Microsoft 365 Certification assessment.</span></span> 

<span data-ttu-id="d019f-215">憑證分析員會嘗試將現有的外部安全性框架與 Microsoft 365 憑證規格對齊。</span><span class="sxs-lookup"><span data-stu-id="d019f-215">Certification analysts will try to align existing external security frameworks to the Microsoft 365 Certification specification.</span></span> <span data-ttu-id="d019f-216">不過，如果支援檔無法保證 Microsoft 365 認證控制項已評估為外部安全性框架的一部分審核/評估，您將需要提供目前所說的控制項的額外證據。</span><span class="sxs-lookup"><span data-stu-id="d019f-216">However, if supporting documentation is unable to provide assurance that Microsoft 365 Certification controls were assessed as part of the external security frameworks audit/assessment you will need to provide additional evidence of the said controls being in place.</span></span> 

<span data-ttu-id="d019f-217">目前，可用於支援 Microsoft 365 認證評估的外部安全性框架包括：</span><span class="sxs-lookup"><span data-stu-id="d019f-217">Currently, the external security frameworks that can be used in support of the Microsoft 365 Certification assessment include:</span></span>

*  <span data-ttu-id="d019f-218">[Ism](#isms) /[Iec](#iec) -IS0/IEC 27001 規格</span><span class="sxs-lookup"><span data-stu-id="d019f-218">[ISMS](#isms)/[IEC](#iec) - IS0/IEC 27001 specification</span></span> 
*  [<span data-ttu-id="d019f-219">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="d019f-219">PCI DSS</span></span>](#pci-dss)
*  [<span data-ttu-id="d019f-220">SOC 2</span><span class="sxs-lookup"><span data-stu-id="d019f-220">SOC 2</span></span>](#soc-2)

<span data-ttu-id="d019f-221">檔必須充分示範 Microsoft 365 憑證的範圍內環境會包含在這些外部安全性框架的範圍內。</span><span class="sxs-lookup"><span data-stu-id="d019f-221">Documentation must adequately demonstrate that the in-scope environment for the Microsoft 365 Certification was included within the scope of these external security frameworks.</span></span> <span data-ttu-id="d019f-222">透過接受由著名的外部協力廠商公司所執行的有效憑證證據，便可驗證這些安全性框架。</span><span class="sxs-lookup"><span data-stu-id="d019f-222">Validation of these security frameworks will be fulfilled by accepting evidence of valid certifications conducted by reputable external third-party companies.</span></span> <span data-ttu-id="d019f-223">這些著名的公司必須是相關規範計畫的國際資格鑒定主體的成員。</span><span class="sxs-lookup"><span data-stu-id="d019f-223">These reputable companies must be members of international accreditation bodies for relevant compliance programs.</span></span><span data-ttu-id="d019f-224">請參閱 iso 27001 和[合格的安全性評估者](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors)的 [Iso 憑證和合規性標準](https://www.iso.org/certification.html)。) PCI DSS 的 (QSA。</span><span class="sxs-lookup"><span data-stu-id="d019f-224"> See [ISO Certification and Conformity Standards](https://www.iso.org/certification.html) for ISO 27001 and [Qualified Security Assessors](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) (QSA) for PCI DSS.</span></span> 

<span data-ttu-id="d019f-225">下表著重于此驗證程式的一部分，這是認證分析員所需的檔：</span><span class="sxs-lookup"><span data-stu-id="d019f-225">The following table highlights documentation required by certification analysts as part of this validation process:</span></span>

| <span data-ttu-id="d019f-226">**Standard**</span><span class="sxs-lookup"><span data-stu-id="d019f-226">**Standard**</span></span> | <span data-ttu-id="d019f-227">**需求**</span><span class="sxs-lookup"><span data-stu-id="d019f-227">**Requirements**</span></span> |
| ----- | ----- |
| <span data-ttu-id="d019f-228">**[ISO 27001](#iso-27001)**</span><span class="sxs-lookup"><span data-stu-id="d019f-228">**[ISO 27001](#iso-27001)**</span></span> | <span data-ttu-id="d019f-229"> (SOA) 且所發出的 ISO 27001 憑證複本是 **公開的公開** 版本。</span><span class="sxs-lookup"><span data-stu-id="d019f-229">A public facing version of the **Statement of Applicability** (SOA) and a copy of the ISO 27001 certificate issued will be required.</span></span>  <span data-ttu-id="d019f-230">SOA 會摘要您在每個114資訊安全性控制上的位置，並將用來識別 ISO 27001 憑證中的任何不滿意的控制項排除。</span><span class="sxs-lookup"><span data-stu-id="d019f-230">The SOA summarizes your position on each of the 114 information security controls and  will be used to identify if any exclusion of controls that are not satisfactorily detailed in the ISO 27001 certificate.</span></span> <span data-ttu-id="d019f-231">如果不能透過檢查 SOA 的公開版本來判斷這種情況，當 ISO 27001 將用來驗證某些 Microsoft 365 證書規格控制項時，分析者可能需要存取完整的 SOA。</span><span class="sxs-lookup"><span data-stu-id="d019f-231">If this can't be determined by reviewing the public facing version of the SOA, the analyst might need access to the full SOA if ISO 27001 will be used to validate some of the Microsoft 365 Certification Specification controls.</span></span>  <span data-ttu-id="d019f-232">除了驗證 ISO 27001 評估活動的範圍之外，分析員也會依照上述所述，確認審計公司的合法性。</span><span class="sxs-lookup"><span data-stu-id="d019f-232">In addition to validating the scope of the ISO 27001 assessment activities, the analysts will also confirm the validity of the audit company as described above.</span></span>|
|<span data-ttu-id="d019f-233">**[PCI DSS](#pci-dss)**</span><span class="sxs-lookup"><span data-stu-id="d019f-233">**[PCI DSS](#pci-dss)**</span></span>| <span data-ttu-id="d019f-234">必須提供有效 **的等級1證明規範** (AOC) 檔，才能明確識別範圍內的應用程式和系統元件。</span><span class="sxs-lookup"><span data-stu-id="d019f-234">A valid **Level 1 Attestation of Compliance** (AOC) document must be provided clearly identifying the in-scope application and system components.</span></span>  <span data-ttu-id="d019f-235">「自我評估 AOC」 **不** 會接受為會議安全性最佳作法的證據。</span><span class="sxs-lookup"><span data-stu-id="d019f-235">A self-assessment AOC **will not** be accepted as evidence of meeting security best practices.</span></span> <span data-ttu-id="d019f-236">AOC 將用來判斷哪一種 Microsoft 365 憑證規格控制已評估並確認為 PCI DSS 評估的一部分。</span><span class="sxs-lookup"><span data-stu-id="d019f-236">The AOC will be used to determine which of the Microsoft 365 Certification Specification controls have been evaluated and confirmed as part of the PCI DSS assessment.</span></span>|
|<span data-ttu-id="d019f-237">**[SOC 2](#soc-2)**</span><span class="sxs-lookup"><span data-stu-id="d019f-237">**[SOC 2](#soc-2)**</span></span>|<span data-ttu-id="d019f-238">**SOC 2 (Type I 或 TYPE II)** report 必須是目前 (于過去15個月內發行的時間，以及在過去27個月內開始的宣告時間週期) ，以當作此 Microsoft 365 認證規格內任何評估控制項的符合性。</span><span class="sxs-lookup"><span data-stu-id="d019f-238">The **SOC 2 (Type I or Type II)** report must be current (issued within the last 15 months and the declared time period started within the last 27 months) to be used as evidence of conformity with any of the assessment controls within this Microsoft 365 Certification Specification.</span></span>|


## <a name="microsoft-365-certification"></a><span data-ttu-id="d019f-239">Microsoft 365 認證</span><span class="sxs-lookup"><span data-stu-id="d019f-239">Microsoft 365 Certification</span></span>

<span data-ttu-id="d019f-240">支援的外部安全性框架可以做為會議部分 Microsoft 365 認證控制項的證據。</span><span class="sxs-lookup"><span data-stu-id="d019f-240">Supported external security frameworks can be used as evidence of meeting some of the Microsoft 365 Certification controls.</span></span> <span data-ttu-id="d019f-241">在您可以考慮使用外部安全性框架之前，認證分析員會透過上述檔中所提交的檔，檢查外部安全性架構的範圍和安全性控制範圍。</span><span class="sxs-lookup"><span data-stu-id="d019f-241">Before external security frameworks can be considered, certification analysts will review the scope and security control coverage of the external security framework using the documentation submitted above.</span></span> 

<span data-ttu-id="d019f-242">下列附錄可用於識別外部安全性架構與 Microsoft 365 憑證規格之間的潛在差距，如下所示：</span><span class="sxs-lookup"><span data-stu-id="d019f-242">The following appendixes can be used to identify where potential gaps between the external security framework and the Microsoft 365 Certification specification exist as follows:</span></span> 

|<span data-ttu-id="d019f-243">**框架**</span><span class="sxs-lookup"><span data-stu-id="d019f-243">**Framework**</span></span> | <span data-ttu-id="d019f-244">**其他考量**</span><span class="sxs-lookup"><span data-stu-id="d019f-244">**Additional considerations**</span></span> |
|-------------- | --------------------|
|<span data-ttu-id="d019f-245">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="d019f-245">ISO 27001</span></span>| <span data-ttu-id="d019f-246">[**附錄 C**](#appendix-c)：證據集合– ISO 27001 的增量。</span><span class="sxs-lookup"><span data-stu-id="d019f-246">[**Appendix C**](#appendix-c): Evidence Collection – Deltas for ISO 27001.</span></span>|
|<span data-ttu-id="d019f-247">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="d019f-247">PCI DSS</span></span> | <span data-ttu-id="d019f-248">[**附錄 D**](#appendix-d)：證據集合– PCI DSS 的增量。</span><span class="sxs-lookup"><span data-stu-id="d019f-248">[**Appendix D**](#appendix-d): Evidence Collection – Deltas for PCI DSS.</span></span>|
|<span data-ttu-id="d019f-249">SOC 2</span><span class="sxs-lookup"><span data-stu-id="d019f-249">SOC 2</span></span>| <span data-ttu-id="d019f-250">[**附錄 E**](#appendix-e)： SOC 2 的證據集合–增量。</span><span class="sxs-lookup"><span data-stu-id="d019f-250">[**Appendix E**](#appendix-e): Evidence Collection – Deltas for SOC 2.</span></span>|

> [!NOTE]
> <span data-ttu-id="d019f-251">雖然上述的外部安全性標準/框架可以提交為證據，以符合某些 Microsoft 365 認證控制項，但傳遞 Microsoft 365 認證並不表示您會成功地透過這些標準/框架進行審計。</span><span class="sxs-lookup"><span data-stu-id="d019f-251">Although the above-mentioned external security standards/frameworks can be submitted as evidence to meet some of the Microsoft 365 Certification controls, passing the Microsoft 365 Certification doesn't mean that you will successfully pass an audit against those standards/frameworks.</span></span> <span data-ttu-id="d019f-252">Microsoft 365 憑證規格只是這些安全性標準/框架的小型子集，可讓 Microsoft 取得安全狀況的保證。</span><span class="sxs-lookup"><span data-stu-id="d019f-252">The Microsoft 365 Certification Specification is only a small subset of those security standards/frameworks that allows Microsoft to gain a level of assurance in reference to your security posture.</span></span>

## <a name="initial-document-submission"></a><span data-ttu-id="d019f-253">初始檔提交</span><span class="sxs-lookup"><span data-stu-id="d019f-253">Initial document submission</span></span>

<span data-ttu-id="d019f-254">初始檔提交會協助認證分析員執行範圍，並決定評估的範圍中的內容。</span><span class="sxs-lookup"><span data-stu-id="d019f-254">The initial document submission will help certification analysts perform scoping and determine what will be in scope for your assessment.</span></span> <span data-ttu-id="d019f-255">之後，您將需要提交用於執行評估的支援檔和證據。</span><span class="sxs-lookup"><span data-stu-id="d019f-255">After which you will be required to submit supporting documentation and evidence used to carry out the assessment.</span></span> <span data-ttu-id="d019f-256">您的初始提交必須包含下列所指定的資訊：</span><span class="sxs-lookup"><span data-stu-id="d019f-256">Your initial submission must include the information specified below:</span></span>

| <span data-ttu-id="d019f-257">**檔 &nbsp; 概述**</span><span class="sxs-lookup"><span data-stu-id="d019f-257">**Documentation&nbsp;Overview**</span></span>     |   <span data-ttu-id="d019f-258">**檔詳細資料**</span><span class="sxs-lookup"><span data-stu-id="d019f-258">**Documentation Details**</span></span>  |
| -------------------------| -----------------------------|
|<span data-ttu-id="d019f-259">**應用程式/增益集描述**</span><span class="sxs-lookup"><span data-stu-id="d019f-259">**App/Add-in Description**</span></span> | <span data-ttu-id="d019f-260">App/增益集的用途及功能的描述。</span><span class="sxs-lookup"><span data-stu-id="d019f-260">A description of the app/add-in’s purpose and functionality.</span></span> <span data-ttu-id="d019f-261">這可讓認證分析分析員充分瞭解應用程式/增益集的功能及其用途。</span><span class="sxs-lookup"><span data-stu-id="d019f-261">This should provide the certification analyst with a good understanding of how the app/add-in functions and what it is intended use is</span></span>
|<span data-ttu-id="d019f-262">**滲透測試報告**</span><span class="sxs-lookup"><span data-stu-id="d019f-262">**Penetration Testing Report**</span></span> |<span data-ttu-id="d019f-263">在過去12個月內完成的滲透測試報告。</span><span class="sxs-lookup"><span data-stu-id="d019f-263">A penetration testing report completed within the last 12 months.</span></span> <span data-ttu-id="d019f-264">此報告必須包含支援部署應用程式/新增的環境，以及支援應用程式/增益集作業的任何其他環境。</span><span class="sxs-lookup"><span data-stu-id="d019f-264">This report must include the environment that supports the deployment of the app/add along with any additional environment that supports the operation of the app/add-in.</span></span> <span data-ttu-id="d019f-265">**附注：** 如果您不執行年度滲透測試，您可以選擇透過認證程式完成。</span><span class="sxs-lookup"><span data-stu-id="d019f-265">**Note:** if you do not do annual penetration testing, you can elect to have them done through the certification process.</span></span>|
|<span data-ttu-id="d019f-266">**架構圖表**</span><span class="sxs-lookup"><span data-stu-id="d019f-266">**Architecture diagrams**</span></span>|<span data-ttu-id="d019f-267">邏輯架構圖，代表應用程式/增益集的支援基礎結構的高層次概述。</span><span class="sxs-lookup"><span data-stu-id="d019f-267">A logical architecture diagram representing a high-level overview of your app's / add-in’s supporting infrastructure.</span></span> <span data-ttu-id="d019f-268">這必須包含支援應用程式/增益集的 **所有** 主控環境和支援基礎結構。</span><span class="sxs-lookup"><span data-stu-id="d019f-268">This must include **all** hosting environments and supporting infrastructure supporting the app/add-in.</span></span> <span data-ttu-id="d019f-269">此圖表必須說明環境內所有不同的支援系統元件，以協助認證分析員瞭解範圍內的系統，並協助判斷抽樣。</span><span class="sxs-lookup"><span data-stu-id="d019f-269">This diagram MUST depict all the different supporting system components within the environment to help certification analysts understand systems in scope and help to determine sampling.</span></span> <span data-ttu-id="d019f-270">請另外指出使用的主控環境類型;ISV 主控、IaaS、PaaS 或混合式。</span><span class="sxs-lookup"><span data-stu-id="d019f-270">Please also indicate what hosting environment type is used; ISV Hosted, IaaS, PaaS, or Hybrid.</span></span> <span data-ttu-id="d019f-271">**附注：** 在使用 SaaS 的地方，請指出用來在環境中提供支援服務的各種 SaaS 服務。</span><span class="sxs-lookup"><span data-stu-id="d019f-271">**Note:** Where SaaS is used, please indicate the various SaaS services that are used to provide the supporting services within the environment.</span></span>|
|<span data-ttu-id="d019f-272">**公開的足跡**</span><span class="sxs-lookup"><span data-stu-id="d019f-272">**Public Footprint**</span></span> | <span data-ttu-id="d019f-273">詳述支援基礎結構所使用的 **所有** 公用 IP 位址和 URLs。</span><span class="sxs-lookup"><span data-stu-id="d019f-273">Detailing **all** public IP Addresses and URLs used by the supporting infrastructure.</span></span> <span data-ttu-id="d019f-274">這必須包含為環境所指派的完整可路由 IP 範圍，除非已執行適當的分割才能分割使用中的範圍 (足夠的分割的證據) </span><span class="sxs-lookup"><span data-stu-id="d019f-274">This must include the full routable IP range allocated to the environment unless adequate segmentation has been implemented to split the range in use (adequate evidence of segmentation will be required)</span></span>|
|<span data-ttu-id="d019f-275">**資料流程圖**</span><span class="sxs-lookup"><span data-stu-id="d019f-275">**Data flow diagrams**</span></span> |<span data-ttu-id="d019f-276">詳述下列各項的流程圖：</span><span class="sxs-lookup"><span data-stu-id="d019f-276">Flow diagrams detailing the following:</span></span>
||<span data-ttu-id="d019f-277">在應用程式/增益集 (中 &#x2713; M365 資料流程，包括 [EUII](#euii) 和 [OII](#oii) ) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-277">&#x2713; M365 Data flows to and from the App / Add-in (including [EUII](#euii) and [OII](#oii) ).</span></span>|
||<span data-ttu-id="d019f-278">&#x2713; 在支援的基礎結構內 M365 資料流程 (適用于) </span><span class="sxs-lookup"><span data-stu-id="d019f-278">&#x2713; M365 Data flows within the supporting infrastructure(where applicable)</span></span>|
||<span data-ttu-id="d019f-279">&#x2713; 圖表會強調儲存的位置和資料，也就是將資料傳遞給外部協力廠商的方式 (包含哪些協力廠商) 的詳細資料，以及如何透過開放/公用網路及靜態網路傳輸來保護資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-279">&#x2713; Diagrams highlighting where and what data is stored, how data is passed to external third parties(including details of what third parties) , and how data is protected in transit over open/public networks and at rest.</span></span>|
|<span data-ttu-id="d019f-280">**API 端點詳細資料**</span><span class="sxs-lookup"><span data-stu-id="d019f-280">**API Endpoint Details**</span></span>| <span data-ttu-id="d019f-281">您的應用程式所使用之所有 API 端點的完整清單。</span><span class="sxs-lookup"><span data-stu-id="d019f-281">A complete listing of all API Endpoints used by your app.</span></span> <span data-ttu-id="d019f-282">為了協助瞭解環境範圍，請在您的環境中提供 API 端點位置。</span><span class="sxs-lookup"><span data-stu-id="d019f-282">To help understand the environment scope, provide API endpoint locations within your environment.</span></span>                                
|<span data-ttu-id="d019f-283">**Microsoft API 許可權**</span><span class="sxs-lookup"><span data-stu-id="d019f-283">**Microsoft API Permissions**</span></span>| <span data-ttu-id="d019f-284">提供檔，詳述 **所有** 與要求的應用程式/增益集一起使用之許可權的 Microsoft APIs，以及要求的許可權的理由</span><span class="sxs-lookup"><span data-stu-id="d019f-284">Provide documentation detailing **ALL** the Microsoft APIs that are used along with what permissions are being requested for the app/add-in to function along with a justification for the requested permissions</span></span>|
|<span data-ttu-id="d019f-285">**資料儲存類型**</span><span class="sxs-lookup"><span data-stu-id="d019f-285">**Data storage types**</span></span> |<span data-ttu-id="d019f-286">資料儲存與處理檔說明：</span><span class="sxs-lookup"><span data-stu-id="d019f-286">Data storage and handling documents describing:</span></span>|
||<span data-ttu-id="d019f-287">&#x2713; 您的客戶 M365 資料 [EUII](#euii) 和 [OII](#oii) 正在接收及儲存的程度</span><span class="sxs-lookup"><span data-stu-id="d019f-287">&#x2713; To what extent is your customers M365 Data [EUII](#euii) and [OII](#oii) is being received and stored</span></span>|
||<span data-ttu-id="d019f-288">&#x2713; 資料保留期間。</span><span class="sxs-lookup"><span data-stu-id="d019f-288">&#x2713; The data retention period.</span></span>|
||<span data-ttu-id="d019f-289">&#x2713; 即將捕獲客戶 M365 資料的原因。</span><span class="sxs-lookup"><span data-stu-id="d019f-289">&#x2713; Why the customer M365 Data is being captured.</span></span>|
||<span data-ttu-id="d019f-290">儲存客戶 M365 資料的 &#x2713; (應該包含在上述) 中的資料流程圖內。</span><span class="sxs-lookup"><span data-stu-id="d019f-290">&#x2713; Where customer M365 Data is stored (should be included within data flow diagrams supplied above).</span></span>|
|<span data-ttu-id="d019f-291">**合規性確認**</span><span class="sxs-lookup"><span data-stu-id="d019f-291">**Compliance confirmation**</span></span>|<span data-ttu-id="d019f-292">包含在發行者認證提交中的外部安全性框架的支援檔，或在複查 Microsoft 365 認證控制項時加以考慮。</span><span class="sxs-lookup"><span data-stu-id="d019f-292">Supporting documentation for external security frameworks included within the Publisher Attestation submission or to be considered when reviewing Microsoft 365 Certification controls.</span></span> <span data-ttu-id="d019f-293">目前支援下列三個專案：</span><span class="sxs-lookup"><span data-stu-id="d019f-293">Currently, the following three are supported:</span></span>|
||<span data-ttu-id="d019f-294"> (AOC) 的相容性 &#x2713; [PCI DSS](#pci-dss) 證明。</span><span class="sxs-lookup"><span data-stu-id="d019f-294">&#x2713; [PCI DSS](#pci-dss) Attestation of Compliance (AOC).</span></span>|
||<span data-ttu-id="d019f-295">&#x2713; [SOC 2](#soc-2) Type I/type II 報告。</span><span class="sxs-lookup"><span data-stu-id="d019f-295">&#x2713; [SOC 2](#soc-2) Type I/Type II reports.</span></span>|
||<span data-ttu-id="d019f-296">&#x2713; [ism](#isms)  /  [IEC](#iec) -1S0/IEC 27001 的適用性聲明 (SoA) 和認證。</span><span class="sxs-lookup"><span data-stu-id="d019f-296">&#x2713; [ISMS](#isms) / [IEC](#iec) - 1S0/IEC 27001 Statement of Applicability (SoA) and Certification.</span></span>|
|<span data-ttu-id="d019f-297">**Web 相依性**</span><span class="sxs-lookup"><span data-stu-id="d019f-297">**Web Dependencies**</span></span>|<span data-ttu-id="d019f-298">檔：列出使用目前執行中的應用程式/增益集所使用的所有依存關係。</span><span class="sxs-lookup"><span data-stu-id="d019f-298">Documentation listing all dependencies used by the app / add-in with the current running versions.</span></span>|
|<span data-ttu-id="d019f-299">**軟體清查**</span><span class="sxs-lookup"><span data-stu-id="d019f-299">**Software Inventory**</span></span>|<span data-ttu-id="d019f-300">最新的軟體清查，包含範圍內環境中所使用的所有軟體，以及版本。</span><span class="sxs-lookup"><span data-stu-id="d019f-300">An up-to-date software inventory which includes all software used within the in-scope environment along with the versions.</span></span>|
|<span data-ttu-id="d019f-301">**硬體清單**</span><span class="sxs-lookup"><span data-stu-id="d019f-301">**Hardware Inventory**</span></span>| <span data-ttu-id="d019f-302">支援基礎結構所使用的最新硬體清單。</span><span class="sxs-lookup"><span data-stu-id="d019f-302">An up-to-date hardware inventory used by the supporting infrastructure.</span></span> <span data-ttu-id="d019f-303">這會在執行評估階段時用於協助抽樣。</span><span class="sxs-lookup"><span data-stu-id="d019f-303">This will be used to help with sampling when performing the assessment phase.</span></span> <span data-ttu-id="d019f-304">如果您的環境包含 PaaS 提供所使用之服務的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-304">If your environment includes PaaS provide details of services consumed.</span></span>|

## <a name="evidence-collection-and-assessment-activities"></a><span data-ttu-id="d019f-305">證據收集和評估活動</span><span class="sxs-lookup"><span data-stu-id="d019f-305">Evidence Collection and Assessment Activities</span></span>

<span data-ttu-id="d019f-306">透過強大的證據收集和評估活動，認證分析師將能夠評估安全性狀態，以取得適當的資料安全性保證，並符合 Microsoft 365 的認證規格控制。</span><span class="sxs-lookup"><span data-stu-id="d019f-306">Through robust evidence collection and assessment activities, certification analysts will be able to assess your security posture to obtain an adequate level of data security assurance and adherence to the Microsoft 365 Certification Specification controls.</span></span> <span data-ttu-id="d019f-307">認證分析員會以下列方式達成此目的：</span><span class="sxs-lookup"><span data-stu-id="d019f-307">Certification analysts will achieve this as follows:</span></span> 

<span data-ttu-id="d019f-308">**證據集合**</span><span class="sxs-lookup"><span data-stu-id="d019f-308">**Evidence Collection**</span></span>

* <span data-ttu-id="d019f-309">初始檔，在上方的 [初始檔提交](#initial-document-submission) 區段中高亮顯示</span><span class="sxs-lookup"><span data-stu-id="d019f-309">Initial documentation, highlighted within the [Initial Documentation Submission](#initial-document-submission) section above</span></span> 
* <span data-ttu-id="d019f-310">原則檔</span><span class="sxs-lookup"><span data-stu-id="d019f-310">Policy documents</span></span> 
* <span data-ttu-id="d019f-311">處理檔</span><span class="sxs-lookup"><span data-stu-id="d019f-311">Process documents</span></span> 
* <span data-ttu-id="d019f-312">系統設定</span><span class="sxs-lookup"><span data-stu-id="d019f-312">System configuration settings</span></span> 
* <span data-ttu-id="d019f-313">變更票證</span><span class="sxs-lookup"><span data-stu-id="d019f-313">Change tickets</span></span> 
* <span data-ttu-id="d019f-314">變更控制項記錄</span><span class="sxs-lookup"><span data-stu-id="d019f-314">Change control records</span></span> 
* <span data-ttu-id="d019f-315">系統報告</span><span class="sxs-lookup"><span data-stu-id="d019f-315">System reports</span></span>

<span data-ttu-id="d019f-316">將使用各種方法來收集完成評估程式所需的證據。</span><span class="sxs-lookup"><span data-stu-id="d019f-316">Various methods will be used to collect the evidence necessary to complete the assessment process.</span></span>  <span data-ttu-id="d019f-317">此證據集合的格式可為：</span><span class="sxs-lookup"><span data-stu-id="d019f-317">This evidence collection may be in the form of:</span></span> 
* <span data-ttu-id="d019f-318">文件</span><span class="sxs-lookup"><span data-stu-id="d019f-318">Documents</span></span> 
* <span data-ttu-id="d019f-319">螢幕擷取畫面</span><span class="sxs-lookup"><span data-stu-id="d019f-319">Screenshots</span></span> 
* <span data-ttu-id="d019f-320">採訪</span><span class="sxs-lookup"><span data-stu-id="d019f-320">Interviews</span></span> 
* <span data-ttu-id="d019f-321">Screensharing</span><span class="sxs-lookup"><span data-stu-id="d019f-321">Screensharing</span></span> 

<span data-ttu-id="d019f-322">使用的證據集合技術會在評估程式期間決定。</span><span class="sxs-lookup"><span data-stu-id="d019f-322">The evidence collection techniques used will be determined during the assessment process.</span></span> 

<span data-ttu-id="d019f-323">**評估活動**</span><span class="sxs-lookup"><span data-stu-id="d019f-323">**Assessment Activities**</span></span>

<span data-ttu-id="d019f-324">認證分析師會檢查您提供的證據，以判斷您是否有足夠的控制此 Microsoft 365 認證規格。</span><span class="sxs-lookup"><span data-stu-id="d019f-324">Certification analysts will review evidence you provide to determine if you have adequately met controls within this Microsoft 365 Certification Specification.</span></span> 

<span data-ttu-id="d019f-325">您應該盡可能提供 [初始檔提交](#initial-document-submission)中所述的任何或所有檔，以盡可能縮短評估所需的時間   。</span><span class="sxs-lookup"><span data-stu-id="d019f-325">Where possible and to reduce the amount of time required to complete the assessment, any or all of the documentation detailed in the [Initial Documentation Submission](#initial-document-submission) should be provided in advance.</span></span>

<span data-ttu-id="d019f-326">憑證分析員會先從最初的檔提交和發行者認證資訊中檢查提供的證據，以識別適當的查詢、採樣大小，以及如以上所述取得進一步證據的需要。</span><span class="sxs-lookup"><span data-stu-id="d019f-326">Certification analysts will first review the evidence provided from the initial documentation submission and the Publisher Attestation information to identify appropriate lines of inquiry, sampling size, and the need for further evidence to be obtained as detailed above.</span></span>  <span data-ttu-id="d019f-327">憑證分析員會分析所有收集到的資訊，以在此 Microsoft 365 認證規格內，如何以及是否要為您的控制會議。</span><span class="sxs-lookup"><span data-stu-id="d019f-327">Certification analysts will analyze all information gathered to draw conclusions as to how and if you are meeting the controls within this Microsoft 365 Certification Specification.</span></span> 

## <a name="app-certification-criteria"></a><span data-ttu-id="d019f-328">應用程式認證準則</span><span class="sxs-lookup"><span data-stu-id="d019f-328">App Certification Criteria</span></span>

<span data-ttu-id="d019f-329">您的應用程式、支援基礎結構，以及支援檔將會跨下列安全網域評估：</span><span class="sxs-lookup"><span data-stu-id="d019f-329">Your app, supporting infrastructure, and supporting documentation will be assessed across the following security domains:</span></span>

1. [<span data-ttu-id="d019f-330">**Application Security**</span><span class="sxs-lookup"><span data-stu-id="d019f-330">**Application Security**</span></span>](#application-security)
1. [<span data-ttu-id="d019f-331">**運作安全性/安全部署**</span><span class="sxs-lookup"><span data-stu-id="d019f-331">**Operational Security / Secure Deployment**</span></span>](#operational-security)
1. [<span data-ttu-id="d019f-332">**資料處理安全性和隱私權**</span><span class="sxs-lookup"><span data-stu-id="d019f-332">**Data Handling Security and Privacy**</span></span>](#data-handling-security-and-privacy)
1. [<span data-ttu-id="d019f-333">**選用的外部規範架構審查**</span><span class="sxs-lookup"><span data-stu-id="d019f-333">**Optional External Compliance Framework Review**</span></span>](#optional-external-compliance-frameworks-review)

<span data-ttu-id="d019f-334">這些安全網域中的每一個都包含特定的主要控制項，包含一或多個在評估程式中評估的特定需求。</span><span class="sxs-lookup"><span data-stu-id="d019f-334">Each of these security domains include specific key controls encompassing one or more specific requirements that will be evaluated as part of the assessment process.</span></span> <span data-ttu-id="d019f-335">為了確保 Microsoft 365 的憑證包含在所有大小的開發人員上，每四個安全網域都會使用計分系統進行評估，以判斷每個網域的整體分數。</span><span class="sxs-lookup"><span data-stu-id="d019f-335">To ensure that Microsoft 365 Certification is inclusive to developers of all sizes, each of the four security domains is assessed using a scoring system to determine an overall score from each of the domains.</span></span> <span data-ttu-id="d019f-336">每個 Microsoft 365 憑證控制項的分數是在 1 (低) 和 3 (高) 之間，根據該控制項未滿足的認知風險進行分配。</span><span class="sxs-lookup"><span data-stu-id="d019f-336">Scores for each of the Microsoft 365 Certification controls are allocated between 1 (low) and 3 (high) based upon the perceived risk of that control not being met.</span></span> <span data-ttu-id="d019f-337">四個安全網域中的每一個都會將最小的百分號視為傳遞。</span><span class="sxs-lookup"><span data-stu-id="d019f-337">Each of the four security domains will have a minimum percentage mark to be deemed a pass.</span></span> <span data-ttu-id="d019f-338">此規格的某些元素包含一些自動失敗的準則：</span><span class="sxs-lookup"><span data-stu-id="d019f-338">Certain elements of this specification include some automatic fail criteria:</span></span>

- <span data-ttu-id="d019f-339">API 許可權不遵循 (PoLP) 最低許可權原則。</span><span class="sxs-lookup"><span data-stu-id="d019f-339">API permissions not following the principle of least privilege (PoLP).</span></span>  
- <span data-ttu-id="d019f-340">不需要滲透測試報告。</span><span class="sxs-lookup"><span data-stu-id="d019f-340">No penetration testing report when it is required.</span></span>
- <span data-ttu-id="d019f-341">無反惡意程式碼防護</span><span class="sxs-lookup"><span data-stu-id="d019f-341">No anti-malware defenses</span></span>
- <span data-ttu-id="d019f-342">未使用 Multi-Factor 驗證來保護系統管理存取。</span><span class="sxs-lookup"><span data-stu-id="d019f-342">Multi-Factor authentication not being used to protect administrative access.</span></span>  
- <span data-ttu-id="d019f-343">沒有修補程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-343">No patching processes.</span></span>  
- <span data-ttu-id="d019f-344">無適當的 [GDPR](#gdpr) 隱私權通知。</span><span class="sxs-lookup"><span data-stu-id="d019f-344">No suitable [GDPR](#gdpr) privacy notice.</span></span>  

## <a name="application-security"></a><span data-ttu-id="d019f-345">Application Security</span><span class="sxs-lookup"><span data-stu-id="d019f-345">Application Security</span></span>

<span data-ttu-id="d019f-346">應用程式安全性網域著重于下列三個區域：</span><span class="sxs-lookup"><span data-stu-id="d019f-346">The application security domain focuses upon the follow three areas:</span></span> 
* <span data-ttu-id="d019f-347">GraphAPI 許可權驗證</span><span class="sxs-lookup"><span data-stu-id="d019f-347">GraphAPI Permission Validation</span></span> 
* <span data-ttu-id="d019f-348">外部連線檢查</span><span class="sxs-lookup"><span data-stu-id="d019f-348">External Connectivity Checks</span></span>
* <span data-ttu-id="d019f-349">應用程式安全性測試</span><span class="sxs-lookup"><span data-stu-id="d019f-349">Application Security Testing</span></span> 

<span data-ttu-id="d019f-350">**GraphAPI 許可權驗證**</span><span class="sxs-lookup"><span data-stu-id="d019f-350">**GraphAPI Permission Validation**</span></span>

<span data-ttu-id="d019f-351">GraphAPI 許可權驗證的執行是為了驗證應用程式/增益集不會要求太好的許可權。</span><span class="sxs-lookup"><span data-stu-id="d019f-351">GraphAPI permission validation is carried out to validate the app/add-in does not request overly permissive permissions.</span></span> <span data-ttu-id="d019f-352">這是透過手動檢查要求的許可權來執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-352">This is carried out by manually checking what permissions are requested.</span></span> <span data-ttu-id="d019f-353">憑證分析員會對照發行者認證提交，以參考這些檢查，並評估所要求的存取層級，以確保符合「最低許可權」作法。</span><span class="sxs-lookup"><span data-stu-id="d019f-353">Certification analysts will cross reference these checks against the Publisher Attestation submission and evaluate the level of access being requested to ensure ‘least privilege’ practices are being met.</span></span> <span data-ttu-id="d019f-354">當憑證分析員認為未符合這些「最低許可權」做法時，認證分析員會與您展開討論，以驗證所要求之許可權的業務理由。</span><span class="sxs-lookup"><span data-stu-id="d019f-354">Where certification analysts believe these ‘least privilege’ practices are not being met, certification analysts will have an open discussion with you to validate the business justification for the permissions being requested.</span></span> <span data-ttu-id="d019f-355">在此評審期間，針對發行者證明提交的任何矛盾也會取得意見反應，使您的發行者證明得以更新。</span><span class="sxs-lookup"><span data-stu-id="d019f-355">Any discrepancies against your Publisher Attestation submission found during this review will also get feedback so your Publisher Attestation can be updated.</span></span> 

<span data-ttu-id="d019f-356">**外部連線檢查**</span><span class="sxs-lookup"><span data-stu-id="d019f-356">**External Connectivity Checks**</span></span>

<span data-ttu-id="d019f-357">在評估過程中，分析員會執行應用程式功能的輕量指導，以識別 M365 之外的連線。</span><span class="sxs-lookup"><span data-stu-id="d019f-357">As part of the assessment, an Analyst will perform a light walk through of the applications functionality to identify connections outside of M365.</span></span>  <span data-ttu-id="d019f-358">在評估期間，將會標記並討論任何未識別為 Microsoft 或直接連線至服務的連線。</span><span class="sxs-lookup"><span data-stu-id="d019f-358">Any connections which are not identified as being Microsoft or direct connections to your service will be flagged and discussed during the assessment.</span></span>

<span data-ttu-id="d019f-359">**應用程式安全性測試**</span><span class="sxs-lookup"><span data-stu-id="d019f-359">**Application Security Testing**</span></span>

<span data-ttu-id="d019f-360">在應用程式/增益集與支援環境相關聯的風險中，有足夠的複查，在應用程式/增益集的安全性中為客戶提供保證保證是必要的。</span><span class="sxs-lookup"><span data-stu-id="d019f-360">An adequate review of the risks associated with your app/add-in and supporting environment is essential in providing customers with assurance in the security of the app/add-in.</span></span> <span data-ttu-id="d019f-361">如果您的應用程式與 Microsoft 未發佈的任何服務有任何連線，則必須執行採用滲透測試形式的應用程式安全性測試。</span><span class="sxs-lookup"><span data-stu-id="d019f-361">Application security testing in the form of penetration testing MUST be carried out if your application has any connectivity to any service not published by Microsoft.</span></span> <span data-ttu-id="d019f-362">如果您的應用程式獨立運作，但沒有連接至任何非 Microsoft 服務或後端，則不需要滲透測試。</span><span class="sxs-lookup"><span data-stu-id="d019f-362">If your app operates standalone without connectivity to any non-Microsoft service or backend, then penetration testing is not required.</span></span>


### <a name="penetration-testing-scope"></a><span data-ttu-id="d019f-363">滲透測試範圍</span><span class="sxs-lookup"><span data-stu-id="d019f-363">Penetration Testing Scope</span></span>

<span data-ttu-id="d019f-364">滲透測試活動 **必須** 包含支援部署應用程式/增益集的環境 (例如，應用程式/增益集程式碼的主控位置通常是資訊清單檔案中的資源) ，以及任何支援應用程式/增益集作業的其他環境 (例如，若應用程式/增益集與 Microsoft 365) 以外的其他 web 應用程式交談。</span><span class="sxs-lookup"><span data-stu-id="d019f-364">Penetration testing activities **MUST** include the environment that supports the deployment of the app/add-in (for example; where the app/add-in code is hosted which will typically be the resource within the manifest file) along with any additional environment that supports the operation of the app/add-in (for example; if the app/add-in talks to other web applications outside of Microsoft 365).</span></span>  <span data-ttu-id="d019f-365">在定義範圍時，必須特別注意，以確保任何「連線至」系統或可能影響範圍內環境安全性的環境，也都會包含在所有滲透測試活動中。</span><span class="sxs-lookup"><span data-stu-id="d019f-365">When defining the scope, care needs to be taken to ensure that any “connected-to” systems or environments that can impact upon the security of the in-scope environment is also included within ALL penetration testing activities.</span></span> 

<span data-ttu-id="d019f-366">使用技術從其他環境分割範圍內的環境時，滲透測試活動必須驗證說出分割技術的有效性。</span><span class="sxs-lookup"><span data-stu-id="d019f-366">Where techniques are used to segment the in-scope environments from other environments, penetration testing activities MUST validate the effectiveness of said segmentation techniques.</span></span> <span data-ttu-id="d019f-367">這必須在滲透測試報告中詳細說明。</span><span class="sxs-lookup"><span data-stu-id="d019f-367">This must be detailed within the penetration testing report.</span></span> 
 

### <a name="testspecification"></a><span data-ttu-id="d019f-368">測試規格</span><span class="sxs-lookup"><span data-stu-id="d019f-368">Test Specification</span></span> 

|<span data-ttu-id="d019f-369">測試</span><span class="sxs-lookup"><span data-stu-id="d019f-369">Test</span></span> | <span data-ttu-id="d019f-370">控制措施</span><span class="sxs-lookup"><span data-stu-id="d019f-370">Controls</span></span> |
|-------|-----------|
|<span data-ttu-id="d019f-371">**滲透測試**</span><span class="sxs-lookup"><span data-stu-id="d019f-371">**Penetration testing**</span></span>| <span data-ttu-id="d019f-372">應用程式和基礎結構滲透測試 **必須** 每年 (12 個月進行，) 且由著名的獨立公司執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-372">Application and infrastructure penetration testing **MUST** take place annually (every 12 months) and conducted by a reputable independent company.</span></span> <span data-ttu-id="d019f-373">修正的嚴重和高風險弱點 **必須** 在滲透測試結束的一個月內完成，或根據所記錄的修補程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-373">Remediation of identified critical and high-risk vulnerabilities **MUST** be completed within one month of the conclusion of the penetration testing, or sooner depending on the documented patching process.</span></span><span data-ttu-id="d019f-374"> (IP 位址、URLs、API 端點 ) 等的完整外部空間，必須包含在滲透測試範圍內，且必須在滲透測試報告中加以記錄。 (IP 位址、URLs、API 端點 ) 等的完整外部 **空間，必須** 包含在滲透測試範圍內，且必須在滲透測試報告中加以記錄。</span><span class="sxs-lookup"><span data-stu-id="d019f-374"> The full external footprint (IP Addresses, URLs, API Endpoints, etc.) MUST be included within the scope of penetration testing and must be documented within the penetration testing report.The full external footprint (IP Addresses, URLs, API Endpoints, etc.) *\*MUST** be included within the scope of penetration testing and must be documented within the penetration testing report.</span></span>                                                                                                                                                                           <span data-ttu-id="d019f-375">Web 應用程式滲透測試必須包含所有弱點類別;例如，最新的 OWASP Top 10 或 SANS Top 25 CWE。</span><span class="sxs-lookup"><span data-stu-id="d019f-375">Web application penetration testing MUST include all vulnerability classes; for example, the most current OWASP Top 10 or SANS Top 25 CWE.</span></span>                                                                                                                                                                                <span data-ttu-id="d019f-376">不需要透過滲透測試公司重新測試已識別的漏洞-修復和自我審查是足夠的，所以評估期間 **必須** 提供足夠的證據來示範足夠的修復。</span><span class="sxs-lookup"><span data-stu-id="d019f-376">Retesting of identified vulnerabilities by the penetration testing company is not required — remediation and self-review is sufficient however, adequate evidence to demonstrate sufficient remediation **MUST** be provided during the assessment.</span></span>|

### <a name="application-security-testing-reportreview"></a><span data-ttu-id="d019f-377">應用程式安全性測試報告檢查</span><span class="sxs-lookup"><span data-stu-id="d019f-377">Application Security Testing Report Review</span></span>

<span data-ttu-id="d019f-378">將會檢查滲透測試報告，以確保沒有任何漏洞可滿足下列 **自動失敗準則：**</span><span class="sxs-lookup"><span data-stu-id="d019f-378">Penetration testing reports will be reviewed to ensure there are no vulnerabilities that meet the following **automatic failure criteria:**</span></span>

* <span data-ttu-id="d019f-379">目前是否有不受支援的作業系統。</span><span class="sxs-lookup"><span data-stu-id="d019f-379">Presence of an unsupported operating system.</span></span> 

* <span data-ttu-id="d019f-380">預設值、可枚舉或 guessable 的系統管理帳戶是否存在。</span><span class="sxs-lookup"><span data-stu-id="d019f-380">Presence of default, enumerable, or guessable administrative accounts.</span></span>

* <span data-ttu-id="d019f-381">SQL 注入風險的存在。</span><span class="sxs-lookup"><span data-stu-id="d019f-381">Presence of SQL injection risks.\*</span></span>

* <span data-ttu-id="d019f-382">跨網站腳本的存在。</span><span class="sxs-lookup"><span data-stu-id="d019f-382">Presence of cross-site scripting.\*</span></span>

* <span data-ttu-id="d019f-383">目錄遍歷 (檔案路徑) 漏洞。 \*</span><span class="sxs-lookup"><span data-stu-id="d019f-383">Presence of directory traversal (file path) vulnerabilities.\*</span></span>

* <span data-ttu-id="d019f-384">HTTP 弱點的存在，例如標頭回應分割、要求 smuggling 及 Desync 攻擊。 \*</span><span class="sxs-lookup"><span data-stu-id="d019f-384">Presence of HTTP vulnerabilities, e.g., Header response splitting, Request smuggling, and Desync attacks.\*</span></span>

* <span data-ttu-id="d019f-385">來原始程式碼洩漏 (包括 [LFI](#lfi)) 。 \*</span><span class="sxs-lookup"><span data-stu-id="d019f-385">Presence of source code disclosure (including [LFI](#lfi)).\*</span></span>

* <span data-ttu-id="d019f-386">CVSS 修補程式管理指導方針所定義的任何重要或高分數。</span><span class="sxs-lookup"><span data-stu-id="d019f-386">Any critical or high score as defined by the CVSS patch management guidelines.</span></span>

* <span data-ttu-id="d019f-387">任何重要的技術弱點，可被攻擊者利用以攻破大量的 EUII 或 OUI。</span><span class="sxs-lookup"><span data-stu-id="d019f-387">Any significant technical vulnerability which can be readily exploited to compromise a large amount of EUII or OUI.</span></span>

<span data-ttu-id="d019f-388">\* 不論弱點 CVSS 分數為何</span><span class="sxs-lookup"><span data-stu-id="d019f-388">\*Regardless of the vulnerabilities CVSS Score</span></span>

> [!IMPORTANT]
><span data-ttu-id="d019f-389">報表必須能夠提供足夠的保證，您可以在 Application Security Test 規格區段中的詳細資訊中加以示範。</span><span class="sxs-lookup"><span data-stu-id="d019f-389">Reports must be able to provide enough assurance that everything detailed within the Application Security Test Specification section can be demonstrated.</span></span>


### <a name="penetration-testing-requirements-and-cost"></a><span data-ttu-id="d019f-390">滲透測試需求和成本</span><span class="sxs-lookup"><span data-stu-id="d019f-390">Penetration Testing Requirements and Cost</span></span>

<span data-ttu-id="d019f-391">針對目前未參與滲透測試的 Isv，滲透測試會包含在 Microsoft 365 認證中。</span><span class="sxs-lookup"><span data-stu-id="d019f-391">For ISVs that currently do not engage in penetration testing, penetration testing is included under the Microsoft 365 Certification.</span></span> <span data-ttu-id="d019f-392">Microsoft 會安排並涵蓋最多12天手動測試的滲透測試成本。</span><span class="sxs-lookup"><span data-stu-id="d019f-392">Microsoft will arrange and cover the cost of a penetration test for up to 12 days of manual testing.</span></span> <span data-ttu-id="d019f-393">滲透測試成本的計算取決於測試環境所需的天數。</span><span class="sxs-lookup"><span data-stu-id="d019f-393">Penetration tests costs are calculated based on the number of days required to test the environment.</span></span> <span data-ttu-id="d019f-394">任何超過12天測試的費用都會成為 ISV 的責任。</span><span class="sxs-lookup"><span data-stu-id="d019f-394">Any expenses exceeding 12 days of testing will be the responsibility of the ISV.</span></span> <span data-ttu-id="d019f-395">ISV 也會負責示範滲透測試中所識別的安全性漏洞已在取得認證之前修正，但不需要產生全新報告。</span><span class="sxs-lookup"><span data-stu-id="d019f-395">The ISV will also be responsible for demonstrating that vulnerabilities identified in the penetration test have been remediated prior to a certification being awarded, but do not need to produce a clean report.</span></span>

<span data-ttu-id="d019f-396">在排列滲透測試之後，ISV 會負責與重新排定和取消相關的費用，如下所示：</span><span class="sxs-lookup"><span data-stu-id="d019f-396">Once a penetration test is arranged, the ISV is responsible for fees associated with rescheduling and cancellations as follows:</span></span>

| <span data-ttu-id="d019f-397">**重新排定費用的時間**</span><span class="sxs-lookup"><span data-stu-id="d019f-397">**Rescheduling Fee Timescale**</span></span> | <span data-ttu-id="d019f-398">**應付比例**</span><span class="sxs-lookup"><span data-stu-id="d019f-398">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="d019f-399">在排定的開始日期之前的30天內，重新排程要求的接收時間超過30天。</span><span class="sxs-lookup"><span data-stu-id="d019f-399">Re-schedule request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="d019f-400">0% 應付</span><span class="sxs-lookup"><span data-stu-id="d019f-400">0% Payable</span></span> |
| <span data-ttu-id="d019f-401">預定的開始日期之前，請重新排定要求的前8至30天。</span><span class="sxs-lookup"><span data-stu-id="d019f-401">Re-schedule request received 8 to 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="d019f-402">25% 應付</span><span class="sxs-lookup"><span data-stu-id="d019f-402">25% Payable</span></span> |
| <span data-ttu-id="d019f-403">在排定的開始日期之前的2到7天內，將要求重新排定的時間設定為固定的重新預約日期。</span><span class="sxs-lookup"><span data-stu-id="d019f-403">Re-schedule request received within 2 to 7 days prior to scheduled start date with a firm re-booking date.</span></span>| <span data-ttu-id="d019f-404">50% 應付</span><span class="sxs-lookup"><span data-stu-id="d019f-404">50% Payable</span></span> |
| <span data-ttu-id="d019f-405">在開始日期之前的2天內，重新排程要求的接收時間小於2天。</span><span class="sxs-lookup"><span data-stu-id="d019f-405">Re-schedule request received less than 2 days before the start date.</span></span> | <span data-ttu-id="d019f-406">100% 應付</span><span class="sxs-lookup"><span data-stu-id="d019f-406">100% Payable</span></span> |

| <span data-ttu-id="d019f-407">**取消費用時間**</span><span class="sxs-lookup"><span data-stu-id="d019f-407">**Cancellation Fee Timescale**</span></span> | <span data-ttu-id="d019f-408">**應付比例**</span><span class="sxs-lookup"><span data-stu-id="d019f-408">**Proportion Payable**</span></span> |
|------------------|------------------------|
| <span data-ttu-id="d019f-409">在排定的開始日期之前收到超過30天的取消要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-409">Cancellation request received more than 30 days prior to scheduled start date.</span></span> | <span data-ttu-id="d019f-410">25% 應付</span><span class="sxs-lookup"><span data-stu-id="d019f-410">25% Payable</span></span> |
| <span data-ttu-id="d019f-411">在排定的開始日期之前，已接收到8至30天的取消要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-411">Cancellation request received 8 to 30 days days prior to scheduled start date.</span></span> | <span data-ttu-id="d019f-412">50% 應付</span><span class="sxs-lookup"><span data-stu-id="d019f-412">50% Payable</span></span> |
| <span data-ttu-id="d019f-413">在排定的開始日期之前7天內收到的取消要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-413">Cancellation request received within 7 days prior to scheduled start date.</span></span> | <span data-ttu-id="d019f-414">90% 應付</span><span class="sxs-lookup"><span data-stu-id="d019f-414">90% Payable</span></span> |

## <a name="operational-security"></a><span data-ttu-id="d019f-415">運作安全性</span><span class="sxs-lookup"><span data-stu-id="d019f-415">Operational Security</span></span>

<span data-ttu-id="d019f-416">這個網域會以安全性最佳作法衡量應用程式的支援基礎結構和部署程式的對齊方式。</span><span class="sxs-lookup"><span data-stu-id="d019f-416">This domain measures the alignment of your app's supporting infrastructure and deployment processes with security best practices.</span></span>

### <a name="test-specification"></a><span data-ttu-id="d019f-417">測試規格</span><span class="sxs-lookup"><span data-stu-id="d019f-417">Test Specification</span></span>

|<span data-ttu-id="d019f-418">測試</span><span class="sxs-lookup"><span data-stu-id="d019f-418">Test</span></span> | <span data-ttu-id="d019f-419">控制措施</span><span class="sxs-lookup"><span data-stu-id="d019f-419">Controls</span></span> |
| ------------------------|------------------------------ |
| <span data-ttu-id="d019f-420">**惡意程式碼保護**</span><span class="sxs-lookup"><span data-stu-id="d019f-420">**Malware Protection**</span></span> | <span data-ttu-id="d019f-421">您必須在經常受到惡意程式碼影響的所有範圍內系統上部署惡意程式碼保護機制。</span><span class="sxs-lookup"><span data-stu-id="d019f-421">You must deploy malware protection mechanisms on all in-scope systems that are commonly affected by malware.</span></span> <span data-ttu-id="d019f-422">這些保護機制可能包括使用防毒軟體或應用程式控制技巧，以防範惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="d019f-422">These protection mechanisms can include the use of anti-virus software or application control techniques that protect against malware.</span></span> <span data-ttu-id="d019f-423">在使用防毒軟體或應用程式控制的地方，必須符合下列準則。</span><span class="sxs-lookup"><span data-stu-id="d019f-423">Where anti-virus software or application control is used, it MUST meet the following criteria.</span></span>                                                                                            <span data-ttu-id="d019f-424">防病毒 (也包含反惡意軟體產品) 必須符合下列各項：</span><span class="sxs-lookup"><span data-stu-id="d019f-424">Anti-virus (also including anti-malware products) MUST meet the following:</span></span> |
||<span data-ttu-id="d019f-425">在範圍內的所有系統元件上執行防毒軟體 &#x2713;。</span><span class="sxs-lookup"><span data-stu-id="d019f-425">&#x2713; Anti-virus software is running on all system components within scope.</span></span>|
||<span data-ttu-id="d019f-426">&#x2713; 防毒軟體會在30天內 () 。</span><span class="sxs-lookup"><span data-stu-id="d019f-426">&#x2713; Anti-virus software is kept up to date (within 30 days).</span></span>|
||<span data-ttu-id="d019f-427">&#x2713; 防病毒碼碼會在1天內 () 。</span><span class="sxs-lookup"><span data-stu-id="d019f-427">&#x2713; Anti-virus signatures are kept up to date (within 1 day).</span></span>|
||<span data-ttu-id="d019f-428">&#x2713; 必須設定 [使用中的掃描] 掃描及（或）定期掃描（必須設定通知）。</span><span class="sxs-lookup"><span data-stu-id="d019f-428">&#x2713; Either on-access scanning and/or periodic scans with notifications must be configured.</span></span>  <span data-ttu-id="d019f-429">在使用存取掃描的情況下，還 **必須** 設定每週掃描，但如果未設定存取掃描，則必須設定每日掃描。</span><span class="sxs-lookup"><span data-stu-id="d019f-429">Where on-access scanning is used, weekly scans **MUST** also be configured, however if on-access scanning is not configured, daily scanning must be configured.</span></span>|
||<span data-ttu-id="d019f-430">&#x2713; 防毒軟體 **必須** 設定如下。</span><span class="sxs-lookup"><span data-stu-id="d019f-430">&#x2713; Anti-virus software **MUST** be configured as follows.</span></span>|
||<span data-ttu-id="d019f-431">&emsp;&#x25fc; 封鎖可疑的惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="d019f-431">&emsp;&#x25fc; Block suspected malware.</span></span>|
||<span data-ttu-id="d019f-432">&emsp;&#x25fc; 隔離可疑的惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="d019f-432">&emsp;&#x25fc; Quarantine suspected malware.</span></span>|
||<span data-ttu-id="d019f-433">&emsp;&#x25fc; 對可疑的惡意程式碼提供警示。</span><span class="sxs-lookup"><span data-stu-id="d019f-433">&emsp;&#x25fc; Provide an alert on suspected malware.</span></span>|
||<span data-ttu-id="d019f-434">&#x2713; 防毒軟體 **必須** 設定為記錄所有活動。</span><span class="sxs-lookup"><span data-stu-id="d019f-434">&#x2713; Anti-virus software **MUST** be configured to log all activities.</span></span>
||<span data-ttu-id="d019f-435">&#x2713; 原則和程式 **必須** 準備好，以提升惡意的反惡意程式碼作法。</span><span class="sxs-lookup"><span data-stu-id="d019f-435">&#x2713; Policies and procedures **MUST** be in place to promote strong anti-malware practices.</span></span>|
||<span data-ttu-id="d019f-436">或</span><span class="sxs-lookup"><span data-stu-id="d019f-436">or</span></span>|
||<span data-ttu-id="d019f-437">必須在所有的內部範圍系統上設定應用程式控制項，才能符合下列各項：</span><span class="sxs-lookup"><span data-stu-id="d019f-437">Application controls MUST be configured on all in-scope system to meet the following:</span></span>|
||<span data-ttu-id="d019f-438">&#x2713; 所有允許在內部範圍系統元件上執行的應用程式，必須由組織正式核准。</span><span class="sxs-lookup"><span data-stu-id="d019f-438">&#x2713; All allowed applications permitted to execute on in-scope system components MUST be formally approved by the organization..</span></span>|
||<span data-ttu-id="d019f-439">&#x2713; 組織必須維護完整的核准應用程式清單，讓應用程式具備業務理由。</span><span class="sxs-lookup"><span data-stu-id="d019f-439">&#x2713; The organization MUST maintain a complete list of approved applications with business justification for the application.</span></span>|
||<span data-ttu-id="d019f-440">必須完整記錄 &#x2713; 特定的應用程式控制機制：例如，白名單位置;代碼簽署等。</span><span class="sxs-lookup"><span data-stu-id="d019f-440">&#x2713; Specific application control mechanisms MUST be fully documented: i.e. whitelisted locations; code signing, etc.</span></span>|
||<span data-ttu-id="d019f-441">&#x2713; 應用程式控制項必須設定為檔。</span><span class="sxs-lookup"><span data-stu-id="d019f-441">&#x2713; Application control MUST be configured as document.</span></span>|
||<span data-ttu-id="d019f-442">針對應用程式核准的 &#x2713; 已記錄的程式必須已就緒且可供審核。</span><span class="sxs-lookup"><span data-stu-id="d019f-442">&#x2713; Documented process for application approvals must be in place and auditable.</span></span>|
|<span data-ttu-id="d019f-443">**修補程式管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-443">**Patch Management**</span></span>|<span data-ttu-id="d019f-444">您 **必須** 具備已記錄的修補原則和程式，以確保及時進行修補程式的實施。</span><span class="sxs-lookup"><span data-stu-id="d019f-444">You **MUST** have documented patching policies and procedures in place that ensure patching is conducted in a timely manner.</span></span> <span data-ttu-id="d019f-445">一個可靠的程式 **必須** 是就地，以根據 CVSS 中的 **建議風險排名分數** 或同等計分分類，識別、排名及修補新的安全性弱點：</span><span class="sxs-lookup"><span data-stu-id="d019f-445">A robust process **MUST** be in place that identifies, ranks, and patches new security vulnerabilities based on the CVSS V3.1 **Recommended Risk Ranking Scores**, or equivalent scoring taxonomy:</span></span> 
||<span data-ttu-id="d019f-446">**建議的風險排名分數** (CVSS App-v 3.1 基本分數範圍) </span><span class="sxs-lookup"><span data-stu-id="d019f-446">**Recommended Risk Ranking Scores** (CVSS v3.1 Base Score Range)</span></span>|
||<span data-ttu-id="d019f-447">&emsp;**嚴重**： 9.0-10.0。</span><span class="sxs-lookup"><span data-stu-id="d019f-447">&emsp; **Critical**: 9.0 - 10.0.</span></span>|
||<span data-ttu-id="d019f-448">&emsp;**高**： 7.0-8.9。</span><span class="sxs-lookup"><span data-stu-id="d019f-448">&emsp; **High**: 7.0 - 8.9.</span></span>|
||<span data-ttu-id="d019f-449">&emsp;**中**： 4.0-6.9。</span><span class="sxs-lookup"><span data-stu-id="d019f-449">&emsp; **Medium**: 4.0 - 6.9.</span></span>|
||<span data-ttu-id="d019f-450">&emsp;**低**： 0.1-3.9。</span><span class="sxs-lookup"><span data-stu-id="d019f-450">&emsp; **Low**: 0.1 - 3.9.</span></span>|
||<span data-ttu-id="d019f-451">&emsp;**無**：0。0</span><span class="sxs-lookup"><span data-stu-id="d019f-451">&emsp; **None**: 0.0</span></span> |
|| <span data-ttu-id="d019f-452">**重要**：識別新漏洞的程式必須具備足夠強大的功能，才能允許以您所定義之已記錄的修補視窗來識別及修補弱點。</span><span class="sxs-lookup"><span data-stu-id="d019f-452">**IMPORTANT**: The process to identify new vulnerabilities must be robust enough to allow for the identification and patching of vulnerabilities in line with the documented patching window you have defined.</span></span> |
|<span data-ttu-id="d019f-453">**Patching**</span><span class="sxs-lookup"><span data-stu-id="d019f-453">**Patching**</span></span>|<span data-ttu-id="d019f-454">&#x2713; 任何嚴重、高或中等風險問題， **都必須** 在主要確定和記錄的期間內進行修補，該 ISV 是由 ISV 所決定，在解決問題之前所 **需** 的最小時間範圍。</span><span class="sxs-lookup"><span data-stu-id="d019f-454">&#x2713; Any Critical, High, or Medium risk issues **MUST** be patched within a pre-determined and documented period decided by the ISV which represents the minimal window of time before the issue **must be** resolved.</span></span>  <span data-ttu-id="d019f-455">雖然 [修補程式] 視窗是由 ISV 定義，但視窗必須在合理的時間範圍內。</span><span class="sxs-lookup"><span data-stu-id="d019f-455">Although the patching window is defined by the ISV, the window needs to be within a reasonable timeframe.</span></span> <span data-ttu-id="d019f-456">例如，用來修補重要弱點的三個月，在您的 Microsoft 365 認證評估中不會有合理的，因此遭到拒絕。</span><span class="sxs-lookup"><span data-stu-id="d019f-456">For example, three months to patch a Critical vulnerability would not be reasonable and therefore rejected within your Microsoft 365 Certification assessment.</span></span>|
||<span data-ttu-id="d019f-457">&#x2713; 的原則和程式詳細說明如何進行 **修補，** **必須** 使用環境中所用的所有適用作業系統、應用程式及軟體元件。</span><span class="sxs-lookup"><span data-stu-id="d019f-457">&#x2713; Policies and procedures detailing how patching is conducted **MUST** be in place and **MUST** include all applicable operating systems, applications and software components used within the environment.</span></span> <span data-ttu-id="d019f-458">這包括應用程式/增益集內使用的任何 web 相關專案。</span><span class="sxs-lookup"><span data-stu-id="d019f-458">This includes any web dependencies used within the app/add-in.</span></span>|
||<span data-ttu-id="d019f-459">不再支援廠商所 &#x2713; 的軟體元件和作業系統， **不得** 在環境內使用。</span><span class="sxs-lookup"><span data-stu-id="d019f-459">&#x2713; Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="d019f-460">支援的原則 **必須** 已到位，以確保會從環境中移除不受支援的軟體元件/作業系統，以及識別何時必須使用軟體元件的程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-460">Supporting policies **MUST** be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>|
|<span data-ttu-id="d019f-461">**弱點掃描**</span><span class="sxs-lookup"><span data-stu-id="d019f-461">**Vulnerability scanning**</span></span>|<span data-ttu-id="d019f-462">弱點掃描必須包括：</span><span class="sxs-lookup"><span data-stu-id="d019f-462">Vulnerability scanning must include:</span></span>|
||<span data-ttu-id="d019f-463">&#x2713; 每個季度外部弱點掃描都是針對範圍外環境的 **完整** 公開範圍所進行的， (基礎結構及 Web 應用程式掃描) 的 URLS 和 IP 位址。</span><span class="sxs-lookup"><span data-stu-id="d019f-463">&#x2713; Quarterly external vulnerability scanning carried out against the **FULL** public footprint of the in-scope environment (URLs AND IP Addresses for Infrastructure and Web Application scanning).</span></span>|
||<span data-ttu-id="d019f-464">&#x2713; 每季驗證的內部弱點掃描會針對範圍內系統元件進行的掃描，而不是 (PaaS) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-464">&#x2713; Quarterly authenticated internal vulnerability scanning carried out against in-scope system components (not for PaaS).</span></span>|
||<span data-ttu-id="d019f-465">&#x2713; 已記載的弱點修正原則 **必須** 已到位，以確保系統元件不會受到已知的漏洞影響，方法是詳述時程表以修正根據您定義的 CVSS  **建議的風險排名分數** 的時程表 (如以上) 所示。</span><span class="sxs-lookup"><span data-stu-id="d019f-465">&#x2713; A documented vulnerability remediation policy **MUST** be in place to ensure system components are free from known vulnerabilities by detailing the timeline to fix vulnerabilities based upon your defined CVSS **Recommended Risk Ranking Scores**(see above).</span></span>|
||<span data-ttu-id="d019f-466">&#x2713; 進行中的重新掃描 **必須** 執行，直到在必要的時程表（如 ISV 的修正原則所定義的）中修正已辨識的風險排名漏洞為止。</span><span class="sxs-lookup"><span data-stu-id="d019f-466">&#x2713; Ongoing re-scans **MUST** be carried out until identified risk ranked vulnerabilities are remediated within the required timeline, as defined by the ISV’s remediation policy.</span></span> <span data-ttu-id="d019f-467">雖然 ISV 定義的是修復時程表，但視窗必須在合理的時間範圍內。</span><span class="sxs-lookup"><span data-stu-id="d019f-467">Although the remediation timeline is defined by the ISV, the window needs to be within a reasonable timeframe.</span></span> <span data-ttu-id="d019f-468">例如，修正嚴重缺陷的三個月，在您的 Microsoft 365 認證評估中將不會有合理的，因此遭到拒絕。</span><span class="sxs-lookup"><span data-stu-id="d019f-468">For example, three months to remediate a Critical vulnerability would not be reasonable and therefore rejected within your Microsoft 365 Certification assessment.</span></span>|
|<span data-ttu-id="d019f-469">**防火牆**</span><span class="sxs-lookup"><span data-stu-id="d019f-469">**Firewalls**</span></span>|<span data-ttu-id="d019f-470">您的支援基礎結構應該會有防火牆 (或同等的雲服務使用中) 設定如下：</span><span class="sxs-lookup"><span data-stu-id="d019f-470">Your supporting infrastructure will be expected to have a firewall (or equivalent where Cloud services are being consumed) configured as follows:</span></span>|
||<span data-ttu-id="d019f-471">在所有公開範圍內環境的網際網路連線上都 **必須** 安裝 &#x2713;。</span><span class="sxs-lookup"><span data-stu-id="d019f-471">&#x2713; **MUST** be installed on all internet connections exposing the in-scope environments.</span></span>|
||<span data-ttu-id="d019f-472">您 **必須** 在所有 DMZs (隔離區域之間安裝 &#x2713;，) 和任何信任的網路。</span><span class="sxs-lookup"><span data-stu-id="d019f-472">&#x2713; **MUST** be installed between all DMZs (Demilitarized Zones) and any trusted networks.</span></span>|
||<span data-ttu-id="d019f-473">&#x2713; 所有公用存取 **必須** 在 DMZ 中終止 (隔離區域) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-473">&#x2713; All public access **MUST** terminate in a DMZ (Demilitarized Zone).</span></span> |
||<span data-ttu-id="d019f-474">在安裝至實際執行環境之前， **必須** 變更 &#x2713; 的預設系統管理認證。</span><span class="sxs-lookup"><span data-stu-id="d019f-474">&#x2713; Default administrative credentials **MUST** be changed, prior to installation into production environments.</span></span>|
||<span data-ttu-id="d019f-475">&#x2713; 任何一方向的透過範圍內防火牆所允許的所有流量 () **必須** 經過核准程式，而且所有的通訊協定、服務和埠都必須與業務合理性論證一起記錄。</span><span class="sxs-lookup"><span data-stu-id="d019f-475">&#x2713; ­All traffic permitted through in-scope firewalls (in either direction) **MUST** go through an approval process and all protocols, services and ports must be documented with business justifications.</span></span>|
||<span data-ttu-id="d019f-476">&#x2713; 防火牆規則必須以記錄的允許規則線上設定。</span><span class="sxs-lookup"><span data-stu-id="d019f-476">&#x2713; Firewall rules must be configured in-line with the documented permitted rules.</span></span>|
||<span data-ttu-id="d019f-477">在所有的防火牆非主控台管理介面上，**必須** 啟用 &#x2713; 強式密碼編譯，也就是 **附錄 B**。</span><span class="sxs-lookup"><span data-stu-id="d019f-477">&#x2713; ­Strong cryptography, in line with **Appendix B**, **MUST** be enabled on all firewall non-console administrative interfaces.</span></span>|
||<span data-ttu-id="d019f-478">&#x2713; 多重要素驗證 (MFA) **必須** 針對防火牆系統管理存取啟用。。</span><span class="sxs-lookup"><span data-stu-id="d019f-478">&#x2713; Multi-factor authentication (MFA) **MUST** be enabled for firewall administrative access..</span></span>|
||<span data-ttu-id="d019f-479">&#x2713; 防火牆評論 **必須** 至少進行六個月的執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-479">&#x2713;­ Firewall reviews **MUST** be conducted at least every six months.</span></span>|
||<span data-ttu-id="d019f-480">憑證分析會檢查防火牆規則基礎，以瞭解是否存在傳出流量流向可能的協力廠商，以驗證外部協力廠商資料共用。</span><span class="sxs-lookup"><span data-stu-id="d019f-480">Certification analysis will review the firewall rules base for the presence of egress traffic flows to potential third parties to validate external third-party data sharing.</span></span>  |
||<span data-ttu-id="d019f-481">**Web 應用程式防火牆 (WAF)**。</span><span class="sxs-lookup"><span data-stu-id="d019f-481">**Web Application Firewall (WAF)**.</span></span> <span data-ttu-id="d019f-482">如果部署 WAF 或同等量值，以協助防範 web 應用程式威脅和弱點，將會提供額外的信用。</span><span class="sxs-lookup"><span data-stu-id="d019f-482">Additional credit will be given if a WAF or equivalent measure is deployed to help protect against web application threats and vulnerabilities.</span></span> <span data-ttu-id="d019f-483">如果有的話，支援的原則和程式 **應** 與下列 WAF 設定搭配使用：</span><span class="sxs-lookup"><span data-stu-id="d019f-483">If present, supporting policies and procedures **SHOULD** be in place along with the following WAF configurations:</span></span> |
||<span data-ttu-id="d019f-484">&#x2713; WAF 應以作用中的防禦模式運作 (自動封鎖已識別的攻擊) 或監視模式， (主動監視/調查警示) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-484">&#x2713; WAF SHOULD operate in active defense mode (automatically blocking identified attacks) or in monitoring mode (actively monitoring/investigating alerts).</span></span>|
||<span data-ttu-id="d019f-485">設定為支援 [SSL](#ssl) 卸載 &#x2713; WAF。</span><span class="sxs-lookup"><span data-stu-id="d019f-485">&#x2713; WAF configured to support [SSL](#ssl) offloading.</span></span>|
||<span data-ttu-id="d019f-486">&#x2713; WAF 應根據 [OWASP](#owasp) **核心規則集** 設定   (3.0 或 3.1) ，以防範下列各項：</span><span class="sxs-lookup"><span data-stu-id="d019f-486">&#x2713; WAF SHOULD be configured as per the [OWASP](#owasp) **Core Rule Set** (3.0 or 3.1) to protect against the majority of the following:</span></span>|
||<span data-ttu-id="d019f-487">&emsp;&#x25fc; 通訊協定和編碼的問題。</span><span class="sxs-lookup"><span data-stu-id="d019f-487">&emsp;&#x25fc; Protocol and encoding issues.</span></span>|
||<span data-ttu-id="d019f-488">&emsp;&#x25fc; 頁首注入、要求 smuggling 及回應分割。</span><span class="sxs-lookup"><span data-stu-id="d019f-488">&emsp;&#x25fc; Header injection, request smuggling, and response splitting.</span></span>|
||<span data-ttu-id="d019f-489">&emsp;&#x25fc; 檔和路徑遍歷攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-489">&emsp;&#x25fc; File and path traversal attacks.</span></span>|
||<span data-ttu-id="d019f-490">&emsp;&#x25fc; Remote file 包含 (RFI) 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-490">&emsp;&#x25fc; Remote file inclusion (RFI) attacks.</span></span>|
||<span data-ttu-id="d019f-491">&emsp;&#x25fc; 遠端程式碼執行攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-491">&emsp;&#x25fc; Remote code execution attacks.</span></span>|
||<span data-ttu-id="d019f-492">&emsp;&#x25fc; PHP 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-492">&emsp;&#x25fc; PHP-injection attacks.</span></span>|
||<span data-ttu-id="d019f-493">&emsp;&#x25fc; 跨網站腳本攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-493">&emsp;&#x25fc; Cross-site scripting attacks.</span></span>|
||<span data-ttu-id="d019f-494">&emsp;&#x25fc; SQL 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-494">&emsp;&#x25fc; SQL-injection attacks.</span></span>|
||<span data-ttu-id="d019f-495">&emsp;&#x25fc; 會話 fixation 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-495">&emsp;&#x25fc; Session-fixation attacks.</span></span>|
|<span data-ttu-id="d019f-496">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="d019f-496">**Change Control**</span></span>|<span data-ttu-id="d019f-497">變更控制原則和程式 **必須** 已到位，以確保以維護環境安全性、穩定性和完整性的方式來執行變更。</span><span class="sxs-lookup"><span data-stu-id="d019f-497">Change control policies and procedures **MUST** be in place to ensure that changes are implemented in a manner aimed at maintaining the security, stability, and integrity of the environment.</span></span> <span data-ttu-id="d019f-498">下列 **是** 必要的變更控制準則：</span><span class="sxs-lookup"><span data-stu-id="d019f-498">The following change control criteria **ARE** required:</span></span>|
||<span data-ttu-id="d019f-499">&#x2713; 責任分隔-開發和測試環境 **必須** 與實際執行環境分開。</span><span class="sxs-lookup"><span data-stu-id="d019f-499">&#x2713; Separation of duties—development and test environments **MUST** be separate from the production environments.</span></span>|
||<span data-ttu-id="d019f-500">從生產環境 &#x2713; 敏感性資料 **不得** 用於開發/測試環境中。</span><span class="sxs-lookup"><span data-stu-id="d019f-500">&#x2713; Sensitive data from production environments **MUST** not be used within development/test environments.</span></span>|
||<span data-ttu-id="d019f-501">&#x2713; 所有變更，必須先在測試/開發環境中測試，然後再引進實際執行環境。</span><span class="sxs-lookup"><span data-stu-id="d019f-501">&#x2713; All changes MUST be tested within a test/development environment prior to being introduced into the production environment.</span></span>|
||<span data-ttu-id="d019f-502">在進入生產環境 **之前**，**會** 引發並授權 &#x2713; 變更要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-502">&#x2713; Change requests **ARE** raised and authorized **PRIOR** to going into production.</span></span>|
||<span data-ttu-id="d019f-503">&#x2713; 變更要求至少 **必須** 包括：</span><span class="sxs-lookup"><span data-stu-id="d019f-503">&#x2713; At a minimum, change requests **MUST** include:</span></span>|
||<span data-ttu-id="d019f-504">&emsp;&#x25fc; 影響的檔。</span><span class="sxs-lookup"><span data-stu-id="d019f-504">&emsp;&#x25fc; Documentation of impact.</span></span>|
||<span data-ttu-id="d019f-505">&emsp;&#x25fc; 記錄的後端程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-505">&emsp;&#x25fc; Documented back-out procedures.</span></span>|
||<span data-ttu-id="d019f-506">&#x2713; 變更要求 **必須** 標示為已完成，只有 **在** 執行成功的功能測試之後。</span><span class="sxs-lookup"><span data-stu-id="d019f-506">&#x2713; Change requests **MUST** be marked as complete, only **AFTER** successful functionality testing has been carried out.</span></span>|
|<span data-ttu-id="d019f-507">**安全的軟體發展/部署**</span><span class="sxs-lookup"><span data-stu-id="d019f-507">**Secure Software Development/Deployment**</span></span>|<span data-ttu-id="d019f-508">安全性需要是軟體發展做法的最大程度，以降低向應用程式/增益集引入編碼弱點的風險，進而維護安全的環境，以及保護資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-508">Security needs to be at the forefront of software development practices to minimize the risk of introducing coding vulnerabilities into the app / add-in, thereby maintaining a secure environment, and securing data.</span></span> <span data-ttu-id="d019f-509">下列軟體發展安全作法 **必須** 已就緒：</span><span class="sxs-lookup"><span data-stu-id="d019f-509">The following software development secure practices **MUST** be in place:</span></span> |
||<span data-ttu-id="d019f-510">&#x2713; 您必須已建立且已記錄的軟體發展程式涵蓋整個軟體發展週期。</span><span class="sxs-lookup"><span data-stu-id="d019f-510">&#x2713; You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>|
||<span data-ttu-id="d019f-511">&#x2713; 所有程式碼變更，都必須透過原始開發人員以外的其他人員進行審閱和授權程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-511">&#x2713; All code changes MUST go through a review and authorization process by someone other than the original developer.</span></span>|
||<span data-ttu-id="d019f-512">&#x2713; 安全的編碼做法和審閱技巧 **必須** 解決 [OWASP 前10個](https://owasp.org/www-project-top-ten) 或 [san 前25個 CWE](https://www.sans.org/top25-software-errors) 弱點類別。</span><span class="sxs-lookup"><span data-stu-id="d019f-512">&#x2713; Secure coding practices and review techniques **MUST** address the [OWASP Top 10](https://owasp.org/www-project-top-ten) or [SANS Top 25 CWE](https://www.sans.org/top25-software-errors) Vulnerability Classes.</span></span>|
||<span data-ttu-id="d019f-513">&#x2713; 開發人員 **必須** 至少一年為安全的軟體編碼訓練。</span><span class="sxs-lookup"><span data-stu-id="d019f-513">&#x2713; Developers **MUST** undergo secure software coding training at least annually.</span></span>|
||<span data-ttu-id="d019f-514">&#x2713; 的程式碼存放庫 **必須** 由 MFA 保護。</span><span class="sxs-lookup"><span data-stu-id="d019f-514">&#x2713; Code repositories **MUST** be secured by MFA.</span></span>|
||<span data-ttu-id="d019f-515">&#x2713; 足夠的存取控制 **必須** 準備好，以保護程式碼存放庫免受惡意程式碼修改。</span><span class="sxs-lookup"><span data-stu-id="d019f-515">&#x2713; Adequate access controls **MUST** be in place to protect code repositories against malicious code modifications.</span></span>|
||<span data-ttu-id="d019f-516">**附注**： microsoft 已發佈 (SDL) 的 [安全性開發週期](https://www.microsoft.com/en-us/securityengineering/sdl/) ，以供 microsoft 用來支援其產品中的安全性保證與規範需求。</span><span class="sxs-lookup"><span data-stu-id="d019f-516">**Note**: Microsoft has published the [Security Development Lifecycle](https://www.microsoft.com/en-us/securityengineering/sdl/) (SDL) that Microsoft follows to support security assurance and compliance requirements within its products.</span></span> <span data-ttu-id="d019f-517">SDL 可協助開發人員建立更安全的軟體，方法是減少軟體中的漏洞數量和嚴重性，同時降低開發成本。</span><span class="sxs-lookup"><span data-stu-id="d019f-517">The SDL helps developers build more secure software by reducing the number and severity of vulnerabilities in software, while reducing development cost.</span></span>|
|<span data-ttu-id="d019f-518">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-518">**Account Management**</span></span>| <span data-ttu-id="d019f-519">範圍內的系統元件帳戶管理，以及支援原則和程式 **必須** 符合下列專案：</span><span class="sxs-lookup"><span data-stu-id="d019f-519">In-scope system component account management as well as supporting policies and procedures **MUST** meet the following:</span></span> |
||<span data-ttu-id="d019f-520">&#x2713; (廠商或 ISV) 的預設認證 **，都是** 在所有範圍內系統元件上停用或移除。</span><span class="sxs-lookup"><span data-stu-id="d019f-520">&#x2713; Default credentials (Vendor or ISV) **ARE** either disabled or removed across all in-scope system components.</span></span>|
||<span data-ttu-id="d019f-521">&#x2713; 帳戶的建立、修改和刪除 **必須** 經過已建立的核准程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-521">&#x2713; Account creation, modification and deletion **MUST** go through an established approval process.</span></span>|
||<span data-ttu-id="d019f-522">尚未使用超過3個月的 &#x2713; 帳戶 **必須** 停用或刪除，因此，ISV 必須具備實現此功能的機制。</span><span class="sxs-lookup"><span data-stu-id="d019f-522">&#x2713; Accounts that have not been used for over 3 months **MUST** be disabled or deleted, therefore, ISV needs to have a mechanism of achieving this.</span></span>|
||<span data-ttu-id="d019f-523">&#x2713;強式密碼原則或其他適當的緩解 **必須** 設定為保護使用者認證。</span><span class="sxs-lookup"><span data-stu-id="d019f-523">&#x2713;Strong password policies or other suitable mitigation **MUST** be configured to protect user credentials.</span></span> <span data-ttu-id="d019f-524">下列密碼原則應該用來做為指導方針：</span><span class="sxs-lookup"><span data-stu-id="d019f-524">The following password policy should be used as a guideline:</span></span>|
||<span data-ttu-id="d019f-525">&emsp;&#x25fc; 長度為八個字元的最小密碼長度</span><span class="sxs-lookup"><span data-stu-id="d019f-525">&emsp;&#x25fc; Minimum password length of eight characters</span></span>|
||<span data-ttu-id="d019f-526">&emsp; 不超過10次嘗試的帳戶鎖定閥值&#x25fc;</span><span class="sxs-lookup"><span data-stu-id="d019f-526">&emsp;&#x25fc; Account lockout threshold of no more than 10 attempts</span></span>|
||<span data-ttu-id="d019f-527">&emsp; 至少有5個密碼的&#x25fc; 密碼歷史記錄</span><span class="sxs-lookup"><span data-stu-id="d019f-527">&emsp;&#x25fc; Password history of a minimum of five passwords</span></span>|
||<span data-ttu-id="d019f-528">&emsp;&#x25fc; 使用強式密碼的強制執行</span><span class="sxs-lookup"><span data-stu-id="d019f-528">&emsp;&#x25fc; Enforcement of the use of strong passwords</span></span>|
||<span data-ttu-id="d019f-529">必須對每位使用者發出 &#x2713; 唯一的使用者帳戶;不會使用任何共用帳戶。</span><span class="sxs-lookup"><span data-stu-id="d019f-529">&#x2713; Unique user accounts MUST be issued to each user; no shared accounts are to be used.</span></span>|
||<span data-ttu-id="d019f-530">&#x2713; 最低特權原則 **必須** 套用至所有使用者，用來達成此目的的機制應該記錄 (（即使用群組) ）。</span><span class="sxs-lookup"><span data-stu-id="d019f-530">&#x2713; Least privilege principles **MUST** apply to all users, the mechanism used to achieve this should be documented (i.e. the use of groups).</span></span> |
||<span data-ttu-id="d019f-531">&#x2713; 適當的服務帳戶強化， **必須** 加以記錄並進行，例如，互動式登入已停用、限制傳送至特定主機等。</span><span class="sxs-lookup"><span data-stu-id="d019f-531">&#x2713; Suitable service account hardening **MUST** be documented and carried out, for example, interactive logon disabled, logons limited to specific hosts, etc.</span></span> |
||<span data-ttu-id="d019f-532">&#x2713; 遠端存取解決方案 **必須** 執行下列作業：</span><span class="sxs-lookup"><span data-stu-id="d019f-532">&#x2713; Remote Access solutions **MUST**:</span></span> |
||<span data-ttu-id="d019f-533">&emsp;&#x25fc; 利用 MFA (多重因素驗證) </span><span class="sxs-lookup"><span data-stu-id="d019f-533">&emsp;&#x25fc; utilize MFA (Multi Factor Authentication)</span></span>|
||<span data-ttu-id="d019f-534">&emsp;&#x25fc; 會利用傳輸保護設定檔中的資料，該資料符合或超過「附錄 A」所述的資料傳輸設定檔</span><span class="sxs-lookup"><span data-stu-id="d019f-534">&emsp;&#x25fc; utilize a data in transit protection profile that meets or exceeds the data-in-transit configuration profile as described in Appendix A</span></span>|
||<span data-ttu-id="d019f-535">&#x2713; 在範圍內環境中管理公用 DNS 之外，必須設定所有可進行 DNS 修改的使用者帳戶，才能使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="d019f-535">&#x2713; Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>|
||<span data-ttu-id="d019f-536">**附注** ：雲端管理入口網站也需要符合適用的帳戶管理需求，如需詳細資訊，請參閱附錄 F。</span><span class="sxs-lookup"><span data-stu-id="d019f-536">**Note** : Cloud Management Portals will also need to meet applicable account management requirements, see Appendix F for further details.</span></span>|
|<span data-ttu-id="d019f-537">**侵入偵測及防護 (選用)**</span><span class="sxs-lookup"><span data-stu-id="d019f-537">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>| <span data-ttu-id="d019f-538">在範圍內的支援環境周邊使用 IDPS (侵入偵測和防護系統) 時，會提供額外的信用。</span><span class="sxs-lookup"><span data-stu-id="d019f-538">Extra credit will be given where IDPS (Intrusion Detection and Prevention System) is used at the perimeter of the in-scope supporting environments.</span></span>  <span data-ttu-id="d019f-539">下列建議的控制項包括：</span><span class="sxs-lookup"><span data-stu-id="d019f-539">The following recommended controls include:</span></span> |
||<span data-ttu-id="d019f-540">在支援的環境周邊應部署 &#x2713; IDPS</span><span class="sxs-lookup"><span data-stu-id="d019f-540">&#x2713; IDPS SHOULD be deployed at the perimeter of the supporting environment</span></span> |
||<span data-ttu-id="d019f-541">&#x2713; IDPS 簽章應保持在最新狀態，在過去一天內</span><span class="sxs-lookup"><span data-stu-id="d019f-541">&#x2713; IDPS signatures SHOULD be kept current, within the past day</span></span> |
||<span data-ttu-id="d019f-542">應該針對 TLS 檢查設定 &#x2713; IDPS</span><span class="sxs-lookup"><span data-stu-id="d019f-542">&#x2713; IDPS SHOULD be configured for TLS inspection</span></span> |
||<span data-ttu-id="d019f-543">應該針對所有輸入和輸出流量設定 &#x2713; IDPS</span><span class="sxs-lookup"><span data-stu-id="d019f-543">&#x2713; IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span> |
||<span data-ttu-id="d019f-544">應該針對警示設定 &#x2713; IDPS</span><span class="sxs-lookup"><span data-stu-id="d019f-544">&#x2713; IDPS SHOULD be configured for alerting</span></span> |
|<span data-ttu-id="d019f-545">**事件記錄**</span><span class="sxs-lookup"><span data-stu-id="d019f-545">**Event Logging**</span></span> |<span data-ttu-id="d019f-546">記錄覆蓋率 **必須** 包括 **所有** 範圍內的系統元件和應用程式，包括惡意程式碼防護機制。</span><span class="sxs-lookup"><span data-stu-id="d019f-546">Logging coverage **MUST** include **ALL** in-scope system components and applications, including malware protection mechanisms.</span></span> <span data-ttu-id="d019f-547">以下是 **必須** 記錄的事件：</span><span class="sxs-lookup"><span data-stu-id="d019f-547">The following events **MUST** be logged:</span></span>|
||<span data-ttu-id="d019f-548">&emsp;&#x25fc; 使用者存取系統元件和應用程式</span><span class="sxs-lookup"><span data-stu-id="d019f-548">&emsp;&#x25fc; Users access to system components and the application</span></span>|
||<span data-ttu-id="d019f-549">&emsp;&#x25fc; 高許可權使用者採取的所有動作</span><span class="sxs-lookup"><span data-stu-id="d019f-549">&emsp;&#x25fc; All actions taken by a high-privileged user</span></span>|
||<span data-ttu-id="d019f-550">&emsp;&#x25fc; 不正確邏輯存取嘗試</span><span class="sxs-lookup"><span data-stu-id="d019f-550">&emsp;&#x25fc; Invalid logical access attempts</span></span>|
||<span data-ttu-id="d019f-551">&emsp;&#x25fc; 特權帳戶建立/修改</span><span class="sxs-lookup"><span data-stu-id="d019f-551">&emsp;&#x25fc; Privileged account creation / modification</span></span>|
||<span data-ttu-id="d019f-552">&emsp;&#x25fc; 事件記錄的篡改</span><span class="sxs-lookup"><span data-stu-id="d019f-552">&emsp;&#x25fc; Event log tampering</span></span>|
||<span data-ttu-id="d019f-553">&emsp;&#x25fc; 停用安全性工具;例如，Anti-Malware 或事件記錄</span><span class="sxs-lookup"><span data-stu-id="d019f-553">&emsp;&#x25fc; Disabling of security tools; for example, Anti-Malware or event logging</span></span>|
||<span data-ttu-id="d019f-554">&emsp;&#x25fc; Anti-Malware 記錄;例如，更新、惡意程式碼偵測、掃描失敗</span><span class="sxs-lookup"><span data-stu-id="d019f-554">&emsp;&#x25fc; Anti-Malware logging; for example, updates, malware detection, scan failures</span></span>|
||<span data-ttu-id="d019f-555">&emsp;&#x25fc; IDPS/WAF 事件 (若已設定) </span><span class="sxs-lookup"><span data-stu-id="d019f-555">&emsp;&#x25fc; IDPS/WAF events (if configured)</span></span>|
||<span data-ttu-id="d019f-556">事件記錄 **必須** 包含下列資訊：</span><span class="sxs-lookup"><span data-stu-id="d019f-556">­Event logs **MUST** include the following information:</span></span>|
||<span data-ttu-id="d019f-557">&emsp;&#x25fc; 使用者識別碼</span><span class="sxs-lookup"><span data-stu-id="d019f-557">&emsp;&#x25fc; User Identification</span></span> |
||<span data-ttu-id="d019f-558">&emsp; 事件的&#x25fc; 類型</span><span class="sxs-lookup"><span data-stu-id="d019f-558">&emsp;&#x25fc; Type of event</span></span> |
||<span data-ttu-id="d019f-559">&emsp;&#x25fc; 日期和時間</span><span class="sxs-lookup"><span data-stu-id="d019f-559">&emsp;&#x25fc; Date and time</span></span> |
||<span data-ttu-id="d019f-560">&emsp;&#x25fc; 成功/失敗指示器</span><span class="sxs-lookup"><span data-stu-id="d019f-560">&emsp;&#x25fc; Success/Failure indicator</span></span>|
||<span data-ttu-id="d019f-561">&emsp; 用以識別受影響系統的&#x25fc; 標籤</span><span class="sxs-lookup"><span data-stu-id="d019f-561">&emsp;&#x25fc; Label to identify the affected system</span></span> |
||<span data-ttu-id="d019f-562">時間同步處理 **必須** 跨所有範圍內的系統元件使用，以協助鑒證調查。</span><span class="sxs-lookup"><span data-stu-id="d019f-562">­Time-synchronization **MUST** be used across all in-scope system components to aid in forensic investigations.</span></span>|
||<span data-ttu-id="d019f-563">時間同步處理 **必須** 設定成使用相同的主要 (和次要的，如果需要) 時間來源</span><span class="sxs-lookup"><span data-stu-id="d019f-563">Time-synchronization **MUST** be configured to utilize the same primary (and secondary if required) time source</span></span>|
||<span data-ttu-id="d019f-564">在 DMZ 內 (系統公開的系統) **必須** 將記錄寫入內部的集中式記錄存放庫。</span><span class="sxs-lookup"><span data-stu-id="d019f-564">­Public facing systems (systems within the DMZ) **MUST** write logs to an internal centralized logging repository.</span></span> <span data-ttu-id="d019f-565">集中式記錄存放庫不得位於 DMZ 內。</span><span class="sxs-lookup"><span data-stu-id="d019f-565">The centralized logging repository must not be within the DMZ.</span></span>|
||<span data-ttu-id="d019f-566">審核追蹤 **必須** 加以保護，以確保記錄檔資料無法由威脅者變更。</span><span class="sxs-lookup"><span data-stu-id="d019f-566">­ Audit trails **MUST** be secured to ensure log data cannot be altered by a threat actor.</span></span> <span data-ttu-id="d019f-567">存取集中式記錄存放庫必須限制為僅限授權的人員。</span><span class="sxs-lookup"><span data-stu-id="d019f-567">Access to the centralized logging repository must be limited to authorized personnel only.</span></span>|
||<span data-ttu-id="d019f-568">記錄檔 **必須** 立即可供30天使用。</span><span class="sxs-lookup"><span data-stu-id="d019f-568">­ Logs **MUST** be immediately available for 30 days.</span></span> <span data-ttu-id="d019f-569">記錄資料至少 **必須** 保留90天。</span><span class="sxs-lookup"><span data-stu-id="d019f-569">Logging data **MUST** be retained for a minimum of 90 days.</span></span>|
|<span data-ttu-id="d019f-570">**檢討**</span><span class="sxs-lookup"><span data-stu-id="d019f-570">**Reviewing**</span></span> |<span data-ttu-id="d019f-571">審核程式以及支援原則和程式 **必須** 符合下列專案：</span><span class="sxs-lookup"><span data-stu-id="d019f-571">Review processes as well as supporting policies and procedures **MUST** meet the following:</span></span>|
||<span data-ttu-id="d019f-572">&#x2713; 執行每日記錄檢查，或利用自動化記錄分析和警示技術，檢查所有範圍內系統元件的事件，以找出任何可能的安全性事件。</span><span class="sxs-lookup"><span data-stu-id="d019f-572">&#x2713; Perform daily log reviews or utilize automated log analysis and alerting technology to review events from all in-scope system components to identify any potential security events.</span></span>|
||<span data-ttu-id="d019f-573">**必須** 立即遵循 &#x2713; 可能的安全性事件。</span><span class="sxs-lookup"><span data-stu-id="d019f-573">&#x2713; Potential security events **MUST** be immediately followed up.</span></span>|
|<span data-ttu-id="d019f-574">**提醒**</span><span class="sxs-lookup"><span data-stu-id="d019f-574">**Alerting**</span></span> |<span data-ttu-id="d019f-575">警示處理常式以及支援原則和程式 **必須** 符合下列各項：</span><span class="sxs-lookup"><span data-stu-id="d019f-575">Alerting processes as well as supporting policies and procedures **MUST** meet the following:</span></span> |
||<span data-ttu-id="d019f-576">&#x2713; 記錄的安全性事件會危及系統安全性、作業或資料的安全性，必須觸發立即警示，例如 (不是詳盡的清單) ：</span><span class="sxs-lookup"><span data-stu-id="d019f-576">&#x2713; Logged security events that pose a risk to the security of your systems, operations or data MUST trigger an immediate alert, for example (not an exhaustive list):</span></span>|
||<span data-ttu-id="d019f-577">&emsp;&#x25fc; 特權帳戶的建立/修改</span><span class="sxs-lookup"><span data-stu-id="d019f-577">&emsp;&#x25fc; Privilege account creation / modifications</span></span>|
||<span data-ttu-id="d019f-578">&emsp;&#x25fc; 惡意程式碼事件</span><span class="sxs-lookup"><span data-stu-id="d019f-578">&emsp;&#x25fc; Malware events</span></span>|
||<span data-ttu-id="d019f-579">&emsp;&#x25fc; 停用安全性工具</span><span class="sxs-lookup"><span data-stu-id="d019f-579">&emsp;&#x25fc; Disabling security tools</span></span>|
||<span data-ttu-id="d019f-580">&emsp;&#x25fc; 事件記錄的篡改</span><span class="sxs-lookup"><span data-stu-id="d019f-580">&emsp;&#x25fc; Event log tampering</span></span>|
||<span data-ttu-id="d019f-581">&emsp;&#x25fc; IDPS/WAF 事件 (若已設定) </span><span class="sxs-lookup"><span data-stu-id="d019f-581">&emsp;&#x25fc; IDPS / WAF events (if configured)</span></span> |
||<span data-ttu-id="d019f-582">&#x2713; 人員必須一定能使用 (24/7) 才能回應觸發的警示。</span><span class="sxs-lookup"><span data-stu-id="d019f-582">&#x2713; Staff MUST always be available (24/7) to react to triggered alerts.</span></span>|
|<span data-ttu-id="d019f-583">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-583">**Risk management**</span></span>|<span data-ttu-id="d019f-584">您必須開發並執行風險評估方法，包括下列各項：</span><span class="sxs-lookup"><span data-stu-id="d019f-584">A risk-assessment methodology must be developed and conducted that includes the following:</span></span>|
||<span data-ttu-id="d019f-585">&#x2713; 正式定義的處理常式。</span><span class="sxs-lookup"><span data-stu-id="d019f-585">&#x2713; A formally defined process.</span></span>|
||<span data-ttu-id="d019f-586">&#x2713; 一年至少執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-586">&#x2713; Performed at least annually.</span></span>|
||<span data-ttu-id="d019f-587">&#x2713; 包括範圍內環境中的所有資產。</span><span class="sxs-lookup"><span data-stu-id="d019f-587">&#x2713; Includes all assets within the in-scope environment.</span></span>|
||<span data-ttu-id="d019f-588">&#x2713; 針對所有包含的資產識別威脅和弱點。</span><span class="sxs-lookup"><span data-stu-id="d019f-588">&#x2713; Identifies threats and vulnerabilities against all included assets.</span></span>|
||<span data-ttu-id="d019f-589">&#x2713; 包括使用已定義的影響和可能性清單。</span><span class="sxs-lookup"><span data-stu-id="d019f-589">&#x2713; Includes the use of defined impact and likelihood matrices.</span></span>|
||<span data-ttu-id="d019f-590">&#x2713; 會產生風險登錄和對應風險治療計畫的建立。</span><span class="sxs-lookup"><span data-stu-id="d019f-590">&#x2713; Results in the creation of a risk register and corresponding risk treatment plan.</span></span>|
|<span data-ttu-id="d019f-591">**事件回應**</span><span class="sxs-lookup"><span data-stu-id="d019f-591">**Incident response**</span></span>|<span data-ttu-id="d019f-592">需要完整的事件回應 **方案，** 至少 **必須** 包含下列專案：</span><span class="sxs-lookup"><span data-stu-id="d019f-592">A thorough incident response plan **IS** required and **MUST** include as a minimum:</span></span>|
||<span data-ttu-id="d019f-593">在最低範圍的系統元件和應用程式的覆蓋率 &#x2713;。</span><span class="sxs-lookup"><span data-stu-id="d019f-593">&#x2713; At a minimum, coverage of the in-scope systems components and applications.</span></span>|
||<span data-ttu-id="d019f-594">&#x2713; 預期威脅模型的特定事件回應程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-594">&#x2713; Specific incident response procedures for expected threat models.</span></span>|
||<span data-ttu-id="d019f-595">&#x2713; 記錄的通訊過程，可確保所有重要專案關係人的及時通知，以及任何相關的外部主體，例如;付款商標/acquirers、法規法律和主管機構 ([GDPR](#gdpr)) 以規定的報表需求。</span><span class="sxs-lookup"><span data-stu-id="d019f-595">&#x2713; Documented communications process, ensuring the timely notification of all key stakeholders and any relevant external bodies such as; payment brands/acquirers, regulatory bodies and supervisory authorities ([GDPR](#gdpr)) in line with mandated reporting requirements.</span></span>|
||<span data-ttu-id="d019f-596">&#x2713; 事件回應會根據所學的教訓、組織變更，以及納入行業發展來更新。</span><span class="sxs-lookup"><span data-stu-id="d019f-596">&#x2713; The incident response is updated based upon lessons learned, organizational changes and to incorporate industry developments.</span></span>|
||<span data-ttu-id="d019f-597">&#x2713; 事件回應小組成員的年度訓練。</span><span class="sxs-lookup"><span data-stu-id="d019f-597">&#x2713; Annual training for members of the incident response team.</span></span>|

## <a name="data-handling-security-and-privacy"></a><span data-ttu-id="d019f-598">資料處理安全性和隱私權</span><span class="sxs-lookup"><span data-stu-id="d019f-598">Data Handling Security and Privacy</span></span>

<span data-ttu-id="d019f-599">在應用程式使用者、仲介服務和 ISV 系統之間傳輸的資料，必須透過支援最低 TLS 1.1 的 TLS 連線來保護。*請參閱*[**附錄 A**](#appendix-a)。</span><span class="sxs-lookup"><span data-stu-id="d019f-599">Data in transit between the application user, intermediary services, and ISV’s systems will be required to be protected by encryption through a TLS connection supporting a minimum of TLS v1.1.*See* [**Appendix A**](#appendix-a).</span></span>

<span data-ttu-id="d019f-600">您的應用程式會在其中檢索及儲存 M365 資料，您必須依照 [**附錄 B**](#appendix-a)中所定義的規格來執行資料儲存加密配置。</span><span class="sxs-lookup"><span data-stu-id="d019f-600">Where your application retrieves and stores M365 data you will be required to implement a data storage encryption scheme that follows the specification as defined in [**Appendix B**](#appendix-a).</span></span>

### <a name="test-specification"></a><span data-ttu-id="d019f-601">測試規格</span><span class="sxs-lookup"><span data-stu-id="d019f-601">Test Specification</span></span>

|<span data-ttu-id="d019f-602">測試</span><span class="sxs-lookup"><span data-stu-id="d019f-602">Test</span></span> | <span data-ttu-id="d019f-603">控制措施</span><span class="sxs-lookup"><span data-stu-id="d019f-603">Controls</span></span> |
| -----------------------|-------------------------------- |
|<span data-ttu-id="d019f-604">**傳輸中的資料**</span><span class="sxs-lookup"><span data-stu-id="d019f-604">**Data in Transit**</span></span>| <span data-ttu-id="d019f-605">傳輸敏感性資料時，至少必須使用 TLS 1.1，但附錄 A 所述的一些例外狀況。</span><span class="sxs-lookup"><span data-stu-id="d019f-605">Transmission of sensitive data MUST use a minimum of TLS 1.1 with a few exceptions described in Appendix A.</span></span>|
||<span data-ttu-id="d019f-606">使用附錄 B 中所述的加密設定檔， **必須** 以適當的方式加密機密資料的傳輸。</span><span class="sxs-lookup"><span data-stu-id="d019f-606">Transmission of sensitive data **MUST** be suitably encrypted in line with encryption profiles described in Appendix B.</span></span>|
||<span data-ttu-id="d019f-607">必須停用 TLS 壓縮。</span><span class="sxs-lookup"><span data-stu-id="d019f-607">TLS compression must be disabled.</span></span>|
||<span data-ttu-id="d019f-608">HSTS (HTTP Strict Transport Security) **必須** 設定成 >= 15552000</span><span class="sxs-lookup"><span data-stu-id="d019f-608">HSTS (HTTP Strict Transport Security) **MUST** be configured to >= 15552000</span></span>|
|<span data-ttu-id="d019f-609">**靜態資料**</span><span class="sxs-lookup"><span data-stu-id="d019f-609">**Data at Rest**</span></span>| <span data-ttu-id="d019f-610">機密資料存放區 **必須** 以附錄 B 中所述的加密設定檔為依據，涵蓋加密、演算法、金鑰大小、雜湊和郵件驗證的基本需求。</span><span class="sxs-lookup"><span data-stu-id="d019f-610">Sensitive data storage **MUST** be protected in line with the encryption profiles described in Appendix B covering minimum requirements of encryption, algorithms, key sizes, hashing and message authentication.</span></span>|
||<span data-ttu-id="d019f-611">所有已儲存的資料類型都必須記錄下來。</span><span class="sxs-lookup"><span data-stu-id="d019f-611">All stored data types MUST be documented.</span></span>|
|<span data-ttu-id="d019f-612">**資料保留與處置**</span><span class="sxs-lookup"><span data-stu-id="d019f-612">**Data Retention and Disposal**</span></span>|<span data-ttu-id="d019f-613">您 **必須** 先執行資料保留與處置原則、程式與程式，至少包括下列各方面的敏感性資料存放區：</span><span class="sxs-lookup"><span data-stu-id="d019f-613">Sensitive data storage **MUST** be kept to a minimum by implementing data retention and disposal policies, procedures and processes that minimally include:</span></span>|
||<span data-ttu-id="d019f-614">&#x2713; 記錄和限制法律、法規和/或業務需求所需的資料儲存量和保留時間。</span><span class="sxs-lookup"><span data-stu-id="d019f-614">&#x2713; Document and limit data storage amount and retention time to that which is required for legal, regulatory, and/or business requirements.</span></span>|
||<span data-ttu-id="d019f-615">&#x2713; 檔和部署程式，以在不再需要時，以記錄的原則進行安全刪除敏感性資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-615">&#x2713; Document and deploy processes for secure deletion of sensitive data when no longer needed, in-line with documented policies.</span></span>|
||<span data-ttu-id="d019f-616">&#x2713; 檔並部署一季程式，用以識別及安全地刪除超出定義保留期間的儲存敏感性資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-616">&#x2713; Document and deploy a quarterly process for identifying and securely deleting stored sensitive data that exceeds the defined retention period.</span></span>|
|<span data-ttu-id="d019f-617">**資料存取管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-617">**Data Access Management**</span></span>|<span data-ttu-id="d019f-618">限制具有合法業務理由的資料存取權，可協助組織避免透過 inexperience 或 malice mishandling 機密資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-618">Limiting data access to those with a legitimate business reason helps organizations prevent mishandling of sensitive data through inexperience or malice.</span></span> <span data-ttu-id="d019f-619">由應用程式/增益集及加密金鑰存取權所接收的敏感性資料，需要在所有存取層級上進行書面核准 (電子或撰寫) ，以供存取，並必須包括核准和驗證的許可權清單，以說明原則採用如下所示的指定需求：</span><span class="sxs-lookup"><span data-stu-id="d019f-619">Sensitive data, received by the app/add-in and access to encryption keys requires documented approval (electronic or in writing) for authorized parties at all access levels to access and must include a listing of approved and verified privileges demonstrating the policy incorporates the specified requirements as follows:</span></span> |
||<span data-ttu-id="d019f-620">&#x2713; 定義僅限特別需要這類特殊許可權存取之角色的存取需求和特權指派。</span><span class="sxs-lookup"><span data-stu-id="d019f-620">&#x2713; Defining access needs and privilege assignments only to roles that specifically require such privileged access.</span></span> |
||<span data-ttu-id="d019f-621">&#x2713; 限制對執行工作職責所需的最低許可權。</span><span class="sxs-lookup"><span data-stu-id="d019f-621">&#x2713; Restricting access to the least privileges necessary to perform job responsibilities.</span></span>|
||<span data-ttu-id="d019f-622">&#x2713; 確定資料共用協定與所有協力廠商消耗 M365 資料的協定相同。</span><span class="sxs-lookup"><span data-stu-id="d019f-622">&#x2713; Ensure data sharing agreements are in place with all third-parties consuming M365 data.</span></span>|
|<span data-ttu-id="d019f-623">**GDPR**</span><span class="sxs-lookup"><span data-stu-id="d019f-623">**GDPR**</span></span>| <span data-ttu-id="d019f-624">在 Microsoft 365 憑證過程中，您必須透過下列方式示範對 GDPR 的遵守：</span><span class="sxs-lookup"><span data-stu-id="d019f-624">As part of the Microsoft 365 Certification process, you must demonstrate adherence to the GDPR, either by:</span></span>|
||<span data-ttu-id="d019f-625">&#x2713; 提供由經驗豐富的外部審計公司獨立複查 GDPR 規範。</span><span class="sxs-lookup"><span data-stu-id="d019f-625">&#x2713; Providing an independent review of the GDPR conformance by an experienced external audit company.</span></span> <span data-ttu-id="d019f-626">您將需要提交報告以供審查，或允許分析員查看報告。</span><span class="sxs-lookup"><span data-stu-id="d019f-626">You will be required to submit the report for review or allow the analyst to view the report.</span></span> <span data-ttu-id="d019f-627">報告應該提供足夠的詳細資料，而不只是驗證外部審計員的評估，但是會提供完全信任，讓外部考核已確認符合 GDPR。</span><span class="sxs-lookup"><span data-stu-id="d019f-627">The report should provide enough details to not only validate the external auditor’s assessment but also provide enough confidence that the external review has confirmed conformance to the GDPR.</span></span>|
||<span data-ttu-id="d019f-628">或</span><span class="sxs-lookup"><span data-stu-id="d019f-628">or</span></span>|
||<span data-ttu-id="d019f-629">&#x2713; 提交進一步的證據，以提供對資料隱私權法律承諾的其他保證，如下所示：</span><span class="sxs-lookup"><span data-stu-id="d019f-629">&#x2713; Submitting further evidence to provide additional assurance of your commitment to data privacy laws, as follows:</span></span>|
||<span data-ttu-id="d019f-630">&#x25fc; 已記錄的主體存取要求 (SAR) 程式，其設計目的是為了符合客戶的要求，並符合 GDPR 的30天需求。</span><span class="sxs-lookup"><span data-stu-id="d019f-630">&#x25fc; A documented subject access request (SAR) process designed to meet the requests of customers and meet the thirty-day requirement of the GDPR.</span></span> <span data-ttu-id="d019f-631">建議使用適當的資料探索工具，以確保在這些時間範圍內滿足 SAR。</span><span class="sxs-lookup"><span data-stu-id="d019f-631">It is recommended that adequate data discovery tooling is in place to ensure a SAR is fulfilled within these time frames.</span></span> <span data-ttu-id="d019f-632">**附注** ：不使用這些工具時，您必須示範其運作方式，並示範處理常式如何能夠保證所有資料主體資訊的探索。</span><span class="sxs-lookup"><span data-stu-id="d019f-632">**Note** : Where these tools are not used, you will need to demonstrate how this works and demonstrate how the processes are able to guarantee discovery of all data subject’s information.</span></span>|
||<span data-ttu-id="d019f-633">&#x25fc;隱私權通知必須存在於網站上，且包含下列資訊：</span><span class="sxs-lookup"><span data-stu-id="d019f-633">&#x25fc;Privacy Notices must be present on the website and contain the following information:</span></span>
||
||<span data-ttu-id="d019f-634">若無法使用獨立的 GDPR 報告，必須先將下列專案當做 M365 認證評估的一部分加以檢查：</span><span class="sxs-lookup"><span data-stu-id="d019f-634">Where an independent GDPR report isn’t available, the following must be in place to be reviewed as part of the M365 Certification assessment:</span></span> |
||<span data-ttu-id="d019f-635">&#x2713; 已記錄的主體存取要求 (SAR) 程式，其設計目的是為了符合客戶的要求，並符合 GDPR 的30天需求。</span><span class="sxs-lookup"><span data-stu-id="d019f-635">&#x2713; A documented subject access request (SAR) process designed to meet the requests of customers and meet the thirty-day requirement of the GDPR.</span></span>  <span data-ttu-id="d019f-636">建議使用適當的資料探索工具，以確保在這些時間範圍內（未使用這些工具）完成 SAR，您將需要示範其運作方式，並示範處理常式如何能夠保證所有資料主體資訊的發現。</span><span class="sxs-lookup"><span data-stu-id="d019f-636">It is recommended that adequate data discovery tooling is in place to ensure a SAR is fulfilled within these time frames, where these tools aren't used, you will need to demonstrate how this works and demonstrate how the processes are able to guarantee discovery of all data subject’s information.</span></span>|
||<span data-ttu-id="d019f-637">&#x2713; 隱私權通知必須存在於網站上，且包含下列資訊：</span><span class="sxs-lookup"><span data-stu-id="d019f-637">&#x2713; Privacy Notices must be present on the website and contain the following information:</span></span>|
||<span data-ttu-id="d019f-638">&emsp;&emsp;&#x25a1; 組織的連絡人詳細資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-638">&emsp;&emsp;&#x25a1; Organizations contact details.</span></span>|
||<span data-ttu-id="d019f-639">&emsp;&emsp; 正在處理的個人資料&#x25a1; 類型。</span><span class="sxs-lookup"><span data-stu-id="d019f-639">&emsp;&emsp;&#x25a1; Type of personal data being processed.</span></span>|
||<span data-ttu-id="d019f-640">&emsp;&emsp;&#x25a1; Lawfulness 處理個人資料 (*文章 6*) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-640">&emsp;&emsp;&#x25a1; Lawfulness of processing personal data (*Article 6*).</span></span>|
||<span data-ttu-id="d019f-641">&emsp;&emsp; 資料主體權力的&#x25a1; 詳細資料：</span><span class="sxs-lookup"><span data-stu-id="d019f-641">&emsp;&emsp;&#x25a1; Details of data subject's rights:</span></span>|
||<span data-ttu-id="d019f-642">&emsp;&emsp;&#x25a1; (*Articles13 和 14*) 所通知的許可權。</span><span class="sxs-lookup"><span data-stu-id="d019f-642">&emsp;&emsp;&#x25a1; Right to be informed (*Articles13 and 14*).</span></span>
||<span data-ttu-id="d019f-643">&emsp;&emsp; 資料主體 (*文章 15*) 的&#x25a1; 許可權。</span><span class="sxs-lookup"><span data-stu-id="d019f-643">&emsp;&emsp;&#x25a1; Right of access by the data subject (*Article 15*).</span></span>|
||<span data-ttu-id="d019f-644">&emsp;&emsp; 修正&#x25a1; 右邊 (*文章 16*) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-644">&emsp;&emsp;&#x25a1; Right of rectification (*Article 16*).</span></span>|
||<span data-ttu-id="d019f-645">&emsp;&emsp;&#x25a1; 對 (*文章 17*) 中的擦除的權利。</span><span class="sxs-lookup"><span data-stu-id="d019f-645">&emsp;&emsp;&#x25a1; Right to erasure (*Article 17*).</span></span>|
||<span data-ttu-id="d019f-646">&emsp;&emsp;&#x25a1; (*文章 18*) 的處理限制許可權。</span><span class="sxs-lookup"><span data-stu-id="d019f-646">&emsp;&emsp;&#x25a1; Right to restriction of processing (*Article 18*).</span></span>|
||<span data-ttu-id="d019f-647">&emsp;&emsp; (*文章 20*) 中&#x25a1; 資料可攜性的權利。</span><span class="sxs-lookup"><span data-stu-id="d019f-647">&emsp;&emsp;&#x25a1; Right to data portability (*Article 20*).</span></span>|
||<span data-ttu-id="d019f-648">&emsp;&emsp;&#x25a1; 對 object 的右 () 的 *專案 21* 。</span><span class="sxs-lookup"><span data-stu-id="d019f-648">&emsp;&emsp;&#x25a1; Right to object (*Article 21*).</span></span>|
||<span data-ttu-id="d019f-649">&emsp;&emsp; 與自動決策標記相關的&#x25a1; 權利，包括分析 (*文章 22*) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-649">&emsp;&emsp;&#x25a1; Rights in relation to automated decision-marking, including profiling (*Article 22*).</span></span>|
||<span data-ttu-id="d019f-650">&#x2713; 與協力廠商共用的資訊必須具備適當的協定，才能確保處理資料主體的資料是以資料隱私權法律為依據。</span><span class="sxs-lookup"><span data-stu-id="d019f-650">&#x2713; Information sharing with third-parties must have agreements in place to ensure processing of data subject’s data are in line with data privacy laws.</span></span>|

## <a name="optional-external-compliance-frameworks-review"></a><span data-ttu-id="d019f-651">選用的外部規範框架審查</span><span class="sxs-lookup"><span data-stu-id="d019f-651">Optional External Compliance Frameworks Review</span></span>

<span data-ttu-id="d019f-652">如果外部安全性框架已包含在發行者證明內，則認證分析人員必須在 Microsoft 365 認證評估中檢查這些安全性合規性框架的合法性。</span><span class="sxs-lookup"><span data-stu-id="d019f-652">If external security frameworks have been included within the Publisher Attestation, certification analysts will need to check the validity of those security compliance frameworks as part of the Microsoft 365 Certification assessment.</span></span>
<span data-ttu-id="d019f-653">下列支援的外部安全性規範框架的證據包括：</span><span class="sxs-lookup"><span data-stu-id="d019f-653">Evidence for the following supported external security compliance frameworks include:</span></span>

* <span data-ttu-id="d019f-654">[Ism](#isms) / [Iec](#iec) -IS0/IEC 27001 規格</span><span class="sxs-lookup"><span data-stu-id="d019f-654">[ISMS](#isms)/ [IEC](#iec) - IS0/IEC 27001 specification</span></span></h5>
* [<span data-ttu-id="d019f-655">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="d019f-655">PCI DSS</span></span>](#pci-dss)
* [<span data-ttu-id="d019f-656">SOC 2</span><span class="sxs-lookup"><span data-stu-id="d019f-656">SOC 2</span></span>](#soc-2)

<span data-ttu-id="d019f-657">在「 [規範證據](#compliance-evidence) 」區段中所標示的檔，將用來執行這項審閱。</span><span class="sxs-lookup"><span data-stu-id="d019f-657">Documentation identified within the [Compliance Evidence](#compliance-evidence) section will be used to perform this review.</span></span>

### <a name="test-specifications"></a><span data-ttu-id="d019f-658">測試規格</span><span class="sxs-lookup"><span data-stu-id="d019f-658">Test Specifications</span></span>

<span data-ttu-id="d019f-659">&#x2713; 應用程式/增益集支援環境 **和** 任何支援的商務程式都 **必須** 包含在任何支援的外部安全性合規性框架範圍內，且必須在提供的檔中明確指出。</span><span class="sxs-lookup"><span data-stu-id="d019f-659">&#x2713; The App/Add-in supporting environment **AND** any supporting business processes **MUST** be included within the scope of any supported external security compliance frameworks and must be clearly indicated in supplied documentation.</span></span>

<span data-ttu-id="d019f-660">&#x2713; 支援的外部安全性合規性框架 **必須** 是最新的，亦即在過去的12個月內 (或在15months 中（如果重新評估目前正在進行中），而且可提供證據) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-660">&#x2713; Supported external security compliance frameworks **MUST** be current, i.e. within the past 12 months (or within 15months if the re-assessment is currently being carried out and evidence can be provided).</span></span>

<span data-ttu-id="d019f-661">&#x2713; 支援的外部安全性合規性框架 **必須** 由獨立于資格鑒定的公司執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-661">&#x2713; Supported external security compliance frameworks **MUST** be carried out by an independent accredited company.</span></span>

## <a name="appendix-a"></a><span data-ttu-id="d019f-662">附錄 A</span><span class="sxs-lookup"><span data-stu-id="d019f-662">Appendix A</span></span>

### <a name="tls-profile-configuration-requirements"></a><span data-ttu-id="d019f-663">TLS 設定檔設定需求</span><span class="sxs-lookup"><span data-stu-id="d019f-663">TLS Profile configuration requirements</span></span>

<span data-ttu-id="d019f-664">所有網路流量（不論是在虛擬網路、雲端服務或資料中心內）都必須受到至少 TLS 1.1 版的保護， (TLS 1.2 \* 為建議) 或其他適用的通訊協定。</span><span class="sxs-lookup"><span data-stu-id="d019f-664">All network traffic, whether within a virtual network, cloud service, or a data center, must be protected with a minimum of TLS v1.1 (TLS v1.2+ is recommended) or other applicable protocol.</span></span> <span data-ttu-id="d019f-665">此要求的例外狀況如下：</span><span class="sxs-lookup"><span data-stu-id="d019f-665">Exceptions to this requirement are:</span></span>

* <span data-ttu-id="d019f-666">**HTTP 對 HTTPS 重新導向**。</span><span class="sxs-lookup"><span data-stu-id="d019f-666">**HTTP-to-HTTPS redirect**.</span></span> <span data-ttu-id="d019f-667">您的應用程式可以透過 HTTP 回應，將用戶端重新導向至 HTTPS，但回應不能包含任何機密資料 (cookie、標頭、內容) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-667">Your app can respond over HTTP to redirect clients to HTTPS, but the response must not contain any sensitive data (cookies, headers, content).</span></span> <span data-ttu-id="d019f-668">允許除重新導向 HTTPS 和回應健康情況探查以外的其他 HTTP 回應。</span><span class="sxs-lookup"><span data-stu-id="d019f-668">No other HTTP responses other than redirects to HTTPS and responding to health probes are allowed.</span></span> <span data-ttu-id="d019f-669">請參閱下列。</span><span class="sxs-lookup"><span data-stu-id="d019f-669">See below.</span></span>
* <span data-ttu-id="d019f-670">**狀況探查**。</span><span class="sxs-lookup"><span data-stu-id="d019f-670">**Health probes**.</span></span> <span data-ttu-id="d019f-671">**只有當** 檢查者不支援 HTTPS 狀況探查時，您的應用程式才可以透過 HTTP 回應健康情況探查。</span><span class="sxs-lookup"><span data-stu-id="d019f-671">Your app can respond to health probes over HTTP **only if** HTTPS health probes are not supported by the checking party.</span></span>
* <span data-ttu-id="d019f-672">**憑證存取**。</span><span class="sxs-lookup"><span data-stu-id="d019f-672">**Certificate access**.</span></span> <span data-ttu-id="d019f-673">您可以存取 CRL、OCSP 和 AIA 端點，以取得憑證驗證和吊銷檢查的目的，可透過 HTTP 進行。</span><span class="sxs-lookup"><span data-stu-id="d019f-673">Access to CRL, OCSP, and AIA endpoints for the purposes of certificate validation and revocation checking is allowed over HTTP.</span></span>
* <span data-ttu-id="d019f-674">**本機通訊**。</span><span class="sxs-lookup"><span data-stu-id="d019f-674">**Local communications**.</span></span> <span data-ttu-id="d019f-675">您的應用程式可以使用 HTTP (或其他非受保護的通訊協定) ，以進行未留下作業系統的通訊（e）。</span><span class="sxs-lookup"><span data-stu-id="d019f-675">Your app can use HTTP (or other non-protected protocols) for communications that do not leave the operating system, e.</span></span> <span data-ttu-id="d019f-676">g.</span><span class="sxs-lookup"><span data-stu-id="d019f-676">g.</span></span> <span data-ttu-id="d019f-677">連接到在 localhost 上公開的網頁伺服器端點。</span><span class="sxs-lookup"><span data-stu-id="d019f-677">connecting to a web server endpoint exposed on localhost.</span></span>

<span data-ttu-id="d019f-678">**必須** 停用 TLS 壓縮。</span><span class="sxs-lookup"><span data-stu-id="d019f-678">TLS Compression **MUST** be disabled.</span></span>

## <a name="appendix-b"></a><span data-ttu-id="d019f-679">附錄 B</span><span class="sxs-lookup"><span data-stu-id="d019f-679">Appendix B</span></span>

### <a name="encryption-profile-configuration-requirements"></a><span data-ttu-id="d019f-680">加密設定檔設定需求</span><span class="sxs-lookup"><span data-stu-id="d019f-680">Encryption Profile Configuration Requirements</span></span>

<span data-ttu-id="d019f-681">只允許加密的基元和參數，如下所示：</span><span class="sxs-lookup"><span data-stu-id="d019f-681">Only cryptographic primitives and parameters are permitted as follows:</span></span>

### <a name="symmetric-cryptography"></a><span data-ttu-id="d019f-682">對稱密碼編譯</span><span class="sxs-lookup"><span data-stu-id="d019f-682">Symmetric cryptography</span></span>

<span data-ttu-id="d019f-683">**加密**</span><span class="sxs-lookup"><span data-stu-id="d019f-683">**Encryption**</span></span>

<span data-ttu-id="d019f-684">&emsp;&#x2713; 只允許 AES、BitLocker、Blowfish 或 TDES。</span><span class="sxs-lookup"><span data-stu-id="d019f-684">&emsp;&#x2713; Only AES, BitLocker, Blowfish or TDES are allowed.</span></span> <span data-ttu-id="d019f-685">任何支援的金鑰長度 >= 128 允許 (128、192及 256 bits) 而且可用於 256 () 。</span><span class="sxs-lookup"><span data-stu-id="d019f-685">Any of the supported key lengths >=128 are allowed (128, 192, and 256 bits) and may be used (256-bit keys are recommended).</span></span>

<span data-ttu-id="d019f-686">&emsp; 僅允許&#x2713; CBC 模式。</span><span class="sxs-lookup"><span data-stu-id="d019f-686">&emsp;&#x2713; Only CBC mode is allowed.</span></span> <span data-ttu-id="d019f-687">每個加密作業都必須使用全新的、隨機產生的初始化向量 (IV) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-687">Every encryption operation must use a fresh, randomly generated initialization vector (IV).</span></span>

<span data-ttu-id="d019f-688">&emsp;**不** 允許使用 stream 密碼的&#x2713; （例如 RC4）。</span><span class="sxs-lookup"><span data-stu-id="d019f-688">&emsp;&#x2713; Use of stream ciphers, such as RC4, **IS NOT** allowed.</span></span>

<span data-ttu-id="d019f-689">**雜湊函數**</span><span class="sxs-lookup"><span data-stu-id="d019f-689">**Hash functions**</span></span>

<span data-ttu-id="d019f-690">&emsp;&#x2713; 所有新的程式碼都必須使用 SHA-256、SHA-1-384 或 512 SHA-1 (共同稱為 SHA-2) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-690">&emsp;&#x2713; All new code must use SHA-256, SHA-384, or SHA-512 (collectively referred to as SHA-2).</span></span> <span data-ttu-id="d019f-691">輸出可能會被截斷為小於128位數</span><span class="sxs-lookup"><span data-stu-id="d019f-691">Output may be truncated to no less than 128 bits</span></span>

<span data-ttu-id="d019f-692">&emsp;&#x2713; SHA-1 只能用於相容性的考慮。</span><span class="sxs-lookup"><span data-stu-id="d019f-692">&emsp;&#x2713; SHA-1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="d019f-693">&emsp; 不允許&#x2713; 使用 MD5、MD4、MD2 及其他雜湊函數，即使是非加密應用程式也是一樣。</span><span class="sxs-lookup"><span data-stu-id="d019f-693">&emsp;&#x2713; Use of MD5, MD4, MD2 and other hash functions IS NOT allowed, even for non-cryptographic applications.</span></span>

<span data-ttu-id="d019f-694">**郵件驗證**</span><span class="sxs-lookup"><span data-stu-id="d019f-694">**Message authentication**</span></span>

<span data-ttu-id="d019f-695">&emsp;&#x2713; 所有新的程式碼都必須使用 HMAC 與其中一個已核准的雜湊函數。</span><span class="sxs-lookup"><span data-stu-id="d019f-695">&emsp;&#x2713; All new code MUST use HMAC with one of the approved hash functions.</span></span> <span data-ttu-id="d019f-696">HMAC 的輸出可能會截斷成小於128位。</span><span class="sxs-lookup"><span data-stu-id="d019f-696">Output of HMAC may be truncated to no less than 128 bits.</span></span>

<span data-ttu-id="d019f-697">&emsp;&#x2713; HMAC SHA1 只能用於相容性原因。</span><span class="sxs-lookup"><span data-stu-id="d019f-697">&emsp;&#x2713; HMAC-SHA1 may only be used for compatibility reasons.</span></span>

<span data-ttu-id="d019f-698">&emsp;&#x2713; HMAC 機碼至少必須是128位。</span><span class="sxs-lookup"><span data-stu-id="d019f-698">&emsp;&#x2713; HMAC key MUST be at least 128 bits.</span></span> <span data-ttu-id="d019f-699">建議使用256位金鑰。</span><span class="sxs-lookup"><span data-stu-id="d019f-699">256-bit keys are recommended.</span></span>

### <a name="asymmetric-algorithms"></a><span data-ttu-id="d019f-700">非對稱演算法</span><span class="sxs-lookup"><span data-stu-id="d019f-700">Asymmetric algorithms</span></span>

<span data-ttu-id="d019f-701">**加密**</span><span class="sxs-lookup"><span data-stu-id="d019f-701">**Encryption**</span></span>

<span data-ttu-id="d019f-702">&emsp; 允許&#x2713; RSA。</span><span class="sxs-lookup"><span data-stu-id="d019f-702">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="d019f-703">索引鍵 **必須** 至少要有2048位，且必須使用 OAEP 襯距。</span><span class="sxs-lookup"><span data-stu-id="d019f-703">Key **MUST** be at least 2048 bits and OAEP padding must be used.</span></span> <span data-ttu-id="d019f-704">僅允許對相容性原因使用 PKCS 填充。</span><span class="sxs-lookup"><span data-stu-id="d019f-704">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="d019f-705">**簽章**</span><span class="sxs-lookup"><span data-stu-id="d019f-705">**Signatures**</span></span>

<span data-ttu-id="d019f-706">&emsp; 允許&#x2713; RSA。</span><span class="sxs-lookup"><span data-stu-id="d019f-706">&emsp;&#x2713; RSA is allowed.</span></span> <span data-ttu-id="d019f-707">機碼 **必須** 至少要有2048位，且必須使用 PSS 的襯距。</span><span class="sxs-lookup"><span data-stu-id="d019f-707">Key **MUST** be at least 2048 bits and PSS padding must be used.</span></span> <span data-ttu-id="d019f-708">僅允許對相容性原因使用 PKCS 填充。</span><span class="sxs-lookup"><span data-stu-id="d019f-708">Use of PKCS padding only allowed for compatibility reasons.</span></span>

<span data-ttu-id="d019f-709">&emsp; 允許&#x2713;ECDSA。</span><span class="sxs-lookup"><span data-stu-id="d019f-709">&emsp;&#x2713;ECDSA is allowed.</span></span> <span data-ttu-id="d019f-710">機碼 **必須** 至少是256位。</span><span class="sxs-lookup"><span data-stu-id="d019f-710">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="d019f-711">必須使用 NIST P-256、P-384 或 P-521 曲線。</span><span class="sxs-lookup"><span data-stu-id="d019f-711">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="d019f-712">**金鑰交換**</span><span class="sxs-lookup"><span data-stu-id="d019f-712">**Key Exchange**</span></span>

<span data-ttu-id="d019f-713">&emsp; 允許&#x2713; ECDH。</span><span class="sxs-lookup"><span data-stu-id="d019f-713">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="d019f-714">機碼 **必須** 至少是256位。</span><span class="sxs-lookup"><span data-stu-id="d019f-714">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="d019f-715">必須使用 NIST P-256、P-384 或 P-521 曲線。</span><span class="sxs-lookup"><span data-stu-id="d019f-715">NIST P-256, P-384 or P-521 curve must be used.</span></span>

<span data-ttu-id="d019f-716">&emsp; 允許&#x2713; ECDH。</span><span class="sxs-lookup"><span data-stu-id="d019f-716">&emsp;&#x2713; ECDH is allowed.</span></span> <span data-ttu-id="d019f-717">機碼 **必須** 至少是256位。</span><span class="sxs-lookup"><span data-stu-id="d019f-717">Key **MUST** be at least 256 bits.</span></span> <span data-ttu-id="d019f-718">必須使用 NIST P-256、P-384 或 P-521 曲線。</span><span class="sxs-lookup"><span data-stu-id="d019f-718">NIST P-256, P-384 or P-521 curve must be used.</span></span>

## <a name="appendix-c"></a><span data-ttu-id="d019f-719">附錄 C</span><span class="sxs-lookup"><span data-stu-id="d019f-719">Appendix C</span></span>

### <a name="evidence-collection--delta-for-iso-27001"></a><span data-ttu-id="d019f-720">證據收集– ISO 27001 的 Delta</span><span class="sxs-lookup"><span data-stu-id="d019f-720">Evidence Collection – Delta for ISO 27001</span></span>

<span data-ttu-id="d019f-721">在您已獲得 ISO27001 合規性的情況下，下列 delta (間距) 並未全部在 ISO 27001 中涵蓋，至少需要在此 Microsoft 365 認證中檢查。</span><span class="sxs-lookup"><span data-stu-id="d019f-721">Where you have already attained ISO27001 compliance, the following delta’s (gaps) not wholly covered by ISO 27001 will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="d019f-722">在您的 Microsoft 365 認證評估中，認證分析員會判斷是否有任何對應的 ISO 27001 控制未納入 ISO 27001 評估的一部分，也可能會決定要包含的範例控制項，以提供進一步的保證。</span><span class="sxs-lookup"><span data-stu-id="d019f-722">As part of your Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped ISO 27001 controls were not included as part of the ISO 27001 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="d019f-723">ISO 27001 缺少的任何需求，都必須包含在您的 Microsoft 365 認證評估活動內。</span><span class="sxs-lookup"><span data-stu-id="d019f-723">Any requirements missing from the ISO 27001 will need to be included within your Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="d019f-724">**惡意程式碼防護–反病毒**</span><span class="sxs-lookup"><span data-stu-id="d019f-724">**Malware Protection – Anti Virus**</span></span>

<span data-ttu-id="d019f-725">如果惡意程式碼保護是使用應用程式控制，且在 ISO 27001 內 attested，則不需要進一步調查。</span><span class="sxs-lookup"><span data-stu-id="d019f-725">If malware protection is in place using application control and is attested to within ISO 27001 Report no further investigation is necessary.</span></span> <span data-ttu-id="d019f-726">如果沒有任何應用程式控制，認證分析程式將需要識別並評估應用程式控制機制的證據，以防止在環境內引爆惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="d019f-726">If no application control is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="d019f-727">這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-727">This will require you to:</span></span>

* <span data-ttu-id="d019f-728">示範防毒軟體是在所有抽樣的系統元件上執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-728">Demonstrate that anti-virus software is running across all sampled system components.</span></span>

* <span data-ttu-id="d019f-729">示範如何在所有抽樣系統元件上設定防病毒，以自動封鎖惡意程式碼，隔離 & 警示或警示。</span><span class="sxs-lookup"><span data-stu-id="d019f-729">Demonstrate that anti-virus is configured across all sampled system components to either automatically block malware, to quarantine & alert or to alert.</span></span>

* <span data-ttu-id="d019f-730">防毒軟體 **必須** 設定為記錄所有活動。</span><span class="sxs-lookup"><span data-stu-id="d019f-730">Anti-virus software **MUST** be configured to log all activities.</span></span>

<span data-ttu-id="d019f-731">**修補程式管理–修補程式**</span><span class="sxs-lookup"><span data-stu-id="d019f-731">**Patch Management – Patching**</span></span>

<span data-ttu-id="d019f-732">因為 ISO 27001 審計並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-732">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="d019f-733">不支援廠商的軟體元件和作業系統， **不得** 在環境內使用。</span><span class="sxs-lookup"><span data-stu-id="d019f-733">Software components and operating systems no longer supported by the vendor **MUST** not be used within the environment.</span></span> <span data-ttu-id="d019f-734">支援的原則必須已到位，以確保從環境中移除不受支援的軟體元件/作業系統，以及識別何時必須使用軟體元件的處理常式。</span><span class="sxs-lookup"><span data-stu-id="d019f-734">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place</span></span>

<span data-ttu-id="d019f-735">**弱點掃描**</span><span class="sxs-lookup"><span data-stu-id="d019f-735">**Vulnerability Scanning**</span></span>  

<span data-ttu-id="d019f-736">因為 ISO 27001 審計並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-736">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="d019f-737">示範執行每季內部及外部漏洞掃描的情況。</span><span class="sxs-lookup"><span data-stu-id="d019f-737">Demonstrate that quarterly internal and external vulnerability scanning is conducted.</span></span>

* <span data-ttu-id="d019f-738">確認支援檔根據風險排名及符合下列專案的規格，針對弱點修正進行。</span><span class="sxs-lookup"><span data-stu-id="d019f-738">Confirm supporting documentation is in place for vulnerability remediation based on risk ranking and in line with the specification as follows:</span></span>
 
 <span data-ttu-id="d019f-739">&#x2713; 以內部掃描的風險排名，線上修正所有重要及 Highs 風險問題。</span><span class="sxs-lookup"><span data-stu-id="d019f-739">&#x2713; Fix all Critical and Highs risk issues in-line with the risk ranking for Internal scanning.</span></span>
 
 <span data-ttu-id="d019f-740">&#x2713; 針對外部掃描的風險排名，修正所有重要、Highs 及中型風險的問題。</span><span class="sxs-lookup"><span data-stu-id="d019f-740">&#x2713; Fix all Critical, Highs and Medium risk issues in-line with the risk ranking for external scanning.</span></span>
 
 <span data-ttu-id="d019f-741">&#x2713; 示範修復會以已記載的漏洞修正原則進行線上。</span><span class="sxs-lookup"><span data-stu-id="d019f-741">&#x2713; Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="d019f-742">**防火牆–防火牆 (或同等技術)**</span><span class="sxs-lookup"><span data-stu-id="d019f-742">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="d019f-743">因為 ISO 27001 審計並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-743">As ISO 27001 audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="d019f-744">示範防火牆是安裝在範圍內環境的邊界上。</span><span class="sxs-lookup"><span data-stu-id="d019f-744">Demonstrate that firewalls are installed on the boundary of the in-scope environment.</span></span>

* <span data-ttu-id="d019f-745">示範如何在 DMZ 和信任的網路之間安裝防火牆。</span><span class="sxs-lookup"><span data-stu-id="d019f-745">Demonstrate that firewalls are installed between the DMZ and trusted networks.</span></span>

*   <span data-ttu-id="d019f-746">示範所有公用存取會在 DMZ 中終止。</span><span class="sxs-lookup"><span data-stu-id="d019f-746">Demonstrate that all public access terminates in the DMZ.</span></span>

*   <span data-ttu-id="d019f-747">示範在安裝到 live 環境之前，會變更預設的系統管理認證。</span><span class="sxs-lookup"><span data-stu-id="d019f-747">Demonstrate that default administrative credentials are changed prior to installation into the live environment.</span></span>

*   <span data-ttu-id="d019f-748">示範透過防火牆 (s) 所允許的所有流量，都是透過授權程式來進行，以取得業務理由的所有流量的檔。</span><span class="sxs-lookup"><span data-stu-id="d019f-748">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

*   <span data-ttu-id="d019f-749">示範所有防火牆皆已設定為丟棄未明確定義的流量。</span><span class="sxs-lookup"><span data-stu-id="d019f-749">Demonstrate that all firewalls are configured to drop traffic not explicitly defined.</span></span>

*   <span data-ttu-id="d019f-750">示範防火牆只支援所有非主控台管理介面上的強式密碼編譯。</span><span class="sxs-lookup"><span data-stu-id="d019f-750">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

*   <span data-ttu-id="d019f-751">示範防火牆對網際網路支援 MFA 所公開的非主控台管理介面。</span><span class="sxs-lookup"><span data-stu-id="d019f-751">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

*   <span data-ttu-id="d019f-752">示範至少每6個月執行防火牆規則檢查</span><span class="sxs-lookup"><span data-stu-id="d019f-752">Demonstrate that firewall rule reviews are conducted at least every 6 months</span></span>

<span data-ttu-id="d019f-753">**防火牆– Web 應用程式防火牆 (WAF)**</span><span class="sxs-lookup"><span data-stu-id="d019f-753">**Firewall – Web Application Firewalls (WAF)**</span></span>  

<span data-ttu-id="d019f-754">如果部署了 WAF，則會提供額外的信用，以協助防範大量 web 應用程式威脅，以及應用程式可以公開的漏洞。</span><span class="sxs-lookup"><span data-stu-id="d019f-754">Additional credit will be provided if a WAF is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="d019f-755">當出現 WAF 或類似的情況時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-755">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="d019f-756">示範 WAF 已設定為作用中的防禦模式，或使用警示進行監視。</span><span class="sxs-lookup"><span data-stu-id="d019f-756">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="d019f-757">示範 WAF 已設定為支援 SSL 卸載。</span><span class="sxs-lookup"><span data-stu-id="d019f-757">Demonstrate the WAF is configured to support SSL Offloading.</span></span>

* <span data-ttu-id="d019f-758">設定為依據 OWASP Core Rule Set (3.0 或 3.1) ，以防範下列大多數的攻擊類型：</span><span class="sxs-lookup"><span data-stu-id="d019f-758">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="d019f-759">&#x2713; 通訊協定和編碼的問題。</span><span class="sxs-lookup"><span data-stu-id="d019f-759">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="d019f-760">&#x2713; 頁首注入、要求 smuggling 及回應分割。</span><span class="sxs-lookup"><span data-stu-id="d019f-760">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="d019f-761">&#x2713; 檔和路徑遍歷攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-761">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="d019f-762">&#x2713; Remote file 包含 (RFI) 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-762">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="d019f-763">&#x2713; 遠端程式碼執行攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-763">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="d019f-764">&#x2713; PHP 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-764">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="d019f-765">&#x2713; 跨網站腳本攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-765">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="d019f-766">&#x2713; SQL 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-766">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="d019f-767">&#x2713; 會話 fixation 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-767">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="d019f-768">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="d019f-768">**Change Control**</span></span>

<span data-ttu-id="d019f-769">因為 ISO 27001 審計並未特別評估變更要求程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-769">As ISO 27001 audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-770">示範變更要求包含下列詳細資料：</span><span class="sxs-lookup"><span data-stu-id="d019f-770">Demonstrate that change requests have the following details:</span></span>

<span data-ttu-id="d019f-771">&#x2713; 記錄的影響。</span><span class="sxs-lookup"><span data-stu-id="d019f-771">&#x2713; Documented impact.</span></span>

<span data-ttu-id="d019f-772">&#x2713; 要執行之功能測試的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-772">&#x2713; Details of what functionality testing is to be conducted.</span></span>

<span data-ttu-id="d019f-773">&#x2713; 任何後向外程式的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-773">&#x2713; Details of any back-out procedures.</span></span>

* <span data-ttu-id="d019f-774">示範執行變更之後所進行的功能測試。</span><span class="sxs-lookup"><span data-stu-id="d019f-774">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="d019f-775">示範進行功能測試後，已登出變更要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-775">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="d019f-776">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-776">**Account Management**</span></span>

<span data-ttu-id="d019f-777">因為 ISO 27001 審計並未特別評估帳戶管理程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-777">As ISO 27001 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="d019f-778">示範如何執行 &#x2713;，以減輕重新顯示攻擊 (例如，MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-778">Demonstrate how &#x2713;s are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>
*   <span data-ttu-id="d019f-779">示範如何停用或刪除3個月內尚未使用的帳戶。</span><span class="sxs-lookup"><span data-stu-id="d019f-779">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>
*   <span data-ttu-id="d019f-780">您必須設定 &#x2713; 或其他適當的緩解措施，以保護使用者認證。</span><span class="sxs-lookup"><span data-stu-id="d019f-780">&#x2713;  or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="d019f-781">下列最小密碼原則應使用為指導方針：</span><span class="sxs-lookup"><span data-stu-id="d019f-781">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="d019f-782">&#x2713; 長度為8個字元的最小密碼長度。</span><span class="sxs-lookup"><span data-stu-id="d019f-782">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="d019f-783">&#x2713; 超過10次嘗試的帳戶鎖定閾值。</span><span class="sxs-lookup"><span data-stu-id="d019f-783">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>
 
<span data-ttu-id="d019f-784">&#x2713; 至少五個密碼的密碼歷史記錄。</span><span class="sxs-lookup"><span data-stu-id="d019f-784">&#x2713; Password history of a minimum of five passwords.</span></span>
 
<span data-ttu-id="d019f-785">&#x2713; 採用強式密碼的強制執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-785">&#x2713; Enforcement of the use of strong passwords.</span></span>
 
*   <span data-ttu-id="d019f-786">示範 MFA 是針對所有遠端存取解決方案進行設定。</span><span class="sxs-lookup"><span data-stu-id="d019f-786">Demonstrate that MFA is configured for all remote access solutions.</span></span>

*   <span data-ttu-id="d019f-787">示範如何在所有遠端存取解決方案上設定增強式加密。</span><span class="sxs-lookup"><span data-stu-id="d019f-787">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

*   <span data-ttu-id="d019f-788">公用 DNS 的管理位於範圍外的環境之外，所有能夠進行 DNS 修改的使用者帳戶都必須設定為使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="d019f-788">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="d019f-789">**侵入偵測及防護 (選用)**</span><span class="sxs-lookup"><span data-stu-id="d019f-789">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="d019f-790">當 ISO 27001 審核未特別評估入侵偵測和防護服務的某些元素 (IDPS) 程式，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-790">As ISO 27001 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="d019f-791">IDPS **應該** 在支援的環境周邊部署。</span><span class="sxs-lookup"><span data-stu-id="d019f-791">IDPS **SHOULD** be deployed at the perimeter of the supporting environment.</span></span>

*   <span data-ttu-id="d019f-792">IDPS 簽章 **應** 保留在過去一天內的最新狀態。</span><span class="sxs-lookup"><span data-stu-id="d019f-792">IDPS signatures **SHOULD** be kept current, within the past day.</span></span>

*   <span data-ttu-id="d019f-793">IDPS **應** 針對 TLS 檢查進行設定。</span><span class="sxs-lookup"><span data-stu-id="d019f-793">IDPS **SHOULD** be configured for TLS inspection.</span></span>

*   <span data-ttu-id="d019f-794">IDPS **應** 針對所有輸入和輸出流量進行設定。</span><span class="sxs-lookup"><span data-stu-id="d019f-794">IDPS **SHOULD** be configured for ALL inbound and outbound traffic.</span></span>

*   <span data-ttu-id="d019f-795">**應該** 設定 IDPS 以進行警示。</span><span class="sxs-lookup"><span data-stu-id="d019f-795">IDPS **SHOULD** be configured for alerting.</span></span>

<span data-ttu-id="d019f-796">**事件記錄**</span><span class="sxs-lookup"><span data-stu-id="d019f-796">**Event Logging**</span></span>

<span data-ttu-id="d019f-797">因為 ISO 27001 審計並未特別評估安全性事件記錄處理常式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-797">As ISO 27001 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-798">示範公開面向的系統會登入集中式記錄解決方案，而不是在 DMZ 內。</span><span class="sxs-lookup"><span data-stu-id="d019f-798">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="d019f-799">示範最少30天的記錄資料是否可以立即可用，保留90天。</span><span class="sxs-lookup"><span data-stu-id="d019f-799">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days being retained.</span></span>

<span data-ttu-id="d019f-800">**檢查 (記錄資料)**</span><span class="sxs-lookup"><span data-stu-id="d019f-800">**Reviewing (Logging Data)**</span></span>

<span data-ttu-id="d019f-801">因為 ISO 27001 審計並未特別評估此類別的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-801">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

*   <span data-ttu-id="d019f-802">示範每日記錄檢查的執行方式，以及如何識別例外狀況和異常的識別方式，以顯示如何處理這些狀況。</span><span class="sxs-lookup"><span data-stu-id="d019f-802">Demonstrate how daily log reviews are conducted and how exceptions and anomalies are identified showing how these are handled.</span></span>

<span data-ttu-id="d019f-803">**提醒**</span><span class="sxs-lookup"><span data-stu-id="d019f-803">**Alerting**</span></span>

<span data-ttu-id="d019f-804">因為 ISO 27001 審計並未特別評估此類別的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-804">As ISO 27001 audits do not specifically assess some elements of this category, this will require you to:</span></span>

* <span data-ttu-id="d019f-805">示範如何設定安全性事件，以觸發立即會審的警示。</span><span class="sxs-lookup"><span data-stu-id="d019f-805">Demonstrate how security events are configured to trigger alerts for immediate triage.</span></span>

* <span data-ttu-id="d019f-806">示範員工如何提供24/7，以回應安全性警示。</span><span class="sxs-lookup"><span data-stu-id="d019f-806">Demonstrate how staff are available 24/7 to respond to security alerts.</span></span>

<span data-ttu-id="d019f-807">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-807">**Risk Management**</span></span>

<span data-ttu-id="d019f-808">因為 ISO 27001 審計並未特別評估風險評估程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-808">As ISO 27001 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-809">示範是否已建立正式的風險管理流程。</span><span class="sxs-lookup"><span data-stu-id="d019f-809">Demonstrate that a formal risk management process is established.</span></span>

<span data-ttu-id="d019f-810">**事件回應**</span><span class="sxs-lookup"><span data-stu-id="d019f-810">**Incident Response**</span></span>

<span data-ttu-id="d019f-811">因為 ISO 27001 審計並未特別評估事件回應原則和程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-811">As ISO 27001 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

*   <span data-ttu-id="d019f-812">示範事件回應計畫/套裝程式括：</span><span class="sxs-lookup"><span data-stu-id="d019f-812">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="d019f-813">&#x2713; 預期威脅模型的特定回應程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-813">&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="d019f-814">&#x2713; 的事件處理功能會對應至 NIST Cybersecurity Framework (識別、保護、偵測、回應、復原) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-814">&#x2713; Incident handling capabilities aligning to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>
 
<span data-ttu-id="d019f-815">&#x2713; IRP 涵蓋範圍內系統。</span><span class="sxs-lookup"><span data-stu-id="d019f-815">&#x2713; The IRP covers the in-scope systems.</span></span>
 
<span data-ttu-id="d019f-816">&#x2713; 事件回應小組的年度訓練。</span><span class="sxs-lookup"><span data-stu-id="d019f-816">&#x2713; Annual training for the incident response team.</span></span>

## <a name="appendix-d"></a><span data-ttu-id="d019f-817">附錄 D</span><span class="sxs-lookup"><span data-stu-id="d019f-817">Appendix D</span></span>

### <a name="evidence-collection--deltas-for-pci-dss"></a><span data-ttu-id="d019f-818">證據集合– PCI DSS 的增量</span><span class="sxs-lookup"><span data-stu-id="d019f-818">Evidence Collection – Deltas for PCI DSS</span></span>

<span data-ttu-id="d019f-819">在您已具備 PCI DSS 規範的地方，下列 delta 的 (間距) 尚未完全涵蓋 PCI DSS，至少需要在此 Microsoft 365 憑證中查看。</span><span class="sxs-lookup"><span data-stu-id="d019f-819">Where you have already attained PCI DSS compliance, the following delta’s (gaps) not wholly covered by PCI DSS will, at a minimum, need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="d019f-820">在 Microsoft 365 認證評估中，認證分析員會判斷是否有任何對應的 PCI DSS 控制措施未納入 PCI DSS 評估的一部分，也可以決定要包含的控制項範例，以提供進一步的保證。</span><span class="sxs-lookup"><span data-stu-id="d019f-820">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped PCI DSS controls were not included as part of the PCI DSS assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="d019f-821">PCI DSS 中缺少的任何需求，都必須納入 Microsoft 365 認證評估活動。</span><span class="sxs-lookup"><span data-stu-id="d019f-821">Any requirements missing from the PCI DSS will need to be included into the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="d019f-822">**惡意程式碼保護-應用程式控制**</span><span class="sxs-lookup"><span data-stu-id="d019f-822">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="d019f-823">如果透過使用防病毒進行惡意程式碼保護，且 attested 至 PCI DSS 報告中，則不需要進一步調查。</span><span class="sxs-lookup"><span data-stu-id="d019f-823">If malware protection is in place through use of anti-virus and is attested to within PCI DSS Report no further investigation is necessary.</span></span> <span data-ttu-id="d019f-824">如果沒有任何防毒軟體，認證分析人員必須識別並評估應用程式控制機制的證據，以防止在環境內引爆惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="d019f-824">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="d019f-825">這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-825">This will require you to:</span></span> 

*   <span data-ttu-id="d019f-826">示範如何進行應用程式核准，並確認已完成此作業。</span><span class="sxs-lookup"><span data-stu-id="d019f-826">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="d019f-827">示範存在業務合理性論證的核准應用程式完整清單。</span><span class="sxs-lookup"><span data-stu-id="d019f-827">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="d019f-828">提供或示範支援檔，以詳述如何設定應用程式控制軟體，以符合特定的應用程式控制機制 (例如 whitelisting、程式碼簽署等 ) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-828">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

*   <span data-ttu-id="d019f-829">示範所有抽樣的系統元件，應用程式控制設定為已記錄。</span><span class="sxs-lookup"><span data-stu-id="d019f-829">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="d019f-830">**修補程式管理–風險排名**</span><span class="sxs-lookup"><span data-stu-id="d019f-830">**Patch Management – Risk Ranking**</span></span>

<span data-ttu-id="d019f-831">因為 PCI DSS 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-831">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="d019f-832">示範風險排名如何進行中的安全。</span><span class="sxs-lookup"><span data-stu-id="d019f-832">Demonstrate how risk ranking of vulnerabilities is conducted.</span></span>

<span data-ttu-id="d019f-833">**弱點掃描**</span><span class="sxs-lookup"><span data-stu-id="d019f-833">**Vulnerability Scanning**</span></span>

<span data-ttu-id="d019f-834">因為 PCI DSS 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-834">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="d019f-835">示範如何使用已記錄的漏洞修正原則即時進行修復。</span><span class="sxs-lookup"><span data-stu-id="d019f-835">Demonstrate that remediation is conducted in-line with the documented vulnerability remediation policy.</span></span>

<span data-ttu-id="d019f-836">**防火牆–防火牆 (或同等技術)**</span><span class="sxs-lookup"><span data-stu-id="d019f-836">**Firewall – Firewalls (or equivalent technologies)**</span></span>

<span data-ttu-id="d019f-837">因為 PCI DSS 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-837">As PCI DSS audits do not specifically assess this category, this will require you to:</span></span>

* <span data-ttu-id="d019f-838">示範防火牆只支援所有非主控台管理介面上的強式密碼編譯。</span><span class="sxs-lookup"><span data-stu-id="d019f-838">Demonstrate that firewalls support only strong cryptography on all non-console administrative interfaces.</span></span>

* <span data-ttu-id="d019f-839">示範防火牆對網際網路支援 MFA 所公開的非主控台管理介面。</span><span class="sxs-lookup"><span data-stu-id="d019f-839">Demonstrate that firewall's non-console administrative interfaces exposed to the Internet support MFA.</span></span>

<span data-ttu-id="d019f-840">如果部署的 Web 應用程式防火牆 (WAF) ，將會提供額外的信用，以協助防範大量 Web 應用程式威脅，以及應用程式可能公開的漏洞。</span><span class="sxs-lookup"><span data-stu-id="d019f-840">Additional credit will be provided if a Web Application Firewall (WAF) s deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="d019f-841">當出現 WAF 或類似的情況時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-841">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="d019f-842">示範 WAF 已設定為作用中的防禦模式，或使用警示進行監視。</span><span class="sxs-lookup"><span data-stu-id="d019f-842">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="d019f-843">示範 WAF 已設定為支援 SSL 卸載。</span><span class="sxs-lookup"><span data-stu-id="d019f-843">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="d019f-844">設定為依據 OWASP Core Rule Set (3.0 或 3.1) ，以防範下列大多數的攻擊類型：</span><span class="sxs-lookup"><span data-stu-id="d019f-844">Is configured as per the OWASP Core Rule Set (3.0 or 3.1) to protect against most of the following attack types:</span></span>

<span data-ttu-id="d019f-845">&#x2713; 通訊協定和編碼的問題。</span><span class="sxs-lookup"><span data-stu-id="d019f-845">&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="d019f-846">&#x2713; 頁首注入、要求 smuggling 及回應分割。</span><span class="sxs-lookup"><span data-stu-id="d019f-846">&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="d019f-847">&#x2713; 檔和路徑遍歷攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-847">&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="d019f-848">&#x2713; Remote file 包含 (RFI) 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-848">&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="d019f-849">&#x2713; 遠端程式碼執行攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-849">&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="d019f-850">&#x2713; PHP 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-850">&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="d019f-851">&#x2713; 跨網站腳本攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-851">&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="d019f-852">&#x2713; SQL 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-852">&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="d019f-853">&#x2713; 會話 fixation 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-853">&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="d019f-854">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="d019f-854">**Change Control**</span></span>

<span data-ttu-id="d019f-855">因為 PCI DSS 審核並未特別評估變更要求程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-855">As PCI DSS audits do not specifically assess some elements of Change Request processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-856">示範變更要求會在實際執行環境中提出之前引發。</span><span class="sxs-lookup"><span data-stu-id="d019f-856">Demonstrate that change requests are raised before being made in production environments.</span></span>

* <span data-ttu-id="d019f-857">示範在實際執行之前，必須先取得變更的授權。</span><span class="sxs-lookup"><span data-stu-id="d019f-857">Demonstrate that changes are authorized before going into production.</span></span>

* <span data-ttu-id="d019f-858">示範執行變更之後所進行的功能測試。</span><span class="sxs-lookup"><span data-stu-id="d019f-858">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="d019f-859">示範進行功能測試後，已登出變更要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-859">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="d019f-860">**安全的軟體發展/部署**</span><span class="sxs-lookup"><span data-stu-id="d019f-860">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="d019f-861">因為 PCI DSS 審核並未特別存取安全軟體發展和部署程式的某些元素，所以這需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-861">As PCI DSS audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

* <span data-ttu-id="d019f-862">程式碼存放庫必須由 MFA 保護。</span><span class="sxs-lookup"><span data-stu-id="d019f-862">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="d019f-863">必須有足夠的存取控制，才能保護代碼存放庫，避免惡意的程式碼修改。</span><span class="sxs-lookup"><span data-stu-id="d019f-863">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="d019f-864">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-864">**Account Management**</span></span>

<span data-ttu-id="d019f-865">因為 PCI DSS 審核並未特別評估帳戶管理程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-865">As PCI DSS audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-866">示範授權機制的實施方式，以減輕重新顯示攻擊 (例如，MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-866">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

* <span data-ttu-id="d019f-867">必須設定強式密碼原則或其他適當的緩解措施，以保護使用者認證。</span><span class="sxs-lookup"><span data-stu-id="d019f-867">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="d019f-868">下列最小密碼原則應使用為指導方針：</span><span class="sxs-lookup"><span data-stu-id="d019f-868">The following minimum password policy should be used as a guideline:</span></span> 

<span data-ttu-id="d019f-869">&#x2713; 長度為8個字元的最小密碼長度。</span><span class="sxs-lookup"><span data-stu-id="d019f-869">&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="d019f-870">&#x2713; 超過10次嘗試的帳戶鎖定閾值。</span><span class="sxs-lookup"><span data-stu-id="d019f-870">&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="d019f-871">&#x2713; 至少五個密碼的密碼歷史記錄。</span><span class="sxs-lookup"><span data-stu-id="d019f-871">&#x2713; Password history of a minimum of five passwords.</span></span>

<span data-ttu-id="d019f-872">&#x2713; 採用強式密碼的強制執行。</span><span class="sxs-lookup"><span data-stu-id="d019f-872">&#x2713; Enforcement of the use of strong passwords.</span></span>

* <span data-ttu-id="d019f-873">示範如何在所有遠端存取解決方案上設定增強式加密。</span><span class="sxs-lookup"><span data-stu-id="d019f-873">Demonstrate that strong encryption is configured on all remote access solutions.</span></span>

* <span data-ttu-id="d019f-874">公用 DNS 的管理位於範圍外的環境之外，所有能夠進行 DNS 修改的使用者帳戶都必須設定為使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="d019f-874">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="d019f-875">**侵入偵測及防護 (選用)**</span><span class="sxs-lookup"><span data-stu-id="d019f-875">**Intrusion Detection and Prevention (OPTIONAL)**</span></span>

<span data-ttu-id="d019f-876">因為 PCI DSS 審核並未特別評估入侵偵測及防護服務 (IDPS) 程式的某些要素，所以這需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-876">As PCI DSS audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-877">IDPS 應針對 TLS 檢查進行設定。</span><span class="sxs-lookup"><span data-stu-id="d019f-877">IDPS SHOULD be configured for TLS inspection.</span></span>

*   <span data-ttu-id="d019f-878">IDPS 應針對所有輸入和輸出流量進行設定。</span><span class="sxs-lookup"><span data-stu-id="d019f-878">IDPS SHOULD be configured for ALL inbound and outbound traffic.</span></span>

<span data-ttu-id="d019f-879">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-879">**Risk Management**</span></span>

<span data-ttu-id="d019f-880">因為 PCI DSS 審核並未特別評估風險評估程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-880">As PCI DSS audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-881">示範風險評估包含影響和可能性清單。</span><span class="sxs-lookup"><span data-stu-id="d019f-881">Demonstrate the risk assessment includes impact and likelihood matrices.</span></span>

<span data-ttu-id="d019f-882">**事件回應**</span><span class="sxs-lookup"><span data-stu-id="d019f-882">**Incident Response**</span></span>

<span data-ttu-id="d019f-883">因為 PCI DSS 審核並未特別評估事件回應原則和程式的某些要素，所以需要開發人員進行下列作業：</span><span class="sxs-lookup"><span data-stu-id="d019f-883">As PCI DSS audits don't specifically assess some elements of incident response policies and processes, this will require the developer to:</span></span>

* <span data-ttu-id="d019f-884">示範事件處理功能，使其符合 NIST Cybersecurity Framework (識別、保護、偵測、回應、復原) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-884">Demonstrate Incident handling capabilities align to NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover).</span></span>

## <a name="appendix-e"></a><span data-ttu-id="d019f-885">附錄 E</span><span class="sxs-lookup"><span data-stu-id="d019f-885">Appendix E</span></span>

### <a name="evidence-collection---deltas-for-soc-2"></a><span data-ttu-id="d019f-886">證據收集-SOC 2 的增量</span><span class="sxs-lookup"><span data-stu-id="d019f-886">Evidence Collection - Deltas for SOC 2</span></span>

<span data-ttu-id="d019f-887">在您已具備 SOC 2 相容性的情況下，下列差異的 (間距) 尚未完全涵蓋在此 Microsoft 365 認證中。</span><span class="sxs-lookup"><span data-stu-id="d019f-887">Where you have already attained SOC 2 compliance, the following delta’s (gaps) not wholly covered by SOC 2 will need to be reviewed as part of this Microsoft 365 Certification.</span></span>

> [!NOTE]
> <span data-ttu-id="d019f-888">在 Microsoft 365 認證評估中，認證分析員會判斷是否有任何對應的 SOC 2 控制項未納入于 SOC 2 評估中，也可以決定要包含的控制項範例，以提供進一步的保證。</span><span class="sxs-lookup"><span data-stu-id="d019f-888">As part of the Microsoft 365 Certification assessment, the certification analyst will determine if any of the mapped SOC 2 controls were not included as part of your SOC 2 assessment and may also decide to sample controls that were found to be included to provide further assurance.</span></span> <span data-ttu-id="d019f-889">SOC 2 評估中遺漏的任何需求，都必須納入 Microsoft 365 認證評估活動的一部分。</span><span class="sxs-lookup"><span data-stu-id="d019f-889">Any requirements missing from your SOC 2 assessment will need to be included as part of the Microsoft 365 Certification assessment activities.</span></span>

<span data-ttu-id="d019f-890">**惡意程式碼保護-應用程式控制**</span><span class="sxs-lookup"><span data-stu-id="d019f-890">**Malware Protection - Application Control**</span></span>

<span data-ttu-id="d019f-891">如果惡意程式碼防護是透過使用防毒程式所進行的，且是在 SOC 2 報表內 attested，則不需要進一步調查。</span><span class="sxs-lookup"><span data-stu-id="d019f-891">If malware protection is in place through use of anti-virus and is attested to within your SOC 2 report no further investigation is necessary.</span></span> <span data-ttu-id="d019f-892">如果沒有任何防毒軟體，認證分析人員必須識別並評估應用程式控制機制的證據，以防止在環境內引爆惡意程式碼。</span><span class="sxs-lookup"><span data-stu-id="d019f-892">If no anti-virus is in place, certification analysts will need to identify and assess evidence of application control mechanisms to prevent detonation of malware within the environment.</span></span> <span data-ttu-id="d019f-893">這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-893">This will require you to:</span></span>

* <span data-ttu-id="d019f-894">提供或示範支援檔，以詳述如何設定應用程式控制軟體，以符合特定的應用程式控制機制 (例如 whitelisting、程式碼簽署等 ) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-894">Provide or demonstrate supporting documentation is in place detailing how application control software is configured to meet specific application control mechanisms (i.e. whitelisting, code signing, etc.).</span></span>

* <span data-ttu-id="d019f-895">示範如何進行應用程式核准，並確認已完成此作業。</span><span class="sxs-lookup"><span data-stu-id="d019f-895">Demonstrate how the application approval is conducted and confirm that this is completed.</span></span>

*   <span data-ttu-id="d019f-896">示範存在業務合理性論證的核准應用程式完整清單。</span><span class="sxs-lookup"><span data-stu-id="d019f-896">Demonstrate that a complete list of approved applications with business justification exists.</span></span>

*   <span data-ttu-id="d019f-897">示範所有抽樣的系統元件，應用程式控制設定為已記錄。</span><span class="sxs-lookup"><span data-stu-id="d019f-897">Demonstrate that across all sampled system components, application control is configured as documented.</span></span>

<span data-ttu-id="d019f-898">**修補程式管理–修補程式**</span><span class="sxs-lookup"><span data-stu-id="d019f-898">**Patch Management – Patching**</span></span>

<span data-ttu-id="d019f-899">因為 SOC 2 審核並未特別評估這類類別，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-899">As SOC 2 audits do not specifically assess this category, this will require you to:</span></span>

*   <span data-ttu-id="d019f-900">所有低、中、高或嚴重問題，都必須在正常的修補使用中視窗內修補。</span><span class="sxs-lookup"><span data-stu-id="d019f-900">Any Low, Medium, High, or Critical issue must be patched within normal patching activity windows.</span></span>

*   <span data-ttu-id="d019f-901">不支援廠商的軟體元件和作業系統，不得在環境內使用。</span><span class="sxs-lookup"><span data-stu-id="d019f-901">Software components and operating systems no longer supported by the vendor MUST not be used within the environment.</span></span> <span data-ttu-id="d019f-902">支援的原則必須已到位，以確保會從環境中移除不受支援的軟體元件/作業系統，以及識別何時必須使用軟體元件的程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-902">Supporting policies MUST be in place to ensure unsupported software components / operating systems will be removed from the environment and a process to identify when software components go end-of-life must be in place.</span></span>

<span data-ttu-id="d019f-903">**防火牆–防火牆**</span><span class="sxs-lookup"><span data-stu-id="d019f-903">**Firewall – Firewalls**</span></span>

<span data-ttu-id="d019f-904">當 SOC 2 審核未特別評估變更控制至防火牆存取控制清單，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-904">As SOC 2 audits do not specifically assess change controls to firewall access control lists, this will require you to:</span></span>

* <span data-ttu-id="d019f-905">示範透過防火牆 (s) 所允許的所有流量，都是透過授權程式來進行，以取得業務理由的所有流量的檔。</span><span class="sxs-lookup"><span data-stu-id="d019f-905">Demonstrate that all permitted traffic through the firewall(s) goes through an authorization process which results in the documentation of all traffic with a business justification.</span></span>

* <span data-ttu-id="d019f-906">示範防火牆規則檢查是否至少每六個月執行一次。</span><span class="sxs-lookup"><span data-stu-id="d019f-906">Demonstrate that firewall rule reviews are conducted at least every six months.</span></span>

<span data-ttu-id="d019f-907">如果已部署 Web 應用程式防火牆 (WAF) 或類似，則會提供額外的信用，以協助防範大量 Web 應用程式威脅，以及應用程式可以公開的漏洞。</span><span class="sxs-lookup"><span data-stu-id="d019f-907">Additional credit will be provided if a Web Application Firewall (WAF) or similar is deployed to help protect against the myriad of web application threats and vulnerabilities that the application can be exposed to.</span></span> <span data-ttu-id="d019f-908">當出現 WAF 或類似的情況時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-908">When a WAF or similar is present, this will require you to:</span></span>

* <span data-ttu-id="d019f-909">示範 WAF 已設定為作用中的防禦模式，或使用警示進行監視。</span><span class="sxs-lookup"><span data-stu-id="d019f-909">Demonstrate the WAF is configured in active defense mode or monitoring more with alerting.</span></span>

* <span data-ttu-id="d019f-910">示範 WAF 已設定為支援 SSL 卸載。</span><span class="sxs-lookup"><span data-stu-id="d019f-910">Demonstrate the WAF is configured to support SSL offloading.</span></span>

* <span data-ttu-id="d019f-911">設定為依照 OWASP Core Rule Set ( (3.0 或 3.1) ，以防範下列大多數的攻擊類型：</span><span class="sxs-lookup"><span data-stu-id="d019f-911">Is configured as per the OWASP Core Rule Set ((3.0 or 3.1) to protect against the majority of the following attack types:</span></span>

<span data-ttu-id="d019f-912">&emsp;&#x2713; 通訊協定和編碼的問題。</span><span class="sxs-lookup"><span data-stu-id="d019f-912">&emsp;&#x2713; Protocol and encoding issues.</span></span>

<span data-ttu-id="d019f-913">&emsp;&#x2713; 頁首注入、要求 smuggling 及回應分割。</span><span class="sxs-lookup"><span data-stu-id="d019f-913">&emsp;&#x2713; Header injection, request smuggling, and response splitting.</span></span>

<span data-ttu-id="d019f-914">&emsp;&#x2713; 檔和路徑遍歷攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-914">&emsp;&#x2713; File and path traversal attacks.</span></span>

<span data-ttu-id="d019f-915">&emsp;&#x2713; Remote file 包含 (RFI) 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-915">&emsp;&#x2713; Remote file inclusion (RFI) attacks.</span></span>

<span data-ttu-id="d019f-916">&emsp;&#x2713; 遠端程式碼執行攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-916">&emsp;&#x2713; Remote code execution attacks.</span></span>

<span data-ttu-id="d019f-917">&emsp;&#x2713; PHP 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-917">&emsp;&#x2713; PHP-injection attacks.</span></span>

<span data-ttu-id="d019f-918">&emsp;&#x2713; 跨網站腳本攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-918">&emsp;&#x2713; Cross-site scripting attacks.</span></span>

<span data-ttu-id="d019f-919">&emsp;&#x2713; SQL 植入攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-919">&emsp;&#x2713; SQL-injection attacks.</span></span>

<span data-ttu-id="d019f-920">&emsp;&#x2713; 會話 fixation 攻擊。</span><span class="sxs-lookup"><span data-stu-id="d019f-920">&emsp;&#x2713; Session-fixation attacks.</span></span>

<span data-ttu-id="d019f-921">**變更控制**</span><span class="sxs-lookup"><span data-stu-id="d019f-921">**Change Control**</span></span>

<span data-ttu-id="d019f-922">當 SOC 2 審核並未特別評估變更要求程式的某些元素時，這需要開發人員進行下列作業：</span><span class="sxs-lookup"><span data-stu-id="d019f-922">As SOC 2 audits don't specifically assess some elements of Change Request processes, this will require the developer to:</span></span>

* <span data-ttu-id="d019f-923">示範如何將開發/測試環境與實際執行的工作環境分開，以加強責任。</span><span class="sxs-lookup"><span data-stu-id="d019f-923">Demonstrate how development / test environments are separate from the production environment enforcing separation of duties.</span></span>

* <span data-ttu-id="d019f-924">示範如何在開發/測試環境中使用即時資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-924">Demonstrate how live data isn't used within the development / test environments.</span></span>

* <span data-ttu-id="d019f-925">示範執行變更之後所進行的功能測試。</span><span class="sxs-lookup"><span data-stu-id="d019f-925">Demonstrate that functionality testing is conducted after changes are completed.</span></span>

* <span data-ttu-id="d019f-926">示範進行功能測試後，已登出變更要求。</span><span class="sxs-lookup"><span data-stu-id="d019f-926">Demonstrate that change requests are signed off after functionality testing is conducted.</span></span>

<span data-ttu-id="d019f-927">**安全的軟體發展/部署**</span><span class="sxs-lookup"><span data-stu-id="d019f-927">**Secure Software Development/Deployment**</span></span>

<span data-ttu-id="d019f-928">當 SOC 2 審核未特別存取安全軟體發展和部署程式的某些元素時，這需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-928">As SOC 2 audits do not specifically access some elements of secure software development and deployment processes; this will require to you:</span></span>

*   <span data-ttu-id="d019f-929">您必須已建立並記錄軟體發展程式，以涵蓋整個軟體發展週期。</span><span class="sxs-lookup"><span data-stu-id="d019f-929">You MUST have an established and documented software development process covering the entire software-development lifecycle.</span></span>

*   <span data-ttu-id="d019f-930">開發人員必須至少一年為安全的軟體編碼訓練。</span><span class="sxs-lookup"><span data-stu-id="d019f-930">Developers MUST undergo secure software coding training at least annually.</span></span>

*   <span data-ttu-id="d019f-931">程式碼存放庫必須由 MFA 保護。</span><span class="sxs-lookup"><span data-stu-id="d019f-931">Code repositories MUST be secured by MFA.</span></span>

*   <span data-ttu-id="d019f-932">必須有足夠的存取控制，才能保護代碼存放庫，避免惡意的程式碼修改。</span><span class="sxs-lookup"><span data-stu-id="d019f-932">Adequate access controls MUST be in place to protect code repositories against malicious code modifications.</span></span>

<span data-ttu-id="d019f-933">**帳戶管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-933">**Account Management**</span></span>

<span data-ttu-id="d019f-934">因為 SOC2 的審計並未特別評估帳戶管理程式的某些要素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-934">As SOC2 audits do not specifically assess some elements of account management processes, this will require you to:</span></span>

*   <span data-ttu-id="d019f-935">示範授權機制的實施方式，以減輕重新顯示攻擊 (例如，MFA、Kerberos) 。</span><span class="sxs-lookup"><span data-stu-id="d019f-935">Demonstrate how the authorization mechanisms are implemented to mitigate replay attacks (e.g. MFA, Kerberos).</span></span>

*   <span data-ttu-id="d019f-936">示範如何停用或刪除3個月內尚未使用的帳戶。</span><span class="sxs-lookup"><span data-stu-id="d019f-936">Demonstrate how accounts that have not been used in 3 months are either disabled or deleted.</span></span>

*   <span data-ttu-id="d019f-937">必須設定強式密碼原則或其他適當的緩解措施，以保護使用者認證。</span><span class="sxs-lookup"><span data-stu-id="d019f-937">Strong password policies or other suitable mitigations must be configured to protect user credentials.</span></span> <span data-ttu-id="d019f-938">下列最小密碼原則應使用為指導方針：</span><span class="sxs-lookup"><span data-stu-id="d019f-938">The following minimum password policy should be used as a guideline:</span></span>

<span data-ttu-id="d019f-939">&emsp;&#x2713; 長度為8個字元的最小密碼長度。</span><span class="sxs-lookup"><span data-stu-id="d019f-939">&emsp;&#x2713; Minimum password length of 8 characters.</span></span>

<span data-ttu-id="d019f-940">&emsp;&#x2713; 超過10次嘗試的帳戶鎖定閾值。</span><span class="sxs-lookup"><span data-stu-id="d019f-940">&emsp;&#x2713; Account lockout threshold of no more than 10 attempts.</span></span>

<span data-ttu-id="d019f-941">&emsp; 至少要有5個密碼的&#x2713; 密碼記錄。</span><span class="sxs-lookup"><span data-stu-id="d019f-941">&emsp;&#x2713; Password history of a minimum of 5 passwords.</span></span>

<span data-ttu-id="d019f-942">&emsp;&#x2713; 使用強式密碼的強制執行</span><span class="sxs-lookup"><span data-stu-id="d019f-942">&emsp;&#x2713; Enforcement of the use of strong passwords</span></span>

*   <span data-ttu-id="d019f-943">示範是否要將唯一的使用者帳戶發佈給所有使用者。</span><span class="sxs-lookup"><span data-stu-id="d019f-943">Demonstrate that unique user accounts are issued to all users.</span></span>

*   <span data-ttu-id="d019f-944">公用 DNS 的管理位於範圍外的環境之外，所有能夠進行 DNS 修改的使用者帳戶都必須設定為使用 MFA。</span><span class="sxs-lookup"><span data-stu-id="d019f-944">Where the management of Public DNS is outside of the in-scope environment, all user accounts able to make DNS modifications MUST be configured to use MFA.</span></span>

<span data-ttu-id="d019f-945">**入侵偵測及防護 (選用) 。**</span><span class="sxs-lookup"><span data-stu-id="d019f-945">**Intrusion Detection and Prevention (OPTIONAL).**</span></span>

<span data-ttu-id="d019f-946">當 SOC 2 審核未特別評估入侵偵測和防護服務的某些元素 (IDPS) 程式時，這將需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-946">As SOC 2 audits do not specifically assess some elements of Intrusion Detection and Prevention Services (IDPS) processes, this will require you to:</span></span>

*   <span data-ttu-id="d019f-947">IDPS 簽章應保持在最新狀態，在過去一天內</span><span class="sxs-lookup"><span data-stu-id="d019f-947">IDPS signatures SHOULD be kept current, within the past day</span></span>

*   <span data-ttu-id="d019f-948">應該針對 TLS 檢查設定 IDPS</span><span class="sxs-lookup"><span data-stu-id="d019f-948">IDPS SHOULD be configured for TLS inspection</span></span>

*   <span data-ttu-id="d019f-949">IDPS 應針對所有輸入和輸出流量進行設定</span><span class="sxs-lookup"><span data-stu-id="d019f-949">IDPS SHOULD be configured for ALL inbound and outbound traffic</span></span>

<span data-ttu-id="d019f-950">**事件記錄**</span><span class="sxs-lookup"><span data-stu-id="d019f-950">**Event Logging**</span></span>

<span data-ttu-id="d019f-951">當 SOC 2 審核未特別評估安全性事件記錄處理常式的某些元素時，這需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-951">As SOC 2 audits do not specifically assess some elements of security event logging processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-952">示範如何在範例集內的所有系統元件上設定下列系統，以記錄下列事件</span><span class="sxs-lookup"><span data-stu-id="d019f-952">Demonstrate how, on all system components within the sample set the following system are configured to log the following events</span></span>

<span data-ttu-id="d019f-953">&emsp;&#x2713; 使用者對系統元件及應用程式 (s) 的存取權。</span><span class="sxs-lookup"><span data-stu-id="d019f-953">&emsp;&#x2713; User access to system components and the application(s).</span></span>

<span data-ttu-id="d019f-954">&emsp;&#x2713; 高許可權使用者採取的所有動作。</span><span class="sxs-lookup"><span data-stu-id="d019f-954">&emsp;&#x2713; All actions taken by a high privileged user.</span></span>

<span data-ttu-id="d019f-955">&emsp;&#x2713; 不正確邏輯存取嘗試。</span><span class="sxs-lookup"><span data-stu-id="d019f-955">&emsp;&#x2713; Invalid logical access attempts.</span></span>

<span data-ttu-id="d019f-956">示範記錄的事件包含;下列資訊至少會有：</span><span class="sxs-lookup"><span data-stu-id="d019f-956">Demonstrate that logged events contain; at a minimum, the following information:</span></span>

<span data-ttu-id="d019f-957">&emsp;&#x2713; 使用者。</span><span class="sxs-lookup"><span data-stu-id="d019f-957">&emsp;&#x2713; User.</span></span>

<span data-ttu-id="d019f-958">&emsp;&#x2713; 事件種類。</span><span class="sxs-lookup"><span data-stu-id="d019f-958">&emsp;&#x2713; Type of Event.</span></span>

<span data-ttu-id="d019f-959">&emsp;&#x2713; 日期和時間。</span><span class="sxs-lookup"><span data-stu-id="d019f-959">&emsp;&#x2713; Date and Time.</span></span>

<span data-ttu-id="d019f-960">&emsp;&#x2713; 成功/失敗指示器。</span><span class="sxs-lookup"><span data-stu-id="d019f-960">&emsp;&#x2713; Success/Failure indicator.</span></span>

<span data-ttu-id="d019f-961">&emsp; 用以識別受影響系統的&#x2713; 標籤。</span><span class="sxs-lookup"><span data-stu-id="d019f-961">&emsp;&#x2713; Label to identify the affected system.</span></span>

*   <span data-ttu-id="d019f-962">示範範例集內的所有系統元件皆已設定為使用時間同步處理，而且這些元件與主要/次要時間伺服器相同。</span><span class="sxs-lookup"><span data-stu-id="d019f-962">Demonstrate that all system components within the sample set are configured to utilize time-synchronization and that these are the same as the primary/secondary time servers.</span></span>

* <span data-ttu-id="d019f-963">示範公開面向的系統會登入集中式記錄解決方案，而不是在 DMZ 內。</span><span class="sxs-lookup"><span data-stu-id="d019f-963">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

*   <span data-ttu-id="d019f-964">示範公開面向的系統會登入集中式記錄解決方案，而不是在 DMZ 內。</span><span class="sxs-lookup"><span data-stu-id="d019f-964">Demonstrate that public facing systems are logging to a centralized logging solution which isn't within the DMZ.</span></span>

* <span data-ttu-id="d019f-965">示範集中式記錄解決方案如何受到保護，以防未經授權篡改記錄資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-965">Demonstrate how the centralized logging solution is protected from unauthorized tampering of logging data.</span></span>

* <span data-ttu-id="d019f-966">示範最少30天的記錄資料如何立即可用，保留90天或更長的時間。</span><span class="sxs-lookup"><span data-stu-id="d019f-966">Demonstrate how a minimum of 30 days’ worth of logging data is immediately available, with 90 days’ or more being retained.</span></span>

<span data-ttu-id="d019f-967">**風險管理**</span><span class="sxs-lookup"><span data-stu-id="d019f-967">**Risk Management**</span></span>

<span data-ttu-id="d019f-968">因為 SOC2 的審計並未特別評估風險評估程式的某些要素，所以這會需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-968">As SOC2 audits do not specifically assess some elements of risk assessment processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-969">示範是否至少一年執行正式的風險評估。</span><span class="sxs-lookup"><span data-stu-id="d019f-969">Demonstrate that a formal risk assessment is conducted at least annually.</span></span>

<span data-ttu-id="d019f-970">*事件回應。*</span><span class="sxs-lookup"><span data-stu-id="d019f-970">*Incident Response.*</span></span>

<span data-ttu-id="d019f-971">因為 SOC2 的審計並未特別評估事件回應原則和程式的某些元素，所以需要您：</span><span class="sxs-lookup"><span data-stu-id="d019f-971">As SOC2 audits do not specifically assess some elements of incident response policies and processes, this will require you to:</span></span>

* <span data-ttu-id="d019f-972">示範事件回應計畫/套裝程式括：</span><span class="sxs-lookup"><span data-stu-id="d019f-972">Demonstrate that the incident response plan/procedure includes:</span></span>

<span data-ttu-id="d019f-973">&emsp;&#x2713; 預期威脅模型的特定回應程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-973">&emsp;&#x2713; Specific response procedures for expected threat models.</span></span>

<span data-ttu-id="d019f-974">&emsp;&#x2713; 記錄的通訊處理常式，以確保重要的專案關係人 (付款商標/acquirers、法規內文、主管機關、董事、客戶等的及時通知。</span><span class="sxs-lookup"><span data-stu-id="d019f-974">&emsp;&#x2713; Documented communications process to ensure timely notification of key stakeholders (payment brands/acquirers, regulatory bodies, supervisory authorities, directors, customers, etc.</span></span>

## <a name="appendix-f"></a><span data-ttu-id="d019f-975">附錄 F</span><span class="sxs-lookup"><span data-stu-id="d019f-975">Appendix F</span></span>

### <a name="hosting-deployment-types"></a><span data-ttu-id="d019f-976">裝載部署類型</span><span class="sxs-lookup"><span data-stu-id="d019f-976">Hosting Deployment Types</span></span>

<span data-ttu-id="d019f-977">Microsoft 承認您會在不同的主控環境中部署應用程式及儲存應用程式/增益集程式碼。</span><span class="sxs-lookup"><span data-stu-id="d019f-977">Microsoft acknowledges you will deploy applications and store app/add-in code within different hosting environments.</span></span> <span data-ttu-id="d019f-978">Microsoft 365 認證中某些安全性控制措施的整體責任將取決於所使用的主控環境。</span><span class="sxs-lookup"><span data-stu-id="d019f-978">The overall responsibilities of some of the security controls within the Microsoft 365 Certification will depend on the hosting environment being used.</span></span> <span data-ttu-id="d019f-979">附錄 F 查看常見的部署類型，並根據評估程式中評估的安全性控制來對應這些類型。</span><span class="sxs-lookup"><span data-stu-id="d019f-979">Appendix F looks at common deployment types and maps these against the security controls that are evaluated as part of the assessment process.</span></span> <span data-ttu-id="d019f-980">已識別下列主控部署類型：</span><span class="sxs-lookup"><span data-stu-id="d019f-980">The following hosting deployment types have been identified:</span></span>

|  |  |
|-----|------|
|<span data-ttu-id="d019f-981">**ISV 主控**</span><span class="sxs-lookup"><span data-stu-id="d019f-981">**ISV Hosted**</span></span>|<span data-ttu-id="d019f-982">ISV 主控類型可定義為您負責用來支援應用程式/增益集環境的基礎結構。</span><span class="sxs-lookup"><span data-stu-id="d019f-982">ISV hosted types can be defined as where you are responsible for the infrastructure used to support the app/add-in environment.</span></span> <span data-ttu-id="d019f-983">這可以實際位於您自己的資料中心或具有共同位置服務的協力廠商資料中心。</span><span class="sxs-lookup"><span data-stu-id="d019f-983">This can be physically located within your own data centers or third-party data centers with a co-location service.</span></span> <span data-ttu-id="d019f-984">最後，您擁有對支援基礎結構和作業環境的完全擁有權和系統管理控制權。</span><span class="sxs-lookup"><span data-stu-id="d019f-984">Ultimately, you have full ownership and administrative control over the supporting infrastructure and operating environment.</span></span>|
|<span data-ttu-id="d019f-985">**基礎結構即服務 (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span><span class="sxs-lookup"><span data-stu-id="d019f-985">**Infrastructure as a Service (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)</span></span>|<span data-ttu-id="d019f-986">基礎結構即服務是一種服務，可讓雲端服務提供者代之實體支援基礎結構由雲端服務提供者 (CSP) 加以管理及維護。</span><span class="sxs-lookup"><span data-stu-id="d019f-986">Infrastructure as a Service is a service that is provided whereby the physical supporting infrastructure is managed and maintained on their behalf by the cloud service provider (CSP).</span></span> <span data-ttu-id="d019f-987">通常，網路、儲存、實體伺服器及虛擬化基礎結構都是 CSP 的責任。</span><span class="sxs-lookup"><span data-stu-id="d019f-987">Typically, networking, storage, physical servers, and the virtualization infrastructure is all the responsibility of the CSP.</span></span> <span data-ttu-id="d019f-988">作業系統、中介軟體、執行時間、資料和應用程式是您的責任。</span><span class="sxs-lookup"><span data-stu-id="d019f-988">The Operating System, Middleware, Runtime, Data and Applications are the responsibilities of you.</span></span> <span data-ttu-id="d019f-989">此外，協力廠商也會管理及維護 Firewalling 功能，但防火牆規則基底的維護通常仍是消費者責任。</span><span class="sxs-lookup"><span data-stu-id="d019f-989">Firewalling capabilities would also be managed and maintained by the third-party, however maintenance of the firewall rule base would usually be still the consumers responsibility.</span></span>|
|<span data-ttu-id="d019f-990">**平臺為服務/無伺服器 (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span><span class="sxs-lookup"><span data-stu-id="d019f-990">**Platform as a Service/Serverless (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)</span></span>| <span data-ttu-id="d019f-991">透過平臺即服務，您可以使用受管理的平臺，以呈現可使用的服務。</span><span class="sxs-lookup"><span data-stu-id="d019f-991">With Platform as a Service, you are provisioned with a managed platform presenting a service that can be consumed.</span></span> <span data-ttu-id="d019f-992">您不需要執行 sysadmin 功能，因為作業系統及支援的基礎結構是由 CSP 所管理。</span><span class="sxs-lookup"><span data-stu-id="d019f-992">You do not need to perform sysadmin functions as the operating system and supporting infrastructure is managed by the CSP.</span></span> <span data-ttu-id="d019f-993">這通常是在組織不想要展示 web 服務，而是可專注于在雲端管理 web 服務上建立 web 應用程式時，使用。</span><span class="sxs-lookup"><span data-stu-id="d019f-993">This would typically be used when organizations do not want to be concerned with presenting a web service and instead can concentrate on creating the web application source code and publishing the web application on the cloud managed web services.</span></span>  <span data-ttu-id="d019f-994">另一個範例可能是資料庫服務，其中會為資料庫提供連線，但是支援基礎結構和資料庫應用程式會從消費者中抽象出來。</span><span class="sxs-lookup"><span data-stu-id="d019f-994">Another example may be a database service where connectivity is given to a database, however the supporting infrastructure and database application is abstracted from the consumer.</span></span>   <span data-ttu-id="d019f-995">**附注：「無伺服器」和「PaaS」類似，所以 Microsoft 365 證書裝載部署類型的 [無伺服器] 和 [PasS] 視為相同。**</span><span class="sxs-lookup"><span data-stu-id="d019f-995">**Note: Serverless and PaaS are similar so for the purpose of the Microsoft 365 Certification Hosting Deployment Type's Serverless and PasS are deemed the same**</span></span>|
|<span data-ttu-id="d019f-996">**混合主控**</span><span class="sxs-lookup"><span data-stu-id="d019f-996">**Hybrid Hosted**</span></span>|<span data-ttu-id="d019f-997">使用混合式主控類型時，您可以使用多個主控類型來支援支援環境的各個部分。</span><span class="sxs-lookup"><span data-stu-id="d019f-997">With the hybrid hosted type, you may utilize multiple hosted types to support various parts of the supporting environment.</span></span> <span data-ttu-id="d019f-998">在多個 M365 堆疊中使用應用程式/增益集的情況可能更多。</span><span class="sxs-lookup"><span data-stu-id="d019f-998">This may be more the case where apps/add-ins are utilized across multiple M365 stacks.</span></span> <span data-ttu-id="d019f-999">雖然 Microsoft 365 的認證將會支援跨多個 M365 服務的應用程式/附加元件的開發，但在應用程式/增益集) 的整個 (的評估，都必須以每個適當的「主控型類型對應」來評估。</span><span class="sxs-lookup"><span data-stu-id="d019f-999">Although the Microsoft 365 Certification will support where apps/add-ons across multiple M365 services are developed, an assessment of the entire (across app/add-ins) supporting environment would need to be assessed in line with each of the applicable "Hosted Type Mappings".</span></span> <span data-ttu-id="d019f-1000">在某些情況下，您可能會利用針對單一增益集的不同主控類型，在其中執行這項功能時，準則的適用性必須仍然遵循各種主控類型的「主控類型對應」準則。</span><span class="sxs-lookup"><span data-stu-id="d019f-1000">Occasionally, you may utilize different hosted types for a single add-in, where this is being carried out, applicability of criteria will need to still follow the "Hosted Type Mappings" criteria across the various hosted types.</span></span>|
|<span data-ttu-id="d019f-1001">**共用主控**</span><span class="sxs-lookup"><span data-stu-id="d019f-1001">**Shared Hosting**</span></span>|<span data-ttu-id="d019f-1002">共用主機是指在由多個個人消費者共用的平臺內主控環境的所在位置。</span><span class="sxs-lookup"><span data-stu-id="d019f-1002">Shared hosting is where you are hosting the environment within a platform that shared by multiple individual consumers.</span></span> <span data-ttu-id="d019f-1003">由於採用雲端，未寫入 Microsoft 365 憑證規格，因此共用主控不是常見的。</span><span class="sxs-lookup"><span data-stu-id="d019f-1003">The Microsoft 365 Certification Specification was not written to account for this due to the adoption of cloud, shared hosting is not common.</span></span> <span data-ttu-id="d019f-1004">如果您認為使用的是，請與 Microsoft 聯繫，因為需要建立額外的需求，以考慮此類型的主機類型下的其他風險。</span><span class="sxs-lookup"><span data-stu-id="d019f-1004">If you believe this is being used please contact Microsoft as additional requirements will need to be created to account for the additional risks under this type of hosting type.</span></span>|


## <a name="appendix-g"></a><span data-ttu-id="d019f-1005">附錄 G</span><span class="sxs-lookup"><span data-stu-id="d019f-1005">Appendix G</span></span>

### <a name="microsoft-365-certification-process-workflow"></a><span data-ttu-id="d019f-1006">Microsoft 365 證書處理常式工作流程</span><span class="sxs-lookup"><span data-stu-id="d019f-1006">Microsoft 365 Certification Process Workflow</span></span>

![工作流程](ProcessFlow.jpg)

## <a name="learn-more"></a><span data-ttu-id="d019f-1008">深入了解</span><span class="sxs-lookup"><span data-stu-id="d019f-1008">Learn more</span></span>

[<span data-ttu-id="d019f-1009">Microsoft 365 應用程式規範計畫概述</span><span class="sxs-lookup"><span data-stu-id="d019f-1009">Microsoft 365 App Compliance Program Overview</span></span>](~/overview.md)  
[<span data-ttu-id="d019f-1010">何謂 Microsoft 365 應用程式發行者認證？</span><span class="sxs-lookup"><span data-stu-id="d019f-1010">What is Microsoft 365 App Publisher Attestation?</span></span>](~/docs/attestation.md)  
[<span data-ttu-id="d019f-1011">何謂 Microsoft 365 認證？</span><span class="sxs-lookup"><span data-stu-id="d019f-1011">What is Microsoft 365 Certification?</span></span>](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a><span data-ttu-id="d019f-1012">詞彙</span><span class="sxs-lookup"><span data-stu-id="d019f-1012">Glossary</span></span>

### <a name="aia"></a><span data-ttu-id="d019f-1013">友邦 保險</span><span class="sxs-lookup"><span data-stu-id="d019f-1013">AIA</span></span>

<span data-ttu-id="d019f-1014">\* 授權資訊存取是用來尋找發證憑證授權憑證的服務位置描述項。</span><span class="sxs-lookup"><span data-stu-id="d019f-1014">\*Authority Information Access is a service location descriptor used to find the certificate of the issuing certificate authority.</span></span>

### <a name="crl"></a><span data-ttu-id="d019f-1015">Crl</span><span class="sxs-lookup"><span data-stu-id="d019f-1015">CRL</span></span>

<span data-ttu-id="d019f-1016">[\* 憑證吊銷清單] 提供一種方法，可讓安全通訊端層 (SSL) 端點，以確認從遠端主機收到的憑證是有效且可靠的。</span><span class="sxs-lookup"><span data-stu-id="d019f-1016">\*Certificate Revocation List provide a means for a Secure Sockets Layer (SSL) endpoint to verify that a certificate received from a remote host is valid and trustworthy.</span></span>

### <a name="cvss-score"></a><span data-ttu-id="d019f-1017">CVSS 分數</span><span class="sxs-lookup"><span data-stu-id="d019f-1017">CVSS score</span></span>

<span data-ttu-id="d019f-1018">[\* 常見弱點計分系統是一種已發佈的標準，可衡量弱點，並根據其嚴重性計算數值分數。</span><span class="sxs-lookup"><span data-stu-id="d019f-1018">\*Common Vulnerability Scoring System is a published standard that measures vulnerability and calculates a numerical score based on its severity.</span></span>

### <a name="cvss-patch-management-guidelines"></a><span data-ttu-id="d019f-1019">CVSS 修補程式管理指導方針</span><span class="sxs-lookup"><span data-stu-id="d019f-1019">CVSS patch management guidelines</span></span>

* <span data-ttu-id="d019f-1020">重大 (9.0-10.0) </span><span class="sxs-lookup"><span data-stu-id="d019f-1020">Critical (9.0 - 10.0)</span></span>
* <span data-ttu-id="d019f-1021">高 (7.0-8.9) </span><span class="sxs-lookup"><span data-stu-id="d019f-1021">High (7.0 - 8.9)</span></span>
* <span data-ttu-id="d019f-1022">中型 (4.0-6.9) </span><span class="sxs-lookup"><span data-stu-id="d019f-1022">Medium (4.0 - 6.9)</span></span>
* <span data-ttu-id="d019f-1023">低 (0.0-3.9) </span><span class="sxs-lookup"><span data-stu-id="d019f-1023">Low (0.0 - 3.9)</span></span>

### <a name="dmz"></a><span data-ttu-id="d019f-1024">Dmz</span><span class="sxs-lookup"><span data-stu-id="d019f-1024">DMZ</span></span>

<span data-ttu-id="d019f-1025">\* 「網路隔離區域」是一種實體或邏輯的內部網路，可直接與外部或非 propriety 網路互動，同時保持主機內部、私人網路的獨立和獨立。</span><span class="sxs-lookup"><span data-stu-id="d019f-1025">\*Demilitarized zone is a physical or logical intermediate network that interacts directly external or non-propriety networks while keeping the host's internal, private network separate and isolated.</span></span>

### <a name="euii"></a><span data-ttu-id="d019f-1026">EUII</span><span class="sxs-lookup"><span data-stu-id="d019f-1026">EUII</span></span>

<span data-ttu-id="d019f-1027">*使用者識別資訊*。</span><span class="sxs-lookup"><span data-stu-id="d019f-1027">*End-user identifiable information*.</span></span>

### <a name="gdpr"></a><span data-ttu-id="d019f-1028">GDPR</span><span class="sxs-lookup"><span data-stu-id="d019f-1028">GDPR</span></span>

<span data-ttu-id="d019f-1029">\* 一般資料保護規定是歐盟 (歐盟) 隱私權和資料保護法規的所有歐盟公民的資料，不論您的應用程式網站位於何處。</span><span class="sxs-lookup"><span data-stu-id="d019f-1029">\*General Data Protection Regulation is a European Union (EU) privacy and data protection regulation for all EU citizens’ data regardless of where your application site is located.</span></span>

### <a name="hsts"></a><span data-ttu-id="d019f-1030">HSTS</span><span class="sxs-lookup"><span data-stu-id="d019f-1030">HSTS</span></span>

<span data-ttu-id="d019f-1031">\* HTTP Strict Transport Security 利用 HTTP 回應標頭指示網頁瀏覽器僅透過 HTTPS 存取內容。</span><span class="sxs-lookup"><span data-stu-id="d019f-1031">\*HTTP Strict Transport Security utilizes a HTTP response header instructing the web browser to only access content over HTTPS.</span></span>  <span data-ttu-id="d019f-1032">這是為了防範降級攻擊和 cookie 劫持所設計。</span><span class="sxs-lookup"><span data-stu-id="d019f-1032">This is designed to protect against downgrade attacks and cookie hijacking.</span></span>

### <a name="iec"></a><span data-ttu-id="d019f-1033">Iec</span><span class="sxs-lookup"><span data-stu-id="d019f-1033">IEC</span></span>

<span data-ttu-id="d019f-1034">\* 國際 Electrotechnical 傭金。</span><span class="sxs-lookup"><span data-stu-id="d019f-1034">\*International Electrotechnical Commission.</span></span>

### <a name="isms"></a><span data-ttu-id="d019f-1035">主義</span><span class="sxs-lookup"><span data-stu-id="d019f-1035">ISMS</span></span>

<span data-ttu-id="d019f-1036">\* 資訊安全性管理系統。</span><span class="sxs-lookup"><span data-stu-id="d019f-1036">\*Information Security Management System.</span></span>

### <a name="isv"></a><span data-ttu-id="d019f-1037">ISV</span><span class="sxs-lookup"><span data-stu-id="d019f-1037">ISV</span></span>

<span data-ttu-id="d019f-1038">獨立的安全性廠商是一個人和組織，可在協力廠商軟體和硬體平臺上開發、投放及銷售軟體。</span><span class="sxs-lookup"><span data-stu-id="d019f-1038">Independent Security Vendors are individuals and organizations who develop, market and sell software that runs on third-party software and hardware platforms.</span></span>

### <a name="iso-27001"></a><span data-ttu-id="d019f-1039">ISO 27001</span><span class="sxs-lookup"><span data-stu-id="d019f-1039">ISO 27001</span></span>

<span data-ttu-id="d019f-1040">組織中的所有技術控制措施的資訊安全性管理系統規格架構。</span><span class="sxs-lookup"><span data-stu-id="d019f-1040">An information security management system specification framework for all technical controls in an organizations risk management policies and procedures processes.</span></span>

### <a name="lfi"></a><span data-ttu-id="d019f-1041">LFI</span><span class="sxs-lookup"><span data-stu-id="d019f-1041">LFI</span></span>

<span data-ttu-id="d019f-1042">*本機檔包含* 可讓攻擊者透過網頁瀏覽器在伺服器上包含檔案。</span><span class="sxs-lookup"><span data-stu-id="d019f-1042">*Local File Inclusion* allows an attacker to include files on a server through the web browser.</span></span>

### <a name="nist"></a><span data-ttu-id="d019f-1043">Nist</span><span class="sxs-lookup"><span data-stu-id="d019f-1043">NIST</span></span>

<span data-ttu-id="d019f-1044">*國家安全局* 的國家標準 (NIST) 中，美國 Commerce 的非規章機關為我們提供的私營部門組織提供指導，以評估和核准其阻止、偵測及回應網路攻擊的能力。</span><span class="sxs-lookup"><span data-stu-id="d019f-1044">The *National Institute of Standards* (NIST), a non-regulatory agency of the U.S. Department of Commerce  provides guidance for private sector organizations in the US to assess and approve their ability to prevent, detect, and respond to cyber attacks.</span></span>

### <a name="non-significant-changes"></a><span data-ttu-id="d019f-1045">非重大變更</span><span class="sxs-lookup"><span data-stu-id="d019f-1045">Non-Significant changes</span></span>

* <span data-ttu-id="d019f-1046">次要錯誤修正。</span><span class="sxs-lookup"><span data-stu-id="d019f-1046">Minor Bug fixes.</span></span>
* <span data-ttu-id="d019f-1047">次要效能增強。</span><span class="sxs-lookup"><span data-stu-id="d019f-1047">Minor performance improvements.</span></span>
* <span data-ttu-id="d019f-1048">作業系統/文件庫/用戶端與伺服器應用程式。</span><span class="sxs-lookup"><span data-stu-id="d019f-1048">Operating systems/libraries/client and server application patches.</span></span>

### <a name="ocsp"></a><span data-ttu-id="d019f-1049">OCSP</span><span class="sxs-lookup"><span data-stu-id="d019f-1049">OCSP</span></span>

<span data-ttu-id="d019f-1050">*線上憑證狀態通訊協定* 是用來檢查 x.509 數位憑證的吊銷狀態。</span><span class="sxs-lookup"><span data-stu-id="d019f-1050">*Online Certificate Status Protocol* is used to check the revocation status of X.509 digital certificates.</span></span>

### <a name="oii"></a><span data-ttu-id="d019f-1051">OII</span><span class="sxs-lookup"><span data-stu-id="d019f-1051">OII</span></span>

<span data-ttu-id="d019f-1052">*組織識別資訊*。</span><span class="sxs-lookup"><span data-stu-id="d019f-1052">*Organizational identifiable information*.</span></span>

### <a name="owasp"></a><span data-ttu-id="d019f-1053">OWASP</span><span class="sxs-lookup"><span data-stu-id="d019f-1053">OWASP</span></span>

<span data-ttu-id="d019f-1054">*開啟 Web 應用程式安全性專案*。</span><span class="sxs-lookup"><span data-stu-id="d019f-1054">*Open Web Application Security Project*.</span></span>

### <a name="pci-dss"></a><span data-ttu-id="d019f-1055">PCI DSS</span><span class="sxs-lookup"><span data-stu-id="d019f-1055">PCI DSS</span></span>

<span data-ttu-id="d019f-1056">*支付卡行業資料安全性標準*-維護全球持卡人資料之安全性標準的組織。</span><span class="sxs-lookup"><span data-stu-id="d019f-1056">*Payment Card Industry Data Security Standard*, an organization that maintains standards for the safety of cardholder data worldwide.</span></span>

### <a name="pen-testing"></a><span data-ttu-id="d019f-1057">畫筆測試</span><span class="sxs-lookup"><span data-stu-id="d019f-1057">Pen testing</span></span>

<span data-ttu-id="d019f-1058">*滲透測試* 是一種測試 web 應用程式的方法，它會類比惡意攻擊，以找出攻擊者可能會利用的安全性弱點。</span><span class="sxs-lookup"><span data-stu-id="d019f-1058">*Penetration testing* is a method of testing a web app by simulating malicious attacks to find security vulnerabilities that an attacker could exploit.</span></span>

### <a name="saml"></a><span data-ttu-id="d019f-1059">Saml</span><span class="sxs-lookup"><span data-stu-id="d019f-1059">SAML</span></span>

<span data-ttu-id="d019f-1060">*安全性聲明標記語言* 是一種開放的標準，用來交換使用者、身分識別提供者和服務提供者之間的驗證和授權資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-1060">*Security Assertion Markup Language* is s an open standard for exchanging authentication and authorization data between the user, the identity provider and the service provider.</span></span>

### <a name="sensitive-data"></a><span data-ttu-id="d019f-1061">機密資料</span><span class="sxs-lookup"><span data-stu-id="d019f-1061">Sensitive Data</span></span>

* <span data-ttu-id="d019f-1062">存取控制資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-1062">Access control data.</span></span>
* <span data-ttu-id="d019f-1063">客戶內容。</span><span class="sxs-lookup"><span data-stu-id="d019f-1063">Customer content.</span></span>
* <span data-ttu-id="d019f-1064">使用者身分識別資訊。</span><span class="sxs-lookup"><span data-stu-id="d019f-1064">End-user identity information.</span></span>
* <span data-ttu-id="d019f-1065">支援資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-1065">Support data.</span></span>
* <span data-ttu-id="d019f-1066">公用個人資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-1066">Public personal data.</span></span>
* <span data-ttu-id="d019f-1067">使用者 pseudonymous 資訊。</span><span class="sxs-lookup"><span data-stu-id="d019f-1067">End-user pseudonymous information.</span></span>

### <a name="significant-changes"></a><span data-ttu-id="d019f-1068">重大變更</span><span class="sxs-lookup"><span data-stu-id="d019f-1068">Significant changes</span></span>

* <span data-ttu-id="d019f-1069">主控環境的重新安置。</span><span class="sxs-lookup"><span data-stu-id="d019f-1069">Relocation of the hosting environment.</span></span>
* <span data-ttu-id="d019f-1070">支援基礎結構的主要升級;例如，實施新的防火牆，主要升級至正面服務等等。</span><span class="sxs-lookup"><span data-stu-id="d019f-1070">Major upgrades to the supporting infrastructure; for example, implementation of a new firewall, major upgrades to front facing services, etc.</span></span>
* <span data-ttu-id="d019f-1071">您的應用程式新增功能和/or 擴充功能。</span><span class="sxs-lookup"><span data-stu-id="d019f-1071">Addition of capabilities and /or extensions to your app.</span></span>
* <span data-ttu-id="d019f-1072">更新您的應用程式，以捕獲其他的敏感性資料。</span><span class="sxs-lookup"><span data-stu-id="d019f-1072">Updates to your app that capture additional sensitive Data.</span></span>
* <span data-ttu-id="d019f-1073">對應用程式的資料流程或授權模型所做的變更</span><span class="sxs-lookup"><span data-stu-id="d019f-1073">Changes to your app's data flows or authorization models</span></span>
* <span data-ttu-id="d019f-1074">加入 API 端點或 API 端點函數。</span><span class="sxs-lookup"><span data-stu-id="d019f-1074">Addition of API endpoints or API endpoint functions.</span></span>

### <a name="soc-2"></a><span data-ttu-id="d019f-1075">SOC 2</span><span class="sxs-lookup"><span data-stu-id="d019f-1075">SOC 2</span></span>

<span data-ttu-id="d019f-1076">*服務組織控制 2*：由五個信任服務原則組成的技術審核程式，可確保服務提供者安全地管理組織之用戶端的資料與隱私權。</span><span class="sxs-lookup"><span data-stu-id="d019f-1076">*Service Organization Control 2*, a technical auditing procedure comprised of five Trust Service Principles to ensure that service providers securely manage the data and privacy for an organization's clients.</span></span>

### <a name="ssl"></a><span data-ttu-id="d019f-1077">Ssl</span><span class="sxs-lookup"><span data-stu-id="d019f-1077">SSL</span></span>

<span data-ttu-id="d019f-1078">*安全通訊端層*。</span><span class="sxs-lookup"><span data-stu-id="d019f-1078">*Secure Sockets Layer*.</span></span>

### <a name="tls"></a><span data-ttu-id="d019f-1079">TLS</span><span class="sxs-lookup"><span data-stu-id="d019f-1079">TLS</span></span>

<span data-ttu-id="d019f-1080">*傳輸層安全性*。</span><span class="sxs-lookup"><span data-stu-id="d019f-1080">*Transport Layer Security*.</span></span>
