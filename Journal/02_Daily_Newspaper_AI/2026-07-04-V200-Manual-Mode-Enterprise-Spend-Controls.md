# AI工作流日報 — 2026-07-04
> 涵蓋範圍：2026-07-03 06:00 ~ 2026-07-04 06:00 (TST)

> 📌 Claude 摘要：Claude Code v2.1.200 是一次「收緊預設值」的版本——預設權限模式正式更名 Manual、AskUserQuestion 不再自動跳過，顯示 Anthropic 正有意減少代理靜默行動空間。同日 Anthropic 推出 Enterprise 花費控管三件組（模型級授權、花費警示、Admin API），直接回應 Uber 四月燒光全年預算、某企業單月 $5 億帳單等事件引發的企業信任危機。Endor Labs 的獨立安全基準測試顯示 Sonnet 5 + Claude Code 功能面 83.2% 表現優異，但安全修補僅 19.6%，延續「好工程師、差資安工程師」的跨模型通病。MCP 2026-07-28 RC 是協議自 2024 年發布以來最大改版，核心走向無狀態、OAuth 對齊企業部署，為七月底正式上線做準備。

## 🧠 Prompt 技巧 & 使用心得

[1] **Endor Labs：Sonnet 5 功能 83.2% 安全僅 19.6%**：獨立基準測試 200 題全數完成，中位數約 7 分鐘；作弊僅 8 例，是近期最誠實的 Claude 模型。([來源](https://www.endorlabs.com/learn/claude-sonnet-5-with-claude-code-strong-on-function-average-on-security-and-unusually-honest))

[2] **HN Sonnet 5 成本論戰**：社群指出高 effort 下每任務成本可能超過 Opus 低 effort，質疑近期模型被調校為消耗更多 token 而非更快解題。([來源](https://news.ycombinator.com/item?id=48736605))

[3] **Willison 六月電子報發布**：回顧 sqlite-utils 4.0rc1 加入 migrations 與巢狀交易，以及六月 Claude 生態重點摘要。([來源](https://simonwillison.net/2026/Jul/3/june-newsletter/))

## 🔧 工作流整合案例

[4] **Claude Code v2.1.200 權限收緊**：預設權限模式正式更名 Manual，CLI/VS Code/JetBrains 同步套用；AskUserQuestion 不再自動跳過，需透過 /config 設定 idle-timeout。([來源](https://github.com/anthropics/claude-code/releases))

[5] **Enterprise 花費控管三件組上線**：模型級授權限制各角色可用模型；花費警示在 75%/90% 組織額度通知管理員；Admin API 支援批次審核額度申請與異常偵測。([來源](https://claude.com/blog/giving-admins-more-visibility-and-control-over-claude-usage-and-spend))

[6] **Sonnet 5 成為 Claude Code 預設模型**：原生 1M context window，促銷價 $2/$10 per Mtok 至 8/31，effort 參數預設 high。([來源](https://www.anthropic.com/news/claude-sonnet-5))

## 🛠️ 新工具 & 套件

[7] **MCP 2026-07-28 RC 釋出**：協議層改為無狀態、移除 Session ID；OAuth 2.1/OIDC 對齊企業部署；新增 Apps（伺服器端 UI）與 Tasks（長時間工作）擴充。([來源](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/))

[8] **v2.1.200 背景代理穩定性修復**：背景 session 在睡眠/喚醒後不再靜默停止；daemon.lock PID 被 OS 重用後不再阻擋代理啟動；macOS 孤兒 pty-host 不再佔 100% CPU。([來源](https://releasebot.io/updates/anthropic/claude-code))

[9] **v2.1.200 /code-review 精簡**：合併五個清理 finder 為一，token 用量降約 25%。([來源](https://code.claude.com/docs/en/changelog))

## 💬 社群熱門討論

[10] **企業 AI 帳單失控成焦點**：TechTimes 報導 78% IT 主管遇意外 AI 帳單，Uber 四月燒光全年預算，促使 Anthropic 加速推出花費控管。([來源](https://www.techtimes.com/articles/319687/20260704/claude-enterprise-spend-controls-arrive-agentic-ai-bills-blow-past-budgets.htm))

[11] **Sonnet 5 瀏覽器注入防禦大幅提升**：System Card 揭露瀏覽器場景攻擊成功率從 Opus 4.8 的 31.5% 降至 0.93%，幻覺與諂媚率同步降低。([來源](https://www.anthropic.com/claude-sonnet-5-system-card))

[12] **Sonnet 5 已登陸 GitHub Copilot**：GitHub 宣布 Sonnet 5 正式可用於 Copilot，與 Claude Code 同步擴展企業開發者觸及面。([來源](https://github.blog/changelog/2026-06-30-claude-sonnet-5-is-generally-available-for-github-copilot/))
