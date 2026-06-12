# AI工作流日報 — 2026-06-12
> 涵蓋範圍：2026-06-11 06:00 ~ 2026-06-12 06:00 (TST)

> 📌 Claude 摘要：DXC 與 Anthropic 宣布多年期全球聯盟，將 Claude 推入銀行、航空等關鍵系統；Fable 5 靜默回退爭議延燒，Anthropic 承諾改為可見提示；FortiGuard 揭露假 Claude Code 教學散佈 AsyncRAT 惡意程式。

## 🧠 Prompt 技巧 & 使用心得

[1] **Fable 5 靜默回退改為可見提示**：6/11 Anthropic 承認敏感查詢靜默降級至 Opus 4.8 是錯誤取捨，將改為顯示回退通知。([來源](https://apidog.com/blog/claude-fable-5-safety-safeguards/))

[2] **Fable 5 免費窗口 6/22 截止**：Pro/Max/Team/Enterprise 用戶可免費使用 Fable 5 至 6/22，之後需用量額度。([來源](https://www.developersdigest.tech/blog/claude-fable-5-june-22-deadline))

[3] **Fable 5 結構化提示最佳化**：開發者實測 XML 標籤在長上下文中大幅降低幻覺，適用於程式碼遷移與 API 文件提取。([來源](https://www.globaltechcouncil.org/Claude/claude-fable-5-for-developers-prompt-engineering-api-best-practices/))

[4] **Simon Willison 評 Fable 5**：稱其為「beast」，慢且貴但複雜任務表現強，一切投入皆能處理。([來源](https://simonwillison.net/2026/Jun/9/claude-fable-5/))

## 🔧 工作流整合案例

[5] **DXC × Anthropic 多年全球聯盟**：6/11 宣布，DXC 成為 Claude Partner Network 首批 Global Premier 夥伴，數萬工程師將獲 Claude 認證。([來源](https://www.anthropic.com/news/dxc-anthropic-alliance))

[6] **DXC OASIS 平台 95% 程式碼由 Claude 生成**：AI 原生編排平台 4 月上線，已部署逾 50 家客戶，軟體交付速度提升 10 倍。([來源](https://dxc.com/newsroom/06112026-dxc-and-anthropic-announce-multi-year-global-alliance-to-bring-ai-into-mission-critical-enterprise-systems))

[7] **Claude Code v2.1.169 Safe Mode 上線**：--safe-mode 一鍵關閉所有自訂（CLAUDE.md、plugins、hooks、MCP），方便排查問題根因。([來源](https://jangwook.net/en/blog/en/claude-code-june-2026-new-features-changelog-developer-guide/))

[8] **Claude Code 新增 /cd 指令**：可在不中斷 prompt cache 的情況下切換工作目錄，減少多 repo 場景的 session 碎片。([來源](https://code.claude.com/docs/en/changelog))

## 🛠️ 新工具 & 套件

[9] **MCP Dev Summit 回顧：110M 月下載量**：6/12 公布，MCP SDK 月下載破 1.1 億次，16 個月達成 React 花三年的里程碑。([來源](https://www.digitalapplied.com/blog/mcp-dev-summit-2026-readout-protocol-roadmap-analysis))

[10] **MCP 7/28 RC 鎖定無狀態架構**：移除 initialize 握手與 session header，支援原生 round-robin 負載均衡，企業規模化部署成為可能。([來源](https://mcp.directory/blog/mcp-2026-07-28-release-candidate))

[11] **Microsoft Dataverse MCP Server 更新**：新 tool shape 讓 AI Agent 更有效操作業務資料，6/8 發布。([來源](https://www.microsoft.com/en-us/power-platform/blog/2026/06/08/dataverse-mcp-server-understanding-the-new-tool-shape/))

## 💬 社群熱門討論

[12] **Fable 5 越獄與「秘密破壞」反彈**：發布數日即遭越獄產出漏洞利用碼，社群批評靜默回退形同暗中降級。([來源](https://www.techtimes.com/articles/318268/20260612/claude-fable-5-hit-jailbreak-claims-secret-sabotage-backlash-days-after-launch.htm))

[13] **FortiGuard 揭露假 Claude Code 教學散佈 AsyncRAT**：偽裝 .7z 教學檔案內含 .lnk 觸發多階段腳本，最終注入遠端存取木馬。([來源](https://hackread.com/hackers-fake-claude-code-guide-ai-pdfs-asyncrat/))

[14] **Fable 5 定價引發開發者反彈**：輸入 token 價格為 Opus 4.8 兩倍，部分開發者測試期間帳單達數百美元，Hacker News 討論破 2000 則。([來源](https://www.kucoin.com/news/flash/anthropic-s-claude-fable-5-launch-sparks-developer-backlash-over-token-costs-and-data-policies))
