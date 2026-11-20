# AI工作流日報 — 2026-11-21
> 涵蓋範圍：2026-11-20 06:00 ~ 2026-11-21 06:00 (TST)

> 📌 Claude 摘要：Anthropic數學家Alpöge宣稱以Claude輔助證明黎曼猜想並以Lean驗證，數學界仍在審查中——若屬實將是AI協作解決世紀數學難題的里程碑。v2.1.329釋出130項變更強化任務可見性與分支級程式審查，ANT次日交易跌8.5%收約$89，ChatPRD創辦人揭露token轉售詐欺迫使Stripe升級偵測，Google正式發布Gemini 4 Neon中階模型挑戰現有定價格局。

## 🧠 Prompt 技巧 & 使用心得

[1] **v2.1.329釋出130項變更**：新增/tasks列出排程與fork，/code-review可審查整個分支，hook信任警告強化安全。([來源](https://www.claudeupdates.dev/version/2.1.329))

[2] **v2.1.329系統提示移除高風險確認規則**：社群changelog發現不再內建暫停確認破壞性操作規則，自動化場景更順暢但需自行把關。([來源](https://x.com/ClaudeCodeLog/status/2123546061234983121))

[3] **Code Mode啟用OpenTelemetry**：v2.1.329讓Code Mode腳本產出事件與指標遙測，方便企業監控代理行為。([來源](https://bettertoken.ai/en/blog/claude-code-2-1-329-changelog-gateway-fixes/))

## 🔧 工作流整合案例

[4] **ChatPRD遭token轉售詐欺**：創辦人Claire Vo揭露大量免費試用被濫用轉售token，Stripe Radar正適應偵測此新型態。([來源](https://simonwillison.net/2026/Nov/20/token-fraud-is-here-and-its-bad/))

[5] **Gemini 4 Neon正式發布**：Google中階模型上線API Studio與Gemini app，1M上下文窗口，定價$3-4/$15-20每百萬token。([來源](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-neon/))

[6] **Willison指token詐欺已成產業**：引述Vo稱詐欺者用旋轉代理跨多家AI產品濫用，鵜鶘騎腳踏車SVG成辨識底層模型的指紋。([來源](https://www.lennysnewsletter.com/p/how-i-ai-fable-52-review-how-i-fight))

## 🛠️ 新工具 & 套件

[7] **黎曼猜想Lean形式化證明公開**：Alpöge以超過250,000頁Lean程式碼發布，Sutherland獨立編譯通過，論文尚未釋出。([來源](https://siliconangle.com/2026/11/20/anthropic-researcher-claims-to-have-proven-riemann-hypothesis-using-claude/))

[8] **Datasette 1.0a43釋出**：Willison推進1.0里程碑至53%完成度，新增串流輸出渲染器與安全修復。([來源](https://simonwillison.net/2026/Nov/15/datasette/))

## 💬 社群熱門討論

[9] **Alpöge宣稱Claude助攻證明黎曼猜想**：Anthropic數學家稱以Claude找到證明並以Lean驗證，Scientific American等多家媒體報導，數學界審查中。([來源](https://www.scientificamerican.com/article/anthropic-mathematician-claims-to-prove-riemann-hypothesis-most-famous-problem-in-all-of-math/))

[10] **ANT次日交易跌約8.5%**：科技股全面拋售中ANT收約$89，盤中一度跌超12%，AI類股承壓。([來源](https://www.cnbc.com/2026/11/20/anthropic-stock-ai-amd-nvidia.html))

[11] **黎曼證明引爆AI能力辯論**：部分數學家質疑250K頁機器證明可讀性，支持者認為Lean通過即為有效，HN與Reddit熱議。([來源](https://officechai.com/ai/claimed-riemann-hypothesis-proof-made-with-claude-appears-on-anthropic-mathematician-levent-alpoges-website/))

[12] **PSF年度募款啟動**：Willison以PSF董事身分推廣Python基金會年終募款，呼籲社群支持開源基礎建設。([來源](https://simonwillison.net/2026/Nov/18/psf-end-of-year-fundraiser/))
