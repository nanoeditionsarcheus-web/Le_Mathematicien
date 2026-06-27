# Le_Mathematicien
Site de téléchargement du récit Le Mathématicien Complètement Dans les Patates
Vitrine — Les Nano-Éditions d'Archéus

Site statique, un seul fichier autonome (`index.html`, CSS inclus, polices via Google Fonts). Pensé pour GitHub Pages.

## Arborescence proposée

    nano-editions-archeus/              ← dépôt dédié à la vitrine (séparé du dépôt de production interne, si vous en avez un)
    ├── index.html                      ← la page d'accueil (livrée ici)
    ├── README.md                       ← ce fichier
    └── assets/                         ← à créer quand les vraies photos seront prêtes
        └── img/
            ├── couverture.jpg          ← photo du livre
            ├── tranche-foret.jpg       ← macro de la toile Vert Forêt
            └── tranche-roseval.jpg     ← macro de la toile Rouge Vin

Pour l'instant, `index.html` n'a besoin d'aucune image : la signature visuelle (la patate lumineuse) et les pastilles de couleur des toiles sont en CSS pur. Quand les photos seront prêtes, elles peuvent remplacer les blocs `.carte-edition-toile` dans le CSS, ou s'ajouter en `<img>` dans les cartes correspondantes.

## Activer GitHub Pages

1. Créez un dépôt (public) — par exemple `nano-editions-archeus`.
2. Déposez `index.html` à la racine du dépôt (branche `main`).
3. Dans le dépôt : **Settings → Pages → Build and deployment → Source : Deploy from a branch**, puis choisissez `main` / `(root)`.
4. GitHub donne une URL du type `https://VOTRE-USERNAME.github.io/nano-editions-archeus/`.

## Releases (PDF / EPUB gratuits)

Les fichiers numériques restent séparés du site — ils vivent dans l'onglet **Releases** du même dépôt (ou d'un dépôt dédié à la production, selon votre préférence) :

1. **Releases → Draft a new release**
2. Joindre le PDF et l'EPUB comme fichiers de la release
3. Publier — GitHub compte automatiquement les téléchargements de chaque fichier

Dans `index.html`, les deux boutons de téléchargement pointent vers :

    https://github.com/VOTRE-USERNAME/VOTRE-REPO/releases/latest

→ à remplacer par votre vrai nom d'utilisateur et de dépôt une fois la première release publiée.

## À compléter dans index.html

Un seul endroit reste marqué dans le fichier :

* Les deux liens de téléchargement (`VOTRE-USERNAME/VOTRE-REPO`)

Les ISBN (papier, PDF, EPUB) sont déjà confirmés dans la fiche technique. Le reste — palette, typographie, structure des sections — est prêt à l'emploi.
