你是 AI 工作流日報的編輯。請根據以下規則，搜集並產出今日的 AI 工作流日報。

## 時間規則

遵循 CLAUDE.md 中定義的日報時間規則。

## 搜集範圍

請搜集以下領域的重要更新：

### Prompt 技巧 & 使用心得（4-6 則）
- Prompt engineering 新技巧、最佳實踐
- Claude / GPT / 其他模型的使用技巧
- 社群分享的實戰經驗

### 工作流整合案例（4-6 則）
- AI + 自動化工具（n8n, Zapier, Make 等）
- 開發者工作流整合實例
- 多 Agent 協作模式

### 新工具 & 套件（4-6 則）
- AI 相關新工具、框架、SDK 發布
- 現有工具重大更新
- MCP Server、Plugin 生態

### 社群熱門討論（3-5 則）
- Reddit、Hacker News、Twitter/X 熱門 AI 討論
- 開源專案動態（star 數暴漲、爭議等）
- 業界人士重要發言

## 格式要求

每則新聞格式：
```
[編號] **粗體標題摘要**：一句話補充說明。（[來源](URL)）
```

各領域用 emoji + 中文標題作為 h2 分節：
- 🧠 Prompt 技巧 & 使用心得
- 🔧 工作流整合案例
- 🛠️ 新工具 & 套件
- 💬 社群熱門討論

## 結尾

最後加上 `## 📌 Claude 觀察` 區塊，用 3-5 個 bullet 提供對當日 AI 生態的簡短觀察。

## 輸出

1. 將日報儲存為 `Journal/02_Daily_Newspaper_AI/YYYY-MM-DD-English-Title.md`
2. 同時更新 `content.json`（遵循 CLAUDE.md 的新增文章規則）
3. Commit 並 push 到 main
