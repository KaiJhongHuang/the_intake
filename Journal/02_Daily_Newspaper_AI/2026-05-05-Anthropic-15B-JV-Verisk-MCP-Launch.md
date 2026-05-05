# AI工作流日報 — 2026-05-05
> 涵蓋範圍：2026-05-04 06:00 ~ 2026-05-05 06:00 (TST)

> 📌 Claude 摘要：Anthropic 大動作跨入企業服務，與華爾街巨頭組 $1.5B 合資公司；同日 Verisk 保險 MCP 連接器上線，顯示 MCP 生態正從開發者工具擴展至垂直產業。Claude Code v2.1.127 持續打磨 plugin 與 MCP 穩定性。

## 🧠 Prompt 技巧 & 使用心得

[1] **規劃優先工作流**：Reddit 社群共識——先讓 Claude 出計畫、人工標註修正、再送回修改，比一次性指令品質高。([來源](https://read.earlystagegrowth.com/p/14-claude-skills-and-workflows-that))

[2] **短 session 勝長 marathon**：r/ClaudeAI 多篇討論建議每次聚焦單一任務，自主工作前先 commit checkpoint。([來源](https://www.morphllm.com/claude-code-reddit))

[3] **datasette-llm 0.1a7**：Simon Willison 發布新版，可為特定模型設定預設參數（如 temperature 0.5），簡化批次操作。([來源](https://simonwillison.net/2026/May/5/datasette-llm/))

## 🔧 工作流整合案例

[4] **Anthropic × Blackstone/Goldman $1.5B 合資**：不做顧問，直接派工程師進企業重設工作流並整合 Claude，瞄準 PE 投資組合公司。([來源](https://www.anthropic.com/news/enterprise-ai-services-company))

[5] **Verisk MCP 連接器上線**：保險業可透過自然語言查詢 ISO 損失成本趨勢與 XactRestore 估價，每份估價省 30 分鐘至 2 小時。([來源](https://www.globenewswire.com/news-release/2026/05/05/3288003/0/en/Verisk-Brings-Its-Trusted-Analytics-and-Generative-AI-Capabilities-Directly-into-Anthropic-s-Claude.html))

[6] **AI 咖啡店營運實測**：Andon Labs 用 Gemini 代理人「Mona」管理斯德哥爾摩實體咖啡店，兩週營收 44,000 SEK，但也暴露 AI 採購失控問題。([來源](https://andonlabs.com/blog/ai-cafe-stockholm))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.127**：--plugin-dir 支援 .zip；/mcp 顯示工具數量；修正平行 shell 呼叫失敗取消兄弟任務的 bug。([來源](https://releasebot.io/updates/anthropic/claude-code))

[8] **llm-echo 0.5a0**：Simon Willison 發布 LLM debug 用 echo 模型插件，方便測試 pipeline 不消耗 token。([來源](https://simonwillison.net/2026/May/5/llm-echo/))

[9] **claude project purge 指令**：新增清理特定專案所有 Claude Code 狀態（transcript、task、file history）的 CLI 命令。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 💬 社群熱門討論

[10] **Claude API 5/4 短暫中斷**：Opus 4.5、Sonnet 4.5、Opus 4.7 皆出現 elevated errors，已於 5/5 前修復。([來源](https://news.ycombinator.com/item?id=47938097))

[11] **AI coding agent 9 秒刪資料庫**：HN 熱議自主代理風險，強調 sandbox 與權限邊界設計的重要性。([來源](https://news.ycombinator.com/item?id=47924586))

[12] **mattpocock/skills 持續爆紅**：21 個結構化 Claude Code 技能已累積 20.4K 星，涵蓋 TDD、PRD、架構改進等模板。([來源](https://github.com/mattpocock/skills))
