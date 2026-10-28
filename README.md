# UBRIS Impact
Landing page UBRIS — audit strategic L&D, self-audit interactiv și concept CEO Office.

## Publicare pe GitHub Pages
1. Creează un repository numit `ubris-impact` în contul sau organizația dorită.
2. Încarcă întreg conținutul acestui folder în rădăcina repository-ului. `index.html` trebuie să fie direct în rădăcină, alături de `style.css`, `app.js` și folderul `assets`.
3. Settings → Pages → Source: Deploy from a branch → main → /(root) → Save.
4. În Custom domain introdu `impact.ubris.com` și salvează. Fișierul CNAME singur nu înlocuiește această setare.
5. În GoDaddy → ubris.com → DNS adaugă CNAME, Name: impact, Value: CONTUL-SAU-ORGANIZATIA.github.io. Înlocuiește valoarea cu numele real al proprietarului repository-ului, fără https și fără /ubris-impact.
6. După validarea DNS și emiterea certificatului, activează Enforce HTTPS în GitHub Pages.

Dacă există deja o înregistrare pentru `impact`, verifică destinația înainte de modificare. Nu modifica înregistrările pentru @, www sau email.
Pentru protecția domeniului, urmează verificarea din GitHub account/organization Settings → Pages înainte de configurarea DNS.

## Fișiere
- index.html — pagina
- style.css — design responsive
- app.js — module și self-audit
- assets/ — imagini și PDF original
- CNAME — domeniul dorit
- .nojekyll — publicare statică fără procesare Jekyll

Nu necesită instalare sau build. Răspunsurile self-auditului rămân în memoria paginii; nu sunt trimise unui server. Contactul deschide aplicația de email.

## Conținut
CEO Office și self-auditul sunt concepte propuse, distincte de oferta originală. Drepturile asupra materialelor UBRIS și PDF-ului aparțin titularilor lor; nu este acordată o licență open-source implicită.
