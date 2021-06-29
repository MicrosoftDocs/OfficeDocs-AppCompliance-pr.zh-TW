---
title: SaaS 應用程式的使用者指南
author: LGerrard
ms.author: legerrar
description: Microsoft 365 應用程式規範方案的 ISV 使用者指南 SaaS
keywords: Microsoft 365 應用程式規範方案的 ISV 使用者指南 SaaS
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 64059ff6d38313765053ab0fe5d023fb606d4eda
ms.sourcegitcommit: bfabb191087786fae2b476e3f30861317886defa
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/29/2021
ms.locfileid: "53178978"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program---saas"></a><span data-ttu-id="4f161-104">Microsoft 365 應用程式規範計畫的協力廠商使用者指南-SaaS</span><span class="sxs-lookup"><span data-stu-id="4f161-104">Partner's User Guide for Microsoft 365 App Compliance Program - SaaS</span></span>

|<span data-ttu-id="4f161-105">階段</span><span class="sxs-lookup"><span data-stu-id="4f161-105">Phase</span></span>|<span data-ttu-id="4f161-106">職稱</span><span class="sxs-lookup"><span data-stu-id="4f161-106">Title</span></span>|
|---|---|
|<span data-ttu-id="4f161-107">階段1</span><span class="sxs-lookup"><span data-stu-id="4f161-107">Phase 1</span></span>| <span data-ttu-id="4f161-108">發行者證明</span><span class="sxs-lookup"><span data-stu-id="4f161-108">Publisher Attestation</span></span>|
|<span data-ttu-id="4f161-109">階段2</span><span class="sxs-lookup"><span data-stu-id="4f161-109">Phase 2</span></span>| <span data-ttu-id="4f161-110">Microsoft 365 憑證</span><span class="sxs-lookup"><span data-stu-id="4f161-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="4f161-111">1. 簡介</span><span class="sxs-lookup"><span data-stu-id="4f161-111">1. Overview</span></span> 

