# 喆圓農產行官方網站

這是可直接部署到 GitHub Pages 的純靜態網站，不需要安裝套件或設定資料庫。

## 方法一：使用 GitHub 網頁上傳（推薦）

1. 登入 GitHub，建立新的 Repository，例如 `zheyuan-fresh-produce`。
2. 將 ZIP 解壓縮，把資料夾內的所有檔案上傳到 Repository 的 `main` 分支。
3. 進入 Repository 的 **Settings → Pages**。
4. 在 **Build and deployment → Source** 選擇 **GitHub Actions**。
5. 稍候約 1～3 分鐘，網站會自動發布。
6. 可在 **Actions** 頁面查看發布進度，完成後會顯示網站網址。

## 方法二：使用 Git 指令

```bash
git init
git add .
git commit -m "建立喆圓農產行網站"
git branch -M main
git remote add origin https://github.com/你的帳號/你的專案名稱.git
git push -u origin main
```

接著到 GitHub 的 **Settings → Pages**，將 Source 設為 **GitHub Actions**。

## 修改內容

- 網站文字：編輯 `index.html`
- 顏色與版面：編輯 `styles.css`
- 首頁圖片：更換 `assets/hero-produce.png`，並保留相同檔名
- 電話：搜尋 `0978771736` 或 `0978 771 736`
- Facebook：搜尋 `facebook.com`

## 專案內容

- `index.html`：網站頁面
- `styles.css`：桌機與手機版樣式
- `assets/hero-produce.png`：主視覺圖片
- `.github/workflows/deploy-pages.yml`：GitHub Pages 自動發布設定
- `.nojekyll`：避免 GitHub Pages 忽略網站檔案

## 現有聯絡資料

- 電話：0978 771 736
- 地址：401 臺中市東區東興里建德街120號
- 主打：美生菜、各式新鮮蔬菜冷藏配送

