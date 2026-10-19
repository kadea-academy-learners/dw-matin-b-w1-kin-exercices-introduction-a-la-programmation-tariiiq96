# RECHERCHES — Semaine 13

> Pour chaque exercice : reformule avec tes mots (pas de copier-coller), ajoute un test que tu as exécuté toi-même,
> et cite une source précise (une page, pas juste « Google »). MDN en français est la référence.
> Si tu as utilisé une IA, indique ton prompt et vérifie sa réponse sur MDN.
> Ne modifie pas les titres `## F1 — …` : ils servent à l'évaluation automatique.

## F1 — Ma carte d'apprenant

**Question :** Pourquoi typeof null renvoie-t-il 'object' alors que null n'est pas un objet ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F2 — Le convertisseur de saisie

**Question :** Qu'est-ce que NaN, et pourquoi NaN === NaN renvoie false ? Quelle fonction utiliser pour le détecter ?

//NaN signifie Not a Number (pas un nombre ). .

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

//NaN En JavaScript, il représente un résultat numérique invalide.
Pourquoi NaN === NaN renvoie false ?
Parce que JavaScript considère que NaN n’est égal à aucune valeur, même pas à lui-même.


...

**Mon test dans la console :**

```js
console.log(Number.isNaN(NaN));     // 

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F3 — Pair ou impair : le tirage des tickets

**Question :** Que renvoie -7 % 2 ? Déduis-en pourquoi il vaut mieux tester % 2 !== 0 plutôt que % 2 === 1 pour détecter un nombre impair.

Que renvoie -7 % 2 ?

En JavaScript, -7 % 2 renvoie -1, car le reste conserve le signe du nombre de départ.



**Ma réponse (avec mes mots, 3 à 5 lignes) :**

Pour détecter un nombre impair, il vaut mieux utiliser nombre % 2 !== 0 plutôt que nombre % 2 === 1.

En effet, un nombre impair négatif, comme -7, donne un reste de -1 et non de 1. La condition nombre % 2 !== 0 fonctionne donc pour les nombres impairs positifs et négatifs.

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F4 — Le contrôleur du bus

**Question :** Peut-on enchaîner plusieurs ternaires ? Pourquoi est-ce souvent déconseillé ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

Oui, on peut enchaîner plusieurs opérateurs ternaires en JavaScript. Cependant, cela rend souvent le code difficile à lire et à comprendre.

Pour plusieurs conditions, il est généralement préférable d'utiliser `if / else if / else`, car le code est plus clair et plus facile à maintenir.


**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```Statut : mineur — Tarif : 500 FC

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F5 — Ma première fonction fléchée

**Question :** Quand peut-on enlever les parenthèses autour des paramètres, et quand peut-on enlever return et les accolades ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**



- **Parenthèses :** on peut les enlever lorsqu'une fonction fléchée possède un seul paramètre. Exemple : `prenom => ...`. Avec zéro ou plusieurs paramètres, elles sont nécessaires.
- **`return` et accolades :** on peut les enlever lorsque la fonction contient une seule expression à retourner. Exemple : `const carre = n => n * n;`.
- Si la fonction contient plusieurs instructions, il faut conserver les accolades et utiliser `return` explicitement si l'on veut renvoyer une valeur.



...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```
Mbote Lys !
49

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## F6 — Le compte à rebours

**Question :** À quoi sert le mot-clé continue ? Quelle différence avec break ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**



- continue` : saute l'itération actuelle et passe à la suivante, sans arrêter la boucle.
- `break` : arrête complètement la boucle immédiatement.

Exemple : dans un compte à rebours, `continue` permet de sauter le nombre 5 tout en continuant jusqu'à 1, tandis que `break` arrête le compte à rebours dès que le nombre 5 est atteint.




...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M1 — FizzBuzz kinois

**Question :** Pourquoi FizzBuzz est-il célèbre dans les entretiens d'embauche de développeurs ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...


FizzBuzz est un exercice classique qui permet de vérifier les bases de la programmation : les boucles, les conditions et l'opérateur modulo `%`.

Il permet aussi d'évaluer la logique du candidat, sa capacité à respecter l'ordre des conditions et à produire un code simple et correct. Malgré sa simplicité, il révèle si une personne maîtrise les fondamentaux de la programmation.



**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```






**IA utilisée ? (prompt + vérification sur MDN) :** non

## M2 — Le distributeur automatique (DAB)

**Question :** Comment afficher 75000 sous la forme 75 000 avec toLocaleString() ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**




La méthode `toLocaleString()` permet de formater un nombre selon les conventions d'une langue ou d'une région.

Exemple :

```javascript
const montant = 75000;

