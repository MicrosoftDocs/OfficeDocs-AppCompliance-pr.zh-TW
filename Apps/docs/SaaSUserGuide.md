---
title: SaaS 應用程式的使用者指南
author: LGerrard
ms.author: legerrar
description: Microsoft 365 應用程式規範方案的 ISV 使用者指南 SaaS
keywords: Microsoft 365 應用程式規範方案的 ISV 使用者指南 SaaS
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: b3b8c37a1babf2f941f5764fddd30523319d9a34
ms.sourcegitcommit: f6f3551bf1c00013efb6313ca3dc280de697137d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/29/2021
ms.locfileid: "53202754"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program---saas"></a><span data-ttu-id="973f8-104">Microsoft 365 應用程式規範計畫的協力廠商使用者指南-SaaS</span><span class="sxs-lookup"><span data-stu-id="973f8-104">Partner's User Guide for Microsoft 365 App Compliance Program - SaaS</span></span>

|<span data-ttu-id="973f8-105">階段</span><span class="sxs-lookup"><span data-stu-id="973f8-105">Phase</span></span>|<span data-ttu-id="973f8-106">職稱</span><span class="sxs-lookup"><span data-stu-id="973f8-106">Title</span></span>|
|---|---|
|<span data-ttu-id="973f8-107">階段1</span><span class="sxs-lookup"><span data-stu-id="973f8-107">Phase 1</span></span>| <span data-ttu-id="973f8-108">發行者證明</span><span class="sxs-lookup"><span data-stu-id="973f8-108">Publisher Attestation</span></span>|
|<span data-ttu-id="973f8-109">階段2</span><span class="sxs-lookup"><span data-stu-id="973f8-109">Phase 2</span></span>| <span data-ttu-id="973f8-110">Microsoft 365 憑證</span><span class="sxs-lookup"><span data-stu-id="973f8-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="973f8-111">1. 簡介</span><span class="sxs-lookup"><span data-stu-id="973f8-111">1. Overview</span></span> 

