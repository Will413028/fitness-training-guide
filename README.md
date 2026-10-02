# 半馬訓練與飲食計畫

一頁式繁體中文訓練與飲食指南，整理半馬跑走進度、每週三次重訓、每日用餐時段，以及 24 道 Instant Vortex Pro 食譜。

## 本機預覽

在專案根目錄執行：

```sh
python3 -m http.server 8000 --directory site
```

再開啟 `http://localhost:8000`。

## Cloudflare Pages

網站使用純 HTML、CSS 與 JavaScript，沒有建置步驟。連接 GitHub repository 時，Cloudflare Pages 設定如下：

- Framework preset：None
- Build command：留空
- Build output directory：`site`
- Production branch：`main`

Cloudflare Pages 的 Git integration 會在 production branch 更新後自動部署。設定方式見[Cloudflare Pages Git integration 文件](https://developers.cloudflare.com/pages/configuration/git-integration/)與[建置設定文件](https://developers.cloudflare.com/pages/configuration/build-configuration/)。

GitHub public repository 已建立：https://github.com/Will413028/fitness-training-guide。Cloudflare Pages Git integration 尚未設定，網站尚未部署。

## 公開內容範圍

頁面保留 75 kg 範例基準、半馬目標、訓練安排與食譜；不收錄個人姓名、用藥清單、病史、檢查數值或治療紀錄。食譜及訓練量是參考範例，請依個人狀況調整。

目前未附開源授權。
