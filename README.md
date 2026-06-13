# my batch — site marketing

Site vitrine de mybatch.cooking. Pages : home, guide, guide complet (post-achat), histoire.
L'application elle-même est hébergée sur app.mybatch.cooking (repo legoutdulien).

Déploiement : push sur GitHub = redeploy Netlify automatique.

## Structure

- `index.html` — home (pitch app)
- `guide.html` — guide public (avec paywall)
- `guide-complet.html` — guide version débloquée (post-achat)
- `histoire.html` — l'histoire du duo
- `styles.css` — feuille partagée
- `netlify.toml` — config + redirects vers app.mybatch.cooking
