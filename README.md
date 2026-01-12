# cepelinai

A personal, static community hub for Terence’s journey toward buying land and building a homestead in Lithuania. Built with semantic HTML, CSS, and vanilla JavaScript, and ready for GitHub Pages.

## File structure

```
/
  index.html
  about.html
  wall.html
  code.html
  contact.html
  404.html
  assets/
    css/style.css
    js/script.js
  README.md
  .gitignore
  LICENSE
```

## Run locally

Open any HTML file directly in your browser, for example:

- `index.html`
- `about.html`

No build steps or dependencies are required.

## GitHub Pages deployment

1. Go to **Settings → Pages** in the repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **Branch: main** and **Folder: / (root)**.
4. Click **Save**.

## Replace placeholders

### Formspree
Update the Formspree endpoint in both forms:

- `index.html` (email capture form)
- `contact.html` (contact form)

Replace:

```
https://formspree.io/f/yourFormId
```

with your real Formspree form ID.

### Giscus
Update the Giscus placeholders in `wall.html`:

- `data-repo="your-org/your-repo"`
- `data-repo-id="your-repo-id"`
- `data-category="General"`
- `data-category-id="your-category-id"`

Use the values from your Giscus setup.

## NO BINARIES policy

This repository intentionally contains **only plain text files** (HTML, CSS, JS, Markdown, .gitignore, and LICENSE). Do not add images, fonts, PDFs, base64, or other binary assets.

## Notes

- Default language is Lithuanian (LT) with a persistent toggle.
- All visible text is translated via `assets/js/script.js`.
