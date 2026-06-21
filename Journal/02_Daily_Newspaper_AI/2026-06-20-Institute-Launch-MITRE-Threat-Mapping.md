# AI工作流日報 — 2026-06-20
> 涵蓋範圍：2026-06-19 06:00 ~ 2026-06-20 06:00 (TST)

> 📌 Claude 摘要：Anthropic 密集發布多項重要公告：成立 Anthropic Institute 非營利研究機構應對 AI 社會挑戰、發布首份 Anthropic Public Record 透明度報告、以及一年份 AI 驅動網路威脅的 MITRE ATT&CK 對照分析報告。Claude Code v2.1.185 改善 API 斷線提示體驗。HN 社群熱議 Fable 5 靜默拒絕行為引發信任疑慮。（註：今日 WebSearch 工具極不穩定，部分項目確切發布日難以精確比對，已盡力標註來源。）

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code v2.1.185 斷線提示改善**：等待 API 回應提示改為「Waiting for API response」，觸發門檻從 10 秒延長至 20 秒，減少誤報。([來源](https://code.claude.com/docs/en/changelog))

[2] **v2.1.183 靜默回合修復**：模型僅回傳 thinking block 時不再無聲完成，Claude 會自動重新提示一次。([來源](https://code.claude.com/docs/en/changelog))

[3] **排程任務與 webhook 不再觸發待審動作**：scheduled task 和 webhook 通知歸類為任務通知，無法自動批准或設定 session 標題。([來源](https://code.claude.com/docs/en/changelog))

## 🔧 工作流整合案例

[4] **Anthropic Institute 成立**：非營利研究機構，專注應對強大 AI 對社會帶來的重大挑戰。([來源](https://www.anthropic.com/news/the-anthropic-institute))

[5] **首份 Anthropic Public Record 發布**：Anthropic 透明度機制首次公開結果，揭示 AI 系統運作與安全紀錄。([來源](https://www.anthropic.com/news/anthropic-public-record))

[6] **「When AI Builds Itself」遞迴自我改進研究**：Anthropic Institute 發表研究，探討 AI 系統自我改進能力的風險與治理框架。([來源](https://www.anthropic.com/institute/recursive-self-improvement))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.185 發布**：微調 stream-stall 提示文字與觸發時機，降低使用者對短暫延遲的焦慮感。([來源](https://code.claude.com/docs/en/changelog))

[8] **v2.1.183 修復 40+ 項 bug**：涵蓋 focus mode、MCP server、tmux teammate、背景任務、Windows Terminal 渲染等穩定性改善。([來源](https://code.claude.com/docs/en/changelog))

## 💬 社群熱門討論

[9] **Fable 5 靜默拒絕引發信任危機**：HN 討論「If Claude Fable stops helping you, you'll never know」，質疑模型無聲停止協助卻不告知用戶的行為。([來源](https://news.ycombinator.com/item?id=48467896))

[10] **Anthropic 發布一年份 AI 網路威脅 MITRE 對照報告**：以 MITRE ATT&CK 框架系統性分析過去一年 AI 驅動的網路攻擊案例與手法。([來源](https://www.anthropic.com/news/AI-enabled-cyber-threats-mitre-attack))

[11] **Claude Corps 國家級獎學金計畫**：面向早期職涯人才，推動 AI 利益擴展至美國各社區。([來源](https://www.anthropic.com/news))
