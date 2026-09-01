# AI工作流日報 — 2026-08-31
> 涵蓋範圍：2026-08-30 06:00 ~ 2026-08-31 06:00 (TST)

> 📌 Claude 摘要：今日焦點是資安事件——Infostealer 惡意軟體大規模劫持 Claude 登入 session，Anthropic 緊急登出受害帳號並退款。同時 Sonnet 5 促銷價正式鎖定為永久價，原訂 9/1 漲價取消；Claude Code 週額度永久+25%但實質-17%的爭議持續發酵。Willison 分析 ChatGPT Work 並介紹騰訊 Hy4 770B 開放權重模型。

## 🧠 Prompt 技巧 & 使用心得
[1] **Willison 解析 ChatGPT Work**：稱其「極度混亂但極度強大」，深入分析 OpenAI 企業產品定位與代理整合架構。([來源](https://simonwillison.net/2026/Aug/30/understanding-chatgpt-work/))
[2] **「困惑環境攻擊」概念浮現**：Lobste.rs 討論指出 AI 代理遭環境惡意指令誤導非傳統 prompt injection，Willison 更新貼文認同此分類。([來源](https://simonwillison.net/2026/Aug/30/))

## 🔧 工作流整合案例
[3] **Claude Code 額度永久+25%實質-17%**：9/14 起 50%促銷結束改永久+25%，現有用戶實際從 150→125，社群炸鍋批 Anthropic 話術。([來源](https://xenospectrum.com/en/claude-code-weekly-limit-change/))
[4] **Sonnet 5 促銷價$2/$10 永久鎖定**：原訂 8/31 到期漲至$3/$15 的計畫已於 8/10 取消，API 用戶成本不變，但新 tokenizer 可能增加 35% token 數。([來源](https://explainx.ai/blog/anthropic-sonnet-5-permanent-pricing-august-2026))
[5] **Infostealer 惡意軟體劫持 Claude session**：Vidar、LummaC2、RedLine 等竊取 session cookie 繞過 2FA，Anthropic 登出受害帳號、刪除付款方式並退款。([來源](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-warns-infostealer-malware-is-hijacking-claude-sessions-to-drain-usage/))

## 🛠️ 新工具 & 套件
[6] **騰訊 Hy4 Preview 770B MoE 開放權重**：49B 活躍參數、1M context、Apache 2.0 授權，內部盲測勝 GLM-5.3 與 K3，首創遞迴自改進訓練迴圈。([來源](https://simonwillison.net/2026/Aug/29/hy4/))
[7] **DeepSeek Harness 登 GitHub 趨勢**：採「萬物皆插件」架構，讓開發者以可熱插拔元件組裝 AI 工作流。([來源](https://dev.to/muildev/github-trending-digest-2026-08-31-lj8))

## 💬 社群熱門討論
[8] **Sony/Warner 控告 Anthropic 大規模版權侵權**：指控以 torrent、爬蟲下載數萬首歌曲詞曲訓練 Claude，索賠每作品最高$15萬，Anthropic 稱將積極抗辯。([來源](https://techcrunch.com/2026/08/29/sony-music-warner-sue-anthropic-alleging-a-brazen-campaign-of-intellectual-property-theft/))
[9] **HN 討論 Hy4 自訓練迴圈引發倫理辯論**：模型協助設計自身訓練流程是否構成遞迴自改進風險，評論兩極。([來源](https://news.ycombinator.com/item?id=49492632))
[10] **Anthropic infostealer 事件登多家資安媒體頭條**：SecurityWeek、BleepingComputer、Help Net Security 等同步報導，強調 session cookie 竊取已成 AI 平台新威脅面。([來源](https://www.securityweek.com/anthropic-warns-claude-users-of-infostealer-malware-infections/))
