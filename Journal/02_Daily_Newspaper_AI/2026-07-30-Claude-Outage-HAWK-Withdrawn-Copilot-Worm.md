# AI工作流日報 — 2026-07-30
> 涵蓋範圍：2026-07-29 06:00 ~ 2026-07-30 06:00 (TST)

> 📌 Claude 摘要：Claude全球當機約三小時是今日最直接衝擊，同時HAWK正式退出NIST標準化代表Mythos密碼學能力獲實質驗證。安全面則出現Copilot for Word自傳播蠕蟲漏洞，凸顯Agent整合進生產力工具後的新攻擊面。MCP無狀態規範上線後各方分析企業部署影響，SDK月下載量破4億顯示生態已達臨界量。

## 🧠 Prompt 技巧 & 使用心得

[1] **Opus 5 Auto Mode防注入實測達0%成功率**：在129個瀏覽器型prompt injection場景中，Opus 5結合輸入掃描與任務阻斷全數攔截。([來源](https://aiagentstore.ai/ai-agent-news/this-week))

[2] **65%企業AI失敗源於Harness非模型**：Frank's World文章指出context drift、schema misalignment、state degradation三類harness缺陷為主因。([來源](https://www.franksworld.com/2026/07/30/debugging-ai-agents-when-the-harness-not-the-model-is-to-blame/))

## 🔧 工作流整合案例

[3] **MCP 2026-07-28無狀態規範正式上線**：最大改版轉為request/response無狀態核心，支援Kubernetes/serverless部署，加強OAuth/OIDC授權與12個月棄用保證。([來源](https://www.theregister.com/ai-and-ml/2026/07/29/mcp-gets-an-enterprise-makeover/5280027))

[4] **MCP SDK月下載量突破4億**：年增4倍，TypeScript/Python/Go/C#四套官方SDK已支援新規範，成為AI Agent連接應用的產業標準。([來源](https://claude.com/blog/bringing-mcp-2026-07-28-to-claude))

[5] **Copilot for Word自傳播AI蠕蟲漏洞曝光**：Willison分享Håkon Måløy研究，白底白字隱藏prompt可跨文件自動複製擴散，微軟已部署多項緩解但攻擊類型仍可重現。([來源](https://simonwillison.net/2026/Jul/29/ai-worming-through-word/))

## 🛠️ 新工具 & 套件

[6] **HAWK-256正式退出NIST後量子標準化**：追蹤報導——HAWK團隊確認Mythos攻擊將安全餘量從2^64降至2^38，正式撤回提案，60小時AI輔助研究超越兩年專家審查。([來源](https://thehackernews.com/2026/07/claude-ai-just-cracked-post-quantum.html))

[7] **Opus 5成Claude Code預設Opus模型**：claude-opus-5定價$10/$50 per Mtok，支援1M context與fast mode，Vertex/Bedrock啟動問題已修復。([來源](https://www.gradually.ai/en/changelogs/claude-code/))

## 💬 社群熱門討論

[8] **Claude全球當機約三小時**：7/29 19:49-22:36 UTC，529 Overloaded錯誤波及所有模型與API，逾2000用戶回報，Claude Code佔約半數。([來源](https://cybersecuritynews.com/claude-worldwide-outage-disrupts-users/))

[9] **OpenAI與Anthropic以公司名義背書Pacing the Frontier**：追蹤——兩公司7/29正式聲明支持建立未來「減速能力」的國際框架，強調非立即暫停而是預建機制。([來源](https://www.techtimes.com/articles/322125/20260729/openai-anthropic-formally-back-plan-slow-ai-that-writes-its-own-code.htm))

[10] **Opus 5是否威脅獨立開發者存亡？**：Frank's World分析Opus 5以近Fable水準半價提供編碼能力，能自行撰寫、驗證、修復程式碼，引發indie hacker競爭力討論。([來源](https://www.franksworld.com/2026/07/30/is-anthropics-claude-opus-5-a-threat-to-the-indie-hacker-dream/))
