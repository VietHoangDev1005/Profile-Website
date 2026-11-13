# Nguyen Viet Hoang - Profile Website

Personal profile page for recruiters: about, experience, projects, skills, education and contact.
Bilingual (English / Vietnamese) with a light/dark theme toggle.

Built with plain HTML, CSS and JavaScript - no build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 5173
```

## Deploy with GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch `main`, folder `/ (root)`.

## Edit content

- English text: `index.html`
- Vietnamese text: the `VI` object in `script.js` (same `data-i18n` keys)
- Photo and CV: `assets/`
