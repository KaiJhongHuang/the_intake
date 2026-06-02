# AI工作流日報 — 2026-06-02
> 涵蓋範圍：2026-06-01 06:00 ~ 2026-06-02 06:00 (TST)

> 📌 Claude 摘要：Anthropic 搶先 OpenAI 向 SEC 遞交 S-1 機密上市申請，同日 Glasswing 擴展至 200 組織並承諾數週內公開 Mythos 級模型。Claude Code v2.1.160 發布，但子代理無限迴圈 bug 觸發全球大當機。六月 15 日 Agent SDK 計費分池倒數兩週，開發者社群反應兩極。

## 🧠 Prompt 技巧 & 使用心得
[1] **Claude for Legal 擴增至 90+ Agent**：涵蓋合約審閱、DSAR 回應、索賠圖表等，均可用自然語言客製化。([來源](https://www.artificiallawyer.com/2026/06/01/claude-for-legal-has-over-90-ai-agents/))

[2] **Claude Code v2.1.160 強化安全提示**：寫入 shell 啟動檔（.zshenv 等）前新增確認提示，防止非預期指令執行。([來源](https://code.claude.com/docs/en/changelog))

[3] **acceptEdits 模式攔截建置設定檔**：.npmrc、.bazelrc 等可授予程式碼執行權的檔案，現需額外確認才能寫入。([來源](https://code.claude.com/docs/en/changelog))

## 🔧 工作流整合案例
[4] **Grant Thornton UK 全員部署 Claude**：£5 億投資計畫，審計、稅務、顧問全線導入，為英國四大首例。([來源](https://letsdatascience.com/news/grant-thornton-deploys-anthropic-claude-across-uk-workforce-9fa5407e))

[5] **Microsoft Build 2026 發布 Agent Framework**：AutoGen + Semantic Kernel 合併為單一 SDK，Windows Agent Store 同步上線。([來源](https://visualstudiomagazine.com/articles/2026/06/02/at-build-2026-microsoft-sets-up-windows-as-an-os-for-ai-agents.aspx))

[6] **Windows Local AI 運行時公布**：支援 Snapdragon X Elite / Intel Lunar Lake NPU，6/9 隨 24H2 更新推送。([來源](https://windowsforum.com/threads/microsoft-build-2026-windows-becomes-the-secure-platform-for-local-ai-agents.421680/))

## 🛠️ 新工具 & 套件
[7] **Anthropic 遞交 S-1 機密上市申請**：$965B 估值、$47B 年化營收，搶先 OpenAI 進入 IPO 程序。([來源](https://www.cnbc.com/2026/06/01/anthropic-ipo-s1-prospectus.html))

[8] **Glasswing 擴展至 200 組織、15+ 國家**：新增電力、水利、醫療等產業，已揪出逾 10,000 高危漏洞。([來源](https://www.cnbc.com/2026/06/02/anthropic-mythos-ai-project-glasswing.html))

[9] **Mythos 級模型承諾數週內公開**：Anthropic 表示將在加強網路安全防護後向所有客戶開放 Mythos 級能力。([來源](https://9to5mac.com/2026/06/02/anthropic-expands-glasswing-as-it-promises-public-claude-mythos-class-model-releases/))

[10] **6/15 Agent SDK 計費分池倒數**：claude -p、GitHub Actions、第三方 Agent 移出訂閱額度，Pro 獲 $20/月獨立信用額。([來源](https://thenewstack.io/anthropic-agent-sdk-credits/))

[11] **Claude 舊模型 6/15 退役**：Sonnet 4 與 Opus 4（2025-05-14 版）API 正式下架。([來源](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/))

## 💬 社群熱門討論
[12] **Claude 全球大當機（6/2）**：子代理無限迴圈 bug 導致 token 指數級暴增，API、Console、Claude Code 全線受影響。([來源](https://www.techradar.com/news/live/claude-outage-june-2026))

[13] **Boris Cherny 回應計費分池爭議**：稱第三方工具「難以永續」，$20 訂閱跑 $500 API 量的套利時代結束。([來源](https://devtoolpicks.com/blog/anthropic-splits-claude-subscriptions-agent-sdk-credit-june-2026))

[14] **Code with Claude: Extended Tokyo 6/11 開放**：針對獨立開發者與早期創辦人，含 Applied AI 團隊實作工作坊。([來源](https://claude.com/code-with-claude/tokyo-extended))

[15] **Microsoft Copilot 6/1 當機五小時**：驗證故障導致 Office、VS、Windows 全線癱瘓，多廠商 AI 備援策略受關注。([來源](https://windowsnews.ai/article/microsoft-copilot-outage-june-1-2026-reliability-and-ai-workflow-risk.421251))
