# AI工作流日報 — 2026-07-15
> 涵蓋範圍：2026-07-14 06:00 ~ 2026-07-15 06:00 (TST)

> 📌 Claude 摘要：Anthropic 重磅推出 Claude for Teachers，免費向全美 K-12 教師開放 Premium 功能與課程對齊工具；M365 Connector 新增寫入工具可直接發信管日曆；Claude for Chrome 被 Manifold Security 揭露兩項未修補漏洞（CVSS 最高 9.6）；Enterprise 新增自助式 HIPAA 啟用流程；Claude 於 7/14 再度中斷約 13 分鐘影響多項服務；Microsoft Dataverse MCP 插件同步上架 Claude、Cursor、Copilot 三大平台。

## 🧠 Prompt 技巧 & 使用心得
[1] **Context Engineering 取代 Prompt Engineering 成主流共識**：多篇社群文章指出 2026 年高效用戶已從「寫好 prompt」轉向「建好 context 系統」——自動載入的 CLAUDE.md、觸發式 Skills、背景執行的 Workflows 與 Agent 才是真正槓桿。([來源](https://emergingai.substack.com/p/claude-changed-the-july-2026-way))
[2] **Simon Willison 建議讓 Fable 自行判斷**：Code w/ Claude 團隊建議「告訴 Fable 用自己的判斷決定是否寫測試」勝過逐步指令，Willison 在實測 Datasette Agent 系統提示時驗證此策略確實減少冗餘輸出。([來源](https://simonwillison.net/2026/Jul/3/judgement/))

## 🔧 工作流整合案例
[3] **Claude for Teachers 正式發布**：免費向全美 K-12 教師開放 Premium 功能，整合 Learning Commons 對齊 50 州學術標準，可連接 ASSISTments、Brisk Teaching、Canva Education 等教育工具；2027/6/30 前註冊享一年免費，資料不用於訓練。([來源](https://www.anthropic.com/news/claude-for-teachers))
[4] **M365 Connector 新增 Write Tools**：管理員啟用後 Claude 可直接從用戶帳號發送 Email、管理行事曆、更新 OneDrive/SharePoint 檔案，寄出信件自動標注 AI 代發；附件暫不支援，需 Entra admin + Claude org admin 雙重開啟。([來源](https://www.beri.net/article/claude-m365-write-tools-email-sharepoint-2026))
[5] **Enterprise 自助式 HIPAA 啟用上線**：Enterprise 與 API 組織可在設定頁面一鍵檢閱 BAA、下載實作指南並啟用 HIPAA 配置，不再需要走銷售或法務流程；Team/Pro/Max/Free 方案不適用。([來源](https://support.claude.com/en/articles/13296973-hipaa-ready-enterprise-plans))
[6] **Microsoft Dataverse MCP 擴展至 Claude 生態**：7/14 Microsoft 將 Dataverse 插件上架 Claude、Cursor、Copilot 三平台，開發者可用自然語言操作 Dataverse；同步公布 60+ MCP Server、夥伴認證機制與企業自建治理框架。([來源](https://visualstudiomagazine.com/articles/2026/07/14/low-coding-in-the-age-of-ai-dataverse-embraces-copilot-claude-and-cursor.aspx))

## 🛠️ 新工具 & 套件
[7] **Claude 新增月度回顧與專注設定**：Web/Desktop 版加入使用回顧、休息提醒、安靜時段與工作洞察功能，需啟用 Memory；為 Anthropic 首次在生產力/健康面向內建用量管理工具。([來源](https://releasebot.io/updates/anthropic/claude))
[8] **Copilot CLI 新增 /security-review 指令**：GitHub Copilot 於 7/14 發布公開預覽，可在 PR 流程中對變更進行 AI 驅動的漏洞掃描，與 Copilot CLI 既有的 voice mode 與 canvas 擴充同步上線。([來源](https://releasebot.io/updates/github))

## 💬 社群熱門討論
[9] **Claude for Chrome 漏洞未修補引爆安全社群**：Manifold Security 7/14 披露 v1.0.80 仍存在兩項漏洞——content script 未驗證 `event.isTrusted` 與 `?skipPermissions=true` 特權側載，CVSS 預設 7.7、開啟自動執行後升至 9.6 Critical，Anthropic 尚未公開回應。([來源](https://www.manifold.security/blog/claude-for-chrome-extension-bypass))
[10] **Claude 7/14 再度中斷約 13 分鐘**：約 2,000+ 用戶回報 claude.ai、Cowork Remote、Claude Code Remote、Claude Design 無法使用，另有 3 分鐘 container creation 故障；為近一個月內第三次顯著中斷事件。([來源](https://gvwire.com/2026/07/14/claude-ai-goes-down-for-thousands-tuesday-downdetector-reports/))
[11] **MIT Technology Review 持續報導 J-Space 研究**：7/14 刊出 Claude 內部運作機制專題，介紹 Anthropic 用 Jacobian Lens 在 Opus 4.6 內發現的「思考空間」，模型計算中間步驟時會在隱藏層產生語義可讀的中繼結果。([來源](https://www.technologyreview.com/2026/07/14/1140391/the-download-anthropic-claude-internal-thoughts-world-models/))
