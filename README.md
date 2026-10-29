# Resume Website — Achebe Justice Chinecherem

A single-page, accessible online resume for **Achebe Justice Chinecherem** — Data Scientist | Data Analyst.

## Highlights

- **Zero dependencies** — hand-written semantic HTML, CSS, and a sprinkle of vanilla JS. No frameworks, no build step, no external requests.
- **Accessible (WCAG-minded)** — skip link, landmark regions, single logical heading order, AA+ color contrast, visible focus states, `aria-current` scroll-spy nav, `prefers-reduced-motion` support, fully usable without JavaScript.
- **Print-ready** — a dedicated print stylesheet turns the page into a clean paper resume (Ctrl/Cmd + P → Save as PDF).
- **SEO** — meta description, Open Graph tags, and JSON-LD `Person` structured data.
- **Downloadable CV** — the hero button serves the ATS-optimized DOCX resume directly from the repo.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The entire site (styles, content, structured data inline) |
| `Achebe_Justice_Chinecherem_Data_Scientist_CV.docx` | Downloadable ATS-optimized CV |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Deploy (GitHub Pages)

1. Push this folder to a GitHub repository.
2. **Settings → Pages → Source: Deploy from a branch → `main` / root → Save.**
3. The site goes live at `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` for a `<username>.github.io` repo).

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
