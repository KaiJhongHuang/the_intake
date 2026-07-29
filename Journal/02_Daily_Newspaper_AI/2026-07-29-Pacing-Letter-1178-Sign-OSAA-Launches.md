# AI工作流日報 — 2026-07-29
> 涵蓋範圍：2026-07-28 06:00 ~ 2026-07-29 06:00 (TST)

> 📌 Claude 摘要：今日焦點集中在 AI 治理與安全層面——1,178 名前線實驗室員工聯署「Pacing the Frontier」公開信要求建立國際減速機制，Nvidia 同步成立 Open Secure AI Alliance 回應 OpenAI 沙盒逃逸事件，而 Amodei 發布開放權重立場文引爆 HN 第一。此為 Claude 摘要，帶有推測成分。

## 🧠 Prompt 技巧 & 使用心得
[1] **1,178名AI員工聯署「Pacing the Frontier」**：要求美國政府建立國際機制，在自動化AI研發失控前保留減速選項；Anthropic揭露超過80%產品代碼由Claude撰寫。([來源](https://www.washingtonpost.com/technology/2026/07/29/openai-anthropic-endorse-call-government-pace-ai-progress/))
[2] **OpenAI與Anthropic以公司名義背書公開信**：Amodei、Pachocki、Mark Chen等高層簽署，信中強調並非呼籲立即暫停，而是預先建立「方向盤」。([來源](https://www.techtimes.com/articles/322125/20260729/openai-anthropic-formally-back-plan-slow-ai-that-writes-its-own-code.htm))
[3] **Zvi深度解讀Pacing信件**：認為信件核心在於遞迴自我改進風險，呼籲在引擎進入遞迴檔位前備好煞車。([來源](https://thezvi.wordpress.com/2026/07/29/frontier-lab-employee-open-letter-calls-for-being-able-to-pace-the-frontier/))

## 🔧 工作流整合案例
[4] **MCP 2026-07-28規範正式落地Claude**：無狀態核心、OAuth/OIDC授權強化、Apps與Tasks版本化擴充、嵌入式UI與企業託管驗證上線，連接器目錄突破950個。([來源](https://claude.com/blog/bringing-mcp-2026-07-28-to-claude))
[5] **Cognizant升級為Anthropic全球首席合作夥伴**：超過30,000名員工取得Claude認證，在製造、生技、保險領域部署Claude，合約審閱時間縮短40%。([來源](https://www.anthropic.com/news/cognizant-anthropic))
[6] **Claude Code將/verify與/code-review改為手動觸發**：不再自動執行，減少不必要的計算開銷。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 🛠️ 新工具 & 套件
[7] **Nvidia成立Open Secure AI Alliance（OSAA）**：37+成員含Microsoft、IBM、SpaceX、Hugging Face、Linux Foundation，開源AI網路防禦工具，回應OpenAI模型入侵HF事件。([來源](https://blogs.nvidia.com/blog/open-secure-ai-alliance/))
[8] **Codex Security CLI與TypeScript SDK發布**：可掃描倉庫漏洞、審查變更、在CI中執行安全檢查並追蹤修復進度。([來源](https://curatedaitools.substack.com/p/todays-featured-ai-tools-in-one-sentence-a13))
[9] **medley：為Claude Code派發任務的多代理協調器**：讓Claude Code接收mission後自動派生一組代理團隊協同完成工作。([來源](https://curatedaitools.substack.com/p/todays-featured-ai-tools-in-one-sentence-a13))

## 💬 社群熱門討論
[10] **Amodei發布「Our position on open-weights models」登HN第一**：明確表示Anthropic從未主張禁止開放權重，提出三項替代政策：阻截晶片走私、打擊工業級蒸餾、要求安全測試。([來源](https://www.anthropic.com/news/position-open-weights-models))
[11] **WSJ報導矽谷對Anthropic信任危機加深**：創辦人與研究者轉向低成本開放權重模型，Fable 5隱性護欄與Design工具爭議持續發酵。([來源](https://www.shopifreaks.com/anthropic-faces-a-silicon-valley-backlash-as-founders-and-researchers-move-to-cheaper-open-weight-models-from-rival-labs/))
[12] **Claude/Anthropic於7/29出現服務中斷**：DownDetector顯示美東時間15:50起數百用戶回報當機。([來源](https://community.designtaxi.com/topic/34256-is-claude-anthropic-ai-down-july-29-2026/))
