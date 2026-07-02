---
name: coffee-chat-prep
description: |
  準備、執行、收尾 founder peer coffee chat / networking meeting 的全流程（準備 → 現場 → 事後收尾）。當使用者提到「幫我 prep 跟 X 的 coffee chat」「下週要見某某怎麼準備」「meeting prep」「coffee chat 策略」「networking meeting 準備」「跟 X 見面要聊什麼」「見完 X 幫我收尾 / follow up」「幫我看這場 chemistry 怎樣」或類似 founder 一對一見面前中後的需求時，觸發此 skill。也適用於使用者提到即將見某人但沒主動要求 prep 時，agent 可主動建議走這個流程。建議問題見附檔 question-bank.md（依 node 類型 / 目的挑題）。
---

# Coffee Chat Playbook（準備 / 現場 / 事後收尾 全流程）

為 founder peer 一對一見面（warm intro、30-90 min、雙重目的：建立關係 + tactical 學習）走完整流程。

> **來源（這份 skill 為什麼存在）**：由 [CW Lin](https://www.linkedin.com/in/chiweilin131)（[Portaly](https://portaly.cc) 創辦人）從一年間在紐約、東京、舊金山進行的 founder coffee chat 中蒸餾而成，對象包含 YC、a16z 背景的創業者和幾位頂尖創作者。以下每條規則都在真實會面中驗證過；anti-pattern 是 CW 實際踩過的坑。其中幾場變成了長久的友誼，有幾場甚至改變了他公司的走向。
>
> **樣本與適用範圍（請當免責聲明讀）**：這是一個 founder 的個人 playbook，不是通用方法論。樣本小而特定：一個人、一年、多為 warm-intro 的 founder peer 一對一，情境是一位亞洲 founder 從零打美國人脈。以下所有 heuristic 都是 prior，不是 ground truth。當眼前這個人給出比規則更清楚的 signal 時，跟著 signal 走。執行時以精神為重（relationship-first、先給再拿），不要機械照表操課。

> **心態優先（讀任何戰術之前先讀這條）**：沒有人有義務幫你。每一次邀約與請求都必須有禮貌、帶著真誠的感謝。這個態度先於下面所有內容，是整份 skill 的地基；戰術只有蓋在它上面才有效。
>
> **核心信念**：高 ROI 的 founder coffee chat 重點不是「extract 多少 lesson」，是**讓對方在 6 個月後會主動想到你**。整個流程服務這個目的。
>
> **配套**：
> - 建議問題題庫 → `question-bank.md`（依 node 類型 / 目的挑題）
> - 產品 demo / user feedback 的深度紀錄 → 另走獨立的 user-interview skill（本 skill 的事後階段只到「會面收尾」）

---

## 適用範圍

✅ Warm intro 的 founder peer、30-90 min 一對一、雙重目的（關係 + 學習）、聯絡人名單裡的候選對象
❌ Sales / investor pitch、cold first meeting、內部會議、recruiter/candidate 面談、純社交 hangout

不適用 → 回報原因，不硬套。

## 三階段總覽

| 階段 | 何時 | 產出 |
|---|---|---|
| 🅰 準備 | 見面前 | prep 稿（node 判定 + takeaway + 對談大綱 + 長短 CTA） |
| 🅱 現場 | 見面中 | 對話節奏腳本 + 觀察點 + chemistry 檢測（可輸出一頁 cheat sheet） |
| 🅲 事後收尾 | 24hr 內 | 24hr deliver + 輕量 debrief + 關係分層追蹤 |

## 術語：關係分層（Layer）

本 skill 中的「Layer」語言來自作者自己的 networking 模型。定義如下：

| Layer | 意思 |
|---|---|
| **1** | 活動 / 社群認識的 cold contact。主要是資訊交換和 idea 刺激。 |
| **1.5** | 有過真正的一對一（可能好幾次），但對方還沒有主動的 reciprocity。這是轉換窗口，還不算關係。 |
| **2** | 真正的 peer。定義性行為是**互相、不用開口的 intro**：他不用你請就替你行動。 |
| **3** | 高槓桿人脈（頂級投資人、tier-1 operators）。幾乎只能透過 Layer 2 的 intro 到達，無法直接打。 |

大多數 coffee chat 都活在 Layer 1.5 的窗口。整個事後階段只為了回答一個問題：這個 1.5 會不會升級成 2？（見下方「Layer 升級追蹤」；注意升級靠的是會後 signal，跟見面次數無關。）

---

# 🅾 在社群留言報名 coffee chat（禮儀）

進入下面三階段之前：如果你是在社群貼文下留言報名（有人開放 coffee chat），基本禮儀會大幅提高中選率。主辦人在掃很多留言，決定誰值得一個時段。

1. **用真實、可辨識的帳號留言**：不要用匿名或只有 handle 的帳號。
2. **把 profile 填好**：短自介 + 真實頭貼。別人有一部分就是靠這個決定要不要跟你聊。
3. **留言本身永遠包含三行**：
   - **你是誰**：怎麼稱呼你 + 你的身分（學生 / founder / 在職）
   - **你現在在做什麼**
   - **你想聊什麼**

> 這三行是報名的基本禮貌：讓主辦人能立刻判斷 fit、知道要準備什麼。空帳號留一句「有興趣！」會直接被跳過。

---

# 🅰 準備（Before）

## Step 1：變數收集（缺哪些主動問，已給的別重問）
1. 對方姓名 / 公司 / 角色 / 階段
2. 場地 / 時間 / **時長**（45 vs 90 min 結構完全不同）
3. Intro path（誰介紹、warm 程度）
4. 對方最近的 public signal（IPO / 新聞 / 新品 / 文章 / funding）
5. 你這場的真實動機（申請 prep？broadcast？純好奇？對方主動約？）
6. 你的 default give（可拋什麼資源 / network / 數據？）

## Step 2：Node 類型判定（決定「這場 aim 什麼」）

| Node | 從他那拿什麼 | 最適合對象 | 時機 |
|---|---|---|---|
| **Broadcast** | 透過他傳播到更大網絡（program batch 內部頻道等） | 1-2 年 out、Series A、有 network 且 active | 等他 mature 才有 value |
| **Playbook** | 剛走過你想走那條路的第一手經驗 | 剛完成該路徑、記憶最新鮮 | **越早越好，遲了記憶 decay** |
| **Ally** | 長期 peer，階段相近、方向相容 | 階段 + 領域對、互補不競爭 | 持續 show up 慢慢養 |

> Founder filter（樣本不足、不寫死）：剛進頂級 program（頂尖加速器 / VC inside track）的 founder，外部 help 需求曲線急降 → 偏 Playbook node，別預期 build long-term Ally。但不要把標籤寫死：有些 program alum 仍會變成真正的長期 Ally，看實際 chemistry 而不是靠 heuristic。

## Step 3：Takeaway 目標（agent 列候選 → 使用者拍板）

> ⚠️ 目標不由 agent 自己定。Agent 依「node 類型 + 對方 stage」列 **2-3 個 primary takeaway 候選**，用互動式提問給使用者選，使用者拍板才寫進 prep（候選不對可選 Other）。

**Primary 候選的分流參考**：

| 對方 stage | Primary 取向 |
|---|---|
| Peer founder（同 layer 在路上） | 關係：「X 6 個月後主動想到我」、種 reciprocity |
| 頂級 program alum（加速器 inside / Series B+） | Playbook：「拿到 actionable playbook + 留 next round 可能」 |

❌ 任何 stage 都錯：「拿到 X 個 lesson」的 extraction framing。

**Bonus（optional，最多一個）**：single insight，不是 full playbook。功能是逼你從 extraction → listening mode。
**內心純然目的（不對外、自己帶進場）**：non-transactional 的 inner frame，例「我來看這 founder 本人是誰，找 peer mirror」。它會 leak 在語氣 / follow-up 深度 / 沉默處理。

## Step 4：對談大綱（時序 20 / 55 / 25）

- **Segment A 開場（~20%）**：你先一句定位 + 框 talk（有 ask 先講）→ 換對方。不切深題，建 chemistry。
- **Segment B 主動議題（~55%）**：3-5 題、**依重要性排序**、標「未必全問，看 chemistry」、標**風險題**。
  → 題目從 `question-bank.md` 依 node 類型 / 動機挑，每題附 1-2 個 sub-clarifier。
  - 排序：actionable for you > 對方 willing to share > unique to this person（公開查得到的不問）
- **Segment C give（~25%，不少於 10 min）**：開頭先 open-ended 問「你現在最想解決但還沒解的事？不限工作」→ default offer 只是備用。

### 短版 vs 長版 CTA（多備長對話的彈藥）
高 chemistry 的 meeting 常自然延長，遠超原訂時間。
- **短版（30-45 min）**：標準 follow-up + 24hr deliver
- **長版（90 min+，過第一個自然 break 才 unlock）**：多備 1-2 個 long-horizon strategic question / proposal，例「假設你明年要 push X 進美國市場，你會怎麼設計第一個 30 天？」
- 不主動 push 延長，但自然延長時**手上要有東西可丟**。

## Step 5：（條件）Collab proposal 設計 4 原則
> 只在這場有真實合作潛力（尤其 dev tool / infra founder）時用。命題*形狀*對不對，比 demo 強度更重要。
1. **Match 對方此刻的 distribution / user 缺口**：設計成對方輕量整合、value 直接落地
2. **Low-stakes framing**：帶「先試試看，不一定有效」降溫，更深的 commit 之後才解鎖
3. **First-give 順序**：兩層以上的 proposal 先做 L1（你先做、對方零投入）再 L2
4. **當場具體 anchor**：開場 30 秒丟一個具體目標，對齊對方動機，follow-up 才有掛點

## Step 6：（條件）介紹人關係管理（前置）
> Warm intro 才有。別在同一個介紹人身上 stack 多個 ask；聊完主動回報結果；到他的城市時請他吃飯；想好能回饋介紹人什麼。

## 🚫 不 ask 鐵則（第一次見面）
- 不 ask intro（任何 intro）
- 不 ask 客戶名單
- 不 ask 具體 metrics（revenue / pricing / 數字）

## 輸出：prep 稿（markdown）
標題 + meta（時間 / 地點 / 時長 / hard stop）→ node 判定 → takeaway（使用者拍板版）→ 對談大綱（A/B/C + 長短 CTA）→ 帶進現場的 cheat sheet。

---

# 🅱 現場（During）

## 對話節奏腳本（手機可瞄的 script）
> 用第二人稱寫，不是教學語氣。時間比例 = Segment A/B/C。

- **前 ~20%**：小聊暖場 → 你用一句話定位自己的公司 + 框 talk（「我在做 X，所以特別想跟你聊」）→ 換對方講 pivot / 近況。**餵料**讓對方有機會反問你細節。
- **中 ~55%**：對方介紹完 → 你追問（Segment B 題目，照排序）。中段丟一顆 **peer-mode 球**（你自己 unfiltered 的踩坑 / judgment）→ 看對方 reciprocate 與否，決定聊多深。
- **後 ~25%**：先 open-ended 問「你最想解決但還沒解的事？」→ 對方講了才對應 give；沒講才拋 default。
- **最後 5 分鐘**：克制，不主動 raise next step。剩 30 秒對方還沒提 → 給一個 low-commit opening：「我在 X 待到 Y，想再 catch up 或需要 intro 隨時 ping 我。」

## 觀察點 5 項（現場 cheat sheet）
1. **Emotional energy**：哪段是 alive 的（真 conviction）vs rehearsed 的（在 protect / 沒想清楚）
2. **對外部 entity（VC / partner / 競品）的 framing**：「they get me」（insider、survivorship bias）/「hard to crack」（raw、有用）→ 影響你怎麼 weight 他的建議
3. **Deflection 點**：用技巧帶過的 topic = 他在 protect 的東西；記下來別硬挖，下次溫和靠近
4. **Spark moment**：你 update 自己 business 時，對方哪句話讓他前傾 / 反問 / 想要細節 = 未來合作的天然接點 → 帶進事後 debrief
5. **Reciprocity signal（最關鍵）**：對方有沒有 unprompted offer（intro / advice / resource）= Layer 升級最強的 signal

（特殊敏感點如 stealth mode，可自行加第 6 項客製化觀察點。）

## 當場 chemistry 檢測（4 signals）
> **核心：先丟球，才能觀察。** 你正常聊，戰術性選擇何時切 peer mode。Signal 測的是對等交流下，對方的 initiative 方向和深度。
1. 他主動問你細節：追問 4-5 層 vs 禮貌一句就 drop
2. 他 share 公開沒講過的東西（**主引擎**）：你先切 peer mode 丟 unfiltered → 他 reciprocate 或不
3. 他把「下次 / 合作」具體化：給日期 / logistics vs 模糊的「有機會吧」
4. 他自然提起下次見面（你**克制不主動 raise**）：他自己提 vs 只交換聯絡方式

| 命中 | 解讀 | 動作 |
|---|---|---|
| 3-4 | 真 chemistry → Layer 2 候選 | Overinvest：24hr 加碼 + 再見面 + 回以 substance |
| 2 | program/batch 的 warmth ≠ chemistry | Light-touch：deliver 交差 + 約 1 個月後 ping |
| 0-1 | one-off | 24hr 禮貌 follow-up 做完，放下 |

## 現場紀律
- 未必全問（看 chemistry，別追題）
- Reading defensive 就停（風險題碰到防衛 → 換 topic）
- **Spark 沒出現就別硬 give**：沒有火花時停止給予，講越多越像在說服對方需要你

## 現場 cheat sheet 輸出（PDF 確認）
把現場那頁（節奏 beat + 5 觀察點 + 4 chemistry signals + 排序過的題目）獨立成一頁 cheat sheet。
→ **問使用者：要不要輸出 PDF？** 要的話用你的 PDF 匯出工具（需要中文時記得用 CJK + Latin 雙字體）。

---

# 🅲 事後收尾（After，24hr 內）

> 姿態：**他帶走的 >> 你帶走的。** 多數 founder 去見人是「我要學」，正確的是反過來：對方帶走東西 → 觸發「這人有料」→ broadcast 機率上升。

## 24hr deliver（見面後 24hr 內送出）
兩種形式：
- **(a) 兌現承諾**：他問過的東西 → 24hr 內給（3 個 profile / 一頁數據 doc）
- **(b) Proactive 丟**：他提過的需求 → 不用他開口主動補上（intro / 人選）

具體包含 (a)(b)(c)：
- (a) 對應對方痛點的 deliverable（default offer 不 fit 就 swap）
- (b) 你帶去但沒講完的東西（數據 sample / context）
- (c) 一個沒問完的問題 = round 2 的勾子

（Priority node 可順手寫 follow-up email 框架：Subject → 開頭 1-2 句 → (a)(b)(c) → Closing + next ping rhythm）

## 輕量 debrief
- 把 spark moment + reciprocity signal 寫進這個人的聯絡人筆記
- 一句 next ping rhythm（什麼時機 / 什麼由頭再連絡，例「他 IPO 後」「我 Q3 數據出來時」）
- 如果是有在追蹤的聯絡人 → 更新他的 Layer 狀態

## Layer 升級追蹤（5 signals，見面後 2-4 週觀察）
1. 他**主動** intro 你給第三方
2. 他公開提到你（發文 tag / podcast / 活動引介）
3. 你遇到困難時他**主動**關心 / 幫忙
4. 他分享 unfiltered 的真實 metrics / 想法（不是 PR 版）
5. 他記得你上次說的事，下次主動 follow up

→ **一條都沒發生 = 還在 Layer 1.5**，不管見過幾次面。升級不靠見面本身，靠這 5 條。

## （條件）介紹人回報 + 產品 feedback 轉檔
- Warm intro → 72hr 內回報介紹人結果
- 若這場有產品 demo / user feedback 要深挖 → 轉獨立的 user-interview skill，不混進來

---

## 🚫 Anti-pattern 總表（7 條，血淚換來的）

| # | Anti-pattern | 階段 |
|---|---|---|
| 1 | 目的性太重 / 索取太多資訊（把對方當 information source） | 🅰 |
| 2 | 每段塞滿、不留 chemistry 空間（留 20-30% buffer） | 🅰 |
| 3 | Give 段直接拋 default offer（沒先問「最想解決什麼」） | 🅰/🅱 |
| 4 | Takeaway 寫成「拿到 X 個 lesson」 | 🅰 |
| 5 | 問題沒排序，逼自己現場決定 | 🅰 |
| 6 | 觀察點寫成抽象原則，而不是 actionable cheat sheet | 🅱 |
| 7 | Give 不亮還硬加碼（沒看 spark 反應就一直拋） | 🅱 |

---

## 輸出格式與存放
最終 prep 稿用 markdown，順序：meta → 🅰 node + takeaway + 大綱 + 長短 CTA → 🅱 節奏 + 觀察點 + chemistry → 🅲 收尾框架。
存放在對應的 project 資料夾；沒有對應就開一個帶日期的 meeting 資料夾。

---

## 流程 checklist（agent 自跑，跑完才 deliver）

**🅰 準備**
- [ ] 變數六項
- [ ] Node 類型判定（Broadcast / Playbook / Ally）
- [ ] Takeaway 候選 2-3 個 → **給使用者拍板**（不自己定）
- [ ] 對談大綱 20/55/25，Segment B 從 question-bank 挑題 + 排序 + 標風險題
- [ ] 長版 CTA 多備 1-2 個
- [ ]（有合作潛力）collab proposal 4 原則
- [ ]（warm intro）介紹人管理前置
- [ ] 不 ask 鐵則有提醒

**🅱 現場**
- [ ] 對話節奏腳本（含開場 / 轉場 / give 帶入 / 收尾句）
- [ ] 5 觀察點（actionable，非抽象）
- [ ] Chemistry 4 signals + 命中 → 動作
- [ ] 現場紀律三條
- [ ] 一頁 cheat sheet + 問使用者要不要 PDF

**🅲 事後收尾**
- [ ] 24hr deliver (a)(b)(c) + 兩種形式
- [ ] Debrief 寫進聯絡人筆記 + next ping
- [ ] Layer 升級 5 signals（追蹤 2-4 週）
- [ ]（warm intro）回報介紹人 /（產品 feedback）轉 user-interview skill

**通用**
- [ ] Anti-pattern 7 條 self-check
