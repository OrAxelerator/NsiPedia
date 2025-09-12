# NsiPédia

### Qu'est ce que c'est ?
Un moyen de publier les cours en .md et que tout le monde puisse modifier.

### Comment ça marche ?

 Arborescence du projet : 

```text
.
├── _config.yml             # configure Jekyll et définit le thème du site
│
├── _python/                # collection Python
│   ├── nav.md              # page d'accueil de la collection Python
│   ├── fonction.md
│   └── concaténation.md
│
├── index.md                # page d'accueil 
├── README.md
````
Le "_" indique à Jekyll que le dossier ou fichier est spécial et doit être traité pour le site.

### Comment créer un article ?

* créer un fichier .md 
* Tout fichier doit commencer par ce qu’on appelle un front matter.
C’est une zone d’informations entre --- qui permet à Jekyll de savoir comment afficher la page.

```yaml
---
title: "nom de la page"
layout: default
---
```


### Accéder à la page d'accueil.

Vous pouvez accéder à la page d'accueil du site ici :  
https://oraxelerator.github.io/NsiPedia/
