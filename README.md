# stock

n8n LINE 台股機器人產生的個股分析報告，由 workflow `每日新聞發送-Rich Menu` 自動 commit 到這裡。

- 檔名格式：`{股票}-{YYYY-MM-DD}.html`（股票即使用者在 LINE 輸入的名稱）
- 瀏覽網址：`https://evachen-del.github.io/stock/{檔名}`
- 同一支股票同一天只會產生一份（n8n 端有 Google Sheet 快取）

報告由 AI 產生，僅供參考，非投資建議。
