# AI工作流日報 — 2026-06-30
> 涵蓋範圍：2026-06-29 06:00 ~ 2026-06-30 06:00 (TST)

> 📌 Claude 摘要：Anthropic 今日同步發布 Claude Sonnet 5 與 Claude Science 科研工作台，前者以接近 Opus 4.8 的效能、不到一半的價格重新定義性價比甜蜜點；後者整合 60+ 科學資料庫與 NVIDIA BioNeMo，正式進軍藥物探索。企業端則推出 Apps Gateway 統一管控 Claude Code 部署。整體方向：讓頂級推理能力以更低成本覆蓋更多場景。

## 🧠 Prompt 技巧 & 使用心得

[1] **Sonnet 5 代理性能逼近旗艦**：SWE-bench Pro 得分 63.2%，距 Opus 4.8 的 69.2% 僅差 6 點，純工具驅動任務差距更小。([來源](https://www.marktechpost.com/2026/06/30/anthropic-claude-sonnet-5-vs-sonnet-4-6-vs-opus-4-8-agentic-coding-benchmarks-api-pricing-and-cost-performance-tradeoffs-compared/))

[2] **知識工作反超旗艦**：Sonnet 5 在 GDPval-AA v2 得 1,618 分，微幅超越 Opus 4.8 的 1,615 分。([來源](https://codersera.com/blog/claude-sonnet-5-launch-guide-2026/))

[3] **Simon Willison 首測 Sonnet 5**：認為效能接近 Opus 4.8 但價格大幅降低，適合大量代理任務場景。([來源](https://simonwillison.net/2026/Jun/30/claude-sonnet-5/))

## 🔧 工作流整合案例

[4] **Claude Apps Gateway 上線**：自建控制面板支援 Bedrock/Google Cloud，提供 SSO、RBAC、每人花費追蹤與限額。([來源](https://claude.com/blog/introducing-the-claude-apps-gateway))

[5] **Opus 4.8 Fast Mode 登陸 GitHub Copilot**：6/29 預覽上線，輸出速度顯著加快且維持同等智能，適用互動式寫碼。([來源](https://github.blog/changelog/2026-06-29-claude-opus-4-8-fast-mode-is-now-in-preview-for-github-copilot/))

[6] **Sonnet 5 同日登陸 GitHub Copilot GA**：Free/Pro 方案預設模型，ZDR 合規，CLI 任務表現尤佳。([來源](https://github.blog/changelog/2026-06-30-claude-sonnet-5-is-generally-available-for-github-copilot/))

## 🛠️ 新工具 & 套件

[7] **Claude Science 科研工作台公測**：整合 60+ 科學資料庫，支援蛋白質結構預測、文獻搜索、實驗管理，Pro 以上方案可用。([來源](https://www.anthropic.com/news/claude-science-ai-workbench))

[8] **NVIDIA BioNeMo Agent Toolkit 整合 Claude Science**：提供 Evo 2、Boltz-2、OpenFold3 等生科模型，50+ 企業已採用。([來源](https://blogs.nvidia.com/blog/claude-science-bionemo-agent-toolkit/))

[9] **Anthropic 自研被忽略疾病藥物計畫**：利用 Claude Science 進行臨床前藥物探索，鎖定傳統藥廠不願投入的疾病。([來源](https://www.cnbc.com/2026/06/30/anthropic-launches-ai-drug-discovery-program-claude-science.html))

[10] **Sonnet 5 正式發布**：1M 上下文、入門價 $2/$10 per M tokens（至 8/31），之後 $3/$15，是 Free/Pro 預設模型。([來源](https://www.anthropic.com/news/claude-sonnet-5))

## 💬 社群熱門討論

[11] **HN 討論 Claude Science**：社群認為科學推理持續進步，但受限開放取用文獻不足，專業領域仍有差距。([來源](https://news.ycombinator.com/item?id=48735770))

[12] **TechCrunch 評 Sonnet 5 為「更便宜的代理方案」**：強調 Opus 級能力搭配 Sonnet 級價格，對企業大規模部署有吸引力。([來源](https://techcrunch.com/2026/06/30/anthropic-launches-claude-sonnet-5-as-a-cheaper-way-to-run-agents/))

[13] **Basecamp Research EDEN 模型上架 Claude Science**：可透過對話介面數分鐘內產出抗生素與疫苗候選清單。([來源](https://www.hpcwire.com/aiwire/2026/06/30/basecamp-research-brings-edens-antibiotic-and-vaccine-design-models-to-claude-science/))
