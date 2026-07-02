# AI工作流日報 — 2026-07-02
> 涵蓋範圍：2026-07-01 06:00 ~ 2026-07-02 06:00 (TST)

> 📌 Claude 摘要：今日焦點是 Claude Code 被發現長達三個月在系統提示中以隱寫術標記中國代理路由用戶，Anthropic 於 v2.1.197 靜默移除但未在 changelog 說明，引爆社群信任討論。安全面接連曝光三項 Agent 攻擊向量：Pentera 紅隊透過 Claude Desktop 個人化設定達成 RCE、Mozilla 0DIN 展示透過乾淨 repo 觸發逆向 shell、Sentry MCP agentjacking 達 85% 成功率。生態面 Gemini Spark 登陸 Mac 支援 MCP，正式進入桌面 Agent 戰場。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code 隱寫術追蹤曝光**：v2.1.197 前三個月，Claude Code 在「Today's date is…」行以不可見 Unicode 字元編碼用戶是否經由中國相關代理路由。([來源](https://thereallo.dev/blog/claude-code-prompt-steganography))

[2] **Fable 5 新分類器誤擋常規開發**：重新部署的安全分類器雖封鎖 99% 已知越獄，但對一般程式碼、基礎設施與除錯工作產生更多誤判。([來源](https://www.digitalapplied.com/blog/claude-fable-5-safety-classifier-coding-tradeoffs-2026))

[3] **Sonnet 5 代理能力逼近 Opus 4.8**：官方定位為最具代理性的 Sonnet，工具使用與多步驟推理已接近旗艦級，入門價 $2/$10 per Mtok 至 8/31。([來源](https://www.anthropic.com/news/claude-sonnet-5))

## 🔧 工作流整合案例

[4] **Gemini Spark 登陸 Mac 支援 MCP**：Google 桌面代理 beta 版可存取本機檔案、即時主題追蹤，並支援 MCP 協議擴充第三方工具。([來源](https://techcrunch.com/2026/07/01/gemini-spark-googles-agentic-assistant-is-now-available-on-mac/))

[5] **Claude Code v2.1.197 安全強化**：`claude mcp list/get` 不再自動啟動 repo 自行核准的 .mcp.json 伺服器，未信任工作區顯示「⏸ Pending approval」。([來源](https://releasebot.io/updates/anthropic/claude-code))

[6] **Claude Code Artifacts 進入 beta**：工作階段可產出即時可分享的互動網頁，支援 PR 走讀、儀表板與調查時間軸，限 Team/Enterprise 方案。([來源](https://code.claude.com/docs/en/artifacts))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.197 新增組織預設模型**：管理員可於 org 主控台設定預設模型，`/model` 顯示「Org default」；新增檔案路徑即時補全與可點擊附件。([來源](https://x.com/ClaudeCodeLog/status/2072020231178838419))

[8] **Gemini Spark 整合 Canva、Dropbox、Instacart 等五項服務**：Mac beta 版同步上線第三方應用連接器，可直接設計傳單、分享檔案或訂餐。([來源](https://blog.google/innovation-and-ai/products/gemini-app/gemini-spark-updates-june-2026/))

[9] **Anthropic 移除隱寫術程式碼**：工程師 Thariq Shihipar 稱三月上線用於防範帳號濫用與模型蒸餾，v2.1.197 已刪除但 changelog 未提及。([來源](https://www.theregister.com/ai-and-ml/2026/07/01/anthropic-is-removing-its-covert-code-for-catching-chinese-competitors/5265366))

## 💬 社群熱門討論

[10] **HN 熱議隱寫術事件**：社群質疑 Anthropic 暗中追蹤代理用戶的透明度，討論延伸至開源 CLI 工具是否應有類似審計機制。([來源](https://news.ycombinator.com/item?id=48734373))

[11] **Pentera 紅隊將 Claude Desktop 變雙面間諜**：利用個人化設定注入 base64 編碼指令，達成開發者機器遠端代碼執行。([來源](https://www.theregister.com/security/2026/07/01/red-teamers-turned-claude-desktop-into-a-double-agent-to-do-their-evil-bidding/5264692))

[12] **Mozilla 0DIN 展示毒化 repo 攻擊 Claude Code**：乾淨外觀的 GitHub repo 透過錯誤訊息引導 Claude Code 執行 DNS TXT 載荷，開啟逆向 shell。([來源](https://www.securityweek.com/new-attack-abuses-claude-code-and-harmless-looking-repositories-to-hijack-developer-machines/))

[13] **Agentjacking 經 Sentry MCP 劫持 AI 編碼代理**：Tenet Security 測試 100+ 目標達 85% 成功率，至少 2,388 組織公開暴露可注入的 Sentry DSN。([來源](https://thenewstack.io/agentjacking-sentry-mcp-attack/))
