# AI工作流日報 — 2026-05-15
> 涵蓋範圍：2026-05-14 06:00 ~ 2026-05-15 06:00 (TST)

> 📌 Claude 摘要：企業採用加速——PwC 三萬人培訓、蓋茲基金會 $2 億合作同日公布；Fast Mode 預設切換至 Opus 4.7 帶來百萬 token 原生上下文；微軟內部砍 Claude Code 授權轉向 Copilot CLI 引發開發者不滿，顯示工具選擇正被平台策略綁架。

## 🧠 Prompt 技巧 & 使用心得

[1] **Fast Mode 預設切 Opus 4.7**：5/14 起 Claude Code `/fast` 預設改用 Opus 4.7，輸出速度提升 2.5 倍、原生支援 100 萬 token 上下文。([來源](https://www.buildfastwithai.com/blogs/claude-opus-4-7-fast-mode-guide))

[2] **Context Engineering 共識成形**：2026 社群結論——模型品質已夠好，任務結構（Context Engineering）比 Prompt 措辭更影響產出品質。([來源](https://www.the-ai-corner.com/p/claude-best-practices-power-user-guide-2026))

[3] **多 Agent 分工模式**：Reddit 熱門做法——主 session 用 Opus 做複雜推理，子 agent 用 Sonnet 跑聚焦任務，透過 `CLAUDE_CODE_SUBAGENT_MODEL` 控制。([來源](https://www.morphllm.com/claude-code-reddit))

## 🔧 工作流整合案例

[4] **PwC × Anthropic 擴大聯盟**：5/14 宣布培訓認證 30,000 名 PwC 員工使用 Claude，全球部署 Claude Code 與 Cowork，交付時間縮短最多 70%。([來源](https://siliconangle.com/2026/05/14/pwc-expands-anthropic-alliance-will-train-30000-staff-claude/))

[5] **Claude for Small Business 巡迴啟動**：5/14 芝加哥首站，免費半日工作坊，整合 QuickBooks、PayPal、HubSpot 等 15 套預建工作流。([來源](https://www.anthropic.com/news/claude-for-small-business))

[6] **蓋茲基金會 $2 億合作**：Anthropic 與 Gates Foundation 投入 $2 億於全球健康、教育與農業 AI 應用，為期四年。([來源](https://www.anthropic.com/news/gates-foundation-partnership))

## 🛠️ 新工具 & 套件

[7] **Claude Code Plugin Marketplace 成熟化**：官方 Marketplace 與社群目錄並行，plugins 可註冊 slash commands、hooks、sub-agents，`/skills` 支援即時篩選。([來源](https://code.claude.com/docs/en/discover-plugins))

[8] **awesome-claude-code-toolkit**：GitHub 社群最大工具包——135 個 agent、176+ plugins、35 skills、42 commands、14 組 MCP 設定。([來源](https://github.com/rohitg00/awesome-claude-code-toolkit))

## 💬 社群熱門討論

[9] **微軟砍 Claude Code 授權**：微軟要求內部開發者 6/30 前全面轉用 GitHub Copilot CLI，儘管開發者普遍偏好 Claude Code。([來源](https://www.windowscentral.com/microsoft/microsoft-cancels-claude-code-licenses-shifting-developers-to-github-copilot-cli-a-move-likely-driven-by-financial-motives))

[10] **Claude Code 五月更新彙整**：新增 `/goal` 持續執行指令、Agent View 視覺化、`--add-dir` 等 agent flags，修復多項 background session 問題。([來源](https://pasqualepillitteri.it/en/news/2223/claude-code-may-2026-release-notes-radio-plugin-marketplace))
