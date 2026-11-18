# Negus Digitals — portfolio

Static site (no build step).

- `/` — portfolio of Natnael Yednekachew
- `/sites/aurum-estates/`, `/sites/savora-cafe/`, `/sites/lumen-clinic/`, `/sites/nova-academy/`, `/sites/velvet-events/` — concept sites

## Deploy to Vercel

**CLI**
```
npm i -g vercel
cd negus-digitals-site
vercel --prod
```
When asked, use: Framework = Other, no build command, output directory = `.`

**GitHub**
Push this folder to a repo, then vercel.com/new → Import → Framework Preset: Other → Deploy.

Custom domain: Project → Settings → Domains.
