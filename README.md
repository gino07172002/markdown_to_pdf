# Markdown to PDF 轉換器

一個簡單的前端工具，可以將 Markdown 轉換成 PDF 檔案。

## 專案背景

這個工具是透過與 Claude AI 多次對話調整而來的。經過了不少次的修正和優化，才慢慢調整到現在這個樣子。主要是因為對前端不太熟，所以需要 AI 幫忙處理技術細節。

## 原始 AI Prompt

```
給我一個純html+javascript的前端頁面,
1.我可以輸入markdown的文件他會幫我轉換成github的markdown的排版並可以存成pdf檔,
2.輸出的pdf檔要可以框選並且複製內文
3.要可以調整文字大小並且預覽pdf輸出時分頁的效果
4.並且要能支援繁體中文
5.不要使用jsPDF等套件因為沒辦法達成我的需求
```

## 功能特色

- GitHub 風格的 Markdown 渲染
- 即時預覽和分頁顯示
- 字體大小調整
- 支援繁體中文
- 可選取複製的 PDF 輸出
- 不依賴外部 PDF 套件

## 使用方法

1. 開啟 HTML 檔案
2. 在左側輸入 Markdown 內容
3. 右側會即時顯示預覽效果
4. 調整字體大小和縮放比例
5. 點擊「下載 PDF」輸出檔案

## 技術說明

- 使用 `marked.js` 解析 Markdown
- 透過瀏覽器原生打印 API 產生 PDF
- 純前端實作，無需後端服務

## 注意事項

- 需要現代瀏覽器支援
- 分頁邏輯可能還有改進空間
- PDF 輸出效果會依瀏覽器而異

## 授權

MIT License

---

# Markdown to PDF converter ( single front-end only program ) 

## About

A simple frontend tool for converting Markdown to PDF with GitHub-style formatting. This project was developed through multiple iterations with Claude AI assistance, as I'm not very familiar with frontend development.

## Features

- GitHub-flavored Markdown rendering
- Real-time preview with pagination
- Adjustable font size
- Traditional Chinese support
- Selectable text in PDF output
- No external PDF libraries required

## Usage

1. Open the HTML file in your browser
2. Type Markdown content in the left panel
3. Preview appears instantly on the right
4. Adjust font size and zoom as needed
5. Click "下載 PDF" to generate PDF

## Technical Notes

- Uses `marked.js` for Markdown parsing
- Leverages browser's native print API for PDF generation
- Pure frontend implementation

## License

MIT License
