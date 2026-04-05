# AI工作流日報 — 2026-04-04
> 涵蓋範圍：2026-04-03 06:00 ~ 2026-04-04 06:00 (TST)

## 🧠 Prompt 技巧 & 使用心得

[1] **Contract-Style Prompt 架構**：2026 年 Claude prompt 設計主流轉向「合約式」——定義成功標準讓模型自行決定方法，而非逐步指令。（[來源](https://promptbuilder.cc/blog/claude-prompt-engineering-best-practices-2026)）

[2] **System Prompt 三段式結構**：高效 System Prompt 遵循 Identity → Rules → Output Format 三層結構，提升一致性與可控性。（[來源](https://chatpromptgenius.com/claude-prompt-engineering-guide-for-beginners-2026-edition/)）

[3] **CLAUDE.md 控制在 200 行內**：Reddit 社群共識——CLAUDE.md 保持精簡，用巢狀目錄分層管理規則，從錯誤中迭代增補。（[來源](https://github.com/shanraisshan/claude-code-best-practice)）

[4] **短 Session 勝過長馬拉松**：開發者實測，專注短對話＋checkpoint commit 的成功率遠高於長時間對話修正。（[來源](https://www.morphllm.com/claude-code-reddit)）

[5] **明確允許模型表達不確定性**：給 Claude 說「不確定就說不確定」的權限，可大幅降低幻覺率。（[來源](https://www.dreamhost.com/blog/claude-prompt-engineering/)）

## 🔧 工作流整合案例

[6] **n8n-MCP 自然語言建 Workflow**：透過 MCP Server 讓 Claude 直接用自然語言建立、除錯、觸發 n8n 工作流，支援 1,396 個節點。（[來源](https://github.com/czlonkowski/n8n-mcp)）

[7] **Zapier MCP 串接 Claude Desktop**：Zapier MCP 讓 Claude 桌面版直接呼叫 Zapier 整合，僅限桌面端使用。（[來源](https://www.nocode.mba/articles/zapier-mcp-claude)）

[8] **Ethan Mollick 用 Claude Code 一小時建完整創業網站**：給 Claude Code 一句指令，AI 獨立工作 74 分鐘產出數百檔案並部署上線。（[來源](https://www.oneusefulthing.org/p/claude-code-and-what-comes-next)）

[9] **Simon Willison：Claude Skills 可能比 MCP 更重要**：Willison 認為可重用的結構化 Skills 將成為 Claude 生態核心擴展機制。（[來源](https://nicknisi.com/posts/claude-skills/)）

[10] **Multi-Agent 模式：Opus 主控＋Sonnet 子任務**：進階用戶以 CLAUDE_CODE_SUBAGENT_MODEL 分配模型，主 session 用 Opus 推理、子任務用 Sonnet 執行。（[來源](https://www.morphllm.com/claude-code-reddit)）

## 🛠️ 新工具 & 套件

[11] **oh-my-claudecode：團隊多 Agent 協作框架**：提供 5 種執行模式、32 個專用 Agent，Ultrapilot 模式 5 並行 worker 可達 3-5 倍加速。GitHub 24 小時獲 858 星。（[來源](https://github.com/yeachan-heo/oh-my-claudecode)）

[12] **Claude Code Plugin 啟動效能大幅改善**：最新更新讓 commands、skills、agents 從磁碟快取載入，不再重新 fetch。（[來源](https://releasebot.io/updates/anthropic/claude-code)）

[13] **Message Batches API max_tokens 提升至 300K**：Claude Opus 4.6 與 Sonnet 4.6 在批次 API 支援 300K token 輸出，適合長文與結構化資料。（[來源](https://releasebot.io/updates/anthropic)）

[14] **Legacy SDK 正式移除**：開發者須遷移至 @anthropic-ai/claude-agent-sdk，舊入口不再支援。（[來源](https://platform.claude.com/docs/en/agent-sdk/plugins)）

[15] **claw-code：Claude Code 開源重寫版**：基於洩漏碼的 clean-room 重寫，2 小時破 50K 星，成 GitHub 史上最快成長 repo。（[來源](https://cybernews.com/tech/claude-code-leak-spawns-fastest-github-repo/)）

## 💬 社群熱門討論

[16] **Claude Code 原始碼洩漏事件**：v2.1.88 npm 包因缺少 .npmignore 意外發布 512K 行 TypeScript 原始碼，Anthropic 稱無客戶資料外洩。（[來源](https://thehackernews.com/2026/04/claude-code-tleaked-via-npm-packaging.html)）

[17] **Anthropic 封鎖 OpenClaw 等第三方 Agent 使用訂閱額度**：4/4 起 Pro/Max 訂閱不再支援第三方 Agent 工具掛載，需額外付費。（[來源](https://techcrunch.com/2026/04/04/anthropic-says-claude-code-subscribers-will-need-to-pay-extra-for-openclaw-support/)）

[18] **洩漏碼遭利用散佈木馬**：攻擊者利用 typosquat 與 dependency confusion 在 npm 植入遠端存取木馬，3/31 特定時段安裝者需檢查。（[來源](https://www.bleepingcomputer.com/news/security/claude-code-leak-used-to-push-infostealer-malware-on-github/)）

[19] **Simon Willison 談 Agentic Engineering 拐點**：2025 年 11 月起 AI 生成程式碼「幾乎總是能用」，從驚喜變成預期。（[來源](https://simonwillison.net/2026/Apr/2/lennys-podcast/)）

[20] **1M Context Window Beta 將於 4/30 退役**：Sonnet 4.5/4.0 的百萬 token 窗口 Beta 結束，需遷移至 Sonnet 4.6 或 Opus 4.6（原生支援）。（[來源](https://releasebot.io/updates/anthropic)）

---
📌 Claude 推測：本週 Claude 生態最大事件無疑是原始碼洩漏——它意外催生了開源替代品的爆發（claw-code、oh-my-claudecode），同時迫使 Anthropic 收緊訂閱政策封鎖第三方 Agent。這標誌著 Claude 從「封閉工具」走向「平台生態博弈」的轉折點。開發者應關注 Plugin SDK 遷移（legacy → claude-agent-sdk）與 1M context beta 退役的時程，及早調整工作流。
