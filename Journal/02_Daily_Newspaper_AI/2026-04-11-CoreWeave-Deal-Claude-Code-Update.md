# AI工作流日報 — 2026-04-11
> 涵蓋範圍：2026-04-10 06:00 ~ 2026-04-11 06:00 (TST)

> 📌 Claude 摘要：Anthropic 與 CoreWeave 簽下 68 億美元多年基礎設施合約，同日 Claude Code v2.1.100 釋出，MCP 工具結果上限大幅提升至 500K；Cowork GA 與 Managed Agents 公測後續效應持續發酵，企業級 AI Agent 生態加速成形。

## 🧠 Prompt 技巧 & 使用心得

[1] **MCP 工具結果上限提升至 500K**：Claude Code v2.1.100 新增 `_meta["anthropic/maxResultSizeChars"]` 註解，允許大型結果（如 DB schema）不被截斷。([來源](https://claude-world.com/articles/claude-code-21100-release/))

[2] **CLAUDE.md 保持精簡約 100 行**：Claude Code 創建者建議控制在 2,500 tokens 內，搭配 lessons.md 讓 Claude 從錯誤中自學改進。([來源](https://mindwiredai.com/2026/03/25/claude-code-creator-workflow-claudemd/))

[3] **Context Engineering 取代 Prompt Engineering**：2026 年重點從單次提示轉向建立持久上下文系統，Claude 每次對話前讀取設定檔了解使用者偏好。([來源](https://www.the-ai-corner.com/p/claude-best-practices-power-user-guide-2026))

## 🔧 工作流整合案例

[4] **Anthropic × CoreWeave 68 億美元多年合約**：Anthropic 將在 CoreWeave 雲端平台以 NVIDIA Vera Rubin GPU 運行 Claude 生產工作負載，CoreWeave 股價當日漲逾 10%。([來源](https://www.cnbc.com/2026/04/10/coreweave-anthropic-claude-ai-deal.html))

[5] **Claude Cowork GA 企業功能上線**：新增 RBAC 角色存取控制、群組費用上限、OpenTelemetry 支援、Zoom MCP 連接器，全面支援 macOS 與 Windows。([來源](https://9to5mac.com/2026/04/09/anthropic-scales-up-with-enterprise-features-for-claude-cowork-and-managed-agents/))

[6] **n8n AI Agent Node 更新 MCP 整合**：修正 MCP tool call 工具名稱擷取問題，AI builder 互動更智慧，webhook 安全性提升。([來源](https://releasebot.io/updates/n8n))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.100 釋出**：Write 工具對大型檔案 diff 計算加速 60%，修復 --resume 快取失效、Edit/Write 格式化 hook 衝突等問題。([來源](https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md))

[8] **Microsoft Agent Governance Toolkit**：開源 MIT 授權，涵蓋 OWASP Agentic Top 10 全部控制項，支援 Python/Rust/TS/Go/.NET，sub-ms 政策引擎。([來源](https://opensource.microsoft.com/blog/2026/04/02/introducing-the-agent-governance-toolkit-open-source-runtime-security-for-ai-agents/))

[9] **Codenotary AgentMon 發布**：專為 AI Agent 設計的監控工具，追蹤 agent 行為、檔案存取與資料存取模式。([來源](https://aiagentstore.ai/ai-agent-news/2026-april))

## 💬 社群熱門討論

[10] **Tom's Hardware 質疑 Mythos 零日漏洞聲明**：指出「數千個嚴重零日漏洞」實際僅基於 198 個人工審核樣本，認為宣傳大於實質。([來源](https://www.tomshardware.com/tech-industry/artificial-intelligence/anthropics-claude-mythos-isnt-a-sentient-super-hacker-its-a-sales-pitch-claims-of-thousands-of-severe-zero-days-rely-on-just-198-manual-reviews))

[11] **Managed Agents 定價引發討論**：$0.08/小時 + token 費用，全天候運行約 $58/月，社群討論相比自建 Agent 基礎設施的成本效益。([來源](https://www.the-ai-corner.com/p/claude-managed-agents-guide-2026))

[12] **CoreWeave 成為 AI 基礎設施焦點**：繼 Meta 210 億擴約後再簽 Anthropic，九大 AI 模型供應商中已有九家使用其平台。([來源](https://thenextweb.com/news/coreweave-has-agreed-a-multi-year-gpu-cloud-deal-with-anthropic-to-power-claude-at-production-scale-its-second-major-ai-infrastructure-announcement-in-48-hours))
