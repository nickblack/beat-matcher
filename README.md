# beat-matcher

Below is everything you need to drop straight into a fresh Git-repository and publish as an MIT-licensed, single-file web app.

---

## 1 ⸺ Repo layout

```
beat-ratio-finder/
├─ index.html        ← the app (rename the current file)
├─ LICENSE           ← MIT text below
├─ README.md         ← project blurb & how-to
└─ .gitignore        ← optional; keeps clutter out
```

> **Tip:** GitHub Pages serves `index.html` from the repo root automatically—no build step needed.

---

## 2 ⸺ LICENSE  (MIT)

Create a file called **`LICENSE`** with exactly this content:

```
MIT License

Copyright (c) 2025 <YOUR NAME>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 3 ⸺ README.md

````markdown
# Beat-Ratio Finder

A lightning-fast, client-side tool for DJs who need to **beat-match two tracks with
integer beat ratios**—no DAW, no database, no backend.

![screenshot](docs/screenshot.png)

## ✨ Features
- **Instant results**: type current BPM & number of beats → options appear.
- **0.5 BPM rounding + tolerances**: practical, real-world values.
- **“Load More”**: reveals deeper ratios only when you need them.
- No dependencies apart from Tailwind’s CDN.

## 🚀 Quick start
```bash
git clone https://github.com/<your-handle>/beat-ratio-finder.git
cd beat-ratio-finder
open index.html        # or double-click in your file explorer
````

Or view the live demo on GitHub Pages:
[https://your-handle.github.io/beat-ratio-finder/](https://your-handle.github.io/beat-ratio-finder/)

## 📂 Files

| File         | Purpose                                   |
| ------------ | ----------------------------------------- |
| `index.html` | The entire app—HTML, Tailwind CDN, and JS |
| `LICENSE`    | MIT License                               |
| `README.md`  | This file                                 |

## 🖥 Developing

Just edit `index.html`, save, and refresh your browser.

## 🤝 Contributing

Pull requests welcome! Please open an issue first to discuss
major changes.

## 📝 License

MIT © 2025 \<Your Name>

```

*(Replace `<your-handle>` and `<Your Name>`.)*

---

## 4 ⸺ Minimal .gitignore

```

# macOS

.DS\_Store

# VS Code

.vscode/

# misc

\*.log

````

---

## 5 ⸺ Publish workflow

```bash
# 1  Initialise & add files
git init
git add index.html LICENSE README.md .gitignore
git commit -m "Initial open-source release"

# 2  Create a new GitHub repo (or via web UI)
git remote add origin git@github.com:<your-handle>/beat-ratio-finder.git

# 3  Push
git push -u origin master   # or main

# 4  Enable GitHub Pages
#    → Settings ▸ Pages ▸ Source: “Deploy from a branch” ▸ branch: master/main
````

That’s it—your single-page DJ helper is now open-source and instantly browsable via GitHub Pages!
