# HomeJarvis MVP 網站部署步驟

這個資料夾是一個可以直接部署的靜態網站 MVP。

## 本地預覽

直接用瀏覽器打開：

```text
index.html
```

## GitHub Pages 部署

1. 建立 GitHub repository。
2. 上傳 `index.html` 到 repository 根目錄。
3. 到 `Settings` → `Pages`。
4. Source 選 `Deploy from a branch`。
5. Branch 選 `main`，Folder 選 `/root`。
6. 按 `Save`。
7. 等 1 到 5 分鐘後，網站會出現在：

```text
https://你的帳號.github.io/你的repo名稱/
```

本專案目前網址應為：

```text
https://jason20070118.github.io/20260603/
```

## 表單說明

目前表單是前端展示用，會模擬送出。若要正式收資料，可以串接 Google Sheet 或 Apps Script。
