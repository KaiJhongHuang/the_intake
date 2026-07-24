# AI工作流日報 — 2026-07-24
> 涵蓋範圍：2026-07-23 06:00 ~ 2026-07-24 06:00 (TST)

> 📌 Claude 摘要：Opus 5 正式發布成為新旗艦，語音模式同日升級支援全模型切換與跨應用自動化，Claude Code v2.1.219 隨即將 Opus 5 設為預設；安全面則有 FakeAgent 惡意廣告攻擊透過 claude.ai Artifact 散佈木馬，白宮亦指控 Moonshot 蒸餾 Fable 開發 K3。

## 🧠 Prompt 技巧 & 使用心得

[1] **語音模式全模型開放**：Claude 語音模式升級，可在 Opus／Sonnet／Haiku 間即時切換，支援十種語言與跨應用工具調用。([來源](https://techcrunch.com/2026/07/23/anthropic-updates-claude-voice-mode-with-more-capable-models/))

[2] **語音模式連接器整合**：語音對話中可直接操作 Gmail、Google Calendar、Slack、Canva、Notion，免費方案限 Haiku 加一個連接器。([來源](https://techmymoney.com/2026/07/23/claude-voice-mode-adds-sonnet-opus-and-app-connectors/))

[3] **Opus 5 努力程度撥盤**：Opus 5 內建 low／medium／high 努力程度切換，可依任務複雜度調整推理深度與成本。([來源](https://fortune.com/2026/07/24/anthropic-debuts-claude-opus-5-with-feature-that-lets-users-toggle-between-cost-and-capability/))

## 🔧 工作流整合案例

[4] **Claude Code v2.1.219 發布**：將 Opus 5 設為預設 Opus 模型（1M context），新增 sandbox.network.strictAllowlist 拒絕非白名單主機，並加入 DirectoryAdded hook。([來源](https://releasebot.io/updates/anthropic/claude-code))

[5] **Claude Security 插件公測**：多代理漏洞掃描器可在 Claude Code 終端內掃描未提交變更或整個 repo，產出可審查的補丁檔案。([來源](https://www.marktechpost.com/2026/07/22/anthropic-releases-claude-security-plugin-for-claude-code-in-beta-a-multi-agent-vulnerability-scanner-that-runs-in-your-terminal/))

[6] **v2.1.219 巢狀子代理轉發**：depth-2+ 子代理在 stream-json 模式下可透過 --forward-subagent-text 顯示，方便深度工作流除錯。([來源](https://www.gradually.ai/en/changelogs/claude-code/))

## 🛠️ 新工具 & 套件

[7] **Claude Opus 5 正式發布**：代號 Honeycomb，1M context、128k 輸出，Frontier-Bench 與 GDPval-AA 登頂，定價 $5/$25 per Mtok 與 Opus 4.8 持平。([來源](https://www.anthropic.com/news/claude-opus-5))

[8] **Opus 5 多平台同步上線**：同日登陸 API、Amazon Bedrock、Google Cloud、Microsoft Foundry、claude.ai、Claude Code 與 Cowork。([來源](https://venturebeat.com/orchestration/anthropic-launches-claude-opus-5-a-cheaper-ai-model-for-coding-agents-and-enterprise-workflows))

[9] **Opus 5 成為 Claude Max／Pro 預設**：Max 方案預設切換至 Opus 5，Pro 方案亦以 Opus 5 為最強可用模型。([來源](https://finance.yahoo.com/technology/article/anthropic-debuts-opus-5-model-as-company-preps-for-ipo-later-this-year-170000070.html))

## 💬 社群熱門討論

[10] **FakeAgent 惡意廣告攻擊 29 組織**：攻擊者透過 Bing 廣告導向 claude.ai 上的惡意 Artifact，假冒 Claude Desktop 散佈 SectopRAT 木馬，下載逾 7100 次。([來源](https://www.huntress.com/blog/fakeagent-claude-desktop-malvertising-ends-in-dotnet-rat))

[11] **白宮指控 Moonshot 蒸餾 Fable 開發 K3**：OSTP 主任 Kratsios 稱 Moonshot 以工業級蒸餾竊取 Fable，財政部威脅制裁；專家質疑 Fable 7/1 才公開，時間線存疑。([來源](https://techcrunch.com/2026/07/22/treasury-threatens-sanctions-after-white-house-claims-moonshot-distilled-anthropics-fable/))

[12] **FakeAgent 使用 EtherHiding 隱藏 C2**：該攻擊的 C&C 基礎設施藏於以太坊區塊鏈交易中，操作者可透過發布新交易輪換基礎設施，規避傳統封鎖。([來源](https://www.bleepingcomputer.com/news/security/fake-claude-app-promoted-by-bing-ads-pushes-sectoprat-malware/))
