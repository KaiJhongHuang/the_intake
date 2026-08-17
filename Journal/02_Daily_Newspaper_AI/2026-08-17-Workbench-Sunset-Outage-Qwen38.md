# AI工作流日報 — 2026-08-17
> 涵蓋範圍：2026-08-16 06:00 ~ 2026-08-17 06:00 (TST)

> 📌 Claude 摘要：Workbench legacy 今日正式退場，未匯出的 prompt 資產永久消失；Claude 平台 8/16 晚間中斷 36 分鐘影響認證層；Willison 實測 Qwen 3.8 27B 預設推理過度 21 分鐘燒 22K token，建議關閉推理；OmniRoute 單月爆增三萬星成 GitHub 最速 AI 閘道。

## 🧠 Prompt 技巧 & 使用心得
[1] **Willison 實測 Qwen 3.8 27B 推理過度**：預設 xhigh 設定下簡單 SVG prompt 耗時 21 分鐘燒 22,276 推理 token，關閉推理後 137 秒即完成同等品質輸出。([來源](https://simonwillison.net/2026/Aug/16/qwen-38-27b/))

[2] **Qwen 3.8 27B 仍成功驅動 Pi coding agent**：儘管推理過度，該模型仍能回答程式碼庫認證問題並撰寫可運作的 Python 轉檔腳本，27B 參數適合筆電本地運行。([來源](https://simonwillison.net/2026/Aug/16/qwen-38-27b/))

## 🔧 工作流整合案例
[3] **Workbench legacy 今日正式退場**：儲存的 prompt、變數與 eval 設定永久消失無恢復路徑，三支實驗性 prompt API 同步下線，Anthropic 將 Workbench 改為無狀態試用介面。([來源](https://www.techtimes.com/articles/324669/20260817/anthropic-kills-claude-workbench-today-saved-prompts-gone-api-pipelines-broken.htm))

[4] **Compliance API 擴展至 Cowork 與 Claude Code**：Enterprise beta 上線，安全團隊可透過統一 API 拉取桌面、網頁、CLI 的 session 內容與中繼資料供稽核。([來源](https://claude.com/blog/compliance-api-cowork-and-claude-code))

[5] **Claude Code Desktop 新增 auto-continue 勾選框**：8/14 發布，用量限制解除後自動恢復中斷的 session，免手動重新提示。([來源](https://www.explainx.ai/blog/claude-code-desktop-auto-continue-usage-limit-august-2026))

## 🛠️ 新工具 & 套件
[6] **OmniRoute 單月爆增三萬星達 48K**：MIT 授權本地 AI 閘道，一端點代理 340+ 供應商含 90+ 免費層，RTK+Caveman 壓縮節省 15-95% token，配額感知自動切換。([來源](https://github.com/diegosouzapw/OmniRoute))

[7] **Qwen 3.8 27B 正式發布**：阿里巴巴 Apache 2 授權 27B 參數視覺語言模型，前代 Qwen 3.6 27B 已獲好評，新版需手動降低推理力度以避免過度思考。([來源](https://simonwillison.net/2026/Aug/16/qwen-38-27b/))

## 💬 社群熱門討論
[8] **Claude 平台 8/16 中斷 36 分鐘**：21:58 UTC 起認證層故障影響 claude.ai、Code、Cowork，API 大致正常，22:40 UTC 全面恢復，Reddit 用戶批狀態頁延遲反映。([來源](https://www.unite.ai/anthropic-outage-disrupts-claude-services-fix-deployed-after-login-failures/))

[9] **r/ClaudeAI 用量顯示異常引熱議**：中斷期間用戶回報用量計量器故障、無端消耗額度，社群共識為伺服器故障非限制變更，status.claude.com 全程顯示正常引發不滿。([來源](https://community.designtaxi.com/topic/35805-is-claude-anthropic-ai-down-august-16-2026))
