# Planning Cours — Seyda Zeynab Academy

Application web (une seule page) pour gérer le planning hebdomadaire des cours en ligne : créneaux par jour, calcul automatique des durées, alerte en cas de chevauchement, résumé hebdomadaire.

## Utilisation

Ouvre simplement `index.html` dans un navigateur. Pas d'installation, pas de serveur requis.

- **✏️ Activer la modification** : édite les horaires, les noms, ajoute ou supprime des créneaux.
- **⬇️ Exporter / ⬆️ Importer** : les données sont sauvegardées uniquement sur l'appareil utilisé. Exporte un fichier de sauvegarde pour le transférer (WhatsApp, email...) et l'importer sur un autre téléphone.
- **🗑 Réinitialiser** : remet le planning par défaut.

## Mettre l'application en ligne (accessible avec un lien, depuis n'importe quel appareil)

### Option 1 — GitHub Pages (gratuit, avec ce dépôt)
1. Crée un nouveau dépôt sur [github.com/new](https://github.com/new).
2. Pousse ce dossier dedans :
   ```
   git remote add origin <URL_DE_TON_DEPOT>
   git branch -M main
   git push -u origin main
   ```
3. Dans le dépôt GitHub : **Settings → Pages → Branch: main → /(root) → Save**.
4. L'application sera accessible à `https://<ton-nom-utilisateur>.github.io/<nom-du-depot>/` après quelques minutes.

### Option 2 — Netlify Drop (le plus simple, sans ligne de commande)
1. Va sur [app.netlify.com/drop](https://app.netlify.com/drop).
2. Glisse-dépose ce dossier (ou juste `index.html`).
3. Un lien public est généré immédiatement.

## Important à savoir

Comme il n'y a pas de serveur ni de base de données, chaque appareil garde sa propre sauvegarde locale (dans le navigateur). Si tu modifies le planning sur ton téléphone, ces changements ne se voient pas automatiquement sur un ordinateur — utilise Exporter/Importer pour transférer les données, ou dis-le-moi si tu veux qu'on ajoute une vraie synchronisation en ligne entre appareils (ça demande un petit service de stockage en plus).
