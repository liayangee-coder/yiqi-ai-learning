# 依起愛學習

依依老師的教學、班級經營與生活小工具箱。網站以 GitHub Pages 發布，首頁依 `resources.json` 顯示分類與工具。

## 網站分類

- 三年級：國語、數學、社會
- 四年級
- 五年級
- 課堂互動與評量
- 班級經營工具
- 備課與教材製作
- 教師行政工具
- 學生學習支持
- 生活小工具
- 聯絡簿
- 其他

目前已收錄三年級 25 個網頁：國語 12 個、數學 9 個、社會 4 個。其他分類已先建立，尚無網頁時會顯示「工具整理中」。

## 新增工具

直接編輯 `resources.json`，每個項目需有 `category`、`title`、`url`、`available` 和 `note`。年級類工具另填 `subject`；班級、生活、聯絡簿和其他工具可省略 `subject`。

年級工具範例：

```json
{
  "category": "四年級",
  "subject": "數學",
  "title": "工具名稱",
  "url": "https://實際網頁網址",
  "available": true,
  "note": ""
}
```

班級經營等生活應用範例：

```json
{
  "category": "班級經營工具",
  "title": "工具名稱",
  "url": "https://實際網頁網址",
  "available": true,
  "note": ""
}
```

`category` 請使用首頁顯示的分類名稱。新增項目時，注意 JSON 項目間的逗號，以及網址須為可公開開啟的網頁。

## 專案檔案

- `index.html`：首頁、分類導覽、年級學科篩選、搜尋與樣式。
- `resources.json`：工具分類、名稱、科目與網址。
- `assets/`：網站形象圖與透明背景書籤圖示。

在 GitHub 儲存庫編輯並提交至 `main` 後，GitHub Pages 會自動發布更新。
