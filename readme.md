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
    { 
        name: 'Kevin', 
        talent: { 
            name: 'Scribe', 
            description: 'even the pen is amazed of me', 
            category: 'lifestyle' 
        }, 
        hasPermanentlySwitchedAccount: false 
    },
    { 
        name: 'Kenza', 
        talent: {
            name: 'Cleanest designs', 
            description: 'come and visit my e-shop my dear, it is beautiful', 
            category: 'design' 
        }, 
        hasPermanentlySwitchedAccount: false 
    },
    { 
        name: 'Liliana', 
        talent: { 
            name: 'Pixel perfect',
            description: 'youtube knows me and I know youtube', 
            category: 'design' 
        }, 
        hasPermanentlySwitchedAccount: true 
    },
    { 
        name: 'Ashley', 
        talent: { 
            name: 'Souls Lover',
            description: '20 times Bloodborne finisher',
            category: 'lifestyle' 
        }, 
        hasPermanentlySwitchedAccount: true 
    },
    { 
        name: 'Claire', 
        talent: { 
            name: 'Startle Hero', 
            description: 'Not only horses can jump', 
            category: 'lifestyle' 
        },
        hasPermanentlySwitchedAccount: false 
    },
    { 
        name: 'Johana', 
        talent: { 
            name: 'Magic hairs', 
            description: 'I am morningly surprised as much as you',
            category: 'design' 
        }, 
        hasPermanentlySwitchedAccount: false
    },
    { 
        name: 'Ayman', 
        talent: { 
            name: 'From Saturn I am alive', 
            description: 'I have sent you a postcard Hello World from Java', 
            category: 'algorithm' 
        }, 
        hasPermanentlySwitchedAccount: false
    },
    { 
        name: 'Martin', 
        talent: { 
            name: 'Potatoes defender', 
            description: 'Nothing more need to be said', 
            category: 'food'
        }, 
        hasPermanentlySwitchedAccount: false
    },
    { 
        name: 'Florian', 
        talent: { 
            name: 'Cookie taster', 
            description: 'You have salt but I will eat you anyway', 
            category: 'food' 
        }, 
        hasPermanentlySwitchedAccount: false 
    },
    { 
        name: 'Gabriel', 
        talent: { 
            name: 'Algo addict', 
            description: 'I am exploring new ways but do not be afraid', 
            category: 'algorithm' 
        }, 
        hasPermanentlySwitchedAccount: false 
    },
    { 
        name: 'Sebastien', 
        talent: { 
            name: 'Terminal Wisdom',
            description: 'MS-DOS crack & talent of the year', 
            category: 'algorithm' 
        }, 
        hasPermanentlySwitchedAccount: false
    },
    { 
        name: 'Mawele',
        talent: { 
            name: 'Senator', 
            description: 'The law is the law and I am not the law but if the law can be, so am I', 
            category: 'lifestyle'
        }, 
        hasPermanentlySwitchedAccount: false 
    }
];
```