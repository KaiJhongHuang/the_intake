# AI工作流日報 — 2026-08-25
> 涵蓋範圍：2026-08-24 06:00 ~ 2026-08-25 06:00 (TST)

> 📌 Claude 摘要：v2.1.243 一口氣加入無密鑰登入、loop token 明細、組織合約價格覆寫與模型選擇器自訂；v2.1.245 緊急修復 glibc 2.44 開機崩潰；Free-Claude-Code 開源專案整合九款代理與 50 家免費供應商；Google Cloud 報告指 83% 組織需升級基礎設施才能安全部署自主代理。

## 🧠 Prompt 技巧 & 使用心得

[1] **v2.1.243 新增 /usage loop 明細**：/usage 增加 Loops breakdown，顯示每個 loop 的執行次數、總 token、每次平均 token 與最後執行時間，一眼抓出耗資源任務。([來源](https://www.havoptic.com/tools/claude-code))

[2] **promptCacheTtl 設定開放自訂**：v2.1.243 新增 promptCacheTtl 與 subagentPromptCacheTtl，API key 與雲端用戶可分別設定主代理與子代理的 prompt cache 持續時間。([來源](https://www.gradually.ai/en/changelogs/claude-code/))

[3] **Willison 分享「你的執行檔就是 SQLite 資料庫」**：轉載 Farid Zakaria 文章，展示 Linux 上將 ELF 執行檔同時作為 SQLite 資料庫的巧妙模式。([來源](https://simonwillison.net/2026/Aug/24/your-executable-is-a-sqlite-database/))

## 🔧 工作流整合案例

[4] **v2.1.243 無密鑰登入上線**：/login 新增「Sign in with your Console account」選項，不允許 API key 的組織也可直接透過 Anthropic Console 登入 Claude Code。([來源](https://www.gradually.ai/en/changelogs/claude-code/))

[5] **modelPricing 管理設定覆寫清單價**：組織可設定合約談定的每模型單價，/cost 計算將自動使用實際費率而非官方定價。([來源](https://www.gradually.ai/en/changelogs/claude-code/))

[6] **Google Cloud 報告：代理安全是規模化首要門檻**：State of AI Infrastructure 報告指 83% 組織需基礎設施升級，建議採用平台級治理、任務級出處追蹤與 human-in-the-loop 檢查。([來源](https://cloud.google.com/blog/products/compute/state-of-ai-infrastructure-report-overview/))

## 🛠️ 新工具 & 套件

[7] **v2.1.245 修復 glibc 2.44 啟動崩潰**：Arch Linux、CachyOS、Fedora Rawhide 等發行版因 glibc 2.44 導致的開機 crash 已修復。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.245))

[8] **Free-Claude-Code 開源：九代理 50 供應商 1.3B 免費 token**：整合 Claude Code、Codex、OpenCode 等九款代理，自動切換供應商，支援終端、IDE、行動與語音。([來源](https://github.com/alishahryar1/free-claude-code))

[9] **Apache Maka 0.1.11 進入 Apache 孵化器**：local-first AI 代理工作區，所有 model message、tool call、權限決策皆寫入 append-only log，24 名貢獻者合併 375 PR。([來源](https://github.com/apache/maka))

## 💬 社群熱門討論

[10] **編碼代理排行洗牌：雙代理棧成為主流**：Morphllm 八月排名 Claude Code 第一、Codex 第二；多數團隊已採前沿代理搭配開源代理的雙棧策略。([來源](https://www.morphllm.com/best-ai-coding-agents-2026))

[11] **v2.1.243 新增 modelPicker 自訂模型選單**：可設定有序、帶標籤的模型清單，讓 /model 選擇器只顯示團隊核准的模型。([來源](https://www.havoptic.com/tools/claude-code))

[12] **HN 討論：速度與效率已取代能力成為 LLM 真正差異化因素**：開發者社群認為用戶不願為線性改進等待指數級時間，成本與回應速度才是決勝點。([來源](https://news.ycombinator.com/item?id=49348751))
