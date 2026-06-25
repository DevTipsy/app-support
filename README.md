# App Support

Page d'assistance centralisée pour les applications de Thibault Sanclemente.

🔗 **Page en ligne :** https://VOTRE-COMPTE.github.io/app-support/

## Ajouter une application

1. Placez le logo (PNG carré, idéalement 120×120 px) dans le dossier `logos/`.
2. Dans `index.html`, dupliquez un bloc `<div class="app-card">` et renseignez :
   - `data-app` : le nom de l'app (utilisé dans l'objet du mail)
   - `src` : le chemin du logo (ex. `logos/monapp.png`)
   - le `<h2>` (nom affiché) et le `<p>` (description courte)

Le bouton « Envoyer un email » est généré automatiquement et pré-remplit
l'objet et le corps du mail avec le nom de l'app concernée.

## Email de contact

Adresse définie dans la constante `SUPPORT_EMAIL` en bas de `index.html`.
