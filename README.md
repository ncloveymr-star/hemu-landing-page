# 小樹苗聯絡簿（SproutBook）— GitHub Pages 部署包

這是一個純 HTML / CSS / JavaScript 的互動式 Mobile-first Demo，不需要 Node.js、npm 或額外安裝任何套件。

## 最短部署方式（GitHub 網頁版）

1. 登入 GitHub，建立一個新的 **Public** repository，例如：`sproutbook-demo`。
2. 在 repository 首頁點選 **Add file → Upload files**。
3. 將這個資料夾內的所有檔案上傳到 repository 根目錄：
   - `index.html`
   - `.nojekyll`
4. 上傳完成後，進入 **Settings → Pages**。
5. 在 **Build and deployment** 的 **Source** 選擇 **Deploy from a branch**。
6. 在 Branch 選擇 `main`，資料夾選擇 `/(root)`，再按 **Save**。
7. GitHub 會顯示公開網址，格式通常是：
   `https://你的帳號.github.io/sproutbook-demo/`

> 建議第一次公開前，先用無痕視窗打開網址測試，確認手機也能正常點擊底部導覽、任務卡與預約視窗。

## 更新內容

未來只要替換 repository 裡的 `index.html`，GitHub Pages 會自動重新發佈。

## 檔案說明

- `index.html`：完整互動 Demo
- `.nojekyll`：避免 GitHub Pages 對靜態檔案進行 Jekyll 處理
