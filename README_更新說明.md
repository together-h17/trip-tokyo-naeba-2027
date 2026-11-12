# 東京＋苗場｜冬日旅行手帖 2027 — 網站更新 v2

## GitHub Pages 更新方式
將本資料夾中的 **全部 7 個網站檔案** 上傳到 GitHub 儲存庫的根目錄（與既有 README.md 同層），其中 `index.html` 需覆蓋原檔。請**不要**上傳外層 `tokyo_naeba_site_v2` 資料夾；若放進子資料夾，GitHub Pages 的根網址不會找到新版網站。

- `index.html`：完整八日行程及新功能
- `manifest.webmanifest`：Android 等瀏覽器的網頁 App 設定
- `icon.svg`：網站圖示
- `icon-192.png`、`icon-512.png`、`icon-maskable-512.png`：Android 圖示
- `apple-touch-icon.png`：iPhone 主畫面圖示

> 以上實際為 7 個網站檔案。圖片介紹使用 Wikimedia Commons 外部連結（不含在 ZIP），若無網路或照片無法載入，網站會顯示原創 SVG 插圖。沒有額外使用 Service Worker，因此這不是完整的離線 PWA。

## 新功能
- 日本時間 `Asia/Tokyo` 判斷旅程是否已開始。旅程外為預覽，旅程中顯示當天正在進行與下一站的規劃事件。
- Google Maps 路線：使用該事件既有的地點欄位作為終點；不是即時列車或目前位置承諾。
- 依日期／A-B-C-D 方案切換交通及行李提醒。
- 8 張景點圖鑑；7 張 Wikimedia Commons 實景照片連結＋1 張水獺原創插圖。每張都有圖片來源與授權說明。
- 保留原版 localStorage 儲存鍵、待辦／行李清單與方案的資料結構。跨手機依舊不同步。

## 更新到 GitHub
1. 儲存庫頁面選擇 Add file → Upload files，把這 7 個檔案拖進根目錄（若已有 index.html，確認將覆蓋它）。
2. 點 Commit changes。
3. 在 Actions 或 Settings → Pages 等候更新完成；用原網址測試。
4. iPhone 若主畫面圖示未更新，刪除舊的主畫面捷徑再由 Safari「加入主畫面」。

圖片僅作景點介紹；非即時現場或營業狀況。水獺咖啡廳互動及動物福利請自行衡量。出發前再核對所有時刻、寄物容量、接送與預約。
