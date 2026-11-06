# AI工作流日報 — 2026-11-05
> 涵蓋範圍：2026-11-04 06:00 ~ 2026-11-05 06:00 (TST)

> 📌 Claude 摘要：Anthropic 開源 FlashProve 可驗證推論原型搶佔信任基建，Claude Code v2.1.318 修復登入與背景代理問題，B2TRADER 成首個整合 MCP 的交易終端，期中選舉日國會仍無聯邦 AI 立法。

## 🧠 Prompt 技巧 & 使用心得

[1] **FlashProve 可驗證推論開源**：Anthropic 以 zkSNARK 證明特定模型權重產出特定回覆，在 H100 達 110 tok/s，Apache 2.0 釋出。([來源](https://www.anthropic.com/research/provable-inference))

[2] **Willison 本地跑 Qwen 3.8 27B 解讀權重**：Simon Willison 在筆電本地執行 Qwen 3.8 27B，實測模型權重解讀能力。([來源](https://simonwillison.net/notes/))

[3] **Willison 評 Apple Core AI 本地推論前景**：稱新框架是開發者善用 Apple 硬體跑本地模型的重要一步。([來源](https://simonwillison.net/notes/))

## 🔧 工作流整合案例

[4] **B2TRADER 整合 MCP 交易代理**：B2BROKER 為交易終端加入 MCP 支援，透過 OAuth 2.1 連接 Claude 或 ChatGPT，提供唯讀與完整交易兩種存取層級。([來源](https://www.globenewswire.com/news-release/2026/11/04/3395078/0/en/b2broker-expands-b2trader-ai-strategy-with-mcp-trading-agents-and-in-terminal-chat.html))

[5] **Copilot Connectors 公開預覽持續推進**：GitHub MCP 連接器涵蓋 Slack、Sentry、Notion 等 26 項服務，跨 CLI、VS Code、Mobile 統一存取。([來源](https://github.blog/changelog/2026-10-28-connect-your-tools-to-copilot-without-all-the-setup))

## 🛠️ 新工具 & 套件

[6] **Claude Code v2.1.318 釋出**：新增登入到期時間顯示（loginExpiresAt）、修復 --continue 對話遺失、macOS 多 Bash 卡頓，IDE 終端不再自動安裝擴充。([來源](https://www.npmjs.com/package/@anthropic-ai/claude-code?activeTab=versions))

[7] **FlashProve 原型 70-95× 開銷**：目前僅測試 Llama 4 Maverick 開放權重模型，尚未部署於 Claude，Anthropic 稱無近期商用計畫。([來源](https://www.helpnetsecurity.com/2026/11/04/anthropic-flashprove-provable-inference/))

[8] **LLM 0.37 加入 GPT-6.1 模型項目**：Willison 的 LLM CLI 新版支援 GPT-6.1 Sol/Terra 及自訂 OpenAI 相容端點，12 位貢獻者多數靠 AI 輔助。([來源](https://simonwillison.net/notes/))

## 💬 社群熱門討論

[9] **期中選舉日國會仍無 AI 立法**：美國期中選舉投票，國會未通過任何聯邦 AI 監管法案，民調顯示多數選民認為政府做得太少。([來源](https://katv.com/news/nation-world/congress-set-to-enter-midterms-elections-without-response-to-ai-threats-democrats-republicans-house-senate))

[10] **IPO 路演最快 11/10 啟動**：S-1 提交滿 15 日限制 11/10 屆滿，Bloomberg 報導行銷最快當週展開，感恩節前掛牌。([來源](https://www.implicator.ai/anthropic-could-start-ipo-roadshow-week-of-nov-9-putting-debut-before-thanksgiving/))

[11] **S-1/A 修訂揭遞迴自我改進風險**：修訂版招股書警告 AI 可能很快達到快速自主進步門檻，但現有模型尚未觸及。([來源](https://www.benzinga.com/markets/private-markets/26/11/62815173/safety-risk-anthropic-warns-ai-could-soon-start-improving-itself-at-dramatically-accelerated-pace-2026-last-normal-year-says-expert))
