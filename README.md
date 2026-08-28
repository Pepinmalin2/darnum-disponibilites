# Disponibilités — Riad Dar Num

Dépôt **public** servant uniquement à publier le calendrier de disponibilités du Riad Dar Num.

## Contenu

- `occupancy.json` — jours occupés par mois. Poussé automatiquement chaque nuit par le dépôt privé `riad-assakina-dashboard`,
  à partir du flux iCal Airbnb fusionné avec les réservations directes.
  Ne contient que des numéros de jour, aucune donnée personnelle.
- `index.html` — calendrier public, intégré au site riaddarnum.com.
  Publié sur https://pepinmalin2.github.io/darnum-disponibilites/
- `_headers` — en-têtes pour un hébergement Cloudflare Pages. Inerte sur GitHub Pages,
  conservé au cas où l'hébergement changerait.

## Règle

⚠️ Ne jamais y copier `direct.json`, `revenus.json`, `analyse.json` ni `darnum.ics` :
ces fichiers contiennent des noms de clients, des montants ou des détails de réservation.
