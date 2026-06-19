# AI工作流日報 — 2026-06-19
> 涵蓋範圍：2026-06-18 06:00 ~ 2026-06-19 06:00 (TST)

> 📌 Claude 摘要：MCP 企業授權正式穩定版上線是今日最大里程碑，搭配首爾辦公室的 NAVER、三星等大規模部署，Anthropic 的企業落地加速明顯。Claude Code v2.1.183 強化 Auto Mode 安全防護，而 Google 正式日落 Gemini CLI 轉向 Antigravity，AI 編碼工具生態持續洗牌。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code Auto Mode 安全強化**：v2.1.183 自動阻擋 `git reset --hard`、`git clean -fd` 等破壞性指令，除非使用者明確要求。([來源](https://code.claude.com/docs/en/changelog))

[2] **`/config --help` 新指令**：Claude Code 新增列出所有可用簡寫鍵功能，Esc 改為儲存並關閉而非還原。([來源](https://code.claude.com/docs/en/changelog))

[3] **attribution.sessionUrl 設定上線**：可在 web 與 Remote Control 模式下省略 commit 中的 claude.ai session 連結。([來源](https://x.com/ClaudeCodeLog/status/2067782800988688648))

## 🔧 工作流整合案例

[4] **MCP 企業授權達穩定版**：以 Okta 為首個 IdP，支援零接觸 SSO，九個 MCP server 同步上線。([來源](https://www.techtimes.com/articles/318708/20260619/mcp-enterprise-authorization-goes-stable-zero-touch-sso-okta-anthropic-vs-code.htm))

[5] **Claude MCP Connector 支援 Okta 集中佈建**：企業管理員一次設定，員工首次登入即繼承 Figma、Linear、Supabase 等所有連接器。([來源](https://www.techtimes.com/articles/318704/20260619/claude-mcp-connectors-now-provision-through-okta-employees-inherit-access-login.htm))

[6] **NAVER 全工程組織部署 Claude Code**：亞洲最大規模企業導入，搭配首爾辦公室開幕同步宣布。([來源](https://www.anthropic.com/news/seoul-office-partnerships-korean-ai-ecosystem))

[7] **Samsung SDS 部署 Claude Cowork + Code**：覆蓋三星電子，LG CNS 同步導入 Claude 給數千名員工。([來源](https://www.anthropic.com/news/seoul-office-partnerships-korean-ai-ecosystem))

[8] **Nexon 工程團隊用 Claude Code 開發線上遊戲**：用於即時服務遊戲的撰寫、審查與部署流程。([來源](https://www.techtimes.com/articles/318637/20260619/anthropic-opens-its-seoul-office-even-us-export-ban-cuts-korean-access-its-top-models.htm))

## 🛠️ 新工具 & 套件

[9] **Claude Code v2.1.183 發布**：移除 `CODEX_HOME`、`GEMINI_HOME` 環境變數與 `gemini-extension.json`，修復 JetBrains 閃爍問題。([來源](https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md))

[10] **Gemini CLI 正式日落（6/18）**：Google 以 Go 語言重寫的閉源 Antigravity CLI（`agy`）取代，改用每週運算配額制。([來源](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/))

[11] **OpenCode 登頂 AI 開發工具排行**：160K+ GitHub stars、750 萬月活開發者，支援 75+ 模型供應商與 LSP 整合。([來源](https://blog.logrocket.com/ai-dev-tool-power-rankings/))

[12] **Willison 發布 Datasette Apps**：可在 Datasette 內以 iframe 沙盒託管完整 HTML+JS 應用，用 Fable 5 + GPT-5.5 打造 API 探索器。([來源](https://simonwillison.net/))

## 💬 社群熱門討論

[13] **SpaceX 600 億美元全股收購 Cursor**：IPO 後數日即簽約，Cursor ARR 已從 2025 初 $1 億飆至 $40 億。([來源](https://techcrunch.com/2026/06/16/spacex-to-acquire-cursor-for-60b-in-stock-days-after-blockbuster-ipo/))

[14] **Fable 5 出口管制第六天**：Anthropic 首爾開幕時承諾模型將於數日內恢復，韓國用戶暫無法存取頂級模型。([來源](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm))

[15] **Claude Code 安全研究持續延燒**：研究者揭露約 50 種繞過權限系統方式，v2.1.128 已修補關鍵漏洞。([來源](https://www.helpnetsecurity.com/2026/06/17/ai-agents-offensive-cyber-operations-claude-codex/))
