# AI工作流日報 — 2026-11-16
> 涵蓋範圍：2026-11-15 06:00 ~ 2026-11-16 06:00 (TST)

> 📌 Claude 摘要：Cursor 正式確認 Claude Code 擴充後門源自竊取的 Fireworks AI 密鑰，供應鏈安全議題升溫；IPO 承銷商考慮將定價推高至 $70–$78 區間之上，11/18 定價 11/19 掛牌倒數三天；Google Modern Web Guidance 1.0 穩定版讓編碼代理跳過過時模式。

## 🧠 Prompt 技巧 & 使用心得

[1] **Google Modern Web Guidance 1.0 穩定版**：Chrome 團隊技能包讓編碼代理用原生 Web API 取代過時模式，含 codebase audit 掃描指令。([來源](https://developer.chrome.com/blog/modern-web-guidance-v1))

[2] **Cursor 事件啟示：推論供應商成攻擊面**：竊取第三方推論密鑰即可將惡意擴充推入 IDE 市集，開發者應定期稽核擴充來源。([來源](https://darkreading.com/cyberattacks-data-breaches/devs-trojanized-claude-code-extension-cursor))

## 🔧 工作流整合案例

[3] **Cursor 確認 Fireworks 密鑰為後門根因**：竊取的存取密鑰讓攻擊者植入 SSH 後門至市集 Claude Code 擴充，最多 5000 用戶受影響。([來源](https://dealroom.co/news/172765-cursor-drops-fireworks-ai-after-a-leaked-vendor-key-let-hackers-steal-da/))

[4] **IPO 承銷商權衡區間上方定價**：帳面多倍超額認購後銀行家考慮將 ANT 推高至 $78 以上，估值可達 $1.5T，11/18 定價。([來源](https://aiweekly.co/alerts/anthropic-ipo-oversubscribed-bankers-weigh-15t-valuation-nvidia-and-google-each))

[5] **Cursor 已將全部推論流量移離 Fireworks**：撤銷密鑰並斷開所有共享資料集，生產系統與簽章金鑰未受影響，最後攻擊活動為 11/1。([來源](https://www.datastudios.org/post/cursor-security-incident-update-fireworks-access-key-inference-moved))

## 🛠️ 新工具 & 套件

[6] **Ludo Toolbox 開源 32 項 CLI 遊戲素材工具**：可被 Claude Code 與 Codex 直接呼叫，`npm install -g @ludoai/cli` 後一鍵安裝全部技能。([來源](https://www.gamespress.com/en-US/Ludo-releases-free-open-source-toolbox-that-lets-AI-coding-agents-prep))

[7] **Claude Dispatch 退役延遲 RCE 仍可利用**：Forever Security 揭露瀏覽器擴充可透過 Dispatch 在桌面端執行程式碼，原定十月底退役但仍運作中。([來源](https://thehackernews.com/2026/11/malicious-browser-extensions-could-use.html))

## 💬 社群熱門討論

[8] **Fireworks AI 二度遭駭波及 Notion**：不足 1% Notion 工作區受影響，部分 AI 聊天記錄遭存取，Notion 已斷開並刪除所有 Fireworks 資料。([來源](https://www.esecurityplanet.com/threats/news-fireworks-ai-second-breach-notion-chat-transcripts/))

[9] **六大券商搶 IPO 散戶配額**：Schwab、Fidelity、Robinhood、SoFi、E*TRADE、Trade-PMR 獲配額，Robinhood CFO 稱競爭為「搶食大戰」。([來源](https://stocktwits.com/news-articles/markets/equity/robinhood-battles-rival-brokers-to-secure-retail-allocations-ahead-of-anthropic-ipo/cNGa9dDR9Pt))
