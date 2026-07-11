# AI工作流日報 — 2026-07-11
> 涵蓋範圍：2026-07-10 06:00 ~ 2026-07-11 06:00 (TST)

> 📌 Claude 摘要：Claude Code v2.1.207 將 auto mode 預設開放至 Bedrock / Vertex AI / Foundry 三大企業部署平台，降低企業啟用門檻；競品同步大動作——Cursor v3.11 推出 Side Chats 副對話與歷史搜尋，Amp 砍掉四種模式改為單一 Dial 成本撥盤並引入開源 GLM-5.2，Kiro 加入 Sonnet 5 支援；system_prompts_leaks 倉庫七日暴增 7.6k 星達 56k，系統提示透明化趨勢加速。

## 🧠 Prompt 技巧 & 使用心得
[1] **Reflect 靜音時段與中斷提醒**：Reflect 支援設定安靜時段與使用時限提醒，還會定期拋出反思問題如「哪些事你想繼續自己做？」，引導使用者釐清 AI 邊界。([來源](https://www.anthropic.com/news/reflect-with-claude))
[2] **Cursor Side Chats 不中斷主線**：v3.11 新增 /side 或 /btw 指令開啟副對話，可在主 Agent 持續運作時查資料、驗證決策，避免上下文污染。([來源](https://cursor.com/changelog))

## 🔧 工作流整合案例
[3] **Claude Code v2.1.207 auto mode 全面上線**：Bedrock、Vertex AI、Foundry 三大平台不再需要 CLAUDE_CODE_ENABLE_AUTO_MODE 環境變數即可啟用，企業可透過 disableAutoMode 關閉。([來源](https://dev.classmethod.jp/en/articles/20260711-cc-updates-v2-1-207/))
[4] **Kiro 加入 Sonnet 5 與 MCP 自動 OAuth**：AWS Kiro IDE 新增 Claude Sonnet 5、Agent 檔案變更 Hooks、MCP 伺服器自動 OAuth 登入，多視窗設定同步。([來源](https://releasebot.io/updates/kiro))
[5] **Amp 用 The Dial 取代四模式**：原 smart / deep / rush / large 四模式改為 low / medium / high / ultra 成本撥盤，low 預設用開源 GLM-5.2 而非私有模型。([來源](https://jls42.org/en/news/ia-actualites-10-jul-2026))

## 🛠️ 新工具 & 套件
[6] **Claude Code v2.1.207 修復與改進**：修復長列表 / 表格串流時終端機凍結問題；升級 highlight.js 11 強化語法高亮；移除 /agents 精靈，改由直接編輯 .claude/agents/。([來源](https://github.com/anthropics/claude-code/releases))
[7] **Cursor v3.11 對話搜尋**：從 Cmd+K 搜尋所有歷史 Agent 對話全文，本地索引可擴展至數千筆，解決長期呼聲最高的功能缺口。([來源](https://cursor.com/changelog))
[8] **Claude for Government 公測**：Claude Code 與 Cowork 進入 FedRAMP High 授權環境，公部門可用於軟體現代化、備忘錄草擬、RFP 審查與簡報製作。([來源](https://letsdatascience.com/news/anthropic-brings-claude-code-and-cowork-to-government-06df8bbb))

## 💬 社群熱門討論
[9] **system_prompts_leaks 倉庫飆破 56k 星**：七日新增 7.6k 星，收錄 Fable 5、GPT-5.6、Gemini 3.5 等最新模型系統提示，華郵五月即以「AI 隱藏規則」為題報導。([來源](https://github.com/asgeirtj/system_prompts_leaks))
[10] **中國後門爭議持續發酵**：Anthropic 回應南華早報稱所謂後門為反蒸餾實驗殘留，但中國媒體仍以「安全風險」為由持續報導。([來源](https://www.scmp.com/news/china/article/3359901/anthropic-hits-back-after-china-warns-claude-code-backdoor-risks))
[11] **AI 編碼工具 90% 採用率**：JetBrains 與多項調查顯示開發者 AI 工具採用率已突破九成，四強格局（Claude Code / Cursor / Copilot / Codex）競爭白熱化。([來源](https://www.developersdigest.tech/blog/what-hacker-news-gets-right-about-ai-coding-agents-2026))
