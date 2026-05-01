# AI工作流日報 — 2026-05-01
> 涵蓋範圍：2026-04-30 06:00 ~ 2026-05-01 06:00 (TST)

> 📌 Claude 摘要：五角大廈與八家科技巨頭簽署機密 AI 協議卻排除 Anthropic，同日微軟 Agent 365 正式 GA，標誌企業 AI Agent 治理時代到來；Claude 生態方面，1M context beta 正式退場、Code v2.1.120 因 resume 崩潰緊急回滾。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code v2.1.120 resume 崩潰**：--resume/--continue 觸發未定義回呼崩潰，可用 `/resume <id>` 替代。([來源](https://github.com/anthropics/claude-code/issues/53086))

[2] **Simon Willison 用 LLM 工具建 iNaturalist 觀察工具**：展示以 AI 輔助快速打造個人資料整合專案。([來源](https://simonwillison.net/2026/May/1/inat-sightings/))

[3] **Sonnet 4.5／Sonnet 4 的 1M context beta 於 4/30 正式退場**：需遷移至 Sonnet 4.6 或 Opus 4.6 方可使用百萬 token。([來源](https://platform.claude.com/docs/en/release-notes/overview))

## 🔧 工作流整合案例

[4] **Microsoft 365 E7 + Agent 365 今日 GA**：$99/user/月，統一 Copilot 與 Agent 治理控制台，首個企業級 Agent 管控平台。([來源](https://techcommunity.microsoft.com/blog/microsoft_365blog/microsoft-365-e7-and-agent-365-are-now-generally-available/4516295))

[5] **GitHub Copilot Opus 4.7 倍率調升至 15×**：促銷價 7.5× 於 4/30 結束，5/1 起正式採 15× premium request 計費。([來源](https://github.blog/changelog/2026-04-16-claude-opus-4-7-is-generally-available/))

[6] **GitHub Copilot 將於 6/1 改為 token 用量計費**：取消 request 制，依模型與 token 數計價。([來源](https://github.blog/news-insights/company-news/changes-to-github-copilot-individual-plans/))

## 🛠️ 新工具 & 套件

[7] **五角大廈與 8 家科技公司簽機密 AI 協議，排除 Anthropic**：OpenAI、Google、Microsoft、Nvidia、SpaceX 等入列，Anthropic 因安全護欄堅持遭黑名單。([來源](https://www.cnn.com/2026/05/01/tech/pentagon-ai-anthropic))

[8] **五角大廈 CTO 稱 Mythos 是「國安時刻」但 Anthropic 仍列風險**：Emil Michael 表示 Mythos 網安能力驚人，但公司整體仍被排除。([來源](https://www.cnbc.com/2026/05/01/pentagon-anthropic-blacklist-mythos-michael.html))

[9] **Anthropic 營收超越 OpenAI 達 $300 億 ARR**：Counterpoint Research 4/30 報告確認，Claude Code 為成長加速器。([來源](https://www.theregister.com/2026/04/30/openai_anthropic_top_lines_research_counterpoint))

## 💬 社群熱門討論

[10] **Hacker News 熱議 Claude API 穩定性**：4/30 Haiku 4.5 短暫錯誤率飆升，社群持續關注可用性。([來源](https://news.ycombinator.com/item?id=47938097))

[11] **白宮與 Anthropic 重啟對話**：Axios 報導政府因 Mythos 能力過強「無法忽視」，正研議解除黑名單。([來源](https://www.axios.com/2026/05/01/washington-new-anthropic-problem))

[12] **Claude Code v2.1.120 自動回滾至 2.1.119**：官方確認 resume bug 後啟動自動降版，新 session 不受影響。([來源](https://github.com/anthropics/claude-code/issues/53086))
