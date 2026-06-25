# sarathviswanath007.github.io

Personal portfolio + blog. Built with Jekyll, hosted on GitHub Pages.

---

## How to publish this site

1. Download all these files.
2. Go to your repo: `https://github.com/sarathviswanath007/sarathviswanath007.github.io`
3. Upload every file here, keeping the folder structure exactly
   (the folders starting with `_` matter — `_layouts`, `_posts`, etc.).
   - On GitHub web: **Add file → Upload files**, then drag everything in.
   - Or push from your computer with git.
4. Commit. GitHub Pages rebuilds automatically in ~1 minute.
5. Visit **https://sarathviswanath007.github.io/**

> Your existing `index.md` (the old near-empty page) should be **deleted or
> replaced** — this new `index.html` is your homepage now.

---

## Before you go live — fill in your contact links

Open `_config.yml` and add your real links so the contact buttons and footer work:

```yaml
email: "you@example.com"
linkedin: "https://www.linkedin.com/in/your-handle"
twitter: ""        # leave blank to hide
github: "sarathviswanath007"
```

Buttons and footer links for any field left blank are hidden automatically.

---

## How to write a new blog post

Every article is one Markdown file in the `_posts/` folder.

1. Create a file named: `YYYY-MM-DD-some-title.md`
   (e.g. `2026-07-15-evaluating-ai-test-output.md` — the date format matters).
2. Start it with this header, then write in Markdown below it:

```markdown
---
layout: post
title: "Your article title"
date: 2026-07-15
reading_time: "6 min read"
excerpt: "One or two sentences shown in the blog list."
---

Your article content starts here. Write in **Markdown**.

## A heading

A paragraph. You can use lists, > blockquotes, `code`, links, and images.
```

3. Commit it. It appears automatically at the top of `/blog/`.

That's it — no other files to touch. The post is styled, listed, and added to
your RSS feed automatically.

---

## File map

| File / folder | What it is |
|---|---|
| `_config.yml` | Site settings — title, links, your name |
| `index.html` | The homepage (portfolio) |
| `blog.html` | The blog listing page |
| `_posts/` | Your articles (one Markdown file each) |
| `_layouts/` | Page templates — you rarely touch these |
| `assets/css/style.scss` | All the styling |
| `Gemfile` | Tells GitHub Pages which plugins to use |

---

## Editing the portfolio content

All the homepage text lives in `index.html` as plain HTML — find the section,
edit the words. The stats, impact items, focus areas, and capabilities are all
there in readable blocks.
