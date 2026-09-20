# AI工作流日報 — 2026-09-21
> 涵蓋範圍：2026-09-20 06:00 ~ 2026-09-21 06:00 (TST)

> 📌 Claude 摘要：v2.1.278將auto mode分類器預設切換至server端，API/Enterprise/Bedrock/Vertex/Foundry用戶不再被收取分類器開銷；Willison發布llm-keys-ui 0.1讓遠端代理機器安全設定API金鑰；反壟斷訴訟控四巨頭「減速共謀」擴散至CBS等十餘媒體；CNN「AI幻覺險引美中衝突」報導被Gizmodo等轉載升溫至「差點開戰」；GitHub 9/20趨勢顯示代理工具鏈主導、edge AI興起。以上為推測性整理。

## 🧠 Prompt 技巧 & 使用心得
[1] **v2.1.278 auto mode server classifier預設**：API與Enterprise用戶自動走server端分類器，不再計費分類器開銷。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.278))
[2] **Willison llm-keys-ui 0.1發布**：為llm CLI提供本地Web UI設定API金鑰，適合遠端代理機器不暴露金鑰。([來源](https://simonwillison.net/2026/Sep/20/llm-keys-ui/))

## 🔧 工作流整合案例
[3] **datasette-explain 0.2.2發布**：Willison更新SQL解釋外掛，輸入時即時驗證並說明SQL語法。([來源](https://simonwillison.net/2026/Sep/20/datasette-explain/))
[4] **自建Claude Code環境進入公測**：Team與Enterprise可在自有基礎設施上運行session，貼近內部工具鏈。([來源](https://claude.com/blog/run-claude-code-sessions-on-your-own-compute))

## 🛠️ 新工具 & 套件
[5] **v2.1.278發布**：新增/status顯示auto mode server狀態列；Bedrock等可用CLAUDE_CODE_AUTO_MODE_SERVER=0退出。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.278))
[6] **cactus-compute/needle持續登GitHub趨勢**：2-bit量化基礎模型14MB即可在樹莓派跑500+ tok/s，Needle 3已上HuggingFace。([來源](https://github.com/cactus-compute/needle))

## 💬 社群熱門討論
[7] **反壟斷訴訟覆蓋擴大**：CBS、Quartz等十餘家9/20轉載，控Anthropic等四巨頭違Sherman Act。([來源](https://www.cbsnews.com/news/ai-slowdown-lawsuit-openai-anthropic-google/))
[8] **AI幻覺險引美中衝突持續升溫**：Gizmodo標題「差點開戰」，Engadget、TechTimes同日跟進報導。([來源](https://gizmodo.com/almost-started-a-war-us-military-nearly-boarded-a-chinese-ship-based-on-bad-intel-from-ai-2000814290))
[9] **GitHub 9/20趨勢：代理工具鏈主導**：agent skill、token效率工具、edge AI成三大方向，cloudflare/security-audit-skill續居前列。([來源](https://github.com/kouweizhu/agents-radar/issues/118))
[10] **Willison引voxium語錄談大公司AI導入**：「沒人知道任何事」引發HN討論企業AI落地現實。([來源](https://simonwillison.net/2026/Sep/20/voxium/))
