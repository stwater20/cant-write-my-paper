# The Cursor Is Still Blinking… ⌨️

[繁體中文](README.md) · **English**

> For everyone staring at a blank page while the cursor blinks back at 3 AM.

A little site about not being able to write. Press a button and it generates a grad student's most honest procrastination thought. It collects those late-night stuck monologues and rounds up the reasons you're blocked — each with a tiny, doable fix — so you can laugh once and then write one bad sentence.

This is the third stop in the trilogy: [the rejection edition](https://we-regret-to-inform-you.sectools.tw) (a rainy night), [the acceptance edition](https://we-are-pleased-to-inform-you.sectools.tw) (a warm dawn), and this one — the night you stare at the cursor.

🔗 **Live site:** <https://stwater20.github.io/cant-write-my-paper/>

<br>

## What's inside

- **Writer's-block generator** — one click serves a stuck-writer monologue with a bit of commentary, and counts how many times you've stared at the blank page.
- **Why you're stuck** — seven common blockers, each with a small fix you can do right now.
- **One-tap sharing** — X, Facebook, LINE, Threads, copy link, plus native sharing on mobile.
- **Save as image** — turn the current line into an image as proof you were "writing."
- **Light / dark theme** — toggle in the top-right; dark is a late-night screen, light is a blank page. Your choice is remembered.
- **No build step** — a single HTML file plus two data files. Just open it.

<br>

## Run it locally

Open `index.html` in your browser. No server required.

<br>

## Contributing procrastination lines

Add your own late-night stuck monologue. All the content lives in standalone data files, so **you never have to touch `index.html`**:

| File | Contents |
| --- | --- |
| `quotes.js` | Writer's-block lines |
| `reasons.js` | Reasons you're stuck (with fixes) |

The flow is simple: **fork → edit `quotes.js` → open a pull request**. See [CONTRIBUTING.en.md](CONTRIBUTING.en.md) for the full guide.

> Every contribution goes through a pull request — nobody pushes to `main` directly, so each line gets a second pair of eyes before it's merged.

<br>

## Project structure

| File | Description |
| --- | --- |
| `index.html` | The page, with all styles and interactions |
| `quotes.js` | Writer's-block line data |
| `reasons.js` | Reasons-you're-stuck data |
| `CONTRIBUTING.md` | Contribution guide |
| `PULL_REQUEST_TEMPLATE.md` | Pull request template |

<br>

## Deploy to GitHub Pages

Go to **Settings → Pages**, set Source to "Deploy from a branch", pick the `main` branch and the `/ (root)` folder, then save. Your site publishes to:

```
https://<username>.github.io/<repo>/
```

<br>

## Disclaimer

The lines are original riffs on everyday grad-student life, meant purely for catharsis and encouragement. This site won't write your paper and doesn't celebrate procrastination — it just wants to make you smile when you're stuck, then remind you: one bad sentence beats a perfect blank page. And if you're simply exhausted, rest — that counts as progress too.

<br>

## More tools

Looking for more handy tools? → <https://sectools.tw/tools>

---

<sub>Made at 3 AM for everyone whose cursor is still blinking. ⌨️</sub>
