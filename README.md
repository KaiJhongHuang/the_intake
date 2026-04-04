# the_intake

**https://kaijhonghuang.github.io/the_intake/**

The Intake — A personal knowledge repository. Daily news digests, curated readings, and fragments worth keeping — collected from across the web, filtered through one perspective.

## Website

透過 GitHub Pages 提供瀏覽：啟用 GitHub Pages 後即可使用 `index.html` 作為入口頁面。

## 新增文章

新增 `.md` 檔案時，請同時在 `content.json` 的 `articles` 陣列加入一筆：

```json
{
  "date": "YYYY-MM-DD",
  "title": "文章標題（繁體中文）",
  "category": "daily-newspaper",
  "file": "Journal/01_Daily_Newspaper/YYYY-MM-DD-Title.md"
}
```

新增分類時，在 `content.json` 的 `categories` 陣列加入對應項目。
