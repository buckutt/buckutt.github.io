# buckutt.github.io

Le blog fonctionne grâce à [Github Pages](https://pages.github.com), le générateur
de sites statiques [Jekyll](https://github.com/jekyll/jekyll) et le dépôt de
démarrage proposé par [Jekyll Now](https://github.com/barryclark/jekyll-now/).

Il n'y a pas eu de modification spéciale par rapport au dépôt de base, à part :

* Ajout d'un champ « author » dans l'en-tête des articles.
* Traduction du template.
* Changement de la page 404.

## Utilisation

**J'ai rapidement traduit la documentation de Jekyll Now, s'y référer directement
s'il manque trop de choses ici !**

### Publication d'un post

Le format retenu est Markdown, on peut trouver [des documents d'aide](http://www.jekyllnow.com/Markdown-Style-Guide/) sur celui-ci si besoin

Il est possible d'ajouter des articles directement de puis Github. Il suffit
de créer un fichier dans le dossier `/_posts/` grâce au petit bouton `+` en haut
à gauche. Le format du nom de fichier doit respecter la convention suivante :
`year-month-day-title.md`, et son contenu doit faire figurer l'en-tête spécifique
aux posts pour Jekyll :

```
---
layout: post
title: ...
author: ...
---

...
```

### Développement en local

1. Une `gem` a été créée, avec `jekyll` et les plugins nécessaires à Jekyll Now.
Pour lancer l'installation, `gem install github-pages`.
2. Il faut ensuite cloner le dépôt correspondant au blog:
`git clone https://github.com/buckutt/buckutt.github.io.git`
3. On peut alors demander à Jekyll de générer le site, le servir et de surveiller
les modifications avec `jekyll serve` (site disponible à `http://127.0.0.1:4000`).
4. Effectuer les modifications, les commmit et les push sur la branche `master`.
Github se chargera du reste !

## Moar!

[Une documentation avancée a été écrite par l'auteur de Jekyll Now pour unsite.](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/)
