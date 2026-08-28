# AI工作流日報 — 2026-08-28
> 涵蓋範圍：2026-08-27 06:00 ~ 2026-08-28 06:00 (TST)

> 📌 Claude 摘要：Anthropic 發布 Model Hardware Standard 讓 AI 代理操控實體設備，同日聯邦法官推翻五角大廈對 Anthropic 的供應鏈黑名單。Claude Code 連發 v2.1.248/250 加入 restricted mode。Z.ai 的神祕模型 Ox Alpha 確認為 GLM-5.3-Flash，320B 參數 MIT 開源。（以上為 Claude 綜合觀察，非事實報導）

## 🧠 Prompt 技巧 & 使用心得
[1] **Claude Code SendFeedback 工具**：v2.1.247 新增自動草擬 bug report，工具失敗或使用者回報問題時自動撰寫回饋草稿待審核送出。([來源](https://www.explainx.ai/blog/claude-code-drafts-bug-reports-feedback-august-2026))
[2] **Restricted Mode 上線**：v2.1.248 加入 --restricted 旗標，移除執行指令與 WebFetch 工具，檔案操作限定工作目錄，適合安全受控環境部署。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.248))
[3] **per-agent cacheTtl 設定**：v2.1.248 新增 experimental.cacheTtl（"5m"/"1h"），可在 agent frontmatter 指定個別代理的 prompt cache TTL。([來源](https://www.havoptic.com/tools/claude-code))

## 🔧 工作流整合案例
[4] **Model Hardware Standard（MHS）發布**：Anthropic 發表實體設備操控規範研究預覽，讓 AI 代理操作顯微鏡、液體處理器、機械臂等儀器，整合時間從數週縮短至數小時。([來源](https://www.cnbc.com/2026/08/27/anthropic-pushes-into-physical-world-with-new-standard-to-help-ai-agents-operate-machines.html))
[5] **Genentech 以 MHS 自動化蛋白質分析**：研究人員串接液體處理器、機械臂與讀板儀，完成全自動蛋白質分析流程。([來源](https://fortune.com/2026/08/27/anthropic-makes-first-move-into-physical-ai-with-universal-standard-for-scientists-manufacturing/))
[6] **QuEra 量子電腦雷射校準**：透過 MHS 讓 AI 代理以 99.3% 成功率自動恢復雷射操作頻率，無需人工介入。([來源](https://www.pymnts.com/news/artificial-intelligence/2026/anthropic-previews-standard-for-ai-control-of-physical-devices/))
[7] **Keenable $26M 種子輪出隱身**：提供 AI 代理專用 web search 基礎設施，含 1000 億文件索引與 MCP server，無需 API key 即可每小時 1000 次查詢。([來源](https://techcrunch.com/2026/08/25/accel-backed-keenable-is-indexing-the-web-for-ai-agents/))

## 🛠️ 新工具 & 套件
[8] **Claude Code v2.1.250**：8/27 釋出，包含 bug fixes 與可靠性改進；v2.1.248 同日釋出 restricted mode 與 MCP v2 連線修復。([來源](https://code.claude.com/docs/en/changelog))
[9] **GLM-5.3-Flash 揭曉**：Z.ai 的神祕模型 Ox Alpha 確認為 GLM-5.3-Flash，320B 總參數 / 18B 活躍，原生多模態，MIT 開源授權。([來源](https://www.gmicloud.ai/en/blog/glm-53-flash-the-stealth-model-that-became-the-talk-of-the-timeline))
[10] **Transformers v5.16.1**：Hugging Face 加入 GLM-5.3-Flash 原生支援，含張量並行修復與安全相關 kernel pinning。([來源](https://github.com/huggingface/transformers/releases))
[11] **LoopX 持續走紅 GitHub**：跨 Codex、Claude Code 的輕量狀態核心，提供持久目標、配額感知自動喚醒與可驗證交接，適合長時間多代理協作。([來源](https://github.com/huangruiteng/loopx))

## 💬 社群熱門討論
[12] **聯邦法官推翻五角大廈 Anthropic 黑名單**：法官裁定國防部將 Anthropic 列為供應鏈風險「違法且無據」，違反第一與第五修正案，發出永久禁令。([來源](https://www.cnbc.com/2026/08/28/judge-blocks-pentagon-blacklist--anthropic-.html))
[13] **MHS 模型不可知設計引關注**：MHS 明確不綁定 Claude，任何模型皆可使用，Doosan Robotics、Tecan、Universal Robots、Raspberry Pi 等已加入測試。([來源](https://www.technology.org/2026/08/28/anthropic-model-hardware-standard-research-preview/))
[14] **Ox Alpha 身世之謎揭曉**：GLM-5.3-Flash 以匿名上架 OpenRouter 一週登頂使用榜，Bloomberg 與 Business Insider 8/26 確認為 Z.ai 出品。([來源](https://llm-stats.com/blog/research/glm-5.3-flash-launch))
