# Contributing procrastination lines ⌨️

[繁體中文](CONTRIBUTING.md) · **English**

Add your own late-night, can't-write-a-word inner monologue.

**Every contribution goes through a pull request** — nobody pushes to `main` directly, so each line gets a second pair of eyes before it's merged.

All the content lives in standalone data files, so **you never have to touch `index.html`**:

| File | Contents |
| --- | --- |
| `quotes.js` | Writer's-block lines |
| `reasons.js` | Reasons you're stuck (with fixes) |

<br>

## How to add a line

1. Click **Fork** in the top-right to copy the project under your own account.
2. Open **`quotes.js`** and append an entry to the `window.QUOTES` array:
   ```js
   { en: "The cursor blinks. I blink back. Nobody writes anything.", zh: "游標閃,我也閃,誰都沒動筆。" },
   ```
   - `en`: a stuck-writer thought in English.
   - `zh`: a line of commentary in Chinese.
3. Commit, then open a **pull request** with a short title describing what you added.

To add a "why you're stuck" entry, edit **`reasons.js`** instead, using this format:

```js
{ title: "Short title", en: "English explanation", zh: "中文旁白(帶一點建議)" },
```

<br>

## Check it locally

Just open `index.html` in your browser — the data loads via `<script src>`, so no server is needed.

<br>

## A few ground rules

- Keep it self-deprecating and kind — **don't punch down**, and don't name real people.
- One to a few lines per pull request, so it's easy to review.
- One English line plus one Chinese line, to keep the site bilingual.
- Not sure whether to add something? Open an issue to discuss first.

<br>

## Code changes

Changes to the interface, animation, sharing, or the light/dark theme are just as welcome — open a pull request with a short description.

Thanks for keeping the stuck nights a little less lonely. One bad sentence beats a perfect blank page. ⌨️
