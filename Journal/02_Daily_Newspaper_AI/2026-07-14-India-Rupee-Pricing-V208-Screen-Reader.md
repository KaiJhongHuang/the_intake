# AI工作流日報 — 2026-07-14
> 涵蓋範圍：2026-07-13 06:00 ~ 2026-07-14 06:00 (TST)

> 📌 Claude 摘要：Anthropic 正式在印度推出盧比定價，Pro 月費 ₹2,000、Max ₹11,999，印度為全球第二大市場佔 5.8% 用量；v2.1.208 新增螢幕閱讀器模式與 vim insert-mode 自訂按鍵、企業啟動包裝器，v2.1.209 修復背景 session 對話框阻塞；Haiku 4.5 發生 25 分鐘短暫中斷；Friendly Fire 攻擊論文持續引發 HN 安全討論；OpenCut 開源影片編輯器登上 GitHub Trending 第一。

## 🧠 Prompt 技巧 & 使用心得
[1] **v2.1.208 新增 vimInsertModeRemaps**：用戶可在設定中定義兩鍵 insert-mode 序列（如 `jj` 對應 Escape），Vim 模式使用者不再需要外掛即可在 Claude Code 中快速切換模式。([來源](https://github.com/anthropics/claude-code/releases))
[2] **Friendly Fire 攻擊持續發酵**：AI Now Institute 7/8 發布的 PoC 持續在 HN 討論，將惡意指令藏在 README 即可劫持 Claude Code / Codex 自動模式執行惡意程式碼，社群呼籲勿在不信任 repo 開啟全自動模式。([來源](https://thehackernews.com/2026/07/friendly-fire-ai-agents-built-to-catch.html))

## 🔧 工作流整合案例
[3] **Anthropic 印度盧比定價上線**：印度用戶可以 ₹2,000/月訂閱 Pro、₹11,999/月訂閱 Max，印度佔全球 Claude 用量 5.8% 為第二大市場；尚未支援 UPI 付款，落後於 OpenAI 在印度的本地化進度。([來源](https://techcrunch.com/2026/07/13/anthropic-starts-localizing-claude-pricing-for-india-its-biggest-market-after-the-us/))
[4] **v2.1.208 企業啟動包裝器 CLAUDE_CODE_PROCESS_WRAPPER**：新增環境變數讓企業 IT 可在 Claude Code 啟動時注入自訂腳本（合規掃描、VPN 檢查等），搭配滑鼠點擊支援全螢幕選單，降低企業部署摩擦。([來源](https://code.claude.com/docs/en/changelog))

## 🛠️ 新工具 & 套件
[5] **v2.1.208 螢幕閱讀器模式上線**：`claude --ax-screen-reader` 或設定 `CLAUDE_AX_SCREEN_READER=1` 啟用純文字渲染，為視障使用者提供 NVDA/JAWS 相容輸出，是 Claude Code 首個正式無障礙功能。([來源](https://releasebot.io/updates/anthropic/claude-code))
[6] **v2.1.209 修復背景 session 對話框阻塞**：還原過度嚴格的防護邏輯，修復 `claude agents` 背景 session 中 /model 等對話框被封鎖的問題。([來源](https://github.com/anthropics/claude-code/releases))
[7] **OpenCut 登上 GitHub Trending 第一**：開源 CapCut 替代品 OpenCut（MIT 授權）於 7/13 登頂，45.8K 星、Next.js + Rust 核心，支援 web/桌面/行動端，90+ 貢獻者持續重寫中。([來源](https://github.com/OpenCut-app/OpenCut))

## 💬 社群熱門討論
[8] **Haiku 4.5 短暫中斷 25 分鐘**：7/13 約 15:04 UTC 起 Haiku 4.5 出現高錯誤率，影響 claude.ai、API、Cowork 與 Claude Code，15:24 UTC 修復完成，為近期較輕微的基礎設施事件。([來源](https://status.claude.com/))
[9] **HN 熱議 Claude Code 限額 vs Codex 定價**：社群討論 Fable 5 延期搭配 50% 限額加碼的策略，對比 OpenAI Codex 將 frontier 模型直接納入訂閱且限額更高，認為 Anthropic 的計費模式對重度開發者仍不夠友善。([來源](https://news.ycombinator.com/item?id=48883064))
[10] **Business Standard：印度定價含稅仍高於美國**：分析指出印度 Pro ₹2,000 約合 $21（美國 $17）、Max ₹11,999 約合 $125（美國 $100），加上無 UPI 支援，社群認為「本地化」仍有改善空間。([來源](https://www.business-standard.com/technology/tech-news/anthropic-claude-india-pricing-subscription-plans-pro-max-benefits-126071400257_1.html))
