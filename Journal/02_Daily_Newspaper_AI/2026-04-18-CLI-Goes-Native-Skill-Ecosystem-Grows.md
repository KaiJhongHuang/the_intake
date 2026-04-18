# AI工作流日報 — 2026-04-18
> 涵蓋範圍：2026-04-17 06:00 ~ 2026-04-18 06:00 (TST)

> 📌 Claude 摘要：Claude Code CLI 架構大改——v2.1.113 切換原生二進位、沙箱安全強化；GitHub `gh skill` 公開預覽讓 Agent 技能進入套件管理時代；OpenAI 以 GPT-Rosalind 搶進生命科學垂直領域。（以上為 Claude 綜合觀察，非事實報導）

## 🧠 Prompt 技巧 & 使用心得

[1] **Simon Willison 用 Opus 4.7 開發 datasette 1.0a28**：大部分改動由 Claude Code 完成，展示 AI 輔助開源維護實例。([simonwillison.net](https://simonwillison.net/2026/Apr/17/datasette/))

[2] **貼上現有程式碼為最佳 prompt 策略**：Claude Code 最佳實踐指出，給真實參考碼比抽象描述產出效果更好。([Smart Web Tech](https://smart-webtech.com/blog/claude-code-workflows-and-best-practices/))

[3] **Skills 取代重複提示**：將每日內循環工作流寫成 .claude/commands/ 下的 slash command，省去反覆 prompting。([Smart Web Tech](https://smart-webtech.com/blog/claude-code-workflows-and-best-practices/))

## 🔧 工作流整合案例

[4] **GitHub `gh skill` 公開預覽**：單指令安裝 Agent 技能，跨 Claude Code、Codex、Cursor、Gemini CLI 通用。([GitHub Changelog](https://github.blog/changelog/2026-04-16-manage-agent-skills-with-github-cli/))

[5] **awesome-agent-skills 突破 1000+ 技能**：VoltAgent 社群策展，涵蓋工程、行銷、合規等領域，支援 8+ 平台。([GitHub](https://github.com/VoltAgent/awesome-agent-skills))

[6] **awesome-design-md 推出 Claude Code 技能**：47+ 品牌設計系統打包為可安裝技能，60KB 即可產出品牌一致 UI。([GitHub](https://github.com/VoltAgent/awesome-design-md))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.113**：CLI 改用原生平台二進位（breaking）、sandbox 新增 deniedDomains、修復 38 項問題。([GitHub Releases](https://github.com/anthropics/claude-code/releases/tag/v2.1.113))

[8] **v2.1.114 修復 Agent Teams 權限崩潰**：隊友請求工具權限時對話框崩潰，已於 4/18 01:34 UTC 修復。([GitHub Releases](https://github.com/anthropics/claude-code/releases))

[9] **OpenAI GPT-Rosalind 研究預覽**：首款生科垂直模型，蛋白質與分子推理超越 GPT-5.4，僅限企業客戶。([OpenAI](https://openai.com/index/introducing-gpt-rosalind/))

## 💬 社群熱門討論

[10] **白宮稱會談「有建設性」但黑名單未解除**：Amodei 與 Wiles 達共識繼續對話，文職機構或先取得 Mythos 存取。([CNN](https://www.cnn.com/2026/04/17/business/anthropic-white-house-meeting-dario-amodei))

[11] **gh skill 安全疑慮浮現**：GitHub 明確警告技能非經驗證，可能含 prompt injection 或惡意腳本，需手動審查。([GitHub Changelog](https://github.blog/changelog/2026-04-16-manage-agent-skills-with-github-cli/))

[12] **OpenAI「Spud」模型即將發布**：內部代號 GPT-5.5/GPT-6，Polymarket 預測 78% 機率於四月底前釋出。([LumiChats](https://lumichats.com/blog/gpt-5-5-spud-openai-release-date-features-april-2026-complete-guide))
