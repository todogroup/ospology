---
title: "第 3 章：打造自己的 Open Source Program Office"
status: Completed
weight: 50
---

- [前言](#前言)
- [從策略開始](#從策略開始)
- [設計你的 OSPO](#設計你的-ospo)
- [善用成熟度模型](#善用成熟度模型)
- [應用在自己的組織](#應用在自己的組織)
- [可能發生的問題與因應方式](#可能發生的問題與因應方式)
- [資源與註腳](#資源與註腳)

## 前言

OSPO 在不同組織中的樣貌差異很大，因此花時間設計一個「真的能回應組織目標」的 OSPO，遠比複製別人的組織圖重要。

本章會先協助釐清策略，讓 OSPO 有一個可以對齊的方向；接著談如何設計一個穩定而有韌性的 OSPO，足以承接組織在開放原始碼上的各種責任；最後再介紹「成熟度模型」，幫助判斷目前 OSPO 所在的位置，以及未來可能的發展路徑。

## 從策略開始

### 如何制定策略

> 對 OSPO 成員來說，要把開放原始碼策略有效傳達給公司高層，就必須理解產業情勢，並對齊 CEO 與 CFO 關注的重點。這代表要先搞清楚整體企業策略，再找出哪些開放原始碼技術，能具體推動組織朝這些目標前進。
>
> Victor Lu 與 Rob Moffat，Strategy - End Game for FINOS Maturity Model [^1]

OSPO 可以透過建立並維護一套涵蓋策略、治理、合規及社群參與的框架來達成。其策略著重於讓組織使用及貢獻開放原始碼的方式，以及相關合規活動，與組織在各項專案、產品、服務及內部基礎設施上的整體目標保持一致。

一份好的策略文件，可以讓大家對一些具體主題有「共識」，而不是散落在各自心中的想像。

制定策略時，可以先思考：

1. **寫成策略文件：** 建議撰寫一份開放原始碼策略文件 [^2]，逐步記錄思考過程與決策。有現成指南可依循，能幫助各方對齊。
2. **理解組織目標：** 如同前一章所述，要先清楚組織的整體目標，以及目前與開放原始碼的實際互動情形。
3. **看清脈絡：** 在考量人員、技術及預算之前，可以先從不同角度規劃 OSPO 的架構，以及它在組織圖中的位置。TODO Group 出版的 *A deep dive into OSPOs* [^3] 可作為規劃參考，其中完整說明 OSPO 架構與營運所需資訊。
4. **參考具體範例：** 想快速了解 OSPO 可能涵蓋的活動，可以參考 OSPO Mind Map [^4]，其中整理了 OSPO 在生態系中的主要職責、角色、行為與團隊規模。

## 設計你的 OSPO

### 明確界定 OSPO 要管理什麼

要讓 OSPO 發揮效果，前提是先理解組織怎麼運作。當你理解公司的目標，就更容易判斷開放原始碼在其中扮演的角色。

以商業組織為例，OSPO 可以從下列面向思考開放原始碼如何串接到既有架構裡：

![組織架構](/images/organization-architecture_zh-tw.png)

每間公司在價值、驅動因素與文化上都不同，很難用一套範本涵蓋全部情況。不過，可以先問自己與利害關係人幾個問題：

* 哪些開放原始碼技術，現在或未來會是產品與策略的關鍵？
* 哪些上游專案會直接或間接影響這些技術與組織目標？
* 要讓整個開放原始碼生態健康運作，需要哪些具體作法？
* 組織既有流程有哪些痛點？開放原始碼可以怎麼幫忙改善？
* 要如何讓員工成為開放原始碼的推動者與倡議者？
* 要怎麼把這些訊息清楚傳達給管理階層？

釐清 OSPO 能帶來價值的地方之後，也比較容易辨識真正的利害關係人。

### 辨識 OSPO 的利害關係人

OSPO 在組織裡通常會面對一群相對固定的利害關係人。所謂利害關係人，就是會受 OSPO 工作影響的人。

常見的角色可以用「OSPO 花朵圖」來表示，每一片花瓣代表一群利害關係人，以及與該群體相關的主要活動。這張圖也很適合用來整理與各群體之間的溝通管道與文件素材。

依照組織的複雜度與 OSPO 能動用的資源，這些花瓣可以再拆得更細，也可以新增其他花瓣。

![OSPO 工作領域](/images/ospo-flower_zh-tw.png)
[ospoflower.pdf](/pdfs/ospoflower-seconddraft-1.pdf)

舉例來說：

* **Individual Contributors（個別貢獻者）：**
  著重在組織裡實際寫程式或參與專案的人，關注他們貢獻開放原始碼的內在與外在動機，可能會包含導師制度等文化推廣活動。

* **Management（管理階層）：**
  聚焦在策略與如何讓開放原始碼與整體事業策略對齊。管理者面臨的挑戰與現場工程師不同，OSPO 可以協助他們看見開放原始碼能如何幫助達成目標。

* **Legal（法務）：**
  專注在開放原始碼相關的法律面向，包含授權條款與合規要求。OSPO 會與法務合作，確保相關政策與流程不會拖累開發，但也不會留下風險缺口。

* **Business（商務／產品）：**
  關注的是如何讓組織內不同部門之間的拼圖拼得起來，包含在各事業單位間分享最佳實務、促進協作與知識流動。

* **Open Source Ecosystem（開放原始碼生態系）：**
  代表組織外更廣大的社群與專案。OSPO 與其他組織、專案與個人互動，交換想法、共同解決問題，並回饋整體生態系。

* **OSPO（OSPO 本身）：**
  指的就是 OSPO 團隊內部的運作，包含如何協調所有開放原始碼相關活動、維持順暢運作，以及為其他利害關係人提供支援。

### 與外部監理與規範單位合作

外部監理單位沒有畫在花朵圖裡，因為性質較特別，但對許多 OSPO 來說非常重要。

組織會受到各類外部監理單位影響，這些單位會形塑組織的政策與流程，確保其符合法律要求、倫理標準與各產業的專業規範。常見單位包括：

* **政府機關：** 制定並執行會影響組織的法律與法規。
* **產業監理單位：** 許多產業都有自己的監理機構或專業協會，負責訂定組織應遵循的指引與標準。
* **消費者保護機構：** 確保組織為消費者提供公平且安全的產品或服務。

要讓開放原始碼在組織內成功且永續發展，除了與開源社群合作，也必須與外部監理單位合作。這樣能確保在制定影響生態系的政策時，各方都清楚理解開放原始碼的原則。合作的主要目標，是充分掌握開放原始碼及其社群可能受到的影響，並據此共同做出周全決策。因此，OSPO 應思考如何規劃與監理單位接觸及溝通，並明確界定各方在政策制定過程中的角色。

## 善用成熟度模型

### 成熟度模型簡介

組織對開放原始碼的投入，可以想像成從「只是戰術性、零星地使用」，一路到「成為策略核心」的一條光譜。成熟度模型的作用，就是幫助你判斷自己目前在光譜上的位置，以及是否需要往前推進。

市面上有各式各樣的開放原始碼成熟度模型，有些是廣泛適用，有些則專門針對政府、NGO 或企業等特定情境。

> 注意：成熟度模型有時看起來像一張「處方箋」，彷彿一定要達到最高階段才算成功。但在實務上，應該先問自己：對於目前的 OSPO 與各個功能來說，什麼樣的成熟度才是「剛好」？有些地方可能已經足以產生價值，硬要往上堆疊，反而會過度複雜。如果覺得成熟度模型不合用，也可以改用能力模型（Capability Model）或其他你覺得較適合的工具。

### 範例：幾種常見的成熟度模型

不同模型在細節上略有差異，但大致都是從「被動、零散」一路走到「主動、策略性」的光譜。

#### 模型一：Dr. Ibrahim H 的「開放原始碼採用模型」 [^5]

* 否認（Denial）：幾乎不使用開放原始碼，或是用了也沒有意識到。
* 使用（Consumption / Usage）：被動使用開放原始碼軟體。
* 參與（Participation）：開始與開放原始碼社群互動。
* 貢獻（Contribution）：有目的地對專案做出貢獻。
* 領導（Leadership）：從策略層面運用開放原始碼，為業務創造價值。

![開放原始碼參與模型](/images/opensourceinvolvementmodel_zh-tw.png)

#### 模型二：Carl-Eric 的「企業開放原始碼採用五階段」 [^6]

* 意外（Accidental）：組織在不自覺的情況下使用開放原始碼。
* 重複（Repetitive）：有基本流程支援使用與貢獻，但貢獻仍然零散。
* 引導（Directed）：主動參與關鍵開放原始碼專案。
* 協作（Collaborate）：把開放原始碼協作當成創造商業價值的工具。
* 主導（Prevail）：透過開放原始碼影響關鍵技術與商業策略。

![Carl-Eric 提出的企業開放原始碼採用五階段模型](/images/osmm-carl_zh-tw.png)

#### 模型三：TODO Group 的 OSPO 成熟度模型 [^7]

* 第 0 階段：零星採用開源軟體
* 第 1 階段：推動開放原始碼合規、軟體清冊與開發者教育
* 第 2 階段：推廣開放原始碼使用與生態系參與
* 第 3 階段：營運開源專案並培育社群
* 第 4 階段：成為策略決策夥伴

![OSPO 成熟度模型](/images/ospo-maturity-model_zh-tw.jpg)

## 應用在自己的組織

以下提供幾項運用前述概念與建議來設立 OSPO 的做法。這些建議以模型三，也就是 TODO Group 的 OSPO 成熟度模型為基礎。

### 使用簡化版檢查清單

TODO Group 的 OSPO checklist [^8] 把前述成熟度模型拆成較易操作的里程碑，協助剛起步或已經運作多年的 OSPO 檢視自己在每個階段的進展情況。實務上，每個 OSPO 都可以依照自身需求，增減或調整清單內容。

### 搭配成熟度模型規劃藍圖

當你對成熟度模型有一定熟悉度之後，就可以開始把它當成設計策略與執行計畫的工具。

例如，日本的 OSPO Local Meetup 工作小組（由 TODO Group 與 OpenChain 支援）正在編寫一份「OSPO 常見問答」指南，將各種開放原始碼活動依照成熟度模型從 0 到 4 分級，並說明 OSPO 在每個階段可以扮演的角色。

以下列出幾項工作成果，供參考：

![OSPO 角色](/images/ospo-role_zh-tw.png)
![開放原始碼的效益](/images/benefits-of-oss_zh-tw.png)

> 注意：其中一位成員在 Qiita 上整理了日文與英文摘要 [^9]，有興趣可以參考。

規劃 OSPO 時，與不同團隊中日常會使用開放原始碼，或其策略涉及開放原始碼專案（例如授權與安全弱點）的經理、高階主管、員工及承包商進行一對一對談，非常有幫助。可以運用這些對話得到的洞見，找出組織特有的動機，並對應到開放原始碼能在組織內創造價值的領域。

即使 OSPO 尚未正式成立與啟動，這也有助於在整個組織中建立對這項工作的認同與支援。

接著，運用 OSPO 成熟度模型，將這些動機對應到組織內不同的活動類型，並依不同成熟度階段再做第二層分類。與利害關係人互動及溝通時，可以把這份分類當作參考。

例如：

<img width="942" alt="開放原始碼參與活動分類" src="/images/activityparticipationcategorization_zh-tw.png">

## 可能發生的問題與因應方式

### 問題

在規劃 OSPO 的過程中，不斷收到新的問題與資訊，只好一再調整計畫；組織內對開放原始碼的理解與價值認知落差很大，造成混亂與潛在風險。

### 建議

務必花時間完整盤點利害關係人，並理解各自的動機與期待。建立公開的開放原始碼宣言、原則與對外網站，是讓不同團隊與子公司共享同一套價值與目標的有效方式。
只要能在早期就打好這種「共同語言」的基礎，OSPO 在之後的協調與治理工作會順利得多。

## 資源與註腳

### 資源

- TODO Group 開放原始碼專案貢獻與發布指南：https://todogroup.org/resources/guides/a-guide-to-outbound-open-source-software/
- TODO Group 開放原始碼社群參與指南：https://todogroup.org/resources/guides/participating-in-open-source-communities/
- DevOps 講求能力，而非成熟度：https://octopus.com/blog/devops-uses-capability-not-maturity
- Porsche 開放原始碼網站：https://opensource.porsche.com/
- OSPO 的演進：https://www.linuxfoundation.org/research/the-evolution-of-the-open-source-program-office-ospo
- OSPO 101 訓練模組－OSPO 與組織：https://github.com/todogroup/ospo-career-path/tree/main/OSPO-101/module3

### 註腳

[^1]: Strategy - End Game for FINOS Maturity Model: https://osr.finos.org/docs/presentations/strategy
[^2]: Creating an open source strategy document: https://todogroup.org/resources/guides/setting-an-open-source-strategy/
[^3]: A deep dive into OSPOs: https://www.linuxfoundation.org/research/a-deep-dive-into-open-source-program-offices
[^4]: OSPO Mind Map: https://todogroup.org/resources/mindmap/
[^5]: Dr. Ibrahim H, Guide to Enterprise Open Source: https://www.linuxfoundation.org/research/guide-to-enterprise-open-source
[^6]: Carl-Eric: https://web.archive.org/web/20240419100823/https://debricked.com/blog/what-is-open-source-maturity-model/
[^7]: The TODO Group Maturity Model: https://github.com/todogroup/ospology/blob/main/ospo-model/zh-tw/five-stage-OSPO-maturity-model.md
[^8]: The TODO OSPO checklist: https://github.com/todogroup/ospology/blob/main/ospo-model/zh-tw/ospo-checklist.md
[^9]: OSPO Japan Local Meetup Working Group 摘要（含日文與英文）：<https://qiita.com/owada-k/items/017d1b98d0e437766bd0>
