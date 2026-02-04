# Exercices sur les fonctions et tableaux

## 1. indexedExponentials

Écrire une fonction `indexedExponentials` qui prend un tableau de nombres en paramètre et retourne un nouveau tableau où chaque nombre est élevé à la puissance de son index.



```javascript
Exemple :
function indexedExponentials(nombres) {

}
indexedExponentials([2, 5, 7, 4]) // => [2^0, 5^1, 7^2, 4^3] => [1, 5, 49, 64]

```

## 2. evenIndexedOddNumbers

Écrire une fonction `evenIndexedOddNumbers` qui prend un tableau de nombres en paramètre et retourne un tableau contenant uniquement les nombres impairs qui se trouvent à un index pair.


```javascript
function evenIndexedOddNumbers(nombres) {

}

evenIndexedOddNumbers([1, 3, 3, 4, 7, 10]) // => [1, 3, 7]

```

## 3. evenIndexedEvenLengths

Écrire une fonction `evenIndexedEvenLengths` qui prend un tableau de chaînes de caractères en paramètre et retourne uniquement les chaînes qui se trouvent à un index pair et qui ont une longueur paire.



```javascript
function evenIndexedEvenLengths(chaines) {

}


evenIndexedEvenLengths(['lion', 'monkey', 'aardvaark', 'cat', 'doge'])// => ['lion', 'doge']
evenIndexedEvenLengths(['red', 'green', 'purple', 'blue', 'yellow']) // => ['purple', 'yellow']
```

---

## 4. unique

Écrire une fonction `unique` qui prend un tableau en paramètre et retourne un nouveau tableau contenant uniquement les éléments uniques (sans doublons).



```javascript
function unique(tableau) {

}
unique([1, 2, 3, 3, 4, 4, 5]) // => [1, 2, 3, 4, 5]
```


## 5. findDuplicates

Écrire une fonction `findDuplicates` qui prend un tableau en paramètre et retourne un tableau contenant toutes les valeurs qui apparaissent plus d’une fois.


```javascript
function findDuplicates(tableau) {

}
findDuplicates([1, 2, 3, 2, 4, 3]) // => [2, 3]
```

## 6. palindrome

Écrire une fonction `palindrome` qui prend une chaîne de caractères en paramètre et retourne `true` si la chaîne est un palindrome (elle se lit de la même façon à l’envers et à l’endroit), sinon `false`.



```javascript
function palindrome(chaine) {

}
palindrome('racecar') // => true
palindrome('hello') // => false
```

## 7. chunk

Écrire une fonction `chunk` qui prend un tableau et une taille de bloc en paramètres, et retourne un tableau de sous-tableaux, chacun ayant la taille indiquée (sauf le dernier qui peut être plus court).


```javascript
function chunk(tableau, taille) {

}
chunk([1, 2, 3, 4, 5], 2) // => [[1, 2], [3, 4], [5]]

chunk([1, 2, 3, 4, 5], 3) // => [[1, 2, 3], [4, 5]]
```

## 8. flattenArray

Écrire une fonction `flattenArray` qui prend un tableau de tableaux en paramètre et retourne un tableau aplati.


```javascript
function flattenArray(tableaux) {

}
flattenArray([[1, 2, 3], [4, 5], [6]]) // => [1, 2, 3, 4, 5, 6]
```

---

## 9. rotateArray

Écrire une fonction `rotateArray` qui prend un tableau et un nombre de rotations en paramètres et qui fait tourner les éléments du tableau vers la droite. La rotation doit se faire **sur place** (sans créer un nouveau tableau).


```javascript
function rotateArray(tableau, rotations) {

}
rotateArray([1, 2, 3, 4, 5], 2) // => [4, 5, 1, 2, 3]

```
