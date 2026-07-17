# AI工作流日報 — 2026-07-18
> 涵蓋範圍：2026-07-17 06:00 ~ 2026-07-18 06:00 (TST)

> 📌 Claude 摘要：三線交錯——EU DMA 裁定迫使 Google 開放 Android 11 項系統級 AI 入口給 Claude 與 ChatGPT 等競爭者；Kimi K3 以 2.8T 參數開源模型登上 Frontend Code Arena 冠軍超越 Fable 5；Claude Corps 首期千人 fellowship 申請截止。同日 Apple 擴大訴訟向約 40 名轉投 OpenAI 的前員工寄發證據保全函，Gemini 3.5 Pro 則連三度跳票，Google 考慮先推 3.6 Flash 權宜版。

## 🧠 Prompt 技巧 & 使用心得
[1] **Opus 4.7 fast mode 7/24 停用，須遷移 Opus 4.8**：遷移後成本從 $30/$150 降至 $10/$50 per Mtok，未遷移的 fast 請求將直接報錯。([來源](https://platform.claude.com/docs/en/build-with-claude/fast-mode))

[2] **Kimi K3 Frontend Code Arena 盲測奪冠超越 Fable 5**：六個前端領域排名第一，從 K2.6 的第 18 名躍升至冠軍；但整體基準仍排第三，落後 Fable 5 Max 與 GPT-5.6 Sol Max。([來源](https://www.tomshardware.com/tech-industry/artificial-intelligence/moonshot-releases-2-8-trillion-parameter-kimi-k3))

## 🔧 工作流整合案例
[3] **EU DMA 裁定 Google 須向 Claude 等開放 Android 11 項系統級功能**：語音喚醒、螢幕讀取、背景操控 app 等權限將與 Gemini 平等，2027 年 7 月起生效。([來源](https://digital-markets-act.ec.europa.eu/commission-provides-guidance-google-ai-interoperability-android-and-sharing-google-search-data-under-2026-07-16_en))

[4] **Claude Corps 首期申請截止：1,000 名 fellow、年薪 $85K**：Anthropic 投入 $1.5 億，10 月起派駐全美非營利組織推動 AI 落地，每人另獲 $2,500 API credits。([來源](https://www.anthropic.com/news/claude-corps))

[5] **Willison mermaid-ascii 工具上線**：以 Go library 編譯 WASM 在瀏覽器將 Mermaid 圖表轉 ASCII/Unicode box-drawing，支援彩色輸出。([來源](https://simonwillison.net/2026/Jul/16/mermaid-ascii/))

## 🛠️ 新工具 & 套件
[6] **Kimi K3 API 上線：2.8T 參數、$3/$15 定價**：OpenAI 相容 API、100 萬 token 上下文、原生視覺，開放權重承諾 7/27 以 Modified MIT 釋出。([來源](https://platform.kimi.ai/docs/pricing/chat-k3))

[7] **Claude API key 新增到期時間設定**：建立 API key 或 Admin API key 時可設定到期日，到期前自動通知，強化安全管理。([來源](https://releasebot.io/updates/anthropic/claude-developer-platform))

## 💬 社群熱門討論
[8] **Apple 向約 40 名前員工寄發證據保全函擴大反擊 OpenAI**：稱逾 400 名前 Apple 員工現任職 OpenAI，懷疑竊密不限原告名單；HN 當日頭條。([來源](https://www.macrumors.com/2026/07/17/apple-sends-legal-letters-openai/))

[9] **Gemini 3.5 Pro 連三度跳票，Google 考慮先推 3.6 Flash**：重建後模型仍存幻覺問題且落後 GPT-5.6，已註冊 3.6 Flash 與 3.5 Flash Light 型號名稱。([來源](https://www.techtimes.com/articles/320736/20260716/rebuilt-gemini-35-pro-misses-third-deadline-google-eyes-stopgap-release.htm))

[10] **Fable 5 免費期限 7/19 逼近，第三度延期反映競爭壓力**：7/20 起改用預付 credits（$10/$50 per Mtok），時機與 GPT-5.6 Sol 全面上線及 Kimi K3 發布重疊。([來源](https://www.bleepingcomputer.com/news/artificial-intelligence/claude-fable-5-stays-free-for-paid-users-until-july-19-as-anthropic-buys-more-time/))
