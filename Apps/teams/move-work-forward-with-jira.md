---
title: 使用 Jira 向前移動工作所需的應用程式資訊。
ms.author: elmalova
author: elenamalova
ms.date: 01/21/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: 所有可用的安全性和符合性資訊，可在 Jira 中向前移動工作、其資料處理原則、其 Microsoft Cloud App Security 應用程式目錄資訊，以及 CSA 星型登錄中的安全性/符合性資訊。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 218c70925805938ff5f241e9df42b667eba81353
ms.sourcegitcommit: 193632a2964d85cb90e9fcd62da021c5dcb0bd9b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/24/2022
ms.locfileid: "62176956"
---
# <a name="move-work-forward-with-jira"></a>使用 Jira 推展工作進度

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開發人員上次更新日期：2022年1月21日</p>

* <a href="https://teams.microsoft.com/l/app/79ca2e8f-dd2c-40d5-897e-1b22d41038fe" target="_blank">在 Teams 儲存區中查看</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002855" target="_blank">在 AppSource 中查看</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

將工作轉寄給 Microsoft 所提供的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | 使用 Jira 推展工作進度 |
| ID | WA200002855 |
| 支援 Office 365 用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | 推展工作進度 |
| 公司的網站 | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| App 的使用條款 | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |
| 應用程式的核心功能 | 移動工作向前可協助公司提供一套整合 Atlassian 工具與 Microsoft Teams、GitHub、Azure DevOps 和其他小組生產力工具的產品，以提升生產力、小組透明性和節省時間。 |
| 公司 headquarter 位置 | 新加坡 |
| 應用程式資訊頁面 | |
| 用來執行應用程式的主控環境或服務模型為何？ | Iaas |
| 應用程式會使用哪一個主控雲端提供者？ | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

此資訊的移動方式是向前移動，以瞭解此應用程式如何收集和儲存組織資料，以及您的組織將對該應用程式所收集的資料所進行的控制。

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式或基礎結構是否可以處理與 Microsoft 客戶或其裝置相關的任何資料？ | 是 |
| 您的應用程式所處理的資料為何？ | DocsPublishingCommon。 AppInfos 的 DataProcess |
| App 是否支援 TLS 1.1 或更新版本？ | 是 |
| 應用程式或基礎結構是否會儲存任何 Microsoft 客戶資料？ | 是 |
| 資料庫中儲存的資料為何？ | 傳送通知的 Teams 和通道。 |
| 如果基礎 infastructure 處理或儲存 Microsoft 客戶資料，該資料地理位置存放在何處？ | 美國地區 |
| 您是否有既定的資料 rentention 與處置程式？ | 否 |
| 在帳戶終止後，資料會保留多久？ | 小於30days |
| 您是否有既定的資料存取管理程式？ | 是 |
| 您是否要將客戶資料或客戶內容轉移至協力廠商或子處理者？ | 否 |
| 您與與您共用 Microsoft 客戶資料的協力廠商服務是否有相同的資料共用協定？ |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

