# Exercice : Filtrer et Organiser les Étudiants

Dans cet exercice, tu vas travailler avec les méthodes `.filter()`. `map()` et/ou `reduce()` pour manipuler une liste d'étudiants et leurs talents (Hé oui, encore hihihi 😌)

## Objectifs

1. Créer une fonction **`getSwitchedStudents`** qui retourne les étudiants ayant déjà switché de compte utilisateur (........)
2. Créer une fonction **`groupStudentsByCategory`** qui retourne les étudiants répartis en groupes selon la catégorie de leur talent (tu peux utiliser l'accumulteur `reduce`)
3. Créer une fonction **`getStudentNamesByCategory`** qui retourne un tableau contenant uniquement les prénoms des étudiants, triés par catégories (tu peux utiliser l'accumulteur `reduce`)


## Données de départ

Voici le jeu de données que tu peux retrouver dans `js/dat.js` 

```javascript
const students = [
    { name: 'Kevin', talent: { name: 'Scribe', category: 'lifestyle' }, hasPermanentlySwitchedAccount: false },
    { name: 'Kenza', talent: { name: 'Cleanest designs', category: 'design' }, hasPermanentlySwitchedAccount: false },
    { name: 'Liliana', talent: { name: 'Pixel perfect', category: 'design' }, hasPermanentlySwitchedAccount: true },
    { name: 'Ashley', talent: { name: 'Souls Lover', category: 'lifestyle' }, hasPermanentlySwitchedAccount: true },
    { name: 'Claire', talent: { name: 'Startle Hero', category: 'lifestyle' }, hasPermanentlySwitchedAccount: false },
    { name: 'Johana', talent: { name: 'Magic hairs', category: 'design' }, hasPermanentlySwitchedAccount: false },
    { name: 'Ayman', talent: { name: 'From Saturn I am alive', category: 'algorithm' }, hasPermanentlySwitchedAccount: false },
    { name: 'Martin', talent: { name: 'Potatoes defender', category: 'food' }, hasPermanentlySwitchedAccount: false },
    { name: 'Florian', talent: { name: 'Cookie taster', category: 'food' }, hasPermanentlySwitchedAccount: false },
    { name: 'Gabriel', talent: { name: 'Algo addict', category: 'algorithm' }, hasPermanentlySwitchedAccount: false },
    { name: 'Sebastien', talent: { name: 'Terminal Wisdom', category: 'algorithm' }, hasPermanentlySwitchedAccount: false },
    { name: 'Mawele', talent: { name: 'Senator', category: 'lifestyle' }, hasPermanentlySwitchedAccount: false }
];