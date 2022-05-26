---
title: Si-Net的 KURO 入口網站應用程式資訊
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/23/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: KURO 入口網站的所有可用安全性與合規性資訊、其資料處理原則、其Microsoft Cloud App Security應用程式目錄資訊，以及 CSA STAR 登錄中的安全性/合規性資訊。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 76bac84d40bcc0b9a3e73b2dd691b6020c353cc5
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/26/2022
ms.locfileid: "65692353"
---
# <a name="kuro-portal"></a>KURO 入口網站

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>上次由開發人員更新日期：2022 年 5 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/c4af7af6-4fa4-4777-bab7-713cda6d0f74" target="_blank">在Teams存放區中檢視</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004019" target="_blank">在 AppSource 中檢視</a>

::: zone pivot="general"

### <a name="general-information"></a>一般資訊

Si-Net提供給 Microsoft 的資訊：

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式名稱 | KURO 入口網站 |
| ID | WA200004019 |
| 支援Office 365用戶端 | Microsoft Teams |
| 合作夥伴公司名稱 | Si-Net |
| 公司的網站 | [https://www.si-net.it](https://www.si-net.it) |
| 應用程式的使用規定 | [https://www.si-net.it/termini-di-utilizzo-kuro/](https://www.si-net.it/termini-di-utilizzo-kuro/) |
| 應用程式的核心功能 | 適用于 Teams 的 KURO 入口網站應用程式承諾為輕量 CRM，讓人員可以一目了然地取得所有必要的客戶資訊、用來作為電話簿，直接透過自己的電話操作員從小組撥打電話、直接傳送電子郵件給連絡人中的人員、直接聊天，以及建立與 Kuro 入口網站來賓客戶的會議。 以簡單快速的方式搜尋客戶資訊，直接存取選取的客戶&#8217;檔集合和共用檔管理  |
| 公司總部位置 | 義大利 |
| 應用程式資訊頁面 | |
| 用來執行應用程式的裝載環境或服務模型為何？ | Paas |
| 應用程式會使用哪些主控雲端提供者？ | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>應用程式如何處理資料

這項資訊是由Si-Net提供，說明此應用程式如何收集和儲存組織資料，以及貴組織對於應用程式所收集資料的控制。

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式或基礎結構是否會處理任何與 Microsoft 客戶或其裝置相關的資料？ | 是 |
| 您的應用程式會處理哪些資料？ | 客戶租使用者和裝置 |
| 應用程式是否支援 TLS 1.1 或更新版本？ | 是 |
| 應用程式或基礎結構是否會儲存任何 Microsoft 客戶資料？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

Microsoft Cloud App Security[目錄中](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)的資訊如下所示。

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否在應用程式上執行年度滲透測試？ | 否 |
| 應用程式是否有記載的災害復原計畫，包括備份和還原策略？ | 否 |
| 您的環境是否使用傳統的反惡意程式碼保護或應用程式控制？ | TraditionalAntiMalware、ApplicationControls |
| 您是否有針對縮排和風險排名安全性弱點所建立的程式？ | 是 |
| 您是否有原則可控管您的服務等級協定 (套用修補程式的 SLA) ？ | 是 |
| 您是否根據修補原則 SLA 執行修補管理活動？ | 是 |
| 您的環境是否有任何不支援的作業系統或軟體？ | 否 |
| 您是否每季對您的應用程式和支援它的結構進行弱點掃描？ | 是 |
| 您的外部網路界限上是否已安裝防火牆？ | 是 |
| 您是否已建立變更管理程式，用來在變更要求部署至生產環境之前，先加以檢閱和核准？ | 是 |
| 是否有其他人員檢閱和核准原始開發人員提交至生產環境的所有程式碼變更要求？ | 是 |
| 安全的程式碼撰寫做法是否將常見弱點類別納入考慮，例如 OWASP 前 10 名？ | 是 |
| 已針對下列專案啟用多重要素驗證 (MFA) ： | CodeRepositories、DNSManagement、Credential |
| 您是否已建立員工帳戶的布建、修改和刪除程式？ | 是 |
| 您是否已在支援應用程式的網路界限周邊部署入侵偵測和預防 (IDPS) 軟體？ | 是 |
| 您是否已在支援應用程式的所有系統元件上設定事件記錄？ | 是 |
| 所有記錄都是透過人類或自動化工具定期檢閱，以偵測潛在的安全性事件嗎？ | 是 |
| 偵測到安全性事件時，警示會自動傳送給員工進行分級？ | 是 |
| 您是否已建立正式的資訊安全性風險管理程式？ | 是 |
| 您是否已記錄並建立正式的安全性事件回應程式？ | 是 |
| 您是否在偵測到 72 小時內向監督機關和個人回報應用程式或服務資料外泄？ | 是 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **回應** |
|:----------------|:-------------|
| 應用程式是否符合 HIPAA)  (健康保險可攜性和會計法？ | 否 |
| 應用程式是否符合健康情況資訊信任聯盟、Common Security Framework (HITRUST CSF) ？ | 否 |
| 應用程式是否符合服務組織控制 (SOC 1) ？ | 否 |
| 應用程式是否符合服務組織控制 (SOC 2) ？ | 否 |
| 應用程式是否符合服務組織控制 (SOC 3) ？ | 否 |
| 您是否針對應用程式及其支援環境執行年度 PCI DSS 評量？ | 否 |
| 應用程式國際標準組織 (ISO 27001) 認證嗎？ | 否 |
| 應用程式是否符合國際標準組織 (ISO 27018) ？ | 否 |
| 應用程式是否符合國際標準組織 (ISO 27017) ？ | 否 |
| 應用程式是否符合國際標準組織 (ISO 27002) ？ | 否 |
|  (FedRAMP) 相容的應用程式是否符合美國聯邦風險和授權管理計畫？ | 否 |
| 應用程式是否符合 FERPA)  (家庭教育權利和隱私權法案？ | 否 |
| 應用程式是否符合兒童線上隱私保護法 (COPPA) ？ | 否 |
| 應用程式是否符合 Sarbanes-Oxley Act (SOX) ？ | 否 |
| 應用程式是否符合 NIST 800-171？ | 否 |
| 應用程式是否已通過雲端安全性聯盟 (CSA Star) 認證？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **回應** |
|:----------------|:-------------|
| 您是否有 GDPR 或其他隱私權或資料保護需求或義務 (，例如 CCPA) ？ | 是 |
| 應用程式是否有外部隱私權注意事項，說明其如何收集、使用、共用及儲存客戶資料？ | 是 |
| 隱私權原則 URL | https://www.si-net.it/termini-di-utilizzo-kuro/ |
| 應用程式是否會執行自動化決策，包括可能會有法律效果或類似影響的分析？ | 否 |
| 應用程式是否針對隱私權通知中未說明的次要用途處理客戶資料， (也就是行銷、分析) ？ | 否 |
| 您是否處理特殊類別的敏感性資料 (例如種族或種族來源、政治意見、種族或種族情緒、基因或生物特徵辨識資料、健康資料) 或資料類別，但可能會違反通知法？ | 否 |
| 應用程式是否會收集或處理未成年人的資料 (也就是 16 歲以下的個人) ？ | 否 |
| 應用程式是否有在要求時刪除個人個人資料的功能？ | 否 |
| 應用程式是否有限制或限制個人個人資料在要求時處理的功能？ | 否 |
| 應用程式是否提供個人更正或更新其個人資料的能力？ | 否 |
| 是否 (執行一般資料安全性和隱私權檢閱，例如資料保護影響評估或隱私權風險評估) ，以識別與處理應用程式個人資料相關的風險？ | 否 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **回應** |
|:----------------|:-------------|
| 您的應用程式是否與 Microsoft 身分識別平臺整合 (Azure AD) 以進行單一登入、API 存取等等？ | 是 |
| 您是否已檢閱並符合Microsoft 身分識別平臺整合檢查清單中所述的所有適用最佳做法？ | 否 |
| 您的應用程式是否使用最新版的 MSAL (Microsoft 驗證程式庫) 或 Microsoft Identity Web 進行驗證？ | 是 |
| 您的應用程式是否支援條件式存取原則？ | 否 |
| 您的應用程式是否支援持續存取評估 (CAE)  | 否 |
| 您的應用程式是否在程式碼中儲存任何認證？ | 否 |
| 適用于 Microsoft 365 的應用程式和增益集可能會使用 Microsoft Graph 以外的其他 Microsoft API。 您的應用程式或增益集是否使用其他 Microsoft API？ | 否 |

>此應用程式不會使用 Microsoft Graph。

>此應用程式沒有其他 API。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

