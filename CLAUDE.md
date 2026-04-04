# CLAUDE.md

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
