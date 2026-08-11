# AI工作流日報 — 2026-05-28
> 涵蓋範圍：2026-05-27 06:00 ~ 2026-05-28 06:00 (TST)

> 📌 Claude 摘要：Opus 4.8 今日正式發布，SWE-Bench Pro 衝上 69.2%，Dynamic Workflows 研究預覽讓 Claude Code 一次調度數百個平行子代理；同日惡意 npm 套件鎖定 Claude 使用者目錄竊取資料，凸顯 AI 工具鏈的供應鏈安全風險升溫。

## 🧠 Prompt 技巧 & 使用心得

[1] **Opus 4.8 誠實度提升**：早期測試者回報模型更常主動標記不確定性、減少無根據聲明。([MacRumors](https://www.macrumors.com/2026/05/28/anthropic-claude-opus-4-8/))

[2] **高 Effort 預設值**：Opus 4.8 Claude Code 預設啟用 high-effort 模式，適合複雜跨檔任務。([The New Stack](https://thenewstack.io/claude-opus-48-release/))

[3] **Mid-task System Messages**：Messages API 新增任務中途插入系統訊息功能，可即時調整模型行為。([MarkTechPost](https://www.marktechpost.com/2026/05/28/anthropic-ships-claude-opus-4-8-alongside-dynamic-workflows-and-cheaper-fast-mode-with-workflows-capped-at-1000-subagents/))

## 🔧 工作流整合案例

[4] **Dynamic Workflows 研究預覽**：Claude Code 可自動拆解大任務並調度數百個平行子代理，上限 1,000 個。([MarkTechPost](https://www.marktechpost.com/2026/05/28/anthropic-ships-claude-opus-4-8-alongside-dynamic-workflows-and-cheaper-fast-mode-with-workflows-capped-at-1000-subagents/))

[5] **Fast Mode 三倍降價**：Opus 4.8 fast mode 速度提升 2.5 倍、價格僅為先前模型三分之一。([Anthropic](https://www.anthropic.com/news/claude-opus-4-8))

[6] **Agent View 上線**：`claude agents` 命令一覽所有 Claude Code session 的運行、等待與完成狀態。([Releasebot](https://releasebot.io/updates/anthropic/claude-code))

[7] **`/code-review --fix` 自動修正**：review 結果現可直接套用到工作目錄，包含重用與簡化建議。([Releasebot](https://releasebot.io/updates/anthropic/claude-code))

## 🛠️ 新工具 & 套件

[8] **Claude Opus 4.8 發布**：SWE-Bench Pro 64.3%→69.2%，同價位直接升級 Opus 4.7（$5/$25/M tokens）。([Anthropic](https://www.anthropic.com/news/claude-opus-4-8))

[9] **Claude Code 大版本更新**：收緊安全檢查、改善 auto mode、修復 background sessions / worktrees / VS Code / Windows 多項 bug。([Claude Code Docs](https://code.claude.com/docs/en/whats-new))

[10] **Managed Agents 企業沙箱**：自託管沙箱進入公開 beta，agent 可連接企業內部 MCP 伺服器。([DEV Community](https://dev.to/hongphuc5497/ai-tools-products-radar-may-28-2026-41hj))

## 💬 社群熱門討論

[11] **惡意 npm 套件鎖定 Claude 目錄**：「mouse5212-super-formatter」竊取 /mnt/user-data，攻擊者還意外洩漏自己的 GitHub token。([The Hacker News](https://thehackernews.com/2026/05/malicious-npm-package-stole-files-from.html))

[12] **Pwn2Own 冠軍警告 Mythos 衝擊**：Chompie 指 Mythos 級 AI 一兩年內恐淘汰人類漏洞獵人。([ResultSense](https://www.resultsense.com/news/2026-05-27-chompie-ethical-hacker-claude-mythos-cyber/))

[13] **Bloomberg 揭 Anthropic 招聘哲學**：約半數技術人員無 ML 背景，重視多元經歷勝過傳統學歷。([Bloomberg](https://www.bloomberg.com/news/features/2026-05-28/anthropic-job-recruiting-brings-in-diverse-careers-to-build-claude))

[14] **Simon Willison「The Pressure」**：反思 AI 工具持續加速帶來的壓力與產業節奏變化。([simonwillison.net](https://simonwillison.net/2026/May/26/the-pressure/))
