---
title: 使用者指南
author: LGerrard
ms.author: legerrar
description: Microsoft 365 應用程式規範計畫的 ISV 使用者指南
keywords: Microsoft 365 應用程式規範計畫的 ISV 使用者指南
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 1da6de6ee6664bb868a2184be538a8e5bbc65ab2
ms.sourcegitcommit: f6f3551bf1c00013efb6313ca3dc280de697137d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/29/2021
ms.locfileid: "53202603"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program"></a><span data-ttu-id="920b8-104">合作夥伴的 Microsoft 365 應用程式規範計畫的使用者指南</span><span class="sxs-lookup"><span data-stu-id="920b8-104">Partner's User Guide for Microsoft 365 App Compliance Program</span></span>

|<span data-ttu-id="920b8-105">階段</span><span class="sxs-lookup"><span data-stu-id="920b8-105">Phase</span></span>|<span data-ttu-id="920b8-106">職稱</span><span class="sxs-lookup"><span data-stu-id="920b8-106">Title</span></span>|
|---|---|
|<span data-ttu-id="920b8-107">階段1</span><span class="sxs-lookup"><span data-stu-id="920b8-107">Phase 1</span></span>| <span data-ttu-id="920b8-108">發行者證明</span><span class="sxs-lookup"><span data-stu-id="920b8-108">Publisher Attestation</span></span>|
|<span data-ttu-id="920b8-109">階段2</span><span class="sxs-lookup"><span data-stu-id="920b8-109">Phase 2</span></span>| <span data-ttu-id="920b8-110">Microsoft 365 憑證</span><span class="sxs-lookup"><span data-stu-id="920b8-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="920b8-111">1. 簡介</span><span class="sxs-lookup"><span data-stu-id="920b8-111">1. Overview</span></span>
<span data-ttu-id="920b8-112">這份檔是在 Microsoft 365 應用程式規範計畫中註冊的合作夥伴逐步使用者指南，其意圖是透過夥伴中心入口網站進行 Publisher 證明和認證。</span><span class="sxs-lookup"><span data-stu-id="920b8-112">This document acts as a step-by-step user guide for our partners enrolled in the Microsoft 365 App Compliance program aiming to undergo Publisher Attestation and Certification though the Partner Center portal.</span></span>


