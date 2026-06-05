# AI工作流日報 — 2026-06-05
> 涵蓋範圍：2026-06-04 06:00 ~ 2026-06-05 06:00 (TST)

> 📌 Claude 摘要：Anthropic 發布重磅文章「When AI builds itself」，揭示 Claude 已撰寫逾 80% 自家合併程式碼並呼籲建立全球 AI 暫停機制；同日 GMO Flatt Security 完整揭露 Claude Code GitHub Action 供應鏈漏洞，Microsoft 隨即發表 CI/CD Agent 安全指南，AI 自我迭代速度與供應鏈信任成為雙焦點。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude 已撰寫 80%+ 自家程式碼**：五月合併程式碼逾八成由 Claude 撰寫，工程師日均合併量為 2024 年八倍。([來源](https://www.anthropic.com/institute/recursive-self-improvement))

[2] **Mythos 加速 AI 開發 52 倍**：Opus 4 提速 3 倍，Mythos Preview 達 52 倍，遞迴自改進已非理論。([來源](https://www.scientificamerican.com/article/anthropic-warns-ai-may-soon-begin-recursive-self-improvement/))

[3] **ultracode 自主工作流實測**：設定 xhigh + dynamic workflows，Claude Code 自動拆分子代理處理大型任務。([來源](https://medium.com/@CodeCoup/set-opus-4-8-ultracode-and-watch-claude-code-go-fully-autonomous-ca754b97833e))

## 🔧 工作流整合案例

[4] **GitHub Action 供應鏈漏洞完整揭露**：單一惡意 issue 可劫持 repo、竊取密鑰，已修補至 v1.0.94，CVSS 7.8。([來源](https://thehackernews.com/2026/06/claude-code-github-action-flaw-let-one.html))

[5] **Microsoft 發表 Agent CI/CD 安全指南**：分析 Read tool 繞過沙箱讀取 /proc 環境變數，建議隔離 AI 工作流。([來源](https://www.microsoft.com/en-us/security/blog/2026/06/05/securing-ci-cd-in-agentic-world-claude-code-github-action-case/))

[6] **6/15 計費分離倒數十天**：Agent SDK、claude -p 移至獨立額度池，Pro $20/月，用盡即停。([來源](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm))

## 🛠️ 新工具 & 套件

[7] **datasette-apps 發布**：Simon Willison 推出 Datasette 應用封裝工具，搭配 Opus 4.8 測試 Pyodide ASGI。([來源](https://simonwillison.net/))

[8] **Claude Code /plugin list 上線**：新增 --enabled/--disabled 過濾，背景代理升級不再冷重啟。([來源](https://releasebot.io/updates/anthropic/claude-code))

[9] **MAI-Code-1 整合 Copilot**：Microsoft AI 推理高效編程模型於 Build 2026 發布，進入 VS Code。([來源](https://blogs.microsoft.com/blog/2026/06/02/microsoft-build-2026-be-yourself-at-work/))

## 💬 社群熱門討論

[10] **全球暫停機制引發辯論**：Anthropic 呼籲多國共同可驗證暫停，IPO 估值破兆時機受質疑。([來源](https://decrypt.co/370089/ai-already-developing-ai-anthropic-humans-slowing-things-down))

[11] **Glasswing 擴至 15 國 150 組織**：Mythos 漏洞掃描進入電力、水務、醫療等關鍵基礎設施。([來源](https://techcrunch.com/2026/06/02/anthropic-scales-claude-mythos-to-critical-infrastructure-in-15-countries/))

[12] **Cursor $2B ARR 但企業端鬆動**：Claude Code 以 46% 最愛率穩居首位，Cursor 企業客戶開始轉向。([來源](https://fortune.com/2026/03/21/cursor-ceo-michael-truell-ai-coding-claude-anthropic-venture-capital/))
