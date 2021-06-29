---
title: 使用者指南
author: LGerrard
ms.author: legerrar
description: Microsoft 365 應用程式規範計畫的 ISV 使用者指南
keywords: Microsoft 365 應用程式規範計畫的 ISV 使用者指南
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 437fcbc56309ca14566dbb95f470097af82c26bf
ms.sourcegitcommit: bfabb191087786fae2b476e3f30861317886defa
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/29/2021
ms.locfileid: "53179044"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program"></a><span data-ttu-id="128c1-104">合作夥伴的 Microsoft 365 應用程式規範計畫的使用者指南</span><span class="sxs-lookup"><span data-stu-id="128c1-104">Partner's User Guide for Microsoft 365 App Compliance Program</span></span>

|<span data-ttu-id="128c1-105">階段</span><span class="sxs-lookup"><span data-stu-id="128c1-105">Phase</span></span>|<span data-ttu-id="128c1-106">職稱</span><span class="sxs-lookup"><span data-stu-id="128c1-106">Title</span></span>|
|---|---|
|<span data-ttu-id="128c1-107">階段1</span><span class="sxs-lookup"><span data-stu-id="128c1-107">Phase 1</span></span>| <span data-ttu-id="128c1-108">發行者證明</span><span class="sxs-lookup"><span data-stu-id="128c1-108">Publisher Attestation</span></span>|
|<span data-ttu-id="128c1-109">階段2</span><span class="sxs-lookup"><span data-stu-id="128c1-109">Phase 2</span></span>| <span data-ttu-id="128c1-110">Microsoft 365 憑證</span><span class="sxs-lookup"><span data-stu-id="128c1-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="128c1-111">1. 簡介</span><span class="sxs-lookup"><span data-stu-id="128c1-111">1. Overview</span></span>
<span data-ttu-id="128c1-112">這份檔是在 Microsoft 365 應用程式規範計畫中註冊的合作夥伴逐步使用者指南，其目標是透過夥伴中心入口網站進行 Publisher 證明和憑證。</span><span class="sxs-lookup"><span data-stu-id="128c1-112">This document acts as a step-by-step user guide for our partners enrolled in the Microsoft 365 App Compliance Program aiming to undergo Publisher Attestation and Certification though Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="128c1-113">2. 縮寫 & 定義</span><span class="sxs-lookup"><span data-stu-id="128c1-113">2. Acronyms & Definitions</span></span>
| <span data-ttu-id="128c1-114">縮略字</span><span class="sxs-lookup"><span data-stu-id="128c1-114">Acronym</span></span> |<span data-ttu-id="128c1-115">定義</span><span class="sxs-lookup"><span data-stu-id="128c1-115">Definition</span></span> |
|---|----|
|<span data-ttu-id="128c1-116">電腦 [ (合作夥伴中心) ](https://partner.microsoft.com/)</span><span class="sxs-lookup"><span data-stu-id="128c1-116">PC [(Partner Center)](https://partner.microsoft.com/)</span></span>|<span data-ttu-id="128c1-117">所有 Microsoft 合作夥伴的入口網站。</span><span class="sxs-lookup"><span data-stu-id="128c1-117">A portal for all Microsoft Partners.</span></span> <span data-ttu-id="128c1-118">合作夥伴會登入至夥伴中心，並提交 Self-Assessment 問卷。</span><span class="sxs-lookup"><span data-stu-id="128c1-118">A Partner logs in to Partner Center and submits Self-Assessment Questionnaire.</span></span> <span data-ttu-id="128c1-119">Microsoft 365 應用程式相容性的[合作夥伴中心](https://partner.microsoft.com/dashboard/home)</span><span class="sxs-lookup"><span data-stu-id="128c1-119">[Partner Center](https://partner.microsoft.com/dashboard/home) for Microsoft 365 App Compliance</span></span>|
|<span data-ttu-id="128c1-120">ISV</span><span class="sxs-lookup"><span data-stu-id="128c1-120">ISV</span></span>|<span data-ttu-id="128c1-121">獨立軟體廠商。</span><span class="sxs-lookup"><span data-stu-id="128c1-121">Independent Software Vendor.</span></span> <span data-ttu-id="128c1-122">A.k.a.</span><span class="sxs-lookup"><span data-stu-id="128c1-122">A.k.a.</span></span> <span data-ttu-id="128c1-123">Partner or Developer</span><span class="sxs-lookup"><span data-stu-id="128c1-123">Partner or Developer</span></span>|
|<span data-ttu-id="128c1-124">應用程式來源</span><span class="sxs-lookup"><span data-stu-id="128c1-124">App Source</span></span>| [<span data-ttu-id="128c1-125">應用程式目錄</span><span class="sxs-lookup"><span data-stu-id="128c1-125">Catalog of apps</span></span>](https://appsource.microsoft.com/)
||<span data-ttu-id="128c1-126">範例： [Now virtual agent](https://appsource.microsoft.com/product/office/WA104381816)</span><span class="sxs-lookup"><span data-stu-id="128c1-126">Example: [Now virtual agent](https://appsource.microsoft.com/product/office/WA104381816)</span></span>|

## <a name="3---publisher-attestation-workflow"></a><span data-ttu-id="128c1-127">3. Publisher 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="128c1-127">3.   Publisher Attestation Workflow</span></span>

<span data-ttu-id="128c1-128">首頁：這是一次夥伴登入夥伴中心的登陸頁面。</span><span class="sxs-lookup"><span data-stu-id="128c1-128">Home Page: This is the landing page once a partner logs in to Partner Center.</span></span>

![合作夥伴中心主畫面](../media/UserGuidePhotos/01.png)

<span data-ttu-id="128c1-130">**步驟 1**   ：在頁面左側的導覽列中：</span><span class="sxs-lookup"><span data-stu-id="128c1-130">**Step 1**   : On the left side of the page, in the navigation bar:</span></span>
1. <span data-ttu-id="128c1-131">選取 Office 儲存區</span><span class="sxs-lookup"><span data-stu-id="128c1-131">Select Office store</span></span>
1. <span data-ttu-id="128c1-132">選取一覽</span><span class="sxs-lookup"><span data-stu-id="128c1-132">Select Overview</span></span>

![Office可以在左側導覽找到存放區](../media/UserGuidePhotos/02.png)

<span data-ttu-id="128c1-134">選取「一覽」時，partner 可以查看透過夥伴中心提交且可用於 Microsoft 365 規範計畫的應用程式清單。</span><span class="sxs-lookup"><span data-stu-id="128c1-134">Upon selecting ‘Overview’, partner can see list of apps submitted through Partner Center and available for the Microsoft 365 Compliance program.</span></span>

<span data-ttu-id="128c1-135">**步驟 2** ：從清單中選取應用程式，以開始 Publisher 認證程式。</span><span class="sxs-lookup"><span data-stu-id="128c1-135">**Step 2** : Select an app from the list to begin the Publisher Attestation process.</span></span>

![選擇您要證明哪個應用程式](../media/UserGuidePhotos/03.png)

<span data-ttu-id="128c1-137">在選取應用程式時，會彈出另一個導覽列，其中包含選項「應用程式相容性」。</span><span class="sxs-lookup"><span data-stu-id="128c1-137">On selecting an app, another navigation bar will pop up with option ‘App Compliance.’</span></span>

<span data-ttu-id="128c1-138">**步驟 3**：選取「應用程式符合性」</span><span class="sxs-lookup"><span data-stu-id="128c1-138">**Step 3**: Select ‘App Compliance’</span></span>

![選取應用程式規範](../media/UserGuidePhotos/04.png)

<span data-ttu-id="128c1-140">**步驟 4**：填寫 Publisher 證明的 Self-Assessment 問卷</span><span class="sxs-lookup"><span data-stu-id="128c1-140">**Step 4**: Fill out the Self-Assessment Questionnaire for Publisher Attestation</span></span>

![發行者證明](../media/UserGuidePhotos/5.5.PNG)

<span data-ttu-id="128c1-142">**附注：** 如果您要回到更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [仿製]。</span><span class="sxs-lookup"><span data-stu-id="128c1-142">**Note:** If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone.’</span></span>

![Clone](../media/UserGuidePhotos/05.PNG)

<span data-ttu-id="128c1-144">您也可以利用匯入/匯出功能，離線完成表單，並在完成後將其匯入。</span><span class="sxs-lookup"><span data-stu-id="128c1-144">You can also leverage the Import/Export feature to complete the form offline and import it once completed.</span></span>

![匯入匯出功能](../media/UserGuidePhotos/06.PNG)

<span data-ttu-id="128c1-146">您也可以利用匯入/匯出功能，離線完成表單，並在完成後將其匯入。</span><span class="sxs-lookup"><span data-stu-id="128c1-146">You can also leverage the Import/Export feature to complete the form offline and import it once completed.</span></span> 

<span data-ttu-id="128c1-147">**步驟 5**：完成後，按一下 [提交]，評估現在會是「審閱」。</span><span class="sxs-lookup"><span data-stu-id="128c1-147">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘under review’.</span></span>

![按一下 Sumbit](../media/UserGuidePhotos/07.png)

![審閱現在正在進行中](../media/UserGuidePhotos/08.png)

### <a name="approvereject-scenarios"></a><span data-ttu-id="128c1-150">核准/拒絕案例：</span><span class="sxs-lookup"><span data-stu-id="128c1-150">Approve/Reject Scenarios:</span></span>

<span data-ttu-id="128c1-151">**Publisher 證明拒絕**</span><span class="sxs-lookup"><span data-stu-id="128c1-151">**A.Publisher Attestation Rejection**</span></span>

<span data-ttu-id="128c1-152">在此階段遭到拒絕時，合作夥伴可以：</span><span class="sxs-lookup"><span data-stu-id="128c1-152">In case of rejection at this stage, an partner can:</span></span>
-   <span data-ttu-id="128c1-153">View 失敗報告。</span><span class="sxs-lookup"><span data-stu-id="128c1-153">View failure report.</span></span>
    - <span data-ttu-id="128c1-154">合作夥伴會透過電子郵件通知，而且可以在夥伴中心中查看失敗報告</span><span class="sxs-lookup"><span data-stu-id="128c1-154">Partner will be notified via email, and they can view the failure report in Partner Center</span></span>
-   <span data-ttu-id="128c1-155">更新並重新提交 Publisher 證明 ![ 更新並重新提交評估](../media/UserGuidePhotos/09.png)</span><span class="sxs-lookup"><span data-stu-id="128c1-155">Update and re-submit Publisher Attestation ![Update and resubmit assessment](../media/UserGuidePhotos/09.png)</span></span>

<span data-ttu-id="128c1-156">**b. Publisher 認證重新提交**</span><span class="sxs-lookup"><span data-stu-id="128c1-156">**B.Publisher Attestation Re-submission**</span></span>

![在審閱下重新提交](../media/PA%20resubmission.png)

<span data-ttu-id="128c1-158">**c. Publisher 證明核准**</span><span class="sxs-lookup"><span data-stu-id="128c1-158">**C.Publisher Attestation Approval**</span></span>

-   <span data-ttu-id="128c1-159">在核准合作夥伴可以執行下列作業：</span><span class="sxs-lookup"><span data-stu-id="128c1-159">Upon approval partner can:</span></span>
    - <span data-ttu-id="128c1-160">更新並重新提交證明</span><span class="sxs-lookup"><span data-stu-id="128c1-160">Update and resubmit attestation</span></span>
    - <span data-ttu-id="128c1-161">查看和共用已完成的 Publisher 證明</span><span class="sxs-lookup"><span data-stu-id="128c1-161">View and share completed Publisher Attestation</span></span>
    - <span data-ttu-id="128c1-162">開始 M365 認證處理常式</span><span class="sxs-lookup"><span data-stu-id="128c1-162">Start M365 Certification Process</span></span>

![更新並重新提交](../media/AttestApproval.PNG)

![<span data-ttu-id="128c1-164">查看已完成的證明</span><span class="sxs-lookup"><span data-stu-id="128c1-164">View completed attestation</span></span> ](../media/PA%20approval%202.png)

![開始 M365 應用程式認證](../media/PA%20approval%203.png)

<span data-ttu-id="128c1-166">**Post Publisher 驗證核准： Publisher attested 應用程式 AppSource 中的連結範例**</span><span class="sxs-lookup"><span data-stu-id="128c1-166">**Post Publisher Verification Approval: Example of link in AppSource for publisher attested apps**</span></span>

![完成證明的範例](../media/Example%20to%20attested%20apps.png)

## <a name="4-microsoft-365-certification-workflow"></a><span data-ttu-id="128c1-168">4. Microsoft 365 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="128c1-168">4. Microsoft 365 Certification Workflow</span></span>

<span data-ttu-id="128c1-169">協力廠商按一下「提交」並提交所有檔和證據進行審閱之後：</span><span class="sxs-lookup"><span data-stu-id="128c1-169">Once partner clicks on ‘Submit’ and submits all documents and evidence for review:</span></span> 

### <a name="microsoft-365-certification---submitted"></a><span data-ttu-id="128c1-170">Microsoft 365認證-已提交</span><span class="sxs-lookup"><span data-stu-id="128c1-170">Microsoft 365 Certification - Submitted</span></span>

![已開始認證](../media/certification%201.png)

<span data-ttu-id="128c1-172">**Microsoft 365 認證-已拒絕**</span><span class="sxs-lookup"><span data-stu-id="128c1-172">**Microsoft 365 certification - Rejected**</span></span>

![拒絕的憑證](../media/certification%20rejected.png)

<span data-ttu-id="128c1-174">**Microsoft 365認證-已核准**</span><span class="sxs-lookup"><span data-stu-id="128c1-174">**Microsoft 365 Certification - Approved**</span></span>

![已核准認證](../media/certification%20approved.png)

<span data-ttu-id="128c1-176">**後憑證核准： AppSource 中 Microsoft 365 憑證徽章的範例**</span><span class="sxs-lookup"><span data-stu-id="128c1-176">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource**</span></span>

![認證標記範例](../media/post%20certification%20badge.png)

## <a name="5-workflow-for-existing-isvs"></a><span data-ttu-id="128c1-178">5. 現有 Isv 的工作流程</span><span class="sxs-lookup"><span data-stu-id="128c1-178">5. Workflow for Existing ISVs</span></span>

<span data-ttu-id="128c1-179">如果您是現有的 ISV，且想要更新 Publisher 證明。</span><span class="sxs-lookup"><span data-stu-id="128c1-179">If you are an existing ISV and want to Update Publisher Attestation.</span></span>

<span data-ttu-id="128c1-180">**步驟 1**：按一下「更新並重新提交您的 Publisher 認證」連結。</span><span class="sxs-lookup"><span data-stu-id="128c1-180">**Step 1**: Click on ‘Update and re-submit your Publisher Attestation’ link.</span></span>

![<span data-ttu-id="128c1-181">更新 Publisher 證明</span><span class="sxs-lookup"><span data-stu-id="128c1-181">Update Publisher Attestation</span></span> ](../media/existing%20isv%201.png)

<span data-ttu-id="128c1-182">**附注：**：如果您要回到更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [匯入]。</span><span class="sxs-lookup"><span data-stu-id="128c1-182">**Note:**: If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Import’.</span></span>

![針對不同整合的匯入證明](../media/M365%20App%20compliance.png)

![按一下 [匯入](../media/M365%20App%20compliance1.png)

<span data-ttu-id="128c1-185">**步驟 2**：對表單進行更新，然後按一下 [儲存/提交]。</span><span class="sxs-lookup"><span data-stu-id="128c1-185">**Step 2**: Make updates to your form and click Save/Submit.</span></span>

![按一下 [儲存] 或 [提交]](../media/existing%20isv%202.png)

<span data-ttu-id="128c1-187">送出後，即會進行考核。</span><span class="sxs-lookup"><span data-stu-id="128c1-187">Once submitted, it will be under review.</span></span>

![審查中的證明](../media/existing%20isv%203.png)

## <a name="6---microsoft-365-publisher-attestation-and-certification-renewal-workflow"></a><span data-ttu-id="128c1-189">6. Microsoft 365 Publisher 證明和認證更新工作流程：</span><span class="sxs-lookup"><span data-stu-id="128c1-189">6.   Microsoft 365 Publisher Attestation and Certification Renewal Workflow:</span></span>

<span data-ttu-id="128c1-190">Microsoft 365App 相容性計畫現在提供一年的更新程式。</span><span class="sxs-lookup"><span data-stu-id="128c1-190">Microsoft 365 App Compliance Program now offers an annual renewal process.</span></span> <span data-ttu-id="128c1-191">在此程式中，應用程式開發人員可以更新 Microsoft 365 憑證所需的現有 Publisher 認證問卷及檔。</span><span class="sxs-lookup"><span data-stu-id="128c1-191">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 

<span data-ttu-id="128c1-192">**好處：**</span><span class="sxs-lookup"><span data-stu-id="128c1-192">**Benefits:**</span></span>

- <span data-ttu-id="128c1-193">在 AppSource 和小組存放區中維護您的憑證徽章，以將您的應用程式與其他使用者區別開來。</span><span class="sxs-lookup"><span data-stu-id="128c1-193">Maintain your certification badge in AppSource and Team Store to differentiate your app from others.</span></span> 
- <span data-ttu-id="128c1-194">使用認證的應用程式，提高客戶的信賴程度。</span><span class="sxs-lookup"><span data-stu-id="128c1-194">Increase customer confidence in using your certified app.</span></span> 
- <span data-ttu-id="128c1-195">協助 IT 管理員以更新的認證資訊作出合理的決策。</span><span class="sxs-lookup"><span data-stu-id="128c1-195">Help IT admins make informed decisions with updated certification information.</span></span> 

<span data-ttu-id="128c1-196">您可以在 [合作夥伴中心](https://partner.microsoft.com/en-us/dashboard/home) 取得新的更新程式，以提供無縫體驗。</span><span class="sxs-lookup"><span data-stu-id="128c1-196">The new renewal process is available in [Partner Center](https://partner.microsoft.com/en-us/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="128c1-197">在夥伴中心的到期日的開始90天之後，將會顯示更新提醒。</span><span class="sxs-lookup"><span data-stu-id="128c1-197">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="128c1-198">定期提醒也會透過電子郵件于到期的90、60和30天傳送。</span><span class="sxs-lookup"><span data-stu-id="128c1-198">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span>

<span data-ttu-id="128c1-199">**第1層： Publisher 認證更新：**</span><span class="sxs-lookup"><span data-stu-id="128c1-199">**Tier 1: Publisher Attestation Renewal:**</span></span> 

<span data-ttu-id="128c1-200">應用程式的 Publisher 認證答案將需要一年重新提交。</span><span class="sxs-lookup"><span data-stu-id="128c1-200">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="128c1-201">當證明臨近1年標記時，系統會傳送電子郵件提醒，以鼓勵重新提交證明。</span><span class="sxs-lookup"><span data-stu-id="128c1-201">When the attestation nears 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 

<span data-ttu-id="128c1-202">**步驟 1**：選取 [**續訂**] 以更新 Publisher 認證。</span><span class="sxs-lookup"><span data-stu-id="128c1-202">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span> 

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/AppComplianceExpirationNotice.png)

<span data-ttu-id="128c1-204">**步驟 2**：查看先前的 Publisher 認證答案，並視需要更新最新資訊。</span><span class="sxs-lookup"><span data-stu-id="128c1-204">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> <span data-ttu-id="128c1-205">提交 Publisher 認證以于準備時進行更新。</span><span class="sxs-lookup"><span data-stu-id="128c1-205">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="128c1-206">M365 應用程式規範分析員會檢查它。</span><span class="sxs-lookup"><span data-stu-id="128c1-206">It will be reviewed by an M365 App Compliance Analyst.</span></span>

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/2.PNG)

<span data-ttu-id="128c1-208">**Publisher 證明已過期：** 應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 Publisher 認證頁面。及時更新也會確保 AppSource 和小組存放區中的應用程式持續聲譽徽章授予及圖示。</span><span class="sxs-lookup"><span data-stu-id="128c1-208">**Publisher Attestation Expired:** The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/3.PNG)

<span data-ttu-id="128c1-210">附注：已到期，只要按一下「更新」，即可隨時啟動 Publisher 證明更新程式。</span><span class="sxs-lookup"><span data-stu-id="128c1-210">Note: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span> 

<span data-ttu-id="128c1-211">**第2層： Microsoft 365 認證更新**</span><span class="sxs-lookup"><span data-stu-id="128c1-211">**Tier 2: Microsoft 365 Certification Renewal**</span></span> 

<span data-ttu-id="128c1-212">應用程式的認證資訊需要一年的頻率重新提交。</span><span class="sxs-lookup"><span data-stu-id="128c1-212">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="128c1-213">這將需要重新驗證您目前環境中的範圍內控制項。</span><span class="sxs-lookup"><span data-stu-id="128c1-213">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="128c1-214">當憑證臨近1年標記時，系統會傳送電子郵件通知，以鼓勵重新提交檔和證據。</span><span class="sxs-lookup"><span data-stu-id="128c1-214">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span> 

<span data-ttu-id="128c1-215">**認證更新核准/拒絕案例：**</span><span class="sxs-lookup"><span data-stu-id="128c1-215">**Certification Renewal Approve/Reject Scenarios:**</span></span>

<span data-ttu-id="128c1-216">**案例1：**</span><span class="sxs-lookup"><span data-stu-id="128c1-216">**Scenario 1:**</span></span> 

<span data-ttu-id="128c1-217">Publisher證明已完成。</span><span class="sxs-lookup"><span data-stu-id="128c1-217">Publisher Attestation  is complete.</span></span> <span data-ttu-id="128c1-218">憑證更新已開始，且正在進行審閱。</span><span class="sxs-lookup"><span data-stu-id="128c1-218">Certification renewal has started and under review.</span></span> 

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/4.PNG)

<span data-ttu-id="128c1-220">**案例1A：**</span><span class="sxs-lookup"><span data-stu-id="128c1-220">**Scenario 1A:**</span></span>

<span data-ttu-id="128c1-221">憑證更新拒絕：在下列情況中，可能會拒絕認證：</span><span class="sxs-lookup"><span data-stu-id="128c1-221">Certification renewal rejection: Certification may be rejected if:</span></span> 

 - <span data-ttu-id="128c1-222">應用程式不具備必要的工具、程式或設定，也無法在認證視窗中執行所需的變更。</span><span class="sxs-lookup"><span data-stu-id="128c1-222">The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> 
 - <span data-ttu-id="128c1-223">應用程式有未完成的漏洞，無法在認證視窗內修正。</span><span class="sxs-lookup"><span data-stu-id="128c1-223">The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/5.PNG)
    
<span data-ttu-id="128c1-225">**案例1B：**</span><span class="sxs-lookup"><span data-stu-id="128c1-225">**Scenario 1B:**</span></span> 

<span data-ttu-id="128c1-226">認證更新已獲批准</span><span class="sxs-lookup"><span data-stu-id="128c1-226">Certification renewal is approved</span></span>  

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/6.PNG)

<span data-ttu-id="128c1-228">**認證到期：**</span><span class="sxs-lookup"><span data-stu-id="128c1-228">**Certification Expiration:**</span></span>

<span data-ttu-id="128c1-229">應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 [證書] 頁面。及時更新也會確保 AppSource 和小組存放區中的應用程式持續聲譽徽章授予及圖示。</span><span class="sxs-lookup"><span data-stu-id="128c1-229">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span> 

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/7.PNG)
    
<span data-ttu-id="128c1-231">**附注**：只要按一下「更新」，即可隨時啟動 Publisher 證明和認證程式。</span><span class="sxs-lookup"><span data-stu-id="128c1-231">**Note**: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 












