# front-end

Study notes from the JavaScript books in this repository.

## Chapter summaries

- **[index.html](index.html)** — Chapter summaries of *Secrets of the JavaScript Ninja, Third Edition*
  (MEAP V10), in one self-contained HTML page with a ten-tab chapter switcher:
  - **Chapter 1 — JavaScript is everywhere** (printed pp. 1–16)
  - **Chapter 2 — Using modern JavaScript tools** (printed pp. 17–43): TypeScript, ESLint, Prettier,
    Husky — listings 2.1–2.15
  - **Chapter 3 — Working with Node.js and npm** (printed pp. 44–60): the runtime, the REPL,
    `node_modules` resolution, semver and lockfiles, forking/patching, scripting and `npx` —
    listing 3.1
  - **Chapter 4 — Building web applications** (printed pp. 61–76): the lifecycle, the
    page-building phase, the DOM, the event queue, and JSX/React — figures 4.1–4.6 and
    listings 4.1–4.3
  - **Chapter 5 — First-class functions for the novice** (printed pp. 77–114): the six ways to
    define functions, IIFEs, arrow functions, callbacks, sets/metadata/memoization, rest and
    default parameters, and TypeScript for functions — figures 5.1–5.6 and listings 5.1–5.18
  - **Chapter 6 — Functions for the journeyman** (printed pp. 115–134): the `this` parameter, the
    four invocation styles, constructors and `new.target`, `call`/`apply`, unbound methods,
    `bind` and lexical `this` — figures 6.1–6.2 and listings 6.1–6.5
  - **Chapter 7 — Functions for the master: closures and scopes** (printed pp. 135–153): the
    closure “bubble”, function-scoped caches, closures in timer callbacks, block scopes, loop
    scope, hoisting and the temporal dead zone, parsing/scope analysis, `globalThis` and
    closure-induced memory leaks — figure 7.1 and listings 7.1–7.8
  - **Chapter 8 — Functions for the future: promises and generators** (printed pp. 154–183):
    promise states and resolution, `then`/`catch`/`finally` chaining, `Promise.all`/`any`/`race`/
    `allSettled`, microtasks vs. macrotasks, `async`/`await`, iterables and iterators, generator
    functions, `yield*` and async generators — figures 8.1–8.2 and listings 8.1–8.14
  - **Chapter 9 — Objects, prototypes, and classes** (printed pp. 184–212): getters and setters,
    property descriptors (accessor and data), proxies and `Reflect`, the prototype chain,
    constructors and `instanceof`, classes, `extends`/`super`, statics and private `#fields`
    — figures 9.1–9.7 and listings 9.1–9.9
  - **Chapter 10 — Dealing with collections** (printed pp. 213–259, the last chapter in the
    excerpt): array creation, `length` and holes, `push`/`pop`/`shift`/`unshift`/`splice`/`slice`,
    the iteration and functional methods (`map`, `flatMap`, `every`, `some`, `find`, `filter`,
    `sort` with `Intl.Collator`, `reduce`), maps and `WeakMap`, sets and `WeakSet`, read-only
    TypeScript collections and Immer — figures 10.1–10.8 and listings 10.1–10.15

  The book’s figure and note icons are embedded as data URIs, and every code listing is reproduced
  with its `#A`–`#E` callouts. No external requests, so the file works offline or opened from disk.

### Assets

The extracted images also live in `assets/chapter1/`, `assets/chapter4/`, `assets/chapter5/`,
`assets/chapter6/` through `assets/chapter10/` as standalone files:

| File | Used for |
| --- | --- |
| `figure-1-1.png` | Figure 1.1 — how a JavaScript runtime brings code to life |
| `icon-eslint.png` | The book’s ESLint-tip icon |
| `icon-performance.png` | The book’s performance-tip icon |
| `chapter4/figure-4-*.webp` | Figures 4.1–4.6 (WebP, 900 px wide) |
| `chapter4/figure-4-*.png` | The same figures at the PDF’s native resolution |
| `chapter5/figure-5-*.webp` | Figures 5.1–5.6 (WebP, 900 px wide) |
| `chapter5/figure-5-*.png` | The same figures at the PDF’s native resolution |
| `chapter6/figure-6-*.webp` | Figures 6.1–6.2 (WebP, 900 px wide) |
| `chapter6/figure-6-*.png` | The same figures at the PDF’s native resolution |
| `chapter7/figure-7-1.webp` | Figure 7.1, the closure bubble (WebP, 900 px wide) |
| `chapter7/figure-7-1.png` | The same figure at the PDF’s native resolution |
| `chapter8/figure-8-*.webp` | Figures 8.1–8.2 (WebP, 900 px wide) |
| `chapter8/figure-8-*.png` | The same figures at the PDF’s native resolution |
| `chapter9/figure-9-*.webp` | Figures 9.1–9.7 (WebP, 900 px wide) |
| `chapter9/figure-9-*.png` | The same figures at the PDF’s native resolution |
| `chapter10/figure-10-*.webp` | Figures 10.1–10.8 (WebP, 900 px wide) |
| `chapter10/figure-10-*.png` | The same figures at the PDF’s native resolution |

`index.html` does not depend on those files — it embeds them inline (figure PNGs as WebP data
URIs to keep the page small), so it works when opened directly from disk, offline, or on its own.

### Source books

- Secrets of the JavaScript Ninja, Third Edition (MEAP V10) — chapters 1–10 summarised
- Eloquent JavaScript, 4th Edition
- JavaScript: The Definitive Guide, 7th Edition
- You Don’t Know JS Yet: Get Started
