# The Cursor Is Still Blinking… ⌨️

**繁體中文** · [English](README.en.md)

> 獻給每一個對著空白文件發呆、游標閃到天亮的深夜。

一個關於「寫不出來」的小站——按一下,就生成一句研究生最真實的拖延心聲。這裡收集了那些卡關夜晚的內心 OS,也整理了寫不出來的原因與小小的解法,陪你笑一下,然後——先寫一句爛的吧。

這是拒稿三部曲的第三站:[被拒絕暖身版](https://we-regret-to-inform-you.sectools.tw)(下雨的夜)、[恭喜錄取版](https://we-are-pleased-to-inform-you.sectools.tw)(溫暖的黎明),還有這個對著游標發呆的深夜。

🔗 **線上看:** <https://stwater20.github.io/cant-write-my-paper/>

<br>

## 這裡有什麼

- **拖延語錄產生器**——按一下,隨機跳出一句研究生卡關時的內心 OS,搭配一句中文旁白,還會記錄你盯著空白文件幾次。
- **為什麼寫不出來?**——整理七個常見的卡點,每一個都附上一個能馬上做的小解法。
- **一鍵分享**——支援 X、Facebook、LINE、Threads 與複製連結,手機還能用系統原生分享。
- **存成圖片**——把當下這句拖延存成圖片,存證你今天有『在寫』。
- **深色 / 淺色主題**——右上角一鍵切換,深色是深夜螢幕、淺色是白紙,選擇會自動記住。
- **免安裝、純前端**——單一 HTML 檔搭配兩個資料檔就能運作,不需要任何建置流程。

<br>

## 在本機開啟

用瀏覽器直接打開 `index.html` 就好,不需要架伺服器。

<br>

## 一起貢獻拖延語錄

歡迎把你自己卡關時的內心 OS 加進來。所有內容都放在獨立的資料檔裡,**你完全不用動到 `index.html`**:

| 檔案 | 內容 |
| --- | --- |
| `quotes.js` | 拖延語錄 |
| `reasons.js` | 寫不出來的原因與解法 |

流程很單純:**Fork → 編輯 `quotes.js` → 送出 Pull Request**。詳細說明請見 [CONTRIBUTING.md](CONTRIBUTING.md)。

> 所有貢獻一律透過 Pull Request 進來,不直接改 `main`,讓每一句都有人再看過一次才合併。

<br>

## 專案結構

| 檔案 | 說明 |
| --- | --- |
| `index.html` | 主頁面,包含所有樣式與互動 |
| `quotes.js` | 拖延語錄資料 |
| `reasons.js` | 寫不出來的原因與解法資料 |
| `CONTRIBUTING.md` | 貢獻指南 |
| `PULL_REQUEST_TEMPLATE.md` | Pull Request 範本 |

<br>

## 部署到 GitHub Pages

前往 **Settings → Pages**,把 Source 設為「Deploy from a branch」,分支選 `main`、資料夾選 `/ (root)`,存檔後網站就會發布到:

```
https://<你的帳號>.github.io/<專案名稱>/
```

<br>

## 免責聲明

站上的句子是取材自研究生日常的再創作,純粹用來自嘲與打氣,並未影射任何特定的人。這個小站不會幫你寫論文,也不鼓勵拖延——它只是想在你卡住的時候陪你笑一下,然後提醒你:先寫一句爛的,永遠好過完美的空白。如果你只是累了,請記得休息,休息也是進度。

<br>

## 更多工具

想找更多實用小工具?歡迎逛逛 → <https://sectools.tw/tools>

---

<sub>Made at 3 AM for everyone whose cursor is still blinking. ⌨️</sub>
