# Disponibilités — Riad Dar Num

Dépôt **public** servant uniquement à publier le calendrier de disponibilités du Riad Dar Num.

## Contenu

- `occupancy.json` — jours occupés par mois. Généré par le dépôt privé `riad-assakina-dashboard`,
  à partir du flux iCal Airbnb fusionné avec les réservations directes.
  Ne contient que des numéros de jour, aucune donnée personnelle.
- `index.html` — calendrier public, intégré au site riaddarnum.com.
- `_headers` — en-têtes Cloudflare Pages (CORS, cache).

## Règle

⚠️ Ne jamais y copier `direct.json`, `revenus.json`, `analyse.json` ni `darnum.ics` :
ces fichiers contiennent des noms de clients, des montants ou des détails de réservation.
