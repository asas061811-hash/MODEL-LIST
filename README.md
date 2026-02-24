✈️ 模型飛機口袋統計器 (Model Airplane Tracker)

這是一個專為模型飛機收藏家打造的輕量級、響應式網頁應用程式 (Web App)。
可以幫助您在手機或電腦上輕鬆追蹤收藏庫存以及製作進度。

✨ 核心功能

📊 庫存與製作雙向管理：輕鬆點擊增減庫存，點擊「🔨」一鍵將庫存轉移至「製作中」。

🎨 智能廠牌標籤：系統會自動根據「廠牌」名稱賦予不同的專屬顏色，讓清單一目了然。

🔍 即時搜尋過濾：內建機型搜尋框，輸入關鍵字即時篩選您的龐大機隊。

💾 離線優先 (Local Storage)：資料預設儲存於瀏覽器本地，開啟網頁即可無延遲查看。

☁️ Google Sheets 雲端同步：支援與 Google Apps Script (GAS) 串接，將資料備份並同步至 Google 表格。

📥 CSV 匯出功能：一鍵將完整收藏清單下載為 Excel 可讀取的 CSV 檔案。

🚀 如何部署至 GitHub Pages

這是一個純靜態網頁，您可以透過 GitHub Pages 免費且快速地部署：

在 GitHub 上建立一個新的儲存庫 (Repository)，例如命名為 model-plane-tracker。

將本專案的 index.html 與 README.md 上傳至該儲存庫。

進入該儲存庫的 Settings (設定)。

在左側選單找到 Pages。

在 Build and deployment 下的 Source 選擇 Deploy from a branch。

Branch 選擇 main (或 master)，然後點擊 Save。

等待約 1-2 分鐘後，GitHub 會提供專屬網址（例如 https://您的帳號.github.io/model-plane-tracker），點擊即可使用！

📱 手機 App 化 (PWA 體驗)

在手機瀏覽器（Safari 或 Chrome）開啟部署後的 GitHub Pages 網址。

點擊瀏覽器的「分享」或「選單」按鈕。

選擇 「加入主畫面」。

現在您可以像原生 App 一樣從手機桌面開啟它了！

⚙️ 雲端同步設定 (可選)

若要將資料同步至 Google 表格：

建立一個 Google 表格，第一列設定為：廠牌、國籍、機型、型號、數量、製作中。

點擊「擴充功能」>「Apps Script」，貼上接收 POST 請求的程式碼。

部署為網頁應用程式（權限設為所有人），複製 Web App URL。

在本 App 的「⚙️ 雲端同步設定」中貼上該網址並儲存即可。

Developed with Gemini AI