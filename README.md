# Site personnel — Matthieu Guémann

Site statique autonome. Deux fichiers seulement :

- `index.html` — le site complet (styles, polices, photo et code inclus)
- `CV.pdf` — le CV téléchargé par le bouton « CV » du menu

## Mise en ligne sur GitHub Pages (5 minutes)

### Option A — site à l'adresse `https://<votre-pseudo>.github.io`

1. Sur GitHub, cliquez sur **New repository**.
2. Nommez-le exactement `<votre-pseudo>.github.io` (par ex. `matthieuguemann.github.io`).
   Laissez-le **Public**, ne cochez rien d'autre, puis **Create repository**.
3. Sur la page du dépôt vide, cliquez **uploading an existing file**.
4. Glissez-déposez `index.html` et `CV.pdf`, puis **Commit changes**.
5. Le site est en ligne à `https://<votre-pseudo>.github.io` sous une à deux minutes.

### Option B — site dans un dépôt nommé (par ex. `.../recherche`)

1. Créez un dépôt public, par ex. `site-recherche`.
2. Déposez-y `index.html` et `CV.pdf` de la même façon.
3. Onglet **Settings** → **Pages** (menu de gauche).
4. Sous *Build and deployment* → *Source*, choisissez **Deploy from a branch**,
   branche **main**, dossier **/ (root)**, puis **Save**.
5. L'adresse s'affiche en haut de la page : `https://<votre-pseudo>.github.io/site-recherche`.

## Mettre à jour le site plus tard

- **Changer le CV** : remplacez `CV.pdf` dans le dépôt (même nom de fichier).
- **Changer un texte, ajouter une publication** : demandez-moi la modification ici,
  je régénère `index.html` et vous n'avez plus qu'à le redéposer.

## Nom de domaine personnalisé (optionnel)

Si vous avez un domaine (par ex. `guemann.fr`), ajoutez-le dans
**Settings → Pages → Custom domain**, puis créez chez votre hébergeur un
enregistrement `CNAME` pointant vers `<votre-pseudo>.github.io`.
