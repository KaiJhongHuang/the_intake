# AI工作流日報 — 2026-10-15
> 涵蓋範圍：2026-10-14 06:00 ~ 2026-10-15 06:00 (TST)

> 📌 Claude 摘要：v2.1.299 釋出修補閘道金鑰外洩與新增閒置壓縮；Anthropic 公開 Scion 版控系統取代 Git 應對日合併三萬次；IPO 投資人日首度披露 Q3 營收 $16.8B 季增 45%；威脅報告揭葉門武裝用 Claude 開發飛彈 GNC 軟體引發安全辯論。

## 🧠 Prompt 技巧 & 使用心得

[1] **v2.1.299 新增閒置壓縮**：終端閒置約 54 分鐘後自動壓縮 200K+ token 對話，避免快取過期後全量重處理。([來源](https://dev.classmethod.jp/en/articles/20261014-cc-updates-v2-1-299/))

[2] **v2.1.299 修正 @-提及行為**：新增 CLAUDE_CODE_DISABLE_FILE_MENTIONS 變數，讓 Claude 收路徑而非全文，用工具自行讀取。([來源](https://dev.classmethod.jp/en/articles/20261014-cc-updates-v2-1-299/))

[3] **Anthropic 中期選舉投票資訊上線**：Claude.ai 偵測到投票相關問題時顯示選舉橫幅，導向 TurboVote 非黨派資源。([來源](https://aiweekly.co/node/5467))

## 🔧 工作流整合案例

[4] **Anthropic 公開 Scion 版控系統取代 Git**：七名工程師五個月建成，處理日合併從五月 2,500 次飆至九月 30,000 次，同步推出 Antique 審查工具。([來源](https://simonwillison.net/2026/Oct/13/redesigning-source-control-at-anthropic/))

[5] **Scion 設計假設客戶端永遠在線**：以 changeset 寫入 WAL 取代 git commit，伺服器端處理歷史與合併，大幅降低 CPU 與記憶體用量。([來源](https://alphasignal.ai/news/anthropic-ditched-git-and-built-scion-after-claude-caused-12x-merge-surge))

[6] **IPO 投資人日首度披露財務數據**：Reuters 引出席者稱 Q3 營收 $16.8B 季增 45%，調整基礎已獲利；2025 全年營收 $4.6B。([來源](https://www.investing.com/news/stock-market-news/anthropics-q3-revenue-surges-45-to-nearly-17-billion-4950208))

## 🛠️ 新工具 & 套件

[7] **v2.1.299 釋出 190 項 CLI 變更**：修補閘道 API 金鑰外洩至 Anthropic 伺服器、修正 UTF-16/Shift-JIS/GBK 編碼轉換、plugin eval 新增 --disallow-tools。([來源](https://mixed-news.com/en/claude-code-2-1-299-third-party-gateway-api-key-sent-to-anthropic/))

[8] **v2.1.299 閘道串流逾時延長至 300 秒**：原 180 秒靜默中斷改為 300 秒，並修正近 200K token 時閘道特定模型名導致 session 結束。([來源](https://dev.classmethod.jp/en/articles/20261014-cc-updates-v2-1-299/))

[9] **morluto/rea 登 GitHub Trending 第一**：用代理逆向工程任何目標，從 app 行為到原生二進位檔，連續多日佔榜首。([來源](https://trendshift.io/))

## 💬 社群熱門討論

[10] **Anthropic 威脅報告揭葉門武裝用 Claude 開發飛彈**：九月報告稱北葉門武裝用 Claude Code 開發導引火箭與彈道飛彈 GNC 軟體，試射失敗後回頭問 Claude 原因。([來源](https://www.business-standard.com/technology/artificial-intelligence/houthis-used-claude-to-develop-missiles-test-fired-rocket-anthropic-126101300180_1.html))

[11] **Codex CLI daemon 爭議持續發酵**：Gigazine 報導 0.157.0 預設安裝持久自更新守護程序，社群要求改為 opt-in，OpenAI 尚未正式回應是否變更預設。([來源](https://gigazine.net/gsc_news/en/20261015-codex-cli-background-daemon/))

[12] **Scion 不開源引社群兩極反應**：Anthropic 明確表示 Scion 非通用 Git 替代品且不會公開釋出，HN 討論聚焦代理規模是否真需拋棄 Git。([來源](https://www.theregister.com/devops/2026/10/13/anthropic-reinvents-source-control-as-claude-floods-the-world-with-code/5302943))
