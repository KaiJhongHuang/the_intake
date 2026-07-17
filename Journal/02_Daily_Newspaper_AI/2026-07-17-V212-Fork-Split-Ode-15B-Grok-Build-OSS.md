# AI工作流日報 — 2026-07-17
> 涵蓋範圍：2026-07-16 06:00 ~ 2026-07-17 06:00 (TST)

> 📌 Claude 摘要：本日焦點三線並行——Claude Code v2.1.212 將 /fork 改為背景 session 並新增子代理與搜尋上限；Anthropic 聯手 Blackstone 等推出 $15 億 AI 導入服務公司 Ode；xAI 因 Grok Build 竊傳用戶 repo 醜聞緊急開源 84 萬行 Rust 碼，但上傳程式碼仍留在二進位中僅靠伺服器旗標關閉，引發信任危機。

## 🧠 Prompt 技巧 & 使用心得
[1] **Willison 用 Grok Build Rust 碼造 Mermaid→Unicode 工具**：從 84 萬行開源碼中抽出終端 Mermaid 渲染器，編譯成 WASM 在瀏覽器即時轉換流程圖。([來源](https://simonwillison.net/2026/Jul/16/grok-mermaid/))

[2] **v2.1.211 修復權限預覽 Unicode 欺騙漏洞**：阻止雙向覆蓋字元與零寬字元偽裝工具輸入，防止核准訊息被視覺篡改。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.211))

## 🔧 工作流整合案例
[3] **Claude Code v2.1.212 發布：/fork 改為背景 session**：/fork 現將對話複製至獨立背景 session，原本的子代理功能改為 /subtask。([來源](https://code.claude.com/docs/en/changelog))

[4] **v2.1.212 新增 session 級搜尋與子代理上限**：WebSearch 預設上限 200 次、子代理產生上限 200，防止失控迴圈耗盡資源。([來源](https://code.claude.com/docs/en/changelog))

[5] **v2.1.212 新增 auto-mode reset 指令**：`claude auto-mode reset` 可一鍵恢復預設自動模式設定，加 `--yes` 跳過確認。([來源](https://code.claude.com/docs/en/changelog))

[6] **Ode with Anthropic 正式發布：$15 億 AI 導入服務公司**：Anthropic 聯手 Blackstone、Hellman & Friedman、Goldman Sachs 等成立 Ode，100 名工程師以「Claude-first」原則進駐企業推動 AI 落地。([來源](https://techcrunch.com/2026/07/15/anthropic-blackstone-bet-the-next-trillion-dollar-ai-business-is-implementation-not-models/))

## 🛠️ 新工具 & 套件
[7] **Grok Build 以 Apache 2.0 開源 84.4 萬行 Rust**：xAI 在用戶 repo 被偷傳至 GCS 的醜聞後數小時緊急開源全部原始碼。([來源](https://simonwillison.net/2026/Jul/15/grok-build/))

[8] **Willison grok-mermaid 上線**：將 Grok Build 的 Mermaid 渲染器編成 WASM，支援 flowchart、sequence、state、class、ER 五種圖表。([來源](https://tools.simonwillison.net/grok-mermaid))

[9] **Enterprise Admin API 擴展成員管理**：Claude Enterprise 可透過 API 管理成員、角色、邀請、群組；API Key 新增到期時間設定與到期前通知。([來源](https://releasebot.io/updates/anthropic/claude))

## 💬 社群熱門討論
[10] **Grok Build 上傳碼仍在二進位中引爆信任危機**：安全研究者確認竊傳程式碼僅靠伺服器旗標關閉，xAI 可在不推送更新的情況下重新啟用。([來源](https://www.techtimes.com/articles/320671/20260716/grok-build-open-sourced-after-covert-upload-code-exfiltrate-repos-stays.htm))

[11] **Anthropic IPO 投資人會議啟動**：Goldman Sachs、Morgan Stanley、JPMorgan 聯手安排投資人會議，最快十月掛牌，將搶先 OpenAI 上市。([來源](https://www.cnbc.com/2026/07/15/anthropic-ipo-banks-investor-meetings.html))

[12] **Continue 資料匯出截止，Cursor 收購整合完成**：Continue 2.0.0 最終版釋出後 GitHub 轉唯讀，Apache 2.0 授權保留供社群 fork。([來源](https://thenewstack.io/cursor-acquires-continue-coding/))
