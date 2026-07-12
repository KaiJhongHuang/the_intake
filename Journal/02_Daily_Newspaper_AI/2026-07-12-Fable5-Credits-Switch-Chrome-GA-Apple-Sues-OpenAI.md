# AI工作流日報 — 2026-07-12
> 涵蓋範圍：2026-07-11 06:00 ~ 2026-07-12 06:00 (TST)

> 📌 Claude 摘要：Fable 5 訂閱期限今日午夜到期，明日起全面轉為 usage credits 計費（$10/$50 per M tokens）；v2.1.207 同步將 Chrome 整合從 Preview 推至正式 GA、子代理預設改為背景非同步執行；Apple 以商業機密竊取為由控告 OpenAI 硬體長 Tang Tan 等人；Gemini 3.5 Pro 洩漏指向 7/17 發布，搭載 2M context 與 Deep Think 推理；MCP 2026-07-28 RC 宣布協議走向 stateless 核心。

## 🧠 Prompt 技巧 & 使用心得
[1] **子代理預設背景執行提升效率**：v2.1.207 起子代理預設在背景運行，主對話不再暫停等待，完成後自動通知；可按 Ctrl+B 手動背景化正在執行的任務。([來源](https://code.claude.com/docs/en/agents))
[2] **Desktop 內建瀏覽器免切換視窗**：Claude Code Desktop 內建沙箱瀏覽器（Cmd/Ctrl+Shift+B），可直接查文件、測試 UI、填表單，省去在終端與瀏覽器間來回切換。([來源](https://9to5mac.com/2026/07/10/anthropic-highlights-claude-codes-in-app-browser-on-the-desktop/))

## 🔧 工作流整合案例
[3] **Chrome 整合正式脫離 Preview**：Claude in Chrome 對所有直接 Anthropic 付費方案用戶正式 GA，Claude Code 可透過擴充套件開分頁、點擊、填表單、讀 console log 並共享登入狀態。([來源](https://www.engadget.com/ai/claudes-chrome-plugin-is-now-available-to-all-paid-users-221024295.html))
[4] **Claude Desktop Linux Beta 上線**：支援 Ubuntu 22.04+ 與 Debian 12+（x64/arm64），提供與 macOS/Windows 相同的 Chat、Cowork、Claude Code 體驗，透過 apt 倉庫安裝自動更新。([來源](https://www.omgubuntu.co.uk/2026/07/claude-desktop-linux-beta))
[5] **MCP 2026-07-28 RC 協議大改**：新規範轉向 stateless 核心，取消 handshake 與 session ID；新增 Extensions 框架、MCP Apps（沙箱 HTML UI）、Tasks 長時間任務管理，7/28 正式發布。([來源](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/))

## 🛠️ 新工具 & 套件
[6] **Fable 5 今日到期轉 usage credits**：7/12 午夜 PT 後 Fable 5 脫離訂閱方案，改為預付 usage credits 計費：$10/M input、$50/M output，為 Opus 4.8 的兩倍價格。([來源](https://fable5.app/fable-5-usage-limits/))
[7] **Gemini 3.5 Pro 洩漏 7/17 上線**：Google 傳以全新 Gemini 3 底層重訓，搭載 2M token context 與 Deep Think 推理層，前端生成與 SVG 能力大幅提升；7/24 為備援日期。([來源](https://hackernoon.com/google-delays-gemini-35-pro-to-july-17-the-strategic-play-behind-the-scrapped-base-model))
[8] **MCP Servers 2026.7.10 維護版**：Filesystem、Time、Fetch、Git 等常用 MCP 伺服器更新，修復穩定性與相容性問題。([來源](https://www.skakarh.com/blog/mcp-servers-2026-7-10-released))

## 💬 社群熱門討論
[9] **Apple 控告 OpenAI 竊取商業機密**：Apple 於北加州聯邦法院起訴，指控 OpenAI 硬體長 Tang Tan（前 Apple VP）指使面試者洩露機密，並協助離職員工規避安全流程。([來源](https://www.cnbc.com/2026/07/10/apple-openai-lawsuit-trade-secrets.html))
[10] **Fed 成立 AI 經濟研究委員會**：聯準會宣布首個 AI 專責研究單位，由 a16z 共同創辦人 Andreessen 共同主持，研究 AI 對就業、生產力與貨幣政策的影響。([來源](https://www.buildfastwithai.com/blogs/ai-news-today-july-12-2026))
[11] **Reflect 使用儀表板持續引發討論**：TechCrunch 評論 Anthropic 以「數位健康」包裝使用數據收集，社群對隱私與行為引導的平衡看法分歧。([來源](https://techcrunch.com/2026/07/09/anthropics-new-claude-feature-is-quietly-selling-you-on-ai/))
