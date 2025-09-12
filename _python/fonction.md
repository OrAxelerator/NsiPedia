---
title: cours fonction
layout: default
---

# 🐍 - Python  

## **La Spécification de fonction**

La **spécification de fonction** en Python permet d’ajouter une description directement dans la fonction.

* Dans VS Code, cela permet d’afficher automatiquement cette description lorsque vous tapez le nom de la fonction.

* Ceci améliore la **compréhension** du code pour tous ceux qui le lisent.

### *exemple :*

```python
def reduc(prix, taux):
    """
    in: prix: un prix, taux: un taux de reduction en % (30 pour 30% par ex)
    out: le prix après réduction
    """
    return prix * (1 - taux / 100)
```
---

[⬅ Retour à la page Python](NsiPedia/python/nav)

