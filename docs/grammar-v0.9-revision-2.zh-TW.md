# WOLN — Simplified English

## Core Grammar Specification V0.9 — Revision 2

**Status:** GRAMMAR REVIEW — PARTIALLY APPROVED  
**Project:** World Open Language for the Internet and AI Era

**Language Philosophy:** Simplified English · Flexible Grammar · Intuitive Speech

**Motto: Meaning First, Grammar Second.**

[English specification](grammar-v0.9-revision-2.md)

---

## A. 基本句型與語序

| ID  | 英文文法項目               | WOLN 簡化規則        | 狀態   |
| --- | -------------------- | ---------------- | ---- |
| G01 | 主詞＋動詞＋受詞             | 保留英文 SVO 基本語序    | 已有共識 |
| G02 | 主詞不可省略               | 聊天及指令中，意思清楚時可省略  | 建議採用 |
| G03 | 動詞後受詞                | 保留英文基本位置，不強制中文語序 | 已有共識 |
| G04 | 命令句                  | 直接用動詞原形          | 建議採用 |
| G05 | there is / there are | 可以省略，直接描述事物與位置   | 建議採用 |
| G06 | 長句結構                 | 優先簡短句型，保留複合句能力   | 建議採用 |

Examples:

- English: There are three files in the folder.
- WOLN: `3 file in folder.`
- English: Please download the new application.
- WOLN: `Please download new app.`

## B. 名詞、冠詞、代名詞、數量

| ID  | 英文文法項目            | WOLN 簡化規則            | 狀態   |
| --- | ----------------- | -------------------- | ---- |
| G07 | 複數 -s / -es       | 名詞不需要複數變化            | 已有共識 |
| G08 | 不規則複數             | 使用單數基本形態，如 `3 child` | 已有共識 |
| G09 | a / an            | 不要求冠詞，英文原形仍接受        | 已有共識 |
| G10 | the               | 不要求使用，依上下文理解         | 已有共識 |
| G11 | this / that       | 保留，明確指定時使用           | 已有共識 |
| G12 | 數字                | 優先使用 1、2、3 表示數量      | 已有共識 |
| G13 | some / many / few | 保留，表達不確定數量           | 建議採用 |
| G14 | 所有格               | my、your、his、her 等保留  | 建議採用 |
| G15 | John's / of       | 保留所有關係的表達            | 建議採用 |
| G16 | I / me、he / him   | 英文形式保留，允許可理解的非標準用法   | 建議採用 |

Examples:

- `I buy 2 app yday.`
- `She have 3 child.`
- `Please send me 1 file.`
- `I need info about this app.`

原有英文單字不強制改寫，取消複數不代表刪除單字本身的 s。

## C. 動詞、時間、狀態及語態

**核心決定：動詞原形為預設形式。時間、進行、完成等資訊可用獨立詞語或選用的英文形式表達。**

| ID      | 英文文法項目        | WOLN 簡化規則                             | 狀態     |
| ------- | ------------- | ------------------------------------- | ------ |
| G17     | 第三人稱 -s       | 不需要，she work                          | 已有共識   |
| G18     | 過去式 -ed       | 不需要，用時間詞表達                            | 已有共識   |
| G19     | 不規則過去式        | go、buy、send 等固定使用原形                   | 已有共識   |
| G20     | 未來式 will      | 不強制，明確時間詞即可                           | 已有共識   |
| G21     | 完成式           | 可用 already、finish、before 等表達          | 建議採用   |
| G22     | 進行狀態          | now、still 或可選 -ing 表達                 | 修訂     |
| **G23** | **be 動詞**     | **am/is/are/was/were 可保留，也可在語意清楚時省略** | **OK** |
| G24     | was / were    | 可用過去時間詞取代，原英文仍接受                      | 修訂     |
| G25     | 情態動詞          | can、must、should、may、need 等保留意義差異      | 建議採用   |
| **G26** | **to + 動詞**   | **保留英文慣用方式，必要時可測試省略**                 | **OK** |
| **G27** | **動名詞及 -ing** | **保留 -ing，選用於強調動作正在進行；不代表必須使用現在時態**   | **OK** |
| **G28** | **被動語態**      | **保留英文被動用法，也允許簡短被動表達；優先選清楚句型**        | **OK** |

