---
title: 使用者指南
author: LGerrard
ms.author: legerrar
description: Microsoft 365 應用程式規範計畫的 ISV 使用者指南
keywords: Microsoft 365 應用程式規範計畫的 ISV 使用者指南
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 0a9c60bda8e9710957ba238f1fe7a96ca0039ea3
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/28/2021
ms.locfileid: "52070932"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program"></a><span data-ttu-id="1b898-104">Microsoft 365 應用程式規範計畫的合作夥伴使用者指南</span><span class="sxs-lookup"><span data-stu-id="1b898-104">Partner's User Guide for Microsoft 365 App Compliance Program</span></span>

|||
|---|---|
|<span data-ttu-id="1b898-105">第1層</span><span class="sxs-lookup"><span data-stu-id="1b898-105">Tier 1</span></span>| <span data-ttu-id="1b898-106">發行者證明</span><span class="sxs-lookup"><span data-stu-id="1b898-106">Publisher Attestation</span></span>|
|<span data-ttu-id="1b898-107">第2層</span><span class="sxs-lookup"><span data-stu-id="1b898-107">Tier 2</span></span>| <span data-ttu-id="1b898-108">Microsoft 365 認證</span><span class="sxs-lookup"><span data-stu-id="1b898-108">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="1b898-109">1. 簡介</span><span class="sxs-lookup"><span data-stu-id="1b898-109">1. Overview</span></span>
<span data-ttu-id="1b898-110">這份檔是為我們的合作夥伴做為逐步使用者指南，註冊 Microsoft 365 應用程式相容性計畫，其意圖是透過發行者證明和憑證，不過是合作夥伴中心入口網站。</span><span class="sxs-lookup"><span data-stu-id="1b898-110">This document acts as a step-by-step user guide for our Partners, enrolled for Microsoft 365 App Compliance Program aiming to undergo Publisher Attestation and Certification though Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="1b898-111">2. 縮寫 & 定義</span><span class="sxs-lookup"><span data-stu-id="1b898-111">2. Acronyms & Definitions</span></span>
| | |
|---|----|
|<span data-ttu-id="1b898-112">縮略字</span><span class="sxs-lookup"><span data-stu-id="1b898-112">Acronym</span></span> | <span data-ttu-id="1b898-113">定義</span><span class="sxs-lookup"><span data-stu-id="1b898-113">Definition</span></span> |
|<span data-ttu-id="1b898-114">電腦 (合作夥伴中心) </span><span class="sxs-lookup"><span data-stu-id="1b898-114">PC (Partner Center)</span></span>|<span data-ttu-id="1b898-115">所有 Microsoft 合作夥伴的入口網站。</span><span class="sxs-lookup"><span data-stu-id="1b898-115">A portal for all Microsoft Partners.</span></span> <span data-ttu-id="1b898-116">合作夥伴會登入至夥伴中心，並提交 Self-Assessment 問卷 https://partner.microsoft.com/</span><span class="sxs-lookup"><span data-stu-id="1b898-116">A Partner logs in to Partner Center and submits Self-Assessment Questionnaire https://partner.microsoft.com/</span></span>|
|<span data-ttu-id="1b898-117">ISV</span><span class="sxs-lookup"><span data-stu-id="1b898-117">ISV</span></span>|<span data-ttu-id="1b898-118">獨立軟體廠商 A.k.a。</span><span class="sxs-lookup"><span data-stu-id="1b898-118">Independent Software Vendor A.k.a.</span></span> <span data-ttu-id="1b898-119">Partner or Developer</span><span class="sxs-lookup"><span data-stu-id="1b898-119">Partner or Developer</span></span>|
|<span data-ttu-id="1b898-120">應用程式來源</span><span class="sxs-lookup"><span data-stu-id="1b898-120">App Source</span></span>| <span data-ttu-id="1b898-121"> (的應用程式目錄 https://appsource.microsoft.com/)</span><span class="sxs-lookup"><span data-stu-id="1b898-121">Catalog of apps (https://appsource.microsoft.com/)</span></span>
||<span data-ttu-id="1b898-122">範例：現在，虛擬代理程式 (https://appsource.microsoft.com/en-us/product/office/WA104381816)</span><span class="sxs-lookup"><span data-stu-id="1b898-122">Example: Now virtual agent (https://appsource.microsoft.com/en-us/product/office/WA104381816)</span></span>|

## <a name="3---publisher-attestation-workflow"></a><span data-ttu-id="1b898-123">3. 發行者證明工作流程</span><span class="sxs-lookup"><span data-stu-id="1b898-123">3.   Publisher Attestation Workflow</span></span>

<span data-ttu-id="1b898-124">首頁：這是一次夥伴登入夥伴中心的登陸頁面。</span><span class="sxs-lookup"><span data-stu-id="1b898-124">Home Page: This is the landing page once a partner logs in to Partner Center.</span></span>

![合作夥伴中心主畫面](../media/Picture1.png)

<span data-ttu-id="1b898-126">**步驟 1**   ：在頁面左側的導覽列中：</span><span class="sxs-lookup"><span data-stu-id="1b898-126">**Step 1**   : On the left side of the page, in the navigation bar:</span></span>
1. <span data-ttu-id="1b898-127">選取 Office 存放區</span><span class="sxs-lookup"><span data-stu-id="1b898-127">Select Office store</span></span>
1. <span data-ttu-id="1b898-128">選取一覽</span><span class="sxs-lookup"><span data-stu-id="1b898-128">Select Overview</span></span>

![您可以在左側導覽找到 Office 存放區](../media/Picture2.png)

<span data-ttu-id="1b898-130">選取「一覽」時，partner 可以查看透過夥伴中心提交且適用于 Microsoft 365 規範計畫的應用程式清單。</span><span class="sxs-lookup"><span data-stu-id="1b898-130">Upon selecting ‘Overview’, partner can see list of apps submitted through Partner Center and available for the Microsoft 365 Compliance program.</span></span>

<span data-ttu-id="1b898-131">**步驟 2** ：從清單中選取應用程式，以開始發行者證明程式。</span><span class="sxs-lookup"><span data-stu-id="1b898-131">**Step 2** : Select an app from the list to begin the Publisher Attestation process.</span></span>

![選擇您要證明哪個應用程式](../media/Picture3.png)

<span data-ttu-id="1b898-133">選取應用程式時，會彈出另一個導覽列，其中包含選項「應用程式相容性」</span><span class="sxs-lookup"><span data-stu-id="1b898-133">On selecting an app, another navigation bar will pop up with option ‘App Compliance’</span></span>

<span data-ttu-id="1b898-134">**步驟 3**：選取「應用程式符合性」</span><span class="sxs-lookup"><span data-stu-id="1b898-134">**Step 3**: Select ‘App Compliance’</span></span>

![選取應用程式規範](../media/App%20compliance%20step%203.png)

<span data-ttu-id="1b898-136">**步驟 4**：填寫發行者證明的 Self-Assessment 問卷</span><span class="sxs-lookup"><span data-stu-id="1b898-136">**Step 4**: Fill out the Self-Assessment Questionnaire for Publisher Attestation</span></span>

![匯入/匯出](../media/step4-new%20add.PNG)

![匯入/匯出](../media/NewFeature%20impExp.PNG)

<span data-ttu-id="1b898-139">**附注**：如果您要回到更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [複製]。</span><span class="sxs-lookup"><span data-stu-id="1b898-139">**Note**:If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘clone’.</span></span>

<span data-ttu-id="1b898-140">![複製 ](../media/clone.PNG)
 ![ Clone2](../media/clone2.PNG)</span><span class="sxs-lookup"><span data-stu-id="1b898-140">![CLone](../media/clone.PNG)
![Clone2](../media/clone2.PNG)</span></span>

<span data-ttu-id="1b898-141">您也可以利用 [匯入/匯出] 功能，離線完成該表單，並在完成後將其匯入。</span><span class="sxs-lookup"><span data-stu-id="1b898-141">You can also leverage the Import/Export feature to complete the form offline and import it once completed.</span></span> 

<span data-ttu-id="1b898-142">**步驟 5**：完成後，按一下 [提交]，評估現在會是「審閱」。</span><span class="sxs-lookup"><span data-stu-id="1b898-142">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘under review’.</span></span>

![按一下 Sumbit](../media/Picture8.png)

![審閱現在正在進行中](../media/Picture9.png)

### <a name="approvereject-scenarios"></a><span data-ttu-id="1b898-145">核准/拒絕案例：</span><span class="sxs-lookup"><span data-stu-id="1b898-145">Approve/Reject Scenarios:</span></span>

<span data-ttu-id="1b898-146">**發行者證明拒絕**</span><span class="sxs-lookup"><span data-stu-id="1b898-146">**A.Publisher Attestation Rejection**</span></span>

<span data-ttu-id="1b898-147">在此階段遭到拒絕時，合作夥伴可以：</span><span class="sxs-lookup"><span data-stu-id="1b898-147">In case of rejection at this stage, an partner can:</span></span>
-   <span data-ttu-id="1b898-148">View 失敗報告。</span><span class="sxs-lookup"><span data-stu-id="1b898-148">View failure report.</span></span>
    - <span data-ttu-id="1b898-149">合作夥伴將會透過電子郵件通知合作夥伴中心。</span><span class="sxs-lookup"><span data-stu-id="1b898-149">Partner will be notified in Partner Center and via email.</span></span>
-   <span data-ttu-id="1b898-150">更新 Self-Assessment 的回應。</span><span class="sxs-lookup"><span data-stu-id="1b898-150">Update Self-Assessment responses.</span></span>
-   <span data-ttu-id="1b898-151">重新提交自我評估。</span><span class="sxs-lookup"><span data-stu-id="1b898-151">Re-submit Self-Assessment.</span></span>

![更新並重新提交評估](../media/Picture10.png)

<span data-ttu-id="1b898-153">**B. 發行者證明重新提交**</span><span class="sxs-lookup"><span data-stu-id="1b898-153">**B.Publisher Attestation Re-submission**</span></span>

![在審閱下重新提交](../media/PA%20resubmission.png)

<span data-ttu-id="1b898-155">**C. 發行者證明核准**</span><span class="sxs-lookup"><span data-stu-id="1b898-155">**C.Publisher Attestation Approval**</span></span>

-   <span data-ttu-id="1b898-156">在核准合作夥伴可以執行下列作業：</span><span class="sxs-lookup"><span data-stu-id="1b898-156">Upon approval partner can:</span></span>
    - <span data-ttu-id="1b898-157">更新並重新提交證明</span><span class="sxs-lookup"><span data-stu-id="1b898-157">Update and resubmit attestation</span></span>
    - <span data-ttu-id="1b898-158">查看和共用已完成的 Publisher 證明</span><span class="sxs-lookup"><span data-stu-id="1b898-158">View and share completed Publisher Attestation</span></span>
    - <span data-ttu-id="1b898-159">開始 M365 認證處理常式</span><span class="sxs-lookup"><span data-stu-id="1b898-159">Start M365 Certification Process</span></span>

![更新並重新提交](../media/AttestApproval.PNG)

![<span data-ttu-id="1b898-161">查看已完成的證明</span><span class="sxs-lookup"><span data-stu-id="1b898-161">View completed attestation</span></span> ](../media/PA%20approval%202.png)

![開始 M365 應用程式認證](../media/PA%20approval%203.png)

<span data-ttu-id="1b898-163">**發佈發行者驗證核准： publisher attested 應用程式的 AppSource 連結範例**</span><span class="sxs-lookup"><span data-stu-id="1b898-163">**Post Publisher Verification Approval: Example of link in AppSource for publisher attested apps**</span></span>

![完成證明的範例](../media/Example%20to%20attested%20apps.png)

## <a name="4-microsoft-365-certification-workflow"></a><span data-ttu-id="1b898-165">4. Microsoft 365 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="1b898-165">4. Microsoft 365 Certification Workflow</span></span>

<span data-ttu-id="1b898-166">協力廠商按一下「提交」並提交所有檔和證據進行審閱之後：</span><span class="sxs-lookup"><span data-stu-id="1b898-166">Once partner clicks on ‘Submit’ and submits all documents and evidence for review:</span></span> 

### <a name="microsoft-365-certification---submitted"></a><span data-ttu-id="1b898-167">Microsoft 365 認證-已提交</span><span class="sxs-lookup"><span data-stu-id="1b898-167">Microsoft 365 Certification - Submitted</span></span>

![已開始認證](../media/certification%201.png)

<span data-ttu-id="1b898-169">**Microsoft 365 認證-已拒絕**</span><span class="sxs-lookup"><span data-stu-id="1b898-169">**Microsoft 365 certification - Rejected**</span></span>

![拒絕的憑證](../media/certification%20rejected.png)

<span data-ttu-id="1b898-171">**Microsoft 365 認證-已核准**</span><span class="sxs-lookup"><span data-stu-id="1b898-171">**Microsoft 365 Certification - Approved**</span></span>

![已核准認證](../media/certification%20approved.png)

<span data-ttu-id="1b898-173">**後憑證核准： AppSource 中的 Microsoft 365 認證徽章範例**</span><span class="sxs-lookup"><span data-stu-id="1b898-173">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource**</span></span>

![認證標記範例](../media/post%20certification%20badge.png)

## <a name="5-workflow-for-existing-isvs"></a><span data-ttu-id="1b898-175">5. 現有 Isv 的工作流程</span><span class="sxs-lookup"><span data-stu-id="1b898-175">5. Workflow for Existing ISVs</span></span>

<span data-ttu-id="1b898-176">如果您是現有的 ISV，且想要更新發行者證明。</span><span class="sxs-lookup"><span data-stu-id="1b898-176">If you are an existing ISV and want to Update Publisher Attestation.</span></span>

<span data-ttu-id="1b898-177">**步驟 1**：按一下「更新並重新提交發行者證明」連結。</span><span class="sxs-lookup"><span data-stu-id="1b898-177">**Step 1**: Click on ‘Update and re-submit your Publisher Attestation’ link.</span></span>

![<span data-ttu-id="1b898-178">更新發行者證明</span><span class="sxs-lookup"><span data-stu-id="1b898-178">Update Publisher Attestation</span></span> ](../media/existing%20isv%201.png)

<span data-ttu-id="1b898-179">**附注：**：如果您要回到更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [匯入]。</span><span class="sxs-lookup"><span data-stu-id="1b898-179">**Note:**: If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Import’.</span></span>

![針對不同整合的匯入證明](../media/M365%20App%20compliance.png)

![按一下 [匯入](../media/M365%20App%20compliance1.png)

<span data-ttu-id="1b898-182">**步驟 2**：對表單進行更新，然後按一下 [儲存/提交]。</span><span class="sxs-lookup"><span data-stu-id="1b898-182">**Step 2**: Make updates to your form and click Save/Submit.</span></span>

![按一下 [儲存] 或 [提交]](../media/existing%20isv%202.png)

<span data-ttu-id="1b898-184">送出後，即會進行考核。</span><span class="sxs-lookup"><span data-stu-id="1b898-184">Once submitted, it will be under review.</span></span>

![審查中的證明](../media/existing%20isv%203.png)

## <a name="6---microsoft-365-re-certification-workflow"></a><span data-ttu-id="1b898-186">6. Microsoft 365 Re-Certification 工作流程：</span><span class="sxs-lookup"><span data-stu-id="1b898-186">6.   Microsoft 365 Re-Certification Workflow:</span></span>

<span data-ttu-id="1b898-187">當應用程式即將達到1年的憑證周年時，會定期提醒您更新認證。</span><span class="sxs-lookup"><span data-stu-id="1b898-187">When an app is about to reach its 1-year Certification Anniversary, there will be periodic reminders to renew certification.</span></span>

![UG Recreation1](../media/UG%20Recreation%201.png)

![UG Recreation2](../media/UG%20Recreation%202.png)

<span data-ttu-id="1b898-190">**已完成發行者證明。認證 InProgress。**</span><span class="sxs-lookup"><span data-stu-id="1b898-190">**Publisher Attestation Completed. Certification InProgress.**</span></span>

![UG Recreation3](../media/UG%20Recreation%203.PNG)

<span data-ttu-id="1b898-192">核准/拒絕 Secnario：已拒絕證書</span><span class="sxs-lookup"><span data-stu-id="1b898-192">Approval/Rejection Secnario: A. Certification Rejected</span></span>

![UG Recreation4](../media/UG%20Recreation%204.PNG)

<span data-ttu-id="1b898-194">B。</span><span class="sxs-lookup"><span data-stu-id="1b898-194">B.</span></span> <span data-ttu-id="1b898-195">已核准認證</span><span class="sxs-lookup"><span data-stu-id="1b898-195">Certification Approved</span></span>

![UG Recreation5](../media/UG%20Recreation%205.PNG)

<span data-ttu-id="1b898-197">到期案例：發行者證明已過期</span><span class="sxs-lookup"><span data-stu-id="1b898-197">Expiration Scenario: A. Publisher Attestation Expired</span></span>

![UG Recreation6](../media/UG%20Recreation%206.PNG)

<span data-ttu-id="1b898-199">B。</span><span class="sxs-lookup"><span data-stu-id="1b898-199">B.</span></span> <span data-ttu-id="1b898-200">憑證已過期</span><span class="sxs-lookup"><span data-stu-id="1b898-200">Certification Expired</span></span>

![UG Recreation7](../media/UG%20Recreation%207.PNG)

