# THE NIGHT SHIFT PLANNING

Application iPhone installable pour gérer un planning de nuit, les heures, les repos et les congés.

## Fonctions incluses

- Horloge avec secondes et date complète
- Planning mensuel : nuits, remplacements, repos, congés et formations
- Compte à rebours avant le prochain service
- Export vers Calendrier iPhone au format `.ics`
- Génération automatique des mois suivants jusqu'à décembre à partir d'un mois modèle
- Conservation des ajouts manuels lors d'une nouvelle génération
- Suivi des congés acquis, utilisés et restants
- Installation sur l'écran d'accueil de l'iPhone
- Fonctionnement hors ligne après la première ouverture

## Publication avec GitHub Pages

1. Créez un nouveau dépôt sur GitHub.
2. Ajoutez **tous les fichiers de ce dossier à la racine du dépôt**. `index.html` doit rester à la racine.
3. Ouvrez **Settings → Pages** dans le dépôt.
4. Dans **Build and deployment**, choisissez **Deploy from a branch**.
5. Sélectionnez la branche **main**, le dossier **/(root)**, puis cliquez sur **Save**.
6. GitHub affichera l'adresse publique de l'application après la publication.

## Installation sur iPhone

1. Ouvrez l'adresse GitHub Pages dans Safari.
2. Touchez le bouton **Partager**.
3. Choisissez **Sur l'écran d'accueil**.
4. Validez avec **Ajouter**.

Les données sont enregistrées localement sur l'iPhone dans Safari. Elles ne sont pas envoyées sur un serveur.

## Mise à jour

Remplacez les fichiers du dépôt par la nouvelle version. Le service worker `v2` efface automatiquement l'ancien cache lors du prochain chargement.
