ChiliScan V7 - VS Code 專案

資料夾結構：
- index.html：網頁內容
- css/style.css：頁面樣式
- js/app.js：光譜資料分析與圖表程式

使用方式：
1. 解壓縮後，在 VS Code 選擇「檔案 > 開啟資料夾」，開啟 ChiliScan_V7_VSCode。
2. 編輯 index.html、css/style.css 或 js/app.js。
3. 在 VS Code 按 F5，選擇「啟動 ChiliScan 預覽」，使用固定預覽位址：http://127.0.0.1:5500/
4. 若未自動啟動伺服器，先執行「終端機 > 執行工作 > 預覽 ChiliScan」。
5. 不要直接用瀏覽器開啟舊的 file:///index.html；請使用上面的 HTTP 預覽位址。
6. 匯入 Excel 時需要網路連線以載入 SheetJS；CSV 可在離線時直接匯入。

公開上架（GitHub Pages）：
1. 在 GitHub 建立公開儲存庫，並將本資料夾中的網站檔案推送至 main 分支。
2. 在儲存庫 Settings > Pages，將 Build and deployment 的 Source 設為 GitHub Actions。
3. 推送後，GitHub Actions 會自動部署；完成後網址會顯示在 Actions 的部署紀錄及 Settings > Pages。
4. 此網站是純前端靜態頁面；Excel 分析仍在訪客的瀏覽器中執行，不會上傳使用者資料。
