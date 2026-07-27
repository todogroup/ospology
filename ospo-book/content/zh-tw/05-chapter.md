---
title: "第 5 章：管理開放原始碼安全"
status: Completed
weight: 70
---

- [前言](#前言)
- [訓練與教育](#訓練與教育)
- [關鍵步驟](#關鍵步驟)
- [應用在自己的組織](#應用在自己的組織)
- [資源與註腳](#資源與註腳)

## 前言

> 注意：本章內容由 Open Source Security Foundation（OpenSSF）專家協助撰寫，並獲得 TODO Group 支援。

開放原始碼軟體已經是軟體供應鏈不可或缺的一部分，因此，協助強化開放原始碼供應鏈安全，也是 OSPO 的重要職責之一，例如：

- 協助開發團隊評估所使用開放原始碼軟體的安全性。
- 鼓勵開發團隊回饋上游，協助改善專案安全。
- 在組織維護、貢獻或主導的開放原始碼專案中，落實安全開發最佳實務。

本章會整理一系列資源，協助 OSPO 與開發者把安全開發與供應鏈最佳實務，實際套用到「自己使用的軟體」與「自己開發的軟體」上。

在某些方面，安全就像其他需求一樣；然而，許多軟體開發者及其管理者未受過足夠的安全訓練。此外，安全的核心是防禦會刻意尋找弱點的攻擊者，而且往往取決於整個系統如何協同運作，而非單一元件。

事後補洞通常代價高昂，比較好的做法，是在設計與開發階段就盡可能減少風險、降低影響，並為未來可能發生的事件預先做準備。這表示在一開始就要預留時間與預算來處理安全議題。開放原始碼在這方面常被認為有優勢，因為它符合「開放設計（open design）」與「多人檢視」的精神，但這些優勢並不會自動發生，需要有對的流程與文化。

## 訓練與教育

許多開發者與管理者其實不知道自己在安全上「應該知道什麼」，知識落差很容易變成實際風險。本節整理幾個關鍵角色與學習重點，並附上免費的 OpenSSF 線上課程做為參考。
不一定要採用這些特定課程，但重要的是：所有參與軟體開發的角色，都要有足夠的安全基礎。

**管理者（包含開放原始碼與封閉原始碼專案）**
應該理解如何管理安全軟體開發，包括：基礎安全術語、風險管理、在設計階段就納入安全考量、保護各種環境（開發、測試、部署）、及早辨識風險，以及如何對利害關係人設定正確預期。同時也要知道開發者需要學什麼、需要哪些支援。
若尚未受過這類訓練，可參考 OpenSSF 免費課程 *Security for Software Development Managers（LFD125）* [^1]。

**開發者**
建議接受一套系統性的「安全軟體開發」課程，涵蓋從規劃、設計、實作、測試到發布各階段如何納入安全考量，也包含如何評估第三方軟體。開發者應理解常見弱點（例如 Web 應用程式的 OWASP Top Ten [^2]、一般軟體的 CWE Top 25 [^3]），以及如何避免，並知道如何保護開發環境、如何回應弱點通報等。
若尚未受訓，可參考 OpenSSF 的 Developing Secure Software（LFD121）課程 [^4]。

**開發者與管理者共同需要理解的法規**
凡是參與開發可能在歐盟（EU）市場提供之軟體的人員，都應了解《EU Cyber Resilience Act（CRA）》。相關人員應理解 CRA 的適用範圍、其定義的不同角色（例如製造商（manufacturer）、開放原始碼軟體受託管理者（open source software steward））與各角色所負擔的責任，以及違規可能帶來的後果。由於 CRA 涵蓋面廣且罰則嚴格，建議相關人員可參考 OpenSSF 的免費課程 *Understanding the European Union (EU) Cyber Resilience Act (CRA)（LFEL1001）* [^5]。

## 關鍵步驟

### 自行開發軟體時

1. 閱讀 OpenSSF 的 **Concise Guide for Developing More Secure Software**，裡面整理了實務資源與指引 [^6]。
2. 盡量達到 OpenSSF Baseline 所列出的基本安全檢查內容 [^7]。
3. 為專案申請 OpenSSF Best Practices 標章，先從「passing」開始，之後逐步朝「silver」與「gold」邁進 [^8]。
4. 檢視並提升自己專案在 OpenSSF Scorecard 上的分數，這套工具不只可以評估別人的專案，也可以拿來看自己 [^9]。

### 重新使用他人軟體與相依元件時

1. 參考 **Concise Guide for Evaluating Open Source Software** [^10]，以結構化方式評估專案。
2. 留意類似名稱（typosquatting）攻擊，仔細核對套件名稱與來源。
3. 使用 OpenSSF Scorecard 評估準備採用的專案 [^9]。

### 保護各種環境（開發、建置、測試與散布）

1. 對重要系統啟用多因素認證（MFA），降低憑證被盜用的風險。
2. 強化建置環境安全，可參考 OpenSSF SLSA 提供的實務指引 [^11]。

### 在 CI 管線中加入安全工具

1. 併用不同類型的工具，因為每種工具擅長偵測的問題不同；可參考 **Guide to Security Tools** [^12]。
2. 對於新專案（green field），可以預設開啟較多安全檢查；對於歷史較久的專案（brown field），可以先從最關鍵的檢查開始，避免一次產生過多噪音。
3. 啟用可偵測相依元件已知弱點的工具。

### 為弱點通報做好準備

不論專案大小，都可能收到弱點回報。建議：

- 在專案頁面清楚說明回報弱點的方式。
- 參考 OpenSSF 的 **Guide to implementing a coordinated vulnerability disclosure process** [^13]，建立協調揭露流程。

## 應用在自己的組織

要提升組織中開放原始碼軟體的安全性，絕不是只靠「多裝幾個工具」就能解決，還牽涉到文化與日常工作流程。

首先，要建立「安全是大家的責任」這種心態，而不是只丟給少數資安團隊。領導者應明確表達安全開發的重要性，並願意投入時間與預算，對參與安全工作的團隊與個人給予適當認可。

其次，要把安全實務內嵌在日常開發流程中，而不是額外加在最後一關。例如，讓 Scorecard 與弱點掃描成為 CI/CD 的一部分，而不是偶爾才跑一次。這樣，安全就會變成開發過程中的「常態」，而不是「例外」。

第三，訓練應該是持續性的，而不是一次性的活動。建議為開發者與管理者規畫固定節奏的安全課程與交流活動，並鼓勵大家利用 OpenSSF 等免費資源進修。當學習被視為職涯的一部分，而不是額外負擔時，安全文化才有機會長期穩定。

第四，鼓勵團隊公開分享安全相關的進展與成果，例如：獲得 Best Practices 標章、Scorecard 分數提升、引進新工具的經驗等。這有助於建立正向循環，讓團隊之間互相學習，而不是只在發生事件時才談安全。

最後，要留下「持續改進」的空間。安全議題永遠不會結束，因此需要定期檢視風險、更新工具與流程，並分享實際案例與教訓。只要越早讓團隊在設計與規畫階段就能做出安全相關決策，就越不需要在專案尾聲或事故發生後，用高昂成本補救。

透過共享責任、把安全融入日常、持續投資學習、鼓勵透明與合作，以及不斷改進，組織就能在自行開發與使用的開放原始碼軟體上，逐步建立更穩固的安全基礎。

## 資源與註腳

### 資源

- OpenSSF: https://openssf.org/
- OWASP: https://owasp.org/
- CWE: https://cwe.mitre.org/index.html

### 註腳

[^1]: Security for Software Development Managers（LFD125）：<https://training.linuxfoundation.org/training/security-for-software-development-managers-lfd125/>
[^2]: OWASP Top Ten（Web 應用程式）：<https://owasp.org/www-project-top-ten/>
[^3]: CWE Top 25（一般軟體）：<https://cwe.mitre.org/top25/>
[^4]: Developing Secure Software（LFD121）：<https://training.linuxfoundation.org/training/developing-secure-software-lfd121/>
[^5]: Understanding the EU Cyber Resilience Act（CRA）：<https://training.linuxfoundation.org/express-learning/understanding-the-eu-cyber-resilience-act-cra-lfel1001/>
[^6]: Concise Guide for Developing More Secure Software：<https://best.openssf.org/Concise-Guide-for-Developing-More-Secure-Software>
[^7]: OpenSSF Baseline：<https://baseline.openssf.org/>
[^8]: OpenSSF Best Practices 標章：<https://www.bestpractices.dev/>
[^9]: OpenSSF Scorecard：<https://github.com/ossf/scorecard>
[^10]: Concise Guide for Evaluating Open Source Software：<https://best.openssf.org/Concise-Guide-for-Evaluating-Open-Source-Software>
[^11]: OpenSSF SLSA：<https://slsa.dev/>
[^12]: Guide to Security Tools：<https://github.com/ossf/wg-security-tooling/blob/main/guide.md#readme>
[^13]: Guide to implementing a coordinated vulnerability disclosure process：<https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md#readme>