### 時間表達

| Standard English            | WOLN                 |
| --------------------------- | -------------------- |
| I go to work every day.     | I go work every day. |
| I went to work yesterday.   | I go work yday.      |
| I will go to work tomorrow. | I go work tmr.       |
| She was happy yesterday.    | She happy yday.      |

### -ing 的選擇性使用

| WOLN                       | 表達重點              |
| -------------------------- | ----------------- |
| She work every day.        | 日常工作              |
| She work now.              | 現在工作，可能表示正在工作     |
| She working now.           | 明確強調正在工作          |
| She was working yday at 9. | 使用熟悉的英文進行式，加上明確時間 |
| She working yday at 9.     | 簡化形式，表示昨天九點正在工作   |

`-ing` 不被取消，也不強迫每次都使用。

### 被動語態的選擇性使用

- English: The file was sent yesterday.
- WOLN Simple: `File sent yday.`
- English Compatible: `File was sent yesterday.`
- Active WOLN: `John send file yday.`

如果必須知道誰完成動作、或動作是否完成，應該使用更完整的表達，不得因簡化而失去重要資訊。

## D. 疑問、否定與禮貌表達

| ID      | 英文文法項目          | WOLN 簡化規則                       | 狀態     |
| ------- | --------------- | ------------------------------- | ------ |
| G29     | Do/Does/Did 問句  | 可直接使用英文語序＋問號                    | 建議採用   |
| G30     | 疑問詞             | 保留 who、what、where、when、why、how  | 已有共識   |
| **G31** | **否定句**         | **簡化形式統一 don't + 原形，原英文形式保留相容** | **OK** |
| G32     | not / no        | 保留否定意義                          | 建議採用   |
| G33     | Can you...?     | 保留常見請求表達                        | 建議採用   |
| G34     | Please / Thanks | 保留熟悉禮貌詞                         | 建議採用   |

Examples:

- `She like coffee?`
- `What you buy yday?`
- `She don't need help.`
- `Please send me file.`

否定詞不可任意省略，因為它會直接改變句意。

## E. 形容詞、副詞、比較級與介系詞

| ID      | 英文文法項目       | WOLN 簡化規則                                  | 狀態     |
| ------- | ------------ | ------------------------------------------ | ------ |
| G35     | 形容詞位置        | 保留英文基本位置                                   | 已有共識   |
| G36     | 副詞 -ly       | 不強制 -ly，保留原詞相容                             | 建議採用   |
| **G37** | **比較級 -er**  | **允許 more + 原形，也接受 better、faster 等常見英文形式** | **OK** |
| **G38** | **最高級 -est** | **優先可使用 most，保留 best 等熟悉短詞**               | **OK** |
| G39     | at / in / on | 一般時間及地點表達允許彈性互通                            | 已有共識   |
| G40     | to / from    | 保留方向區別                                     | 建議採用   |
| G41     | 空間位置         | 影響裡面／上面等實際意義時保留區別                          | 建議採用   |
| G42     | 動詞片語         | turn on/off、log in/out 等保留意義差異             | 建議採用   |

Examples:

- `She drive slow.`
- `This app more useful.`
- `This app most useful.`
- `We meet at Monday.`
- `I work in Taipei.`

如果介系詞會改變實際的方向、位置或動作意義，則不能當作完全同義。

## F. 複合句、條件句及進階文法

| ID      | 英文文法項目     | WOLN 簡化規則                      | 狀態     |
| ------- | ---------- | ------------------------------ | ------ |
| G43     | and/or/but | 保留，已經簡短清楚                      | 建議採用   |
| G44     | because/so | 保留因果關係，可使用核准縮寫                 | 建議採用   |
| G45     | if 條件句     | 保留 if，不要求動詞時態變化                | 建議採用   |
| **G46** | **假設語氣**   | **可用 if、maybe 等表意，完整英文形式仍可使用** | **OK** |
| G47     | 關係子句       | 保留英文用法，也可以拆成短句                 | 建議採用   |
| G48     | 間接引述       | 不強制時態回溯，保留必要時間資訊               | 建議採用   |
| G49     | 祈使句        | 直接使用動詞原形                       | 已有共識   |
| G50     | 感嘆及口語      | 允許簡短自然表達                       | 建議採用   |

