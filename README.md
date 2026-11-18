# 遊戲遊戲遊戲（Firebase + GitHub Pages 版）

## 檔案
- index.html：遊戲本體
- firebase-config.js：把 Firebase 設定貼在這裡
- database.rules.json：Firebase Realtime Database 的安全規則
- board.png、pixel.png、hero.svg、mouse.png、rabbit.png、cubic11.woff2：圖片和字體

## 設定步驟
1. Firebase 主控台建立新專案 → 建構 → Realtime Database → 建立資料庫（位置選 asia-southeast1 新加坡）→ 以「鎖定模式」開始。
2. Realtime Database →「規則」分頁 → 把 database.rules.json 的內容整段貼上 → 發布。
3. 專案設定 → 一般 → 你的應用程式 → 新增網頁應用程式（</>）→ 複製 firebaseConfig，貼進 firebase-config.js。
4. 把所有檔案上傳到 GitHub repo 的根目錄 → Settings → Pages → Branch 選 main / root → Save。
5. 幾分鐘後打開 https://<帳號>.github.io/<repo 名稱>/ 。

## 兩支手機連線
兩個人打開同一個網址，填一樣的房間密碼（至少 4 個英文字母或數字），各自選自己的名字。
