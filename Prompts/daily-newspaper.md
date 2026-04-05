## 任務簡介
產出每日新聞摘要，僅使用精選可靠來源，每條附索引號與來源 URL。

---

## 報告結構（7 個區塊）

| 區塊 | 說明 | 建議則數 |
|------|------|---------|
| 🇹🇼 台灣要聞 | 政經、社會、兩岸 | ~5 |
| 📰 中美要聞 | 中國、美國 | ~5 |
| 🌏 世界要聞 | 重大政治、外交、地緣衝突(除中美) | ~5 |
| 💹 財經 & 市場 | 股市、總經、油價、匯率 | ~3 |
| 💻 科技業 & 半導體 | 大廠動態、晶片、製造 | ~3 |
| 🤖 AI 產業趨勢 | 融資、法規、競爭格局、大廠發布 | ~3 |
| 🔬 科學 & 能源 | 重大研究、能源轉型、氣候 | ~3 |

則數可依當日重要程度增減。

---

## 精選來源（搜尋時優先使用）

### 🇹🇼 台灣要聞
- cna.com.tw
- udn.com
- ltn.com.tw

### 📰 中美要聞
- scmp.com
- nytimes.com
- wsj.com

### 🌏 世界要聞
- reuters.com
- apnews.com
- bbc.com/news

### 💹 財經 & 市場
- bloomberg.com
- reuters.com/finance
- money.udn.com

### 💻 科技業 & 半導體
- digitimes.com
- arstechnica.com
- theverge.com

### 🤖 AI 產業趨勢
- technologyreview.com
- venturebeat.com/ai
- theregister.com

### 🔬 科學 & 能源
- nature.com/news
- iea.org/news
- arstechnica.com/science

---

## 內容規範（嚴格執行）

- **每條 50 字以內**，加流水索引號 [1]、[2]...
- **每條必須附來源 URL**（WebSearch 實際回傳的連結）
- **禁止推測或幻覺**：無法找到確實來源 → 標記「⚠️ 未找到來源，略過」
- **補充分析時**明確標注「📌 Claude 推測：...」，與事實段落分開

---

## 產出格式

```
# 每日新聞 — YYYY-MM-DD
> 涵蓋範圍：YYYY-MM-(DD-1) 06:00 ~ YYYY-MM-DD 06:00 (TST)

## 🇹🇼 台灣要聞
[1] **標題**：50字內摘要。([來源](URL))

## 📰 中美要聞
[N] ...

## 🌏 世界要聞
[N] ...

## 💹 財經 & 市場
[N] ...

## 💻 科技業 & 半導體
[N] ...

## 🤖 AI 產業趨勢
[N] ...

## 🔬 科學 & 能源
[N] ...

---
📌 Claude 推測：[今日整體觀察，標明為推測]
```

---

## 標題生成
根據今日整體報告，產出一個英文短標題（3-5個單字，用連字號連接），
代表當日最核心的新聞主軸，用於檔案命名：
`YYYY-MM-DD-<Title>.md`

## 產出位置
`Journal/01_Daily_Newspaper/YYYY-MM-DD-<Title>.md`

## Commit 設定
直接推到 main branch
