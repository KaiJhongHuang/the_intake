# AI工作流日報 — 2026-04-08
> 涵蓋範圍：2026-04-07 06:00 ~ 2026-04-08 06:00 (TST)

> 📌 Claude 摘要：Anthropic 發布 Claude Mythos Preview 並啟動 Project Glasswing，僅限約 50 家合作夥伴用於防禦性資安研究；Claude 連續第二天出現服務中斷；NousResearch 釋出 Hermes Agent v0.8.0，Agent 生態持續擴張。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code /powerup 互動教學上線**：v2.1.90 新增終端內互動式動畫教學，直接在 CLI 學習功能。([來源](https://daily1bite.com/en/blog/ai-tutorial/claude-code-april-2026-update))

[2] **MCP 工具回傳上限提升至 500K 字元**：v2.1.91 透過 _meta 標註可將單次結果上限設為 50 萬字，大幅改善大型輸出場景。([來源](https://help.apiyi.com/en/claude-code-v2-1-92-mcp-persistence-powerup-tutorial-en.html))

[3] **多 Agent 模式成社群主流技巧**：主會話用 Opus 做複雜推理，子代理用 Sonnet 做聚焦任務，Reddit 社群大量討論此模式。([來源](https://www.morphllm.com/claude-code-reddit))

[4] **Headless 模式新增 defer 權限決策**：PreToolUse hook 可暫停工具呼叫，之後用 --resume 恢復，適合 CI/CD 整合。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 🔧 工作流整合案例

[5] **Simon Willison 用 Claude Code 研究各家 LLM API**：發布 research-llm-apis，用 Claude Code 撰寫 curl 指令並擷取各供應商 HTTP API 回應。([來源](https://simonwillison.net/))

[6] **Simon Willison 評論 Project Glasswing**：認為限制 Mythos 僅供資安研究者使用是合理且必要的做法。([來源](https://simonwillison.net/2026/Apr/7/project-glasswing/))

[7] **Claude Code /cost 新增模型與快取拆分**：訂閱用戶可查看各模型及 cache-hit 的費用明細，便於成本追蹤。([來源](https://daily1bite.com/en/blog/ai-tutorial/claude-code-april-2026-update))

## 🛠️ 新工具 & 套件

[8] **Claude Mythos Preview 發布（Project Glasswing）**：Anthropic 最強模型，已發現數千個零日漏洞含 27 年 OpenBSD 舊 bug，僅限約 50 家合作夥伴使用。([來源](https://fortune.com/2026/04/07/anthropic-claude-mythos-model-project-glasswing-cybersecurity/))

[9] **Hermes Agent v0.8.0 釋出**：NousResearch 的自我進化 Agent，新增活動偵測式 timeout、支援 6 種終端後端與多平台閘道。([來源](https://github.com/nousresearch/hermes-agent))

[10] **Goose 移至 Linux Foundation AAIF**：Block 的開源 AI Agent 支援 15+ 供應商與 MCP 協定，正式納入 Linux 基金會治理。([來源](https://aitoolly.com/ai-news/article/2026-04-07-block-launches-goose-an-open-source-extensible-ai-agent-for-automated-engineering-tasks))

[11] **Hugging Face TRL v1.0 正式發布**：統一 SFT、Reward Modeling、DPO、GRPO 後訓練流程，從研究工具轉為生產級框架。([來源](https://www.marktechpost.com/2026/04/01/hugging-face-releases-trl-v1-0-a-unified-post-training-stack-for-sft-reward-modeling-dpo-and-grpo-workflows/))

[12] **Mistral Voxtral TTS 開放權重**：支援零樣本語音複製、多語言、即時串流的文字轉語音模型，權重上架 Hugging Face。([來源](https://huggingface.co/blog))

## 💬 社群熱門討論

[13] **Claude 連續第二天服務中斷**：4/8 Sonnet 4.6 於 UTC 07:00-09:50 出現高錯誤率，450+ 用戶回報，影響 Chat 與 Code。([來源](https://www.ibtimes.com.au/claude-ai-down-again-april-8-2026-anthropic-outage-hits-users-after-yesterdays-major-incident-1865761))

[14] **HN 討論「AI 大生產力恐慌」**：Bloomberg 報導 AI 編碼代理掀起高壓競速，vibe coding 一年後氛圍已變調。([來源](https://news.ycombinator.com/item?id=47467922))

[15] **Anthropic 營收突破 300 億美元**：年化營收超越 OpenAI，年花百萬以上企業客戶突破 1,000 家，IPO 最快十月。([來源](https://www.tradingkey.com/analysis/stocks/us-stocks/261756528-anthropic-openai-ipo-tradingkey))

[16] **Mythos 零日漏洞發現引發資安討論**：The Hacker News 報導 Mythos 在主要作業系統及瀏覽器中發現數千個高嚴重性漏洞。([來源](https://thehackernews.com/2026/04/anthropics-claude-mythos-finds.html))
