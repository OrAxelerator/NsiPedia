---
title: Le Module Random
layout: default
---

# 🐍 - Python  

## **Le module random**

**Qu'est-ce qu'un module ?**

* Un module est un programme contenant des fonctions, des variables et des classes, que l’on peut réutiliser.  
Le module `random` est utilisé pour simuler de l'aléatoire dans un programme.

---

Pour pouvoir utiliser toutes les fonctions du module `random`, il faut d'abord taper `import random` au tout début du fichier.

Le module `random` possède plusieurs fonctions comme :  

| Fonction  | Description                        |
|-----------|------------------------------------|
| `random.random()`      | Retourne un nombre flottant aléatoire entre `0.0` et `1.0`. |
| `random.randint(a, b)` | Génère un entier aléatoire **inclus** entre `a` et `b`. |
| `random.choice(sequence)` | Choisit un élément au hasard dans une séquence : `liste`, `tuple`, `chaînes de caractères`. |
| `random.sample(population, k)` | Choisit `k` éléments dans `population` et ne peut pas prendre deux fois le même élément. |
| `random.shuffle(x)`      | Mélange la séquence `x` de manière aléatoire. |

Devant chaque fonction, on ajoute `random.` pour que Python puisse retrouver la fonction.

Il existe encore plein d'autre fonction mais qui sont utiles que dans certain cas particulier ..

---

[⬅ Retour à la page Python](/NsiPedia/python/nav)
