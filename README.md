# Cours pour debutant en javascript
Le but de ce tutoriel est de guider toute personne qui aborde pour la première fois ou toute personne souhaitant développer des compétences en Javascript
# Introduction
## 1. Les fondamentaux en javascript
### 1.1 Les Variables
La plupart du temps, une application JavaScript doit travailler avec des informations. Voici deux exemples :

- Une boutique en ligne – les informations peuvent inclure des produits vendus et un panier.
- Une application de chat - les informations peuvent inclure des utilisateurs, des messages et bien plus encore.
Des variables sont utilisées pour stocker ces informations.

### Une variable
Une variable est un « stockage nommé » pour les données. Nous pouvons utiliser des variables pour stocker des goodies, des visiteurs et d'autres données.

Pour créer une variable en JavaScript, utilisez le letmot - clé.

L'instruction ci-dessous crée (en d'autres termes : déclare ) une variable avec le nom « message » :

```javascript
    let message;
```
Maintenant, nous pouvons y mettre des données en utilisant l'opérateur d'affectation égale(**=**)

```javascript
    let message;

    message = 'Hello';
```
La chaîne est maintenant enregistrée dans la zone mémoire associée à la variable. Nous pouvons y accéder en utilisant le nom de la variable :

```javascript
    let message;
    message = 'Hello';

    alert(message);
```

Pour être concis, nous pouvons combiner la déclaration et l'affectation de la variable en une seule ligne :

```javascript
    let message = 'Hello';

    alert(message);
```

Nous pouvons également déclarer plusieurs variables sur une seule ligne :

```javascript
    let user = 'John', age = 25, message = 'Hello';
```

### 1.1 Les conditions
