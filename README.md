# Post Script — The editor LinkedIn forgot.

> Format, grade and refine your LinkedIn posts before you publish.

**[→ Try it live](https://tadisweb.github.io/PostScript/)**

---

## What is this?

LinkedIn's native composer is barebones. Post Script gives you the writing environment it should have had — a proper editor with real-time feedback, a live preview, post grading, and optional AI rewrites, all in a single file that runs entirely in your browser.

No sign-up. No data sent anywhere (unless you choose to use AI rewrites, which use your own API key). Nothing installed.

---

## Features

**Editor**
- Rich text editing with bold and italic (via toolbar or `Ctrl+B` / `Ctrl+I`)
- Bullet and numbered lists
- Blank line insertion to control spacing in the LinkedIn feed
- Undo / redo
- Strip formatting — converts everything back to clean plain text

**Real-time stats**
- Character count against LinkedIn's 3,000 character limit
- Unicode count — shows the true character count after bold/italic conversion (LinkedIn uses Unicode characters for formatting, which inflates your count)
- Hook length — tracks the first ~210 characters visible before the "see more" fold
- Word count

**Post Grader**
- Scores your post and flags specific things to improve — hook strength, length, readability, and more

**AI Suggestions**
- Toggle on for live coaching as you write

**AI Rewrite** *(optional)*
- Generates 3 alternative versions of your post using Claude (Anthropic) or ChatGPT (OpenAI)
- Requires your own API key — entered locally, never stored on a server

**Templates**
- Pre-built post structures to start from when you're staring at a blank page

**Live Preview**
- See exactly how your post will render in the LinkedIn feed, including the "see more" fold

**Drafts**
- Save and reload drafts within your browser session
- Export and import drafts as JSON to back them up or move them between devices

**Copy to LinkedIn**
- One click to copy the formatted post ready to paste directly into LinkedIn

---

## How to use

1. Open the live link above in any modern browser
2. Write your post in the editor on the left
3. Watch the preview update in real time on the right
4. Use the Post Grader and AI Suggestions panels to refine your draft
5. When you're happy, click **Copy to LinkedIn** and paste into the LinkedIn composer

---

## Tech stack

A single HTML file — no frameworks, no build step, no dependencies. Vanilla HTML, CSS, and JavaScript. The only external resource is the [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) font loaded from Google Fonts.

---

## Running locally

No setup needed. Just download `index.html` and open it in a browser.

```
open index.html
```

---

## Privacy

Post Script runs entirely client-side. Your writing never leaves your browser unless you use the AI Rewrite feature, which sends your post text to Anthropic or OpenAI using your own API key. No analytics, no tracking, no accounts.

---

*Built by [Ahmed Sidat](https://www.linkedin.com/in/ahmedsidat) — exploring the nexus between leadership, next-gen sales and marketing mastery.*
