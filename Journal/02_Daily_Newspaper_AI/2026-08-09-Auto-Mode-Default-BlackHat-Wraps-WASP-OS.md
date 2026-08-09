# AI工作流日報 — 2026-08-09
> 涵蓋範圍：2026-08-08 06:00 ~ 2026-08-09 06:00 (TST)

> 📌 Claude 摘要：Anthropic 宣布 8/14 起 auto mode 成為 Pro / Max / Team 預設，測試顯示分類器攔截 89% 危險指令而人類僅 13.6%；Trajectory Labs 獨立評測 720 次攻擊全數失敗。Willison 同日質疑 pip install 盲區，恰逢 litellm 供應鏈攻擊同週曝光。Black Hat USA 2026 閉幕，29% 場次聚焦 AI 安全——NVIDIA WASP-OS 以 30B 開源模型達 56% agent 攻擊成功率、成本僅 frontier 模型 1/70，agent 攻擊正式成為獨立攻防學科。

## 🧠 Prompt 技巧 & 使用心得
[1] **Auto mode 8/14 成為預設**：Claude Code Pro/Max/Team 新 session 將預設 auto mode，分類器攔截 89% 危險指令，人類僅 13.6%。([來源](https://claude.com/blog/auto-mode-default-in-claude-code))
[2] **Trajectory Labs 720 次攻擊零成功**：72 項間接 prompt injection 場景各跑 10 次，Fable 5/Opus 5/Sonnet 5 全數攔截。([來源](https://the-decoder.com/anthropic-sets-claude-code-to-auto-mode-by-default-to-protect-developers-from-bad-approvals/))
[3] **Willison 質疑 auto mode pip 盲區**：pip install 在預設允許清單內，同週 litellm 供應鏈攻擊竊取 SSH 金鑰，分類器無法捕捉。([來源](https://simonwillison.net/2026/Aug/8/auto-mode/))
[4] **人類審批疲勞數據**：1,053 名測試者面對危險指令僅攔 13.6%，session 超 50 次提示後降至約 5%。([來源](https://thenewstack.io/claude-code-auto-mode/))

## 🔧 工作流整合案例
[5] **v2.1.226 穩定性修復已上線**：8/8 發布，聚焦 bug 修復與可靠性提升，無新功能。([來源](https://www.havoptic.com/tools/claude-code))
[6] **v2.1.225 gateway 消費上限警示**：用量警示現顯示額度上限、重置時間與營運商訊息，強化企業管控。([來源](https://code.claude.com/docs/en/changelog))

## 🛠️ 新工具 & 套件
[7] **NVIDIA WASP-OS 30B 攻擊模型**：Black Hat 發表，微調開源模型達 56% agent 攻擊成功率，成本僅 frontier 1/70-1/125。([來源](https://forkast.news/black-hat-usa-2026-signals-agent-exploitation-has-become-its-own-infrastructure-discipline/))
[8] **PleaseFix 零點擊瀏覽器劫持持續延燒**：Zenity Labs 展示攻擊五大 agentic 瀏覽器，單封惡意郵件可竊 Gmail、Drive 與 Slack 帳號。([來源](https://www.securityweek.com/zero-click-ai-browser-hacking-claude-and-chatgpt-atlas-hijacked-via-emails-x-posts/))

## 💬 社群熱門討論
[9] **HN 激辯 auto mode 11% 漏放率**：社群質疑分類器仍有 11% 漏網，Anthropic 回應三次阻擋後自動降回手動模式。([來源](https://news.ycombinator.com/item?id=49214994))
[10] **Black Hat 閉幕：29% 場次聚焦 AI**：121 場 briefing 中 35 場直接涵蓋 AI 安全，agent 攻擊成為獨立攻防學科。([來源](https://www.techrepublic.com/article/news-black-hat-ai4-2026-ai-security-takeaways/))
[11] **SiliconANGLE 總結 Black Hat AI 投資熱**：企業 AI 安全支出激增，但治理成熟度僅 35/100，落差巨大。([來源](https://siliconangle.com/2026/08/09/finding-big-money-ai-smaller-world-security-black-hat-usa-2026/))
[12] **GPT-5.6 Sol auto-review 仍有 5.83% 漏放**：Trajectory Labs 同場景下 GPT-5.6 Sol Full Access 模式漏放率達 19.03%。([來源](https://en.cryptonomist.ch/2026/08/09/claude-code-auto-mode/))
