# AI工作流日報 — 2026-04-14
> 涵蓋範圍：2026-04-13 06:00 ~ 2026-04-14 06:00 (TST)

> 📌 Claude 摘要：本日三條主線——(1) AWS 與 Anthropic 雙邊同步：Bedrock 正式上架 Claude Mythos Preview（Gated）與全新 Agent Registry，把 Glasswing 聯盟從宣告推進到雲端可用；(2) Claude for Word 完成 Office 三件套（Word/Excel/PowerPoint）原生整合，正面對決 Copilot；(3) Mythos SWE-bench 93.9% vs Opus 4.6 80.8% 公開，社群辯論「選擇性釋出」的實際防守紅利。此為 Claude 綜合觀察，非事實報導。

## 🧠 Prompt 技巧 & 使用心得

[1] **Boris Cherny 實測工作流**：Claude Code 作者公開自己使用方式「驚人普通」——CLAUDE.md 僅 2.5k tokens，主要靠 slash commands 累積 inner loop。([來源](https://howborisusesclaudecode.com/))

[2] **CLAUDE.md 作為錯誤紀錄本**：每次 Claude 做錯，就把「這樣做不對」加進 CLAUDE.md，讓模型下次自動避開。([來源](https://getpushtoprod.substack.com/p/how-the-creator-of-claude-code-actually))

[3] **/commit-push-pr 模式**：slash command 內嵌 bash 預計算 git status，避免模型來回問，日常每日用十幾次。([來源](https://x.com/bcherny/status/2007179847949500714))

[4] **@.claude tag on PR**：在同事 PR 上 tag @.claude，自動把該 PR 的學習寫回 CLAUDE.md，集中團隊知識。([來源](https://karozieminski.substack.com/p/boris-cherny-claude-code-workflow))

[5] **Mythos 漏洞掃描 Workflow**：獨立容器跑 Claude Code + Mythos，自主讀碼、跑專案、輸出 PoC exploit 與重現步驟。([來源](https://red.anthropic.com/2026/mythos-preview/))

## 🔧 工作流整合案例

[6] **AWS Bedrock 上架 Claude Mythos Preview**：US East (N. Virginia) Gated 版本，僅限 Project Glasswing 白名單組織，由 AWS team 直接聯絡開通。([來源](https://aws.amazon.com/about-aws/whats-new/2026/04/amazon-bedrock-claude-mythos/))

[7] **AWS Agent Registry 預覽**：AgentCore 下的 AI Agent / Tool / MCP server 私有目錄，含草稿→待審→發佈 approval workflow 與 CloudTrail 審計。([來源](https://aws.amazon.com/blogs/machine-learning/the-future-of-managing-agents-at-scale-aws-agent-registry-now-in-preview/))

[8] **Registry 作為 MCP server**：可被 Kiro、Claude Code 等任何 MCP-compatible client 直接查詢，避免組織內重複造輪子。([來源](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-claude-mythos-preview-in-amazon-bedrock-aws-agent-registry-and-more-april-13-2026/))

[9] **Claude for Word 公開 Beta**：Mac / Windows Word 內建 sidebar，審查長文件、redline、改寫條文皆保留樣式編號。([來源](https://www.openpr.com/news/4468672/anthropic-rolls-out-claude-for-word-add-in-now-full-microsoft))

[10] **Word 改寫走 Track Changes**：Claude 編輯全部以追蹤修訂呈現，使用者可逐條 accept / reject，同事互改流程無縫。([來源](https://www.thurrott.com/a-i/334834/anthropic-launches-claude-for-word-in-beta))

[11] **Office 三件套共享 context**：沿用 3 月 Excel/PowerPoint 共享 context 機制，跨檔跨應用不用再複製貼上。([來源](https://thenextweb.com/news/dario-amodei-london-united-kingdom))

## 🛠️ 新工具 & 套件

[12] **Claude Mythos SWE-bench 93.9%**：Opus 4.6 為 80.8%，InfoQ 形容為「step change」，同步投入 $100M usage credits 給修漏洞組織。([來源](https://www.infoq.com/news/2026/04/anthropic-claude-mythos/))

[13] **Mythos 在 Bedrock 定位為新 model class**：主打 cybersecurity、autonomous coding、long-running agents 三大工作負載。([來源](https://docs.aws.amazon.com/bedrock/latest/userguide/model-card-anthropic-claude-mythos-preview.html))

[14] **Claude for Word 僅限 Team / Enterprise 方案**：相容 Web、Windows (M365 v2205+)、Mac (v16.61+)。([來源](https://www.issuewire.com/anthropic-rolls-out-claude-for-word-add-in-now-full-microsoft-office-suite-natively-supports-claude-1862154066706488))

[15] **Mythos 瞄準法律業**：TechRadar 指初期 use case 以合約審查、條款比對為主，直接打 Copilot 弱項。([來源](https://www.techradar.com/pro/anthropic-is-bringing-claudes-ai-power-to-microsoft-word))

## 💬 社群熱門討論

[16] **Mythos「非對稱釋出」再起爭議**：選擇性開放 Glasswing 聯盟 vs 中小企業裸奔，社群辯論壓縮 N-day 視窗的實際代價。([來源](https://www.wiz.io/blog/claude-mythos))

[17] **Simon Willison 引 Bryan Cantrill**：「LLM 工作不花錢、不為未來時間成本優化，樂於往垃圾層蛋糕堆上加料」，延伸 slop 警戒。([來源](https://simonwillison.net/2026/Apr/13/bryan-cantrill/))

[18] **Boris Cherny 貼文連帶爆紅**：VentureBeat、Hacker News 都瘋傳 .claude/ 資料夾解剖，Hacker News 那篇衝到 556 分。([來源](https://venturebeat.com/technology/the-creator-of-claude-code-just-revealed-his-workflow-and-developers-are))

[19] **Harness Engineering 成新顯學**：CLAUDE.md + hooks + custom commands + MCP + CI workflow，高手已從「提示工程」轉向「圍繞模型造 harness」。([來源](https://medium.com/@richardhightower/claude-code-2026-the-daily-operating-system-top-developers-actually-use-d393a2a5186d))

[20] **Reddit 對 Mythos 分成兩派**：r/ClaudeAI、r/claude 一邊驚呼能力，一邊質疑「無具名研究員證實、像都市傳說」。([來源](https://medium.com/data-science-in-your-pocket/claude-mythos-is-fake-a3a6c5cb02db))
