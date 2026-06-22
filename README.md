# pbrunetgil.github.io

Personal and professional website for **Pol Brunet Gil** — machine learning &
applied mathematics. Live at <https://pbrunetgil.github.io>.

A single static page (no build step), designed around the trajectory from
deterministic RF signals to the stochastic processes of machine learning and
applied mathematics.

## Stack

Plain HTML, CSS, and vanilla JavaScript — no framework, served directly by
GitHub Pages.

| File | Purpose |
| --- | --- |
| `index.html` | Page content and structure |
| `styles.css` | Design system and layout |
| `script.js` | Hero "signal → noise" waveform, Experience-section interactive diagrams (BSC globe, WiNe RF gauge), and scroll reveals |
| `assets/` | CV PDF and favicon |

## Develop locally

Any static server works, for example:

```sh
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

GitHub Pages serves the `main` branch root automatically for a
`<user>.github.io` repository. Push to `main` and the site updates.
