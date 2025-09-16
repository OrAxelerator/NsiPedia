---
title: La fonction input()
layout: default
---

# 🐍 - Python  

## **La fonction input()**

La **fonction input()** en Python permet à l'utilisateur de **rentrer** du texte depuis le terminal et de l'enregistrer (taper **entrée** pour valider).

### *exemple :*

```python
nom = input("Quel est ton nom ? ")
print("salut " + nom + " !")
```

Ce programme attend la réponse de l'utilisateur avant de continuer, puis il va afficher le nom que l"utilisateur a rempli.

---

La fonction input() renvoie toujours une chaîne de caractères (string). Donc, si on veut récupérer un âge pour calculer une date de naissance par exemple, il faut transformer l'entrée en nombre (int).

### *exemple :*

```python
annee = 2025
age = int(input("Quel est ton âge ? "))
print("tu es né en ", (annee - age))
```
Le programme récupère bien l'âge de l'utilisateur et calcule sa date de naissance.
(La fonction int() transforme ce qu'elle a entre parenthèses en nombre)