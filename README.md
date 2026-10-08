# MRB — Mass Report Bot · Educational Simulation (plain web build)

A frontend-only educational demo. Every target, job, report and chart is fictional and generated
locally in your browser. **No real reports are submitted and no external platform is contacted.**

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole app: HTML, CSS, JavaScript and fonts in one file. No npm, no build step, no internet needed. |
| `favicon.svg` | Browser tab icon. |
| `.htaccess` | Optional, for Hostinger: forces HTTPS and sets cache/security headers. |

## Run it locally
Double-click `index.html`. It opens in your browser and works offline.

## Put it on Hostinger
1. hPanel → Websites → Manage → **File Manager** → open `public_html/`.
2. Upload `index.html`, `favicon.svg` and `.htaccess` (enable "show hidden files" to see `.htaccess`).
3. Open your domain. Works the same in a sub-folder (e.g. `public_html/mrb-demo/`) with no changes.

Pages use addresses like `yourdomain.com/#/dashboard`, so refreshing any page always works.

## Demo login
`demo@mrb.local` / `demo1234`, or click **Enter Demo Mode**.

## Pages
Landing · Login · Dashboard · Targets · Report Simulation (5-step wizard + live view) · Results (export report) ·
Jobs · Activity Logs · Analytics · Settings · Profile · Architecture · Presentation Mode.

Data and settings are saved in your browser (localStorage). Reset them in **Settings → Demo configuration → Reset data**.

## Editing the source
The readable source code (React + TypeScript) is in `mrb-educational-demo-source.zip`. After editing, run
`npm install` then `npm run build:web` and copy `dist-web/index.html` here.

*Mass Report Bot — Educational Simulation · Built for educational demonstration · Simulation Mode • No real reports submitted*
