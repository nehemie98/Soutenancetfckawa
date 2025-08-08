# Affiche Défense de Projet

[![Prévisualisation](preview.jpg)](https://nehemie98.github.io/soutenancetfckawa/)

## Comment visualiser l'affiche

1. Cliquez sur le lien ci-dessus
2. Ou téléchargez et ouvrez le fichier `index.html`

## Personnalisation

Remplacez l'image dans `index.html` par votre photo :
```html
<img src="votre-photo.jpg" alt="Votre Nom">


## Pourquoi ça n'a pas fonctionné ?

1. **Markdown ≠ HTML** : GitHub affiche les README.md en Markdown, pas comme une page web
2. **Sécurité** : GitHub ne permet pas d'exécuter du JavaScript ou d'afficher du HTML complet dans les README
3. **Solution** : Utilisez GitHub Pages pour héberger l'HTML

## Étapes Correctes :

1. Créez un nouveau dépôt sur GitHub
2. Ajoutez deux fichiers :
   - `index.html` (votre code complet)
   - `README.md` (description)
3. Activez GitHub Pages :
   - Settings > Pages > Source: main branch
4. Attendez 1-2 minutes
5. Votre affiche sera visible à :
   `https://votre-utilisateur.github.io/votre-repo/`

## Alternative si vous voulez tout dans le README

Si vous insistez pour tout mettre dans le README (mais avec des limitations) :

````markdown
```html
<!-- Votre code HTML complet ici -->


Mais cela ne montrera qu'un aperçu statique du code, pas le rendu visuel. La première méthode est bien meilleure.
