# AI工作流日報 — 2026-05-19
> 涵蓋範圍：2026-05-18 06:00 ~ 2026-05-19 06:00 (TST)

> 📌 Claude 摘要：Google I/O 大量發表衝擊 AI 格局，Anthropic 同日以 MCP tunnels 與 Mythos 開放回應，代理計費模式也開始轉向消費制。

## 🧠 Prompt 技巧 & 使用心得

[1] **Simon Willison PyCon US 閃電演講**：五分鐘回顧半年 LLM 變遷，指出最佳模型六個月內五度易主。([來源](https://simonwillison.net/2026/May/19/5-minute-llms/))

[2] **Claude cache diagnostics 公測**：API 新增 diagnostics 欄位，可比對前後請求找出 prompt cache miss 確切斷點。([來源](https://platform.claude.com/docs/en/build-with-claude/cache-diagnostics))

[3] **Google 開發者論壇坦言差距**：I/O 前夕社群貼文指 70% 開發者偏好 Claude 處理實際產出工作。([來源](https://discuss.ai.google.dev/t/a-serious-wake-up-call-before-i-o-why-power-users-are-quietly-abandoning-gemini-for-claude-and-chatgpt/145215))

## 🔧 工作流整合案例

[4] **MCP tunnels 研究預覽上線**：Managed Agents 可透過加密出站通道連接私有 MCP server，無需開放防火牆。([來源](https://claude.com/blog/claude-managed-agents-updates))

[5] **自架沙箱公測**：Managed Agents 工具執行可改在客戶端基礎設施運行，支援 Cloudflare、Modal、Vercel。([來源](https://the-decoder.com/anthropic-adds-self-hosted-sandboxes-and-mcp-tunnels-to-claude-managed-agents/))

[6] **n8n-mcp 突破兩萬星**：用自然語言讓 Claude 直接建構 n8n 自動化流程，五分鐘內完成部署。([來源](https://github.com/czlonkowski/n8n-mcp))

[7] **OpenAI × Dell 將 Codex 帶入企業內網**：5/18 宣布 Codex 整合 Dell AI Data Platform，支援混合雲與地端部署。([來源](https://openai.com/index/dell-codex-enterprise-partnership/))

## 🛠️ 新工具 & 套件

[8] **Google I/O：Gemini 3.5 Flash 發布**：預設模型升級，程式碼與 agent 基準超越 3.1 Pro，支援長時間任務。([來源](https://www.cnbc.com/2026/05/19/google-ai-ultra-gemini-spark-omni.html))

[9] **Gemini Omni Flash 上線**：任意輸入生成影片，搭載 SynthID 浮水印，已登陸 Gemini app 與 YouTube Shorts。([來源](https://www.newsbytesapp.com/news/science/google-updates-gemini-model-family-at-i-o-2026/story))

[10] **Gemini Spark agent 預覽**：24/7 雲端個人代理，可串聯 Gmail、Docs、Canva、OpenTable 等服務執行多步驟任務。([來源](https://techcrunch.com/2026/05/19/google-introduces-gemini-spark-a-24-7-agentic-assistant-with-gmail-integration/))

[11] **Google AI Ultra 訂閱 $100/月**：新增頂級訂閱層，面向開發者與重度使用者。([來源](https://www.androidpolice.com/google-gemini-plan-takes-chatgpt-pro-claude-max/))

## 💬 社群熱門討論

[12] **Mythos 保密令解除**：Anthropic 允許 Glasswing 夥伴公開分享漏洞發現，可通知監管機關與開源維護者。([來源](https://gizmodo.com/anthropic-is-loosening-the-secrecy-around-claude-mythos-so-findings-can-be-shared-broadly-2000760355))

[13] **Agent 計費轉消費制**：6/15 起 Claude 訂閱區分聊天與程式化用量，Pro 用戶每月獲 $20 API 額度。([來源](https://www.infoworld.com/article/4171274/anthropic-puts-claude-agents-on-a-meter-across-its-subscriptions.html))

[14] **HN 熱議 Gemini vs Claude**：社群認為 Google 以 Spark 正面迎戰 Claude Agent 生態，但程式碼品質仍有差距。([來源](https://techcrunch.com/2026/05/19/google-updates-its-gemini-app-to-take-on-chatgpt-and-claude/))
