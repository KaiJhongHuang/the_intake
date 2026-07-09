# AI工作流日報 — 2026-07-09
> 涵蓋範圍：2026-07-08 06:00 ~ 2026-07-09 06:00 (TST)

> 📌 Claude 摘要：AI 安全議題集中爆發——Friendly Fire 攻擊、Sophos 誤報、中國後門警告三箭齊發；GPT-5.6 三模型同日 GA 形成史上首次三大實驗室同步前沿對決；VS Code 1.128 多聊天 Claude Agent 上線標誌 IDE 整合再深化。

## 🧠 Prompt 技巧 & 使用心得
[1] **Claude 月度回顧上線**：Settings > Reflect 可查看主題分布、活躍日與尖峰時段，需開啟記憶功能。([來源](https://support.claude.com/en/articles/15672559-see-your-monthly-recap))
[2] **時間與專注設定**：新增休息提醒與安靜時段，使用者可自訂 Claude 使用節奏避免過度依賴。([來源](https://releasebot.io/updates/anthropic/claude))
[3] **Context Engineering 取代 Prompt Engineering**：2026 模型品質已到位，結構化上下文（CLAUDE.md、Skills、Sub-agents）比措辭更關鍵。([來源](https://emergingai.substack.com/p/claude-changed-the-july-2026-way))

## 🔧 工作流整合案例
[4] **VS Code 1.128 多聊天 Claude Agent**：支援分岔對話、並行發送、同 session 內多 chat 各自保留歷史與模型選擇。([來源](https://visualstudiomagazine.com/articles/2026/07/08/claude-ai-gets-yet-another-boost-in-vs-code-1-128.aspx))
[5] **VS Code 1M token 上下文窗口**：相容 Anthropic 與 OpenAI 模型，可處理大型 codebase 長對話不截斷。([來源](https://code.visualstudio.com/updates/v1_128))
[6] **Copilot Vision GA**：可貼上、拖放圖片與 PDF 至 Chat，視覺理解正式脫離預覽階段。([來源](https://www.ntcompatible.com/story/visual-studio-code-1128-launches-with-multichat-claude-agents-and-ga-copilot-vision))

## 🛠️ 新工具 & 套件
[7] **GPT-5.6 Sol / Terra / Luna 正式 GA**：7/9 全面開放，Sol $5/$30、Terra $2.50/$15、Luna $1/$6；Cerebras 上 Sol 可達 750 tok/s。([來源](https://openai.com/index/previewing-gpt-5-6-sol/))
[8] **Claude Code v2.1.204**：修復 headless session 中 SessionStart hook 事件未串流導致遠端 worker 被閒置回收的問題。([來源](https://code.claude.com/docs/en/changelog))
[9] **三大前沿實驗室同步有前沿模型可用**：AI 史上首次 OpenAI、Anthropic、Google 各自擁有公開前沿模型同時在線。([來源](https://www.buildfastwithai.com/blogs/ai-news-today-july-9-2026))

## 💬 社群熱門討論
[10] **Friendly Fire 攻擊曝光**：AI Now Institute 發布 PoC，Claude Code 與 Codex 自主模式下審查惡意 repo 會反被誘導執行 payload，跨四模型均中招。([來源](https://thehackernews.com/2026/07/friendly-fire-ai-agents-built-to-catch.html))
[11] **Sophos：AI Coding Agent 觸發端點偵測規則**：Claude Code、Cursor、Codex 的正常行為模式與攻擊者 MITRE ATT&CK 手法高度相似，產生大量誤報。([來源](https://thehackernews.com/2026/07/ai-coding-agents-found-triggering.html))
[12] **中國工信部指 Claude Code 含後門**：涵蓋 v2.1.91–2.1.196，建議解安裝或升級；Anthropic 稱為反蒸餾實驗殘留，阿里巴巴 7/10 起全面禁用。([來源](https://www.cnbc.com/2026/07/08/china-anthropic-ai-claude-code-backdoor-security-threat.html))
[13] **Jim Cramer 稱 Anthropic 是贏家**：CNBC 節目指企業 AI 預算正大幅壓縮，模型層才是真正收費站，Anthropic $300 億年化營收領跑。([來源](https://247wallst.com/investing/2026/07/09/jim-cramer-anthropic-is-the-winner-now-as-enterprises-move-to-slash-tech-budgets-in-half/))