console.log(montant.toLocaleString("fr-FR"));
// Résultat : 75 000
```

Pour afficher le solde dans la fonction, on peut écrire :

```javascript
return `Retrait accepté. Nouveau solde : ${(solde - montant).toLocaleString("fr-FR")} FC`;
```
...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M3 — Le détecteur de champs vides (Truthy / Falsy)

**Question :** Quelle est la liste complète des valeurs falsy en JavaScript ? (Indice : il y en a plus que dans cet exercice.)

**Ma réponse (avec mes mots, 3 à 5 lignes) :**



Les valeurs falsy sont les valeurs considérées comme fausses dans une condition.

La liste complète comprend :

- `false`
- `0`
- `-0`
- `0n` (BigInt zéro)
- `""` (chaîne vide)
- `null`
- `undefined`
- `NaN`

En JavaScript, `document.all` constitue également un cas particulier historique considéré comme falsy dans les navigateurs.

Toutes les autres valeurs sont généralement truthy, notamment `" "`, `"0"`, `[]` et `{}`.

**Attention :** pour un formulaire, un champ contenant uniquement des espaces peut sembler rempli. On peut utiliser `valeur.trim()` pour vérifier si une chaîne ne contient que des espaces.






...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M4 — Le score par défaut : || contre ??

**Question :** Que fait l'opérateur ?? (coalescence des nuls) et en quoi est-il différent de || ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**




L'opérateur `??`, appelé coalescence des nuls, renvoie la valeur située à droite uniquement si celle de gauche est `null` ou `undefined`.

Contrairement à `||`, il conserve les valeurs falsy valides comme `0`, `false` et `''`.

Exemple :

```javascript
console.log(0 || 'aucun'); // aucun
console.log(0 ?? 'aucun'); // 0
```

On privilégie `??` lorsqu'on veut fournir une valeur par défaut uniquement si la donnée est absente (`null` ou `undefined`).









...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M5 — La vitre teintée (portée de bloc)

**Question :** Pourquoi var est-il banni du code moderne ? Cherche ce que sont la portée de fonction et le « hoisting ».


**Ma réponse (avec mes mots, 3 à 5 lignes) :**

..
### Pourquoi `var` est-il déconseillé dans le code moderne ? Qu'est-ce que la portée de fonction et le hoisting ?

**1. Pourquoi éviter `var` ?**

`var` possède une portée de fonction plutôt qu'une portée de bloc. Cela peut rendre les variables accessibles dans des endroits inattendus et provoquer des erreurs difficiles à détecter. On préfère généralement `const` et `let`.

**2. La portée de fonction**

Une variable déclarée avec `var` dans une fonction est accessible dans toute cette fonction. En revanche, `let` et `const` sont limités au bloc `{}` dans lequel ils sont déclarés.

**3. Le hoisting**

Le hoisting est le mécanisme par lequel JavaScript traite les déclarations avant l'exécution du code.

- `var` est initialisé à `undefined` avant l'exécution.
- `let` et `const` ne peuvent pas être utilisés avant leur déclaration : ils se trouvent dans une zone temporaire appelée *Temporal Dead Zone*.

**Conclusion :** privilégier `const` par défaut, puis `let` si une réaffectation est nécessaire.






.

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M6 — Le détective du return

**Question :** Le troisième bug vient de l'« insertion automatique de point-virgule » (ASI). Explique ce mécanisme en 3 lignes.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M7 — La tirelire numérique

**Question :** Cite tous les opérateurs d'affectation composée (+=, -=…) et donne un exemple pour chacun.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## M8 — La batterie qui se décharge

**Question :** Quelle est la différence entre while et do...while ? Que donnerait l'étape 4 avec un do...while ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A1 — Kadea Express v2 : le calculateur de livraison

**Question :** Pourquoi 0.1 + 0.2 ne donne-t-il pas 0.3 en JavaScript ? Et pourquoi toFixed() est un piège si on veut continuer à calculer ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A2 — Le moteur de paie v2

**Question :** La méthode .reduce() n'a pas été vue en atelier. Explique ce qu'elle fait et réécris l'étape 2 avec elle.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A3 — L'inventaire en console

**Question :** Comment afficher seulement les colonnes nom et stock avec console.table() ? Et que renvoient .find() et .filter() quand rien ne correspond ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A4 — Le classement de la promo

**Question :** Comment classer le bulletin de la meilleure à la moins bonne moyenne avec .sort() ? Pourquoi .sort() modifie-t-il le tableau d'origine, et comment l'éviter ?

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non

## A5 — Le nombre mystère

**Question :** Explique la « recherche dichotomique » et pourquoi 7 essais suffisent toujours pour trouver un nombre entre 1 et 100.

**Ma réponse (avec mes mots, 3 à 5 lignes) :**

...

**Mon test dans la console :**

```js
// colle ici le test que tu as exécuté et le résultat obtenu
```

**Source :** 

**IA utilisée ? (prompt + vérification sur MDN) :** non