<span data-ttu-id="4f161-112">這份檔是為我們的合作夥伴做為逐步的使用者指南，註冊 Microsoft 365 應用程式規範計畫，想要對其 SaaS app 進行 Publisher 證明和認證，但夥伴中心入口網站。</span><span class="sxs-lookup"><span data-stu-id="4f161-112">This document acts as a step-by-step user guide for our Partners, enrolled for Microsoft 365 App Compliance Program aiming to undergo Publisher Attestation and Certification for their SaaS apps, though Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="4f161-113">2. 縮寫 & 定義</span><span class="sxs-lookup"><span data-stu-id="4f161-113">2. Acronyms & Definitions</span></span>
|<span data-ttu-id="4f161-114">縮略字</span><span class="sxs-lookup"><span data-stu-id="4f161-114">Acronym</span></span> | <span data-ttu-id="4f161-115">定義</span><span class="sxs-lookup"><span data-stu-id="4f161-115">Definition</span></span> |
|----|----|
|[<span data-ttu-id="4f161-116">電腦 (合作夥伴中心) </span><span class="sxs-lookup"><span data-stu-id="4f161-116">PC (Partner Center)</span></span>](https://partner.microsoft.com/)|<span data-ttu-id="4f161-117">所有 Microsoft 合作夥伴的入口網站。</span><span class="sxs-lookup"><span data-stu-id="4f161-117">A portal for all Microsoft Partners.</span></span> <span data-ttu-id="4f161-118">合作夥伴會登入至夥伴中心，並提交 Self-Assessment 問卷。</span><span class="sxs-lookup"><span data-stu-id="4f161-118">A Partner logs in to Partner Center and submits Self-Assessment Questionnaire.</span></span> <span data-ttu-id="4f161-119">[Microsoft 365 應用程式相容性](https://partner.microsoft.com/dashboard/home)的合作夥伴中心</span><span class="sxs-lookup"><span data-stu-id="4f161-119">Partner Center for [Microsoft 365 App Compliance](https://partner.microsoft.com/dashboard/home)</span></span>|
|<span data-ttu-id="4f161-120">ISV</span><span class="sxs-lookup"><span data-stu-id="4f161-120">ISV</span></span> | <span data-ttu-id="4f161-121">獨立軟體廠商 a.k.a。</span><span class="sxs-lookup"><span data-stu-id="4f161-121">Independent Software Vendor a.k.a.</span></span> <span data-ttu-id="4f161-122">Partner or Developer</span><span class="sxs-lookup"><span data-stu-id="4f161-122">Partner or Developer</span></span> |
|<span data-ttu-id="4f161-123">應用程式來源</span><span class="sxs-lookup"><span data-stu-id="4f161-123">App Source</span></span> | <span data-ttu-id="4f161-124"> (的應用程式目錄 AppSource) 範例： [Now virtual agent](https://appsource.microsoft.com/product/office/WA104381816)</span><span class="sxs-lookup"><span data-stu-id="4f161-124">Catalog of apps (AppSource) Example: [Now virtual agent](https://appsource.microsoft.com/product/office/WA104381816)</span></span> |

## <a name="3-publisher-attestation-workflow"></a><span data-ttu-id="4f161-125">3. Publisher 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="4f161-125">3. Publisher Attestation Workflow</span></span>

<span data-ttu-id="4f161-126">**首頁**：這是一次夥伴登入夥伴中心的登陸頁面。</span><span class="sxs-lookup"><span data-stu-id="4f161-126">**Home Page**: This is the landing page once a partner logs in to Partner Center.</span></span>

![atl-ws-01](../media/UserGuidePhotos/01.png)
  
<span data-ttu-id="4f161-128">**步驟 1** ：在頁面左側的導覽列上：</span><span class="sxs-lookup"><span data-stu-id="4f161-128">**Step 1** : On the left side of the page, on the navigation bar:</span></span>

      a.    Select Commercial Marketplace
      
      b.    Select Overview

![02](../Apps/media/UserGuidePhotos/02.png)
  
<span data-ttu-id="4f161-130">選取「一覽」時，partner 可以查看可用的應用程式清單，以啟動 Microsoft 365 合規性計畫。</span><span class="sxs-lookup"><span data-stu-id="4f161-130">Upon selecting ‘Overview’, partner can see list of apps available to start the Microsoft 365 Compliance program.</span></span>
  
<span data-ttu-id="4f161-131">**步驟 2**：從清單中選取應用程式，以開始 Publisher 認證程式。</span><span class="sxs-lookup"><span data-stu-id="4f161-131">**Step 2**: Select an app from the list to begin the Publisher Attestation process.</span></span>

 ![3 ](../Apps/media/UserGuidePhotos/03.png)

<span data-ttu-id="4f161-133">在選取應用程式時，會以選項「應用程式相容性」彈出另一個導覽列。</span><span class="sxs-lookup"><span data-stu-id="4f161-133">On selecting an app, another navigation bar will pop up with option ‘App Compliance’.</span></span>
  
<span data-ttu-id="4f161-134">**步驟 3**：選取「應用程式符合性」</span><span class="sxs-lookup"><span data-stu-id="4f161-134">**Step 3**: Select 'App Compliance’</span></span>
  
![4 ](../Apps/media/UserGuidePhotos/04.png)
  
<span data-ttu-id="4f161-136">**步驟 4**：填寫 Publisher 證明的 Self-Assessment 問卷。</span><span class="sxs-lookup"><span data-stu-id="4f161-136">**Step 4**: Fill out the Self-Assessment Questionnaire for Publisher Attestation.</span></span>
 
![5 ](../Apps/media/UserGuidePhotos/05.png)
  
<span data-ttu-id="4f161-138">**附注：如果您要回到更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [複製]。**</span><span class="sxs-lookup"><span data-stu-id="4f161-138">**Note: If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone’.**</span></span>
  
![6 ](../Apps/media/UserGuidePhotos/06.png)
  
<span data-ttu-id="4f161-140">**您也可以利用匯入/匯出功能，離線完成表單，並在完成後將其匯入。**</span><span class="sxs-lookup"><span data-stu-id="4f161-140">**You can also leverage the Import/Export feature to complete the form offline and import it once completed.**</span></span>
  
 ![7 ](../Apps/media/UserGuidePhotos/07.png)
  
 <span data-ttu-id="4f161-142">**步驟 5**：完成後，按一下 [提交]，評估現在會是「審閱」。</span><span class="sxs-lookup"><span data-stu-id="4f161-142">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘under review’.</span></span>
  
 ![8 ](../Apps/media/UserGuidePhotos/08.png)
  
 ![9 ](../Apps/media/UserGuidePhotos/09.png)
  
<span data-ttu-id="4f161-145">**核准/拒絕案例：**</span><span class="sxs-lookup"><span data-stu-id="4f161-145">**Approve/Reject Scenarios:**</span></span>
  
<span data-ttu-id="4f161-146">答：</span><span class="sxs-lookup"><span data-stu-id="4f161-146">A.</span></span>  <span data-ttu-id="4f161-147">Publisher證明拒絕</span><span class="sxs-lookup"><span data-stu-id="4f161-147">Publisher Attestation Rejection</span></span>

    a.  In case of rejection, a Partner can:
    
        •   View failure report
        
            o   Partner will be notified via email, and they can view the failure report in Partner Center
          
        •   Update and re-submit Self-Assessment Questionnaire.
  
 ![10 ](../Apps/media/UserGuidePhotos/10.png)
  
<span data-ttu-id="4f161-149">B。</span><span class="sxs-lookup"><span data-stu-id="4f161-149">B.</span></span>  <span data-ttu-id="4f161-150">Publisher證明核准</span><span class="sxs-lookup"><span data-stu-id="4f161-150">Publisher Attestation Approval</span></span>

    a.  Upon approval, the partner can:
    
        •   Update and resubmit attestation
        
        •   View completed Publisher Attestation
        
        •   Start M365 Certification Process
  
 ![11 ](../Apps/media/UserGuidePhotos/11.png)
  
 ![12 ](../Apps/media/UserGuidePhotos/12.png)
  
 <span data-ttu-id="4f161-153">**Post Publisher 驗證核准： Publisher attested 應用程式 AppSource 中的連結範例。**</span><span class="sxs-lookup"><span data-stu-id="4f161-153">**Post Publisher Verification Approval: Example of link in AppSource for publisher attested apps.**</span></span>
  
  ![13 ](../Apps/media/UserGuidePhotos/13.png)
  
 ## <a name="4--microsoft-365-certification-workflow"></a><span data-ttu-id="4f161-155">4. Microsoft 365 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="4f161-155">4.  Microsoft 365 Certification Workflow</span></span>
  
 <span data-ttu-id="4f161-156">協力廠商可以從選取核取方塊，然後按一下 [提交]，以開始認證程式。</span><span class="sxs-lookup"><span data-stu-id="4f161-156">A partner can begin the Certification process by selecting the checkbox and clicking ‘Submit’</span></span>
  
 ![14 ](../Apps/media/UserGuidePhotos/14.png)
  
<span data-ttu-id="4f161-158">**步驟 1** ：初始檔提交</span><span class="sxs-lookup"><span data-stu-id="4f161-158">**Step 1** : Initial Document Submission</span></span>

 <span data-ttu-id="4f161-159">填寫所有詳細資料，上傳相關的檔，然後按一下 [提交]</span><span class="sxs-lookup"><span data-stu-id="4f161-159">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>
  
 ![8](../Apps/media/UserGuidePhotos/15.png)
  
 ![16 ](../Apps/media/UserGuidePhotos/16.png)
 
<span data-ttu-id="4f161-162">在按一下 [提交] 時，會進行審閱。</span><span class="sxs-lookup"><span data-stu-id="4f161-162">On clicking Submit, the submission will be under review.</span></span>
 
![17 ](../Apps/media/UserGuidePhotos/17.png)
  
 <span data-ttu-id="4f161-164">當初始檔不足或沒有相關時，分析員會要求修訂。</span><span class="sxs-lookup"><span data-stu-id="4f161-164">An analyst requests a revision in case the initial documents are not sufficient or relevant.</span></span> <span data-ttu-id="4f161-165">分析員會與合作夥伴合作，協助您取得適當的檔以供核准。</span><span class="sxs-lookup"><span data-stu-id="4f161-165">The analyst will work with the Partner to help get the right documents for approval.</span></span>
  
![18 ](https://github.com/MicrosoftDocs/OfficeDocs-AppCompliance-pr/blob/master/Apps/media/UserGuidePhotos/18.png)
  
<span data-ttu-id="4f161-167">當分析員核准初始檔提交後，協力廠商必須提交控制需求。</span><span class="sxs-lookup"><span data-stu-id="4f161-167">Once the analyst approves the initial document submission, the partner needs to submit the control requirements.</span></span>
  
<span data-ttu-id="4f161-168">**步驟 2**：控制需求提交</span><span class="sxs-lookup"><span data-stu-id="4f161-168">**Step 2**: Control Requirement Submission</span></span>
  
<span data-ttu-id="4f161-169">填寫所有詳細資料，上傳相關的檔，然後按一下 [提交]</span><span class="sxs-lookup"><span data-stu-id="4f161-169">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>

![19](../Apps/media/UserGuidePhotos/19.png)

![共](../Apps/media/UserGuidePhotos/20.png)

![ 21](../Apps/media/UserGuidePhotos/21.png)
 
<span data-ttu-id="4f161-173">在按一下 [提交] 時，會進行審閱。</span><span class="sxs-lookup"><span data-stu-id="4f161-173">On clicking Submit, the submission will be under review.</span></span>
  
![22](../Apps/media/UserGuidePhotos/22.png)
  
<span data-ttu-id="4f161-175">當控制項需求檔不足或沒有相關時，分析員會要求修訂。</span><span class="sxs-lookup"><span data-stu-id="4f161-175">An analyst requests a revision in case the control requirement documents are not sufficient or relevant.</span></span> <span data-ttu-id="4f161-176">分析員會與合作夥伴合作，協助您取得適當的檔以供核准。</span><span class="sxs-lookup"><span data-stu-id="4f161-176">The analyst will work with the Partner to help get the right documents for approval.</span></span>
  
![至](../Apps/media/UserGuidePhotos/23.png)
  
![24](../Apps/media/UserGuidePhotos/24.png)
  
![0.25](../Apps/media/UserGuidePhotos/25.png)
  
<span data-ttu-id="4f161-180">若提交不符合核准標準，則分析員會拒絕提交。</span><span class="sxs-lookup"><span data-stu-id="4f161-180">In case the submission does not satisfy the approval standards, the analyst will reject the submission.</span></span>
  
<span data-ttu-id="4f161-181">合作夥伴可以與分析員搭配使用，以提供相關資訊和檔。</span><span class="sxs-lookup"><span data-stu-id="4f161-181">The partner can work with the analyst to provide the relevant information and documents.</span></span>
  
![得到](../Apps/media/UserGuidePhotos/26.png)
  
<span data-ttu-id="4f161-183">所有的安全性標準都符合後，分析員便會核准提交，而且會 Microsoft 365 認證合作夥伴。</span><span class="sxs-lookup"><span data-stu-id="4f161-183">Once all the security standards have been met, the analyst will approve the submission and the partner will be Microsoft 365 Certified.</span></span>
  
![7](../media/UserGuidePhotos/27.png)
  
<span data-ttu-id="4f161-185">\* \* 後憑證核准： AppSource 中 Microsoft 365 憑證徽章的範例。</span><span class="sxs-lookup"><span data-stu-id="4f161-185">\*\*Post Certification Approval: Example of Microsoft 365 certification badge in AppSource.</span></span> ** 
  
![日](../Apps/media/UserGuidePhotos/28.png)
  
## <a name="5---microsoft-365-renewal-workflow"></a><span data-ttu-id="4f161-187">5. Microsoft 365 更新工作流程：</span><span class="sxs-lookup"><span data-stu-id="4f161-187">5.   Microsoft 365 Renewal Workflow:</span></span>
  
<span data-ttu-id="4f161-188">**Microsoft 365 Publisher 證明和認證更新工作流程：**</span><span class="sxs-lookup"><span data-stu-id="4f161-188">**Microsoft 365 Publisher Attestation and Certification Renewal Workflow:**</span></span>  

<span data-ttu-id="4f161-189">Microsoft 365App 相容性計畫現在提供一年的更新程式。</span><span class="sxs-lookup"><span data-stu-id="4f161-189">Microsoft 365 App Compliance Program now offers an annual renewal process.</span></span> <span data-ttu-id="4f161-190">在此程式中，應用程式開發人員可以更新 Microsoft 365 憑證所需的現有 Publisher 認證問卷及檔。</span><span class="sxs-lookup"><span data-stu-id="4f161-190">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 
 
<span data-ttu-id="4f161-191">**好處：**</span><span class="sxs-lookup"><span data-stu-id="4f161-191">**Benefits:**</span></span> 

  <span data-ttu-id="4f161-192">•維護 AppSource 和團隊存放區中的憑證徽章，以將您的應用程式與其他使用者區別開來。</span><span class="sxs-lookup"><span data-stu-id="4f161-192">• Maintain your certification badge in AppSource and Team Store to differentiate your app from others.</span></span> 
  
  <span data-ttu-id="4f161-193">•使用認證的應用程式，提高客戶的信賴程度。</span><span class="sxs-lookup"><span data-stu-id="4f161-193">• Increase customer confidence in using your certified app.</span></span> 
  
  <span data-ttu-id="4f161-194">•協助 IT 管理員以更新的認證資訊作出合理的決策。</span><span class="sxs-lookup"><span data-stu-id="4f161-194">• Help IT admins make informed decisions with updated certification information.</span></span>

<span data-ttu-id="4f161-195">新的續訂程式可在夥伴中心 (https://partner.microsoft.com/dashboard/home) ，以提供無縫體驗。</span><span class="sxs-lookup"><span data-stu-id="4f161-195">The new renewal process is available in Partner Center(https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="4f161-196">在夥伴中心的到期日的開始90天之後，將會顯示更新提醒。</span><span class="sxs-lookup"><span data-stu-id="4f161-196">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="4f161-197">定期提醒也會透過電子郵件于到期的90、60和30天傳送。</span><span class="sxs-lookup"><span data-stu-id="4f161-197">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span> 
 
<span data-ttu-id="4f161-198">**第1層： Publisher 認證更新：**</span><span class="sxs-lookup"><span data-stu-id="4f161-198">**Tier 1: Publisher Attestation Renewal:**</span></span>
  
<span data-ttu-id="4f161-199">應用程式的 Publisher 認證答案將需要一年重新提交。</span><span class="sxs-lookup"><span data-stu-id="4f161-199">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="4f161-200">當證明臨近1年標記時，系統會傳送電子郵件提醒，以鼓勵重新提交證明。</span><span class="sxs-lookup"><span data-stu-id="4f161-200">When the attestation nears 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 
 
<span data-ttu-id="4f161-201">**步驟 1**：選取 [**續訂**] 以更新 Publisher 認證。</span><span class="sxs-lookup"><span data-stu-id="4f161-201">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span>
  
![29](../Apps/media/UserGuidePhotos/29.png)
  
<span data-ttu-id="4f161-203">**步驟 2**：查看先前的 Publisher 認證答案，並視需要更新最新資訊。</span><span class="sxs-lookup"><span data-stu-id="4f161-203">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> 
  
<span data-ttu-id="4f161-204">提交 Publisher 認證以于準備時進行更新。</span><span class="sxs-lookup"><span data-stu-id="4f161-204">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="4f161-205">M365 應用程式規範分析員會檢查它。</span><span class="sxs-lookup"><span data-stu-id="4f161-205">It will be reviewed by an M365 App Compliance Analyst.</span></span>
  
![大約](../Apps/media/UserGuidePhotos/30.png)
  
<span data-ttu-id="4f161-207">**Publisher認證更新已核准：**</span><span class="sxs-lookup"><span data-stu-id="4f161-207">**Publisher Attestation Renewal Approved:**</span></span>
  
![加](../Apps/media/UserGuidePhotos/31.png)
  
<span data-ttu-id="4f161-209">**Publisher證明已到期：**</span><span class="sxs-lookup"><span data-stu-id="4f161-209">**Publisher Attestation Expired:**</span></span>
  
<span data-ttu-id="4f161-210">應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 Publisher 認證頁面。及時更新也會確保 AppSource 和小組存放區中的應用程式持續聲譽徽章授予及圖示。</span><span class="sxs-lookup"><span data-stu-id="4f161-210">The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>
  
![32](../Apps/media/UserGuidePhotos/32.png)
  
<span data-ttu-id="4f161-212">**附注**：已到期，只要按一下「更新」，即可隨時啟動 Publisher 證明更新程式。</span><span class="sxs-lookup"><span data-stu-id="4f161-212">**Note**: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span>
 
<span data-ttu-id="4f161-213">**第2層： Microsoft 365 認證更新**</span><span class="sxs-lookup"><span data-stu-id="4f161-213">**Tier 2: Microsoft 365 Certification Renewal**</span></span>
  
<span data-ttu-id="4f161-214">應用程式的認證資訊需要一年的頻率重新提交。</span><span class="sxs-lookup"><span data-stu-id="4f161-214">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="4f161-215">這將需要重新驗證您目前環境中的範圍內控制項。</span><span class="sxs-lookup"><span data-stu-id="4f161-215">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="4f161-216">當憑證臨近1年標記時，系統會傳送電子郵件通知，以鼓勵重新提交檔和證據。</span><span class="sxs-lookup"><span data-stu-id="4f161-216">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span>
  
![33](../Apps/media/UserGuidePhotos/33.png)
  
<span data-ttu-id="4f161-218">**認證更新核准/拒絕案例：**</span><span class="sxs-lookup"><span data-stu-id="4f161-218">**Certification Renewal Approve/Reject Scenarios:**</span></span>
 
<span data-ttu-id="4f161-219">**案例1：** 憑證更新已開始，且正在審查中。</span><span class="sxs-lookup"><span data-stu-id="4f161-219">**Scenario 1:** Certification renewal has started and is under review.</span></span>
  
![34](../Apps/media/UserGuidePhotos/34.png)

<span data-ttu-id="4f161-221">案例1A：憑證更新拒絕：如果：•應用程式沒有適當的工具、處理常式或設定，也無法在認證視窗中執行所需的變更，則可能會拒絕認證。</span><span class="sxs-lookup"><span data-stu-id="4f161-221">Scenario 1A: Certification renewal rejection: Certification may be rejected if: •   The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> <span data-ttu-id="4f161-222">•應用程式有未完成的漏洞，無法在認證視窗內修正。</span><span class="sxs-lookup"><span data-stu-id="4f161-222">•   The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 
  
![35](../Apps/media/UserGuidePhotos/35.png)
  
<span data-ttu-id="4f161-224">案例1B：認證更新已獲核准</span><span class="sxs-lookup"><span data-stu-id="4f161-224">Scenario 1B: Certification renewal is approved</span></span>

![36](../Apps/media/UserGuidePhotos/36.png)

<span data-ttu-id="4f161-226">**認證到期：**</span><span class="sxs-lookup"><span data-stu-id="4f161-226">**Certification Expiration:**</span></span>
 
<span data-ttu-id="4f161-227">應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 [證書] 頁面。及時更新也會確保 AppSource 和小組存放區中的應用程式持續聲譽徽章授予及圖示。</span><span class="sxs-lookup"><span data-stu-id="4f161-227">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![5.5](../Apps/media/UserGuidePhotos/5.5.png)
  
<span data-ttu-id="4f161-229">附注：只要按一下「更新」，即可隨時啟動 Publisher 證明和認證程式。</span><span class="sxs-lookup"><span data-stu-id="4f161-229">Note: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 




  

  
 

  

 
