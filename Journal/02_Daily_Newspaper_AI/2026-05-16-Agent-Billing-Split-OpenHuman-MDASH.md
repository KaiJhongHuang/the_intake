# AI工作流日報 — 2026-05-16
> 涵蓋範圍：2026-05-15 06:00 ~ 2026-05-16 06:00 (TST)

> 📌 Claude 摘要：Anthropic 正式將 Agent SDK 計費從訂閱中獨立出來，反映 agent 使用已成主流且需專屬額度管理；同時 OpenHuman 以「先讀懂使用者」的反向策略登頂 GitHub Trending，顯示個人 AI agent 賽道正從工具層轉向情境層競爭。

## 🧠 Prompt 技巧 & 使用心得

[1] **Simon Willison 談 AI 鎖定降低**：各家 coding agent 工具趨同，切換成本大幅下降，建議別過度依賴單一平台。([來源](https://simonwillison.net/2026/May/14/not-so-locked-in/))

[2] **CLAUDE.md 最佳實踐共識**：社群建議控制 200 行以內、用層級式 markdown 結構，Claude 掃描效率最高。([來源](https://github.com/shanraisshan/claude-code-best-practice))

[3] **多 agent 分工模式**：主 session 用 Opus 做複雜推理，subagent 用 Sonnet 跑聚焦任務，社群回報生產力顯著提升。([來源](https://www.morphllm.com/claude-code-reddit))

## 🔧 工作流整合案例

[4] **Anthropic Agent SDK 獨立計費**：6/15 起 Agent SDK、claude -p、GitHub Actions 從訂閱分離，Pro 用戶每月 $20 額度。([來源](https://www.infoworld.com/article/4171274/anthropic-puts-claude-agents-on-a-meter-across-its-subscriptions.html))

[5] **OpenClaw 與第三方 agent 解禁**：Anthropic 恢復第三方 agent 使用權，搭配月度用量上限。([來源](https://venturebeat.com/technology/anthropic-reinstates-openclaw-and-third-party-agent-usage-on-claude-subscriptions-with-a-catch))

[6] **Claude Code v2.1.137 更新**：Fast mode 預設切換至 Opus 4.7，plugin 依賴檢查與 /plugin 預估 token 成本上線。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 🛠️ 新工具 & 套件

[7] **OpenHuman 登頂 GitHub Trending**：tinyhumansai 開源個人 AI agent，以 1B-token 記憶樹與 118+ 整合先讀懂使用者再回應。([來源](https://www.techtimes.com/articles/316731/20260516/agent-that-reads-you-first-openhuman-tops-github-trending-inverting-playbook.htm))

[8] **Microsoft MDASH 公開**：100+ agent 協作找漏洞，發現 16 個 Windows 關鍵 RCE 漏洞，基準測試 88.45% 領先業界。([來源](https://www.microsoft.com/en-us/security/blog/2026/05/12/defense-at-ai-speed-microsofts-new-multi-model-agentic-security-system-tops-leading-industry-benchmark/))

## 💬 社群熱門討論

[9] **AI coding agent 三強爭霸**：Claude Code、OpenAI Codex CLI、xAI Grok Build 形成 2026 主流三角競爭格局。([來源](https://devops.com/xai-enters-the-coding-agent-race-with-grok-build/))

[10] **Claude for Small Business 持續發酵**：Hacker News 討論 15 條預建工作流能否真正取代 SMB 手動流程，社群反應兩極。([來源](https://news.ycombinator.com/item?id=48130950))

[11] **Notion 開放外部 agent 接入**：Developer Platform 支援 Claude Code、Cursor、Codex 等直接在 Notion 內操作。([來源](https://peerlist.io/cnyouzige/articles/ai-agents-news--may-15-2026-claude-code-expansion-microsoft-))