Examples:

- `If rain tmr, we stay home.`
- `Maybe she come tmr.`
- `App I download yday is useful.`
- `Open file and send to me.`

條件句的 if 不應隨意省略，以免條件和確定發生的事情混淆。

## G. 書寫、縮寫、發音與相容性

| ID  | 項目    | WOLN 規則              | 狀態   |
| --- | ----- | -------------------- | ---- |
| G51 | 大小寫   | 英文習慣為主，網路交流可彈性       | 建議採用 |
| G52 | 標點    | 保留重要標點，尤其問號          | 建議採用 |
| G53 | 日期時間  | 優先 YYYY-MM-DD、24 小時制 | 建議採用 |
| G54 | 英文原形  | 完整英文單字永遠接受           | 已有共識 |
| G55 | 網路縮寫  | 優先現有通用縮寫，避免歧義        | 已有共識 |
| G56 | 簡化口語  | 英語發音為主，短發音逐步驗證       | 已有共識 |
| G57 | 不同口音  | 允許不同母語的可理解口音         | 建議採用 |
| G58 | AI 相容 | 研究 AI 解析及轉換簡化句型的能力   | 研發目標 |
| G59 | 歧義處理  | 重要時補充時間、數量、對象、方向     | 已有共識 |
| G60 | 英文相容  | 接受完整英文與 WOLN 簡化形式    | 已有共識 |

---

## H. WOLN 文法設計的核心架構

### 1. WOLN Simple

主要用於教學、日常聊天、網路及 AI Prompt。

Examples:

- `She happy yday.`
- `I buy 2 app.`
- `We meet tmr.`
- `She working now.`

### 2. WOLN Flexible

容許使用者依照已掌握的英文程度，自由保留或省略不影響意思的文法。

Examples:

- `She is happy now.`
- `She happy now.`
- `I go to work tomorrow.`
- `I go work tmr.`

### 3. English Compatible

完整標準英文直接接受，不要求使用者重新學習語言。

Examples:

- `She was happy yesterday.`
- `I bought two apps yesterday.`
- `We will meet tomorrow.`

這三種形式共同屬於 WOLN 的相容範圍，而不是三套獨立語言。

---

## I. AI 時代的彈性文法理念

WOLN 充分利用大型語言模型理解上下文、補足省略資訊及辨識語言變體的能力。

但必須區分：

- **AI can interpret:** 模型通常可以推測簡化句子的意思。
- **AI verified:** 必須透過實際測試確認特定模型的正確理解率。
- **Human understood:** 必須透過不同母語的真人測試確認。

語言設計不以傳統文法的形式完整性作為唯一目標，而是優先確保人類交流能理解、關鍵資訊不遺失。

### WOLN Grammar Priority

1. Meaning — 意義
2. Clarity — 清楚
3. English Familiarity — 英文熟悉度
4. Simplicity — 簡單
5. Shortness — 簡短

**Meaning First, Grammar Second.**

---

## J. Review Status

**Version:** V0.9 Revision 2

**Confirmed in this revision:**

- G23 — be 動詞可保留，也可在意思清楚時省略
- G26 — to + 動詞保留，容許研究簡化
- G27 — 保留 -ing，強調動作正在進行
- G28 — 被動語態保留，優先清楚表達
- G31 — don't 作為預設簡化否定形式
- G37 — 比較級可用 more，熟悉形式保留
- G38 — 最高級可用 most，熟悉形式保留
- G46 — 假設語氣以簡單語意詞表達，保留英文相容

**Remaining status:** 其他標記「建議採用」的規則仍待最終審核。

**Publication:** Draft only. Not yet declared a frozen Grammar V1.0 standard.
