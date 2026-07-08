# cfk44.github.io

Persönliche Website von Christoph Friedrich Koch (CFK) — Business Development × Data Science, Berlin.

**Live:** https://cfk44.github.io

## Stack
Statisches HTML/CSS/JS in einer Datei — kein Build-Prozess, keine Dependencies.
Typografie: Space Grotesk + JetBrains Mono (Google Fonts).

## Struktur
| Datei | Zweck |
|---|---|
| `index.html` | Gesamte Site (bilingual DE/EN, Toggle oben rechts) |
| `404.html` | Fehlerseite |
| `favicon.svg` | Site-Icon (Höhenprofil-Mark) |
| `robots.txt` / `sitemap.xml` | SEO |

## Deployment
GitHub Pages, Branch `main`, Root-Verzeichnis. Jeder Push auf `main` deployt automatisch (~1 min).

```bash
git add . && git commit -m "update" && git push
```

## Custom Domain (später)
1. Domain registrieren, 2. in Settings → Pages eintragen, 3. beim Registrar A-Records auf
185.199.108.153 / .109 / .110 / .111 setzen + CNAME `www` → `cfk44.github.io`,
4. Canonical-URL und sitemap.xml/robots.txt in diesem Repo auf die neue Domain umstellen.
