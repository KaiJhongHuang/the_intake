# AI工作流日報 — 2026-04-02

## 🧠 Prompt 技巧 & 使用心得

[1] **Simon Willison 談 Agentic Engineering 拐點**：2025 年 11 月起 AI 生成程式碼「幾乎總是能用」，從驚喜變成預期，專業程式設計的本質正在轉變。（[來源](https://simonwillison.net/2026/Apr/2/lennys-podcast/)）

[2] **Willison：Claude Skills 可能比 MCP 更重要**：可重用的結構化 Skills 將成為 Claude 生態核心擴展機制，比工具連接更具影響力。（[來源](https://nicknisi.com/posts/claude-skills/)）

[3] **Slash Commands 提升內循環效率**：將每日重複工作流包裝成 .claude/commands/ 中的 slash command，存入 git 共享全團隊。（[來源](https://www.morphllm.com/claude-code-reddit)）

[4] **Tom's Guide：Thinking Prompts 函式庫**：建立專門觸發 Claude 深度推理的 prompt 範本庫，適用於複雜分析與多步驟任務。（[來源](https://www.tomsguide.com/ai/i-built-a-library-of-thinking-prompts-for-claude-these-are-the-ones-i-use-most)）

[5] **別把 Claude 當 ChatGPT 用**：Tom's Guide 整理 10 個解鎖 Claude 真正潛力的 prompt 技巧，強調角色設定與結構化輸出。（[來源](https://www.tomsguide.com/ai/stop-using-claude-like-chatgpt-10-prompts-that-unlock-its-real-potential)）

## 🔧 工作流整合案例

[6] **Ethan Mollick：AI 軟體工廠實驗**：Mollick 邀請 Willison 等觀察者進入「軟體工廠」，測試 AI 如何根本性改變組織運作方式。（[來源](https://www.oneusefulthing.org/p/the-shape-of-the-thing)）

[7] **SSE Transport 效能修復**：MCP SSE 傳輸從二次方降為線性時間處理大型串流 frame，長對話不再拖慢 SDK session。（[來源](https://releasebot.io/updates/anthropic/claude-code)）

[8] **MCP Tool Search 減少 95% Context 佔用**：MCP Server 延遲載入功能上線，可同時掛載多個 MCP Server 而不擔心 context 限制。（[來源](https://www.aibase.com/news/24669)）

## 🛠️ 新工具 & 套件

[9] **oh-my-claudecode 登上 GitHub Trending #1**：5 種執行模式、32 個專用 Agent，Ultrapilot 模式 5 並行 worker，24 小時 858 星。（[來源](https://github.com/yeachan-heo/oh-my-claudecode)）

[10] **claw-code 2 小時破 50K 星**：洩漏碼的 clean-room Python/Rust 重寫版成為 GitHub 史上最快成長 repo。（[來源](https://cybernews.com/tech/claude-code-leak-spawns-fastest-github-repo/)）

[11] **claude-code-system-prompts Repo 更新**：完整收錄 Claude Code 全部 system prompt、24 個內建工具描述、子 Agent prompt。（[來源](https://github.com/Piebald-AI/claude-code-system-prompts)）

[12] **awesome-claude-plugins：Plugin 採用度追蹤**：用 n8n workflow 自動蒐集 GitHub 上 Claude Code plugin 的採用指標。（[來源](https://github.com/quemsah/awesome-claude-plugins)）

## 💬 社群熱門討論

[13] **Gartner：2028 年過半企業將放棄助理式 AI**：轉向「成果導向工作流」平台，人類角色從執行者變為 Agent Steward（監督者）。（[來源](https://www.gartner.com/en/newsroom/press-releases/2026-04-02-gartner-expects-most-enterprises-to-abandon-assistive-ai-for-outcome-focused-workflow-by-2028)）

[14] **HN 熱議洩漏碼架構設計**：討論從「尷尬事件」轉向分析 state-of-the-art agent 設計：orchestration、memory system、planning/review flow。（[來源](https://news.ycombinator.com/item?id=47609294)）

[15] **洩漏碼改變 AI 競賽格局**：評論指出洩漏讓競爭者獲得了 Anthropic 花數十億美元打造的 Agent 架構藍圖。（[來源](https://www.pymnts.com/artificial-intelligence-2/2026/anthropics-claude-source-code-leak-hands-competitors-a-blueprint-it-spent-billions-to-build/)）

[16] **Moltbook AI 社交網路引關注**：Willison 稱其「當前網路最有趣的地方」，但警告 Agent 每 4 小時從 Moltbook 伺服器抓取指令存在安全風險。（[來源](https://fortune.com/2026/01/31/ai-agent-moltbot-clawdbot-openclaw-data-privacy-security-nightmare-moltbook-social-network/)）

---
📌 Claude 推測：4/2 的主旋律是「反思與重建」——社群從洩漏碼的震驚中恢復，開始認真分析 Agent 架構設計。Gartner 的預測與 Willison 的觀察不約而同指向同一方向：AI 正從「助理」進化為「自主工作者」，而 oh-my-claudecode 與 claw-code 的爆發正是開發者用行動回應這個趨勢。
