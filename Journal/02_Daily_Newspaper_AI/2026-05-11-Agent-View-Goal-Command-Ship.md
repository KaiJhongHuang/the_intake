# AI工作流日報 — 2026-05-11
> 涵蓋範圍：2026-05-10 06:00 ~ 2026-05-11 06:00 (TST)

> 📌 Claude 摘要：Claude Code v2.1.139 帶來 Agent View 與 /goal 自主完成指令，是本日最重要更新；社群持續討論 HTML 取代 Markdown 的輸出策略與 Anthropic 80 倍營收暴增後的算力佈局。

## 🧠 Prompt 技巧 & 使用心得
[1] **HTML 取代 Markdown 輸出**：Anthropic 工程師 Thariq 提倡以 HTML 取代 Markdown，可嵌入導覽、摺疊區塊與互動元素。([來源](https://simonwillison.net/2026/May/8/unreasonable-effectiveness-of-html/))
[2] **Context Engineering 優先於 Prompt 技巧**：2026 社群共識——任務前建好 CLAUDE.md 等持久上下文檔，比精雕 prompt 更有效。([來源](https://www.the-ai-corner.com/p/claude-best-practices-power-user-guide-2026))
[3] **Interview-First 模式處理模糊任務**：先讓 Claude 訪談你，釐清邊界與取捨，再進入實作階段。([來源](https://code.claude.com/docs/en/best-practices))

## 🔧 工作流整合案例
[4] **Claude Code v2.1.139 發布 Agent View**：新增 `claude agents` 儀表板，一覽所有執行中、等待輸入與已完成的 session。([來源](https://claude-world.com/articles/claude-code-21139-release/))
[5] **v2.1.139 新增 /goal 指令**：設定完成條件後 Claude 自主多輪迭代直到達標，附即時面板顯示耗時與 token 用量。([來源](https://claude-world.com/articles/claude-code-21139-release/))
[6] **n8n-MCP 讓 Claude 直接建構自動化工作流**：Claude 可讀寫 n8n 實例，從零建立、部署並除錯 workflow。([來源](https://blog.n8n.io/n8n-mcp-server/))

## 🛠️ 新工具 & 套件
[7] **Ruflo 多代理編排平台突破 15K 星**：為 Claude Code 加上分散式 swarm、自學記憶與聯邦通訊，SWE-bench 解題率 84.8%。([來源](https://github.com/ruvnet/ruflo))
[8] **CyberSecQwen-4B 開源資安專用模型**：4B 參數即可在消費級 GPU 本地運行，CVE 分類準確度逼近 8B 模型。([來源](https://huggingface.co/blog/lablab-ai-amd-developer-hackathon/cybersecqwen-4b))
[9] **Gemini 3.1 Flash-Lite 正式 GA**：Google 最快最省模型，延遲降 2.5 倍，每百萬 input token 僅 $0.25。([來源](https://cloud.google.com/blog/products/ai-machine-learning/gemini-3-1-flash-lite-is-now-generally-available))

## 💬 社群熱門討論
[10] **Anthropic 80 倍營收成長達 $300 億年化**：Dario Amodei 稱成長「太瘋狂」，已租用 SpaceX Colossus 與 Akamai $18 億合約補算力。([來源](https://venturebeat.com/technology/anthropic-says-it-hit-a-30-billion-revenue-run-rate-after-crazy-80x-growth))
[11] **HN 熱議「HTML 的不合理有效性」**：正方讚互動性與視覺密度，反方憂安全與可審查性下降，討論超 500 則留言。([來源](https://news.ycombinator.com/item?id=48071940))
[12] **Uber 四個月燒光全年 AI 預算用於 Claude Code**：引發企業 AI 支出控管討論。([來源](https://news.ycombinator.com/item?id=47976415))
