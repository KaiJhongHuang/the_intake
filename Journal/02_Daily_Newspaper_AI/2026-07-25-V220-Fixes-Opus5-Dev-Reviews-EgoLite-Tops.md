# AI工作流日報 — 2026-07-25
> 涵蓋範圍：2026-07-24 06:00 ~ 2026-07-25 06:00 (TST)

> 📌 Claude 摘要：Opus 5 發布首日開發者實測結果陸續出爐，CodeRabbit 指出 code review 精準度提升但 nitpick 倍增；v2.1.220 修復插件載入回歸、token 計費重複計算等六項 bug；GitHub MCP Server 率先支援即將於 7/28 生效的無狀態規範 RC；ego lite AI 代理瀏覽器衝上 GitHub Trending 第一。

## 🧠 Prompt 技巧 & 使用心得

[1] **Opus 5 code review 實測**：CodeRabbit 評測顯示 Opus 5 產出更精準可操作的審查意見，但 nitpick 數量為基線四倍，建議搭配 effort 撥盤調低以控制雜訊。([來源](https://www.coderabbit.ai/blog/opus-5-model-review))

[2] **Mollick：提示技巧已失效，管理才是核心**：Ethan Mollick 7/7 文章指出 prompting trick 效益遞減，定義目標、產出格式、評估標準與測試方法才是 AI 協作的關鍵技能。([來源](https://explainx.ai/blog/ethan-mollick-wharton-prompting-science-specs-not-tricks-2026))

[3] **Opus 5 對齊分數最低**：Anthropic 行為審計顯示 Opus 5 整體失準行為分數 2.30，為 Claude 全系列最低，優於 Opus 4.8、Sonnet 5 與 Fable 5。([來源](https://www.buildfastwithai.com/blogs/claude-opus-5-review))

## 🔧 工作流整合案例

[4] **Claude Code v2.1.220 發布**：修復插件載入回歸（自 v2.1.181）、長時間 session feature flag 過期、/ultrareview 無 merge base 時拒絕執行、token 遙測重複計算等六項 bug。([來源](https://www.gradually.ai/en/changelogs/claude-code/))

[5] **GitHub MCP Server 搶先支援新規範**：GitHub MCP Server 於 7/23 宣布支援 7/28 即將生效的 MCP 無狀態規範 RC，移除 session 與 initialize 階段，可直接部署在一般負載平衡器後。([來源](https://github.blog/changelog/2026-07-23-github-mcp-server-supports-the-next-mcp-specification/))

[6] **DeepSeek API 遷移截止**：7/24 起 deepseek-chat 與 deepseek-reasoner 舊端點停止回應，開發者須切換至新版 API；FLI 安全指數同日給予 DeepSeek F 等級。([來源](https://www.techtimes.com/articles/319877/20260708/gemini-35-pro-targets-july-17-deepseeks-july-24-deadline-hits-developers-now.htm))

## 🛠️ 新工具 & 套件

[7] **ego lite 登 GitHub Trending 第一**：Chromium 核心 AI 代理瀏覽器，可一鍵匯入 Chrome 設定，每個代理在獨立 Space 中操作，DOM 變更時 @N ref 保持穩定。([來源](https://runtimewire.com/article/ego-lite-reaches-github-trending-1-marking-a-surge-in-ai-agent-tool-interest))

[8] **MCP 無狀態規範 RC 定於 7/28 發布**：新規範移除 session 與 initialize、新增 Extensions 框架與 Tasks 長任務機制、加入 MCP Apps 伺服器端 UI、強化 OAuth 授權流程。([來源](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/))

[9] **OmniRoute 免費 AI 閘道**：單一端點路由至 231+ 供應商（50+ 免費），支援 Claude Code、Codex、Cursor、Copilot 等工具直接連接多模型池。([來源](https://debate.tellodb.com/blog/top-ai-tools-launched-2026-july))

## 💬 社群熱門討論

[10] **Opus 5 IPO 戰略定位**：多家媒體分析 Opus 5 發布時機與年底 IPO 計畫密切相關，以半價提供接近 Fable 5 性能的策略意在擴大企業採用基礎。([來源](https://ca.finance.yahoo.com/news/anthropic-debuts-opus-5-model-as-company-preps-for-ipo-later-this-year-170000070.html))

[11] **FLI 安全指數全體偏低**：夏季評比最高為 Anthropic C+，OpenAI 與 Google DeepMind 得 C，Meta D+，xAI、DeepSeek、Mistral 不及格，無一實驗室超過 C+。([來源](https://futureoflife.org/ai-safety-index-summer-2026/))

[12] **Claude Code 登 AI 編碼工具榜首**：七月底最新排名因 Opus 5 與子代理模型控制功能將 Claude Code 推至第一，Codex 降至第二，Copilot 與 Cursor 分據三四位。([來源](https://mightybot.ai/blog/coding-ai-agents-for-accelerating-engineering-workflows/))