<span data-ttu-id="973f8-112">這份檔是為我們的合作夥伴做逐步的使用者指南，註冊 Microsoft 365 App 合規性計畫，其適用于其 SaaS 應用程式的 Publisher 證明和認證，但夥伴中心入口網站。</span><span class="sxs-lookup"><span data-stu-id="973f8-112">This document acts as a step-by-step user guide for our partners, enrolled for Microsoft 365 App Compliance program aiming to undergo Publisher Attestation and Certification for their SaaS apps, though the Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="973f8-113">2. 縮寫 & 定義</span><span class="sxs-lookup"><span data-stu-id="973f8-113">2. Acronyms & Definitions</span></span>
|<span data-ttu-id="973f8-114">縮略字</span><span class="sxs-lookup"><span data-stu-id="973f8-114">Acronym</span></span> | <span data-ttu-id="973f8-115">定義</span><span class="sxs-lookup"><span data-stu-id="973f8-115">Definition</span></span> |
|----|----|
|[<span data-ttu-id="973f8-116">電腦 (合作夥伴中心) </span><span class="sxs-lookup"><span data-stu-id="973f8-116">PC (Partner Center)</span></span>](https://partner.microsoft.com/)|<span data-ttu-id="973f8-117">所有 Microsoft 合作夥伴的入口網站。</span><span class="sxs-lookup"><span data-stu-id="973f8-117">A portal for all Microsoft partners.</span></span> <span data-ttu-id="973f8-118">協力廠商會登入至夥伴中心，並提交自我評估問卷。</span><span class="sxs-lookup"><span data-stu-id="973f8-118">A partner logs in to Partner Center and submits self-assessment questionnaire.</span></span> <span data-ttu-id="973f8-119">[Microsoft 365 應用程式相容性](https://partner.microsoft.com/dashboard/home)的合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="973f8-119">Partner Center for [Microsoft 365 App Compliance](https://partner.microsoft.com/dashboard/home)</span></span>|
|<span data-ttu-id="973f8-120">ISV</span><span class="sxs-lookup"><span data-stu-id="973f8-120">ISV</span></span> | <span data-ttu-id="973f8-121">獨立軟體廠商 a.k.a。</span><span class="sxs-lookup"><span data-stu-id="973f8-121">Independent Software Vendor a.k.a.</span></span> <span data-ttu-id="973f8-122">Partner or Developer</span><span class="sxs-lookup"><span data-stu-id="973f8-122">Partner or Developer</span></span> |
|<span data-ttu-id="973f8-123">應用程式來源</span><span class="sxs-lookup"><span data-stu-id="973f8-123">App Source</span></span> | <span data-ttu-id="973f8-124">應用程式目錄</span><span class="sxs-lookup"><span data-stu-id="973f8-124">Catalog of apps</span></span> |
|<span data-ttu-id="973f8-125">範例</span><span class="sxs-lookup"><span data-stu-id="973f8-125">Example</span></span> |[<span data-ttu-id="973f8-126">現在，虛擬代理程式</span><span class="sxs-lookup"><span data-stu-id="973f8-126">Now virtual agent</span></span>](https://appsource.microsoft.com/product/office/WA104381816)|

## <a name="3-publisher-attestation-workflow"></a><span data-ttu-id="973f8-127">3. Publisher 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="973f8-127">3. Publisher Attestation Workflow</span></span>

<span data-ttu-id="973f8-128">**首頁**：這是一次夥伴登入夥伴中心的登陸頁面。</span><span class="sxs-lookup"><span data-stu-id="973f8-128">**Home Page**: This is the landing page once a partner logs in to Partner Center.</span></span>

![合作夥伴中心主畫面](../media/Saas1.PNG)
  
<span data-ttu-id="973f8-130">**步驟 1** ：在頁面左側的導覽列上：</span><span class="sxs-lookup"><span data-stu-id="973f8-130">**Step 1** : On the left side of the page, on the navigation bar:</span></span>

- <span data-ttu-id="973f8-131">選取商業市場</span><span class="sxs-lookup"><span data-stu-id="973f8-131">Select Commercial Marketplace</span></span>
- <span data-ttu-id="973f8-132">選取一覽</span><span class="sxs-lookup"><span data-stu-id="973f8-132">Select Overview</span></span>

![合作夥伴中心的商業市場](../media/Saas2.PNG)
  
<span data-ttu-id="973f8-134">選取「一覽」時，partner 可以查看可用的應用程式清單，以啟動 Microsoft 365 合規性計畫。</span><span class="sxs-lookup"><span data-stu-id="973f8-134">Upon selecting ‘Overview’, partner can see list of apps available to start the Microsoft 365 Compliance program.</span></span>
  
<span data-ttu-id="973f8-135">**步驟 2**：從清單中選取應用程式，以開始 Publisher 認證程式。</span><span class="sxs-lookup"><span data-stu-id="973f8-135">**Step 2**: Select an app from the list to begin the Publisher Attestation process.</span></span>

![在商業市場上選取應用程式](../media/Saas3.PNG)

<span data-ttu-id="973f8-137">在選取應用程式時，會以選項「應用程式相容性」彈出另一個導覽列。</span><span class="sxs-lookup"><span data-stu-id="973f8-137">On selecting an app, another navigation bar will pop up with option ‘App Compliance’.</span></span>
  
<span data-ttu-id="973f8-138">**步驟 3**：選取「應用程式符合性」</span><span class="sxs-lookup"><span data-stu-id="973f8-138">**Step 3**: Select 'App Compliance’</span></span>
  
![商業市場中的應用程式合規性](../media/Saas4.PNG)
  
<span data-ttu-id="973f8-140">**步驟 4**：填寫 Publisher 認證的自我評估問卷。</span><span class="sxs-lookup"><span data-stu-id="973f8-140">**Step 4**: Fill out the self-assessment questionnaire for Publisher Attestation.</span></span>

![完成 Publisher 證明](../media/UserGuidePhotos/5.5.png)
  
<span data-ttu-id="973f8-142">**附注如果您會傳回更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [複製]。**</span><span class="sxs-lookup"><span data-stu-id="973f8-142">**NOTE If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone’.**</span></span>

![複製功能](../media/UserGuidePhotos/05.png)

<span data-ttu-id="973f8-144">**您也可以利用匯入/匯出功能，離線完成表單，並在完成後將其匯入。**</span><span class="sxs-lookup"><span data-stu-id="973f8-144">**You can also leverage the Import/Export feature to complete the form offline and import it once completed.**</span></span>

![匯入匯出功能](../media/UserGuidePhotos/06.png)
 
<span data-ttu-id="973f8-146">**步驟 5**：完成後，按一下 [提交]，評估現在會是「審閱」。</span><span class="sxs-lookup"><span data-stu-id="973f8-146">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘Under Review’.</span></span>
 
 <span data-ttu-id="973f8-147">![提交 Publisher Attesation ](../media/UserGuidePhotos/07.png) ![ 提交確認](../media/UserGuidePhotos/08.png)</span><span class="sxs-lookup"><span data-stu-id="973f8-147">![Submit Publisher Attesation](../media/UserGuidePhotos/07.png) ![Confirmation of submission](../media/UserGuidePhotos/08.png)</span></span>
  
<span data-ttu-id="973f8-148">**核准/拒絕案例：**</span><span class="sxs-lookup"><span data-stu-id="973f8-148">**Approve/Reject Scenarios:**</span></span>
  
<span data-ttu-id="973f8-149">答：</span><span class="sxs-lookup"><span data-stu-id="973f8-149">A.</span></span> <span data-ttu-id="973f8-150">Publisher證明拒絕</span><span class="sxs-lookup"><span data-stu-id="973f8-150">Publisher Attestation Rejection</span></span>
- <span data-ttu-id="973f8-151">在拒絕時，合作夥伴可以：</span><span class="sxs-lookup"><span data-stu-id="973f8-151">In case of rejection, a partner can:</span></span>
     - <span data-ttu-id="973f8-152">查看失敗報告</span><span class="sxs-lookup"><span data-stu-id="973f8-152">View failure report</span></span>
          - <span data-ttu-id="973f8-153">合作夥伴會透過電子郵件通知，而且可以在夥伴中心中查看失敗報告</span><span class="sxs-lookup"><span data-stu-id="973f8-153">Partner will be notified via email, and they can view the failure report in Partner Center</span></span>
     - <span data-ttu-id="973f8-154">更新並重新提交自我評估問卷。</span><span class="sxs-lookup"><span data-stu-id="973f8-154">Update and re-submit self-assessment questionnaire.</span></span>
        
![Publisher已拒絕證明](../media/UserGuidePhotos/09.png)

<span data-ttu-id="973f8-156">B。</span><span class="sxs-lookup"><span data-stu-id="973f8-156">B.</span></span>  <span data-ttu-id="973f8-157">Publisher證明核准</span><span class="sxs-lookup"><span data-stu-id="973f8-157">Publisher Attestation Approval</span></span>
- <span data-ttu-id="973f8-158">核准後，合作夥伴可以：</span><span class="sxs-lookup"><span data-stu-id="973f8-158">Upon approval, the partner can:</span></span>
     - <span data-ttu-id="973f8-159">更新並重新提交證明</span><span class="sxs-lookup"><span data-stu-id="973f8-159">Update and resubmit attestation</span></span>
     - <span data-ttu-id="973f8-160">View 已完成 Publisher 證明</span><span class="sxs-lookup"><span data-stu-id="973f8-160">View completed Publisher Attestation</span></span>
     - <span data-ttu-id="973f8-161">啟動 Microsoft 365 認證程式</span><span class="sxs-lookup"><span data-stu-id="973f8-161">Start the Microsoft 365 Certification process</span></span>
        
 ![Publisher證明已完成](../media/UserGuidePhotos/10.png)       
  
 ![啟動 Microsoft 365 憑證](../media/UserGuidePhotos/11.png)
  
<span data-ttu-id="973f8-164">**Post Publisher 認證核准： Publisher attested 應用程式 AppSource 中的連結範例。**</span><span class="sxs-lookup"><span data-stu-id="973f8-164">**Post Publisher Attestation Approval: Example of link in AppSource for publisher attested apps.**</span></span>
  
![核准的連絡人範例](../media/UserGuidePhotos/12.png)
   
## <a name="4---microsoft-365-certification-workflow"></a><span data-ttu-id="973f8-166">4. Microsoft 365 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="973f8-166">4.   Microsoft 365 Certification Workflow</span></span>
  
<span data-ttu-id="973f8-167">協力廠商可以從選取核取方塊，然後按一下 [提交]，以開始認證程式。</span><span class="sxs-lookup"><span data-stu-id="973f8-167">A partner can begin the Certification process by selecting the checkbox and clicking ‘Submit’</span></span>
  
![開始 Microsoft 365 認證](../media/UserGuidePhotos/13.png) 
  
<span data-ttu-id="973f8-169">**步驟 1** ：初始檔提交</span><span class="sxs-lookup"><span data-stu-id="973f8-169">**Step 1** : Initial Document Submission</span></span>

<span data-ttu-id="973f8-170">填寫所有詳細資料，上傳相關的檔，然後按一下 [提交]</span><span class="sxs-lookup"><span data-stu-id="973f8-170">Fill out all the details, upload relevant documents and click ‘Submit’</span></span>
  
<span data-ttu-id="973f8-171">![初始檔提交 ](../media/UserGuidePhotos/14.png) 
 ![ 提交初始檔提交](../media/UserGuidePhotos/15.png)</span><span class="sxs-lookup"><span data-stu-id="973f8-171">![Initial Document Submission](../media/UserGuidePhotos/14.png) 
![Submit Initial Document Submission](../media/UserGuidePhotos/15.png)</span></span>
  
<span data-ttu-id="973f8-172">在按一下 [提交] 時，將會進行「審閱」的初始檔提交。</span><span class="sxs-lookup"><span data-stu-id="973f8-172">On clicking submit, the initial document submission will be under review.</span></span>

![在考核下初始檔提交](../media/UserGuidePhotos/16.png)
  
<span data-ttu-id="973f8-174">當初始檔不足或沒有相關時，分析員會要求修訂。</span><span class="sxs-lookup"><span data-stu-id="973f8-174">An analyst requests a revision in case the initial documents are not sufficient or relevant.</span></span> <span data-ttu-id="973f8-175">分析員會與合作夥伴合作，協助您取得適當的檔以供核准。</span><span class="sxs-lookup"><span data-stu-id="973f8-175">The analyst will work with the partner to help get the right documents for approval.</span></span>

![需要更新](../media/UserGuidePhotos/17.png)

<span data-ttu-id="973f8-177">當分析員核准初始檔提交後，協力廠商必須提交控制需求。</span><span class="sxs-lookup"><span data-stu-id="973f8-177">Once the analyst approves the initial document submission, the partner needs to submit the control requirements.</span></span>
  
<span data-ttu-id="973f8-178">**步驟 2**：控制需求提交</span><span class="sxs-lookup"><span data-stu-id="973f8-178">**Step 2**: Control Requirement Submission</span></span>
  
<span data-ttu-id="973f8-179">填寫所有詳細資料，上傳相關的檔，然後按一下 [提交]</span><span class="sxs-lookup"><span data-stu-id="973f8-179">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>

![完全控制需求](../media/UserGuidePhotos/18.png)
  
![Upload控制需求](../media/UserGuidePhotos/19.png)

![符合控制需求](../media/UserGuidePhotos/20.png)
 
<span data-ttu-id="973f8-183">在按一下 [提交] 時，將會進行「審閱」的初始檔提交。</span><span class="sxs-lookup"><span data-stu-id="973f8-183">On clicking Submit, the initial document submission will be under review.</span></span>

![提交時審閱](../media/UserGuidePhotos/21.png)
  
<span data-ttu-id="973f8-185">當控制項需求檔不足或沒有相關時，分析員會要求修訂。</span><span class="sxs-lookup"><span data-stu-id="973f8-185">An analyst requests a revision in case the control requirement documents are not sufficient or relevant.</span></span> <span data-ttu-id="973f8-186">分析員會與合作夥伴合作，協助您取得適當的檔以供核准。</span><span class="sxs-lookup"><span data-stu-id="973f8-186">The analyst will work with the partner to help get the right documents for approval.</span></span>

![需要更新證據](../media/UserGuidePhotos/22.png)

![哪些控制項需要更新](../media/UserGuidePhotos/23.png)
  
![進行中審閱](../media/UserGuidePhotos/24.png) 
 
<span data-ttu-id="973f8-190">若提交不符合核准標準，則分析員會拒絕提交。</span><span class="sxs-lookup"><span data-stu-id="973f8-190">In case the submission does not satisfy the approval standards, the analyst will reject the submission.</span></span>
  
<span data-ttu-id="973f8-191">合作夥伴可以與分析員搭配使用，以提供相關資訊和檔。</span><span class="sxs-lookup"><span data-stu-id="973f8-191">The partner can work with the analyst to provide the relevant information and documents.</span></span>

![已拒絕證書](../media/UserGuidePhotos/25.png)
  
<span data-ttu-id="973f8-193">所有的安全性標準都符合後，分析員便會核准提交，而且會 Microsoft 365 認證合作夥伴。</span><span class="sxs-lookup"><span data-stu-id="973f8-193">Once all the security standards have been met, the analyst will approve the submission and the partner will be Microsoft 365 Certified.</span></span>

![Microsoft 365已核准應用程式認證](../media/UserGuidePhotos/26.png)
  
<span data-ttu-id="973f8-195">**後憑證核准： AppSource 中 Microsoft 365 憑證徽章的範例。**</span><span class="sxs-lookup"><span data-stu-id="973f8-195">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource.**</span></span> 

![認證後核准](../media/UserGuidePhotos/27.png)
 
## <a name="5---microsoft-365-renewal-workflow"></a><span data-ttu-id="973f8-197">5. Microsoft 365 更新工作流程：</span><span class="sxs-lookup"><span data-stu-id="973f8-197">5.   Microsoft 365 Renewal Workflow:</span></span>
  
<span data-ttu-id="973f8-198">**Microsoft 365 Publisher 證明和認證更新工作流程：**</span><span class="sxs-lookup"><span data-stu-id="973f8-198">**Microsoft 365 Publisher Attestation and Certification Renewal Workflow:**</span></span>  

<span data-ttu-id="973f8-199">Microsoft 365App 相容性計畫現在提供一年的更新程式。</span><span class="sxs-lookup"><span data-stu-id="973f8-199">Microsoft 365 App Compliance program now offers an annual renewal process.</span></span> <span data-ttu-id="973f8-200">在此程式中，應用程式開發人員可以更新 Microsoft 365 憑證所需的現有 Publisher 認證問卷及檔。</span><span class="sxs-lookup"><span data-stu-id="973f8-200">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 
 
<span data-ttu-id="973f8-201">**好處：**</span><span class="sxs-lookup"><span data-stu-id="973f8-201">**Benefits:**</span></span> 

- <span data-ttu-id="973f8-202">在 AppSource、Office 存放區、Teams 存放區和各種系統管理員入口網站中維護您的憑證徽章，以將您的應用程式與其他使用者區別開來。</span><span class="sxs-lookup"><span data-stu-id="973f8-202">Maintain your certification badge in AppSource, the Office Store, the Teams Store and various admin portals to differentiate your app from others.</span></span> 
- <span data-ttu-id="973f8-203">使用認證的應用程式，提高客戶的信賴程度。</span><span class="sxs-lookup"><span data-stu-id="973f8-203">Increase customer confidence in using your certified app.</span></span> 
- <span data-ttu-id="973f8-204">協助 IT 管理員以更新的認證資訊作出合理的決策。</span><span class="sxs-lookup"><span data-stu-id="973f8-204">Help IT admins make informed decisions with updated certification information.</span></span>

<span data-ttu-id="973f8-205">您可以在 [合作夥伴中心](https://partner.microsoft.com/dashboard/home) 取得新的更新程式，以提供無縫體驗。</span><span class="sxs-lookup"><span data-stu-id="973f8-205">The new renewal process is available in [Partner Center](https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="973f8-206">在夥伴中心的到期日的開始90天之後，將會顯示更新提醒。</span><span class="sxs-lookup"><span data-stu-id="973f8-206">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="973f8-207">定期提醒也會透過電子郵件于到期的90、60和30天傳送。</span><span class="sxs-lookup"><span data-stu-id="973f8-207">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span> 
 
<span data-ttu-id="973f8-208">**階段1： Publisher 證明更新：**</span><span class="sxs-lookup"><span data-stu-id="973f8-208">**Phase 1: Publisher Attestation Renewal:**</span></span>
  
<span data-ttu-id="973f8-209">應用程式的 Publisher 認證答案將需要一年重新提交。</span><span class="sxs-lookup"><span data-stu-id="973f8-209">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="973f8-210">當證明接近1年標記時，系統會傳送電子郵件提醒，以鼓勵重新提交證明。</span><span class="sxs-lookup"><span data-stu-id="973f8-210">When the attestation nears the 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 
 
<span data-ttu-id="973f8-211">**步驟 1**：選取 [**續訂**] 以更新 Publisher 認證。</span><span class="sxs-lookup"><span data-stu-id="973f8-211">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span>
  
![Renewel 核准](../media/UserGuidePhotos/31.png)
  
<span data-ttu-id="973f8-213">**步驟 2**：查看先前的 Publisher 認證答案，並視需要更新最新資訊。</span><span class="sxs-lookup"><span data-stu-id="973f8-213">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> 
  
<span data-ttu-id="973f8-214">提交 Publisher 認證以于準備時進行更新。</span><span class="sxs-lookup"><span data-stu-id="973f8-214">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="973f8-215">M365 應用程式規範分析員會檢查它。</span><span class="sxs-lookup"><span data-stu-id="973f8-215">It will be reviewed by an M365 App Compliance analyst.</span></span>

![更新為證明](../media/UserGuidePhotos/29.png)
  
<span data-ttu-id="973f8-217">**Publisher認證更新已核准：**</span><span class="sxs-lookup"><span data-stu-id="973f8-217">**Publisher Attestation Renewal Approved:**</span></span>
  
![提交以進行更新](../media/UserGuidePhotos/30.png)
  
<span data-ttu-id="973f8-219">**Publisher證明已到期：**</span><span class="sxs-lookup"><span data-stu-id="973f8-219">**Publisher Attestation Expired:**</span></span>
  
<span data-ttu-id="973f8-220">應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 Publisher 認證頁面。及時更新也會確保在不同的店面中應用程式的持續聲譽徽章授予和圖示。</span><span class="sxs-lookup"><span data-stu-id="973f8-220">The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in various storefronts.</span></span> 
 
![Renewel 核准](../media/UserGuidePhotos/31.png)

<span data-ttu-id="973f8-222">**附注**：已到期，只要按一下「更新」，即可隨時啟動 Publisher 證明更新程式。</span><span class="sxs-lookup"><span data-stu-id="973f8-222">**Note**: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span>
 
<span data-ttu-id="973f8-223">**階段2： Microsoft 365 憑證更新**</span><span class="sxs-lookup"><span data-stu-id="973f8-223">**Phase 2: Microsoft 365 Certification Renewal**</span></span>
  
<span data-ttu-id="973f8-224">應用程式的認證資訊需要一年的頻率重新提交。</span><span class="sxs-lookup"><span data-stu-id="973f8-224">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="973f8-225">這將需要重新驗證您目前環境中的範圍內控制項。</span><span class="sxs-lookup"><span data-stu-id="973f8-225">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="973f8-226">當憑證臨近1年標記時，系統會傳送電子郵件通知，以鼓勵重新提交檔和證據。</span><span class="sxs-lookup"><span data-stu-id="973f8-226">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span>
 
![證明 Renewel](../media/UserGuidePhotos/32.png) 

<span data-ttu-id="973f8-228">**認證更新核准/拒絕案例：**</span><span class="sxs-lookup"><span data-stu-id="973f8-228">**Certification Renewal Approve/Reject Scenarios:**</span></span>

<span data-ttu-id="973f8-229">**案例1：**</span><span class="sxs-lookup"><span data-stu-id="973f8-229">**Scenario 1:**</span></span> 

<span data-ttu-id="973f8-230">憑證更新已開始，且正在審查中。</span><span class="sxs-lookup"><span data-stu-id="973f8-230">Certification renewal has started and is under review.</span></span>
 
![認證 renewel](../media/UserGuidePhotos/33.png) 

<span data-ttu-id="973f8-232">案例1A：</span><span class="sxs-lookup"><span data-stu-id="973f8-232">Scenario 1A:</span></span> 

<span data-ttu-id="973f8-233">認證更新拒絕：</span><span class="sxs-lookup"><span data-stu-id="973f8-233">Certification renewal rejection:</span></span> 
- <span data-ttu-id="973f8-234">在下列情況中，可能會拒絕認證：</span><span class="sxs-lookup"><span data-stu-id="973f8-234">Certification may be rejected if:</span></span> 
     - <span data-ttu-id="973f8-235">應用程式不具備必要的工具、程式或設定，也無法在認證視窗中執行所需的變更。</span><span class="sxs-lookup"><span data-stu-id="973f8-235">The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> 
     - <span data-ttu-id="973f8-236">應用程式有未完成的漏洞，無法在認證視窗內修正。</span><span class="sxs-lookup"><span data-stu-id="973f8-236">The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 
 
![憑證拒絕](../media/UserGuidePhotos/34.png)

<span data-ttu-id="973f8-238">案例1B：</span><span class="sxs-lookup"><span data-stu-id="973f8-238">Scenario 1B:</span></span> 

<span data-ttu-id="973f8-239">認證更新已獲批准</span><span class="sxs-lookup"><span data-stu-id="973f8-239">Certification renewal is approved</span></span>

![認證 renewel 核准](../media/UserGuidePhotos/35.png)

<span data-ttu-id="973f8-241">**認證到期：**</span><span class="sxs-lookup"><span data-stu-id="973f8-241">**Certification Expiration:**</span></span>

<span data-ttu-id="973f8-242">應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 [證書] 頁面。及時更新也會確保 AppSource 和小組存放區中的應用程式持續聲譽徽章授予及圖示。</span><span class="sxs-lookup"><span data-stu-id="973f8-242">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![認證 renewel 核准](../media/UserGuidePhotos/36.png)
  
<span data-ttu-id="973f8-244">附注：只要按一下「更新」，即可隨時啟動 Publisher 證明和認證程式。</span><span class="sxs-lookup"><span data-stu-id="973f8-244">Note: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 
