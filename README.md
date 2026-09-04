# 電商易 EshopEasy

香港中小企網站同 App 宣傳頁。公開品牌係 **電商易**（中文）／ **EshopEasy**（英文）。倉庫名維持 `katan-studio`，GitHub Pages 路徑係 [`/katan-studio/`](https://katanli.github.io/katan-studio/)。

負責人：Katan Li（[github.com/katanli](https://github.com/katanli)）。查詢 WhatsApp：[wa.me/85251057090](https://wa.me/85251057090)。

## 本機預覽

靜態檔，用任何 HTTP server 開根目錄即可（唔好用 `file://`，相對路徑同字型會較穩）：

```bash
python3 -m http.server 8080
```

然後開 <http://localhost:8080/>。

## 開 GitHub Pages

上線目標：<https://katanli.github.io/katan-studio/>

1. 將 `main` 推上 GitHub（呢個 repo 嘅預設分支）。
2. 開 **Settings → Pages**。
3. **Source** 揀 **Deploy from a branch**。
4. Branch 揀 **`main`**，資料夾揀 **`/ (root)`**。
5. 儲存。一兩分鐘後可用上面嘅 Pages 網址。

唔使 Jekyll build（已放 `.nojekyll`）。`index.html`、`css/`、`js/`、`assets/` 全部用相對路徑，喺 `/katan-studio/` 底下會正常載入。

## 內容備註

- 套餐價（港幣）：Starter HK$6,800；Business HK$14,800；網店／預約由 HK$24,800 起；每月保養 HK$280–480。
- iOS App 係進階項目，頁面只寫「另行報價」。
- 作品例子只放已上線嘅 [Wonderland JP](https://katanli.github.io/wonderland-jp/)，冇假評價、假 logo。
- 查詢 WhatsApp：+852 5105 7090。
