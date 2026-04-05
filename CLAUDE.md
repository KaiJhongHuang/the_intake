# CLAUDE.md

## 日報時間規則

- 時區：台灣時間（UTC+8）
- 「一天」定義：前一日 06:00 至當日 06:00
- 例：「2026-04-05」的日報，涵蓋 2026-04-04 06:00 ~ 2026-04-05 06:00 (TST)
- 今天台灣時間若為 4/5 早上，正在產出的是 **4/5 的日報**
- 來源僅標示日期無時間時，以該來源所在時區對應台灣時間判斷歸屬日
- 跨日事件：以首次報導時間決定歸屬日，後續追蹤可在隔日日報提及

### Markdown 開頭格式

日報正文第一行為標題，第二行記錄涵蓋的時間範圍：

```markdown
# 每日新聞 — 2026-04-05
> 涵蓋範圍：2026-04-04 06:00 ~ 2026-04-05 06:00 (TST)
```

## 日報內容規範（嚴格執行）

- **每條 50 字以內**，加流水索引號 [1]、[2]...
- **每條必須附來源 URL**（WebSearch 實際回傳的連結）
- **禁止推測或幻覺**：無法找到確實來源 → 標記「⚠️ 未找到來源，略過」
- **補充分析時**明確標注「📌 Claude 摘要：...」，與事實段落分開

## Commit 設定

- 產出日報後直接 commit 並 push 到 **main branch**
- Commit 時同時包含 `.md` 檔案與更新後的 `content.json`

## 新增文章規則

在 Journal/ 新增 .md 檔案時，**必須同時更新 `content.json`** 的 `articles` 陣列，否則網站不會顯示新文章。

格式：

```json
{
  "date": "YYYY-MM-DD",
  "title": "中文標題",
  "category": "分類id",
  "file": "Journal/資料夾/YYYY-MM-DD-Title.md"
}
```

## 分類對照

| category id | 資料夾 |
|---|---|
| `daily-newspaper` | `Journal/01_Daily_Newspaper/` |
| `daily-newspaper-ai` | `Journal/02_Daily_Newspaper_AI/` |

新增分類時，同時在 `content.json` 的 `categories` 陣列加入對應項目。

## Markdown 檔名格式

`YYYY-MM-DD-English-Title.md`
