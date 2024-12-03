# Exercice : Filtrer les Produits en Stock

Cet exercice vise à travailler la méthode `.filter()` en JavaScript.

## Objectif

Créer une fonction **`filterProductsByStock`** qui retourne un tableau filtré contenant uniquement les produits en stock.

## Instructions

1. Vous avez un tableau d'objets représentant des produits d'un magasin.
2. Chaque produit a les propriétés suivantes :
   - `name` : Le nom du produit (string)
   - `price` : Le prix du produit (number)
   - `inStock` : Un booléen indiquant si le produit est en stock (`true` ou `false`)
3. Écrivez une fonction qui filtre les produits pour ne garder que ceux dont la propriété `inStock` est `true`.

---

## Exemple de données

Voici un exemple du tableau des produits :

```javascript
const products = [
  { name: "Pomme", price: 1.5, inStock: true },
  { name: "Banane", price: 1.0, inStock: false },
  { name: "Cerise", price: 2.5, inStock: true },
  { name: "Ananas", price: 3.0, inStock: false },
  { name: "Orange", price: 1.8, inStock: true }
];
```



# Exercice : Filtrer et Transformer une Liste de Films

Dans cet exercice, vous allez travailler avec `.filter()` et `.map()` pour manipuler une liste d'objets représentant des films.

## Objectif

Créer une fonction **`getTopRatedMovies`** qui :
1. Filtre les films ayant une note (`rating`) supérieure ou égale à 8.
2. Retourne un nouveau tableau contenant uniquement les titres (`title`) des films filtrés.

---

## Exemple de données

Voici un tableau représentant une collection de films :

```javascript
const movies = [
  { title: "Inception", rating: 8.8, year: 2010 },
  { title: "The Dark Knight", rating: 9.0, year: 2008 },
  { title: "Interstellar", rating: 8.6, year: 2014 },
  { title: "Dunkirk", rating: 7.9, year: 2017 },
  { title: "Tenet", rating: 7.5, year: 2020 },
];
```