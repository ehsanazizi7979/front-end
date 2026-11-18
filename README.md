# front-end

Study notes from the JavaScript books in this repository.

## Chapter summaries

- **[index.html](index.html)** — Chapter summaries of *Secrets of the JavaScript Ninja, Third Edition*
  (MEAP V10), in one self-contained HTML page with a chapter switcher:
  - **Chapter 1 — JavaScript is everywhere** (printed pp. 1–16)
  - **Chapter 2 — Using modern JavaScript tools** (printed pp. 17–43): TypeScript, ESLint, Prettier,
    Husky — listings 2.1–2.15

  The book’s figure and note icons are embedded as data URIs, and every code listing is reproduced
  with its `#A`–`#E` callouts. No external requests, so the file works offline or opened from disk.

### Assets

The extracted images also live in `assets/chapter1/` as standalone PNGs:

| File | Used for |
| --- | --- |
| `figure-1-1.png` | Figure 1.1 — how a JavaScript runtime brings code to life |
| `icon-eslint.png` | The book’s ESLint-tip icon |
| `icon-performance.png` | The book’s performance-tip icon |

`index.html` does not depend on those files — it embeds them inline, so it works when opened
directly from disk, offline, or on its own.

### Source books

- Secrets of the JavaScript Ninja, Third Edition (MEAP V10) — chapters 1 and 2 summarised
- Eloquent JavaScript, 4th Edition
- JavaScript: The Definitive Guide, 7th Edition
- You Don’t Know JS Yet: Get Started
