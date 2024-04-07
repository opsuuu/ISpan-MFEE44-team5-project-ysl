# 第五組專題

> 此專案為 ISpan 前端工程師就業養成班 MFEE44 第五組 YSL 二手遊戲買賣平台。
> 為了延長每個 Switch 遊戲的市場賞玩期，致力於實現「最大化 Switch 遊戲生活」的宗旨，以此在人們尋找新遊戲和資源重複利用之間找到平衡點。
> 打造二手 switch 遊戲片的買賣平台，網站角色為第三方電商平台，
> 用戶是買方也是賣方，致力打造友善、安全、價格透明的買賣空間。

## 開發組員

- 會員中心: [Wendy Zing]((https://github.com/ZingWen)
- 賣家中心: [Chiwen Chen]((https://github.com/pollochen97)
- 優惠券、新手任務、聊天室: [Shiang-Ni]((https://github.com/Shiang-Ni)
- 購物車、結帳: [Wendy Lai]((https://github.com/opsuuu)
- 商品專區: [HsinYu]((https://github.com/angela041199)
- 文章專區: [Kkrismamm](https://github.com/Kkrismamm)

## 使用技術/工具 :

- 框架 - React
- 網頁功能 - HTML CSS JavaScript
- 版本控制 - Github
- 後端串接 - Node.js express
- 資料庫 - MySQL
- UI 設計 - Figma Illustrator Photoshop

## 執行方式

### 前端 React(版本號^18.2.0)

- `client`資料夾使用 install 即可安裝使用套件

```sh
   npm install
```

- 啟動專案，這將在開發模式下啟動:

```sh
   npm start
```

### 後端 Express(版本號^4.18.1)

- 下載 Node.js(版本號 v20.10.0) [Node.js 下載傳送門]((https://nodejs.org/en)
- Server 資料夾安裝使用套件

```sh
   npm install
```

- 終端機執行啟用後台管理網頁

```sh
   nodemon
```

### 套件版本

- "express": "^4.18.1"
- "express-session": "^1.17.3"
- "mysql2": "^2.3.3"
- "dotenv": "^16.0.1"
- "pug": "^3.0.2"
  > 資料庫為 MySQL

### 資料夾說明

#### client

- `components`: 共用元件及頁面元件放置的資料夾
- `pages`: 所有功能頁面
- `styles`: 樣式所在資料夾
- `public`: 靜態圖檔放置位置
- `hooks`: 包含了專案中自定義的 React 鉤子（Hooks），這些鉤子封裝了可重複使用的邏輯，以支持元件間的狀態管理和副作用操作

### server

- `routes`: 各路由功能串接及 api
- `configs`: 包含專案的配置檔案，用於定義和管理資料庫連接以及其他全局配置。例如，`db.mjs` 文件使用 `mysql2` 模組創建並導出 MySQL 連接池
- `views`: 包含專案中的 pug 樣板引擎文件
- `sql`: 儲存 ysl_db_DEMO.sql 文件可以下載使用以初始化資料庫

### 免責聲明

> 使用我們的網站或其提供的內容之前，請詳細閱讀以下免責聲明：

1. 本網站僅供資展國際期末專題使用，不得使用於任何商業用途，如有侵權敬請告知。
2. 本網站所提供的內容僅供參考及學術研究，我們不對其作出任何保證。
3. 網站可能包含連結到第三方網站的連結，但我們不對第三方網站內容負責。
4. 本網站所有原始內容受版權法和知識產權法保護，未經授權的使用、複製或修改都屬於侵權行為。
5. 使用網站內容所產生的任何問題或損失，我們概不負責。
6. 本網站涉及的所有第三方遊戲和品牌，包括但不限於 Nintendo Switch 及其遊戲，均屬其各自擁有者的財產。本平台不擁有任何第三方內容的版權、商標或其他擁有權，且此類內容的使用僅出於非商業的教育目的。
   >
