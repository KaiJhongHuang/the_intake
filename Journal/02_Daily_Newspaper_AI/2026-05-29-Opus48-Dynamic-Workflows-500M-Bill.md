# AI工作流日報 — 2026-05-29
> 涵蓋範圍：2026-05-28 06:00 ~ 2026-05-29 06:00 (TST)

> 📌 Claude 摘要：Opus 4.8 發布是今日最大事件，Dynamic Workflows 讓 Claude Code 可平行調度上千子代理；企業端則出現 $5 億帳單事故與微軟砍 Claude Code 授權，顯示 AI 工具採用的成本治理仍是痛點。

## 🧠 Prompt 技巧 & 使用心得

[1] **Opus 4.8 誠實度大幅提升**：較 4.7 少四倍機率放過程式碼瑕疵不提，遇不確定問題傾向拒答而非捏造。([來源](https://www.anthropic.com/news/claude-opus-4-8))

[2] **Willison 評 Opus 4.8「modest but tangible improvement」**：基準分 1890 Elo，領先 GPT-5.5 約 121 分，高難度任務勝率約 67%。([來源](https://simonwillison.net/2026/May/28/claude-opus-4-8/))

[3] **r/ClaudeAI 用戶反映諂媚問題**：上線數小時即有人指出 Opus 4.8 比 4.7 更傾向附和，與官方宣稱矛盾，引發討論。([來源](https://aiweekly.co/node/2035))

## 🔧 工作流整合案例

[4] **Dynamic Workflows 研究預覽上線**：Claude Code 可動態生成編排腳本，單次會話最多產生 1,000 個平行子代理處理大規模遷移。([來源](https://techcrunch.com/2026/05/28/anthropic-releases-opus-4-8-with-new-dynamic-workflow-tool/))

[5] **Self-Hosted Sandboxes 公開 Beta**：Managed Agents 工具執行移至客戶自有基礎設施，支援 Cloudflare、Modal、Vercel 等平台。([來源](https://thenewstack.io/anthropic-mcp-tunnels-sandboxes/))

[6] **MCP Tunnels 研究預覽**：代理透過單一加密出站連線存取私有 MCP 伺服器，無需開放入站防火牆規則。([來源](https://www.infoq.com/news/2026/05/claude-mcp-tunnels/))

[7] **Domotz MCP Server GA**：網路監控平台 Domotz 推出 MCP 伺服器，AI 代理可直接監控管理 4 萬+網路。([來源](https://www.globenewswire.com/news-release/2026/05/28/3302681/0/en/AI-Agents-Can-Now-Monitor-and-Manage-Networks-Through-New-Domotz-MCP-Server.html))

## 🛠️ 新工具 & 套件

[8] **Opus 4.8 正式發布**：距 4.7 僅 41 天，Fast Mode 費用降至前代三分之一，API 定價不變。([來源](https://www.anthropic.com/news/claude-opus-4-8))

[9] **Bumblebee v0.1.1 持續走紅**：Perplexity 開源供應鏈掃描器，覆蓋八大套件生態與 MCP 設定，純讀取零依賴設計。([來源](https://github.com/perplexityai/bumblebee))

[10] **Fast Mode Opus 4.8 三倍降價**：高速模式 2.5 倍速度輸出，Max/Team/Enterprise 方案預設開啟。([來源](https://thenewstack.io/claude-opus-48-release/))

## 💬 社群熱門討論

[11] **企業客戶一個月燒 $5 億 Claude 帳單**：未設用量上限，員工無限制使用導致全年 AI 預算四月耗盡。([來源](https://techstartups.com/2026/05/28/company-accidentally-spent-500-million-on-claude-ai-in-one-month-after-forgetting-usage-limits/))

[12] **微軟砍大部分內部 Claude Code 授權**：六月底前轉向 GitHub Copilot CLI，成 2026 年最大規模企業 AI 支出回縮。([來源](https://www.windowscentral.com/microsoft/microsoft-cancels-claude-code-licenses-shifting-developers-to-github-copilot-cli-a-move-likely-driven-by-financial-motives))

[13] **Uber 四個月燒光 $34 億 AI 預算**：5,000 工程師使用率達 84-95%，每人月成本 $500-$2,000。([來源](https://thenextweb.com/news/microsoft-claude-code-retreat-ai-cost))

[14] **GitHub Copilot 六月起全面轉用量計費**：改為 AI Credits 制度，反映企業 AI 工具定價模式正在重塑。([來源](https://aiweekly.co/alerts/microsoft-drops-claude-code-as-enterprise-ai-roi-fails))
