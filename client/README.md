# 開始使用 Create React App

這個專案項目是用[Create React App](<[text](https://github.com/facebook/create-react-app)>)創建的.

## 可使用的命令 Scripts

在專案目錄中，你可以運行以下命令：
`**npm start**`
在開發模式下執行應用。
打開 http://localhost:3000 在瀏覽器中查看。

當你進行更改時，頁面將會重新加載。
你還可能在控制台看到任何 lint 錯誤。

`**npm run build**`  
為生產環境將應用構建到 build 文件夾中。
它正確地將 React 打包在生產模式下，並優化構建以獲得最佳性能。

build 會被壓縮，且文件名包含 hashes。
你的應用準備好部署了！

更多信息請查看 [deployment]([text](https://create-react-app.dev/docs/deployment/)) 部分。

`**npm run dev**`  
啟動開發模式下的服務器。當你進行代碼更改時，此服務器將提供實時重載功能，無需手動刷新頁面就能看到更新的結果。

- 實時重載：開發時的任何更改都會自動刷新網頁，讓開發過程更加高效。
- 調試支持：此模式提供額外的調試信息，幫助你更快地定位和解決問題。
- 訪問地址：開啟 http://localhost:3000 在瀏覽器中查看效果。如果你需要更改默認的端口，可以在啟動命令中指定。  
  當你使用 npm run dev 命令時，可能還會看到控制台中的其他有用信息，比如編譯錯誤、lint 錯誤或警告。
