# AI工作流日報 — 2026-05-02
> 涵蓋範圍：2026-05-01 06:00 ~ 2026-05-02 06:00 (TST)

> 📌 Claude 摘要：Claude Code 發布 v2.1.126 大版本更新，Microsoft Agent 365 正式 GA 開放多模型治理，五角大廈 AI 協議繼續排除 Anthropic 但前國防智庫主管加入 Anthropic 任駐場策略師，攻守態勢微妙。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code v2.1.126 發布**：新增 /model picker 支援自訂 gateway、`project purge` 指令清除專案狀態、MCP 啟動自動重試。([來源](https://releasebot.io/updates/anthropic/claude-code))

[2] **1M Context Beta 正式退場**：Sonnet 4.5/4 的 1M token beta 已於 4/30 終止，需遷移至 Sonnet 4.6 或 Opus 4.6 使用 GA 版本。([來源](https://releasebot.io/updates/anthropic))

[3] **Reddit 社群共識：多 Agent 分工模式**：主 session 跑 Opus 做複雜推理、subagent 跑 Sonnet 做聚焦任務，用 CLAUDE_CODE_SUBAGENT_MODEL 控制。([來源](https://www.aitooldiscovery.com/guides/claude-code-reddit))

## 🔧 工作流整合案例

[4] **Trimble SketchUp MCP Connector 上線**：透過 MCP 讓 Claude 直接操作 .skp 檔，用自然語言生成 3D 模型，免費額度 30 個模型。([來源](https://www.prnewswire.com/news-releases/trimble-links-sketchup-with-anthropics-claude-bringing-new-conversational-ai-powered-capabilities-to-3d-modeling-302756403.html))

[5] **Microsoft Agent 365 正式 GA**：每用戶 $15/月，提供 AI agent 即時可見性與治理，可匯入 AWS Bedrock 與 Gemini Enterprise agent。([來源](https://www.microsoft.com/en-us/security/blog/2026/05/01/microsoft-agent-365-now-generally-available-expands-capabilities-and-integrations/))

[6] **Zensai Human Success Agent 上架 Agent 365**：整合人力資源資料，在 M365 內即時驅動績效與技能發展洞察。([來源](https://www.prnewswire.com/news-releases/zensai-introduces-human-success-agent-for-microsoft-agent-365-redefining-ai-driven-learning-and-human-success-in-the-flow-of-work-302760146.html))

## 🛠️ 新工具 & 套件

[7] **Claude Code 支援多平台 PR URL**：`--from-pr` 現接受 GitLab MR、Bitbucket PR 與 GitHub Enterprise URL。([來源](https://releasebot.io/updates/anthropic/claude-code))

[8] **Cursor CVE-2026-26268 揭露**：惡意 repo 的 Git hook 可繞過沙箱執行任意程式碼，已於 Cursor 2.5 修復。([來源](https://cybersecuritynews.com/cursor-ai-coding-agent-vulnerability/))

[9] **Agent 漏洞利用時間從 5 個月縮至 10 小時**：RunSybil CEO 指出前沿 LLM 正大幅加速從 bug 發現到可用 exploit 的時程。([來源](https://blog.mean.ceo/ai-agents-news-may-2026/))

## 💬 社群熱門討論

[10] **五角大廈 AI 協議排除 Anthropic**：DoD 與 7 家科技巨頭簽約，Anthropic 因川普政府黑名單持續被排除。([來源](https://www.cnn.com/2026/05/01/tech/pentagon-ai-anthropic))

[11] **前五角大廈智庫主管加入 Anthropic**：Jim Baker（ONA 前主任）任「駐場策略師」，研究 AI 對美國制度與中國競爭的影響。([來源](https://www.defenseone.com/technology/2026/05/former-head-pentagons-think-tank-joins-anthropic/413256/))

[12] **Bloomberg：叫 Claude 的人生活變複雜了**：AI 同名效應讓真人 Claude 在機場、職場頻繁被誤認，引發身份困擾。([來源](https://www.bloomberg.com/news/articles/2026-05-01/claude-ai-is-complicating-life-for-people-named-claude))
