# nunc.gannaca.com

Teaser-Site des NUNC Verlags (Marke der gannaca GmbH & Co. KG). Statisches HTML, keine Build-Pipeline.

- `index.html` deutsch, `en/index.html` englisch, Danke-Seiten unter `danke/` und `en/thanks/`
- Newsletter über Netlify Forms (Formularname `newsletter`, Hidden-Feld `source=nunc.gannaca.com`)
- Fonts self-gehostet unter `assets/fonts/` (Fraunces, Newsreader)
- Header, Cache und CSP in `netlify.toml`

Deploy: Netlify, Publish-Verzeichnis `.` (Repo-Root). Custom Domain `nunc.gannaca.com`, CNAME im KAS auf `<site>.netlify.app`.
