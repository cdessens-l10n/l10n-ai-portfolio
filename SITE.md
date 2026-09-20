# Site details

Low-level notes for maintaining the public portfolio. For the work summary and live link, see [README.md](README.md).

## Live URL

https://cdessens-l10n.github.io/l10n-ai-portfolio/

GitHub Pages is configured to publish from the **`docs/`** folder on the **`main`** branch.

## What’s in `docs/`

| File | Role |
|------|------|
| `index.html` | Horizontal slide deck (intro → outcomes → Autopilot → Terminology → also-built → FAQ → contact) with left/right arrows, dots, and keyboard navigation |
| `styles.css` | Layout and typography |
| `assets/` | Optional static assets (diagrams, images) |
| `.nojekyll` | Serve plain HTML without Jekyll processing |

Relative links inside `index.html` (e.g. `styles.css`) assume that CSS lives next to the HTML in `docs/`.

## Local preview

From the repo root:

```bash
cd docs
python3 -m http.server 8080
```

Open http://localhost:8080

Or open `docs/index.html` directly in a browser (Mermaid diagrams need network access to the CDN).

## What this repo is not

- Not private skill source trees, CLIs, or configs  
- Not credentials, tokens, or TMS/project identifiers  
- Keep personal skill zips **offline / private** — never commit them here  

The public page **describes** system roles (file inventory tables, diagrams). It does not ship the production skill packs.

## Publishing checklist (after edits)

1. Edit files under `docs/` (and README/SITE if needed).  
2. Commit and push to `main`.  
3. Wait for Pages to rebuild (often 1–2 minutes).  
4. Hard-refresh the live URL if the browser caches an old page.

## Contact (also on the live page)

- LinkedIn: https://www.linkedin.com/in/frenchlanguagemanager  
- Email: christelledessens@gmail.com  
