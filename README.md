# Muzamil Murtaza — Tennis Portfolio

A single-page, fully interactive, tennis-themed portfolio for **Muzamil Murtaza**, Pakistan's No.1 tennis player.

## Files
- `index.html` — the entire site (HTML + CSS + JS, no build step).
- `assets/Muzamil-Murtaza-CV.pdf` — CV used by the **View CV** (in-page modal) and **Download CV** buttons.

## Run locally
Just open `index.html` in a browser. (The in-page CV viewer works best when served over http — see below — but Download CV works either way.)

```powershell
# optional local server so the embedded CV viewer loads cleanly
cd muzamil-murtaza-portfolio-2026
python -m http.server 8080   # then open http://localhost:8080
```

## Deploy as `muzamil-murtaza-portfolio-2026`

### Vercel (matches the reference site)
1. Push this folder to a GitHub repo named `muzamil-murtaza-portfolio-2026`.
2. Import it at https://vercel.com/new — it deploys as a static site automatically.
3. Your URL becomes `muzamil-murtaza-portfolio-2026.vercel.app`.

Or with the CLI:
```powershell
npm i -g vercel
vercel --prod
```

### GitHub Pages
1. Repo name: `muzamil-murtaza-portfolio-2026`.
2. Settings → Pages → deploy from `main` / root.
3. URL: `https://<username>.github.io/muzamil-murtaza-portfolio-2026/`.

## Sections
Hero · About · Achievements (replaces a tech stack) · Tournaments & Finals (timeline) ·
Skills & Strengths · How He Can Contribute · CV (view + download) · Contact.

## Interactive touches
- Custom tennis-ball cursor, animated typing role, scroll progress bar.
- Count-up stat numbers, animated skill bars, scroll-reveal sections.
- Floating bouncing tennis ball (click it to smash it faster).
- In-page CV viewer modal + one-click download.

Edit any text directly in `index.html` to update achievements or contact details.
