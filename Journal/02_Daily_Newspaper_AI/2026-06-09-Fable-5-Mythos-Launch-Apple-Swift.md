# AI工作流日報 — 2026-06-09
> 涵蓋範圍：2026-06-08 06:00 ~ 2026-06-09 06:00 (TST)

> 📌 Claude 摘要：今日最大事件為 Anthropic 同時發布 Fable 5 與 Mythos 5，Mythos 級模型首次公開可用；Apple WWDC 宣布 iOS 27 Extensions 開放 Claude 取代 Siri，並釋出 Foundation Models Swift SDK，標誌 Claude 正式進入 Apple 生態系。同時 Anthropic Institute 發表遞迴自我改進論文，揭露 Claude 已撰寫自身 80% 以上程式碼，呼籲建立全球暫停機制。

## 🧠 Prompt 技巧 & 使用心得

[1] **Fable 5 安全分類器自動降級**：高風險請求（生化、網安、蒸餾）自動路由至 Opus 4.8，95% 以上對話不受影響。([來源](https://www.anthropic.com/news/claude-fable-5-mythos-5))

[2] **Fable 5 用量加倍消耗**：Pro/Max 方案免費試用至 6/22，但 Fable 5 對話消耗速度約為 Opus 4.8 的兩倍。([來源](https://claudefa.st/blog/guide/development/fable-5-usage-credits))

[3] **Willison sandbox 實驗**：Simon Willison 釋出 micropython-wasm，為 Datasette Agent 提供安全沙箱執行環境。([來源](https://simonwillison.net/))

## 🔧 工作流整合案例

[4] **Apple Foundation Models Swift SDK**：Anthropic 發布 Swift package，開發者可在 iOS 27/macOS 27 以統一介面呼叫 Claude，支援串流、Tool Use 與結構化回應。([來源](https://claude.com/blog/claude-for-foundation-models))

[5] **iOS 27 Extensions 開放 AI 市集**：使用者可將 Claude 設為 Siri、Writing Tools、Image Playground 的預設 AI 提供者。([來源](https://aiweekly.co/node/2611))

[6] **Fable 5 上架三大雲平台**：同日登陸 AWS Bedrock、Azure Foundry、GitHub Copilot，企業可直接調用 Mythos 級模型。([來源](https://aws.amazon.com/about-aws/whats-new/2026/06/claude-fable-5-aws/))

## 🛠️ 新工具 & 套件

[7] **Claude Fable 5 正式發布**：首款公開 Mythos 級模型，API 定價 $10/M 輸入、$50/M 輸出，編碼與科學基準全面領先。([來源](https://www.anthropic.com/news/claude-fable-5-mythos-5))

[8] **Claude Mythos 5 限定合作夥伴**：專攻網安與基因體學，Mythos 5 僅向特定合作夥伴開放，自主運作能力顯著提升。([來源](https://the-decoder.com/anthropic-releases-claude-fable-5-and-mythos-5-with-major-gains-in-coding-and-science/))

[9] **Claude Code GitHub Action v1.0.94 修補**：修復 prompt injection 漏洞，攻擊者曾可透過偽造 bot 帳號竊取 OIDC token 取得 repo 寫入權限。([來源](https://thehackernews.com/2026/06/claude-code-github-action-flaw-let-one.html))

## 💬 社群熱門討論

[10] **遞迴自我改進論文**：Anthropic Institute 揭露 Claude 已撰寫自身 80% 以上合併程式碼，呼籲建立可驗證的全球 AI 暫停機制。([來源](https://www.anthropic.com/institute/recursive-self-improvement))

[11] **Microsoft 70+ GitHub repo 遭植入惡意碼**：攻擊者鎖定 Claude Code 與 Gemini CLI 使用者，竊取開發者憑證。([來源](https://www.404media.co/microsoft-hacked-to-deliver-malware-to-claude-and-gemini-users/))

[12] **Fable 5 計費模式引發社群焦慮**：6/23 起從訂閱方案移除，改採 usage credits，重現先前 Claude Code 計費爭議。([來源](https://www.unite.ai/claude-fable-5-makes-frontier-ai-a-metered-utility/))
