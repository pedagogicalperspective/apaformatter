# apa7-formatter

**Claude skill** — APA 7th edition reference list formatter with Turkish title translation.

Live docs → `https://<your-username>.github.io/apa7-formatter/`

## What it does

- Formats raw reference lists to strict APA 7 rules
- Normalises DOIs (`http://dx.doi.org/` → `https://doi.org/`)
- Removes publication cities from books
- Italicises journal names, volumes, and book titles
- Appends `[English translation]` to every Turkish-language title
- Flags suspicious entries inline (`[doğrulanmalı]`, `[tamamlanmalı]`)

## Trigger phrases

> APA 7'ye göre düzenle · kaynakçayı düzelt · format references · APA formatına çevir

## Deploy to GitHub Pages

1. Create a new repo (e.g. `apa7-formatter`)
2. Push `index.html` and `README.md` to the `main` branch
3. Go to **Settings → Pages → Source: Deploy from branch → main / (root)**
4. Site will be live at `https://<your-username>.github.io/apa7-formatter/`

## Install the skill

Download `apa7-formatter.skill` and upload it via the **Skills** panel in Claude.

---

*Pedagogical Perspective · eISSN 2822-4841 · pedagogicalperspective.com*
