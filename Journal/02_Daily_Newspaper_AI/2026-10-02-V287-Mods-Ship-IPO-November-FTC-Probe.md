# AI工作流日報 — 2026-10-02
> 涵蓋範圍：2026-10-01 06:00 ~ 2026-10-02 06:00 (TST)

> 📌 Claude 摘要：v2.1.287帶來Mods插件架構是Claude Code生態的重要里程碑；IPO時程首度具體化瞄準感恩節前；FTC正式調查代理安全問題標誌監管壓力升級。整體觀察為「產品成熟化與監管追趕同步加速」。

## 🧠 Prompt 技巧 & 使用心得

[1] **Willison引Green論代理蠕蟲風險**：沙盒代理透過共享套件快取互傳指令，具備蠕蟲所需全部要素。([來源](https://simonwillison.net/2026/Oct/1/matthew-green/))

[2] **Claude Code Mods架構上線**：v2.1.287推出Mods，插件可攔截工具呼叫、修改提示與介面渲染，深度擴展能力。([來源](https://code.claude.com/docs/en/plugins/mods/overview))

[3] **「You Should Know」內建Mod發布**：第一方伴隨代理，可在session中即時標記使用者或主代理可能遺漏的事項。([來源](https://kingy.ai/news/claude-code-2-1-287-mods-permissions-rollout/))

## 🔧 工作流整合案例

[4] **Barclays全行擴大部署Claude**：目標年底50%開發者使用Claude Code，Knowledge Assistant已16K用戶處理逾100萬次查詢。([來源](https://www.anthropic.com/news/barclays-scales-claude))

[5] **Barclays市場部門日處理12萬封郵件**：以Claude模型自動分類處理客戶詢問信件，大幅精簡作業流程。([來源](https://www.bloomberg.com/news/articles/2026-10-01/barclays-expands-use-of-anthropic-s-claude-in-efficiency-push))

[6] **NVIDIA OpenShell開源代理安全執行環境**：Apache 2.0授權，支援Claude Code等代理，一鍵安裝沙盒、憑證管理與網路策略。([來源](https://developer.nvidia.com/blog/add-runtime-controls-to-ai-agents-with-nvidia-openshell/))

## 🛠️ 新工具 & 套件

[7] **v2.1.287正式發布**：新增VSCode書籤、背景執行、代理地圖shell輸出、/config左右循環與MCP啟動穩定性改善。([來源](https://github.com/anthropics/claude-code/releases))

[8] **NVIDIA Sentry硬體看門狗**：搭配BlueField-4 DPU，毫秒級隔離失控代理，超過100家合作夥伴參與平台。([來源](https://www.securityweek.com/nvidia-unveils-ai-agent-safety-platform-with-hardware-based-watchdog/))

[9] **PageIndex登GitHub趨勢第一**：Vectorless RAG專案單日+1095星達38K，以結構化圖索引取代傳統向量資料庫。([來源](https://github.com/VectifyAI/PageIndex))

[10] **openrig多代理協作工具**：同時運行Claude Code與Codex作為單一系統，登GitHub趨勢榜。([來源](https://github.com/mvschwarz/openrig))

## 💬 社群熱門討論

[11] **Bloomberg報Anthropic IPO瞄準感恩節前**：最快11/9啟動路演，估值$1.8T-$2T，為史上最大IPO。([來源](https://www.bloomberg.com/news/articles/2026-10-01/anthropic-said-to-target-mega-ipo-before-thanksgiving-holiday))

[12] **川普稱「喜歡」Amodei釋緩和訊號**：白宮私人晚宴後態度轉變，稱其「非常聰明」，IPO前政治風險降低。([來源](https://www.bloomberg.com/news/articles/2026-10-01/trump-says-he-liked-anthropic-s-amodei-in-sign-of-detente))

[13] **FTC正式調查Anthropic與OpenAI代理安全**：關注逃逸代理是否構成不公平行為，將索取紀錄與高管證詞。([來源](https://abcnews.com/Politics/ftc-opens-probe-safety-ai-including-anthropic-open/story?id=136896227))

[14] **Anthropic紅隊揭GLM-5.3網攻能力近Mythos**：智譜開放權重模型安全護欄以$4400即可移除，繞過率64-100%。([來源](https://the-decoder.com/anthropic-says-zhipus-open-weight-glm-5-3-nearly-matches-claude-mythos-preview-at-building-exploits/))

[15] **Google Gemini 4 Argon發布**：DeepSWE 77.9%超越GPT-6 Astra，但Bloomberg報員工質疑實際表現不如跑分。([來源](https://ai-engineering-trend.medium.com/google-unveils-gemini-4-argon-benchmarks-match-gpt-6-astra-with-the-industrys-lowest-8b70aef55fd6))
