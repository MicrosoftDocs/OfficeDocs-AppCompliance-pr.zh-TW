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
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program"></a>Microsoft 365 應用程式規範計畫的合作夥伴使用者指南

|||
|---|---|
|第1層| 發行者證明|
|第2層| Microsoft 365 認證|

## <a name="1-overview"></a>1. 簡介
這份檔是為我們的合作夥伴做為逐步使用者指南，註冊 Microsoft 365 應用程式相容性計畫，其意圖是透過發行者證明和憑證，不過是合作夥伴中心入口網站。

## <a name="2-acronyms--definitions"></a>2. 縮寫 & 定義
| | |
|---|----|
|縮略字 | 定義 |
|電腦 (合作夥伴中心) |所有 Microsoft 合作夥伴的入口網站。 合作夥伴會登入至夥伴中心，並提交 Self-Assessment 問卷 https://partner.microsoft.com/|
|ISV|獨立軟體廠商 A.k.a。 Partner or Developer|
|應用程式來源|  (的應用程式目錄 https://appsource.microsoft.com/)
||範例：現在，虛擬代理程式 (https://appsource.microsoft.com/en-us/product/office/WA104381816)|

## <a name="3---publisher-attestation-workflow"></a>3. 發行者證明工作流程

首頁：這是一次夥伴登入夥伴中心的登陸頁面。

![合作夥伴中心主畫面](../media/Picture1.png)

**步驟 1**   ：在頁面左側的導覽列中：
1. 選取 Office 存放區
1. 選取一覽

![您可以在左側導覽找到 Office 存放區](../media/Picture2.png)

選取「一覽」時，partner 可以查看透過夥伴中心提交且適用于 Microsoft 365 規範計畫的應用程式清單。

**步驟 2** ：從清單中選取應用程式，以開始發行者證明程式。

![選擇您要證明哪個應用程式](../media/Picture3.png)

選取應用程式時，會彈出另一個導覽列，其中包含選項「應用程式相容性」

**步驟 3**：選取「應用程式符合性」

![選取應用程式規範](../media/App%20compliance%20step%203.png)

**步驟 4**：填寫發行者證明的 Self-Assessment 問卷

![匯入/匯出](../media/step4-new%20add.PNG)

![匯入/匯出](../media/NewFeature%20impExp.PNG)

**附注**：如果您要回到更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [複製]。

![複製 ](../media/clone.PNG)
 ![ Clone2](../media/clone2.PNG)

您也可以利用 [匯入/匯出] 功能，離線完成該表單，並在完成後將其匯入。 

**步驟 5**：完成後，按一下 [提交]，評估現在會是「審閱」。

![按一下 Sumbit](../media/Picture8.png)

![審閱現在正在進行中](../media/Picture9.png)

### <a name="approvereject-scenarios"></a>核准/拒絕案例：

**發行者證明拒絕**

在此階段遭到拒絕時，合作夥伴可以：
-   View 失敗報告。
    - 合作夥伴將會透過電子郵件通知合作夥伴中心。
-   更新 Self-Assessment 的回應。
-   重新提交自我評估。

![更新並重新提交評估](../media/Picture10.png)

**B. 發行者證明重新提交**

![在審閱下重新提交](../media/PA%20resubmission.png)

**C. 發行者證明核准**

-   在核准合作夥伴可以執行下列作業：
    - 更新並重新提交證明
    - 查看和共用已完成的 Publisher 證明
    - 開始 M365 認證處理常式

![更新並重新提交](../media/AttestApproval.PNG)

![查看已完成的證明 ](../media/PA%20approval%202.png)

![開始 M365 應用程式認證](../media/PA%20approval%203.png)

**發佈發行者驗證核准： publisher attested 應用程式的 AppSource 連結範例**

![完成證明的範例](../media/Example%20to%20attested%20apps.png)

## <a name="4-microsoft-365-certification-workflow"></a>4. Microsoft 365 認證工作流程

協力廠商按一下「提交」並提交所有檔和證據進行審閱之後： 

### <a name="microsoft-365-certification---submitted"></a>Microsoft 365 認證-已提交

![已開始認證](../media/certification%201.png)

**Microsoft 365 認證-已拒絕**

![拒絕的憑證](../media/certification%20rejected.png)

**Microsoft 365 認證-已核准**

![已核准認證](../media/certification%20approved.png)

**後憑證核准： AppSource 中的 Microsoft 365 認證徽章範例**

![認證標記範例](../media/post%20certification%20badge.png)

## <a name="5-workflow-for-existing-isvs"></a>5. 現有 Isv 的工作流程

如果您是現有的 ISV，且想要更新發行者證明。

**步驟 1**：按一下「更新並重新提交發行者證明」連結。

![更新發行者證明 ](../media/existing%20isv%201.png)

**附注：**：如果您要回到更新/重新提交應用程式，請按一下 [選擇產品的下拉式清單]，選取應用程式，然後按一下 [匯入]。

![針對不同整合的匯入證明](../media/M365%20App%20compliance.png)

![按一下 [匯入](../media/M365%20App%20compliance1.png)

**步驟 2**：對表單進行更新，然後按一下 [儲存/提交]。

![按一下 [儲存] 或 [提交]](../media/existing%20isv%202.png)

送出後，即會進行考核。

![審查中的證明](../media/existing%20isv%203.png)

## <a name="6---microsoft-365-re-certification-workflow"></a>6. Microsoft 365 Re-Certification 工作流程：

當應用程式即將達到1年的憑證周年時，會定期提醒您更新認證。

![UG Recreation1](../media/UG%20Recreation%201.png)

![UG Recreation2](../media/UG%20Recreation%202.png)

**已完成發行者證明。認證 InProgress。**

![UG Recreation3](../media/UG%20Recreation%203.PNG)

核准/拒絕 Secnario：已拒絕證書

![UG Recreation4](../media/UG%20Recreation%204.PNG)

B。 已核准認證

![UG Recreation5](../media/UG%20Recreation%205.PNG)

到期案例：發行者證明已過期

![UG Recreation6](../media/UG%20Recreation%206.PNG)

B。 憑證已過期

![UG Recreation7](../media/UG%20Recreation%207.PNG)

