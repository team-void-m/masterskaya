# Landing page of the vibe-coding workshop (Мастерская вайбкодинга)

This repo is one static web page. It is live at https://makscee.ru/course about a minute after a change lands on `main`. The owner of the text is Ася (not a developer): she asks for changes in plain Russian, you make them.

## Rules

- **One static file.** All of the page is `index.html` (HTML, CSS and a little JS inline). Do not split it into many files, do not add a framework, a bundler, `package.json`, a build step or a generator. Pages serves the files as they are.
- **Fonts are self-hosted** in `fonts/` (Golos and Manrope, `.woff2`). Never link Google Fonts or any other font CDN, and never load anything else from a third-party host (analytics, trackers, CDN scripts).
- **Images** go in `assets/`. Keep a photo under about 300 KB and square if it sits in a round frame; keep `og.png` at 1200×630.
- **Paths start with `/course/`**: the page is served at `makscee.ru/course`, so a file `assets/max.jpeg` is written `/course/assets/max.jpeg` in the HTML. A path without `/course/` breaks on the live page.
- **Sign-up buttons** all open the Google Form (the same `href` in every «Хочу в мастерскую» button). If the form link changes, change it in all of them.
- **Language:** the page is in Russian; keep the style of the text around the change. Keep the page working on a phone (390 px wide) with no sideways scrolling.
- **Changes go live straight away.** Work on `main`, commit with a short message in plain words, and say in the answer what changed and where on the page. If a request is unclear, ask before changing.
- **Undo** is `git revert` of the last commit (or restoring the file from an earlier commit).
