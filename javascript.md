# JavaScript

## Sommaire

* [Prérequis](#prerequis)
0. [Ch.0 - Le langage JavaScript](#ch0---le-langage-javascript)
1. [Ch.1 - Grammaire et types](#ch1---grammaire-et-types)
2. [Ch.2 - Expressions et opérateurs](#ch2---expressions-et-opérateurs)
3. [Ch.3 - Traitements des données numériques](#ch3---traitements-des-données-numériques)
4. [Ch.4 - Traitements des données textes](#ch4---traitements-des-données-textes)
5. [Ch.5 - Structures conditionnelles](#ch5---structures-conditionnelles)
6. [Ch.6 - Structures itératives](#ch6---structures-itératives)
7. [Ch.7 - Fonctions](#ch7---fonctions)
8. [Ch.8 - Collections indexées](#ch8---collections-indexées)
9. [Ch.9 - Collections référencées](#ch9---collections-référencées)
10. [Ch.10 - Collections propriétaires](#ch10---collections-propriétaires)
11. [Ch.11 - Modèle objet orienté prototypes](#ch11---modèle-objet-oriente-prototypes)
12. [Ch.12 - Modèle objet orienté classes](#ch12---modèle-objet-oriente-classes)
13. [Ch.13 - Gestion des erreurs](#ch13---gestion-des-erreurs)
14. [Ch.14 - Promesses](#ch14---promesses)
15. [Ch.15 - Expressions rationnelles](#ch15---expressions-rationnelles)
16. [Ch.16 - Itérateurs et générateurs](#ch16---itérateurs-et-générateurs)
17. [Ch.17 - Modules](#ch17---modules)
18. [Ch.18 - Connaissance complémentaire](#ch18---connaissance-complementaire)

---

## Prérequis

- [Fondamentaux informatiques](/fondamentaux-informatiques.md)
- [Algorithmique](/algorithmique.md)
- Première expérience avec JavaScript
- Première approche de l'orienté objet

---

## Ch.0 - **Le langage JavaScript**

### 0.0 :: Description
- Historique : Brendan Eich et Netscape
- ECMAScript : Spécification ECMA-262
- Utilisation : Scripts embarqués
- Évolution : Modules

### 0.1 :: Technologie
- Architecture
- Côté client
- Côté serveur

---

## Ch.1 - **Grammaire et types**

### 1.0 :: Syntaxe
- Instruction (_Statement_)
- Commentaires

### 1.1 :: Déclaration
- Variables
- Constantes
- Évaluations `let`, `const`, `var` et sans instruction
- Portée : Contexte global ou local (_Scope_)
- Remontée (_Hoisting_)

### 1.2 :: Types de données
- Types primitifs
- Types par référence (_Objects_)
- Conversions implicites et explicites (_Cast_)
- Données structurées

### 1.3 :: Littéraux
- Chaines de caractères
- Numériques entiers
- Numériques réels
- Booléen
- Tableau
- Objets
- Expressions rationnelles

### 1.3 :: Mode strict
- Principes
- Distinction du mode classique
- Avantages

---

## Ch.2 - **Expressions et opérateurs**

### 2.0 :: Opérateurs
- Principes
- Affectation
- Arithmétiques : résultats numériques
- Comparaisons : résultat booléens
- Logiques : opérandes et résultat booléens
- Binaires : opérandes binaires (32bits)
- Chaines de caractères
- Ternaire : test conditionnel
- Virgule
- Unaires : instructions `delete`, `typeof` et `void`
- Relationnels : appartenance `in` et `instanceof`
- Précédence des opérateurs

###  2.1 :: Expressions
- Primaires : `this`, `()`
- Vers la gauche : `new`, `super`, `...` 

---

## Ch.3 - **Traitements des données numériques**

### 3.0 :: Nombres
- Format IEEE-754
- Valeurs spéciales : symbolique _+Infinity_, _-Infinity_ et _NaN_
- Nombres entiers et décimaux
- Nombres binaires
- Nombres octaux
- Nombres hexadécimaux
- Nombres scientifiques

### 3.1 :: Objet Number
- Propriétés : constantes de valeurs
- Méthodes : résolutions de nombres
- Prototype : formatage de nombre
- Transversalité avec littéraux et variables

### 3.2 :: Objet Math
- Propriétés statiques : constantes mathématiques
- Méthodes statiques : fonctions mathématiques

### 3.3 :: Objet Date
- Principe
- Propriétés
- Méthodes : manipulation
- Transversalité avec littéraux et variables

---

## Ch.4 - **Traitements des données textes**

### 4.0 :: Chaines de caractères
- Littéraux de chaines
- Littéraux de modèles

### 4.1 :: Objet String
- Propriétés
- Méthodes

### 4.2 :: Format internationaux
- Objet Intl : API d'internationalisation ES
- Date et heure : `DateTimeFormat`
- Nombres : `NumberFormat`
- Ordonnancement : `Collator`

---

## Ch.5 - **Structures conditionnelles**
	
### 5.0 :: Blocs
- Une ou plusieurs instructions
- Nouvelle portée

### 5.1 :: Instruction `if...else...`
- Construction
- Valeurs fausses en contexte booléen

### 5.2 :: Instruction `switch`
- Construction
- Instructions `break` et `default`

---

## Ch.6 - **Structures itératives**

### 6.0 :: Instruction `for`
- Construction
- Expressions initiale, conditionnelle, instructionnelle et multiples

### 6.1 :: Instruction `do...while`
- Construction
- Condition de sortie

### 6.2 :: Instruction `while`
- Construction
- Condition de sortie

### 6.3 :: Instruction `for...in`
- Construction
- Propriétés énumérables d'un objet

### 6.4 :: Instruction `for...of`
- Construction
- Valeurs d'un itérable

### 6.5 :: Instructions spéciales
- Étiquette : `label`
- Interruption : `break`
- Poursuivre : `continue`

---

## Ch.7 - **Fonctions**

### 7.0 :: Déclarations
- Avec ou sans `return`
- Par instruction
- Par expression
- Portée (_Scope_)
- Appels

### 7.1 :: Paramètres
- Valeurs et références
- Par défaut (ES6)
- Objet arguments
- Reste (ES6)

### 7.2 :: Imbrications, Accès et Piles
- Récursivité par nom
- Récursivité par référence de portée
- Principe de la Pile
- Imbrication

### 7.3 :: Fléchées
- Syntaxe
- `this` non-distinct

### 7.4 :: Techniques spécifiques
- Le rappel (_Callback_)
- L'auto-invocation (_Self-Invoked_)

### 7.5 :: Fermetures
- Portée (_Scope_) et environnement lexical
- Principe de fermetures
- Modèles et méthodes privées
- Performances

### 7.6 :: Fonctions natives
- Distinctions avec les méthodes d'objets
- Classement et utilités

---

## Ch.8 - **Collections indexées**

### 8.0 :: Le type Tableau (_Array_)
- Construction : `new Array()`, `Array.of` et `[]`
- Valeurs et accès
- Parcourir
- Méthodes et l'objet _Array_
- Manipulations
- Objets similaires et distinction

### 8.1 :: Tableaux typés
- Vues et tampons de mémoire (`ArrayBuffers` et `DataView`)
- `Int8Array` et `Uint8Array`
- `Int18Array` et `Uint16Array`
- `Int32Array` et `Uint32Array`
- `BigInt64Array` et `BigUint64Array`
- `Float32Array` et `Float64Array`

---

## Ch.9 - **Collections référencées**

### 9.0 :: Le type Dictionnaire (API _Map_)
- _Map_
- _WeakMap_ : clés non énumérables
- Distinction avec _Object_

### 9.1 :: Le type Ensemble de valeurs uniques (API _Set_)
- _Set_
- _WeakSet_ : valeurs non énumérables
- Distinction avec _Array_

---

## Ch.10 - **Collections propriétaires**

### 10.0 :: Le type Objet (_Object_)
- Construction : `new Object()` et `{}`
- Propriétés, valeurs et accès
- Parcourir
- Méthodes et l'objet Object
- Manipulation
- Accesseurs et Mutateurs

### 10.1 :: Fonction constructrice
- Création de modèles
- `this` et le contexte de l'instance
- Principe prototype
- Définition Méthodes

---

## Ch.11 - **Modèle objet orienté prototypes**

### 11.0 :: Distinctions 'prototype' et 'classe'
- Principe du prototypage en JavaScript
- Définition de modèle
- Héritage et chainage de prototype
- Exploitation de propriétés

### 11.1 :: Prototypage
- Modèle
- Instance
- Propriétés
- Methodes

### 11.2 :: Héritage
- Principe
- Surcharge
- Polymorphisme

---

## Ch.12 - **Modèle objet orienté classes**

### 12.0 :: Composition d'une classes
- Constructeurs
- Propriétés
- Méthodes

### 12.1 :: Accessibilité
- Statisme : `static`
- Public et privé
- Encapsulation
- Héritage : `extends`
- Abstraction
- Polymorphisme
- Espace de noms

### 12.2 :: Les principes _SOLID_
- Définition
- Responsabilité unique
- Ouverture et fermeture
- Substitution Liskov
- Ségrégation d'interfaces
- Inversion des dépendances

---

## Ch.13 - **Gestion d'erreurs**

### 13.0 :: Identification et interceptions
- Types d'erreurs
- Lever une exception : `throw`
- Attraper une exception : `try...catch...finally`
- Objet _Error_
- Exceptions utilisateur

---

## **Ch.14 - Promesses**

### 14.0 :: Distinction des callbacks
- Structure classique
- Gestion d'erreurs
- Pyramide de l'enfer
- Code spaghetti

### 14.1 :: Principe des promesses
- Objet `Promise` : _resolve_, _reject_, _states_ et _result_
- Consommation : `.then`, `.catch`, `.finally`
- Chainage de promesses
- Propagation d'erreur
- Composition complète : `.all`, `.allSettled`, `.race`, `.any`, `.resolve`, `.reject`
- Instructions`async` et `await`

---

## Ch.15 - **Expressions rationnelles**

---

## Ch.16 - **Itérateurs et générateurs**

---

## Ch.17 - **Modules**

### 17.0 :: Distinctions des scripts classiques
- Description, importer et exporter
- Fonctionnement général
- Standardisation et environnements
- Outils de construction (_Webpack_)

### 17.1 :: Principe et structure
- Importer et Exporter : `import`, `export`
- Alias et nommage : `as`
- Par défaut : `default`

### 17.2 :: Application
- Agrégat de modules et re-export : `export...from...`
- Imports dynamiques : `import()`

---

## Ch.18 - **Connaissance complémentaire**

### 18.0 :: Métapogrammation

### 18.1 :: Programmation fonctionnelle

### 18.2 :: Architecture MVC
