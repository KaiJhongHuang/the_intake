# AI工作流日報 — 2026-07-27
> 涵蓋範圍：2026-07-26 06:00 ~ 2026-07-27 06:00 (TST)

> 📌 Claude 摘要：本日焦點為 Claude 共享對話遭 Google 索引的隱私事件、Kimi K3 釋出史上最大開放權重模型，以及 MCP 2026-07-28 規範 RC 發布。Anthropic 同步發表 Claude 5 世代 Context Engineering 新規則，社群反應熱烈。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude 5 Context Engineering 新規則**：Anthropic 移除 Opus 5/Fable 5 系統提示 80%內容無損效能，建議用 /doctor 簡化 CLAUDE.md。([來源](https://claude.com/blog/the-new-rules-of-context-engineering-for-claude-5-generation-models))

[2] **Opus 5 IMO 滿分 42/42**：無 Agent 框架、無工具輔助，ARC-AGI 3 分數為次佳模型三倍，但幻覺率升 14 個百分點至 50%。([來源](https://tech-tech.life/2026/07/26/claude-opus-5-full-review-i-ran-the-benchmarks/))

[3] **Claire Vo 評 Opus 5「聰明但惱人」**：盲測排第一，但拒絕解 merge conflict、nitpick 倍增，開發者體驗兩極。([來源](https://www.eesel.ai/blog/claude-opus-5-review))

## 🔧 工作流整合案例

[4] **MCP 2026-07-28 規範 RC 發布**：無狀態核心、回應快取、MCP Apps（沙盒 iframe UI）、擴充框架，Python/TS/Go/C# Beta SDK 同步上線。([來源](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/))

[5] **Hallmark 反 AI-slop 設計 Skill 衝 12.2K 星**：57 項檢查閘門阻擋模板化 UI，支援 Claude Code、Cursor、Codex。([來源](https://github.com/nutlope/hallmark))

[6] **Anthropic 經濟未來研究基金 $2 億**：資助 $5-30M 規模實驗，研究 AI 對勞動力影響與收入支持現代化。([來源](https://www.anthropic.com/news/economic-futures-research-fund-agenda))

## 🛠️ 新工具 & 套件

[7] **Kimi K3 開放權重提前釋出**：2.8T 參數 MoE、每 token 啟用 50B、1M 上下文，Modified MIT 授權，Together AI 與 Modal 提供 Day-0 託管。([來源](https://qz.com/moonshot-ai-kimi-k3-open-weights-download-072726))

[8] **Nathan Lambert 分析 K3 開放權重升級**：稱其為開放權重領域的「escalation」，1.4TB 權重檔對自建部署形成門檻。([來源](https://www.interconnects.ai/p/kimi-k3-the-open-weights-escalation))

[9] **OmniRoute AI 閘道器**：單一端點路由 231+ 供應商（含 50+ 免費），開源免費。([來源](https://debate.tellodb.com/blog/top-ai-tools-launched-2026-july))

## 💬 社群熱門討論

[10] **Claude 共享對話遭 Google 索引**：缺少 noindex 標籤致分享連結被搜尋引擎收錄，暴露 API 金鑰、加密錢包等敏感資料；Anthropic 已修補，Google 開始移除。([來源](https://venturebeat.com/technology/uh-oh-some-claude-shared-conversations-and-artifacts-appear-to-be-indexed-and-publicly-accessible-on-google-search))

[11] **GitHub 已存檔 453 筆外洩對話**：Shared-Claude-Chats repo 備份 453 Claude 與 519 Grok 對話，Bing 與第三方爬蟲仍有殘留。([來源](https://decrypt.co/374412/anthropic-share-button-quietly-publishing-claude-chats-google))

[12] **Cato CTRL 揭俄語駭客武器化 Claude**：代號「Trim」將越獄教學包裝為商業攻擊工具 AI Pentest Checker，記錄六種 Claude Opus 越獄技術。([來源](https://cybersecuritynews.com/claude-ai-shared-chats/))

[13] **Claude 服務 7/27 再度中斷**：部分用戶回報無法使用，為近期第三次短暫停機。([來源](https://community.designtaxi.com/topic/34006-is-claude-anthropic-ai-down-july-27-2026/#comment-36257))
