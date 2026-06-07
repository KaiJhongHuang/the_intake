# AI工作流日報 — 2026-06-07
> 涵蓋範圍：2026-06-06 06:00 ~ 2026-06-07 06:00 (TST)

> 📌 Claude 摘要：本日焦點集中在安全與基礎設施層面——Microsoft 揭露 Claude Code GitHub Action 供應鏈漏洞，Anthropic 同時發布自我撰寫程式碼比例超過 80% 的報告並呼籲建立暫停機制；工具端 Simon Willison 為 agent 推出 WASM 沙盒執行環境，Claude Code 則更新 fallback 與跨 session 安全機制。整體趨勢：AI agent 進入 CI/CD 帶來的攻擊面正在被認真對待。（以上為 Claude 推測性觀察）

## 🧠 Prompt 技巧 & 使用心得
[1] **Context Engineering 取代 Prompt Engineering**：2026 核心技能轉向設計模型的資訊環境而非措辭。([DEV Community](https://dev.to/gabrielhca/context-engineering-the-skill-replacing-prompt-engineering-in-2026-3lgd))
[2] **Willison MicroPython 沙盒**：發布 micropython-wasm 0.1a2，讓 agent 在 WASM 沙盒內安全執行 Python。([simonwillison.net](https://simonwillison.net/2026/Jun/6/micropython-in-a-sandbox/))
[3] **Ultracode 關鍵字更名**：Claude Code 動態工作流觸發詞由 workflow 改為 ultracode。([Releasebot](https://releasebot.io/updates/anthropic/claude-code))

## 🔧 工作流整合案例
[4] **Claude Code fallbackModel**：v2.1.166 新增備用模型設定，主模型過載時自動切換。([Releasebot](https://releasebot.io/updates/anthropic/claude-code))
[5] **跨 Session 訊息安全強化**：SendMessage 不再攜帶 user 權限，auto 模式封鎖越權請求。([Releasebot](https://releasebot.io/updates/anthropic/claude-code))
[6] **Bun Zig→Rust 移植**：Jarred Sumner 用 dynamic workflows 數百 agent 平行改寫，測試通過率 99.8%。([InfoQ](https://www.infoq.com/news/2026/06/dynamic-workflows-claude-code/))

## 🛠️ 新工具 & 套件
[7] **datasette-agent-micropython 0.1a0**：Datasette Agent 外掛，提供持久化 WASM MicroPython 直譯器。([GitHub](https://github.com/datasette/datasette-agent-micropython))
[8] **Claude Code Action v1.0.94 修補**：堵住 prompt injection 供應鏈漏洞，CVSS 7.8。([Flatt Security](https://flatt.tech/research/posts/poisoning-claude-code-one-github-issue-to-break-the-supply-chain/))

## 💬 社群熱門討論
[9] **Microsoft 揭露 CI/CD Agent 攻擊面**：安全部落格詳述 Claude Code Action 可透過 /proc 洩漏憑證。([Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2026/06/05/securing-ci-cd-in-agentic-world-claude-code-github-action-case/))
[10] **Anthropic：Claude 撰寫自身 80%+ 程式碼**：發布「When AI Builds Itself」報告，呼籲建立全球暫停機制。([VentureBeat](https://venturebeat.com/technology/anthropic-says-80-of-its-new-production-code-is-now-authored-by-claude-how-your-enterprise-can-keep-up))
[11] **6/5 全球宕機兩小時**：所有 Claude 服務中斷，Anthropic 調查疑似用戶資料外洩。([Cybernews](https://cybernews.com/ai-news/claude-outage-resolved-anthropic-opus-model-errors/))
