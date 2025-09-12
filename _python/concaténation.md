---
title: cours concatenation
layout: default
---

# 🐍 - Python  

## **La concaténation en python**

 **La concaténation** en Python permet d’additioner 2 chaines de caractères (string)

### *exemple :*

```python
a = "ordi"
b = "nateur"
mot = a + b
print(mot)
```

***sortie :***

```
ordinateur
```

L'expression ```print(a + b)``` marche aussi et est plus courte et simple 

### voici un exemple en fonction : 

```python
def pluriel(mot):
    return mot + "s"
```
***sortie :***

```python
>>> pluriel("voiture")
voitures    
>>> pluriel("cheval")
chevals
```
---

## 🚀 Explorez davantage …

On peut aller plus loin avec les chaines de caractères (string). Exemple :

* On peut les multiplier :

```python
>>> print("ha" * 3)
hahaha
```

* MAIS on ne peut pas  **additioner** et **diviser** avec tout nombre ℝ (int/float ..)

```python
>>> print("ha" + 3)
TypeError: can only concatenate str (not "int") to str
>>> print("ha" / 3)
TypeError: can only concatenate str (not "int") to str
```

---

[⬅ Retour à la page Python](/python/nav)