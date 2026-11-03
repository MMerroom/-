# 包裝配色實驗室

高中基本設計教學工具：原包裝觀察、色彩聯想、兩款新版本配色與設計筆記。

## 發布 GitHub Pages

1. 建立 Public 儲存庫，例如 packaging-color-lab。
2. 解壓縮本發布包，將 index.html、save-note.html、.nojekyll 與 README.md 上傳至儲存庫根目錄。不要只上傳 ZIP，也不要多包一層資料夾。
3. 儲存庫 Settings → Pages → Build and deployment → Source 選 Deploy from a branch。
4. Branch 選 main，資料夾選 / (root)，按 Save。
5. 等待發布完成，使用 Pages 顯示的 Visit site 網址。

## 功能與資料

- 不需要 API key、後端伺服器或安裝依賴。
- 照片只在訪客自己的瀏覽器內取色，填寫內容暫存於該瀏覽器。
- 第五步自動產生 PNG 圖片，手機可長按儲存，另有純圖片頁。
- 換裝置或換網址前，先匯出進度 JSON；進入新網址後匯入，原網址的暫存不會自動跟隨。
- 部分 App 的內建預覽會限制儲存圖片，請在 Safari 或 Chrome 開啟網站實測。

## 更新

更新時替換對應 HTML 檔案並提交，等待 Pages 再次發布。請保留 save-note.html 的相對路徑。
