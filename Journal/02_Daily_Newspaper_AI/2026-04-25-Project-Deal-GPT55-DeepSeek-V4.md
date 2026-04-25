# AI工作流日報 — 2026-04-25
> 涵蓋範圍：2026-04-24 06:00 ~ 2026-04-25 06:00 (TST)

> 📌 Claude 摘要：本日焦點為 Anthropic 發布 Project Deal agent 交易實驗、GPT-5.5 與 DeepSeek V4 同日登場，以及 Google 400 億美元投資 Anthropic 確認。Agent 自主商務與多模型競爭進入白熱化階段。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code 品質下降事後報告**：Anthropic 公布三項根因——推理努力降級、session 記憶 bug、系統提示過度精簡，均已修復。([來源](https://www.anthropic.com/engineering/april-23-postmortem))

[2] **用量上限全面重置**：作為補償，Anthropic 4/23 起重置所有訂閱者的使用限額。([來源](https://simonwillison.net/2026/Apr/24/recent-claude-code-quality-reports/))

[3] **Pro/Max 預設推理努力回歸 high**：v2.1.117 起 Opus 4.6 與 Sonnet 4.6 預設回到 high effort，改善輸出品質。([來源](https://clskillshub.com/blog/claude-code-april-2026-updates))

## 🔧 工作流整合案例

[4] **Project Deal：Agent 對 Agent 交易實驗**：69 名員工委託 Claude 代理買賣，完成 186 筆交易逾 $4,000。([來源](https://techcrunch.com/2026/04/25/anthropic-created-a-test-marketplace-for-agent-on-agent-commerce/))

[5] **進階模型談判優勢明顯**：實驗中 Opus 4.5 代理比 Haiku 4.5 取得更好交易結果，弱模型使用者未察覺差距。([來源](https://the-decoder.com/anthropic-says-stronger-ai-models-cut-better-deals-and-the-losers-dont-even-notice/))

[6] **GPT-5.5 上線：統一超級應用**：OpenAI 發布 GPT-5.5，整合編碼、瀏覽器、資料分析為單一介面。([來源](https://openai.com/index/introducing-gpt-5-5/))

## 🛠️ 新工具 & 套件

[7] **DeepSeek V4 Flash/Pro 預覽版開源**：支援 100 萬 token 上下文，編碼基準測試領先。([來源](https://www.cnbc.com/2026/04/24/deepseek-v4-llm-preview-open-source-ai-competition-china.html))

[8] **Claude Code v2.1.118 發布**：新增自訂主題、MCP hook 工具呼叫、DISABLE_UPDATES 環境變數。([來源](https://changelogs.directory/tools/claude-code/releases/2.1.118))

[9] **Qwen3.6-27B 開源**：首個支援 Thinking Preservation 的開源模型，262K 原生上下文。([來源](https://huggingface.co/Qwen/Qwen3.6-27B))

[10] **Rate Limits API 上線**：開發者可程式化查詢組織與工作區速率限制。([來源](https://platform.claude.com/docs/en/api/rate-limits))

## 💬 社群熱門討論

[11] **Google 400 億美元投資 Anthropic**：首批 100 億現金，估值 3,500 億；達標後再追加 300 億。([來源](https://www.cnbc.com/2026/04/24/google-to-invest-up-to-40-billion-in-anthropic-as-search-giant-spreads-its-ai-bets.html))

[12] **v2.1.119/120 回歸 bug 頻傳**：社群報告 30+ 項回歸，建議暫時退回 v2.1.117。([來源](https://gist.github.com/yurukusa/a866b4cd2976486156a00c190c39cef6))

[13] **Fed 與財政部就 Mythos 網安風險召集銀行高層**：擔憂近乎自主的漏洞掃描能力失控。([來源](https://www.sullcrom.com/insights/memo/2026/April/Treasury-Secretary-Federal-Reserve-Chair-Warn-Bank-CEOs-About-Cybersecurity-Risks-Posed-Anthropics-New-AI-Model))

[14] **HN 熱議 Claude Code 是否變笨**：AMD AI 主管公開表示更新後品質下降，引發大量討論。([來源](https://news.ycombinator.com/item?id=47696210))
