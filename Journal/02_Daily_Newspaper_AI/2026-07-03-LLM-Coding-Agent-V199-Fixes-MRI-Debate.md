# AI工作流日報 — 2026-07-03
> 涵蓋範圍：2026-07-02 06:00 ~ 2026-07-03 06:00 (TST)

> 📌 Claude 摘要：Simon Willison 連發兩篇重量文章——llm-coding-agent 0.1a0 將 LLM 函式庫演化為可用的編碼代理框架，「Fable's judgement」則提出子代理應降級模型、主迴圈保留判斷力的成本策略。Claude Code v2.1.199 為純可靠性版本，修復子代理被限速後靜默失敗、串流中斷丟棄部分輸出、Linux 背景守護程序自殺等問題。HN 上一篇用 Opus 4.8 分析肩膀 MRI 並挑戰骨科醫師診斷的文章引爆 368+ 則討論，放射科醫師大量參戰。Confluent 宣布 MCP Server 與 Agent Skills 正式 GA，將 Kafka 生態整合進 AI 編碼工具。

## 🧠 Prompt 技巧 & 使用心得

[1] **Willison：Fable's judgement 子代理降級策略**：主迴圈保留旗艦模型做判斷與綜合，實作子代理改用 Sonnet/Haiku 降低成本，實測品質無顯著差異。([來源](https://simonwillison.net/2026/Jul/3/judgement/))

[2] **HN 熱文：Opus 4.8 分析 MRI 挑戰骨科診斷**：開發者餵入 266MB DICOM 資料，AI 判定肩袖為輕度肌腱病變而非醫師診斷的 Grade III 撕裂，引發 368+ 則討論。([來源](https://news.ycombinator.com/item?id=48708941))

[3] **Claude Code v2.1.198 子代理預設背景執行**：子代理完成 worktree 工作後自動 commit、push 並開啟 draft PR，無需停下來詢問使用者。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 🔧 工作流整合案例

[4] **Claude Code v2.1.199 可靠性修復**：子代理被限速或伺服器錯誤後改回傳部分成果而非靜默失敗；串流中斷保留已收內容並附未完成提示。([來源](https://github.com/anthropics/claude-code/releases))

[5] **Claude in Chrome 正式 GA**：v2.1.198 將 Chrome 擴充套件推向全面可用，瀏覽器工具改為單次批次載入，減少初始化延遲。([來源](https://code.claude.com/docs/en/changelog))

[6] **Trusted Devices 裝置驗證上線**：Team/Enterprise 管理員可要求成員以 Face ID / Touch ID / Windows Hello 驗證裝置後才能遠端操控 Claude Code。([來源](https://releasebot.io/updates/anthropic/claude))

## 🛠️ 新工具 & 套件

[7] **llm-coding-agent 0.1a0 發布**：Simon Willison 將 LLM 函式庫演化為代理框架，實作類 Claude Code 架構含檔案讀寫與指令執行工具，支援 `llm code --yolo` 模式。([來源](https://simonwillison.net/2026/Jul/2/llm-coding-agent/))

[8] **Confluent MCP Server & Agent Skills GA**：開源與託管 MCP Server 讓 AI 代理直接存取 Kafka、Schema Registry 與 Connector，Agent Skills 內建平台最佳實踐。([來源](https://www.confluent.io/blog/ai-developer-tools-mcp-server-agent-skills-ga/))

[9] **Claude Code v2.1.199 堆疊技能載入**：`/skill-a /skill-b` 連續指令現可一次載入最多五個技能，SSL 憑證錯誤改為立即失敗並附修復提示。([來源](https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md))

## 💬 社群熱門討論

[10] **放射科醫師反駁 AI MRI 判讀**：多位執業放射科醫師在 HN 指出 AI 缺乏臨床脈絡與觸診資訊，警告不應以 LLM 輸出取代專業影像診斷。([來源](https://news.ycombinator.com/item?id=48708941))

[11] **Linux 背景代理守護程序修復**：v2.1.199 修復不乾淨關機後守護程序每約 50 秒自殺並殺死所有執行中代理的 bug。([來源](https://github.com/anthropics/claude-code/releases))

[12] **阿里巴巴禁用 Claude Code**：因隱寫術追蹤事件，阿里巴巴內部全面禁止使用 Claude Code，凸顯中國科技企業對外部 AI 工具信任危機。([來源](https://thenextweb.com/news/alibaba-bans-claude-code-anthropic-tracking-chinese-users))
