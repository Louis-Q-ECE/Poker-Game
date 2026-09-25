# Spin Poker

Un jeu de poker Spin & Go solo contre des bots, jouable directement dans le navigateur — aucun serveur, aucune installation, un seul fichier HTML autonome.

## Jouer

Une fois ce dépôt publié avec **GitHub Pages** (voir plus bas), le jeu est accessible à cette adresse :

```
https://TON-PSEUDO.github.io/NOM-DU-DEPOT/
```

Remplace `TON-PSEUDO` et `NOM-DU-DEPOT` par les tiens.

### Installer l'icône sur ton téléphone (recommandé)

1. Ouvre l'adresse ci-dessus dans **Safari** (iPhone) ou **Chrome** (Android).
2. Appuie sur le bouton Partager, puis **« Sur l'écran d'accueil »**.
3. Lance toujours le jeu depuis cette icône plutôt que depuis un onglet du navigateur : ta progression (jetons, écurie, ligue…) est sauvegardée localement sur l'appareil, et les apps ajoutées à l'écran d'accueil sont protégées de l'effacement automatique des données que Safari applique aux onglets normaux après quelques jours d'inactivité.

## Activer GitHub Pages

1. Dans ce dépôt, va dans **Settings → Pages**.
2. Sous « Build and deployment », choisis la branche `main` et le dossier `/ (root)`.
3. Enregistre. L'adresse du jeu apparaît en haut de cette page après une minute environ.

## Mettre à jour le jeu

Pour publier une nouvelle version, remplace simplement le fichier `index.html` de ce dépôt par la nouvelle version (bouton crayon « Edit » ou glisser-déposer via « Add file → Upload files »), puis valide (« Commit »). GitHub Pages republie automatiquement.

## Technique

- Fichier unique (`index.html`), HTML/CSS/JS, aucune dépendance externe hors polices Google Fonts.
- Sauvegarde de la progression via `localStorage` du navigateur — propre à chaque appareil/navigateur, non synchronisée entre appareils.
- Aucune donnée envoyée à un serveur : tout tourne localement dans le navigateur.
