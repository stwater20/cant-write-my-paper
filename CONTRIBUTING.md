# 一起收集拖延語錄 ⌨️

**繁體中文** · [English](CONTRIBUTING.en.md)

歡迎把你自己卡關、寫不出來時的內心 OS 貢獻上來。

**所有貢獻一律透過 Pull Request**——不直接改 `main`,讓大家一起看過再合併。

所有內容都拆成獨立的資料檔,**你完全不用動到 `index.html`**:

| 檔案 | 內容 |
| --- | --- |
| `quotes.js` | 拖延語錄 |
| `reasons.js` | 寫不出來的原因與解法 |

<br>

## 怎麼加一句語錄

1. 按右上角的 **Fork**,把這個專案複製到你自己的帳號底下。
2. 打開 **`quotes.js`**,在 `window.QUOTES` 陣列的最後加上一筆:
   ```js
   { en: "The cursor blinks. I blink back. Nobody writes anything.", zh: "游標閃,我也閃,誰都沒動筆。" },
   ```
   - `en`:一句寫不出來時的內心 OS(英文)。
   - `zh`:一句中文旁白。
3. Commit 之後送出 **Pull Request**,標題簡單說明你加了什麼。

想補充「寫不出來的原因與解法」就改 **`reasons.js`**,格式如下:

```js
{ title: "Short title", en: "English explanation", zh: "中文旁白(帶一點建議)" },
```

<br>

## 在本機確認

直接用瀏覽器打開 `index.html` 就能看到效果——資料是透過 `<script src>` 載入的,不需要架伺服器。

<br>

## 幾個小規矩

- 保持自嘲、療癒,**別酸別人**,也不點名真實的人。
- 一次 Pull Request 加一到數句就好,方便大家 review。
- 中英各一句,維持全站的雙語風格。
- 不確定要不要加?先開一個 Issue 討論也可以。

<br>

## 想改功能

介面、動畫、分享、深淺色主題之類的改動同樣歡迎,一樣送 Pull Request、附上簡短說明就好。

謝謝你讓卡關的深夜多一點陪伴。先寫一句爛的,永遠好過完美的空白。⌨️