來自[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)目錄的資訊如下所示。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否要在應用程式中執行年度滲透測試？ | 是 |
| 應用程式是否有記錄的嚴重損壞修復計畫，包括備份與還原策略？ | 是 |
| 您的環境使用傳統的反惡意程式碼保護或應用程式控制嗎？ | TraditionalAntiMalware, ApplicationControls |
| 您是否已針對 indentifying 及風險排名安全性弱點建立處理常式？ | 是 |
| 您是否有原則可以控制您用來套用修補程式的服務等級協定 (SLA) ？ | 是 |
| 您是否根據修補原則 Sla 來執行修補程式管理活動？ | 是 |
| 您的環境是否有不受支援的作業系統或軟體？ | 否 |
| 您是否在您的應用程式和支援 infastructure 的應用程式上進行季度弱點掃描？ | 否 |
| 您的外部網路界限是否已安裝防火牆？ | 否 |
| 您是否有已建立的變更管理程式，用來在將變更要求部署至生產環境之前，加以檢查和核准？ | 是 |
| 是否有其他人員檢查及核准原始開發人員送出給生產的所有程式碼變更要求？ | 是 |
| 安全的編碼做法會考慮常見的弱點類別，例如 OWASP Top 10？ | 是 |
| 啟用下列各要素驗證 (MFA) ： | CodeRepositories、DNSManagement、身分憑證 |
| 您是否已確定要提供、修改和刪除員工帳戶的程式？ | 是 |
| 您是否有入侵偵測及防護 (IDPS) 軟體部署在支援您應用程式的網路邊界周邊？ | 是 |
| 您是否已在所有支援應用程式的系統元件上設定事件記錄？ | 否 |
| 所有記錄檔中的所有記錄是否都透過人工或自動工具檢查，以偵測可能的安全性事件？ | |
| 偵測到安全性事件時，會自動將預警傳送給員工以進行會審？ | 否 |
| 您是否已建立正式的資訊安全性風險管理程式？ | 否 |
| 您是否已記錄並建立正式的安全性事件回應程式？ |  |
| 您是否要將應用程式或服務資料違例報告給主管機關和個人在偵測到72小時內受破壞的人員？| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式是否符合健康保險業便攜性和會計法案 (HIPAA) ？ | 否 |
| 應用程式是否符合健康資訊信任同盟，常見的安全性框架 (HITRUST CSF) ？ | 否 |
| 應用程式是否符合服務組織控制 (SOC 1) ？ | 否 |
| 最近的 SOC1 認證日期 |   |
| 應用程式是否符合服務組織控制 (SOC 2) ？ | 否 |
| 您已完成哪一種 SOC 2 憑證？ | |
| 最近的 SOC2 認證日期 | |
| 應用程式是否符合服務組織控制 (SOC 3) ？ | 否 |
| 最近的 SOC3 認證日期 | |
| 您是否要針對 appand 其支援的環境，進行每年 PCI DSS 評估？ | 否 |
| 應用程式的國際標準組織 (ISO 27001) 驗證？ | 否 |
| 應用程式是否符合國際標準組織 (ISO 27018) ？ | 否 |
| 應用程式是否符合國際標準組織 (ISO 27017) ？ | 否 |
| 應用程式是否符合國際標準組織 (ISO 27002) ？ | 否 |
| 應用程式的聯邦風險和授權管理計畫是否 (FedRAMP) 相容？ | 否 |
| 應用程式是否符合家庭教育權利和隱私權法案 (FERPA) ？ | 不適用 |
| 應用程式是否符合孩子的線上隱私權保護法案 (COPPA) ？ | 不適用 |
| 應用程式是否符合 Sarbanes-Oxley 法案 (SOX) ？ | 不適用 |
| 應用程式是否符合 NIST 800-171？ | 不適用 |
| App 是否已 (CSA 星) 認證？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否有 GDPR 或其他隱私權或資料保護需求或義務 (例如 CCPA) ？ | 是 |
| 此應用程式是否有對外的隱私權通知，描述其收集、使用、共用及儲存客戶資料的方式？ | 是 |
| 隱私權原則 URL | https://www.moveworkforward.com/privacy-policy |
| 應用程式是否會執行自動決策，包括可能具有法律效果或類似影響的分析？ | 否 |
| 此應用程式是否會在隱私權通知 (（例如行銷，分析) ？）中處理次要用途的客戶資料。 | 否 |
| 您是否處理特殊類別的機密資料 (例如種族或種族、政治觀點、宗教或哲學 beliefs、遺傳或生物統計學資料、健康資料) 或受侵犯通知法律之資料的類別）？ | 否 |
| 應用程式會收集或處理來自未成年人的 (，亦即，在 16) 年齡的個人。 | 否 |
| 應用程式是否有功能可在要求時刪除個人資料？ | 是 |
| 應用程式是否具有限制或限制在要求時處理個人資料的功能？ | 否 |
| App 是否提供個人資料，以更正或更新其個人資料？ | 否 |
| 常規資料安全性和隱私權評論執行 (例如，資料保護影響評估或隱私權風險評估) 識別與處理應用程式個人資料相關的風險？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **回應** |
|:----------------|:-------------|
| 您的應用程式與 Microsoft Identity Platform (Azure AD) 是否整合，以進行單一登入、API 存取等等）？ | 是 |
| 您是否已複習並編譯 Microsoft 身分識別平臺整合檢查清單中所述的所有適用的最佳作法？ | 是 |
| 您的應用程式是否使用最新版的 MSAL (Microsoft 驗證程式庫) 或 Microsoft Identity Web 進行驗證？ | 是 |
| 如果您的應用程式不使用上述其中一個文件庫，它會使用哪個驗證程式庫或文件庫？ |  |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否支援持續存取評估 (CAE)  | 否 |
| 您的應用程式是否會在程式碼中儲存任何認證？ | 否 |
| Microsoft 365 的應用程式和增益集可能會使用 microsoft Graph 以外的其他 microsoft APIs。 您的應用程式或增益集會使用其他 Microsoft APIs 嗎？ | 否 |

#### <a name="data-access-using-microsoft-graph"></a>使用 Microsoft Graph 的資料存取

>|   **Graph 許可權**  | **權限類型** |          **對齊**          |
>|:------------------------|:--------------------|:------------------------------------|
>| 通道。建立 | 委託 | 建立 Jira 問題的討論管道 |
>| ReadBasic | 委託 | 要將通知傳送給的小組讀取通道 |
>| 電子郵件 | 委託 | 對應 Microsoft 和 Atlassian 帳戶 |
>| Team.ReadBasic.All | 委託 | 可讀取 [設定] 頁面上顯示的小組。 Jira 的通知。 |
>| TeamsAppInstallation.ReadForTeam | 委託 | 檢查是否已在團隊中安裝應用程式。 |
>| User.Read | 委託 | 以加強使用者體驗。 |

>此應用程式沒有額外的 APIs。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

