# AI工作流日報 — 2026-06-21
> 涵蓋範圍：2026-06-20 06:00 ~ 2026-06-21 06:00 (TST)

> 📌 Claude 摘要：本日焦點為 Claude Code v2.1.185 修復多項 IDE 體驗問題、Claude Design 強化與 Code 雙向同步、Developer Platform 新增 response_inclusion 精簡 agentic 回應。Google Gemini CLI 已於 6/18 結束免費服務並轉型為 Antigravity CLI。

## 🧠 Prompt 技巧 & 使用心得

[1] **Fable 5 proactive 邊界設定**：Willison 指出 Fable 5 會主動擴大任務範圍，建議在 prompt 中明確標註「僅評估、不執行」以限制行為。([來源](https://simonwillison.net/2026/Jun/11/fable-is-relentlessly-proactive/))

[2] **response_inclusion 精簡 agentic 回應**：Developer Platform 新增 response_inclusion 參數，可裁剪已消費的 result blocks，降低多輪 agent 的 token 成本。([來源](https://releasebot.io/updates/anthropic))

[3] **Auto mode 安全強化**：Claude Code 現封鎖未經請求的 git reset --hard、commit --amend 非本次 session commit、及 terraform destroy 等破壞性指令。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 🔧 工作流整合案例

[4] **Claude Design ↔ Code 雙向同步**：Design 更新加入 sidebar 入口、直接 canvas 編輯、更強 layout 控制，設計稿變更可即時反映至 Code。([來源](https://releasebot.io/updates/anthropic/claude))

[5] **WIF 無金鑰認證正式上線**：Workload Identity Federation 以短期憑證取代靜態 API key，支援 AWS IAM、GCP SA、GitHub Actions OIDC 等提供者。([來源](https://releasebot.io/updates/anthropic))

[6] **Salesforce Summer '26 Hosted MCP GA**：Salesforce 託管 MCP server 正式 GA，外部 AI agent 可透過 OAuth 存取 sObject CRUD、Data 360、Tableau 分析。([來源](https://developer.salesforce.com/blogs/2026/06/the-salesforce-developers-guide-to-the-summer-26-release))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.185 發布**：修復 JetBrains 2026.1+ 終端閃爍、Kitty 協定 Shift+非 ASCII 字元遺失、stream-stall 提示改為 20 秒觸發。([來源](https://code.claude.com/docs/en/changelog))

[8] **Gemini CLI → Antigravity CLI 轉型**：Google 於 6/18 終止 Gemini CLI 免費服務，未付費用戶轉由 Antigravity CLI 接手。([來源](https://geminicli.com/docs/resources/quota-and-pricing/))

[9] **OpenCode 突破 165K 星**：開源 coding harness 整合 LSP 提供型別資訊，支援 18+ 語言，月活開發者超 750 萬。([來源](https://opencode.ai/))

## 💬 社群熱門討論

[10] **Claude Code GitHub Action 供應鏈漏洞回顧**：Microsoft 揭露 Action 處理不受信任 issue 內容時可洩漏 CI/CD secrets，已於 v2.1.128 修復。([來源](https://www.microsoft.com/en-us/security/blog/2026/06/05/securing-ci-cd-in-agentic-world-claude-code-github-action-case/))

[11] **Terminal-Bench 2.1 排名更新**：Claude Code + Fable 5 得分 83.1%、Opus 4.8 得 78.9%，Gemini CLI + Gemini 3.1 Pro 得 70.7%。([來源](https://www.morphllm.com/best-ai-coding-agents-2026))

[12] **Datasette Apps 發布**：Willison 推出 datasette-apps 插件，用 Fable 5 + Claude Code 與 GPT-5.5 Codex 協作建構 WASM 互動應用。([來源](https://simonwillison.net/))
