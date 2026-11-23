# Site personnel d'Adrien Boeuf

Page de présentation professionnelle, bilingue français / anglais, publiée avec GitHub Pages.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | La page complète : contenu, mise en forme (CSS) et sélecteur de langue (JavaScript). Aucune dépendance. |
| `adrien-nb.jpg` | Portrait affiché dans l'en-tête. |
| `.nojekyll` | Demande à GitHub Pages de publier les fichiers tels quels, sans transformation. |
| `CNAME` | (à ajouter une fois le domaine acheté) Nom de domaine personnalisé, par exemple `adrienboeuf.fr`. |

## Modifier le site

1. Ouvrir `index.html` dans un éditeur de texte.
2. Chaque texte existe en deux versions : `<span data-l="fr">…</span>` et `<span data-l="en">…</span>`. Toujours modifier les deux.
3. Vérifier le résultat en ouvrant `index.html` dans un navigateur (double-clic).
4. Enregistrer la modification dans ce dépôt : la mise en ligne est automatique en une à deux minutes.

La notice en tête de `index.html` détaille l'organisation du code (sections, langue, affichage mobile).

## Publication

- Hébergement : GitHub Pages (gratuit), branche `main`, dossier racine.
- Nom de domaine : à relier via le fichier `CNAME` et la configuration DNS chez le registraire (OVHcloud).
- HTTPS : fourni gratuitement par GitHub Pages ; cocher « Enforce HTTPS » dans *Settings › Pages*.
