# The Intake — 專案流程圖

## 整體架構

```mermaid
flowchart TD
    subgraph Trigger["① 觸發"]
        A1["🕐 排程 / 手動觸發"]
    end

    subgraph Claude["② Claude Code 產生內容"]
        B1["讀取 Prompt 模板<br/>/Prompts/daily-newspaper.md<br/>/Prompts/daily-newspaper-ai.md"]
        B2["遵守 CLAUDE.md 規則<br/>・台灣時間 UTC+8<br/>・50字內 + 來源URL<br/>・禁止幻覺"]
        B3["WebSearch 搜尋<br/>當日新聞"]
        B4["產出 Markdown 日報<br/>Journal/01_Daily_Newspaper/<br/>Journal/02_Daily_Newspaper_AI/"]
        B5["更新 content.json<br/>新增文章索引"]
        B1 --> B2 --> B3 --> B4 --> B5
    end

    subgraph GitHub["③ GitHub"]
        C1["git commit + push<br/>直接推到 main"]
        C2["GitHub Pages<br/>自動部署"]
    end

    subgraph Website["④ 網站呈現"]
        D1["index.html<br/>載入 content.json"]
        D2["marked.js 渲染<br/>Markdown → HTML"]
        D3["使用者瀏覽<br/>・分類篩選<br/>・日期篩選<br/>・全文搜尋"]
        D1 --> D2 --> D3
    end

    A1 --> B1
    B5 --> C1
    C1 --> C2
    C2 --> D1
```

## 檔案結構

```mermaid
flowchart LR
    subgraph Repo["the_intake/"]
        CLAUDE["CLAUDE.md<br/><i>執行規則</i>"]
        PROMPTS["Prompts/<br/><i>Prompt 模板</i>"]
        JOURNAL["Journal/<br/><i>日報文章 .md</i>"]
        CONTENT["content.json<br/><i>文章索引</i>"]
        INDEX["index.html<br/><i>網站前端</i>"]
    end

    CLAUDE -.->|規範| PROMPTS
    PROMPTS -->|產出| JOURNAL
    JOURNAL -->|登記| CONTENT
    CONTENT -->|讀取| INDEX
```

## 三個核心角色

| 角色 | 負責什麼 | 怎麼運作 |
|------|----------|----------|
| **Claude Code** | 內容產生 | 讀 Prompt 模板 + WebSearch 搜新聞 → 寫 Markdown 日報 + 更新 content.json |
| **Schedule** | 定時觸發 | 每日排程（或手動）啟動 Claude Code 執行 Prompt |
| **GitHub** | 儲存 + 部署 | Git 版控所有檔案，GitHub Pages 自動將 main branch 部署為靜態網站 |

## 一句話總結

> **排程觸發 Claude Code → 自動搜尋新聞寫日報 → push 到 GitHub → GitHub Pages 自動上線**
>
> 零後端、零資料庫，整個網站就是一個 Git repo + 靜態頁面。
