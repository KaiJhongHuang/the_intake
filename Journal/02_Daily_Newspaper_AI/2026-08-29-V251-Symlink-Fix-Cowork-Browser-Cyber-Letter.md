# AI工作流日報 — 2026-08-29
> 涵蓋範圍：2026-08-28 06:00 ~ 2026-08-29 06:00 (TST)

> 📌 Claude 摘要：Claude Code v2.1.251 修補第三次 symlink 路徑逃逸漏洞並新增模型切換鉤子。Cowork 桌面版內建瀏覽器開放 Pro/Max/Team，AI 代理首次直接操作網頁。OpenAI 聯合 Anthropic 等 130 家企業發表 AI 網攻聯合警告。HN 熱議「Claude 承重詞彙」語料分析。（以上為 Claude 綜合觀察，非事實報導）

## 🧠 Prompt 技巧 & 使用心得
[1] **PreModelSwitch / PostModelSwitch 鉤子**：v2.1.251 新增模型切換前後鉤子事件，可攔截、確認或標註模型切換，企業可強制鎖定特定模型。([來源](https://code.claude.com/docs/en/changelog))
[2] **SessionStart resume 增強**：v2.1.251 的 SessionStart 鉤子新增 session 閒置時長與預估 re-cache 成本，方便開發者決定是否恢復舊 session。([來源](https://www.gradually.ai/en/changelogs/claude-code/))
[3] **「承重詞彙」語料分析登 HN 第一**：開發者分析 GitHub PR 歸類出 Claude 八大詞彙叢集，「load-bearing」佔人類歸因 PR 的 45%，引爆社群過濾鉤子分享潮。([來源](https://news.ycombinator.com/item?id=49461817))

## 🔧 工作流整合案例
[4] **Cowork 內建瀏覽器上線**：桌面版 Cowork 新增專屬瀏覽器側面板，AI 可直接開啟網頁、點擊、填表、下載報告，不共用使用者書籤與密碼。([來源](https://yourstory.com/ai-story/anthropic-claude-cowork-built-in-browser))
[5] **Cowork 瀏覽器可選轉移登入**：使用者可從 Chrome/Edge/Firefox 逐站授權登入資訊給 Claude，macOS/Windows/Linux 皆支援。([來源](https://thenextweb.com/news/anthropic-claude-cowork-built-in-browser-dma-choice-screen))
[6] **Remote Control 即時串流子代理**：v2.1.251 讓前景子代理的工具呼叫與結果即時串流至 Remote Control 用戶端，背景子代理仍僅顯示狀態。([來源](https://code.claude.com/docs/en/changelog))

## 🛠️ 新工具 & 套件
[7] **Claude Code v2.1.251**：8/28 釋出，新增 /usage 花費限額列、/cost prompt-cache 命中率明細、attach/logs/stop/respawn/rm CLI 指令，並修復 symlink 安全漏洞。([來源](https://code.claude.com/docs/en/changelog))
[8] **CVE-2026-39861 symlink 逃逸修補**：第三次 symlink 路徑驗證漏洞，Read/Write/Edit 在權限檢查後仍跟隨被置換的 symlink，可讀寫工作目錄外檔案，已修復。([來源](https://github.com/advisories/ghsa-4q92-rfm6-2cqx))
[9] **NVIDIA Q2 營收 $962 億年增 106%**：資料中心部門約 $890 億年增 117%，Jensen Huang 預測 FY28 資料中心營收再增 70%，AI 算力需求遠超供給。([來源](https://intellectia.ai/blog/nvidia-q2-earnings-august-29-2026))

## 💬 社群熱門討論
[10] **130 家企業 AI 網攻聯合警告**：OpenAI、Anthropic、Google、Microsoft、AWS 等聯署公開信，警告 AI 驅動網攻即將大規模爆發，呼籲政府與企業展開「防禦激增」行動。([來源](https://qz.com/openai-anthropic-google-ai-cyberattack-open-letter-082726))
[11] **TRM Labs 犯罪 AI 指數倍增**：AI 犯罪採用指數從 2024 年 28 分升至 2026 年 54 分，2026 上半年加密駭攻 201 件對比去年 83 件。([來源](https://tech-insider.org/openai-116-firms-ai-cyberattack-defense-letter-2026/))
[12] **Cowork 瀏覽器 prompt injection 風險討論**：社群關注 AI 直接操作網頁帶來的 prompt injection 新攻擊面，網頁隱藏指令可能誘導 AI 執行非預期操作。([來源](https://www.ithinkdiff.com/claude-adds-built-in-browser-to-cowork-enabling-autonomous-task-completion/))