## <a name="2-acronyms--definitions"></a><span data-ttu-id="920b8-113">2. 縮寫 & 定義</span><span class="sxs-lookup"><span data-stu-id="920b8-113">2. Acronyms & Definitions</span></span>
| <span data-ttu-id="920b8-114">縮略字</span><span class="sxs-lookup"><span data-stu-id="920b8-114">Acronym</span></span> |<span data-ttu-id="920b8-115">定義</span><span class="sxs-lookup"><span data-stu-id="920b8-115">Definition</span></span> |
|---|----|
|<span data-ttu-id="920b8-116">電腦 [ (合作夥伴中心) ](https://partner.microsoft.com/)</span><span class="sxs-lookup"><span data-stu-id="920b8-116">PC [(Partner Center)](https://partner.microsoft.com/)</span></span>|<span data-ttu-id="920b8-117">所有 Microsoft 合作夥伴的入口網站。</span><span class="sxs-lookup"><span data-stu-id="920b8-117">A portal for all Microsoft partners.</span></span> <span data-ttu-id="920b8-118">協力廠商會登入至夥伴中心，並提交自我評估問卷。</span><span class="sxs-lookup"><span data-stu-id="920b8-118">A partner logs in to Partner Center and submits self-assessment questionnaire.</span></span> <span data-ttu-id="920b8-119">Microsoft 365 應用程式相容性的[合作夥伴中心](https://partner.microsoft.com/dashboard/home)</span><span class="sxs-lookup"><span data-stu-id="920b8-119">[Partner Center](https://partner.microsoft.com/dashboard/home) for Microsoft 365 App Compliance</span></span>|
|<span data-ttu-id="920b8-120">ISV</span><span class="sxs-lookup"><span data-stu-id="920b8-120">ISV</span></span>|<span data-ttu-id="920b8-121">獨立軟體廠商。</span><span class="sxs-lookup"><span data-stu-id="920b8-121">Independent Software Vendor.</span></span> <span data-ttu-id="920b8-122">A.k.a.</span><span class="sxs-lookup"><span data-stu-id="920b8-122">A.k.a.</span></span> <span data-ttu-id="920b8-123">partner or developer</span><span class="sxs-lookup"><span data-stu-id="920b8-123">partner or developer</span></span>|
|<span data-ttu-id="920b8-124">應用程式來源</span><span class="sxs-lookup"><span data-stu-id="920b8-124">App Source</span></span>| [<span data-ttu-id="920b8-125">應用程式目錄</span><span class="sxs-lookup"><span data-stu-id="920b8-125">Catalog of apps</span></span>](https://appsource.microsoft.com/)
|<span data-ttu-id="920b8-126">範例</span><span class="sxs-lookup"><span data-stu-id="920b8-126">Example</span></span>|[<span data-ttu-id="920b8-127">現在，虛擬代理程式</span><span class="sxs-lookup"><span data-stu-id="920b8-127">Now virtual agent</span></span>](https://appsource.microsoft.com/product/office/WA104381816)|


## <a name="3---publisher-attestation-workflow"></a><span data-ttu-id="920b8-128">3. Publisher 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="920b8-128">3.   Publisher Attestation Workflow</span></span>

<span data-ttu-id="920b8-129">**首頁** ：這是一次夥伴登入夥伴中心的登陸頁面。</span><span class="sxs-lookup"><span data-stu-id="920b8-129">**Home Page** : This is the landing page once a partner logs in to Partner Center.</span></span>

![合作夥伴中心主畫面](../media/UserGuidePhotos/01.png)

<span data-ttu-id="920b8-131">**步驟 1**   ：在頁面左側的導覽列中：</span><span class="sxs-lookup"><span data-stu-id="920b8-131">**Step 1**   : On the left side of the page, in the navigation bar:</span></span>
- <span data-ttu-id="920b8-132">選取 Office 儲存區</span><span class="sxs-lookup"><span data-stu-id="920b8-132">Select Office store</span></span>
- <span data-ttu-id="920b8-133">選取一覽</span><span class="sxs-lookup"><span data-stu-id="920b8-133">Select Overview</span></span>


![Office可以在左側導覽找到存放區](../media/UserGuidePhotos/02.png)

<span data-ttu-id="920b8-135">選取「一覽」時，partner 可以查看透過夥伴中心提交且可用於 Microsoft 365 規範計畫的應用程式清單。</span><span class="sxs-lookup"><span data-stu-id="920b8-135">Upon selecting ‘Overview’, partner can see list of apps submitted through Partner Center and available for the Microsoft 365 Compliance program.</span></span>

<span data-ttu-id="920b8-136">**步驟 2** ：從清單中選取應用程式，以開始 Publisher 認證程式。</span><span class="sxs-lookup"><span data-stu-id="920b8-136">**Step 2** : Select an app from the list to begin the Publisher Attestation process.</span></span>

![選擇您要證明哪個應用程式](../media/UserGuidePhotos/03.png)

<span data-ttu-id="920b8-138">在選取應用程式時，會彈出另一個導覽列，其中包含選項「應用程式相容性」。</span><span class="sxs-lookup"><span data-stu-id="920b8-138">On selecting an app, another navigation bar will pop up with option ‘App Compliance.’</span></span>

<span data-ttu-id="920b8-139">**步驟 3**：選取「應用程式符合性」</span><span class="sxs-lookup"><span data-stu-id="920b8-139">**Step 3**: Select ‘App Compliance’</span></span>

![選取應用程式規範](../media/UserGuidePhotos/04.png)

<span data-ttu-id="920b8-141">**步驟 4**：填寫 Publisher 證明的自我評估問卷</span><span class="sxs-lookup"><span data-stu-id="920b8-141">**Step 4**: Fill out the self-assessment questionnaire for Publisher Attestation</span></span>

![發行者證明](../media/UserGuidePhotos/5.5.png)

<span data-ttu-id="920b8-143">**附注如果您會傳回更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [複製]。**</span><span class="sxs-lookup"><span data-stu-id="920b8-143">**Note If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone.’**</span></span>

![Clone](../media/UserGuidePhotos/05.png)

<span data-ttu-id="920b8-145">您也可以利用匯入/匯出功能，離線完成表單，並在完成後將其匯入。</span><span class="sxs-lookup"><span data-stu-id="920b8-145">You can also leverage the Import/Export feature to complete the form offline and import it once completed.</span></span>

![匯入匯出功能](../media/UserGuidePhotos/06.png)

<span data-ttu-id="920b8-147">**步驟 5**：完成後，按一下 [提交]，評估現在會是「審閱」。</span><span class="sxs-lookup"><span data-stu-id="920b8-147">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘Under Review.'</span></span>

![按一下 Sumbit](../media/UserGuidePhotos/07.png)

![審閱現在正在進行中](../media/UserGuidePhotos/08.png)

### <a name="approvereject-scenarios"></a><span data-ttu-id="920b8-150">核准/拒絕案例：</span><span class="sxs-lookup"><span data-stu-id="920b8-150">Approve/Reject Scenarios:</span></span>

<span data-ttu-id="920b8-151">**Publisher 證明拒絕**</span><span class="sxs-lookup"><span data-stu-id="920b8-151">**A. Publisher Attestation Rejection**</span></span>

- <span data-ttu-id="920b8-152">在此階段遭到拒絕時，合作夥伴可以：</span><span class="sxs-lookup"><span data-stu-id="920b8-152">In case of rejection at this stage, an partner can:</span></span>
    - <span data-ttu-id="920b8-153">查看失敗報告</span><span class="sxs-lookup"><span data-stu-id="920b8-153">View failure report</span></span>
         - <span data-ttu-id="920b8-154">合作夥伴會透過電子郵件通知，而且可以在夥伴中心中查看失敗報告</span><span class="sxs-lookup"><span data-stu-id="920b8-154">Partner will be notified via email, and they can view the failure report in Partner Center</span></span>
    - <span data-ttu-id="920b8-155">更新並重新提交 Publisher 證明</span><span class="sxs-lookup"><span data-stu-id="920b8-155">Update and re-submit Publisher Attestation</span></span>

![更新並重新提交評估](../media/UserGuidePhotos/09.png)


<span data-ttu-id="920b8-157">**b. Publisher 證明核准**</span><span class="sxs-lookup"><span data-stu-id="920b8-157">**B. Publisher Attestation Approval**</span></span>

- <span data-ttu-id="920b8-158">在核准合作夥伴可以執行下列作業：</span><span class="sxs-lookup"><span data-stu-id="920b8-158">Upon approval partner can:</span></span>
    - <span data-ttu-id="920b8-159">更新並重新提交證明</span><span class="sxs-lookup"><span data-stu-id="920b8-159">Update and resubmit attestation</span></span>
    - <span data-ttu-id="920b8-160">查看和共用已完成的 Publisher 證明</span><span class="sxs-lookup"><span data-stu-id="920b8-160">View and share completed Publisher Attestation</span></span>
    - <span data-ttu-id="920b8-161">開始 Microsoft 365 認證程式</span><span class="sxs-lookup"><span data-stu-id="920b8-161">Start Microsoft 365 Certification process</span></span>

![更新並重新提交](../media/UserGuidePhotos/10.png)

![開始 M365 應用程式認證](../media/UserGuidePhotos/11.png)

<span data-ttu-id="920b8-164">**Post Publisher 認證核准： Publisher attested 應用程式 AppSource 中的連結範例**</span><span class="sxs-lookup"><span data-stu-id="920b8-164">**Post Publisher Attestation Approval: Example of link in AppSource for publisher attested apps**</span></span>

![完成證明的範例](../media/UserGuidePhotos/12.png)


## <a name="4-microsoft-365-certification-workflow"></a><span data-ttu-id="920b8-166">4. Microsoft 365 認證工作流程</span><span class="sxs-lookup"><span data-stu-id="920b8-166">4. Microsoft 365 Certification Workflow</span></span>

<span data-ttu-id="920b8-167">協力廠商可以從選取核取方塊，然後按一下 [提交]，以開始認證程式。</span><span class="sxs-lookup"><span data-stu-id="920b8-167">A partner can begin the Certification process by selecting the checkbox and clicking ‘Submit’</span></span> 

![開始認證](../media/UserGuidePhotos/13.png)

<span data-ttu-id="920b8-169">**步驟1：** 初始檔提交填寫所有詳細資料，上傳相關的檔，然後按一下 [提交]</span><span class="sxs-lookup"><span data-stu-id="920b8-169">**Step 1:** Initial Document Submission Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>

<span data-ttu-id="920b8-170">![初始提交 ](../media/UserGuidePhotos/14.png)
 ![ 初始提交2](../media/UserGuidePhotos/15.png)</span><span class="sxs-lookup"><span data-stu-id="920b8-170">![Initial Submission](../media/UserGuidePhotos/14.png)
![Initial Submission 2](../media/UserGuidePhotos/15.png)</span></span>

<span data-ttu-id="920b8-171">在按一下 [提交] 時，證明提交將會受到審核。</span><span class="sxs-lookup"><span data-stu-id="920b8-171">On clicking submit, the attestation submission will be under review.</span></span> 

![Certificaiton 下的評論](../media/UserGuidePhotos/16.png)

<span data-ttu-id="920b8-173">當初始檔不足或沒有相關時，分析員會要求修訂。</span><span class="sxs-lookup"><span data-stu-id="920b8-173">An analyst requests a revision in case the initial documents are not sufficient or relevant.</span></span> <span data-ttu-id="920b8-174">分析員會與合作夥伴合作，協助您取得適當的檔以供核准。</span><span class="sxs-lookup"><span data-stu-id="920b8-174">The analyst will work with the partner to help get the right documents for approval.</span></span> 

![分析檢查提交](../media/UserGuidePhotos/17.png)

<span data-ttu-id="920b8-176">當分析員核准初始檔提交後，協力廠商必須提交控制需求。</span><span class="sxs-lookup"><span data-stu-id="920b8-176">Once the analyst approves the initial document submission, the partner needs to submit the control requirements.</span></span> 

<span data-ttu-id="920b8-177">**步驟2：** 控制需求提交填寫所有詳細資料、上傳相關的檔，然後按一下 [提交]</span><span class="sxs-lookup"><span data-stu-id="920b8-177">**Step 2:** Control Requirement Submission Fill out all the details, upload relevant documents and Click ‘Submit’</span></span> 

<span data-ttu-id="920b8-178">![完全控制需求 ](../media/UserGuidePhotos/18.png)
 ![ Upload 證據 ](../media/UserGuidePhotos/19.png)
 ![ 保證控制需求已完成](../media/UserGuidePhotos/20.png)</span><span class="sxs-lookup"><span data-stu-id="920b8-178">![Complete Control Requirements](../media/UserGuidePhotos/18.png)
![Upload Evidence](../media/UserGuidePhotos/19.png)
![Assure control requirements are complete](../media/UserGuidePhotos/20.png)</span></span>

<span data-ttu-id="920b8-179">在按一下 [提交] 時，認證提交即會進行審閱。</span><span class="sxs-lookup"><span data-stu-id="920b8-179">On clicking Submit, the certification submission will be under review.</span></span> 

![審查中的證據](../media/UserGuidePhotos/21.png)

<span data-ttu-id="920b8-181">當控制項需求檔不足或沒有相關時，分析員會要求修訂。</span><span class="sxs-lookup"><span data-stu-id="920b8-181">An analyst requests a revision in case the control requirement documents are not sufficient or relevant.</span></span> <span data-ttu-id="920b8-182">分析員會與合作夥伴合作，協助您取得適當的檔以供核准。</span><span class="sxs-lookup"><span data-stu-id="920b8-182">The analyst will work with the partner to help get the right documents for approval.</span></span> 

<span data-ttu-id="920b8-183">![證據需要更新 ](../media/UserGuidePhotos/22.png)
 ![ 瞭解哪些證據需要 ](../media/UserGuidePhotos/23.png)
 ![ 在審查時更新證據](../media/UserGuidePhotos/24.png)</span><span class="sxs-lookup"><span data-stu-id="920b8-183">![Evidence needs updating](../media/UserGuidePhotos/22.png)
![Understand which evidence needs updating](../media/UserGuidePhotos/23.png)
![Evidence under review](../media/UserGuidePhotos/24.png)</span></span>

<span data-ttu-id="920b8-184">若提交不符合核准標準，則分析員會拒絕提交。</span><span class="sxs-lookup"><span data-stu-id="920b8-184">In case the submission does not satisfy the approval standards, the analyst will reject the submission.</span></span> <span data-ttu-id="920b8-185">合作夥伴可以與分析員搭配使用，以提供相關資訊和檔。</span><span class="sxs-lookup"><span data-stu-id="920b8-185">The partner can work with the analyst to provide the relevant information and documents.</span></span> 

![拒絕提交](../media/UserGuidePhotos/25.png)

<span data-ttu-id="920b8-187">所有的安全性標準都符合後，分析員便會核准提交，而且會 Microsoft 365 認證合作夥伴。</span><span class="sxs-lookup"><span data-stu-id="920b8-187">Once all the security standards have been met, the analyst will approve the submission and the partner will be Microsoft 365 Certified.</span></span> 

![已核准提交](../media/UserGuidePhotos/26.png)

<span data-ttu-id="920b8-189">**後憑證核准： AppSource 中 Microsoft 365 憑證徽章的範例**</span><span class="sxs-lookup"><span data-stu-id="920b8-189">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource**</span></span>

![認證標記範例](../media/UserGuidePhotos/27.png)

## <a name="5---microsoft-365-renewal-workflow"></a><span data-ttu-id="920b8-191">5. Microsoft 365 更新工作流程：</span><span class="sxs-lookup"><span data-stu-id="920b8-191">5.   Microsoft 365 Renewal Workflow:</span></span>
  
<span data-ttu-id="920b8-192">**Microsoft 365 Publisher 證明和憑證更新工作流程：** Microsoft 365 App 合規性計畫現在提供一年的更新程式。</span><span class="sxs-lookup"><span data-stu-id="920b8-192">**Microsoft 365 Publisher Attestation and Certification Renewal Workflow:** Microsoft 365 App Compliance Program now offers an annual renewal process.</span></span> <span data-ttu-id="920b8-193">在此程式中，應用程式開發人員可以更新 Microsoft 365 憑證所需的現有 Publisher 認證問卷及檔。</span><span class="sxs-lookup"><span data-stu-id="920b8-193">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 
 
<span data-ttu-id="920b8-194">**好處：**</span><span class="sxs-lookup"><span data-stu-id="920b8-194">**Benefits:**</span></span> 

- <span data-ttu-id="920b8-195">在 AppSource、Teams 存放區、Office 存放區和其他書店中維護您的憑證徽章，以區別應用程式。</span><span class="sxs-lookup"><span data-stu-id="920b8-195">Maintain your certification badge in AppSource, the Teams Store, the Office Store and other storefronts to differentiate the app.</span></span> 
- <span data-ttu-id="920b8-196">使用認證的應用程式，提高客戶的信賴程度。</span><span class="sxs-lookup"><span data-stu-id="920b8-196">Increase customer confidence in using your certified app.</span></span> 
- <span data-ttu-id="920b8-197">協助 IT 管理員以更新的認證資訊作出合理的決策。</span><span class="sxs-lookup"><span data-stu-id="920b8-197">Help IT admins make informed decisions with updated certification information.</span></span> 

<span data-ttu-id="920b8-198">您可以在 [合作夥伴中心](https://partner.microsoft.com/dashboard/home) 取得更新程式，以提供無縫體驗。</span><span class="sxs-lookup"><span data-stu-id="920b8-198">The renewal process is available in [Partner Center](https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="920b8-199">在夥伴中心的到期日的開始90天之後，將會顯示更新提醒。</span><span class="sxs-lookup"><span data-stu-id="920b8-199">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="920b8-200">定期提醒也會透過電子郵件于到期的90、60和30天傳送。</span><span class="sxs-lookup"><span data-stu-id="920b8-200">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span>

<span data-ttu-id="920b8-201">**階段1： Publisher 證明更新：**</span><span class="sxs-lookup"><span data-stu-id="920b8-201">**Phase 1: Publisher Attestation Renewal:**</span></span> 

<span data-ttu-id="920b8-202">您可以在 [合作夥伴中心](https://partner.microsoft.com/dashboard/home) 取得新的更新程式，以提供無縫體驗。</span><span class="sxs-lookup"><span data-stu-id="920b8-202">The new renewal process is available in [Partner Center](https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="920b8-203">在夥伴中心的到期日的開始90天之後，將會顯示更新提醒。</span><span class="sxs-lookup"><span data-stu-id="920b8-203">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="920b8-204">定期提醒也會透過電子郵件于到期的90、60和30天傳送。</span><span class="sxs-lookup"><span data-stu-id="920b8-204">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span> 

<span data-ttu-id="920b8-205">**步驟 1**：選取 [**續訂**] 以更新 Publisher 認證。</span><span class="sxs-lookup"><span data-stu-id="920b8-205">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span> 

![Microsoft 365 Publisher 證明和認證更新工作流程 ](../media/UserGuidePhotos/28.png)

<span data-ttu-id="920b8-207">**步驟 2**：查看先前的 Publisher 認證答案，並視需要更新最新資訊。</span><span class="sxs-lookup"><span data-stu-id="920b8-207">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> <span data-ttu-id="920b8-208">提交 Publisher 認證以于準備時進行更新。</span><span class="sxs-lookup"><span data-stu-id="920b8-208">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="920b8-209">Microsoft 365 應用程式相容性分析員會檢查它。</span><span class="sxs-lookup"><span data-stu-id="920b8-209">It will be reviewed by an Microsoft 365 app compliance analyst.</span></span>

![更新 Publisher 證明](../media/UserGuidePhotos/29.png)

<span data-ttu-id="920b8-211">**Publisher已核准的證明更新**</span><span class="sxs-lookup"><span data-stu-id="920b8-211">**Publisher Attestation Renewal Approved**</span></span>

![Publisher認證更新](../media/UserGuidePhotos/30.png)

<span data-ttu-id="920b8-213">**Publisher 證明已過期：** 應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 Publisher 認證頁面。及時更新也會確保 AppSource 中的應用程式持續聲譽徽章授予和圖示、Teams 儲存區、Office 存放區及其他書店。</span><span class="sxs-lookup"><span data-stu-id="920b8-213">**Publisher Attestation Expired:** The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource, Teams Store, Office Store and other storefronts.</span></span>

![Publisher證明已到期](../media/UserGuidePhotos/31.png)

<span data-ttu-id="920b8-215">附注：已到期，只要按一下「更新」，即可隨時啟動 Publisher 證明更新程式。</span><span class="sxs-lookup"><span data-stu-id="920b8-215">Note: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span> 

<span data-ttu-id="920b8-216">**階段2： Microsoft 365 憑證更新**</span><span class="sxs-lookup"><span data-stu-id="920b8-216">**Phase 2: Microsoft 365 Certification Renewal**</span></span> 

<span data-ttu-id="920b8-217">應用程式的認證資訊需要一年的頻率重新提交。</span><span class="sxs-lookup"><span data-stu-id="920b8-217">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="920b8-218">這將需要重新驗證您目前環境中的範圍內控制項。</span><span class="sxs-lookup"><span data-stu-id="920b8-218">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="920b8-219">當憑證臨近1年標記時，系統會傳送電子郵件通知，以鼓勵重新提交檔和證據。</span><span class="sxs-lookup"><span data-stu-id="920b8-219">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span> 

![認證更新](../media/UserGuidePhotos/32.png)

<span data-ttu-id="920b8-221">**認證更新核准/拒絕案例：**</span><span class="sxs-lookup"><span data-stu-id="920b8-221">**Certification Renewal Approve/Reject Scenarios:**</span></span>
 
<span data-ttu-id="920b8-222">**案例1：**</span><span class="sxs-lookup"><span data-stu-id="920b8-222">**Scenario 1:**</span></span> 

<span data-ttu-id="920b8-223">憑證更新已開始，且正在審查中。</span><span class="sxs-lookup"><span data-stu-id="920b8-223">Certification renewal has started and is under review.</span></span>

![在審查時進行認證更新](../media/UserGuidePhotos/33.png)

<span data-ttu-id="920b8-225">**案例1A：**</span><span class="sxs-lookup"><span data-stu-id="920b8-225">**Scenario 1A:**</span></span>


<span data-ttu-id="920b8-226">憑證更新拒絕：在下列情況中，可能會拒絕認證：</span><span class="sxs-lookup"><span data-stu-id="920b8-226">Certification renewal rejection: Certification may be rejected if:</span></span> 
- <span data-ttu-id="920b8-227">應用程式不具備必要的工具、程式或設定，也無法在認證視窗中執行所需的變更。</span><span class="sxs-lookup"><span data-stu-id="920b8-227">The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> 
- <span data-ttu-id="920b8-228">應用程式有未完成的漏洞，無法在認證視窗內修正。</span><span class="sxs-lookup"><span data-stu-id="920b8-228">The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 
 
![憑證拒絕](../media/UserGuidePhotos/34.png)
    
<span data-ttu-id="920b8-230">**案例1B：**</span><span class="sxs-lookup"><span data-stu-id="920b8-230">**Scenario 1B:**</span></span> 

<span data-ttu-id="920b8-231">認證更新已獲批准</span><span class="sxs-lookup"><span data-stu-id="920b8-231">Certification renewal is approved</span></span>  

![認證更新已核准](../media/UserGuidePhotos/35.png)


<span data-ttu-id="920b8-233">**認證到期：**</span><span class="sxs-lookup"><span data-stu-id="920b8-233">**Certification Expiration:**</span></span>
 
<span data-ttu-id="920b8-234">應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 [證書] 頁面。及時更新也會確保 AppSource 和小組存放區中的應用程式持續聲譽徽章授予及圖示。</span><span class="sxs-lookup"><span data-stu-id="920b8-234">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>


<span data-ttu-id="920b8-235">應用程式的資訊必須在到期日之前更新，以維護 Microsoft 檔上應用程式的 [證書] 頁面。及時更新也會確保 AppSource 中的應用程式持續聲譽徽章授予和圖示、Teams 儲存區、Office 存放區及其他書店。</span><span class="sxs-lookup"><span data-stu-id="920b8-235">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource, Teams Store, Office Store and other storefronts.</span></span> 

![認證更新到期](../media/UserGuidePhotos/36.png)
    
<span data-ttu-id="920b8-237">**附注**：只要按一下「更新」，即可隨時啟動 Publisher 證明和認證程式。</span><span class="sxs-lookup"><span data-stu-id="920b8-237">**Note**: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 

