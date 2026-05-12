# AI工作流日報 — 2026-05-12
> 涵蓋範圍：2026-05-11 06:00 ~ 2026-05-12 06:00 (TST)

> 📌 Claude 摘要：Anthropic 今日三箭齊發——Claude for Legal 攜 12 款法律插件與 20+ MCP 連接器正式上線、Claude Platform on AWS 全面 GA、Claude Code Agent View 研究預覽登場。同時 Bloomberg 報導 Anthropic 正洽談以 9000 億美元估值融資 300 億美元，若成真將超越 OpenAI。產業面則見 GitLab 宣布為「agentic era」裁員重組，Google 攔截首起 AI 生成零日漏洞攻擊。

## 🧠 Prompt 技巧 & 使用心得
[1] **Simon Willison：LLM CLI 放進 shebang line**：示範在腳本第一行直接用 `llm` 指令，讓 shell 腳本自帶 AI 推理能力，無需額外包裝。([來源](https://simonwillison.net/2026/May/11/llm-shebang/))
[2] **「Your AI Use Is Breaking My Brain」**：Simon Willison 轉載 Jason Koebler 憤怒文，指 AI 生成內容已令網路閱讀體驗全面惡化，形成「殭屍網路」。([來源](https://simonwillison.net/2026/May/11/zombie-internet/))
[3] **James Shore：AI Agent 須降低維護成本**：Simon Willison 引用 Shore 觀點，認為 AI 編碼代理若不能減少長期維護負擔，終將被淘汰。([來源](https://simonwillison.net/2026/May/11/james-shore/))

## 🔧 工作流整合案例
[4] **Claude for Legal 正式上線**：Anthropic 推出 12 款法律實務插件（商事、勞動、訴訟等）與 20+ MCP 連接器，整合 Thomson Reuters CoCounsel、DocuSign、Everlaw。([來源](https://www.artificiallawyer.com/2026/05/12/claude-for-legal-launches-may-reshape-the-legal-tech-world/))
[5] **Thomson Reuters × Anthropic 擴大合作**：新 MCP 整合讓 Claude 直接存取 Westlaw 判例資料庫與 Practical Law 指引。([來源](https://the-decoder.com/anthropic-expands-legal-ai-offerings-with-new-cowork-plugins/))
[6] **Claude Platform on AWS 全面 GA**：Claude API 原生登陸 AWS，支援 IAM 認證、CloudTrail 稽核，涵蓋 Managed Agents、Skills、MCP Connector 等功能，全球 17 區域可用。([來源](https://aws.amazon.com/about-aws/whats-new/2026/05/claude-platform-aws/))
[7] **Claude Code Agent View（研究預覽）**：新 CLI 面板一覽所有 session 狀態，支援 `claude agents` 開啟、`/bg` 背景執行、`--bg` 直接啟動，Pro/Max/Team/Enterprise 均可用。([來源](https://claude.com/blog/agent-view-in-claude-code))

## 🛠️ 新工具 & 套件
[8] **Claude Code v2.1.139**：新增 `/goal` 指令讓 Claude 持續執行直到達標、`--plugin-url` 支援 .zip 插件下載、PostToolUse hooks 全工具可替換輸出。([來源](https://code.claude.com/docs/en/changelog))
[9] **Anthropic NLA 可解釋性工具**：Natural Language Autoencoders 將模型內部激活轉為自然語言解釋，並開源訓練程式碼與 Neuronpedia 互動前端。([來源](https://www.anthropic.com/research/natural-language-autoencoders))
[10] **Hermes Agent v0.13.0 "Tenacity"**：Nous Research 加入 Kanban 多代理任務板、Checkpoints v2 狀態修剪、Google Chat 支援，目前以日均 2240 億 token 領先 OpenRouter 排行。([來源](https://www.marktechpost.com/2026/05/10/openclaw-vs-hermes-agent-why-nous-researchs-self-improving-agent-now-leads-openrouters-global-rankings/))

## 💬 社群熱門討論
[11] **Anthropic 洽談 $300 億融資、估值逾 $9000 億**：Bloomberg 報導若成真將超越 OpenAI 的 $8520 億估值，IPO 最快十月。([來源](https://www.bloomberg.com/news/articles/2026-05-12/anthropic-in-talks-to-raise-30-billion-at-900-billion-valuation))
[12] **GitLab 為「agentic era」裁員重組**：縮減 30% 國家據點、砍三層管理、R&D 改組為 60 個小團隊，六月一日前完成新架構。([來源](https://simonwillison.net/2026/May/11/gitlab-act-2/))
[13] **Google 攔截首起 AI 生成零日漏洞攻擊**：駭客用 AI 模型發現網路管理工具漏洞並繞過雙因素驗證，Google 威脅情報團隊及時通報開發者阻止大規模利用。([來源](https://www.cnbc.com/2026/05/11/google-thwarts-effort-hacker-group-use-ai-mass-exploitation-event.html))
[14] **日本政府洽談取得 Claude Mythos 存取權**：因 Mythos 可識別可利用軟體漏洞，日本希望用於國防資安。([來源](https://letsdatascience.com/news/japan-seeks-access-to-anthropics-claude-mythos-0f6c9788))
