# Piscine_js_ATronel

========== EX00=========

/* Ecrivez une fonction qui prend deux paramètres et qui retourne la somme des deux paramètres. Votre fonction devra se nommer add */

function add(a,b){

}

// Ne touchez pas les lignes en dessous.
module.exports = {
  add
}

========== EX01 ============

/* Ecrivez une fonction qui prend deux paramètres et qui retourne la somme des deux paramètres. Votre fonction devra se nommer add */

function add(nb1,nb2){
return nb1 + nb2;
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  add
}

=========== EX02 ===========

/* Ecrivez une fonction multiply qui prend deux paramètres et retourne la multiplication des deux paramètres */


function multiply (nb1, nb2) {
 return nb1 * nb2;
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  multiply
}

============ EX03 =============

/* Ecrivez une fonction divide qui prend en paramètre deux arguments et qui retourne la division du premier par le second, attention la division par zéro est interdite et doit retourner la chaîne de caractère Forbidden */

function divide (nb1, nb2){
if (nb2 == 0) {
  return("Forbidden")
} else {
  return nb1/nb2;
  }
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  divide
}

======== EX04 =============

/* Ecrivez une fonction modulo qui prend deux paramètres en arguments et qui retourne le premier paramètre modulo le deuxième paramètre */

function modulo (nb1, nb2){
  return nb1%nb2
  }

// Ne touchez pas les lignes en dessous.
module.exports = {
  modulo
}

======= EX05 =============

/* Ecrivez un programme qui affiche uniquement les nombres de 0 à 10 à l'aide d'une variable i */

//Testez votre programme sur index.js

for(let i = 0; i <= 10; i++){
  console.log(i);
}

console.log("fin du programme")

/* la console doit afficher  :
0
1
2
3
4
5
6
7
8
9
10
*/

======== EXO5 ========

/* Ecrivez un programme qui affiche uniquement les nombres de 0 à 10 à l'aide d'une variable i */

//Testez votre programme sur index.js

for(let i = 0; i <= 10; i++){
  console.log(i);
}

console.log("fin du programme")

/* la console doit afficher  :
0
1
2
3
4
5
6
7
8
9
10
*/

========= EX06 ==========

/* Créez un programme qui affiche uniquement les nombres pairs de 2 à 100, à l'aide d'une variable */

// Testez votre programme sur index.js

for(let i = 2; i<=100; i = i+2) {
  console.log(i);
}
console.log("fin du programme")





/* la console doit afficher  :

2
4
6
8
10
...
98
100
*/
