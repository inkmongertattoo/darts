DartScore - version PWA corrigée

À mettre dans le dossier /darts/ de GitHub Pages :
- dartscore.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

Après publication :
1. Ouvre https://inkmongertattoo.github.io/darts/dartscore.html
2. Dans Chrome Android : menu ⋮ > Paramètres du site > Supprimer les données du site si besoin.
3. Recharge la page.
4. Menu ⋮ > Installer l'application.

Corrections effectuées :
- Manifest externe au lieu d'un data: URL.
- Icônes PNG externes au lieu d'icônes SVG base64 intégrées.
- Service worker externe ./sw.js au lieu d'un service worker Blob/ObjectURL.
- start_url fixé sur ./dartscore.html et scope sur ./.
